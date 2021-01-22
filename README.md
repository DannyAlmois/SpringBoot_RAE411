Application for authorization Spring Boot, Spring Security, JPA, Thymeleaf and MySQL + Maven

Used application programm: Eclipse and MySQL 8.0

Code references: 
- https://betacode.net/11705/create-a-login-application-with-spring-boot-spring-security-jpa
- https://habr.com/ru/post/482552/ 
- https://github.com/Ex3mS1ze/spring-reg-auth 

Thanks @Ex3mS1ze 

Used only open-source references not for sale or personal using, only for study goals

MySQL 8.0 database: Test 

MySQL 8.0 Tables: 
APP_USER
APP_ROLE
USER_ROLE
PERSISTENT_LOGINS

SpringBoot configurations:
Name: SpringBootSecurityJPA
Group: com.example
Artifact: SpringBoot
Description: SpringBoot + Spring Security + JPA + Remember Me
Package: com.example.sbsecurity

/src/main/java/com/example/sbsecurity/config - configurations classes
WebSecurityConfig.java - configuration for application security

/src/main/java/com/example/sbsecurity/controller - controller classes
MainController.java - main controller for SpringBoot application

/src/main/java/com/example/sbsecurity/dao - Data Access Object classes for database access
AppRoleDAO.java - used for manipulation for APP_ROLE table
AppUserDAO.java - used for manipulation for APP_USER table

/src/main/java/com/example/sbsecurity/entity - models classes
AppRole.java - application for MySQL table APP_ROLE
AppUser.java - application for MySQL table APP_USER
UserRole.java - application for MySQL table USER_ROLE

/src/main/java/com/example/sbsecurity/service - service classes for models
UserDetailsServiceImpl.java - central interface for Spring Security and authorization

/src/main/java/com/example/sbsecurity/utils - utilities classes for application
EncrytedPasswordUtils.java - utilities for Remember Me password and MySQL tables
WebUtils.java - authorization utilities

/src/main/resources/application.properties - driver for JPA+MySQL bundle 

/src/main/resources/templates - static object .html for application *Thymeleaf template*
_menu.html - main menu for all pages 
403Page.html - error page/access denied
adminPage.html - page for admin *logged on admin*
loginPage.html - login Page
logoutSuccessfulPage.html - successful logout page 
userinfoPage.html - information about user page
welcomePage.html - welcome Page

pom.xml - all used SpringBoot configurations and packages

SpringBootSecurityJPAApplication.java - application for SpringBoot library start and attach

Thanks for attention! :)


