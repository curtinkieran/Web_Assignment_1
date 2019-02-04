Code for all pages has been validated on validator.w3.org (HTML) and jigsaw.w3.org/css-validator (CSS).

(CSS validator is telling me to add a "type" attribute with a value of "text/css" to the "link" element for each external-level css styling I have on every
page.  I am not sure if I am doing this right, because I have already entered type="text/css" within the link.)

I took inspiration for the website from my previous employer, "Ottobock".  It is mainly the colour scheme that I have tried to replicate.
w3schools was used extensivey as well as lecture notes for HTML and CSS.

 - Links to my own pages are all contained within the navigation bar.

 - Links to external webpages can be found as image links in the footer (Facebook and Instagram) and also as image links in the resources section.

 - The navigation bar is found in every page, apart from the Entrance/Welcome/Index page (which also has active/hover styling).

 - Ordered list is found in the resources page to list the Prosthetic companies.

 - Embedded Video is on the Prosthetics page.  This example was taken from w3schools.

 - Some CSS3 elements used: 
	border radius (heading, nav bar, profile photos in home page)
	opacity (index)
	text-decoration-style (<h3> home page)
	background-size (external css stylesheet).

 - Some HTML5 elements used: 
	footer (all pages)
	time (locations page, in the table).  I was unable to enter a time duration/time span, so I just used the starting time for time/datetime element
	nav (all pages)
	aside (resources page).

 - CSS positional properties used in home page to position text and logo/profile pictures.  Also in resource section to position image links.

 - HTML 5 tags were used to help my with labeling specific sections on the page.  Nav, Footer, and Aside gave me locations for inputting information,
and made it a lot easier to find and style when using CSS.  Inline styling for text-decoration-style and color were used (in resouces) to override the
 document level style.
	In the index page, I wanted the entire picture to be visible, the opacity css style helped with this.  You can still have the text rendered 
quite strong, while viewing the picture in the background.  I wanted to have a way of making the links in the navigation bar more individual, without
 adding any spacing between them.  The border-radius css style made this possible (as well as .hover).  It also made heading backgroungs and pictures appear
less severe, which I think is appropriate for this "clinical-style" website.

I played around a lot with different positional properties when designing the website. I found the box-model to be particularly helpful
(content, padding, border, margin).  "Developer tools" in google chrome also helped me to overcome positional problems I encountered.
using the mouse to hover over items and inspect specific elements was very useful.
