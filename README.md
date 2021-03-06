﻿**Spring-boot And Angular app**

   * Building a web App based on Spring-boot as back-end and Angular as a front end.
As we know that Angular is one of the most popular JavaScript frameworks with incredible tooling, speed and performance.
   * so our project should be doing the following:
 
  -  Store the customers’ accounts information in a database.
  -  Make deposits. 
  -  Make withdrawals.
  -  Search for an account (given the account number)
  -  Delete an account from the active accounts in the database.
  -  managing groups.
  -  Performing the communication between the Back/front end by REST FULL Protocol.
 
### Prerequisites
  Spring boot is a Maven project, to run the project start by add the dependencies.(See Pom.xml)
  ````
  $ spring-boot-starter-web
  $ spring-boot-starter-data-jpa
  $ mysql-connector-java
  $ spring-boot-devtools
  ````
  For the part of our Fron end, we already added the Libraries(Angluar, Bootstrap ..) in our resources as a static folder.
  
### The Data Model(Entity-relationship)  
   ![alt text](MLD.png)
   
### Services(All the services are a @RestController )
  * ClientRestService : for performing the Client' operations.
  * CompteRestService : the Account' Operations.
  * EmployeRestService: managing the Employees.
  * OperationRestService : managing and controlling the operations on the accounts(withdrawals, deposits,..).

### The Front-end side :
 Try the app after Running the server, by sending the following url.
 ````
 Localhost.../index.html
 ````
  ![alt text](App.png)
 
