2024-05-16
Dhariya Bharwaj
13:30 PM 

####Part 1- Get Started
0130 UTC

Created a project name MVC Movies and added a controller

13:45 UTC
Ran the program, Confirmed the default works:

Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME
Created README.in the MVC Movies
Was able to confirm the default page

14:10 UTC
I confirmed Part1 of the tutorial is complete, The started with part2

Part2-Add a Controller

14:30 UTC

Commented the default index method which is returning to class view()
Then added new index method and changed the content to "This is my default action..."
Was running when i ran the program



14:45  UTC
Added another method called welcome with the content of "This is the Welcome action method..."
Confirmed it was running

https://localhost:\[Port]/Helloworld/welcome

14:55 UTC

Change the Welcome method to include two parameters(name,numtimes)
Ran the program, Confirmed the changes works:

https://localhost:[Port]/helloworld/welcome?name=Dhariys&numTimes=3

####Part3-Add a view

15:30 UTC

Added the Index in the helloworldcontroller

15:35 UTC

Created a razer file in Views/HelloWorld/Index.cshtml added the CSHTML which showed the index
webpage.

2024-05-16

01:45 UTC

Change the title, footer, and menu in Views/Shared/_Layout.cshtml added the CSS code.
so than when we click on privacy it created the new page.

01:55 UTC

In HelloWorldController.cs, change the Welcome method to add a Message 
and NumTimes value to the ViewData dictionary.

02:05 UTC

 now that is opened https://localhost:][Port]/HelloWorld/Welcome?name=Dhariya&numtimes=4

 it showd my name 4 times. and you can the numtimes to 10 and it will show your name 10 times.

####Part-4 Add a modal

 02:55 UTC

  added the scafolded the movie page and update the files in nutgets in tools and when i clicked the 
 movieapps link it showed me the database.

 03:15 UTC
 Timestamp
 20240523184636_InitialCreate is the Migrations timeframe

 In the index i created some list of movies with differet columns.

####Part-5 Work with Database

14:00 Configured Database Context in Program.cs

14:03 i added Connection String in appsettings.json

14:05 Created SeedData Class in Models Folder

14:10 Implementd SeedData Initialization Logic

14:13 Modify Program.cs to Call SeedData Initialize

14:16 Verify Seeded Data in Application

14:20 Check Database Records Using SSOX

14:21 Confirmed Application Functionality with Seed Data


####Part-6 Controller action and views

13:30 Added DataAnnotations for "Release Date" and price formatting.

13:32Ensure "Release Date" shows correctly without time.

- Examined the generation of Edit, Details, Delete links in Views/Movies/Index.cshtml.

- Viewed the source in the browser to understand the generated markup.

- Analyzed GET and POST Edit methods in MoviesController.

- Confirmed use of [ValidateAntiForgeryToken] attribute for security.

- Updated Views/Movies/Edit.cshtml to render form elements and handle validation.

- Ran the app, navigated to /Movies, and verified the "Release Date" display.

- Checked functionality of Edit, Details, and Delete actions with correct data formatting.


13:45 UTC
Part-7 Add search
- Update the Index
- Examine the code
- Filtered the Movies Search
- Add the HTTP get request 

14:15 UTC
Part-8 Add Rating Part 
-Review Code in Movie.cs
- Add the Rating Option to required folders
- Update the database

14:45 UTC 
Part-9 Add Validation

- Add validation rules to the movie model
- Update the class which is required for built-in Validation
- Testing the app and fixed the error which I got
- Examine the codes and Follow Professor Instruction regarding github repository.

- 20240530151800_Rating Migration time

2024-06-06

Update Project on Github 

- Create an Account on Github
- add Repository in github account snd made them publci 

Back to Project 
- Update Seeddata.cs file by adding new file name
- Clone the project for uploading on github account 

- Upload the Project on github so that everyone can access
-Here we go 

