<h2>Overview</h2>
A simple Spring Boot REST application that allows you to perform all CRUD operations on a list of employees. Employees are in the database and information is transferred using JSON
<br>
<br>
The application allows you to get a list of all employees, a single employee by ID, add a new employee, modify an existing employee and delete an employee
<br>
<br>
When creating the REST API, we adhered to generally accepted standards:
<br>
<br>

| HTTP method  | URL | CRUD operation |
| ------------- | ------------- | ----------- |
| GET  | api/employees  | getting all employees |
| GET  | api/employees/{employeeId}  | getting single employee |
| POST  | api/employees  | adding an employee |
| PUT  | api/employees  | employee updating |
| DELETE  | api/employees/{employeeId}  | employee removal |

Settings for connection to the database are specified in the file application.properties (/src/main/resources/application.properties)
<h3>Configuration</h3>
The application is configured with Spring Initializr (start.spring.io) using starter packages "Spring Web", "Spring Data JPA" and "MySQL Driver"<br>
Server support is built in
