# QA Internship -Sign in form

## Name
Automate testing of the sign in form (Happy flow)

## Description
Desired outcome is that the test will succeed after filling in the authentication details in the login form, in an automated way.


## Requirements
* Google Chrome 106
* Java version 11
* Selenium framework + ChromeDriver
* Eclipse IDE


## Tools used during development
* ChroPath (selector tool)
* Eclipse IDE
* Chrome + Chrome developer tools


## Workflow
The browser driver(ChromeDriver) is used to interact with the Chrome browser. 
An driver object is created to interact with the methods of the class ChromeDriver(for loading the web page, finding elements).
The locators are used to identify the  HTML elements in the sign in form and for filling in the credentials 


## Improvement ideas
* Test Negative Flows, like wrong password, wrong Username
* Wire up the automation in a CI pipeline

## Author
 Adriana Vultur

