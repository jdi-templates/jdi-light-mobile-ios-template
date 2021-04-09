This template contains jdi-light-mobile iOS tests

How to launch ios tests

1) Stable requirements:
Java 8, Maven 3.6.3, TestNG 6.14.3, Appium 1.18.3, Xcode (last version) <br>

2) Install Appium & Xcode for iOS simulator

3) Install test-app on your simulator

4) _mvn clean install_ - to install project dependencies

5) Run tests by Maven command: 
`mvn clean test site -Dsuite.xml.file=src/test/resources/iosApps.xml`

6) Get allure report in target/site package
