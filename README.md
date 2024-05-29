## Requirements
<a href="https://www.java.com/" title="Java"><img src="https://github.com/get-icon/geticon/raw/master/icons/java.svg" alt="Java" width="30px" height="30px"></a>
<a href="https://spring.io/" title="Spring"><img src="https://github.com/get-icon/geticon/raw/master/icons/spring.svg" alt="Spring" width="30px" height="30px"></a>
<a href="https://dev.mysql.com/" title="MySQL"><img src="https://github.com/get-icon/geticon/raw/master/icons/mysql.svg" alt="MySQL" width="30px" height="30px"></a>
<a href="https://hibernate.org/" title="Hibernate"><img src="https://github.com/get-icon/geticon/blob/master/icons/hibernate.svg" alt="Hibernate" width="30px" height="30px"></a>
<a href="https://reactjs.org/" title="React"><img src="https://github.com/get-icon/geticon/raw/master/icons/react.svg" alt="React" width="30px" height="30px"></a>

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

 ### Run the spring boot application with the command: 
		mvn spring-boot:run
  ### Run the React application with the command: 
		npm start
- your frontend application is started on http://localhost:3000/
- your backend application is started on http://localhost:8080/
