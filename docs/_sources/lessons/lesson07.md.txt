# Lesson 7: Classes
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=LK8n0uQIC_306218949) about Understanding Classes from the C# for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=ymM4awQIC_5206218949), More About Classes and Methods, from the C# for Absolute Beginners course

## Learning Objectives
* Understand the difference between a class and an object
* Define your own custom class
* Create an instance or object from that class
* Add properties to classes
* Add methods to classes

## In-class Work
Here is a video of what we did in class:

## Assignments
* Take the [Understanding Classes Assessment]() and upload a screenshot of your score into Canvas
* Take the [More About Classes and Methods Assessment]() and upload a screenshot of your score into Canvas
* Pick one or more of the following groups of classes, and diagram your design for each (including methods and properties). Be sure to use lines and arrows to indicate inheritance relationships, and to include data and behavior that somebody using your classes would likely want.
   * Shape, Square, Rectangle, Circle
   * Computer, Desktop, Laptop, Smartphone
   * Student, GraduateStudent, UndergraduateStudent
* For one of the groups of classes above, implement your design and test it in a Program.cs class
* Consider the group of classes that you designed. Suppose you had a web program that used these classes, and you needed to assign a unique ID to every object created from one of these classes within the application. In other words, each such class should have an Id property, and no two objects created from any of the classes may have the same ID value. Create an abstract class, AbstractEntity, that contains the behavior for assigning and accessing such a unique ID for each class that extends it. Add this class to your program above, and add AbstractEntity to the class hierarchy in the correct place.
* If you have a project idea or two brewing, try to model out what you think the objects and classes would look like. If you don't have an idea yet, pretend you are going to create a timesheet application where employees can log their work hours, sick time and vacation time and create a model of what that might look like. As a second run at modeling, try to model out the classes and objects you would find in the game of checkers.
* Your homework this week is to create a program that contains a deck of cards and randomly draws one. You will need a Card class to store information about each individual card. The Card class should have a method that gives you the full card name like "2 of Hearts". You will need a Deck class that contains an array of all the cards. The Deck class will need a method to draw a random card. Your main method in the Program class should create a deck object, draw a random card and display the value. If you have extra time, you could see how this program can grow by creating different types of card games like War or Blackjack

## Resources
*
