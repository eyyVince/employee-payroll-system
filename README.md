The system manages employee records and automates payroll processing. Users can add and manage employees, calculate salaries and deductions, and store all data in a database for easy retrieval and reporting.

Employee and Payroll System (Frontend- HTML, CSS, Javascript, SCSS | Backend- PHP, Apache, XAMPP, MySQL)
![image alt](https://github.com/eyyVince/employee-payroll-system/blob/151218b9cf88cad13a283188f0e131aee9f09411/Employee%26PayrollManagementSystem1.jpg)

![image alt](https://github.com/eyyVince/employee-payroll-system/blob/151218b9cf88cad13a283188f0e131aee9f09411/Employee%26PayrollManagementSystem3.jpg)

Workflow Diagram

![image alt](https://github.com/eyyVince/employee-payroll-system/blob/151218b9cf88cad13a283188f0e131aee9f09411/Employee%26PayrollManagementSystem2.jpg)

1. Architecture

The system follows a layered web architecture:

Frontend (User Interface)
Login form, dashboard, employee management pages
Accepts user inputs (credentials, employee data, salary details)
Backend (PHP Application Logic)
Handles authentication (login success/failure)
Processes business logic (salary computation, deductions)
Controls system flow (routing between modules)
Database Layer (MySQL/PostgreSQL)
Stores users, employees, payroll records
Retrieves and updates data as requested by the backend

This separation ensures the system is modular, maintainable, and scalable.

2. Data Flow (Input → Process → Output)
Step 1: User Input
User opens the system and interacts with:
Login form (username/password)
Employee forms (add/edit employee)
Payroll inputs (salary, deductions)

Step 2: Authentication Process
Credentials are validated against the users table
If invalid → Login Failure
If valid → Login Success → Dashboard

Step 3: System Navigation
After login, the user can access:

Employee Management
Add Employee
Edit Employee
Delete Employee
Payroll Processing

Step 4: Payroll Processing Flow
Input salary details
System performs:
Deduction calculations
Net pay computation
Data is stored in the payroll table

Step 5: Data Storage & Retrieval
Employee and payroll data are:
Saved in the database
Retrieved when needed (e.g., dashboard, payroll records)

Step 6: Output
Display results:
Payroll records
Employee list
Dashboard summaries

To all visitors for this project, you can visit my work thru this website # eyyvince.42web.io (InfinityFree.com) and it still in development
