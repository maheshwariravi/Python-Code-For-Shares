Python-Code-For-Shares
======================
Requirement Traceability Matrix (RTM) is a report that maps and traces every functional requirement has respective test-cases to make sure if the requirement is covered for testing or not and no functionality is unchecked during Regression testing cycle. Typically we map below data in the report:
1.	Requirement ID 
2.	Requirement Description
3.	Application Name
4.	Test-case ID
5.	Test-case Description
6.	Test-case Designer
7.	Test-case Execution Status
8.	Defects?
9.	Defect ID
10.	Defect Status









A TEST PLAN is a detailed document that describes the test strategy, objectives, schedule, estimation and deliverables and resources required for testing. It helps to determine the effort needed to validate the quality of the application under test. Which works as a blueprint to conduct software testing activities as a defined process which is minutely monitored and controlled by the test manager. 
This document includes below information in detail:
Test Plan Identifier:
•	Provide a unique identifier for the document.
Introduction:
•	Provide an overview of the test plan. 
•	Specify the goals/objectives. 
•	Specify any constraints.
References:
•	List the related documents, with links to them if available.
Test Items:
•	List the test items and their versions.
Features to be Tested:
•	List the features of the software/product to be tested. 
•	Provide references to the Requirements and Design specifications of the features to be tested
Features Not to Be Tested:
•	List the features of the software/product which will not be tested. 
•	Specify the reasons these features won’t be tested.
Approach:
•	Mention the overall approach to testing. 
•	Specify the testing levels, the testing types, and the testing methods [Manual/Automated; White Box/Black Box/Gray Box]
Item Pass/Fail Criteria:
•	Specify the criteria that will be used to determine whether each test item has passed or failed testing.
Suspension Criteria and Resumption Requirements:
•	Specify criteria to be used to suspend the testing activity. 
•	Specify testing activities which must be redone when testing is resumed.
Test Deliverables:
•	List test deliverables, and links to them if available, including the following: 
•	Test Plan 
•	Test Cases 
•	Test Scripts 
•	Defect/Enhancement Logs 
•	Test Reports
Test Environment:
•	Specify the properties of test environment: hardware, software, network etc. 
•	List any testing or related tools.
Estimate:
•	Provide a summary of test estimates (cost or effort) and provide a link to the detailed estimation.
Schedule:
•	Provide a summary of the schedule, specifying key test milestones, and/or provide a link to the detailed schedule.
Staffing and Training Needs:
•	Specify staffing needs by role and required skills. 
•	Identify training that is necessary to provide those skills, if not already acquired.
Responsibilities:
•	List the responsibilities of each team/role/individual.
Risks:
•	List the risks that have been identified. 
•	Specify the mitigation plan and the contingency plan for each risk.
Assumptions and Dependencies:
•	List the assumptions that have been made during the preparation of this plan. 
•	List the dependencies.
Approvals:
•	Specify the names and roles of all persons who must approve the plan. 
•	Provide space for signatures and dates. (If the document is to be printed.)







Key principles of designing good Test Case:
1.	Create test cases that are as simple as possible in assertive language. They must be clear and concise as any person can execute it.
2.	The ultimate goal of any software project is to create test cases that meet customer requirements and is easy to use and operate. A tester must create test cases keeping in mind the end user perspective
3.	Do not repeat test cases. If a test case is needed for executing some other test case, call the test case by its test case id in the pre-condition column
4.	Do not assume functionality and features of your software application while preparing test case. Stick to the Requirement Documents.
5.	No unnecessary steps should be included in it.
6.	It should be traceable to requirements.
7.	Make sure you write test cases to check all (100%) software requirements mentioned in the requirement document. 
8.	Name the test case name such that they are identified easily while tracking defects or identifying a software requirement at a later stage.
9.	The test case you create must return the Test Environment to the pre-test state and should not render the test environment unusable. This is especially true for configuration testing.
10.	The test case should generate the same results every time no matter who tests it
11.	After creating test cases, get them reviewed by your colleagues. Your peers can uncover defects in your test case design, which you may easily miss.
12.	Testing methodologies should be considered while writing any test-case:
•	Boundary Value Analysis: As the name suggests it's the technique that defines the testing of boundaries for a specified range of values. 
•	Equivalence Partition: This technique partitions the range into equal groups that tend to have the same behavior. 
•	State Transition Technique: This method is used when software behavior changes from one state to another following particular action. 
•	Error Guessing Technique: This is anticipating the error that may arise while doing manual testing. This is not a formal method and takes advantages of a tester's experience with the application





