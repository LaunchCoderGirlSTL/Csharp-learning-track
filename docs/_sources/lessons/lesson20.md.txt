# Lesson 20: Master Detail Layout
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=G6i9DBDrB_4505632527) introducing the hero explorer project from the Windows 10 Development for Absolute Beginners course.  **Make sure you code along with Bob during this series.  See Assignment 20-1**
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=SmtFaBDrB_4805632527) on accessing the Marvel Web API from the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=GP9hzBDrB_9405632527) on creating an MD5 hash and calling the API from the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=PpceVCDrB_7005632527) on databinding and navigating the object graph in the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=M9Mm3CDrB_3305632527) displaying character details in the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=E08aQDDrB_9605632527) displaying comic books for character in the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=NSIOnDDrB_8405632527) displaying comic book details in the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=nXRVHFDrB_3305632527) to add an adaptive layout and perform UI cleanup on the hero explorer project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=R6dbeFDrB_405632527) to add Cortana integration to the hero explorer project
* Complete [this hands-on lab](https://github.com/Windows-Readiness/WinDevHOLs/blob/master/06A Speech Commands/06. Lab A.  Launching Apps with Speech Commands.pdf) to create a voice command definition file and add commands to launch your app and customize its appearance

## Learning Objectives
* Work with 3rd party API documentation
* Encrypt data to protect it from unauthorized viewing
* Work with APIs that require authentication
* Understand rate limits and how to work with them
* Layout a view in a traditional master list on the left with details on the right
* Add a voice interface to your application through the Cortana digital assistance

## Assignments
* Take the [Accessing the Marvel Web API Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=SmtFaBDrB_4805632527)
* Take the [Creating an MD5 Hash and Calling the API Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=GP9hzBDrB_9405632527)
* Take the [DataBinding and Navigating Through the Object Graph Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=PpceVCDrB_7005632527)
* Take the [Displaying Character Details Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=M9Mm3CDrB_3305632527)
* Take the [Displaying Comic Books for a Character Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=E08aQDDrB_9605632527)
* Take the [Displaying Comic Book Details Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=NSIOnDDrB_8405632527)
* Take the [Adding an Adaptive Layout and UI Cleanup Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=nXRVHFDrB_3305632527)
* Take the [Cortana Integration Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=R6dbeFDrB_405632527)
* Code along with Bob to create the Hero Explorer application.  Again, please be sure to comment your code.  Upload your program to a new repository called CG 20-1
* Extend Hero Explorer by caching all results that come back from the API.  You will do this by saving the JSON data into a Dictionary with the key being the URL of the request.  When a user makes the exact same request used the cached JSON data to populate the return results.  You will not want to cache the request that returns a list of random characters or you will always get the same results.  Upload your program to a new repository called CG 20-2
* Extend Hero Explorer with the ability to search for characters instead of just getting a random result set.  Upload your program to a new repository called CG 20-3

## Resources
* [Cortana](https://developer.microsoft.com/en-us/cortana) – The Microsoft development portal for Cortana.
* [Monkey Cache](https://montemagno.com/data-caching-made-simple-with-monkey-cache/) - A library to keep a local copy of cloud data on your computer.
