# Back-to-the-arcade
Code Institute Portfolio Project 01

---

## Site Overview
Back To The Arcade is the website for a fictional Business that would be located in Brighton, England. The aim of the Arcade is to bring back the nostalgic feel of classic 80’s arcades when video games were in their infancy.

The Arcade aims to bring Retro games into the modern world and share the joy of these classic machines and games while also allowing for current console games and table top gaming all to be enjoyed in one place. 
  
![Am I Responsive screenshot](assets/images/AmIResponsive.png)

# Table of Contents
1. [Site Overview](#site-overview)  
2. [Planning Stage](#planning-stage)
    * [Target Audience](#target-audience)
    * [User Stories](#user-stories)
    * [Site Aims](#site-aims)
    * [Color Scheme](#color-scheme)
    * [Typography](#typograpy)   
3. [Current Features](#current-features)
    * [Header Element:](#header-element)
    * [The Site Features](#the-site-features)
    * [Footer](#footer)
4. [Future Enhancements](#future-enhancements)
5. [Testing Phase](#testing-phase)
6. [Deployment](#deployment)
7. [Tech](#tech)
8. [Credits](#credits)
    * [Honorable Mentions](#honerable-mentions)
    * [General Reference](#general-reference)
    * [Content](#content)
    * [Media](#media)

## Planning Stage

### Target Audience
The target audience for back to the Arcade are people that enjoy gaming of all eras.
* People interested in the nostalgic effect of retro gaming
* People that enjoy going to arcades
* People who like the atmosphere of piers and arcades and want food, refreshments and a top notch gaming experience all in one place
* People interested in family friendly activities in the Brighton area

### User Stories
During the reaserch phase, users of retro arcades had the following they wanted to see in this arcade:
* A user said they wanted somewhere to play classic games with a friendly atmosphere
* A user said they wanted an authentic gaming experience with the ability to eat good food while playing
* A user wanted a family friendly place where they can teach their children about the golden age of gaming

### Site Aims
The site aims to provide information to people in the brighton area about the arcade in an easy to use format with all possible questions answered in one place by:
* Informing the user who we are and what we offer
* Providing the user with the prices of all the items in one place
* Giving users the information they need on how to find the arcade

### Color Scheme
The site uses a color scheme to compliment the Logo image. The primary colors used are:
* black
    * #000000
    * rgb(0, 0, 0)
  
* Dark Orange
    * #FF8C00
    * rgb(255, 140, 0)
 
* White
    * #ffffff
    * rgb(255, 255, 255

### Typograpy
This website solely uses the Exo 2 font as it fits in with the theme of the logo font and has a retro game feel to it.  
The font was taken from Google Fonts as described in the credits section.

## Current Features Common to all pages
Across the site I have used the same styles for each of the web pages so they are easy to follow and the code is readable.

### Header Element:
 * The Header encorporates a logo image that takes up the same amount of the screen across devices.
 * There is a Navigation bar with working links across all devices, it has different sizes and styles depending on the size of the device:
      * On Mobile devices such as smart phones, the nav bar shows as a burger menu icon with a dropdown toggle.
      * On larger portable devices such as Tablets, the Navigation bar is still hidden in a burger style dropdown toggle menu.
      * On Laptops and Desktops the Navigation links span across the top-right of the screen and the Logo is fixed to the left of the screen.

### The Site Features: 
 * Each page of the website follows the same basic structure with a Hero image followed by 1 or more sections.
 * Each hero image has a cover text element and these all follow the same design structure as this provides consistancy above the whole site.
 * The index and Features pages both employ the same design style with a center image surrounded by text, note that for responsiveness this image only appears on larger devices, while on smaller devices the text stacks on top of each other.
 * The tables on the pricing and refreshments pages are laid out consistantly with the design of the website by:   
    * Using the same dark orange coloring for the borders as the cover image text.
    * being consistent in size and spacing to allow for full content to be viewable on mobile devices while not looking crampt on larger screens.

### Footer:
The footer element is designed to be responsive and spans across the bottom of the page across all screen sizes without taking up too much room.
 * The social network icons are evenly spaced across the footer and all open as new tabs rather than the current tab, this improves accessibility.

## Future Enhancements
 * A Sign-up page to inform potential customers about the arcades latest updates
 * The option for potential customers to book their visit online
 * There is potential to add javascript to make the web page interactive 

## Testing Phase
During the Testing Phase I relied heavely on Google Developer Tools which allowed me to test the responsiveness and layouts across multiple screen sizes. 
   * With the GitHub Mobile app I was able to continuously test the layout of each page and feature on My iPhone 14 pro, as well as my iPad Air 4th Gen.
   * I was able to test the layout on a MacBook Air as well as a larger monitor which all helped me see any bugs and issues in real time.

### Header:
The header element had to be extensively tested as it worked as expected on large devices but I encountered issues on smaller devices;
* The navigation toggle seemed to dance around the top of the page when switching from small -smartphone- displays to medium sized tablet displays, this caused inconsistancy with the pages.
* The drop down menu was one of the most confusing aspects of developing the site while being restricted to css and html.    The following issues were present:
    * The nav links would show up as a single horizontal line on smaller devices which made it all but unusable on smart phones. 
    * Once the nav bar had been styled for a block layout rather than inline this fixed the problem and allowed the items to fall vertically.
* During the testing phase, the logo had issues where it would spontainiously change its size and position on tablets, this has now been fixed with an aditional media query. 

### Body:
* The body element has sections on it that on a larger screen all flex in a row however on a smaller screen it took a lot of testing to get them to show up correctly. I was not confident with CSS flexing but after some experimentation I was able to get the sections to stack up correctly.
* The images between the text on the features and index pages both use the same css styling, originally they were seperate with the images as backgrounds in css however I realised that if they are img elements on in the html it is easier to make their styling more uniform with each other.
* The images also caused issues on smaller devices so I decided it was better for them to only show up on larger devices as they didn't sit right on mobiles.

### Footer:
The footer element works across all device sizes and the links opened new tabs across all devices thanks to me using the _blank actribute. The code works as it was closely borrowed from a previous project on Code Institute. On mobile devices, if the user has the apps for the social network links then rather than opening a new tab the link directly opens the app.

Once I was happy that the project had all the desired content I was able to run the working url through some validators with the following results: -
 * I ran the website through w3 html validator.
![536C09CE-4962-4256-86E4-049D601919D5_1_201_a](https://github.com/LeighAllenDev/Back-to-the-arcade/assets/140525595/68df0b93-2116-4aa1-91a6-fc21b4a1c25e)

 * I then ran the website through w3c jigsaw css checker.
![CCDF6F65-115C-43F1-953D-47243491B347_1_201_a](https://github.com/LeighAllenDev/Back-to-the-arcade/assets/140525595/2dfef421-bfab-4775-baa3-a7cdfaa13152)


## Bugs
* The logo has issues loading correctly when changing between small and medium screen sizes in Chrome Dev Tools. I believe this is caused by the size of the nav bar. there is a fix in place with a media query that allows the logo to show correctly on tablets however this isnt a permanent fix as the issue still persists in dev tools.

## Deployment
As I needed to text the website on multiple devices with different screen sizes, I deployed the website very early in the development proce. To achieve this I depoloyed the site using GitHub pages where I performed the following steps: -
   1. In the projects repository I clicked on the **Settings** tab.
   2. I then selected the **Pages** tab in the menu on the left.
   3. In the **Source** section, I Selected the **Main branch** of my repository from the dropdown menu, then clicked **Save**.
   4. A Message was displayed that confirmed successful deployment to GitHub pages and this provided a live link. The live website can be found via the following URL - https://leighallendev.github.io/Back-to-the-arcade/

## Tech
As per the Code Institute project guidlines, this website is entirely built using the following technologies:
  * HTML
  * CSS

## Credits

### Honerable Mentions
* For this site I got most of my inspiration from my Mentor for the course and he's been very helpful during the development process.
* My manager at my current job is a big fan of retro gaming and he helped me with some of the games to mention on this project.
* My partner helped me with the menu and the bundle tables and prices as she likes food and has experience in canteens.
* The logo design was taken from the Back To The Future movie franchise which I edited on my iPad using Procreate to create the logo as seen on the site. This logo also inspired the color scheme of the entire site.

### General Reference
* A lot of the layout and the styling aspects of this project were inspired by the Love Running project on Code Institute.
* Most of the images were from Pexels.com free to use stock images. See media section for references

### Content


### Media
* index.html
    * Hero image: Photo by cottonbro studio: https://www.pexels.com/photo/people-standing-in-front-of-store-during-night-time-4836371/
    * Center image: Photo by Mikhail Nilov: https://www.pexels.com/photo/woman-wearing-a-denim-jacket-playing-a-video-game-7887721/
* Features.html
    * Hero image: Photo by cottonbro studio: https://www.pexels.com/photo/man-in-black-jacket-and-white-pants-standing-in-front-of-counter-4841182/
    * Center Image: Photo by Francesco Ungaro: https://www.pexels.com/photo/mosaic-alien-on-wall-1670977/
* Refreshments.html
    * Hero image: Photo by <a href="https://unsplash.com/@xdqx?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">darlene</a> on <a href="https://unsplash.com/photos/iRL1P94z4Xc?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
* Pricing.html
    * Hero image: Photo by <a href="https://unsplash.com/@kanchanara?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Kanchanara</a> on <a href="https://unsplash.com/photos/tL9NpBM0KhY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  


[def]: assets/images/AmIResponsive.png
