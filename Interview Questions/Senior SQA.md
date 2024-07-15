1. What is Quality Assurance?
Quality assurance aims to ensure that the generated software complies with all the requirements and specifications in the SRS document.

2. Define the purpose of QA in Software Development.
QA’s Roles And Responsibilities:

Defining test objectives and the strategy for achieving them.
Developing a test strategy based on the specifications and timelines of the project.
Executing tests using the appropriate methods (manually or with test execution tools) and recording test failures.
Determining the root cause by analyzing the flaws.
Repairing flaws, so they don’t compromise the quality of the final output.
Reporting software flaws to developers using a bug tracking system (e.g., Bugzilla, Mantis, QA Touch). Early testing to remove deficiencies at an early stage lowers the cost and duration of bug fixes.



3. What is the lifecycle of a Quality Assurance Process?
QA follows a PDCA lifecycle:

i. Plan

The organization specifies the procedures needed to create a software product of the highest caliber during the planning phase of the Quality Assurance process.

ii. Do

Do is a stage in which the procedures are developed and tested.

iii. Check

This stage is intended to monitor the operations and determine whether they adhere to the users’ needs.

iv. Act

The Act is a step in putting the necessary procedures into action.


4. Differentiate between Test Plan and Test Strategy.
Test Plan	
Test Strategy

A test plan for software projects is a document that outlines the goal, strategy, approach, and emphasis of a software testing effort.	
A test strategy is a set of rules that specifies test design and how testing must be carried out.

A testing manager or lead executes a test plan that specifies how, when, and what to test. 	
The project manager implements a test strategy. It explains the kind of methodology to use and the module to test.

The test plan describes the specification. 	
Test strategy describes the general methods.

The test plan may alter. 	
There is no way to adjust the test strategy.

The Test approach is a long-term action plan. Test planning aims to detect risks by identifying potential problems and dependencies. 
Non-project-specific information can be abstracted and applied to test strategy.

Test plan can be an individual plan. 	
The test strategy element of a test plan is frequently encountered in smaller projects.

5. Explain What is Build and Release. Differentiate Between Them.
Build:

The development team provides the test team with a “build.”
The test team may reject it if any tests fail or a “build” does not satisfy the requirements. 
Multiple builds comprehend to a single release.
Release:

 A product’s official release to customers is called a “release.”
Customers receive a build when it has been “released” after being tested and approved by the test team.


6. What Do You Understand About Bug Leakage and Bug Release?
Bug leakage:

A bug leak occurs when the bug is missed in previous builds or versions of the application.
A bug leakage is a fault that happens while testing but is discovered later by the tester or end-user.
Bug release:

A bug release occurs when a specific software version is released with several known bugs or defects. Usually, the Release Notes make mention of these bugs. These bugs are frequently of low priority and low severity. 
When the business can afford it, it is decided to leave the bug in the deployed software rather than spend time and money correcting it in that specific version.

7.  What Do You Mean by Monkey Testing?
In software development, The effectiveness of an application is tested through monkey testing. “Monkey testing” involves a tester randomly inputting data into the program with no intention of crashing it. By supplying arbitrary inputs and attempting to break the program, it is appropriate for load testing. 

Some flaws might not always be discovered using conventional methods at regular intervals. These problems are more likely to be found if random inputs are provided. This method is used to uncover bugs not typically encountered by conventional methods and is applied to the entire system.

8. What Do You Mean by Gorilla Testing?
Gorilla testing meticulously tests every last bit of code until it fails using arbitrary inputs, whereas the resilience of an application is tested rigorously by hand. 

The main difference between Gorilla and Monkey testing is that the former tests specific modules, whereas the latter evaluates the entire system. Random valid and invalid inputs are supplied into each product’s modules until a module crashes.

This phase is carried out for each module in the last phases of the software development cycle to test the robustness of the application. It is also known as “torture testing” or “fault tolerance testing” because it is rigorous.

9. Explain Testware.
Testware refers to the artifacts created during the testing process needed to plan, design, and carry out tests. 

Documentation, scripts, inputs, anticipated outcomes, setup and teardown methods, files, databases, environments, and other software or utilities needed in testing are considered testware.

Testware is considered a testing tool that is adequately saved and controlled by a configuration management tool.

Testware differs from regular software in two ways:

It is created by testers for a specific objective.
It has multiple users and various quality measures.

10. What is a traceability matrix?
The Traceability matrix is a specific kind of document used in software development projects to track, identify, and confirm the development of a particular capability or component. Aids in connecting and tracing business, application, security, and other requirements to their execution, testing, or completion. It assesses and compares various system components and gives information on the state of the project’s needs in terms of their degree of completion.

