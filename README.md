
<h1> 💯	Madison-Island Aautomation Project</h1>
This is my first automation project with Java and Selenium using eclipse, for shopping demo site: https://madison-island.com/ <br>
<!--Further details can be found on the following website: __  -->

<h2> 🔍 Overview </h2>
I implemented the Page Object Model (POM) design pattern by organizing the project into 'Page' and 'Test' classes, where each web page is represented by its own corresponding class. <br>
Additionally, I designed the methods to be reusable and flexible, ensuring they can easily accommodate new features as the application evolves. <br>
<br>
<p align="center">
<img src="images/website-general.jpeg" alt="A beautiful scenery"  width="780" border="20" >
</p>
<h2>💻 Technologies </h2>
<p>☕<b>Java:</b> A versatile, object-oriented programming language known for portability and a vast ecosystem, ideal for web, mobile, and enterprise applications.<br></p>
<p>💽<b>Selenium:</b> An open-source tool for automating web browsers, supporting multiple languages to test web applications.<br></p>
<p>🧰<b>TestNG:</b> A Java testing framework offering features like parallel execution and data-driven testing for large-scale test automation.<br></p>
<p>📊<b>Allure:</b> A test reporting framework that integrates with tools like TestNG to generate detailed, dynamic HTML reports.<br></p>
<p>🛠️<b>Maven:</b> A build automation tool for managing Java project dependencies, structure, and the build lifecycle.<br></p>
<p>🌳<b>Git:</b> A distributed version control system for tracking code changes and enabling collaboration among developers.<br></p>
<p>🤖<b>Jenkins:</b> An open-source automation server for continuous integration and delivery (CI/CD), supporting various tool integrations.<br></p>
<br>


<!--<h2>📊 Reports </h2>
 -->

<!-- <h2>📖 User Guide </h2>
Please review this file: https://docs.google.com/document/d/1krdPGVB7Q1rza0lzCrx5gbg1yLOrP-CuVnI-RYg-5f0/edit?usp=sharing
ads the file to GitHub
 -->
 

<h2>📂 Project Structure</h2> 

```
├───.settings
├───bin
│   ├───data
│   ├───pages
│   ├───tests
│   └───utils
├───src
│   ├───data
│   ├───pages
│   ├───tests
│   └───utils
└───test-output
    ├───Default suite
    ├───junitreports
    ├───old
        ├───Default suite
        └───Suite
    └───Suite

  ```

<h2>🌱 Page Object Model</h2> 

```mermaid
graph TD;
    Web_Application-->pages;
    Web_Application-->tests;
    pages-->Page1;
    pages-->Page2;
    pages-->Page3;
    tests-->Test1;
    tests-->Test2;
    tests-->Test3;
    Page1-->Automation_Infrastructure;
    Page2-->Automation_Infrastructure;
    Page3-->Automation_Infrastructure;
    Test1-->Automation_Infrastructure;
    Test2-->Automation_Infrastructure;
    Test3-->Automation_Infrastructure;
``` 

 
<h2> Contact</h2>
Thanks for taking the time to explore my GitHub!<br>
For any questions or feedback, feel free to contact me at: <br>
📧 danielleamano01@gmail.com <br>
📲 0502110677<br>
<br>
<img src="images/Picture.JPG" alt="A beautiful scenery"  width="200"  >

[Back to top](#top)
