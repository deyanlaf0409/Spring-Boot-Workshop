## Requirements
<a href="https://www.java.com/" title="Java"><img src="https://github.com/get-icon/geticon/raw/master/icons/java.svg" alt="Java" width="21px" height="21px"></a>
### Backend technologies:
- Java 17 or higher required
- Spring Boot
- MySQL Database
- Hibernate

### Frontend technologies:
- Javascript
- CSS
- HTML
- ReactJS

### Backend
- Create a new Spring Boot application with Spring Data and connector for MySql database
- Add Rest Controller class for catching HTTP requests, locating it in a package .controller
- Add Entity Model class Student (locating it in a package .model)
- Student entity will be used for creating a new MySQL table, called Student in the Database
- Add Student Repository class (locating it in a package .repository) which will be used from Spring Data to translate Java classes to SQL tables
- Add Student Service interface and Student Service class to implement it (locating it in a package .service).
- Create a new database schema in MySql called 'studentsystem'

### Frontend
- Create a new `ReactJS` application
- Add a well-looking registration form
- Call the POST API from the backend for creating a new student
