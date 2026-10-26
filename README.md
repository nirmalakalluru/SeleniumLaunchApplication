Selenium Automation – Launch Application
📌 Project Overview
This project contains a basic Selenium WebDriver automation test written in Java. The test launches the Chrome browser, navigates to the Cloudberry Store website, validates the page title, and closes the browser.

🎯 Test Case: TC01_LaunchApplication
Objective: Verify that the Cloudberry Store application launches successfully and displays the expected page title.

Test Steps
Launch the Google Chrome browser.
Navigate to https://cloudberrystore.services/.
Maximize the browser window.
Retrieve the page title and validate that it matches the expected title: Your store of fun.
Print the test result to the console.
Close the browser.
🛠️ Technologies Used
Programming Language: Java
Automation Tool: Selenium WebDriver
Browser: Google Chrome
WebDriver: ChromeDriver
IDE: Eclipse or any Java-compatible IDE
📋 Prerequisites
Before running the test, ensure that you have installed:

Java Development Kit (JDK)
Eclipse IDE or another Java IDE
Google Chrome browser
Selenium WebDriver Java libraries
A compatible ChromeDriver setup or Selenium Manager configuration
📂 Project Structure

text
SeleniumAutomation/
├── src/
│   └── day5/
│       └── TC01_LaunchApplication.java
└── README.md
▶️ How to Run the Test
Clone or download the project to your local machine.
Import the project into your Java IDE.
Configure the Selenium WebDriver dependencies.
Ensure Chrome is installed and accessible.
Open TC01_LaunchApplication.java.
Run the class as a Java application.
✅ Expected Results
If the test passes:


text
Test Passed
The test passes when the actual page title matches Your store of fun.

If the test fails:


text
Test Failed
The test fails when the actual page title does not match the expected title.

💻 Code Summary
The test uses the following Selenium WebDriver methods:


Method	Purpose
new ChromeDriver()	Launches Chrome
driver.get()	Opens the application URL
driver.manage().window().maximize()	Maximizes the browser window
driver.getTitle()	Retrieves the current page title
driver.quit()	Closes the browser and ends the WebDriver session
🔍 Test Validation
Application URL: https://cloudberrystore.services/
Expected Page Title: Your store of fun
Validation Method: String comparison using equals()
Test Output: Test Passed or Test Failed
🚀 Future Improvements
Replace console output with TestNG or JUnit assertions.
Add exception handling and reporting.
Integrate screenshots for failed test cases.
Execute the test through a test automation framework.
Integrate the project with a CI/CD pipeline.
👨‍💻 Author
Created as part of Selenium WebDriver automation practice.
