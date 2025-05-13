 🛒 Shopping Mall Backend Application :

This project is a **Spring Boot**-based backend application designed to manage the operations of a shopping mall system. It utilizes **MySQL** as the database and provides **RESTful APIs** to perform standard **CRUD (Create, Read, Update, Delete)** operations. The application is built with a layered architecture using **Java 8**, **Spring 5**, and **Spring Boot**, and employs **JDBC** for seamless interaction with the database.

 🚀 Features :

 - RESTful API endpoints for managing shopping mall data
 - Full CRUD functionality for entities like products, users, orders, etc.
 - Backend database implementation using **MySQL**
 - Database interaction using **Java JDBC**
 - Version control using **Git**

 🛠️ Technologies Used :

 - Java 8
 - Spring 5.0
 - Spring Boot
 - JDBC
 - MySQL
 - Git

 📁 Project Structure :
 
 ├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com.example.shoppingmall/
│ │ │ ├── controller/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── ShoppingMallApplication.java
│ │ └── resources/
│ │ ├── application.properties
│ │ └── data.sql
├── pom.xml
└── README.md

📬 API Endpoints

Method	Endpoint	Description :

GET	= Get all products
POST	=	Add a new product
PUT	=	Update an existing item
DELETE	= Delete an item

🙌 Acknowledgements

This project was developed to strengthen backend skills and gain hands-on experience with Spring Boot and MySQL integration.

⚙️ Getting Started

🤖 Prerequisites

 - Java 8 or higher installed
 - Maven installed
 - MySQL installed and running

 🔧 Setup Steps

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/shopping-mall-backend.git
   cd shopping-mall-backend

2. Configure the database

   a) Create a database in MySQL:

      CREATE DATABASE shoppingmall;

   b) Update application.properties with your MySQL credentials:

      spring.datasource.url=jdbc:mysql://localhost:3306/shoppingmall
      spring.datasource.username=your_username
      spring.datasource.password=your_password

3. Build and run the application

      mvn clean install
      mvn spring-boot:run



