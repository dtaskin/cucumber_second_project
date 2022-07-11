# cucumber_second_project
In this project, I tested smartbear website functionalities using maven as project build tool, Java as the language, JUnit for its assertions. 
I also used BDD framework because I believe this project will perform best with cucumber. 
You can see maven reports about my smoke and regression suites on my target folder. 
I use a page object model design pattern and maintain a separate class for each webpage. Each page class stores the members, locators, and associated methods for each webpage. This helps with refactoring.
I have a base class for the common functions, hooks class, and a very useful utility class for the repetitive methods which helps us achieve better usability.
The runner class is used to run steps classes, run execute test suites, save reports, and more.
Screenshots are captured for failed scripts and are included in Html and emailable reports generated after suite execution.
