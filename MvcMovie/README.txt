2024-05-16
23456
Viralkumar Labhubhai Dobariya

Part 1
2024-05-16
1410 UTC

Created a project name MVC Movies and added a controller

2024-05-16
1420 UTC
Ran the program, Confirmed the default works:
https://localhost:[Port]/
Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME
Created README.in the MVC Movies
Was able to confirm the default page

2024-05-16
1435 UTC
I confirmed Part1 of the tutorial is complete, The started with part2

Part 2
2024-05-16
1455 UTC

Commented the default index method which is returning to class view()
Then added new index method and changed the content to "This is my default action..."
Was running when i ran the program

https://localhost:[Port]/Helloworld
2024-05-16
1520  UTC
Added another method called welcome with the content of "This is the Welcome action method..."
Confirmed it was running

https://localhost:\[Port]/Helloworld/welcome

2024-05-16
15336 UTC
Change the Welcome method to include two parameters(name,numtimes)
Ran the program, Confirmed the changes works:

https://localhost:[Port]/helloworld/welcome?name=Aditya&numTimes=6

Part 3

2024-05-23
1434 UTC
Add a view successful with https://localhost:7166/HelloWorld

2024-05-23
1440 UTC
Change the tital, footer, and menu link using "Layout.cshtml" file

I veryfy this process using https://localhost:7166/Home/Privacy

1450 UTC


Passing Data from the Controller

And then after I able to open this link https://localhost:7166/HelloWorld/Welcome?name=Rick&num I am successful run this link.

In HellowolrdController.cs change Welcome method to Which massage I display and how many time I And then after I create new file in ViewData. Which is Wlcome.cshtml


Part 4

0130 UTC

Added the Index in the helloworldcontroller

0135 UTC

Created a razer file in Views/HelloWorld/Index.cshtml added the CSHTML which showed the index
webpage.

0145 UTC

Change the title, footer, and menu in Views/Shared/_Layout.cshtml added the CSS code.
so than when we click on privacy it created the new page.

0155 UTC

In HelloWorldController.cs, change the Welcome method to add a Message 
and NumTimes value to the ViewData dictionary.

0205 UTC

now that is opened https://localhost:7125/HelloWorld/Welcome?name=Aditya&numtimes=4
it showd my name 4 times. and you can the numtimes to 10 and it will show your name 10 times.

Part 5
2024-05-23
1425 UTC
Check the data is available in SQL Server Express LocalDB
And here found data of the movies which I add through the Index code

2024-05-23
1435 UTC
Add SeedData on the Model Folder replacing with code

2024-05-23
1443 UTC
After Adding Seed I add the seed initializer
And Open link with  https://localhost:7125/Movies

Part 6
2024-05-23
1450 UTC
In this section first I genretate link for Edit, Details, and Delete .

2024-05-23
1510 UTC
Here I have request for for POST processing
When user Input any wrong details or any details input but not match with field shows error massage.



Part 7
2024-05-30
1413 UTC
In these part I updated the index method inside MoviesController.cs

2024-05-30
1420 UTC
The var movies in _context.Movie creates the LINQ query.

2024-05-30
1433 UTC
After I navigated inside index file and appended the query string.

2024-05-30
1446 UTC
I changed all parameter to ID and changes all the occurences of searchstring.
I added the command to add search by genre.

2024-05-30
1455 UTC
Again i updated the Index.cshtml file for adding search by genre to index view.
I examined by running it and yes it works.

Part 8
2024-05-30
1507 UTC
In these part i updated the movie.cs file with given code.

2024-05-30
1515 UTC
After that I added Rating action method.

2024-05-30
1520 UTC
Again i edited the Index.cshtml file with rating field.
    
In the powershell package manager i added migration rating and then updated those database.

20240530171455_Rating

Part 9