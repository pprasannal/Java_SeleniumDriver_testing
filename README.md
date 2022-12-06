# Java_Selenium_webDriver_testing

Sample Application: 
KimSchiller (https://www.kimschiller.com/page-object-pattern-tutorial/)

Test models:
1) No Page Object Model(POM)
2) Repository object model
3) with Page object and no Page Factory(PF)

1. Page Object: it is a class that represents a web page and hold the functionality and members.
2. Page Factory: it is a way to initialize the web elements you want to interact with within the page object when you create an instance of it.
3. Repository Object: An object repository is a centralized storage of locators in the form of objects. QAs store all the element locators in a separate file, also referred to as a property file (.properties) in Selenium. The property file stores information in a key-value pair format. This file serves as an object repository in Selenium WebDriver

Test Type: Unit Testing,  
Java Selenium framework: Junit5
