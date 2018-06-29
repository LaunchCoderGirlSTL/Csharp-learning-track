# Lesson 12: XAML
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=cWn0dxwqB_4305632527) on Series Introduction from the Windows 10 Development for Absolute Beginners course.
* Complete [this Hello World tutorial](https://docs.microsoft.com/en-us/windows/uwp/get-started/create-a-hello-world-app-xaml-universal) from Microsoft to get your first hands on experience with UWP
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=rXZlwKxqB_2505632527) on Creating Your First Universal Windows Platform App from the Windows 10 Development for Absolute Beginners course.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=qUu7MRxqB_1505632527) on an Overview of Topics Related to Universal Windows Platform App Development from the Windows 10 Development for Absolute Beginners course.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=IXFbpfxqB_905632527), What is XAML?, from the Windows 10 Development for Absolute Beginners course.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=aC9NFjxqB_9105632527) on Understanding Type Converters from the Windows 10 Development for Absolute Beginners course.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=nReXrlxqB_1405632527) on Understanding Default Properties, Complex Properties, and the Property Element Syntax from the Windows 10 Development for Absolute Beginners course.
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=1jTstuxqB_1005632527) on Understanding XAML Schemas and Namespace Declarations from the Windows 10 Development for Absolute Beginners course.

## Learning Objectives
* Create your first UWP application
* Drag and Drop design
* Change control properties through the XAML editor or Properties window
* Add a button control to a page and respond to a click
* Add a text block control to a page to display read-only text
* Understand partial classes and the relationship between a XAML file and its C# code behind file
* Understand the relationship between XML, HTML and XAML
* Run code when a page is loaded
* Understand the relationship between XAML markup and C# objects
* Use Type Converters in XAML
* Set properties on XAML controls
* Set the contents of a default property on a XAML control
* Set the value of a complex property on a XAML control
* Understand schemas in XAML

## In-class Work
Here is a video of what we did in class:

## Assignments
* Enable development mode on your computer under Settings
* Take the [Series Introduction Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=cWn0dxwqB_4305632527) and upload a screenshot of your score into Canvas
* Take the [Creating Your First Universal Windows Platform App Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=rXZlwKxqB_2505632527) and upload a screenshot of your score into Canvas
* Take the [Overview of Topics Related to Universal Windows Platform App Development Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=ucRNgYxqB_4005632527) and upload a screenshot of your score into Canvas
* Take the [What is XAML? Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=IXFbpfxqB_905632527) and upload a screenshot of your score into Canvas
* Take the [Understanding Type Converters Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=nReXrlxqB_1405632527) and upload a screenshot of your score into Canvas
* Take the [Understanding Default Properties, Complex Properties, and the Property Element Syntax Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=OvbQApxqB_5305632527) and upload a screenshot of your score into Canvas
* Take the [Understanding XAML Schemas and Namespace Declarations Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=1jTstuxqB_1005632527) and upload a screenshot of your score into Canvas
* Create a program with a single button. Every time the user clicks the button the color changes. Cycle through a list of 4 or more colors of your choosing. Upload your program to a new repository called CG 12-1
* Create a whack-a-mole game. Put 9 buttons on the page using margins to space them out into a 3-by-3 grid. Put a text block control on the page with their current score, starting at 0. Start a timer on page load that changes one random button to a green background. The user has 3 seconds to click that button or the game ends. When they click the button, increase their score by 1 point. Start the cycle over, but reduce the time given by .1 seconds until they don't click the button in time. Upload your program to a new repository called CG 12-2

## Resources
* [Windows Development Center](https://developer.microsoft.com/en-us/windows) - Microsoft's home for all Windows development
* [Introduction to WPF in Visual Studio](https://docs.microsoft.com/en-us/dotnet/framework/wpf/getting-started/introduction-to-wpf-in-vs) - WPF is the predecessor to UWP and they are very closely related
* [Windows Forms](https://docs.microsoft.com/en-us/dotnet/framework/winforms/getting-started-with-windows-forms) - Windows Forms is the predecessor to WPF and was the first desktop application creation tool for C# and .NET
* [An Introduction to Xamarin Forms](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/get-started/introduction-to-xamarin-forms) - Xamarin Forms uses similar XAML-based technology to create mobile applications for iOS and Android

## Errata
* **Series Introduction**: At the time this course was published, Visual Studio 2015 was the latest version. We are using Visual Studio 17 in this course, which is also capable of building Windows 10 apps.
* **Series Introduction**: We will not be focusing on build applications for phones because Microsoft ended all new development for them. The future of mobile devices is based on full Windows 10 instead of Windows Mobile. Do not worry about the system requirements to run phone emulators.
* **Creating Your First Universal Windows Platform App**: When creating a new application, you should get a popup window asking you to Select the target and minimum platform versions that your UWP application will support. Just choose the default.
* **Creating Your First Universal Windows Platform App**: XAML controls by default will not have an x:Name property. You will need to add it yourself if your control needs a name. They will only need a name if they are being referenced from C# code.
* **Creating Your First Universal Windows Platform App**: Font properties are listed in pixels (px) instead of points (pt). This will keep the FontSize property in the XAML editor and the property window consistent.
* **Creating Your First Universal Windows Platform App**: You can skip the part where Bob runs the code on a phone emulator. We will not be focusing on phones. Just know that the code you are writing will also work on Windows Mobile phones if you really want it to.
