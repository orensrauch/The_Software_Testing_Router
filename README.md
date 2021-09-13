# The Software Testing Router

This repo is the best place to learn and keep your testing skills sharpen,
The entire content listed below was gathered and placed in a specific order from the intro of the software testing domain up to advanced testing technologies and skills.

<div align="center">
<img src="https://github.com/orensrauch/The_Software_Testing_Router/blob/main/assets/the%20best%20software%20testing%20resource.png" alt="software-testing-router-header" width="100%"/>
</div>

### 👨🏻‍💻 If you can, contribute to this great repo. 👩‍💻



Happy Testing 🚀
------------

**Table of Contents**

- [Top Page](#The-Software-Testing-Router)
- [Software testing fundamentals](#Software-testing-fundamentals)
  - [Document writing methodology](#Document-writing-methodology)
  - [Test Types](#Testing-Types)
- [Manual testing](#Manual-testing)
- [Automation testing](#Automation-testing)
  - [Automation testing articles](#Automation-testing-articles) 
  - [Automation testing codeless](#Automation-testing-codeless-tools)
  - [Automation testing practice websites](#Automation-testing-practice-websites)
  - [Automation testing with code](#Automation-testing-with-code)
  - [Automation testing libraries & frameworks](#Automation-testing-libraries-and-frameworks)
- [Testing Tools](#Testing-Tools)
- [Test Management and Collaboration Tools](#Test-Management-and-Team-collaboration-Tools)
- [Software Testing Read & Learn Resources](#Articles-and-Learning-resources)
- [Credits and Thanks](#Credits-and-Thanks)
 
------------

# Software testing fundamentals 
⚙️
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)
- 
Hi 👋 and welcome to this Awesome repo that is all about software testing.
Before you can start testing software, you need to understand the terminology, the logical reason of when to do what, and the why.
I suggest of course to learn ISTQB FOUNDATION as a ground base of knowledge required to start your path.
there is also a need to understand testing methodologies such as Agile and SCRUM framework which is the main domain of performing tests nowadays.
here are the main objectives a QA tester needs to understand and apply, the deeper the understanding will go, the smarter the QA tester will be, the more professional skills and confidence he will add to the project under test.

The QA tester has the main responsibility, to give confidence in the stability of the software to perform as the client expects it to be.
we need to think about every scenario, every test case, we need to challenge the software in the most creative possible way our time and budget allow in order to alert on every defect we can find to raise the confidence rate before the software goes production.

# How to Start with Testing?
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

Depend on your path you aim for, Software developer or QA Manual/ Automation or Automation developer, all of those paths start from the understanding of testing or debugging edit value, why do we even need this? why cant a developer just write his App and deploy for production? can't a developer do his own testing? and many more importent questions you should learn the answer to.

there is a universal language related to the Software development lifecycle that all tech employees must stick to inorder to communicate and understand each other whatever his role, basic set of terms and approaches are listed below.
more information can be learned at [ISTQB Glossary](https://glossary.istqb.org/en/search/)

# Terminology & Glossary
💬
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

## The meaning of 
| Term ☝🏻        |                Meaning❓      |
| ------------- | -------------               |
| Quality Assurance | Activities focused on providing confidence that quality requirements will be fulfilled|
|Testing|The process consisting of all lifecycle activities, both static and dynamic, concerned with planning, preparation and evaluation of a component or system and related work products to determine that they satisfy specified requirements, to demonstrate that they are fit for purpose and to detect defects|
|Defect|An imperfection or deficiency in a work product where it does not meet its requirements or specifications|
|Bug| a failure or a flaw in the software program|
|Failure|An event in which a component or system does not perform a required function within specified limits|
|Error / Mistake|A human action that produces an incorrect result|
|Agile|A group of software development methodologies based on iterative incremental development, where requirements and solutions evolve through collaboration between self-organizing cross-functional teams|
|SCRUM|An iterative incremental framework for managing projects commonly used with Agile software development|
|atomic condition|A condition that does not contain logical operators|
|[test pyramid](#Test-Pyramid)|A graphical model representing the relationship of the amount of testing per level, with more at the bottom than at the top|
|equivalence partition|A subset of the value domain of a variable within a component or system in which all values are expected to be treated the same based on the specification|




# Document writing methodology
📝
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)


# Testing Types 
🎯
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

Theres many testing types and techniques, each one is suited for a different need in the SDLC, most of them can be automated(will be discussed later in this repo) and some are are avalable only when using third-party tools and scripting language.

Here are testing types and techniques a tester must understand and apply when scenario require:

### Testing Levels and approach:

| Test name  | Used for      | Learn more |
| ------------- | ------------- | ------------- |
| `Unit testing`   | a software testing method by which individual units of source code being tested  | [Unit testing](https://en.wikipedia.org/wiki/Unit_testing) |
| `Component testing`  | done after unit testing, testing component without integrating with other components e.g. modules, classes, objects, and programs |[Component testing](https://economictimes.indiatimes.com/definition/component-testing) |
| `Integration testing` |Testing group of units that suppose to work together and being connected as one unit of action| [Integration testing](https://en.wikipedia.org/wiki/Integration_testing)|
|`System testing`|a complete integrated system test to evaluate the system's compliance with its specified requirements|[System testing](https://en.wikipedia.org/wiki/System_testing)|
|`Acceptance testing`| a test conducted to determine if the requirements of a specification or contract are met|[Acceptance testing](https://en.wikipedia.org/wiki/Acceptance_testing) |

#### Test Pyramid

<img src="https://github.com/orensrauch/The_Software_Testing_Router/blob/main/assets/Testing%20Pyramid.png" alt="test pyramid cot" width="500"/>


### Testing techniques and tactics:
| Test name  | Used for      | 
| ------------- | ------------- |
|End to end testing|AKA E2E testing, A type of testing in which business processes are tested from start to finish under production-like circumstances|
|API testing|Testing performed by submitting requests to the test object using its application programming interface|
|Alpha testing| A type of acceptance testing performed in the developer's test environment by roles outside the development organization|
|Beta testing|A type of acceptance testing performed at an external site to the developer's test environment by roles outside the development organization|
|Production acceptance testing|A type of acceptance testing performed to determine if operations and/or systems administration staff can accept a system.|
|Smoke / Confidence test|A test suite that covers the main functionality of a component or system to determine whether it works properly before planned testing begins|
|Sanity/ Check test|a basic test to quickly evaluate whether a claim or the result of a calculation can possibly be true|
|Regression testing|A type of change-related testing to detect whether defects have been introduced or uncovered in unchanged areas of the software|
|regression-averse test strategy|A test strategy whereby the test team applies various techniques to manage the risk of regression such as functional and/or non-functional regression test automation at one or more levels|
|back-to-back testing|Testing to compare two or more variants of a test item or a simulation model of the same test item by executing the same test cases on all variants and comparing the results|
|UI/ GUI testing|Testing performed by interacting with the software under test via the graphical user interface|
|Black box test technique|A test technique based on an analysis of the specification of a component or system, tester does not care about the internal code, but the expected output by the given input|
|Grey box testing| a combination of white-box testing and black-box testing, The aim of this testing is to search for the defects if any due to improper structure or improper usage of applications|
|White/ clear box testing|The opposit of Black box, The tester chooses inputs to exercise paths through the code and determine the expected outputs|


# Manual testing 
👩🏻‍🔧
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)



# Automation testing 
👩🏻‍💻
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)


# Automation testing codeless tools
📦
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

# Automation testing practice websites 
🖥️
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

wwww

# Automation testing with code 
🧰
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)


# Automation testing libraries and frameworks
💾
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

## Javascript
| Library name  | Used for      |
| ------------- | ------------- |
|[Chai](https://www.chaijs.com/)|BDD / TDD assertion library|
|[Mocha](https://mochajs.org/)|Testing framework allowing Async|
|[Jest.js](https://jestjs.io/)       | Unit testing|
|[jasmine.js](https://jasmine.github.io/index.html)     |Unit testing|
|[K6](https://k6.io/) |Stress testing|
|[Cypress](https://www.cypress.io/)    | E2E testing (next big thing) |
|[playwright](https://playwright.dev/)|end-to-end testing for modern web apps|
|[Karma](https://karma-runner.github.io/latest/index.html) |testing JavaScript code in real browsers|
|Phantom|Scriptable Headless Browser (currently this project is suspended)|  
|[cucumber](https://github.com/cucumber/cucumber-js)|tool for running automated tests written in plain language|
|[nightwatch.js](https://nightwatchjs.org/)  |End-to-end testing, the easy way.   |
|[webdriver.io](https://webdriver.io/) |browser and mobile automation test framework for Node.js|
|[CodeceptJS](https://codecept.io/)|End 2 End Testing|
|[TestCafe](https://testcafe.io/)|No WebDriver required. No manual timeouts needed. Cross-browser E2E testing|

## Java
| Library name  | Used for      |
| ------------- | ------------- |
|[TestNG](https://testng.org/doc/documentation-main.html)|designed to cover all categories of tests:  unit, functional, end-to-end, integration, etc...|
|[JUnit](https://junit.org/junit5/)|TDD and unit testing |
|[Spock](https://spockframework.org/)|testing and specification framework for Java and Groovy applications|
|[Karate](https://github.com/intuit/karate)|open-source general-purpose test-automation framework|
|[Scalatest](https://www.scalatest.org/)|open-source testing toolkit for Scala and Java programmers|

  
## Python
| Library name  | Used for      |
| ------------- | ------------- |
|[Robot framework](https://robotframework.org/)  | used for test automation and robotic process automation (RPA)  |
|[PyTest](https://docs.pytest.org/en/6.2.x/)  | Functional and API testing  |
|[Unittest](https://docs.python.org/3/library/unittest.html#module-unittest) |automated unit test framework|
|[nose](https://nose.readthedocs.io/en/latest/)|Unit testing|

# Testing Tools 
🛠️
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

| Tool name  | Used for      |
| ------------- | ------------- |
|[`Leonardo`](https://github.com/outbrain/Leonardo)|Developed By outbrain dev team, This tool allow you as a dev or tester to test your app behaviour under empty inputs, errors coming from the server and situations when the server not responding, Also, unique option is to check "Slow" server responds behaviour|
|[`POSTMAN`](https://www.postman.com/)|de-facto most used API testing software in the industry nowdays|
|[`RANOREX`](https://www.ranorex.com/)| A great `*paid` GUI tool for automation testing, can build sophisticated tests for desktop, web, and mobile apps|
|[`BrowserStack`](https://www.browserstack.com/)|web and mobile testing platform |
|[`Percy`](https://percy.io/)|Percy detects, groups, and highlights relevant visual changes across your web applications and components.|

#### Good to Know

| Tool name  | Used for      |
| ------------- | ------------- |
|[`GTmetrix`](https://gtmetrix.com/)|A recommended tool for Advanced analysis on your webstie performance in Desktop & Mobile, ability to monitor and track and export reports and many more features|


# Test Management and Team collaboration Tools
🤝 🧠
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

| Logo  | Link      | What is About|
| ------------- | ------------- | ------------- |
|![](https://www.jfrog.com/jira/images/atlassian-jira-logo-large.png)|[`Jira`](https://www.atlassian.com/software/jira)| a proprietary issue tracking product developed by Atlassian that allows bug tracking and agile project management|
|![](https://iconape.com/wp-content/files/ej/371677/svg/371677.svg)|[`YouTrack`](https://www.jetbrains.com/youtrack/)|Developed by Jet Brains, `paid*` tool, concidered to be the most professional a team can get|
|![](https://d1myhw8pp24x4f.cloudfront.net/software_logo/1574939028_TestLink%20logo_mid.png)|[`testlink`](https://testlink.org/)|Well known open source test management tool|
|![](https://www.appvizer.com/media/application/29234/logo/logo-testrail-by-gurock.png)|[`Testrail`](https://www.gurock.com/testrail/)|currently marked as the top tool `*paid` for team collaboration in the agile era|
|![](https://www.practitest.com/assets/img/logo.png)|[`PractiTest`](https://www.practitest.com/)|High quality test management tool with fantastic Documentation and multi integration capabilities|
|![](https://avatars.githubusercontent.com/u/17636279?s=200&v=4)|[`ReportPortal.io`](https://reportportal.io/)|AI-powered Test Automation Dashboard open source|

# Articles and Learning resources
🔍
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)

| Logo  | Link      | What is About|
| ------------- | ------------- | ------------- |
|![](https://github.com/orensrauch/The_Software_Testing_Router/blob/main/assets/satisfice-logo.jpg?raw=true)|[`SATISFICE`](https://www.satisfice.com/)|by James and Lenore Bach, Awesome testing practical learning material|
|![](https://github.com/orensrauch/The_Software_Testing_Router/blob/main/assets/tmap-logo.png.jpg?raw=true)|[`Tmap`](https://www.tmap.net/)|Well known publisher of books and learning material in the QA and DevOps domain|
|![](https://cdn.guru99.com/images/cropped-test2.png)|[`Guru99`](https://www.guru99.com/)|This website in the ultimate learning resource for software tester, with a lot of rich content and nice testing simulatores for the beginner QA tester|


# Credits and Thanks
- [⏫ Back to Page Top ⏫](#The-Software-Testing-Router)
- 
* Assets

  -header image : <a href='https://www.freepik.com/photos/technology'>Technology photo created by freepik - www.freepik.com</a>









