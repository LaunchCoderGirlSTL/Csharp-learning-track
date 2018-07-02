# Lesson 8: Scope and Namespaces
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=kCLKbyQIC_9106218949), Understanding Scope and Accessibility Modifiers, from the C# for Absolute Beginners course
* Follow [this very short tutorial](https://www.microsoft.com/net/learn/get-started/windows) on how to build and run a program from the command line, without using Visual Studio.
* [This article]() should help clarify what .NET Core is today and what its goals are, how it relates to the Microsoft .NET Framework and the fundamentals of the command-line tooling that you can use to get started with .NET Core.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=JUpuxzQIC_5506218949) on Understanding Namespaces and Working with the .NET Class Library from the C# for Absolute Beginners course. **Note**: This is a place where there have been a lot of implementation changes between the .NET Framework and .NET Core. See the [Errata](../lesson08.html#errata) below
* Read all 10 parts of [this Classes tutorial]() and review what you have already learned and extend your knowledge with inheritance, abstraction and interfaces.

## Learning Objectives
* Understand how curly braces `{ }` affect the lifetime or scope of a variable
* Fields vs properties
* Understand encapsulation
* Use the public and private accessibility modifiers
* Understand what an assembly is
* Inspect the bin directory for your program's output when you build it
* Understand the difference between a debug and release version of your program
* Understand what a Namespace is
* Use using statements to reference namespaces
* How to search Microsoft's documentation from a search engine
* Use the CTRL + .keyboard command to add missing using statements
* Extend a class by inheriting functionality from another class
* Create classes that can't be used until they are extended by another class
* Create interfaces that only define things a class must do

## In-class Work
Here is a video of what we did in class:

## Assignments
* Take the [Understanding Scope and Accessibility Modifiers Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=LK8n0uQIC_306218949) and upload a screenshot of your score into Canvas
* Take the [Understanding Namespaces and Working with the .NET Class Library Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=JUpuxzQIC_5506218949) and upload a screenshot of your score into Canvas
* Extend the code from the last card assignment to play a game of War or Blackjack. Hint: create a Game class. Upload your program to a new repository called CG 8-1
* Write a program where tutors have a credit rate to help a student and students have to transfer credits to a tutor for their services. Start by creating your classes in a People folder. Students and tutors both have a first name and last name. Tutors have a cost. This value can be read or updated by any other class. Tutors earn credit from helping students. This value cannot be accessed by any class other than the Tutor class. Create a method that pays a tutor by increasing their earned credit by their cost. Display a message with the tutor's new credit balance. Use the tutor's name in the message. Students have a starting amount of credit (100). Set this in the student’s constructor. This value should not be able to be accessed by any other class. Students can earn credit, so create a method that adds credit to a student. A student can pay a tutor, so create a method that pays a tutor. If the student does not have enough credit to cover the cost of tutor, display a message. Use the student's name in the message. If the student does have enough credit, reduce the student's current credits based on the tutor cost, pay the tutor and display a success message. Use the tutor's name in the message. Always display a message after the transaction that shows how many credits the student has left.

Now, update your Program Main class with the following flow:
   1. Create a new student
   2. Create a new tutor that costs 50 credits
   3. Create a new tutor that costs 75 credits
   4. Have the student pay tutor 1, this should produce a success message
   5. Have the student pay tutor 2, this should produce a failure message
   6. Give the student 100 more credits
   7. Have the student pay tutor 2, this should produce a success message

Upload your program to a new repository called CG 8-2

## Resources
* [Self-contained .NET Core Applications](https://www.hanselman.com/blog/SelfcontainedNETCoreApplications.aspx) - A nice article on how to wrap your application as an executable so your user does not need to run the dotnet run command
* [Runtime Package Store](https://docs.microsoft.com/en-us/dotnet/core/deploying/runtime-store) - Starting with .NET Core 2.0, it's possible to package against a known set of packages that exist in the target environment

## Errata
* **Understanding Namespaces and Working with the .NET Class Library**: The older versions of the .NET Framework would compile an application into .exe file or executable. .NET Core will compile your program into a .dll file or library instead. This is because .NET Core is cross-platform and will also run on Macintosh and Linux. When you ran your program from the command line in this lesson's tutorial you used the dotnet run command. This command is the executable that is operating system specific instead of your program being compiled for all possible operating systems. This is a very low-level detail that you won't be dealing with much, but that's the way it works.
* **Understanding Namespaces and Working with the .NET Class Library**: The Global Assembly Cache (GAC) Bob mentions does not exist in .NET Core. Instead, all the assemblies you reference in your application are shipped with your application in the same folder. In version 2.0 of .NET Core, something like the GAC was implemented called the Runtime Package Store to save on disk space and improve performance. Again, this is a low-level detail.
* **Understanding Namespaces and Working with the .NET Class Library**: The references folder in .NET Core projects has been replaced with a Dependencies folder.
* **Understanding Namespaces and Working with the .NET Class Library**: .NET Core command line projects start with only one using statement (using System) instead of the 5 that were typical in .NET Framework applications.
* **Understanding Namespaces and Working with the .NET Class Library**: If you try to write a file to the C drive like in Bob's example, it might not work. .NET Core has some additional security restrictions to keep programs from manipulating files it shouldn't. You can get Bob's code to work by simply giving it only a file name like `WriteText.txt`. The file will appear in the bin folder along with your application.
