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

## Solution One
For this solution, I decided to use the embed tag instead of iframes. The embed tag is completely cross-platform compatible. It allows you to take all types of external files and, well, embed them into an existing HTML file, with a few specifications needed.  In this case, I needed to specify the source, width, height, and type of file being embedded.  Some of the JavaScript completely broke upon adding these files because of the way attributes were formatted in the iframe, so I rewrote some of the DOM manipulation in a very WET manner I'm not so proud of. However, the functionality worked and the site looks and functions exactly as it did.

As far as the researching process went with this, I started by looking up exactly what an iframe did, and found that it simply allows you to embed a file within an HTML file, very similarly to the embed tag.  From there, I looked up viable alternatives, and found embed, the object tag, and web components to be the most useful in this scenario.  After learning more about embed and object, I decided to go with embed and implement it in this site.  Plugging it into the HTML was fairly simple, beyond the fact that the JavaScript stopped working.  I had to do a little refreshing of my DOM manipulation skills to figure out how to get the popups to show up when the topics were clicked.  Again, the JavaScript I wrote was definitely not the most succinct, but it got the job done in this case.