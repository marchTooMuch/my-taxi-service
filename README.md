# Taxi-service 🚖

📃 Project description:

Web application for adding manufacturers, cars, drivers and showing them.
Also in app implemented registration and authentication with drivers login and password. The app wrote according to all SOLID principles and supported all CRUD operations.

🚀 Features

* Registration and Authentication drivers
* Add Driver, Car, Manufacturer
* Show all cars, drivers
* Add driver to car
* Deleted  Driver, Car
* Show all cars of current driver.

⚙ Project Structure

Layer | description            |
--- |------------------------|
Filter | Authentication level   |
Controllers | Handle http requests   |
Services | Process all logic      |
DAO | Get data from database |
JSP | Layout for pages       |

UML

![img.png](img.png)

💻 Technologies:

* JDK	11
* Maven	4.0.0
* MySQL	8.0.22
* TomCat	9.0.50
* Servlet 4.0.1

Start the program

1. Clone the project from GitHub
2. Create schema and tables with init_db.sql
3. Configure ConnectionUtil.java 
4. Configure Tomcat server 
    




