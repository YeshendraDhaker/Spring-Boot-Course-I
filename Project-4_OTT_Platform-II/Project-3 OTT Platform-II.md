###### **OTT PLATFORM- I SOLUTION IS ONLY THE BOILER PLATE KIT FOR OTT PLATFORM - II**



**INSTRUCTIONS:**



**Problem Statement:**



In continuation to the Cinemaxify application, now you have to take the user’s choice for plan selection, set them and print the details along with the user plan selection for the specific member.



A new interface, "Plan", along with its implementations, "NormalPlan" and "PremiumPlan", has been introduced to enable the selection of subscription plans for specific user types in the application.



**TASKS**:



1\. The Plan interface features a single method, `getPlanName()`, which retrieves the plan name.



&nbsp;2. Implement the Plan interface and override the getPlanName() method in the below-mentioned classes:



&nbsp;a. NormalPlan



&nbsp;b. PremiumPlan



&nbsp;3. The User interface now includes the method `Plan getUserPlan()`, which returns the plan object.



&nbsp;4. Implement the following changes in the Self and Spouse classes:



&nbsp;a. Add attribute private Plan plan.



&nbsp;b. Create a parameterized constructor like public Self(Plan plan)/ Spouse(Plan plan): It accepts a Plan parameter and assigns it to the class plan attribute.



&nbsp;c. Override the Plan getUserPlan(): It returns the plan attribute.



&nbsp;5. Create the beans for NormalPlan, PremiumPlan and all types of members possible with different Plan types in the applicationContext.xml file as described in the template.



&nbsp;• For example, the self has a premium plan; the spouse has a normal plan.



&nbsp;6. In the main() method, load context from the applicationContext.xml file which is located in "src>main>resources".



&nbsp;7. Create a console application that follows the flow to select a user, choose a plan, store user details, and display them as shown in the output.



&nbsp;8. Test your implementation by running the Main class.

