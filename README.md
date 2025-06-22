# Student_info_sys

Student Information System Desktop Application JAVA using Eclipse IDE.

Student information system is an environment where all the process of the student in the institution is managed. It is done through the automated.

Write a program to build a simple Software for Student Information Management System which can perform the following operations: Store the First name of the student. Store the Last name of the student. Store the unique Roll number for every student. Store the CGPA of every student so on....

Screenshots

 ![sample2](https://github.com/user-attachments/assets/ecd40527-ffc9-463a-a86d-91a1ed2305d6)

 ![sample1](https://github.com/user-attachments/assets/3c1af65a-d4ff-4b4f-b907-a5d739a945ec)

Requirements

  Eclipse IDE
  
  Mysql 8 database
  
How to run the application

First import the project into Eclipse. Do not worry about errors right now.

Database Config

Mysql 8 database is required for the application.If you have mysql database already installed follow the below instruction:

Create a database named smsdb

import smsdb.sql into the smsdb database

Configure db.java class with your database connection parameters

Database configuration Instructions images:

![db](https://github.com/user-attachments/assets/d21ca34e-68e1-438d-9b09-c52e1e8e50ff)




If you do not have mysql database you can install it on your computer by yourself or you can use the below instruction to install it with docker:

Install docker and docker-compose for your OS

goto project root directory and run the command using command prompt or terminal: docker-compose up -d

You are all done.

If you used docker to install database then you can go to http://localhost:8181 from browser to see all databases.

Running the application

Select the project in eclipse and Run as Java Application

![run](https://github.com/user-attachments/assets/cfd6de7b-4707-4351-9c60-153f8a82bbcc)



If error occurred during running the application

Please add this /lib/mysql-connector-j-8.0.33.jar into file into Build Path if the application is not running. Add it like below:

![build-path](https://github.com/user-attachments/assets/662aaa3d-72bc-4a7b-a466-537113291e26)
