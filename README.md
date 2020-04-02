// This project contains CRUD operation for fetching, deleting, creating and updating employee from employee_table. (FileName - mysqlDatabase.xml)

// Functionalties used in this project
    
    - Flow Reference
    - Error Handling using raise error and Error handlers
    - Request Components for calling REST APIs
    


Employee CRUD Operations:

    1) Get All Employees
       API Endpoint: GET /api/employees
       Description: This API returns all the existing employees in database.

    2) Get an Employee with employee ID 
       API Endpoint: GET /api/employeeByID?id=3
       Description: This API returns all the existing employees in database.

    3) Create Employee
       API Endpoint: POST /api/employee
       Payload Structure: 
            {
                "Name": "John2 johnson",
                "Designation": "QA L1",
                "Email_ID": "john2@yopmail.com",
                "Registration_Date": "2020-03-27T19:04:45"
            }
      Description: This API adds/insert an employee in database

    4) Update Employee with employee ID
       API Endpoint: POST /api/employee/{ID}
       Description: This API updates employee details in database

    5) Delete Employee with employee ID
       API Endpoint: DELETE /api/deleteEmployee/{ID}
       Description: This API delete an employee from database.

