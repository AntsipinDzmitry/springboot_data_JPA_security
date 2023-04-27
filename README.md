# Spring Boot Data JPA Security

<p align="center">
      <img src="https://github.com/AntsipinDzmitry/springboot_data_JPA_security/blob/master/.idea/SpringJPA.png" alt="Project Logo" width="726">
</p>

## Spring Boot Rest


Spring Boot RESTFull CRUD application with JPA & MySQL

## The main goals of the project:

* The practice of using the standard spring boot functionality
* Comparison of the native JPA functionality and the Hybernate functionality as the default JPA implementation in Spring Boot
* An attempt to accept and understand the "spring magic", greatly reducing the amount of code and simplifying the configuration of the application

## Frameworks and tools

* `IDE`: IntelliJ IDEA 2022.3.2 with JDK17
* `Backend`: Spring-boot-starters: data-jpa, web
* `Database` mySQL
* `Web Server` Apache TomCat
* `Build tool` Maven
* `Others` Postman, spring-security

## Project structure looks like this:

<p align="center">
      <img src="https://github.com/AntsipinDzmitry/springboot_data_JPA_security/blob/master/.idea/projectStructure.png" alt="Project Logo" width="726">
</p>

## About

*  The application uses the JPArepository interface to facilitate the possible scaling of the application and increase the number of entities in it
*  Although hibernate is the default implementation of the JPA in the spring boot, I followed "the best practice" standards and used the functionality of the JPA
*  Easy and quick addition of the methods we need to the repository to expand the functionality
