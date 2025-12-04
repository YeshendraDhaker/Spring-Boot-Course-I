**INSTRUCTIONS**



**Problem statement**



Suppose you are a software developer working at a fintech startup called SureTech. You are assigned to create a console Insurance Premium calculator application using Spring Boot and the concept of Inversion of Control.



**Tasks**:



1\. Go to start.spring.io and create a new project.



&nbsp;2. Add the necessary dependencies for the project.



&nbsp;3. Create a customer class with the following attributes:



&nbsp;a. String name



&nbsp;b. Integer age



&nbsp;c. Insurance as a dependency



&nbsp;4. Create an Insurance interface with three methods



&nbsp;a. getInsurancePremium()



&nbsp;b. setInsurenceDetails with three boolean parameters mentioned in point 4



&nbsp;c. getInsuranceName()



&nbsp;5. Create the class HealthInsurac which implements the Insurance interface. Override the interface methods and add the following attributes:



&nbsp;a. isSmoker(boolean)



&nbsp;b. isDrinker(boolean)



&nbsp;c. previousConditions(boolean)



&nbsp;d. insurance(double default = 10000, this is the base premium value).



&nbsp;6. Create the class TermInsurance which implements the Insurance interface. Override the interface methods and add the following attributes:



&nbsp;a. isMarried(boolean)



&nbsp;b. hasChildren(boolean)



&nbsp;c. isSalaried(boolean)



&nbsp;d. insurance(double default = 5000, this is the base premium value).



&nbsp;7. Depending on the conditions of the customer and input, you have to increase the base insurance premium value. Implement this logic in the setInsuranceDetails method based on the condition below:



&nbsp;a. Term Insurence:



&nbsp;1. If salaried or married, increase the premium by 1.5 times the base value.



&nbsp;2. If hasChildren is true, increase the premium by 2 times the base value.



&nbsp;b. Health insurance:



&nbsp;1. If Smoker or Drinker, increase the premium by 1.5 times the base value.



&nbsp;2. If the previous condition exists, increase the premium by 2 times the base value.



&nbsp;8. User Setter method to inject the dependency. Defines the bean definitions for the user, health insurance, and term insurance in XML.



&nbsp;9. Run and test your code.

