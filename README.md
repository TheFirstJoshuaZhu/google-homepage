# google-homepage
By Joshua Zhu G11 SC

__________________________________________________________________________________

//What this is//
This is a demonstration of my HTML and CSS skills acquired from the module Project: Google Homepage. Through HTML, CSS, and a lot of time, I have created two re-creations of two different parts of the google search engine. Firstly, there is the google search page, with the main search bar and the google logo, as well as some other UI elements for signing into google, etc. Overall, the UI design for this page was not as challenging as the next. In the google search results page, more time was spent on creating and perfecting the CSS code. Overall, some of the buttons function, like the ones in the google home page, and the majority of links are visuals in the search result page. A aspect I particularly enjoyed doing is the buttons for the All, Image, Video and More tabs, as perfecting them to be exactly like the ones in google is satisfying. 

//Skills demonstrated//
Things that went smoothly: 
Knowing how to set margins, move, scale and have elements react when the user interacts with it was all incorporated in the assignment. Such as small details like having the search bar's shadow change colour when hovered over, as well as the appearing of the "x" tool and the circle shadow that appears when the mouse hovers over the menu element. 

//Skills demonstrated: Challenges and solutions//
1. The scaling issue of the home page: 
When the home page was originally made, it did not scale correctly with the resolution of the window; such that when the window size is changed. After independent testing, I found the solution to the problem. Instead of using x number of pixels as a unit, I must use a % in margins and heights, since the value scales with the resolution of the screen. This then lead me to rewrite all my code since everything I had before was fixed. 

2. The reverse scaling issue on the search result page:
Since I was so used to using percentages for setting the margins of pages, when it came to the search result page where nothing had to move with the changing of the resolution, I found it difficult to make elements to remain stationary again with the re-scaling of the window. It took around a day to figure out a simple solution, where setting the maximum size of the window would stop the elements in the page from moving when scaling. 

3. The svg elements:
When small images and logos are added to the website, I have always found it difficult to scale the images well, as well as have them move correctly in the search page when the window is rescaled (sometimes the images and the text overlap each other's space, resulting in one getting pushed outwards). After independent research, the solution to the problem is to add a set of complicated coordinates detailing the graphic of the image using <svg><path></path></svg>. 


__________________________________________________________________________________

//Special Note 1: Voice tool//
When doing the google home page, I followed FireFox's version of google, which doesn't have a voice tool button on both the search result page nor the home page. Thus I added it in the homepage to demonstrate that I have the skills to create the element. 

//Special Note 2: The "X" cancel button in the google homepage//
Due to browser differences, the "X" cancel button automatically generates in chrome, while it needs to be manually added in as a <svg> in Firefox (or else it won't appear). If there appears to be an overlapping of crosses in the search page when the mouse focuses on the search bar, switching to a Firefox browser would fix the issue. Another file is also presented without the CSS "X" element if it automatically generates. 

