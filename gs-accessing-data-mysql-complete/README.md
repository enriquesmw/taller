# About this project
This project contains examples from [Introduction to Spring Data REST](http://www.baeldung.com/angularjs-crud-with-spring-data-rest):


# Running the project

The application uses [Spring Boot](http://projects.spring.io/spring-boot/), so it is easy to run. You can start it any of a few ways:

* Running in Spring STS (Current latest 3.9.3.RELEASE) 
* Run the `main` method from `SpringDataRestApplication`
* Use the Maven Spring Boot plugin: `mvn spring-boot:run`
* Package the application as a JAR and run it using `java -jar intro-spring-data-rest.jar`

# Viewing the running application
To view the running application, visit [http://localhost:8080](http://localhost:8080) in your browser

# Using UI

The UI is very poor, but is works, you can add users entering in the name and lastname field and then click in the add button, then with a few users added you can do the rest of the cruds operations (good luck ;) )

* http://localhost:4200/

# Using REST API

* http://localhost:8080/users
* http://localhost:8080/demo/add?name=First&email=someemail@someemailprovider.com

* http://localhost:4200/ 

# TODO:

* Using in memory db (h2): DONE
* Make a better ui (https://github.com/akveo/ngx-admin): WIP

###Relevant Articles:
* https://spring.io/guides/gs/accessing-data-mysql/ 
* http://www.baeldung.com/angularjs-crud-with-spring-data-rest
* http://www.baeldung.com/spring-data-rest-intro 
* https://dzone.com/articles/integrate-h2-database-in-your-spring-boot-applicat

- The source of this README.md: https://github.com/eugenp/tutorials/tree/master/spring-data-rest
- [Guide to Spring Data REST Validators](http://www.baeldung.com/spring-data-rest-validators)
- [Working with Relationships in Spring Data REST](http://www.baeldung.com/spring-data-rest-relationships)
- [AngularJS CRUD Application with Spring Data REST](http://www.baeldung.com/angularjs-crud-with-spring-data-rest)
- [List of In-Memory Databases](http://www.baeldung.com/java-in-memory-databases)
