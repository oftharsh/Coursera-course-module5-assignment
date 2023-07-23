# Module 5 Coding Assignment
**Coursera course: HTML, CSS, and Javascript for Web Developers**

Last assignment and you are DONE!

Time to complete: About 30 minutes.

Ask questions in Discussions if you get stuck! We are all learning, and going through getting stuck and then unstuck (even with someone's help) can be a very valuable learning experience!

**Summary**: In this assignment, we are going to have a bit of fun with our built restaurant web application. The front page of our web app contains 3 clickable tiles: Menu, Specials, and Map. If you click on the Specials tile, you will be taken to a single category page where all the menu items that belong to the Specials menu category will be shown. Your task in this assignment is to alter this behavior such that when the user clicks on the Specials tile, the web app takes the user to a random single category menu page, listing menu items in the category, be it "Lunch", "Dinner", "Sushi", etc. That way, any random category can become the Specials! What fun! (not! :-) )

In order to accomplish this, we need to change the home HTML snippet and, besides pulling it dynamically from the server, also insert a random category short_name into the function call of the following code. Previously, the code to send the user to the "Specials" category was this:

`<a href="#" onclick="$dc.loadMenuItems('SP');">`
For this assignment, we changed this line to prepare it for a random category short_name to be this:

`<a href="#" onclick="$dc.loadMenuItems({{randomCategoryShortName}});">`
Here is what you will need to complete the assignment:

You are NOT allowed to change the `home-snippet.html` file. Any adjustments to the value of randomCategoryShortName property needs to be done in Javascript code.

There are 4-5 fairly simple steps to implement the required functionality.

1. Open up `js/script.js` file.

2. Find TODO: STEP 0, and follow the instructions until you are done with TODO: STEP 4.

   If you've watched the lectures, the code should be very familiar to you.

3. Once you are done, verify that the desired functionality is working correctly. Use Browser Sync or deploy your solution to GitHub pages.

4. Load the home page in the browser.
-  Click on the Specials tile. A single page category with a list of menu items for some category should appear.
-  Click on the restaurant logo to go back to the home page.
-  Click on the Specials tile again. Most likely, a different single page category page will be shown.

5. Repeat this several times to make sure that most of the time you see a different single category page.

That's it!
