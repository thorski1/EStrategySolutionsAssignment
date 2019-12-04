# ESS Frontend Assignment
Develop two solutions that are cross-platform compatible and delivers the same functionality and styling that exists in the index.html page without the use of an iframe. 

## Getting Started
1. open index.html in an iframe supported browser to be able to see the iframe's content (ex: Chrome)
2. Code away!

## Requirements
* Come up with two solutions to solve this problem. 
* In the included README.md please include a brief explanation as to why each solution was chosen.
* ** The index.html styling should only be dependent on the main.css file. **
* ** The content that was previously rendered by the iframe should not be affected by the main.css file but should still have styling. **
* The solutions should be compatible across all browsers (Edge, IE, Chrome, Firefox, Mobile)


## For each solution please provide a brief explanation below.

## Solution Two
In this solution, instead of using the embed tag, I used the very similar object tag. I checked, first and foremost, on caniuse.com to make sure the object tag would be cross-platform compatible, and it is supported by all browsers. Almost all of the rest of the code is identical to the first solution.  Again, the JavaScript is rewritten in the embedded files and I made a small tweak to the JavaScript in the index.html so that only the homepage file shows up when you open the page.  Otherwise, the two solutions do not vary much.  There is one other way to do this, which involves web components. Almost everything in React, which is the framework I use most often, is broken into components, so the idea of web components makes a lot of sense to me.  However, it is not something I've studied up until this point.  It would be very interesting to take a few days and learn how to use them, and then come back to this project to implement a couple of web components instead of the solutions I came up with. 