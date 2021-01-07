[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a419ef5a36d9449f9ebd00135777d2d5)](https://app.codacy.com/gh/MrEvgeny13/RESTful_Training?utm_source=github.com&utm_medium=referral&utm_content=MrEvgeny13/RESTful_Training&utm_campaign=Badge_Grade)

# RESTful_Training

RESTful API training project based on Spring Boot with CRUD operations.


**Startup instruction:**

For example, will be used the **Postman**.

1) Download and install Postman application;

2) Run "RestExampleApplication" in IDE;

3) Create New request in Postman, give it a name and assign it to the required category;

4) Setting the request parameters: type of request, URI;

5) Click "Body" -> "raw", setting the JSON format;

6) Enter a request (for example, POST):
example:

{
"name" : "Evgeny",
"email" : "mr.evgeny13@gmail.com",
"phone" : "+7 (999) 999-99-99"
}

7) Send the request and then check the status (should be: "201 Created");

8) All other types of requests are executed similarly. Also, GET can be executed if you enter a request in the browser: http://localhost:8080/clients
