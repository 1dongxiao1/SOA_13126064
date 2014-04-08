1.My understanding of formal methods in general 

Formal methods contains formal specifications and formal verification. Formal specification produces an unambiguous set of product specifications so that customer requirements, as well as environmental con- straints and design intentions, are correctly reflected, thus eliminating certain error sources and reducing the chance of accidental fault injections. Formal verification checks the con- formance of software design or code to these formal specifications, thus ensuring that the software is fault-free with respect to its formal specifications. And the basic idea of formal verification is to verify the correctness, or absence of faults, of some given program code or design against its formal specifications. Therefore, the existence of formal specifications is a prerequisite for formal verifications. 

The use of formal methods can be summarized in the following two-step process:
1.Constructing formal specijications. The expected behavior and other properties of the software artifacts are represented in formal models.
2.Performingformal verijications. Formalanalysistechniquesareappliedontheprod- uct components, typically product code or formal designs, to verify their correctness with respect to their formal specifications,or to check for certain properties. 


2.My understanding of model checking in particular

Model checking is such an approach that automatically or algorithmically checks certain properties for some software systems. It combines algorithmic checking of propositions through execution with formal assertions stated as the propositions with respect to software systems modeled as finite-state machines. And the model checker is a software that runs an algorithm to check the validity of the proposition. If it is checked to be true, a proof is said to be produced. Otherwise, a counterexample is given, much like a failed test case that can be analyzed further for defect fixing.
 
