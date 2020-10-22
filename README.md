# Adopt Don't Shop 

The aim of this project is to encourage people to rescue animals, in particular dogs. The project will showcase
stores of rescue animals and the benefits of rescue. The campaign will highlight the problems that can occur when
purchasing dogs from unregulated breeders. There will be a page containing information about where people in Ireland go can to 
rescue a dog or support charities.

## UX 

### User Stories 
1. As a user I want to be able to navigate the site easily.
2. As a user I want to be able to contact the campaign organisers if I have a question.
3. As a user I want to be able to find out where I can go to adopt a dog or support a charity.
4. As a user I want to understand what the websites purpose is immediately. 
5. As a user I want to read stories from others who have rescued, to see if it is for me.

### Site Owner 
1. As a site owner I want the information to be clear and informative.
2. As a site owner I want the content to encourage people to support the campaign purpose. 
3. As a site owner I want the website to be easy and straightforward to use. 

### 1. Strategy 
Project Purpose:

* To encourage users to consider rescue shelters when looking for a pet.
* To educate people about the dangers of buying dogs from unregulated breeders.
* To promote rescue through the showcasing of other rescue stories. 
* To inform people in Ireland where they can go to rescue a pet. 

### 2. Scope 

* I wanted a simple, straightforward UX experience. 
* I needed what I designed to be within the realms of my current knowledge whilst still being a modern, easy to use website.
* Although fictional, I wanted my content to be clear and concise as though it would be used by real world users. 

### 3. Structure

### 4. Skeleton 

### 5. Surface 

## Features 

### Current Features 

* A four page site navigated using the Nav Bar on large device screens, or a hamburger menu on medium and smaller devices. 
* A page displaying multiple cards containing buttons which allow the user to visit external websites. 
* Social media links are easily accessible in the footer for the user. 

### Features Left To Be Implemented

## Technologies Used 

### Languages Used 

* HTML5 
* CSS3 


### Frameworks & Libaries Used

* Bootstrap 4.5 
* Google Fonts
* Font Awesome 
* Git 
* Github 
* Gitpod 
* Github Pages 
* Google Chrome Developer Tools

## Resources 

* YouTube - general resource and specifically for Nav Bar implementation as commented in code. 
* https://www.w3schools.com/ - general reference 
* https://getbootstrap.com/ - documentation for different features. 

## Testing

* Once I had implemented my Nav Bar and Home Page image, I viewed this using Google Chrome Developer Tools to see how the image and nav bar 
appeared on different device sizes. I then physically checked this on an Iphone 8, Iphone 8 Plus, Ipad Pro 11" and a Macbook Air 13".
* In my Wireframes you'll see I initally had a different layout planned for the Home Page, however on inserting content and viewing on multiple
devices I decided to change the grid layout. I again viewed on the above devices and used Google Chrome Developer Tools. 
* When I added the Contact Page, I tested the responsiveness of the site so far on mobile devices by using https://search.google.com/test/mobile-friendly. 
This test returned the result that the site was mobile friendly and that there were no loading issues. 
* I ran each deployed page individually through https://color.a11y.com/ to test that the colour contrast was accessible, this returned excellent results.
* I checked that each Nav Bar item takes the user to the intended page site by clicking and viewing. 
* On the Rescue Centres page I checked that each button opens a new tab and takes the user to the intended external site. When I did this I found an error on the 
last rescue centre, I fixed this by implementing the correct URL in the href. 
* The site was viewed through a Samsung A21s, on this device all pages appeared as they should and links / buttons worked well. 


## Project Barriers And Solutions 

* I ran into issues almost immediately with creating a responsive image on the home page that would work across different devices and wouldn't
contain too much white space. In the end using "img-fluid" gave the best response.

* I implemented a hamburger menu that upon clicking a link within, it would not collapse. I found a solution on Stack Overflow which is credited in my code, 
the solution used is found at this link https://stackoverflow.com/questions/36405991/bootstrap-toggle-menu-on-one-page-site-does-not-uncollapse-when-clicked. 

* I deployed my site and when I did so, the images on my "Rescue Centres" page were not showing and were instead displaying as the "alt" description. 
When I had been using Gitpod to preview, these images had been working fine. I searched through Slack and realised I was using absolute file paths rather than relative.

* When viewing the site on larger device screens, I noticed my page was scrollable horizontally and was leaving unwanted space to the right. I searched 
Stack Overflow and found a solution, the link for the code I used is here and credited in my style.css file. Link: https://stackoverflow.com/questions/17756649/disable-the-horizontal-scroll

* My cards on the "Rescue Centres" page, weren't displaying at the same height on all devices. I added a class of h-100 to the card and this fixed the issue.
I got this information from Stack Overflow, the link is as follows: https://stackoverflow.com/questions/35868756/how-to-make-bootstrap-4-cards-the-same-height-in-card-columns.


## Code Validity 

* HTML - 
* CSS - 

## Version Control 

For version control, Git was used.

## Deployment

* All code was written using Gitpod, an online IDE.
* This code was pushed to Github and stored as a repositorie.
* To deploy I chose the repositorie to be deployed, then I entered the settings of this repo. 
* Within settings I scrolled down until I found the section titled "Pages". 
* In this section I selected "Master" as the branch, then saved.
* Once this is saved a link will be shown with the website deployed onto GitHub pages. 
* If you follow this link it will bring you to the deployed website. 

### To Clone: 

## Acknowledgements 

* The layout of my Rescue Centre page using cards, the layout was taken from the Bootstrap documentation and then customised for my content.
  The link to this documentation can be found here https://getbootstrap.com/docs/4.0/components/card/. 
* To the Code Institute course material, as the basis of all my knowledge is from here.
* To the Slack community as I have used the different channels to find answers to problems!
* My background image on the "Contact Page" is from https://www.pexels.com.
* My homepage image is from https://unsplash.com. 
* My 5th and 6th "Rescue Stories" images are from https://unsplash.com.
* Stack Overflow as a valuable resource for solving a couple of issues. 
* Images that aren't referenced above are my own personal photos. 