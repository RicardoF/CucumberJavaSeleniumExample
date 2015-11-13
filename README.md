# CucumberJavaSeleniumExample
UI Acceptance **automated testing** example, using **Cucumber** + **Java** + **Selenium**.

Marks and Spencer specialises in the selling of clothing, home products and luxury food products.
The following UI Acceptance test scenario is used to test [Marks & Spencer website] (http://www.marksandspencer.com/):
```
Feature: As a customer, I wish to view the contents of my bag prior to checkout

  Scenario: Add shirt to bag and view bag
    Given I have added a shirt to my bag
    When I view the contents of my bag
    Then I can see the contents of the bag include a shirt
```

## Requirements
*Java 7, JDK 1.7
Find it [here](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)
After installing it, make sure JAVA_HOME is added to PATH.
*Maven
It requires JD 1.7 or above.
Find it [here](https://maven.apache.org/download.cgi)
Make sure to update PATH variable, append Maven bin folder.

## Supported architectures
* Windows

## Supported browsers
* Chrome

## How to use
Using the command-line, navigate to the project's root directory and run:
```
mvn test
```

## References
* [Cucumber] (https://cucumber.io/)
* [Selenium] (http://www.seleniumhq.org/)
