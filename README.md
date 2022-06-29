

## YemekSepeti Test Automation POC

Test scenarios developed with Selenium and Cucumber and stored under feature files. POM design pattern has been followed while developing project. Also Page Object Factory used for storing web elements.

* Java : JDK11

Frameworks that using in the project : 

* Selenium : 3.141.59
* Cucumber : 6.11.0
* Extend Reports : 5.0.4
* maven : 3.8.2

### Running Tests

Tests are running in parallel.

For selecting browser  : 

* Chrome (`mvn test "-Dbrowsername=Chrome"`)
* Firefox (`mvn test "-Dbrowsername=Firefox"`)

Note1 : In default, tests run in Chrome.(`mvn test`)
Note2 : WebDrivers in /webdriver directory should update according to chrome and firefox versions while running the scenarios