A worksheet-style document with a table typically serves as a traceability matrix. An identifier for one group is placed in the top row, and an identification for the other set is placed in the left column to compare the two sets of values. A mark is made if there is a similarity or a connection.

11. Distinguish Between Verification and Validation.
Verification	
Validation

The Verification involves verifying documentation, designs, codes, and programs.	
The validation process involves testing and validating the actual product. 

Verification does not involve code execution.	
Validation involves code execution

Verification uses techniques like reviews, walkthroughs, inspections, and desk-checking.	
Validation employs black box testing, white box testing, and non-functional testing.

Verification examines whether the software confirms a specification.	
Validation examines whether the program satisfies the needs and expectations.

Verification discovers the bugs early in the development cycle.	Validation finds the issues that verification is unable to catch. 

Verification targets software architecture, design, and databases.	
Validation focuses on the actual software product

The QA team conducts verification	
The QA team does validation independently of testing teams

Verification occurs first	
Validation is performed after verification

12. Distinguish Between Retesting and Regression Testing?

Retesting:
Retesting is a technique to verify particular test cases discovered to have bugs in the final execution. Testers typically find these defects as they test a software program, then they are given to developers to remedy. The developers then fix the bugs and provide them back to the testers for validation. Retesting is the name of this ongoing procedure.

Regression testing:
Regression testing validates if a code update has negatively affected the application’s current features and functions.

Regression testing is conducted on passed test cases, whereas retesting is only performed on failed test cases.

While retesting verifies that the initial flaw has been fixed, regression testing looks for unanticipated side effects.

Unlike Regression testing, retesting includes defect verification.
Retesting is planned to test, whereas regression testing is called generic testing.
Automation makes it possible to perform regression testing but not retesting


13. What Do You Know About the Defect Leakage Ratio?
Defect Leakage is a metric used to measure how well QA testing is done or how many problems get overlooked.

Formula to find the defect leakage ratio:

Defect Leakage = (No. of Defects Found in UAT / No. of Defects Found in QA Testing)

14. Describe the Different Forms of Software Quality Assurance Documentation.
i. Test policy: is a high-level document outlining the organization’s fundamental testing principles, methodologies, and critical testing objectives.

ii. Testing strategy: The testing strategy outlines the test levels (types) used for the project.

iii. Test plan: A test plan is an all-inclusive planning document (often formatted as a digital flipbook or interactive PDF) that includes information about the purpose, strategy, available tools, schedule, and other testing activities.

iv. Requirements Traceability Matrix: The requirements and test cases are related to this document.

v. Test scenario: A software system’s test scenario is a component or occurrence that one or more test cases could confirm.

vi. Test case: It is a collection of input values, expected postconditions for the execution, and results.

vii. Test Data: Test Data is information present before a test is run.

viii. Defect Report: A defect report is a written description of any error in a software system that prevents it from operating as intended.

ix. Test summary report: A high-level test summary report outlines the testing operations and test results.


15. What is a Cause-Effect Graph?
The cause-effect graph is an inclusion of a black box testing technique that identifies the fewest test cases that can adequately test the full scope of the product, Based on a set of criteria. It also highlights the connection between a particular result and the elements influencing the outcome.

The real benefit of cause-effect graph testing is the reduced test execution time and cost.

16. What are the Five Dimensions of Risk?
The five dimensions of risk are as follows:

i. Schedule: Unrealistic timelines, such as building a large piece of software in a single day.

ii. Client: Unclear requirements, changing requirements, and ambiguous requirements descriptions.

iii. Human Resource: Lack of sufficient resources with the required expertise for the project.

iv. System assets: An unfavorable outcome will result from the inability to acquire all necessary resources, including hardware and software tools or licenses.

v. Quality: Product quality will be impacted by multiple factors, such as a lack of resources, a strict delivery timetable, and frequent modifications.

17. What Do You Understand About Regression Testing? Which Test Cases Should be Selected for this Process?
Regression testing is testing performed to ensure that a software update won’t impact how the product currently operates.

Practical regression tests may use the test cases listed below:

If features are apparent, users can see more of them.
Scenarios that examine the core properties of the product
Case studies of functionality that have undergone significant and recent changes
Every Integration Test Case
All Comprehensive Test Cases
Examples of boundary value tests
A variety of failure test case examples

18. Distinguish Between Severity and Priority.
Severity: The degree to which a specific flaw can affect the software is known as its severity. The parameter of “severity” describes how the defect affects the software’s functionality.

