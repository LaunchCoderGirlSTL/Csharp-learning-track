# Lesson 10: LINQ and Switch Statements
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=LhI1HGRIC_8806218949) on Working with LINQ from the C# for Absolute Beginners course
* [Learn](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/implicitly-typed-local-variables) how to declare variables using the `var` keyword
* Complete [this tutorial](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/working-with-linq) on LINQ to gain a better understanding of this powerful feature
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=dHjsrIRIC_1806218949), Enumerations and the Switch Decision Statement, from the C# for Absolute Beginners course
* Read [this article](https://deviq.com/magic-strings/) to understand why hard-coded numbers and strings can lead to problems

## Learning Objectives
* Run LINQ queries using query style syntax
* Run LINQ queries using method style syntax
* Understand Lambda expressions
* Filter a list with LINQ
* Sort a list with LINQ
* Loop through a list with LINQ
* Use aggregate function on lists with LINQ
* Declare variables using the `var` keyword
* Get the type of class that an object is
* Retrieve only some properties from a list using LINQ to a new anonymous type
* Use enumerations to limit input
* Use the switch statement to compare longer lists of possibilities

## Assignments
* Take the [Working with LINQ Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=W04QuwSIC_1306218949)
* Take the [Enumerations and the Switch Decision Statement Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=dHjsrIRIC_1806218949)
* Update your program from the previous class that asked the user to enter the name of every student and their ID. This time, replace the foreach loop with LINQ. Upload your program to a new repository called CG 10-1
* Create a program that contains a Student class. You must track the student's first name, last name, grade (1 - 12), and current GPA (1-4). Store a list of 10 or more fake students in a list. Then, use LINQ to print a list of students with a GPA of 3 or higher that are in the 9th - 12th grade. The list should output their first name, last name, grade and GPA. It should be sorted by highest grade, then highest GPA, then last name, then first name. Upload your program to a new repository called CG 10-2
* Create a program with an enumeration of all students in class' first name. Ask the user to enter their name. Using a Switch statement, print their last name. Upload your program to a new repository called CG 10-3

## Resources
* [101 LINQ Samples](https://code.msdn.microsoft.com/101-LINQ-Samples-3fb9811b) - A large collection of sample code for LINQ

## Errata
* The LINQ and Switch projects that Bob makes available for download are written and compiled for the .NET Framework version 4. As a reminder, we are using .NET Core in class, which is a newer version of .NET. In this case, the code is the same for .NET Framework and .NET Core.
