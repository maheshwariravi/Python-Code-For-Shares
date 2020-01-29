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

