Priority: A characteristic that determines the sequence in which a defect should be addressed is called a priority. The first defect that needs to be corrected is the one with the highest importance.

Severity	
Priority

A parameter that describes a software defect’s impact is called severity. 	
Priority is a parameter that determines the sequence to fix the problems.

The degree to which a flaw affects functionality is its severity.	
Priority refers to how quickly a fault must be corrected.

The quality standard is related to severity. 	
Priority is related to how the issue will be scheduled for resolution.

The testing engineer determines the severity of the flaw.	
The product manager sets the order of importance for defects.

Value is a measurement of severity. 	
The priority value is a matter of opinion.


23. What is the Difference Between Functional and Non-Functional Testing?
Functional Testing:

Functional testing validates each software function or feature.
Functional testing focuses on the client’s needs.
Functional testing aims to validate program actions.
Functional testing example would be to verify the login process.
Functional describes what the product performs, whereas Non-Functional describes how the product operates.
Functional testing is conducted before nonfunctional testing.
Non-Funtional Testing:

Non-functional testing validates nonfunctional elements, including performance, usability, and reliability.
Non-functional testing is challenging to execute manually.
non-functional testing is based on the customer’s expectations.
Non-functional testing confirms software performance.
Non-functional testing example would ascertain that the dashboard should load within two seconds.
Non-functional testing is performed after functional testing.


24. How Do You Decide When to Stop Testing?
Sometimes, as project managers or project leads, we may have to cancel testing to launch the product sooner. In those circumstances, we must determine whether the product has received sufficient testing from the testers.

When deciding when to halt testing in real-time projects, various considerations must be taken into account:

If the testing or release deadlines are met.
By entering the determined test case pass rate.
If the risk in the real-time project is below the permitted level.
If all the critical bugs and roadblocks have been resolved.
If the submission meets the requirements.

25. Differentiate Between Load Testing And Stress Testing.
The purpose of each is what makes a difference:

Through load testing, you can learn how a system responds to a predicted load.

Stress testing enables you to comprehend the maximum loads at which a system can function.

In other words, stress tests show you how a system might respond to heavy demand, such as a DDoS attack, the Slashdot effect, or different scenarios. In this manner, you might be ready for unforeseen occurrences. 

On the other hand, load tests ensure you fulfill user expectations, such as service level agreement (SLA) obligations. So instead of breaking the application, the objective is to guarantee a satisfactory overall user experience. It enables you to deploy new code with assurance.

26. What is Ad-hoc Testing?
Adhoc testing is a causal method of software testing. It does not adhere to established procedures such as test plans, test cases, and requirement documentation.

Adhoc testing has the following traits:

It is done on an application after formal testing is finished.
Its primary goal is to malfunction the program without a predetermined procedure.
Adhoc testers should be well knowledgeable about the product they are testing.

27. ow is Adhoc Testing Different From Monkey Testing and Exploratory Testing? State the Differences Among Them:
Adhoc and monkey testing both use an informal style. Although monkey testing does not require in-depth software understanding, Adhoc testing requires testers to have a thorough program knowledge.

The following is a list of the distinctions between exploratory testing and ad-hoc testing:

Adhoc testing is testing software without reference to requirements documents or specifications. Exploratory testing entails understanding the software and investigating the application.
In Adhoc testing, documentation is not necessary. In exploratory testing, documentation is required.
Adhoc testing’s primary goal is to refine the testing process. Learning about the application is the primary goal of exploratory testing.
Adhoc testing is a non-formal approach, while exploratory testing is a formal procedure.

28. What is a Bug Life Cycle?
i. New,

The status of a new defect, is set to New when it is initially logged and posted.

ii. Assigned

After the tester posts a bug, the tester’s lead reviews the bug and designates it for the developing team.

iii. Open

The developer gets to work on the defect fix and analysis.

iv. Fixed

A developer may mark an issue as fixed once the required code modifications have been made and verified.

v. Retest

The tester retests the code to see if the developer has fixed the issue. If not, then the status is changed to retest.

vi. Reopen

Once the developer has fixed the bug, but it still exists, the tester switches the status to Reopen, and the bug runs through the bug life cycle.

vii. Verified

After the developer has corrected the bug, the tester retests it; if no bugs are discovered, the status is changed to Verified.

viii. Closed

The status is changed to Closed if the bug is no longer present.

ix. Duplicate

The status is changed to Duplicate if the defect occurs twice or if it shares the same concept as the prior problem.

x. Rejected

The status is changed to Rejected if the developer believes the flaw is not there.

xi. Deferred

