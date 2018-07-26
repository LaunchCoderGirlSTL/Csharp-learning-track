# Lesson 11: Exceptions and Events
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=NUjUyKRIC_2106218949) about Gracefully Handling Exceptions from the C# for Absolute Beginners course
* Watch [this video](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=WZ4BFLRIC_2606218949) on creating automated tests for your code.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=WZ4BFLRIC_2606218949), Understanding Events and Event-Driven Programming, from the C# for Absolute Beginners course
* Watch [this video](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=N9J5qLRIC_7806218949) and enjoy your accomplishment
* Add [this extension](https://marketplace.visualstudio.com/items?itemName=josefpihrt.Roslynator2017) to Visual Studio to help you write better code
* Add [this extension](https://marketplace.visualstudio.com/items?itemName=EWoodruff.VisualStudioSpellCheckerVS2017andLater) to help with silly typos
* Add [this extension](https://marketplace.visualstudio.com/items?itemName=SteveCadwallader.CodeMaid) to Visual Studio to keep your code organized
* Browse [this list](https://marketplace.visualstudio.com/vs) of available extensions for Visual Studio to see all the possibilities. **Warning**: Don't go overboard with extensions at first; they can overload you with too many options.

## Learning Objectives
* Explain the difference between a compile error and a runtime error
* Remember that ALL INPUT IS EVIL
* Use `try catch` statements to handle exceptions
* Use multiple `catch` statements to handle different types of exceptions
* Use `finally` statements to run after an exception
* Write automated tests to prove your code is working
* Identify the three A’s of unit testing: arrange, act and assert
* Understand what Test-Driven Development is
* Listen for an event and execute code
* Stop listening for an event
* Install some useful extensions to Visual Studio to make your life easier

## Assignments
* Take the [Gracefully Handling Exceptions Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=NUjUyKRIC_2106218949)
* Take the [Understanding Events and Event-Driven Programming Assessment](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=WZ4BFLRIC_2606218949)
* Create a basic calculator app that lets the user enter a basic formula like `10 + 4`. If the user enters in any invalid data, catch the error and let the user know their input was bad. This application should be able to do addition, subtraction, division and multiplication. You should also be using a calculator class instead of putting everything in the Program class. Upload your program to a new repository called CG 11-1
* Update your calculator app with a unit testing project.  Create tests that send in valid input and tests that send in bad input.  Upload your program to a new repository called CG 11-2
* Create a basic timer application that lets the user set a timer in minutes, seconds, hours or a combination thereof. Think of it as a command line version of setting a timer through Siri or an Amazon Echo. Try to make it as flexible as possible to all kinds of crazy input command. Make sure to document your program well with comments and create the proper classes and objects. Don't forget your new error handling skills. Upload your program to a new repository call CG 11-3
* Update your timer app with a unit testing project.  Create tests that send in valid input and tests that send in bad input.  Upload your program to a new repository called CG 11-4
* Celebrate your completion of C# Fundamentals!

## Resources
* [Syncfusion Succinctly Series](https://www.syncfusion.com/ebooks) - A huge list of free eBooks aimed at helping you learn new things quickly. Be sure to check out [C#](https://www.syncfusion.com/ebooks/csharp) and [.NET Core](https://www.syncfusion.com/ebooks/net_core_succinctly)
* [Saint Louis .NET User Group](https://www.meetup.com/St-Louis-NET-User-Group/) - There is a local, free monthly meetup of .NET professionals for learning new things and networking with peers
* [dev up](https://devupconf.org/) - A very affordable annual developer conference here in St. Louis that covers a lot of topics on .NET
* [.NET Application Architecture](https://www.microsoft.com/net/learn/architecture) - A deep dive into building professional grade applications with .NET

## Errata
* **Unit Testing Tutorial for C# Developers:** When adding a unit test project for a .NET Core application, choose the MSTest Test Project (.NET Core) option under Visual C# > .NET Core.
* **Unit Testing Tutorial for C# Developers:** You can run or debug a single unit test by right clicking instead the test method selecting Run Tests or Debug Tests from the menu.
