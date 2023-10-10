2023-10-10   10:40
I had issues with my project so here is a new fresh one
I Created my AlureSoap Web App tried to run but i saw an "can't reach this page error message"
went back to my MvcMovie README to look for solutions

10:49
Found it!! i was supposed to comment out the ssl port in my properties folder in my launchSettings.json file

10:52
I Have My Welcome Page Running
10:53
I created a Github Repository for my project

11:09
Trying to add the product catalogue link and the About Us link to my page which is adding a controller 

11:28
i added two controllers to my application the About me and the Product Catelogue page
i decided to add a default text to display on my web page with the content that came with the controller page when created just to see if my About me page works properly
 11:29
 MY TEXT WAS HIGHLIGHTED IN RED!!!
 something is wrong somewhere,it says cannot implicitly covert type string with  Microsoft.AspNetCore.Mvc.IActionResult

 11:30
 i changed the function IActionResult to string because my text is in string let see if it works
 IT WORKED!!!

 11:41
Moving to create My views for the links i have created in my Controller so that i can call the controller View method and display some content on my page

11:52
I created my Views For My About Us Page And The Product Catelogue Page To Create Content For My Alure Soap which will ne called as a method in My Controller

11:54
I added some Content in MY About Us page to try if it will be displayed on the About Me page 
YAYYY! It Worked