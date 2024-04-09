# spring-boot3-jwt-security-main

Spring Boot Security:-
=====================
1) Spring Boot 3.0 Security | Authentication and Authorization | [New Changes] | javaTechie  --> Basic Authentication
	https://www.youtube.com/watch?v=R76S0tfv36w&t=1224s

  --> Install MySQL Database into local system
  --> Create mysql database as "javatechie", user/pass- root / Password
  		CREATE DATABASE "javatechie";
  --> Install dbeaver and connect with DB "javatechie"

	select * from userinfo;

Service Endpoint:-
	http://localhost:8080/products/welcome
	http://localhost:8080/users/createuser
	http://localhost:8080/products/all
	http://localhost:8080/products/10

	Create User Request Body:-
	--------------------------
	{
	    "name":"Pabitra",
	    "password":"Pwd3",
	    "email":"pabitramail03@gmail.com",
	    "roles":"ROLE_ADMIN"
	}

	{
	    "name":"Ajay",
	    "password":"Pwd1",
	    "email":"ajay@gmail.com",
	    "roles":"ROLE_USER"
	}

	{
	    "name":"Ravi",
	    "password":"Pwd2",
	    "email":"ravi@gmail.com",
	    "roles":"ROLE_USER"
	}

Authorization :- What all users can access as per thir role.
Authentication :- Authentication is nothing, Whatever user and password you have given is correct or not. So the user is Authenticate to access application or not.

2) Spring Boot 3.0 + Spring Security 6 | JWT Authentication & Authorization | JavaTechie   --> JWT Authentication (Bearer Token)
	https://www.youtube.com/watch?v=NcLtLZqGu2M