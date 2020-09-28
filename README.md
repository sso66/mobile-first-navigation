# mobile-first-navigation
## A Responsive Animated CSS Icon Navbar

Watch the [Responsive CSS Navbar](https://youtu.be/biOMz4puGt8) episode on on youtube


> How to build a responsive, animated icon navigation bar using nothing but plain CSS. This project combines a variety of modern CSS features like flexbox, media queries, transitions, and filters to build a unique experience with minimal code?

> - Step 1 - Initial SetupCreate an index.html
> We start with a typical HTML layout - just a navigation bar <nav> element with an unordered list <ul> nested inside.
  
> Create a style.css
> Start by setting some global variables resetting and overriding the body’s defaults.


Step 2 - Customize the Content Scrollbar
The browser’s default scrollbar looks really bad with a fixed vertical navigation bar. Let’s fix that.

Step 3 - Position the Navbar
There are several important CSS positioning concepts happening here:

The .navbar container is fixed to the left side and takes up 100% of the viewport height.
The .navbar-nav is a flex container with it’s children flowing vertically as a column.
Setting margin-top: auto on the last child forces the last icon to the very bottom.
The width of the navbar is expanded on hover.


Step 4 - Animate the Navbar Links
Each nav-link is also a flex container, but flows horizontally as a row. The background and icon colors are animated using using a filter to make them go from gray to their natural pink.
Step 5 - Animate the Logo
The logo features an animated rotating arrow icon. This effect is created with a CSS transform to rotate the icon on hover.

Step 6 - Make the Navbar Responsive
Our final challenge is to make the navbar switch to a fixed bottom bar on smaller screens. Mutually-exclusive media queries are used apply styles based on the screen width. Notice how little code is needed to reposition the navbar for small screens - the power of flexbox is its ability to transform columns to rows, or vice-versa.

Go Further
You may have noticed how the navbar can cycle through themes - learn how to dynamically theme your website with a little bit of JS.