Software Testing Principles:
1.	Testing shows presence of defects: The goal of software testing is to make the software fail. Software testing reduces the presence of defects. Software testing talks about the presence of defects and doesn’t talk about the absence of defects. Software testing can ensure that defects are present but it can’t prove that software is defects free. Even multiple testing can never ensure that software is 100% bug-free. Testing can reduce the number of defects but not removes all defects. 
2.	Exhaustive testing is not possible: It is the process of testing the functionality of a software in all possible inputs (valid or invalid) and pre-conditions is known as exhaustive testing. Exhaustive testing is impossible means the software can never test at every test cases. It can test only some test cases and assume that software is correct and it will produce the correct output in every test cases. If the software will test every test cases then it will take more cost, effort, etc. and which is impractical. 
3.	Early Testing: To find the defect in the software, early test activity shall be started. The defect detected in early phases of SDLC will very less expensive. For better performance of software, software testing will start at initial phase i.e. testing will perform at the requirement analysis phase. 
4.	Defect clustering: In a project, a small number of the module can contain most of the defects. Pareto Principle to software testing state that 80% of software defect comes from 20% of modules. 
5.	Pesticide paradox: Repeating the same test cases again and again will not find new bugs. So it is necessary to review the test cases and add or update test cases to find new bugs. 
6.	Testing is context dependent: Testing approach depends on context of software developed. Different types of software need to perform different types of testing. For example, The testing of the e-commerce site is different from the testing of the Android application. 
7.	Absence of errors fallacy: If a built software is 99% bug-free but it does not follow the user requirement then it is unusable. It is not only necessary that software is 99% bug-free but it also mandatory to fulfill all the customer requirements.



Severity Vs Priority:

Severity	Priority
Severity is a parameter to denote the impact of a particular defect on the software.	Priority is a parameter to decide the order in which defects should be fixed.
Severity means how severe defect is affecting the functionality.	Priority means how fast defect has to be fixed.
Severity is related to the quality standard.	Priority is related to scheduling to resolve the problem.
Testing engineer decides the severity level of the defect.	Product manager decides the priorities of defects.
Its value is objective.	Its value is subjective.
Its value doesn’t change from time to time.	Its value changes from time to time.
Priority is of 3 types: Low, Medium, and High.	Severity is of 5 types: Critical, Major, Moderate, Minor, and Cosmetic.















Test Metric

Software Testing Metric is be defined as a quantitative measure that helps to estimate the progress, quality, and health of a software testing effort. A Metric defines in quantitative terms the degree to which a system, system component, or process possesses a given attribute. 




The different types of Test deliverables are:
Hence, the test deliverables prepared during the process of software testing are:
1.	Test Specification Document: This document contains a detailed summary of the scenarios that are going to be tested, the way they will be tested, and how often the testing activity is going to be performed.
2.	Test Plan Document: A test plan document is a blueprint for carrying out testing process. It lists the sequence of activities that are followed by the team to test the software. Apart from defining the testing process, it also identifies the scope and objective of testing.
3.	Test Strategy: This is the the way or approach used by the team to achieve the testing target. It includes the test objectives, methods to test new functions, time and resources required for the project as well as the test environment.
4.	Test Scenario Document: Such a document simply depicts the flow of application. A test scenario document helps to make sure that every process flow is tested thoroughly.
5.	Test Design Standards: Standards are the formally defined ways or rules that lay the foundation upon which the design of tests is prepared.
6.	Test Case Document: The test case document enlists the various combinations of input and output that produces a pass or fail report. Based on the report, further rectifications or updates are decided upon.
7.	Requirement Traceability Report: A traceability matrix is prepared to map the requirements with specifications. The traceability matrix is followed throughout the validation process to ensure that requirements are not compromised while testing the software. This document is updated as the project progresses.
8.	Test Logs: A log report is a complete list of series of test execution activities. It is a precise report of the passed or failed tests, contains details regarding test operations and states the reasons behind passed or failed activities.
9.	Test Data: The data or input provided to the application with the intent of fetching some results, are called test data.
10.	Test Metrics: The measuring mechanisms for analysing a product's efficiency and its degree of complexity are termed as test metrics. Test metrics have various models and formulas for calculating results.
11.	Test Status Report: Status report is that document which is prepared with an aim to track the progress of the application. Status report can be prepared on a periodic or weekly basis, to list the accomplishments till that time, the work that remains pending, and a milestone analysis.
12.	Test Scripts: Test script defines the various steps as well as instructions that are executed by the team on the software to tests and validate its functionality and to ensure that it is as per the requirements and expectations of the client.
13.	Installation & Configuration Guide: It defines system’s or program’s installation and configuration requirements, such as the way it is set up, the components that make up the system, and its hardware & software requirements.
14.	Effort Estimation Report: Effort estimation report highlights the efforts put in by the team to complete the process of testing. Moreover, the cost and time of failed and passed test cases is also defined by the team in this document. 
15.	Test Execution Report: This document contains the test results and the summary of test execution activities.
16.	Test Incident Reports: Reports all the incidents- resolved or unresolved -found while testing the software. It tracks, classifies and manages the incidents. Additionally, it helps the team differentiate incidents from defects. 
17.	Bugs/Defects Report: A bug report is simply a document enlisting all the errors generated through a test.
18.	Test Closure Reports: From defining various testing techniques and methodologies, to providing details about the various defects, bugs, and discrepancies found in the software, this report offers a summary of the entire testing process to the reader.
19.	Release Notes: These are the documents and reports delivered to the client, customer or other stakeholders of the project after the culmination of the testing process.







