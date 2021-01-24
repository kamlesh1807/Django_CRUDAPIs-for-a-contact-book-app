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

 1. To Register a new user - POST 

         http://127.0.0.1:8080/api/ky/accounts/register/
         
         
 2. To get the Token -  POST
 
         http://127.0.0.1:8080/api/ky/accounts/token/
         
         
 3. To Add Contact  - POST
              
         http://127.0.0.1:8080/api/ky/server/  Authorization Token : eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNjExNDI0ODUxLCJqdGkiOiJkODcyNTM
         
         
 4. To List Contact  - GET
   
         http://127.0.0.1:8080/api/ky/server/   Authorization Token :eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNjExNDI0ODUxLCJqdGkiOiJkODcyNTM 
         
         
 5.  To Update Contact  - PUT
  
         http://127.0.0.1:8080/api/ky/server/<ID>   Authorization Token : eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0bNjZXNzIiwiZXhwIjoxNjExNDI0ODUxLCJqdGkiOiJkODcyNTM
           
     Note : to update a contact -The  <ID> of the Contact which we want to update is passed while calling.
           
 6.  To Delete Contact  - DELETE
  
         http://127.0.0.1:8080/api/ky/server/<ID>   Authorization Token :eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjNDI0ODUxLCJqdGkiOiJkODcyNTM
           
      Note : to Delete a contact -The  <ID> of the Contact which we want to update is passed while calling.
     
     
## Test

  We can test the API using  POSTMAN  extension.
  Registration of a new user Add Contact Read Contact Update and Delete Contact  :
  
 ![Register A user](https://user-images.githubusercontent.com/61351274/105619324-7d0a0700-5e17-11eb-80b7-d2e22f0d2323.JPG)
 
 
  
  


      
      
