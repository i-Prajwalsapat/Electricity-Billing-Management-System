Electricity Billing System

The Electricity Billing System is a Java-based web application developed using Spring Boot. It is designed to manage electricity bills and customer information, providing features such as bill generation, customer management, and more.


Features
•	Customer Management: 
o	Add, edit, and view customer details.

•	Billing System: 
o	Generate and view electricity bills.
o	List and edit bills.

•	Security: 
o	Configured authentication and authorization using Spring Security.

•	Frontend: 
o	HTML templates for user interaction.

•	Database Integration: 
o	Persistent storage for customers and bills using Spring Data JPA.

Prerequisites

•	Java: JDK 17 or later
•	Maven: Build tool
•	MySQL: Database (or an alternative database supported by JPA)

Installation
1.	Clone the repository:
2.	git clone https://github.com/i-Prajwalsapat/Electricity_Billing_System.git
3.	cd Electricity_Billing_System/E-bill-System
4.	Configure the database:
o	Update the application.properties file with your database credentials: 
o	spring.datasource.url=jdbc:mysql://localhost:3306/electricity_billing
o	spring.datasource.username=your-username
o	spring.datasource.password=your-password
o	spring.jpa.hibernate.ddl-auto=update
5.	Build the project:
6.	mvn clean install
7.	Run the application:
8.	mvn spring-boot:run
9.	Access the application:
o	Open a web browser and navigate to http://localhost:8080/customers

Usage
•	Use the web interface to add customers, generate bills, and manage data.
•	Sample endpoints: 
o	/customers: View and manage customer data.
o	/bills: View and manage bills.


Technologies Used
•	Backend: 
o	Java, Spring Boot
o	Spring Data JPA, Spring Security
•	Frontend: 
o	HTML templates (Thymeleaf)
•	Database: 
o	MySQL

Contributing
1.	Fork the repository.
2.	Create a feature branch: 
3.	git checkout -b feature-name
4.	Commit your changes: 
5.	git commit -m "Add feature-name"
6.	Push to the branch: 
7.	git push origin feature-name
8.	Open a pull request.
   
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
•	Author: Prajwal Sapat
•	GitHub: i-Prajwalsapat
Feel free to report issues or suggest features!
