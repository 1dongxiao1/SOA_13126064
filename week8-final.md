Why testing? Two primary purposes is to demonstrate quality or proper behavior and to detect and fix problems. I will take Sogou Search, a android app, as the object of my design.   

First of all, I will finish a test plan to document test objectives, test requirements, test designs, and other project management information. It defines development and testing deliverables and secure commitment and resources for the test effort .         

As the first section of the test plan, testing scope must be confirmed. What is being tested and what is the overall objective? For this moment the answer is Sogou Search and the overall objective is to confirm its functions and use-friendliness. The main functions of Sogou Search can be divided into two parts, which is search part and cards part. Both function testing and performance testing are needed.

* Functional testing.         

I will take black-box testing first as it verifies the correct handling of the external functions provided or supported by the software, or whether the observed behavior conforms to user expectations or product specifications. It is a type of testing in which the functionality of the software is tested without any reference to the internal design, code, or algorithm used in the program. The test cases are generally built around the requirements and specifications of the software application. During this step, there are several methods can be used, such as Equivalence partitioning, Marginal analysis, Error guessing method , Cause and effect diagram and so on.  

  White-box test is also necessary. White-box teasing is a method of testing software that tests internal structures or workings of an application, as opposed to its functionality. In white-box testing an internal perspective of the system, as well as programming skills, are used to design test cases. The tester chooses inputs to exercise paths through the code and determine the appropriate outputs. This is analogous to testing nodes in a circuit. While white-box testing can be applied at the unit, integration and system levels of the software testing process, it is usually done at the unit level. It can test paths within a unit, paths between units during integration, and between subsystems during a system–level test.             
  
Software testing systems usually run through a spectrum from "pure" unit tests through to fully integrated systems tests. We've described low level unit tests above. Integrated testing typically involves some sort of script that simulates user actions and then verifies that the result matches what's expected. This sort of "end to end" test verifies that all parts of the system are working correctly.          

A subsystem test verifies that two or more units of code are interacting correctly to produce the desired result. In the simplest case, a subsystem test can be created simply by replacing mock objects with real objects and running unit tests on the top level module.          

Integrated testing involves recording a user's interaction with the system into a script that can be replayed. The testing framework then compares the system's response with the expected response and passes or fails the test.

* Performance testing.       

No matter how many functional tests you’ve run, there’s really only one way to know if your software can handle the actual demands of your end users and that is through performance testing. Performance testing determine the responsiveness, throughput, reliability, and/or scalability of a system under a given workload. performance testing is commonly conducted to accomplish the following: Assess production readiness, Evaluate against performance criteria, Compare performance characteristics of multiple systems or system configurations, Find the source of performance problems, Support system tuning, Find throughput levels, Determine compliance with performance goals and requirements, Collect other performance-related data to help stakeholders make informed decisions related to the overall quality of the application being tested, Ensure the hardware configuration is suitable for the application’s optimum performance


