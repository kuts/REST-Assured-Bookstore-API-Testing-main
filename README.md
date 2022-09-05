# REST-Assured-Bookstore-API-Testing

A testing repository using **REST Assured** and **TestNG** to Automate Demo Bookstore API.


1. [Technology](#technology)
2. [Prerequisites](#prerequisites)
3. [How to run this project](#How-to-run-this-project)
4. [Reports View](#Reports-View)


### Technology:
- Tool: REST Assured
- IDE: IntelIJ
- Build tool: Gradle
- Language: Java
- Framework: TestNG

### Prerequisites
* Install jdk 8 or any LTS version
* Configure **JAVA_HOME** and **GRADLE_HOME**
* Download Allure latest version and configure system environment path
* Stable internet connection

### How to run this project
* Clone the repo in your local directory
* Open terminal to the project folder
* Run command `gradle clean test` to build the project
```
gradle clean test
```
6. Run command `allure generate allure-results --clean -o allure-report` to generate allure report.
```
allure generate allure-results --clean -o allure-report
```
7. Run command `allure serve allure-results` to generate html report and automatically open it in a web browser.
```
allure serve allure-results
```

### Reports View
These are the screenshots of **Allure** reports:
![Allure-Report1](https://user-images.githubusercontent.com/422126/188506876-ca8a949a-b468-47b1-b6b9-ec66c0d4c174.png)

![Allure-Report2](https://user-images.githubusercontent.com/422126/188506846-0f60f03d-70c9-431e-b205-50a8c7df4e90.png)


