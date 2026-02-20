About the Project
This automation project is developed using Java and Selenium WebDriver in Eclipse IDE. The main goal of this project is to automate the complete workflow of the application from login to logout. The framework is designed in a simple and structured way so it is easy to understand and maintain.
In this project, Java is used as the programming language to write automation scripts. Selenium WebDriver is used to automate browser actions like clicking buttons, entering text, selecting dropdown values, and verifying page elements. The scripts are executed in the Chrome browser using ChromeDriver.
The project is managed using Webdriver on selenium4, which helps to handle required dependencies like Selenium libraries in an organized way. It also helps to build and run the project easily design pattern. In this design:
Each web page is created as a separate Java class.
All web elements (locators) and methods (actions) are written inside that page class.
The main test class calls methods from page classes.
This structure makes the code reusable and easy to update if any UI changes happen.
The execution flow starts with launching the browser and logging into the application. Then it creates a new generator, fills billing information, verifies latitude and longitude fields, assigns route and service details, updates the price book, and finally logs out. After each important step, validation is performed to ensure the application works correctly.
The automation code is stored in GitHub for version control and easy sharing.
Overall, this framework is simple, organized, and suitable for real-time automation testing projects.
