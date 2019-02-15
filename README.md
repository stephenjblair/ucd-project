# User Centric Design Project 01  
This project is a fan based website for Australian electro-pop band Empire of the Sun.
UX

## User Stories

1.	As a user, when I click on the biography section, I want to view information on the band so that I can learn about its history and formation.
2.	Users can listen to audio of selected albums and singles.
3.	Users can view tour date information.
4.	Users can view music videos from the site.
5.	Users can view pictures of past live shows via an image gallery.
6.	Users can view the site across multiple devices via responsive design.


## Wireframes
Wireframes for mobile, tablet and desktop versions of the site were created with Balsamiq Cloud. These are can be found here. https://balsamiq.cloud/sw7wei7/pjfm2qw/r2278

## Design
Empire of the Sun are known for their vibrant and colorful live shows and styling. I used neon colours and cosmic imagery where possible with a modern, contemporary font to give an overall futuristic theme to the project. Ideas for colour schemes and the corresponding hex code values I would need were obtained from Palleton. Insert link.


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
*	Social Media Links – Links to the band’s Facebook, Twitter, Instagram and YouTube accounts were included at the end of the site. These open in new windows via target blank to avoid the user from fully navigating away from the site and to sustain engagement.

## Features Left to Implement
*	Buy Music – Links to the iTunes store could be included to allow users to buy albums or singles by the band.
*	Mailing List – A full mailing list sign up could be implemented to allow users to stay up to date with news, releases and tour date information from the band.
*	Purchase Tour Tickets – Links to external ticket retailers or integration of an API, such as Ticketmaster, could be included to allow for current tour date information and the ability to purchase event tickets..

## Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
* HTML5 - For site layout and structure.
* CSS3	- For design and styling of the site.
* CSS Tricks – For the responsive data table in the Tour Dates section.
* Google Fonts - 'Sycopate' modern and contempoary style font was used to fit with the styling of the site.
* Font Awesome - For the use of social media icons in the Sign Up page.
* Palleton - To assist with colour schemes.
* Javascript - For the responsive Navbar, modal gallery and alert box on the Sign Up page once the submit button has been clicked.
* jQuery - For DOM manipulation.
* Spotify - For the embedded Spotify players to allow users to sample albums by the band.
* YouTube - For the embedded YouTube playlist of singles.
* Balsamiq Cloud - For Wireframes of the site on both desktop and mobile devices.


## Testing

HTML – W3 schools HTML validator
CSS – W3 Schools CSS validator
JavaScript – console via Chrome Developer Tools
Google Chrome Developer Tools - For quickly identifying elements with issues and be able to trial new code quickly before committing to the project.

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).
In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
•	Different values for environment variables (Heroku Config Vars)?
•	Different configuration files?
•	Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits
### Content
*	The text for the biography section was copied from the Wikipedia entry for Empire of the Sun.  
*	The Javascript code for the modal image gallery (lightbox) was taken from the W3 Schools website.

## Media
The photos used in this site were obtained from:
*	Google images
*	Pexels
*	Unsplash    

The albums were embedded via Spotify player.

The video singles playlist was embedded via YouTube player.