Tests that should be automated:
•	Business critical paths – the features or user flows that if they fail, cause a considerable damage to the business. 
•	Tests that need to be run against every build/release of the application, such as smoke test, sanity test and regression test. 
•	Tests that need to run against multiple configurations — different OS & Browser combinations. 
•	Tests that execute the same workflow but use different data for its inputs for each test run e.g. data-driven. 
•	Tests that involve inputting large volumes of data, such as filling up very long forms. 
•	Tests that can be used for performance testing, like stress and load tests. 
•	Tests that take a long time to perform and may need to be run during breaks or overnight. 
•	Tests during which images must be captured to prove that the application behaved as expected, or to check that a multitude of web pages looks the same on multiple browsers.
Tests that should not be automated:
•	Tests that you will only run only once. The only exception to this rule is that if you want to execute a test with a very large set of data, even if it’s only once, then it makes sense to automate it. 
•	User experience tests for usability (tests that require a user to respond as to how easy the app is to use). 
•	Tests that need to be run ASAP. Usually, a new feature which is developed requires a quick feedback so testing it manually at first 
•	Tests that require ad hoc/random testing based on domain knowledge/expertise – Exploratory Testing. 
•	Intermittent tests. Tests without predictable results cause more noise that value. To get the best value out of automation the tests must produce predictable and reliable results in order to produce pass and fail conditions. 
•	Tests that require visual confirmation, however, we can capture page images during automated testing and then have a manual check of the images. 
•	Test that cannot be 100% automated should not be automated at all, unless doing so will save a considerable amount of time.




Load testing
Load testing measures system performance as the workload increases. That workload could mean concurrent users or transactions.The system is monitored to measure response time and system staying power as workload increases. That workload falls within the parameters of normal working conditions.
Stress testing
Unlike load testing, stress testing — also known as fatigue testing — is meant to measure system performance outside of the parameters of normal working conditions. The software is given more users or transactions that can be handled. The goal of stress testing is to measure the software stability. At what point does software fail, and how does the software recover from failure?
Spike testing
Spike testing is a type of stress testing that evaluates software performance when workloads are substantially increased quickly and repeatedly. The workload is beyond normal expectations for short amounts of time.
Endurance testing
Endurance testing — also known as soak testing — is an evaluation of how software performs with a normal workload over an extended amount of time. The goal of endurance testing is to check for system problems such as memory leaks. (A memory leak occurs when a system fails to release discarded memory. The memory leak can impair system performance or cause it to fail.)
Scalability testing
Scalability testing is used to determine if software is effectively handling increasing workloads. This can be determined by gradually adding to the user load or data volume while monitoring system performance. Also, the workload may stay at the same level while resources such as CPUs and memory are changed.
Volume testing
Volume testing determines how efficiently software performs with a large, projected amounts of data. It is also known as flood testing because the test floods the system with data.













