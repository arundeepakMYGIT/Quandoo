Cucumber Test for https://the-internet.herokuapp.com/

Technology Stack used:
1. Language: Java
2. Automation Framework: Selenium Webdriver (version: 3.0.0-beta3) with Cucumber
3. Test run with: Junit framework version: 3.8.1
4. Build Management Tool: Maven
5. JAVA 1.7
6. IDE: Eclipse Luna 4.4.0
7. POM.XML favoring the dependencies for Junit: 3.8.1, Cucumber-Junit: 1.2.5, Cucumber-Java: 1.2.5, Selenium-Java: 3.0.0-beta

Pre-requisites: 
Have an IDE supporting JAVA 1.7 and Cucumber for Java

Workaround:
*Project Name: Quandoo

*Packages: 
1 com.quandoo.Java: 
[Classes]
- QuandooJavaTask (It contains all the steps used with cucumber annotations)

2 com.quandoo.Test: (It contains the below 5 Testrunner methods)
[Classes]
- Scenario1Test: Describes the test runner class for the respective tags from the feature file: Scenario1.feature
- Scenario2Test: Describes the test runner class for the respective tags from the feature file: Scenario2.feature
- Scenario3Test: Describes the test runner class for the respective tags from the feature file: Scenario3.feature
- Scenario4Test: Describes the test runner class for the respective tags from the feature file: Scenario4.feature
- Scenario5Test: Describes the test runner class for the respective tags from the feature file: Scenario5.feature

*Feature files (Scenario1.feature - Scenario2.feature) are described with the respective scenario, tag and the annotations that are used in QuandooJavaTask class.

*Report:
HTML Report is saved in the folder target\Report after running each test runner class

(i)Please note:
Selenium version 3.0.0-beta version has currently problem with Mouse Hover functionality. Please refer to the documentation "https://github.com/SeleniumHQ/selenium/issues/2285". But I have implemented the correct code.


*How to Run:
Run the specific class from Scenario1Test/Scenario2Test/Scenario3Test/Scenario4Test/Scenario5Test, as specific to the asked scenari