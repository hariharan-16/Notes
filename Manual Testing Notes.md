Manual Testing

1. What is SDLC?
    Software Development Life Cycle is a step by step procedure to develop a software.
    7 types of stages in SDLC:
        1. Requirement analysis.
        2. Feasibility study.
        3. System Design - HLD & LLD.
        4. Coding.
        5. Testing.
        6. Installation.
        7. Maintenance.

2. What is requirement analysis?
    It is a process of gathering the requirement from the clients and understand what the system should do. The BA will convert the CRS(Customer Requirement Specification) to SRS(Software Requirement Specification).

3. What is feasibility study?
    It is a process of analyzing how much developers needed for the project, how much need to be invested in the ptoject to get profit & which tech stack should be used.

4. What is system Design?
    In design we will analyze how the architecture, database and UI will be built.
    HLD - High Level Design is used to design the architecture of the project.
    LLD - Low Level Design is used to design feature or module of the project.

5. What are the types of SDLC models?
    1. Waterfall Model.
    2. Spiral Model.
    3. V Model.
    4. Prototype Model.
    5. Agile Model.

6. What is waterfall model?
    It is a step by step procedure to develop a software.
    It follows linear and sequential approach. It is one of the oldest and simplest model.
    Advantage:
        Requirement and design doesn't change.
        Quality of software is good.
    Disadvantage:
        Backtracking is not possible. Example: Requirement can not be changed once design stage is complete.
        Developers are involved in the testing.
    Applications:
        Used in small applications like Alarm, Calander, Notes, etc..

7. What is spiral model?
    It is a step by step procedure to develop a software.
    In spiral model the software is developed module by module.
    Once requirement collection is completed for module A then we will go to design for module A. Once design is completed in Module A we go for coding and after coding we go  testing for Module A. After everything is perfect we can go for the process of Module B. Otherwise if there are any minor changes it will be fixed with the cycle of Module B. Otherwise if there are any major changes the process of Module B needs to wait and major changes need to fixed again with the cycle after it is fixed we can move to Module B.
    Advantages:
        Requirement changes are allowed after each cycle.
        New requirements can be added.
    Disadvantage:
        Same process of each and every cycle's module.
        Developers are involved in the testing.
    Applications:
        Project which the requirement are based on stages.

8. What is V model?
    It is a step by step procedure to develop a software.
    It is also called Verification and Validation Model.
    Verification:
        It is a process of reviewing CRS, SRS, Design, Coding, Testing, Testcase and related documents.
        Verification process is involved with reviewing documents.
    Validation:
        It is an actual testing done after the software is developed.
        Here we execute the test cases.
    Here both testers and developers are involved parallely.
    Verification is done to prevent the defect. Validation is done to identify the defect.

    Stages:
        CRS <==> Acceptance Testing    [ Review CRS, Write Acceptance Testing Plans, Case ]
	    SRS <==> System Testing    [ Review SRS based on CRS, Write System Testing Plans, Cases ]
	    HLD <==> Integration Testing [ Review HLD based on SRS, Write Integration Testing Plans, Cases ]
	    LLD <==> Functionality Testing [ Review LLD based on HLD, Write Functionality Testing Plans, Cases ]
	    Coding <==> WBT	
	Here CRS, SRS, HLD, LLD, Coding, WBT comes under Verification Process.
	Functionality Testing, Integration Testing, System Testing, Acceptance Testing comes under Validation Process.
    Advantages:
        Testing is started from the initial stages.
        Software quality is good.
    Disadvantages:
        Initial investment and documentations are high.
    Applications:
        Complex projects.
        Huge or long term projects.

9. What is prototype model?
    It is a step by step procedure to develop a software.
    If a customer is new to business or not aware of the requirement or new to the domain we can use prototype model.
    Here we can create a prototype of the software before building the full software and show it to the client, if the client accepts the design we can start to develop the software.
    Advantage:
        Software quality is good.
        Requirement changes are allowed.
    Disadvantages:
        Time taken and investment is high.
        Software delay may occurs.
    Application:
        Customer is new to business or domain.

