### Task 8: Laundry Services Hamburger Menu in Mobile 

## Files: 
* index.html
* style.css 
* laundry image 
-----------
 
****CONTENT:****
## Top section:  
* logo,username,navbar as in previous task 7.
* Navbar is hidden for mobile width.
* A new division is used for lists of navbar inside the hamburger button.
* Hamburger button is hidden for the Laptop, Tablet width . 
* When we click on the hamburger button , the menu opens , it takes half width of the page and full height . 
* When we click on the outside of the menu , it lose focus .
* The hamburger button is created using the button tag and the black lines using &#9776; . 
The display of hamburger button and menu list is none by default .
* Inside the mobile media query the dispaly is set to block so now in mobile it is visible, position is absolute .
 * Inside the menu the lists are set in a column one after the other , and also they are in center both vertically and horizontally. 
 * ##### Working of hamburger button : 
 * .hamburger-btn:focus ~ .menu-list: When we click  on the hamburger button, it gains focus. 
 The tilde (~) symbol tells CSS to look at the menu-list that comes after that button and apply the style.
 * .menu-list:hover: When we hover the menu list it gains the :hover state.
 It remains in focus , it does not close until we click outside it.
* .menu-list:focus-within: When we click on anything inside the menu, the menu gets this state.it keeps the menu open while we are trying to click the links inside it.
It remains in focus , it does not close until we click outside it.
* display: flex !important;: When any of the three triggers above happen, this rule is activated. It forces the menu to display as a flexible box (which aligns items nicely in rows or columns) and the !important tag ensures that this rule overrides any default CSS that might be trying to hide the menu.

## Hero Section:

* It contains the heading, paragraph , and a button , and a image.
* It is same as in the previous assignment .

------------------------

###### HOW TO RUN :
 ****Method I**** 
 * Make sure to save index.html , style.css file and the image in the same folder on your computer.
* Double-click on the html file , it will open in your browser. 
* We cannot open the same web page using the local link .
* We can also open the file using any live result extension in our code editor.

****Method II****
 * Upload the html, css, image files on  platforms like github , netlify,etc as a repository.
* Once it is uploaded ,  we can deploy our project using github, vercel, netlify,etc. 
* After the deployment we get the url for our project .
* Using the url ,we can open it on any device.

-----  
Author : Divyanshi Sharma
 -------
 This is the 8th assignment of the Tutedude MERN STACK Development course.
 
 