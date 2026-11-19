# Inheritance and interfaces

A checklist of concepts to try out.

## Let a class inherit another class
Create a Person class. Let it have Age and Name. Make it able to Jump, Climb and Walk. Sort out typing these properties and methods in a way that satisfy you. 

Create an Athlete class and let it inherit from the Person class. 

## Use the keywords as and is 
Create an object instance of the Athlete class, but set the type for the variable to Person. Check if the variable *is* Athlete and write the result to the Console. Add a property to the Athlete class, give your object instance a value for this property by treating the variable *as* Athlete.

## Let a class inherit from an abstract class
Add the abstract keyword to the Person class definition. Make the necessary adjustments so that the code still compiles. 

## Extract an interface
Open the Person class definition, select the class name and choose to extract an IPerson interface. Include all of the methods but not the properties. Extract it to a separate file. 

## Implement an interface
Remove the inheritance from the Athlete class and make it instead implement the IPerson interface. Make the necessary adjustments so that the code still compiles. 

**Repeat the steps with another class if necessary** 

