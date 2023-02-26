# Taxi-service
Simple web application

--------------------------------------
## Description
It is a small pet-project that allows to create Driver,
Car and Manufacture entities. Also, you have the opportunity
to see all list with drivers, cars, manufacturers,
add drivers to cars, do CRUD operations and receive the list of cars by driver login in each session.
Also, in this pet-project implemented driver authentication.

-------------------
## Structure
This project implements 3-tier architecture
+ Controller
+ Service
+ DAO

----------------
### Used technologies
+ Java 11
+ Maven
+ MySql 8.0.22
+ Apache TomCat 9.0.71
+ JSP
+ JSTL
+ HTML/CSS

--------------------
How to run this project
* If you don't have MySQL(version 8.0.22) and TomCat(version 9.0.71) - install it.
* Start IDE and MySQL on your computer
* Clone this repository to your IDE and open it
* Copy script from init_db.sql and run it
* Replace your data (URL, username, password, JDBC Driver) in ConnectionUtil
* Configure TomCat (version 9.0.71)
* Run the project# taxi-service
