# Lesson 16: Adaptive Interfaces
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=H7LdtOCrB_1605244527) on Utilizing the VisualStateManager to Create Adaptive Triggers from the Windows 10 Development for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=hc34mQCrB_4005244527) on Working with Adaptive Layout from the Windows 10 Development for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=3zG3ZWCrB_1405244527) on Adaptive Layout with Device Specific Views from the Windows 10 Development for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=w2WF1YCrB_6505244527) on Data Binding to the GridView and ListView Controls from the Windows 10 Development for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=iimAYcCrB_2005244527) on Keeping Data Controls Updated with ObservableCollection from the Windows 10 Development for Absolute Beginners course
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=qp3GVeCrB_6805244527) on Utilizing User Controls as Data Templates from the Windows 10 Development for Absolute Beginners course
* Complete [this hand-on lab](https://github.com/Windows-Readiness/WinDevHOLs/blob/master/01A Hello UWP World/01. Lab A. Hello UWP World.pdf) to use the Universal Windows App Development Tools to build a Hello World app that runs on all Windows 10 devices
* Read [this article](https://blogs.msdn.microsoft.com/johnshews_blog/2015/09/09/a-minimal-mvvm-uwp-app/) and code along to understand how to design an application using the MVVM design pattern.
* Watch and follow along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=d8htEhCrB_9405244527) from the Windows 10 Development for Absolute Beginners course to create a cheat sheet for yourself

## Learning Objectives
* Change your user interface based on the window size
* Utilize Microsoft Blend to style an application
* Use different XAML views for different types of devices
* Add a GridView control to display a list of complex items
* Add a ListView control to display a list of complex items
* Use data binding to read and write data to C# objects
* Use data binding to update the user interface when a C# object changes
* Create your own custom user controls
* Use the MVVM design pattern to create maintainable applications

## Assignments
* Take the [Utilizing the VisualStateManager to Create Adaptive Triggers Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=H7LdtOCrB_1605244527)
* Take the [Working with Adaptive Layout Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=hc34mQCrB_4005244527)
* Take the [Adaptive Layout with Device Specific Views Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=3zG3ZWCrB_1405244527)
* Take the [Data Binding to the GridView and ListView Controls Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=w2WF1YCrB_6505244527)
* Take the [Keeping Data Controls Updated with ObservableCollection Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=iimAYcCrB_2005244527)
* Take the [Utilizing User Controls as Data Templates Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=qp3GVeCrB_6805244527)
* Take the [Cheat Sheet Review: Adaptive Layout, Data Binding Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=d8htEhCrB_9405244527)
* Create a program that users a newspaper style layout with banner that goes across the top of the page and three columns of text and images below it.  Use real text and images from your favorite news site.  When the window becomes too narrow, have the columns drop to one.  For this exercise you can put the text directly into the XAML.  Upload your program to a new repository called CG 16-1
* Update the previous program to use data binding to retrieve the data from C# classes instead of doing it directly in the XAML.  Upload your program to a new repository called CG 16-2
* Complete the [Adeptly Adaptive Challenge](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=DtFgZkCrB_7405244527).  Upload your program to a new repository called CG 16-3.  Make sure you don’t watch [Bob’s solution](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=hgN3ykCrB_9005244527) until after you have uploaded your solution.  Do not worry about making sure it is working on mobile.  And remember, that are many solutions to these types of projects.  For example, for the navigation you could use Bob’s hamburger menu or the newer Navigation View control
* Take each of the Adeptly Adaptive Challenge Solution Assessments ([Setup](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=pf4FZoCrB_6305244527), [Data Modeling](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=lomtlsCrB_1005244527), [User Controls](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=mjg89vCrB_3705244527) and [Resizing](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=BqYHM0CrB_6305244527))
* Redo the Adeptly Adaptive Challenge using the MVVM pattern.  This is a good example of something you might be asked to do at work after another developer reviews your code.  Or as your application grows you might decide yourself to put in some more consistent patterns to make the application easier to maintain.  Upload your program to a new repository called CG 16-4

## Resources
* [Creating a UI by using Blend for Visual Studio](https://docs.microsoft.com/en-us/visualstudio/designers/creating-a-ui-by-using-blend-for-visual-studio) – Microsoft documentation on how to use Blend
* [Microsoft Blend for Visual Studio (UWP): Creating a simple animation](https://social.technet.microsoft.com/wiki/contents/articles/32741.microsoft-blend-for-visual-studio-uwp-creating-a-simple-animation.aspx) – Forum post on how to do some basic animation of an airplane firing missiles on a button click
* [Prism](https://github.com/PrismLibrary/Prism) – A powerful MVVM framework
* [WindowsStateTriggers](https://github.com/dotMorten/WindowsStateTriggers) - A collection of custom visual state triggers
* [MVVM Helpers](https://github.com/jamesmontemagno/mvvm-helpers) - Collection of MVVM helper classes for any application

## Errata
* **Working with Adaptive Layout:** The link mentioned in the video does still work at this time, but the images are broken.
* **Adaptive Layout with Device Specific Views:** The link mentioned in the video no longer works.