10. What is agile model?
    It is a step by step procedure to develop a software.
    It is a process of customer satisfaction through quick delivery of working piece of software.
    Advantages:
        Requirement can be changed anytime.
        Release should be short.
        Simple model to follow.
    Disadvantages:
        Less scope for desing and documentation.
        For agile experienced resource are required.
    Agile testing:
        Testing the software by the principles of agile.
            1. Scrum Model.
            2. Extreme Programming.
            3. Future driven developemnt/ Test driven development.
            4. Crystal clear.
            5. Lean & Kanban
            6. ASDM [Adophile Software Developement Method]
            7. DSDM [Dynamic Software Developement Method]
    SCRUM model:
        It is a step by step procedure or framework which helps teams to work together.
        Release:
            Combination of sprint is called release.
        Epic:
            Complete set of requirement is called epic.
        Story:
            Stories are feature or module of the epic.
            One epic contain multiple stories.
        Story point:
            Rough estimation given by developer to develop the story and the tester to test the story.
        Sprint:
            It is an actual time spent by the developers to develop and testers to test the stories.
        Product backlog:
            Here we prioritize which story to develop in the current sprint.
        Sprint backlog:
            List of stories and tasks which must be delivered within the sprint.
        Burn down chart:
            Total amount of work remaining.
            Pictorial representation of work left vs time.
        Story board:
            Board contains list of pending tasks, in progress or completed tasks.
        Chicken:
            People who bring the project to the company.
        Hotfix:
            Quick and urgent software update to address the critical bug.
            Minor defect(Patch): 3 Hours.
            Major defect(Re-Spin): 1 Day.
        Fishbone technique:
            Entire team will meet and discuss about the root cause of the defect.
    SCRUM meeting types:
        1. Sprint planning meeting: First day of every sprint BA will explain the entire team about the project. Explain how each and every story would work to the team.
        2. Daily standup meeting: This will held on daily basis upto 10-15 minutes discuss about what we did yesterday and today's work.
        3. Sprint retrospective meeting: Last day of every sprint discuss about what went well and what didn't went well and what are the plans.
        4. Sprint review meeting: Few weeks before release or sprint the team will discuss about the pending stories which are not included in the sprint and prioritize it.

11. What is software testing?
    After the software is developed the testing team will test the software before giving it to the client there maybe chance the software may have defect. The process of finding the defect in the software is called software testing.
    It has 2 types:
        1. Manual testing: Testing the software again and again manually to find the defect.
        2. Automation testing: Tester will write the code and run the code automatically test the software and give result as pass or failed.

12. What is BBT?
    Black Box Testing is the process of testing the functionality of an application against customer requirements.
    1. Functional testing.
    2. Integration testing.
    3. System testing.
    4. Acceptance testing.
    5. Smoke testing.
    6. Adhoc testing.
    7. Performance testing.
    8. Globalization testing.
    9. Usability testing.
    10. Exploratory testing.
    11. Compatability testing.
    12. Regression testing.
    13. Comparison testing.
    14. Accessibility testing.
    15. Yellow box testing.
    16. Reliability testing.
    17. Recovery testing.

13. What is functional testing?
    Testing each and every components of an applications thoroughly against CRS.
    First need to do positive testing and then we should go to negative testing. If software is not working for valid data no need to check negative data report and wait for the updated new module.
    Always do optimized testing (No duplicates).

14. What is integration testing?
    Testing the dataflow or interface between 2 or more modules.
    1. Incremental integration testing:
        Incrementally adding module and test the dataflow between the modules.
        1. Top-Down approach:
            The incrementally added module is the child module of the previous module.
        2. Bottom-Up approach:
            The incrementally added module is the parent module of the previous module.
    2. Non incremental integration testing:
        It is also called as Big Bang method. In this we combine all modules and test the dataflow between modules. Here we don't know which is parent module and which is child module.
    
15. What is system testing?
    It is an end to end testing done to find the test environment is similar to the production environment.
    Navigating to all modules and test the end feature is working as expected or not.
    System testing is done after functional and integration testing. When the minimum required module is done.

16. What is acceptance testing?
    It is an end to end testing done at sitting in the customer place while applying real time business scenarios to the software and check whether the software is capable.
    Acceptance testing is done after the software is developed and tested by the developers.

17. What is smoke testing?
    It is a process of testing the critical features of the software before thorough testing.
    Smoke testing is done before functional, integration and system testing.
    By this the test engineer will find any blocker defect in early stages and the developer have enough time to fix it.

18. What is adhoc testing?
    It is a process of testing the software without looking into requirement.
    1. Buddy testing: TE sit with developer and come up with scenarios.
    2. Pair testing: TE sit with another TE and come up with scenarios.
    3. Monkey testing: TE test the software without applying any logic.

19. What is usability testing?
    It is a process of testing the user friendliness of the software.
    1. Yellow box testing: Testing the warning messages of the software.
    2. GUI testing: Testing the visual elements and user interaction of the software.
    3. Accessibility testing: Testing the user friendliness of the software for physically challanged POV.

20. What is recovery testing?
    It is a process of testing the software how well it recover from the crash or disaster.