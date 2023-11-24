![Cucumber](https://github.com/BrijeshYadav05253/BrijeshYadav05253/assets/138758351/595d2841-7094-4ddb-a87a-daf9e6fda645)

# Overview

* Cucumber is an open-source software testing tool written in Ruby. Cucumber enables you to write test cases that anyone can easily understand regardless of their technical knowledge.
  
* Cucumber Framework executes automated acceptance tests written in the “Gherkin” language. Gherkin is a domain-specific language for behavior descriptions. Gherkin is business-readable.

#  Cucumber Framework

**1-Feature file** 

Contains code written in Gherkin (plain English text)

**2-Step definition file** 

Contains the actual code written by the developer

# Uses of Cucumber Framework in different fields


### Cucumber acts as a bridge between the following teams:

1 - Business Analysts and Software Engineers

2 - Manual and Automation Testers

3 - Manual Testers and Developers

# Benefits of using Cucumber Testing Tools

* Involving stakeholders becomes easier regardless of their programming knowledge.
  

* Testers can write Test scripts without having in-depth knowledge of programming
 * Plugins are faster as compared to Selenium
* Supports various programming languages
* Code can be reused
* Simple and quick setup
*Flexible with different software platforms like Selenium, Ruby on Rails, Watir, Spring framework, and so forth.


# How does Cucumber work?

Cucumber BDD framework mainly consists of three major parts:

**1-Feature File**
<br>
Cucumber tests are written in plain text files called feature files stored with the extension – “.feature”. A Feature File can be described to make the documentation more legible. These files describe the behavior and functionality of the software using a specific syntax called Gherkin. Gherkin is a structured language that uses keywords like Given, When, and Then to define the steps of a test scenario.


**2-Step Definitions** 
<br>
Each step in a feature file is associated with a step definition implemented in the code. Step definitions define the actions or operations that must be executed for each step of the test scenario. They map the plain text steps in the feature file to the corresponding code implementation.

**3-Test Runner File** 

In Cucumber, the test runner file executes the Cucumber feature files and coordinates the steps defined in those feature files with the corresponding step definitions.

### BDD in Cucumber Automation
<br>
Behaviour-driven Development (BDD) is a software development technique that has evolved from TDD (Test Driven Development), which is an approach or programming practice where the developers write new code only when the automated test case fails.

<br>

# Ghrekin Scenarios

* Gherkin uses a set of special keywords to give structure and meaning to executable specifications. Each keyword is translated to many spoken languages; in this reference we’ll use English.

* Most lines in a Gherkin document start with one of the keywords.

* Comments are only permitted at the start of a new line, anywhere in the feature file. They begin with zero or more spaces, followed by a hash sign (#) and some text.

* Block comments are currently not supported by Gherkin.

* Either spaces or tabs may be used for indentation. The recommended indentation level is two spaces. 

# These are the keyword used to write the case in feature file(Ghrekin Scenarios)

* **Feature Keyword:** The feature file starts with the keyword Feature. Under feature, you can mention the feature name which is to be tested.
 <br>

* **Scenario Keyword:** There can be more than one scenario under one feature file, and each scenario starts with the keyword Scenario, followed by the scenario name.

* **Given Keyword:** Given keyword is normally used when we have to give some pre-condition in our test case.

* **When Keyword:** When the keyword is used to perform some action.

* **And Keyword:** There is no annotation for AND keyword. It is used to connect two statements and provides the logical AND condition between any two statements. 

* **And Keyword:** There is no annotation for AND keyword. It is used to connect two statements and provides the logical AND condition between any two statements. 

* **But Keyword:** But the keyword is used to represent negative assertions in addition to the previous statement.

* **Background Keyword:** If there is any repetitive step that is going to be used in every test case. We just add the repetitive step under Keyword Background. Step keep under Background would be run before every test case.

### Consider the example below for a better understanding:
<br>

**Given** the user has entered invalid credentials
<br>

**When** the user clicks the submit button
<br>

**Then** display the proper validation message


# Benefits of BDD in Cucumber Framework
<br>

* Focuses on defining ‘behavior’ rather than defining ‘tests’.
  
* Enhances communication among the members of a cross-functional product team.

* Helps reach a wider audience by the usage of non-technical language.
  
* It enables you to understand how the system should perform from the developer’s and customer’s perspective.
  
* The improvement in the quality of code results in reduced costs of maintenance and also minimizes the project’s associated risks.
  
# The below image describes a simple BDD operation –

![Alt text](image.png)



# Limitations of Behavior-driven development


* Testers must have prior experience in TDD (Test-driven Development) to work in BDD.


* BDD approach may be ineffective if the requirements are not correctly analyzed.
  
* Testers must have sufficient technical skills.

### Cucumber with Selenium
* Many organizations prefer the Selenium framework for cross-browser compatibility testing. These organizations also prefer integrating Cucumber with Selenium as it makes it easier to read and understand the flow of applications among the members of different teams. Gherkin syntax involves simple and plain text, which makes it easier to understand test cases.

* Running the Cucumber Selenium tests on real browsers and devices is essential.

* BrowserStack cloud testing supports Selenium testing with Cucumber; sign up, choose the required device-browser-OS combination, and start testing websites.
  
* With BrowserStack Test Management, teams can upload BDD-JSON based report upload using Cucumber. This enables you to sync test case reports on BrowserStack Test Management from your terminal.

### Summary

* The Cucumber testing tool is a purely business-driven development tool written in Ruby.
  
* The business-driven development approach is an advancement over the test-driven development approach, which follows the
  
* ‘Given-When-Then’ steps for writing test cases
  
* Cucumber framework uses Gherkin ( A simple plain text language parser) to describe expected software behaviors logically, resulting in better communication and collaboration among technical and non-technical team members.

* Cucumber is compatible with popular software platforms like Selenium, Watir, Ruby, and others.
  
* One must also consider the limitations before deciding on the behavior-driven development approach.
