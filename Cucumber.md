![Cucumber](https://github.com/BrijeshYadav05253/BrijeshYadav05253/assets/138758351/595d2841-7094-4ddb-a87a-daf9e6fda645)

# Table of Content



[Overview](#overview)

[Cucumber Framework](#cucumber-framework)

[Cucumber Framework Uses In Various fields](#cucumber-framework-uses-in-various-fields)

[Benefits of using Cucumber Testing Tools](#benefits-of-using-cucumber-testing-tools)

[How does Cucumber work?](#how-does-cucumber-work)

[Ghrekin Scenarios](#ghrekin-scenarios)

[These are the keywords used to write the case in the feature file](#these-are-the-keywords-used-to-write-the-case-in-the-feature-file)

[Benefits of BDD in Cucumber Framework](#benefits-of-bdd-in-cucumber-framework)

[The below image describes a simple BDD operation](#the-below-image-describes-a-simple-bdd-operation)

[Limitations of Behavior-driven development](#limitations-of-behavior-driven-development)

[Pre-requisites](#pre-requisites)

[Environment](#environment)

[Configuration](#configuration-needs-to-run-cucumber-framework)

[Installation Of VS Code](#installation-of-vs-code)

[Installation of node.js](#installation-of-nodejs)

[Example of scenario](#example-of-scenario)





# Overview

* Cucumber is a free and open-source tool that supports behavior-driven development (BDD) for software testing. It uses a language that is easy for everyone to understand, even if they don't know much about technology. With Cucumber, you can write tests that describe how the software should behave. This helps people like developers, testers, and others work together better.
*  The language Cucumber uses is called Gherkin, and it uses keywords like "Given," "When," "Then," "And," and "But" to explain each step in a test. Cucumber is good for different types of teams because it lets everyone be part of creating and maintaining tests.
*  The tests are written in a programming language like Ruby, and they can be connected to other testing tools. Cucumber helps make sure that the software does what it's supposed to do, and the tests can also be used as a type of living document to understand how the software works.

#  Cucumber Framework

**1-Feature file** 

Feature files contain code written in the Gherkin language, which is a simple form of the English language. Gherkin is designed to be easily understood by both technical and non-technical person.

**2-Step definition file** 

A step definition file is a simple file in which developers write the actual code.

# Cucumber Framework Uses In Various fields

Here are some common uses of the Cucumber framework in different domains:

1-Software Testing<br>
2-API Testing<br>
3-Continuous Integration/Delivery (CI/CD)

### Cucumber acts as a bridge between the following teams:

1 - Business Analysts and Software Engineers

2 - Manual and Automation Testers

3 - Manual Testers and Developers

# Benefits of using Cucumber Testing Tools

### Working Together Easily:

Cucumber helps different team members, like developers and testers, work together better. It uses simple language that everyone can understand.

### Tests Are Easy to Read:

Test scenarios written in Cucumber are easy to read because they use plain English. This helps everyone on the team understand what the tests are doing.

### Automation Made Possible:

Cucumber lets you automate tests. This means that once you write a test, a computer can run it many times to check if the software is working correctly.

### Team Collaboration:

Cucumber brings teams together by providing a language that everyone can use to express ideas. It breaks down barriers between different roles in the team.

### Reusing Test Steps:

With Cucumber, you can use the same steps in different tests. This helps reduce repetition and makes it easier to manage tests.


# How does Cucumber work?

The Cucumber BDD framework mainly consists of three major parts:

**1-Feature File**
<br>
A feature file is like a storybook for a computer program. It's a place where you write down what you want the program to do in a way that both people and computers can understand.
<br>
The special thing about a feature file is that it's written in a language called Gherkin, which is super simple and looks like plain English. This makes it easy for everyone on the team, even those who don't know much about programming, to understand what the program is supposed to do.

**2-Step Definitions** 
<br>
Each step in a feature file is associated with a step definition implemented in the code. Step definitions define the actions or operations that must be executed for each step of the test scenario. They map the plain text steps in the feature file to the corresponding code implementation.

**3-Test Runner File** 

The test runner file makes sure that the actions in the feature files happen the way they're supposed to by coordinating with the step definitions.

## BDD in Cucumber Automation
<br>
Using Cucumber for Automation in Behavior-Driven Development (BDD) means writing tests in a way that's easy for everyone to understand. You describe how you want the software to behave using simple language (Gherkin). Cucumber then turns these descriptions into actual tests that a computer can run. This helps teams work together, understand requirements, and create documentation that stays up-to-date.
<br>
<br>

# Ghrekin Scenarios


* Gherkin, the language for writing test scenarios, uses special keywords for structure. Lines typically start with keywords, allow comments, and recommend two-space indentation.

# These are the keywords used to write the case in the feature file

* **Feature Keyword:** The feature file starts with the keyword Feature. Under feature, you can mention the feature name which is to be tested.

* **Scenario Keyword:** There can be more than one scenario under one feature file, and each scenario starts with the keyword Scenario, followed by the scenario name.

* **Given Keyword:** Given keyword is normally used when we have to give some pre-condition in our test case.

* **When Keyword:** When the keyword is used to perform some action.

* **And Keyword:** There is no annotation for AND keyword. It is used to connect two statements and provides the logical AND condition between any two statements. 

* **And Keyword:** There is no annotation for AND keyword. It is used to connect two statements and provides the logical AND condition between any two statements. 

* **But Keyword:** But the keyword is used to represent negative assertions in addition to the previous statement.

* **Background Keyword:** If there is any repetitive step that is going to be used in every test case. We just add the repetitive step under Keyword Background. Step keep under Background would be run before every test case.

# Benefits of BDD in Cucumber Framework
<br>

* BDD with Cucumber is about describing how the software should behave, not just writing tests. It's like telling a story of what you want the software to do, making sure everyone understands and agrees on how it should work.
  
* The improvement in the quality of code results in reduced costs of maintenance and also minimizes the project’s associated risks.
  
# The below image describes a simple BDD operation

![image](https://github.com/BrijeshYadav05253/Document-Cucumber/assets/138758351/4e6e269a-48cd-4b68-b209-8698d3bda88a)




# Limitations of Behavior-driven development


* Testers must have prior experience in TDD (Test-driven Development) to work in BDD.

* BDD approach may be ineffective if the requirements are not correctly analyzed.
  
* Testers must have sufficient technical skills.

### Cucumber with Selenium
* Teams write test scenarios in Gherkin syntax using Cucumber, describing the behavior of a web application.
* These scenarios are then connected to automation code, often written in a programming language like Java or Ruby.
* Selenium is used in this code to simulate user interactions with the web application, such as clicking buttons, filling forms, and verifying results.
* When the automated tests run, Cucumber interprets the Gherkin scenarios, and Selenium performs the actions on the web application, checking if it behaves as expected.



  # Pre-requisites

  * Visual Studio code install
  * Node.js and npm (Node Package Manager) installed
  * Java needs to be installed version(SE-8) and Maven-version 3.3.1 or higher. 
 
 # Environment

PRETTY_NAME="Ubuntu 22.04.3 LTS"
<br>
NAME="Ubuntu"
<br>
VERSION_ID="22.04"
<br>
VERSION="22.04.3 LTS (Jammy Jellyfish)"
<br>
VERSION_CODENAME=jammy
<br>
ID=ubuntu
<br>
ID_LIKE=debian
<br>
HOME_URL="https://www.ubuntu.com/"
<br>
SUPPORT_URL="https://help.ubuntu.com/"
<br>
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
<br>
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
<br>
UBUNTU_CODENAME=jammy

# Configuration needs to run Cucumber Framework

* A minimum of 4 to 8 gigabytes of RAM is required.
* A minimum of 20 to 30 gigabytes of free storage is required.
* A minimum multicore processor is required to run the Cucumber Framework.

### My system configuration

* Model name: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz
* RAM size is 8 GB
* Storage 256 GB



# Installation of VS Code

* There are many methods of installing vs code in Ubuntu Linux one is given below

*  Using .deb package

### Download the .deb package:

   * Visit the VS Code download page and download the .deb package for Debian/Ubuntu.

   ### Install the package:

   * Open the folder where the package is downloaded. Then open the terminal inside the folder and run the below command.
     <br>
```
   $ sudo apt install ./(FileName).deb
```
* After completion of installation open the VS Code by the command given below.

```
$ code .
```

# Installation of node.js

* installing Node.js by using the command
  ```
  $ sudo snap install node --classic
  ```

<br>

 # Install Cucumber Language Support:

 ### 1. Open Visual Studio Code.


* Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of
the window.

* Search for & Cucumber (Gherkin) Full Support or a similar extension for Cucumber support.
  
* Install the extension.

### 2. Create a New Feature File:
* In your Visual Studio Code workspace, create a new feature file with the .feature
extension (e.g., my.feature). You can do this by right-clicking on your project directory
and selecting New File.

### 3. Write Gherkin Scenarios:
* Inside your feature file, write your Gherkin scenarios. For example:

Feature: My Feature

Scenario: My Scenario<br>
Given I have some precondition<br>
When I perform some action<br>
Then I should see some results<br>

### 4. Install Cucumber Step Definition Generator

* Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of
the window.

* Search for Cucumber Step Definition Generator.
* Install the extension.

### 5. Change the settings in the step definitions generator
* Access the settings and search for Step Definition Generator.
Modify the desired setting value.<br>
Save the updated settings.

* "Step-definition-generator:Runner"<br>
The testing framework used for step definitions: cypress

* "Step-definition-generator:language"<br>
The programing language used for step definitions:typescript

* "step-definition-generator.arrow": true,

* "step-definition-generator.async": false

### 6.Generate a step definition using Cucumber Step Definitions Generator extension:
* The extension can automatically create a new file for the step definition when you generate it.
To do this, click an icon in the Editor Actions menu .<br>
The extension can also generate the step definition and copy it to the clipboard, which makes it
easy to access and paste into the appropriate file. To use this option, you can again right-click
on the feature file or click an icon in the Editor Actions menu.


* import { Given, When, Then, DataTable } from '@badeball/cypress-cucumber-preprocessor';<br><br>
Given(`I have some precondition`, () => {<br>
// [Given] Sets up the initial state of the system.<br>
});<br><br>
When(`I perform some action`, () => {<br>
// [When] Describes the action or event that triggers the scenario.<br>
});<br><br>
Then(`I should see some result`, () => {<br>
// [Then] Describes the expected outcome or result of the scenario.<br>
});

### Before Generating Step Definition Install the Package:

* Make sure you have installed the @badeball/cypress-cucumber-preprocessor package. Run the following command in your project directory:

```
npm install --save-dev @badeball/cypress-cucumber-preprocessor

```

### Type Declarations:

* If TypeScript is being used in your project, ensure that the required type declarations are installed. You can install the TypeScript types for this package by running:

```
npm install --save-dev @types/cypress-cucumber-preprocessor
```



# Example of scenario

* Adding two numbers
  
  Feature: Addition


    Scenario: Adding two number

    Given I have first numbers<br>
    And I have Second number<br>
    When I add the two number<br>
    Then I should see some result<br>

    ### The output should be 

    
  ```

  import { Given, When, Then, DataTable } from '@badeball/cypress-cucumber-preprocessor';
   const assert = require('assert');


   let firstNumber;
   let secondNumber;
   let result;

   Given('I have the first number as {int}', (a) => {
   console.log("Enter the first Number a") ;
   firstNumber = a;
   });

   Given('I have the second number as {int}', (b) => {
    console.log("Enter the second Number b" );
    secondNumber = b;
   });

  When('I add the numbers', () => {
  result = firstNumber + secondNumber;
  console.log("The Result" +result)
  });

  Then('the result should be {int}', (expectedResult) => {
  assert.strictEqual(result, expectedResult);
  });

    ```

  * To run the feature file run the below command
 
    ```
    path/to/your/feature/file.feature
    ```
     Replace this with the actual path to your feature file. This command will execute the tests defined in the specified feature file.
