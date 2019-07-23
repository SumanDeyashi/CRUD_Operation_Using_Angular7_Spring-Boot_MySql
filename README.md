# CRUD_Operation_Using_Angular_Spring-Boot_MySQL
# Description:

Company(Hashworks IT Services Private Limited)_Internship_Project.

Download all files and put it in one folder. After that, Build and Run Spring Boot project with command lines: mvn clean install and mvn spring-boot:run and run the "Angular Client" with command: ng serve. Finally, open it on your favorite browser using http://localhost:4200 url.

Technology Used: HTML/HTML5, CSS/CSS3, Angular 4, Java, Spring-Boot, Maven, MySql.

Duration: Oct, 2018 to Nov, 2018.

# Procedure:

Here, Angular is  Http Client & Spring Boot Server which uses Spring JPA to do CRUD with MySQL and Angular as a front-end technology to make request and receive response.

Here, Customer class corresponds to entity and table customer. CustomerRepository is an interface extends CrudRepository, will be autowired in CustomerController for implementing repository methods and custom finder methods. CustomerController is a REST Controller which has request mapping methods for RESTful requests such as: getAllCustomers, postCustomer, deleteCustomer, deleteAllCustomers, findByAge, updateCustomer.

Now, 4 components: customers-list, customer-details, create-customer, search-customer. 3 modules: FormsModule, HttpClientModule, AppRoutingModule. customer.ts: class Customer (id, firstName, lastName) customer.service.ts: Service for Http Client methods.

Configuration for Spring Datasource and Spring JPA properties in application.properties Dependencies for Spring Boot and MySQL in pom.xml.

