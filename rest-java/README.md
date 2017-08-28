#JAVA REST Application
====================

Technology used:

 * Jersey + JAX-RS
 * Spring Integration
 * Spring Data + Hibernate
 * Groovy Integration tests
 * OAuth
 * Velocity + Java Mail
 * Facebook Login
 * Password Reset
 * Login/Sign Up + Email Verification
 * JSR 303 Validation

##Run the application
Open up git bash and locate to the following directory: C:\Users\Administrator\git\rest-java
Once there, there is two things that can be done. It is advised to do this for testing.

1) Run the following command for testing purposes: ./gradlew clean build integrationTest

2) To run the application on a web-browser run the following command: ./gradlew tomcatRun

The 1st command is not always needed, as for the 2nd command, it is always needed when you would like to run the application.

To access the application, go to either Google Chrome or Internet Explorer and on the searchbar type in the following URL link: http://localhost:8080/java-rest/






