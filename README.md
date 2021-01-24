# Django_CRUDAPIs-for-a-contact-book-app
A suite of CRUD APIs for a contact book app .

## Functionality
- Authentication of User
- Create Contact
- Read Contact
- Update Contact
- Delete Contact

## Requirements
- Python 3.6
- Django (2.2.13)
- Django REST Framework (3.9.4)
- Django Rest Auth

## Set Up Guide ..
* <Open the terminal/shell and insert>

           git clone https://github.com/kamlesh1807/Django_CRUDAPIs-for-a-contact-book-app.git

           pip install -r requirements.txt

           python3 manage.py makemigrations

           python3 manage.py migrate

           python3 manage.py runserver


## Structure
In a RESTful API, endpoints (URLs) define the structure of the API and how end users access data from our application using the HTTP methods - GET, POST, PUT, DELETE.

`     GET    READ        Get all Contact
      POST   CREATE      Create a new movie
      PUT    UPDATE      Update a movie
      DELETE DELETE      Delete a movie
