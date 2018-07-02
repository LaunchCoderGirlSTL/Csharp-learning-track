# Lesson 9: Assemblies and Collections
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Ry6jz0QIC_5706218949) about Creating and Adding References to Assemblies from the C# for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=XIMI21QIC_2406218949) on Working with Collections from the C# for Absolute Beginners course
* Work through [this guide](https://docs.microsoft.com/en-us/dotnet/csharp/quick-starts/list-collection) on Collections in C#

## Learning Objectives
* Add references to other third-party code using NuGet
* Create a class library project for sharing code
* Add a reference to a class library from another solution
* Add a reference to a class library from the same solution
* Set the startup project for debugging when a solution has multiple projects
* List the benefits of lists over arrays
* Explain the difference between an ArrayList and a List
* Explain what Genetics are
* Explain what a Dictionary is
* Use an ArrayList to store a list of objects
* Use a List to store a list of objects
* Use a Dictionary to store a list of objects
* Initialize properties while declaring a new class without using a constructor

## In-class Work
Here is a video of what we did in class:

## Assignments
* Take the [Creating and Adding References to Assemblies Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Ry6jz0QIC_5706218949) and upload a screenshot of your score into Canvas.
* Take the [Working with Collections Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=XIMI21QIC_2406218949) and upload a screenshot of your score into Canvas.
* Write a static method to find the sum of all the even numbers in a list. This method should be in a class called `NumberCruncher` in its own class library called `NumberUtility`. Within your console project, create a list with at least 10 integers and call your method on the list. Upload your program to a new repository called CG 9-1
* Write a static method to print out each word in a list that has exactly 5 letters. This method should be in a class called `LetterCruncher` in its own class library called `LetterUtility`. Within your console project, create a list with at least 10 strings and call your method on the list. Upload your program to a new repository called CG 9-2
* Update the program you just wrote for `LetterCruncher` and add a second overloaded method that takes the number of letters to match instead of being fixed to 5 letters. Also, this version of the method should not print out each word, but instead return a list of only those words. The console program should take this list and print each value to the console. Upload your program to a new repository called CG 9-3
* Create a program that asks the user to enter the name of every student in a class and their ID (as integers). When they are done entering, ask the user to search for a student. Use a foreach loop to find the student. If there is a matching ID or name, print it, otherwise print a message that the student is not in the class. Keep this loop going until the student types exit or quit. Upload your program to a new repository called CG 9-4

## Errata
* **Creating and Adding References to Assemblies**: You add references to a .NET Core project from Dependencies instead of References in the project structure. You no longer add references to other parts of the .NET Framework like Bob does in his video. Those are all already located in the dependencies folder and your appplication will only use the ones you reference with `using` statements.
* **Creating and Adding References to Assemblies**: When you open the NuGet Package Manager, you will see a package installed called `Microsoft.NETCore.App`. Even Microsoft's own .NET Core library updates are now delivered through NuGet.
* **Creating and Adding References to Assemblies**: When creating or adding a class library project, be sure to choose `Class Library (.NET Core)`.
