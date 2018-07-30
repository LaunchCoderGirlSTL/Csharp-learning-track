# Lesson 18: Web APIs
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=4YnMObErB_3605244527) introducing the weather project from the Windows 10 Development for Absolute Beginners course.  **Make sure you code along with Bob during this series.  See Assignment 18-1**
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=pmgqRcErB_1605244527) for the setting up and working with the weather API for the weather project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=dreKHhErB_3805244527) accessing the GPS location in the weather project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=sIICkjErB_2005244527) to test location in the phone emulator
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=bp51nlErB_2905244527) to update the weather project tile with periodic notifications.  You do not need to create the web services that Bob does in this video.  We have made versions of them available at [https://cgtime.azurewebsites.net/](https://cgtime.azurewebsites.net/) and [https://cgweather.azurewebsites.net/](https://cgweather.azurewebsites.net/)
* Watch [this video](https://channel9.msdn.com/Series/A-Developers-Guide-to-Windows-10/20) from Channel 9 that goes more in depth on Tiles and Notifications
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=nbvqloErB_3205244527) to add finishing touches to the weather project
* Complete [this hands-on lab](https://github.com/Windows-Readiness/WinDevHOLs/blob/master/03. Live Tiles and Notifications/03. Lab. Live Tiles and Notifications.pdf) to build live tiles and toast notifications

## Learning Objectives
* Integrate your apps with web APIs
* Convert web data (JSON) into C# classes
* Add geolocation services to your applications
* Create Live Tiles for your application
* Add toast notifications to your application

## Assignments
* Take the [Setup and Working with the Weather API Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=pmgqRcErB_1605244527)
* Take the [Accessing the GPS Location Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=dreKHhErB_3805244527)
* Take the [Testing Location in the Phone Emulator Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=YnZuRlErB_8205244527)
* Take the [Updating the Tile with Periodic Notifications Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=bp51nlErB_2905244527)
* Take the [Finishing Touches Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=nbvqloErB_3205244527)
* Code along with Bob to create the Weather application.  Again, please be sure to comment your code.  Upload your program to a new repository called CG 18-1
* Extend the weather application to provide a 5-day forecast.  Upload your program to a new repository called CG 18-2
* Extend the weather application to show a badge when it is too hot, too cold or raining.  Upload your program to a new repository called CG 18-3
* Extend the weather application to pop up a toast notification when it is too hot, too cold or raining.  Upload your program to a new repository called CG 18-4
* Create a new application that converts using [The Free Currency Converter API](https://free.currencyconverterapi.com/). Upload your program to a new repository called CG 18-5

## Resources
* [Open Weather Map](https://openweathermap.org/) – An API for adding weather forecasts to your application
* [JSON to C#](http://json2csharp.com/) - An online converter that will generate C# classes from JSON data
* [Json.NET](https://www.newtonsoft.com/json) – A very popular NuGet library for working with JSON formatted data
* [RestSharp](http://restsharp.org/) – A NuGet library that makes it easier to work with REST based APIs
* [ProgrammableWeb](https://www.programmableweb.com/apis/directory) – A large list of APIs available on the web.  This might give you some ideas for your own projects
* [Adaptive Tile Templates](https://blogs.msdn.microsoft.com/tiles_and_toasts/2015/06/30/adaptive-tile-templates-schema-and-documentation/) - This article documents Adaptive Tile Templates which is a replacement for the older templates that Bob is using
* [Universal Tile Maker](https://github.com/Aftnet/UniversalTileMaker) - This script creates all the 43 PNG images that are used for Tile assets in a Universal Windows 10 application. It is optimized to generate transparent tiles which will use the system's accent color as default and that look consistent with Microsoft's own apps
* [Live Tiles, Notifications, and Action Center](https://mva.microsoft.com/en-US/training-courses/a-developers-guide-to-windows-10-12618?l=6goHMdqRB_4505095281) – A 1-hour video that goes more in depth on live tiles and notifications

## Errata
* **Setup and Working with the Weather API:** You will notice that APIs calls has been reduced dramatically in the free tier from 1200 calls per minute to 60.  While this does not affect the class it’s important to note that when working with APIs things can change over time.  At the time of the recording the open weather API was on version 2.5 and currently it is still on version 2.5.  Existing calls to the API should still be the same, but more API endpoints are now available.
* **Testing Location in the Phone Emulator:** We are skipping mobile development on Windows 10 in this course because Microsoft has discontinued it.  But you can still use the mobile emulator like Bob is doing to test Geolocation.  You can also test different location in Windows by opening Settings and searching for Location privacy settings.  On this screen you can turn location to Off and set a default location of your choosing.  Be sure to change it back when you are done testing your apps this way.  Unfortunately, there is no Geolocation emulation in the Windows Simulator.
* **Updating the Tile with Periodic Notifications:** The template catalog Bob uses has been deprecated.  It has been replaced with Adaptive Tile Templates shown in the following lessons.