# Electricity Billing System

The Electricity Billing System is a software solution designed to manage electricity billing operations. It includes modules for:

- **Customer Management**: Add, update, and delete customer records.
- **Bill Management**: Generate and manage electricity bills.
- **User Roles**: Role-based access for administrators and clerks.

## Features

- **Customer Management**:
  - CRUD operations on customer records.
- **Bill Management**:
  - Generate, view, and manage bills.
-
## Technologies Used

- **Backend**: Java (Spring Boot framework)
- **Frontend**: HTML, CSS (Thymeleaf templates)
- **Database**: MySQL
- **Version Control**: Git and GitHub

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/i-Prajwalsapat/Electricity_Billing_System.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Electricity_Billing_System
   ```

3. Configure the database:
   - Update the `application.properties` file with your database credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/electricity_billing
     spring.datasource.username=root
     spring.datasource.password=your-password
     spring.jpa.hibernate.ddl-auto=update
     ```

4. Build the project:
   ```bash
   mvn clean install
   ```

5. Run the application:
   ```bash
   mvn spring-boot:run
   ```

6. Access the application at [http://localhost:8080](http://localhost:8080).

## Usage Instructions

1. Log in using the admin account.
2. Navigate to the desired module (e.g., Customers, Bills).
3. Perform CRUD operations based on user roles and permissions.

## Contact

For any queries or support, please feel free to reach out:

- **Name**: Prajwal Sapat
- **Email**: prajwalsapat19@gmail.com

