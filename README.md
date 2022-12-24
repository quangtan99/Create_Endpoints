# Create_Endpoints


# At terminal we type these ones as follow:

1. krok:create virtual environment:                                                  python -m venv my_env
2. krok: activate environment:                                                       my_env\Scripts\activate
3. krok: move to original file:                                                      cd ~ 
4. krok: create an initial migration for our snippet model,                          python manage.py makemigrations snippets
and sync the database for the first time:                                            python manage.py migrate snippets
5. krok: install django:                                                             pip install django
6. krok: install django rest framework:                                              pip install djangorestframework
7. krok: run server:                                                                 python manage.py runserver
8. krok: We can test our API using httpie,
In another terminal window, we can test the server.
You can install httpie using pip:                                                    pip install httpie


# On web browser we access these link to manipulate with data.
# and we can post our JSON data here by using "POST" endpoint.

9. runserver on web browser:                                                         http://127.0.0.1:8000/snippets/
10. use POST endpoint:                                                              
type this to part "content"!! and the click post: 
                                                                                    {
                                                                                       "the_json": <paste your JSON data here!!!!!>
                                                                                    }

11. use this link to access 1.detail endpoint "GET",
for example: we'd like to access "AttributeName":                                   http://127.0.0.1:8000/snippets/the_json/1/AttributeName/
12. use this link to access 2.detail endpoint "GET",
for example: we'd like to access "AttributeName" at id "1":                          http://127.0.0.1:8000/snippets/the_json/1/AttributeName/1/

                                                                    