If the bug can be patched in the upcoming release and does not have a higher priority, the status becomes Deferred.

29. You have an input field that accepts an integer. The valid input is a positive two-digit integer. Specify test cases according to equivalence partitioning and boundary value analysis testing techniques.

30. What is the difference between severity and priority? Give examples of issues having high severity and low priority versus low severity and high priority.

31. When is test automation not desirable?

32. What are the steps of the quality assurance life cycle?
For this question, the QA engineer interviewee can mention the steps, what they entail, and why each is important. The steps include:

Requirements gathering
Test planning
Test execution
Bug tracking
Regression testing
Release
The QA team develops test plans and strategies, creates test cases, executes tests, logs bugs, and performs regression testing. After all tests are passed the product is released to customers.

33. What is a requirements traceability matrix (RTM), and why use it?
A requirements traceability matrix (RTM) is a document that helps to trace the relationship between requirements and the test cases that verify those requirements. It is a table that maps the requirements of a project to the test cases that ensure each requirement has been fulfilled.

Using an RTM can provide several benefits to a software development project, such as:

Ensure all requirements have been met and tested, reducing the risk of missing critical features or functions.
Enable easy tracking and managing of requirements and test cases throughout the project lifecycle for all staff involved.
Identify gaps or inconsistencies in the requirements, allowing for early detection and resolution of potential issues.
Improve communication and collaboration between different teams working on the project to ensure everyone clearly understands the testing procedures and status.

34. What would you do if you lacked documentation for testing purposes?
If documentation is lacking for testing purposes, the first step is communicating with the stakeholders and development team to gather as much information as possible.

It's important to prioritize the testing based on critical features and functionalities and focus on exploring the system to discover potential defects. Exploratory testing techniques can be helpful in such situations.

One should also document the testing process and results thoroughly to facilitate future testing and ensure traceability. Finally, report any issues or risks associated with the lack of documentation to the relevant stakeholders.

35. What are the key automation testing challenges?
Some key automation testing challenges you may face during your senior QA engineer career include:

Test case selection
Maintaining automation scripts
Test environment setup
Data management
Test execution scheduling and management
Reporting and analysis
Test tool selection and integration
Continuous integration and continuous testing

36. How do you start quality assurance on a project?
To start quality assurance on a simple or advanced project, you should review the project requirements and create a test plan. The test plan should identify the test objectives, testing scope, testing resources, testing tools, and testing timelines.

You should then execute the test cases outlined in the plan, log any defects found, and track the progress of testing activities. It's important to communicate regularly with the development team and stakeholders to ensure that all parties know the testing progress and any issues found.

As testing progresses, you can adjust the test plan and test cases as needed to ensure that all aspects of the project are covered.

37. What is the difference between smoke testing and sanity testing?
Smoke testing is a preliminary level of testing to ensure that the critical functionalities of the software are working correctly. It is conducted to verify if the software is stable enough for further testing.

Sanity testing is a narrow and focused type of regression testing to ensure that the changes made to the codebase do not adversely affect the system's existing functionalities. It is performed to check if the bugs found in previous testing have been fixed and that no new bugs have been introduced.

38. Describe the bug cycle steps
As a candidate, you should have knowledge of the bug cycle, which typically follows these steps:

Defect discovery: A defect is discovered during testing or by a customer.
Defect reporting: The tester reports the defect along with a detailed description and steps to reproduce it.
Defect prioritization: The defect is prioritized based on its severity and impact on the product.
Defect assignment: The defect is assigned to a developer to investigate and fix.
Defect fixing: The developer fixes the defect and verifies the fix.
Defect verification: The tester verifies that the defect has been fixed and closes it if it has.
Defect closure: The defect is closed after being fixed and verified.

39. What should a good test strategy include?
A good test strategy should include the following elements as part of the QA improvement process:

Clear objectives and goals for testing
Scope and coverage of testing
Types of testing to be performed, such as functional, performance, or security
Test environment requirements
Test data requirements
Test case design and execution approach
Test automation approach
Defect management and reporting processes
Roles and responsibilities of the testing team
Communication and collaboration channels with stakeholders

40. Do you think QAs can also participate in resolving production issues?
Yes, QAs can and should participate in resolving production issues. Quality assurance professionals can bring a unique perspective to the problem-solving process as they deeply understand the system's functionality and how it is expected to behave.

In addition, they are skilled at identifying and replicating bugs and defects, which can be invaluable in identifying the root cause of a production issue.

By collaborating with developers and other stakeholders, QAs can help diagnose and resolve issues quickly, minimizing their impact on users and improving the system's overall quality.

