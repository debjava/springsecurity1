springsecurity1
===============
Author : Debadatta Mishra
This project provides an insight into the web security using the features of Spring framework.
There are two types of actors, one is normal user and another is admin.

Use Case - 1 : A normal user logs into the application and tries to change the url to go the admin page. 
In this case it should get access denied error.

Use Case - 2 : An admin logs into the application and tries to change the url to go the admin.
In this case admin should be able to visit the admin page.

How to Do
=========
Deploy the application in any web container after building using maven.
Navigate to the url as http://localhost:8080/springsecurity1 and try to log into the application using the user as user1/1234.
Aftdr successful login, change url as http://localhost:8080/springsecurity1/admin and invoke the url.
The user will get the access denied exception where as it is not applicable for Admin.
