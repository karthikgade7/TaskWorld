# Task World

Pre-requisites:
- Eclipse IDE
- Maven
-TestNG
- JDK

Installation & Execution:
-Take the clone or download project Taskworld in .zip file
-Import the project into your Eclipse IDE.  

Install TestNG in Eclipse:
- Open Eclipse and goto Help-> Install New Software -> Click on Add.
- Add name as TestNG and location as http://beust.com/eclipse
- Select TestNG checkbox and install it and restart Eclipse IDE.

Update Maven Dependencies:
- Right click on pom.xml -> Maven -> Update Project

Run on Mac-Chrome:
Open Driver_Setup.java file and make sure Chrome driver looks similar to below
- System.setProperty("webdriver.chrome.driver", Constants.driverPath+ "chromedriver");

Run on Windows-Chrome:
-Open Driver_Setup.java file and make sure Chrome driver looks similar to below
- System.setProperty("webdriver.chrome.driver", Constants.driverPath+ "chromedriver.exe");

Execute Taskworld automation suite:
- Right click on testng.xml file and run as TestNG Suite
