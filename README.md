# Party Planner
[Head First C#](http://www.headfirstlabs.com/books//hfcsharp/)

&nbsp;
## 00 Start the project
* In VS, create a Windows Forms Application project.

&nbsp;
## 01 Configure the form
* Set name, text, icon etc.
* Turn off the minimize box and maximize box.
* Add the labels, numericUpDown and checkboxes controls.

&nbsp;
## 02 Create the *DinnerParty* class
* Create the *DinnerParty* class.
* Add the public properties. These properties are set in the constructor and updated by the form, and they're used when calculating the cost.
* Add the constructor. It sets the three properties based on the values passed into it by the form.

&nbsp;
## 03 Create private methods to calculate the intermediate costs
* In the *DinnerParty* class create the *CalculateCostOfDecorations* and *CalculateCostOfBeveragesPerPerson* private methods.

&nbsp;
## 04 Add the read-only Cost property to calculate the cost
* Add a read-only property called *Cost* that calculates the cost of the dinner party. The calculations are private and encapsulated behind the Cost property.

&nbsp;
## 05 Update the form to use the properties
* Use the constructor and the three properties(NumberOfPeople, FancyDecoration, and HealthyOption) to pass information into the object, and the Cost property to calculate the cost.
* The *DisplayDinnerPartyCost* method updates the dinner party cost on the form by accessing the
Cost property every time it updates the form.

&nbsp;
## 06 Add a tab control
* Add a tab control, set a tab for the dinner party and another for a birthday party version.
* Copy the dinner party controls to the first tab and adjust the existing code.

&nbsp;
## 07 Add the *BirthdayParty* class
* Create the *BirthdayParty* class.
* Add the public properties. These properties are set in the constructor and updated by the form, and they're used when calculating the cost.
* Add the constructor. It sets the three properties based on the values passed into it by the form.

&nbsp;
## 08 Add private properties to the *BirthdayParty* class
* Add the required private properties to the *BirthdayParty* class.
