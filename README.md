# RESTful_Training

RESTful API training project based on Spring Boot with CRUD operations.


**Startup instruction:**

For example, will be used the **Postman**.

1) Run "RestExampleApplication" in IDE;

2) Create Collection in Postman and give it a name (optional);

3) Add a request to Collection, set the type (GET, POST, etc) and enter request URL: *localhost:8080/clients*;

4) Click "Body" -> "raw". Set the JSON format;

5) Enter the request body (for example, for POST):  
*example:*

{  
"name" : "Evgeny",  
"email" : "mr.evgeny13@gmail.com",  
"phone" : "+7 (999) 999-99-99"  
}

6) Click "Send" and then check the status (should be: "201 Created");

7) All other types of requests are executed similarly. Also, GET can be executed if you enter a request in the browser: http://localhost:8080/clients
