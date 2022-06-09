# Project-Admin-Dashboard
Create a Dashboard Page 

TakeAways:
---
1. Here is a screenhot of the dashboard page I created, Check it Out Live Here: :airplane: https://babb2000.github.io/Project-Admin-Dashboard/

![Odin Project Dashboard Picture](Side-Bar%20Images/Website_screenshot.png)



2. The purpose of this build was to practice making layouts with a CSS grid. The first thing I started with on this website is researching a little on viewport height and viewport width. It seems like I still don't fully understand this topic too well as I had elements not spanning the full height of the browser window. I think this became an issue when I used absolute positioning to place the header away from certain elements, causing the normal flow of the document to be altered. Will be researching both CSS positioning and viewport.


3. Using CSS grid for the main portion of the website's layout was pretty simple as I didn't have any real complex designs which required divs to overlap one another. One question I had thought was if you could span a grid item across a row and a half? For example `grid-row-start: 1; ` `grid-row-end: 2.5;`
So far I guess you can only span your grid items across the given grid tracks and grid lines. Towards the end of this build, I also learned how to use the grid area. Seems very simple as there are no numbers involved, all you have to do is repeat the grid item variable name with the number of rows or columns you wish to have. Displaying flexbox within grid items or grid containers was also pretty simple, I can say I am getting a lot more comfortable with flexbox.

4. The actual content of the website is a mock dashboard page for full-time Doordash delivery drivers with 5000+ deliveries. The website will provide live order counts from partnered restaurants and fast-food chains that have the top dashers in the area delivering their food. The main map sections are updated hotspots given by actual dashers on the road. Some might think the dasher market will get saturated with people dashing at the same place. However I have 7000+ deliveries in the Columbia MD area myself and see that is usually the same dashers doing the most orders, and during real peak times, there are always plenty of orders to go around.

5. Also wanted to make a portion of the website that show top dasher earnings (with the number of completed deliveries) in different cities. This idea was inspired by the well-known software dev salary website of [levels.fyi](https://www.levels.fyi/?compare=PayPal,Cisco,Yahoo&track=Software%20Engineer)


## Returning Project to add:
1. Fix viewport and height and width on elements
2. Add Javascript Functionality
3. Make the resturant names anchor tags that lead to the address
