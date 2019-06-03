# User Centric Design Project 01  
This project is a fan based website for Australian electro-pop band Empire of the Sun.


## User Stories

1.	As a user, when I click on the biography section, I want to view information on the band so that I can learn about its history and formation
2.	As a user, when I click on the albums, I want to listen to audio of selected albums by the band.
3.	As I user, when I click on the tour dates section, I want to view any past or upcoming live shows with venue and date information.
4.	As a user when, I click on the singles section, I want to be able to view music videos of a selection of the band's singles.
5.	As a user, when I click on the gallery section, I was to view pictures of past live gigs via an image gallery.
6.	As a user, when I click on the sign up section, I want to be able to join the mailing list for ubmitting the form so that I can stay up to date with news, releases and upcoming tour dates.
7.	As a user, I want to be able to view the site across multiple devices.


## Wireframes
Wireframes for the site were created with Balsamiq Cloud. An PNG file is included in the UX folder.

## Design
Empire of the Sun are known for their vibrant and colorful live shows and styling. I used neon colours and cosmic imagery where possible with a modern, contemporary font to give an overall futuristic theme to the project. Ideas for colour schemes and the corresponding hex code values I would need were obtained from [Palleton](http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF).


## Features
### Existing Features
*	Navbar – A seven tab, fixed position navigation bar with neon purple hover action for each link. The links navigate to the corresponding section of the site. For style and design purposes, a medium opacity was employed for the home page which then changes to a solid color once scrolling is actioned. Fixed positioning allows ease of navigation throughout the site at any given time and the change to a solid colour ensures ease of visibility when scrolling over certain text and images.
*	Responsive Navbar – CSS media queries are used to collapse the navigation bar to into a ‘burger’ icon for tablet and mobile devices.
*	Biography Page – a simple section of information on the history and background of the band, taken from Wikipedia.
*	Tour Dates Responsive Table – A table showing tour dates was used and features hover over actions in white or neon purple for either the table head or table row. The table is responsive and collapses the rows to display as blocks once the CSS media query is triggered. This allows for ease of use across multiple devices. An additional ‘overflow-x:auto’ attribute was used on the HTML div section for the table to allow the user to scroll horizontally if necessary. All tour dates and venues are fictional. The code was obtained from CSS Tricks – Responsive Data Tables.
*	Spotify Album Players – Embedded Spotify album players were used via i frames to allow the user to sample tracks from the band’s main three albums. The three players are responsive and collapse to a column view via CSS flex direction once the media query has been triggered.
*	Embedded YouTube Player – An embedded video playlist of the band’s singles was included via an i frame. The player is responsive and resizes for multiple devices.
*	Responsive Modal Gallery – A thumbnail gallery of 8 images showing live images from various performances. Clicking on any of the thumbnails will result in a pop out modal of a larger version of the image. The Javascript code was obtained via W3 Schools website.
*	Mailing List Sign Up – A simple form was included with appropriate placeholders in each field. The submit button is redundant at this stage but could post to a database as a future feature.
*	Social Media Links – Links to the band’s Facebook, Twitter, Instagram and YouTube accounts were included at the end of the site. These open in new windows via target_blank to avoid the user from fully navigating away from the site and to sustain engagement.

## Features Left to Implement
*	Buy Music – Links to the iTunes store could be included to allow users to buy albums or singles by the band.
*	Mailing List – A full mailing list sign up could be implemented to allow users to stay up to date with news, releases and tour date information from the band.
*	Purchase Tour Tickets – Links to external ticket retailers or integration of an API, such as Ticketmaster, could be included to allow for current tour date information and the ability to purchase event tickets.




## Technologies Used
* [HTML5](https://en.wikipedia.org/wiki/HTML5) - For site layout and structure.
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)	- For design and styling of the site.
* [CSS Tricks](https://css-tricks.com/) – For the responsive data table in the Tour Dates section.
* [Google Fonts](https://fonts.google.com/) - 'Sycopate' modern and contempoary style font was used to fit with the styling of the site.
* [Font Awesome](https://fontawesome.com/) - For the use of social media icons in the Sign Up page.
* [Palleton](http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF) - To assist with colour schemes.
* [Javascript](https://en.wikipedia.org/wiki/JavaScript) - For the responsive Navbar, modal gallery and alert box on the Sign Up page once the submit button has been clicked.
* [Spotify](https://www.spotify.com/uk/) - For the embedded album players.
* [YouTube](https://www.youtube.com/) - For the embedded singles playlist of music videos.
* [Balsamiq Cloud](https://www.youtube.com/) - For the site wireframes.
* [GitHub](https://www.github.com) - For version control.


## Testing

* [HTML](https://validator.w3.org/) – W3 schools HTML validator. To check for syntax errors. 
A number of images throughout the site returned the error:  
"An `img` element must have an `alt` attribute, except under certain conditions."  
Amendments were made to each one accordingly by providing suitable alt attributes.  
All links were manually tested to ensure that they point to the correct location.  
External links, for social media etc, will open in a new browser using 'target="_blank"' - these were also tested manually.
* [CSS](https://jigsaw.w3.org/css-validator/) – W3 Schools CSS validator. To check for syntax errors.
The validator returned the following errors:  
Lines 11 , 22, 30 and 49 - Parse errors for `centre centre fixed`. Not neeeded as `background-size` set to `cover`. Removed manually.  
Line 161 - Value Error : `background-color` `none`is not a `background-color value` : none. Inherited value. Removed manually.  
Line 168 - Value Error : `border-style` Too many values or values are not recognized : `solid 2px #000`. `border-style` used in error. Changed to `border` to apply shorthands.  
Line 473 - Value Error : width Missing a semicolon before the property name height. Amended manually.

* [JavaScript](https://developers.google.com/web/tools/chrome-devtools/console/) – console via Chrome developer Tools. To check for any scripting errors. No Javascript errors were found.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/) - To check cross-device compatibility. To trial and error styles and design options in the quickest manner possible. The following devices were tested via the device toolbar:  
Mobiles  
Pixel 2/XL
iPhone 5/SE/6/7/8
iPhone 6/7/8+
iPhone X
Galaxy S5/S9/S9+  
Tablets  
iPad/iPad Pro
* [Responsinator](http://www.responsinator.com/?url=http%3A%2F%2Fstephenjblair.github.io%2Fucd-project) - To further check cross device compatibility.

## Manual Testing

* Navbar 

1. Check all links are active and navigate to the correct sections of the site.
2. Check responsiveness of navbar across all devices. Ensure that burger icon collapses correctly when media quuery is triggered.
3. Ensure `hover` actions are fucntioning across each `li` item.
4. Ensure nav bar stays in fixed position for ease of navigation throughout the site.

* Tour Dates Table

1. Ensure `hover` effects are active.
2. Check responsiveness across all devices and that table is still clearly visible in its intended format.

* Albums Page

1. Ensuring Spotify embedded players load correctly each time.
2. Checking that the players successfully launch the 30 second sample clip for each album when play is pressed.
3. Checking responsiveness across devices. Albums collapse into a single column when the media query is triggered.

* Singles Page

1. Check embedded YouTube player loads correctly, and the link is active.
2. Check responsiveness across devices. Player autosizes when media query is triggered.

* Gallery Page

1. Light box and modal are working correctly when each picture is clicked.
2. All loads as intended and nothing is distorted in any way.
3. Gallery ensures responsiveness across devices by adotping a single column formate when the media query is triggered.

* Sign Up Page

1. Ensure form placeholders are in place.
2. Check that submit button triggers Javascript alertbox.
3. Check that all external social media links are active and open in a new window.
4. Check resposniveness across devices. Form elements collapse into single column when the media query is triggered.

## Cross Browser Testing

Chrome - 80.3% of users - [W3 Schools - April 2019 stats.](https://www.w3schools.com/browsers/default.asp)  Version 74.0.3729.131 - no errors or issues found.  


Firefox - 9.6% of users - [W3 Schools - April 2019 stats.](https://www.w3schools.com/browsers/default.asp) Quantum 67.0 - no errors or issues found.

Safari 3.3% of users - [W3 Schools - April 2019 stats.](https://www.w3schools.com/browsers/default.asp) Version 12 - no errors or issues found.  

## Further Testing
Friends and family were asked to review the website and provide feedback. The response was very positive with people mainly commenting on the modern design and use of colour.

## Deployment

The site is deployed live via GitHub Pages, directly from the master branch, and can be viewed [here](https://stephenjblair.github.io/ucd-project/). To run locally, use `git clone https://github.com/stephenjblair/ucd-project` into a terminal window. To end, use `git remote rm origin`.

## Credits
### Content
*	The text for the biography section was copied from the [Wikipedia](https://en.wikipedia.org/wiki/Empire_of_the_Sun_(band)) entry for Empire of the Sun.  
*	The code for the modal image gallery (lightbox) was taken from the [W3 Schools](https://www.w3schools.com/howto/howto_css_modal_images.asp) website.
*	The code for the responsive table in the tour dates section was taken from [CSS Tricks](https://css-tricks.com/responsive-data-tables/).

## Media
The photos used in this site were obtained from:
*	[Google images](https://images.google.com/)
*	[Pexels](https://www.pexels.com/)
*	[Unsplash](https://unsplash.com/)    

The albums were embedded via [Spotify](https://www.spotify.com/uk) player.

The video singles playlist was embedded via [YouTube](https://www.youtube.com) player.
