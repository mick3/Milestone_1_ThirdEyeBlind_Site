# Milestone_1_ThirdEyeBlind_Site
### By: Mike Webber
User Centric Frontend Development Milestone Project

## UX
This website is for new fans of the band, old fans, and people who have just now heard of the band. The site has everything you'd want to get to know the sound of the band and the look of the band members. The only thing the site doesn't have is a store to buy merchandise. I wanted to implement a very simple and straight forward navigating experience. Starting off on the landing page with a 'hero' image of the lead singer, once you get to this point, you know you're in the right place. The site is a single-page app navigable from the dropdown menu or scrollable.

#### The main wireframe for the conception of this project was created using Balsamiq Mockups 3, and is viewable from the main file structure of the repository. Other images used to design and 'flesh out' the site design are also viewable from the repository. The images are pictures of a notepad that were written up during the project to get over idea blockages.

## User Stories:
1. As a longtime fan of Third Eye Blind, I can navigate to this site and listen to their entire playlist on spotify.
2. As a new fan of Third Eye Blind, I can go to this site to find all their music and listen to it.
3. As a concert goer who wants to see Third Eye Blind live, I can come to this site to view upcoming tour date times and locations, as well as purchase tickets from external sites.
4. As someone who wants to host the band at an event, I can fill out the form at the bottom of the page and someone will contact me about that event in the future.
5. As a developer, I want to showcase my skills to date utilizing HTML5, CSS3, Bootstrap and other libraries to make a website dedicated to one of my favorite bands.

### Design:

I wanted the site to be minimal in appearance, yet definitive in it's delivery of pertinent content about the band, Third Eye Blind.

#### Font:

The project's main font is Open Sans and Source Sans Pro as a backup. I originally saw these fonts in use on the bands already existing website and thought they worked well with the feel of what font should be used. I didn't have to reinvent the wheel either.

#### Color Scheme:

The main colors used in the project are Black (#000) and White (#FFF) as well as North Carolina Blue or Baby Blue (#87ceeb). I didn't want to overwhelm anyone with a complicated and unecessary color scheme selection so I kept it simple. I thought the #87ceeb color went well with the lyrics of the band which often are "daydreamy" and "hopeful", so I used sky blue.

## Features
The first thing we see when we navigate to the page is a hero image of the lead singer. The second section is a tour date list and ways to purchase tickets. The third part of the project is where you can listen to music by the band or watch a music video. The next section is an Image Gallery. The section after that is a booking form you can use to book the band for an event. And in the footer there are more ways to follow the band or listen to more of their music on other web services.

### Features left to implement:
I would like to somehow include more music videos on the site, but for the sake of brevity, I selected videos "throughout" the career of the band, providing an oversight of their music.

I didn't really think about this until the end of the project, but would like to implement a tagline at the bottom of the 'landing-page' that explains a little bit about Third Eye Blind.

I would also like to implement a 'stop-scrolling-while-video-plays' function for when a user clicks one of the videos in the carousel to play. The carousel keeps scrolling otherwise. 

## Technologies used
  #### HTML 5
  #### CSS3
  #### Javascript
  #### Fancybox
  #### Bootstrap 4.3.1
  #### Font Awesome
  
  ## Deployment
  I deployed the website to Github pages by, first creating a repository for where my code exists. I clicked the "new" button in my main github login page. It then takes you to the page where you name your repository. You can make your repository public or private. I made mine public. I initialized the repository with a README.md file. I then created files in my code editor VSCode and pushed the files to the repository via terminal and git commands. I made sure to create the 'index.html' file so that github and github pages would publish that as the main page versus not having the index.html file and github defaulting to host the readme.md file as the main file. 
  
I added the link to the live Github pages link to the Github repository so you can navigate it without having to go to settings in github.

Otherwise, to find the Github Pages live page, go to Settings and scroll down to where the link to the page is, and click on it. This will take you to the live page. 

## Media
image used for jumbotron landing-page background found at: https://substreammagazine.com/2019/07/third-eye-blind-summer-gods-tour-photo/
took an image from https://www.paradiso.nl/nl/programma/third-eye-blind/62618/ to use on the "booking-area" section of the page. Named it "Stephan_Jenkins.jpg"

All images in Image Gallery were downsized at http://www.onlineimageresize.com/. Images used for the Image gallery were resized to be small for thumbnail viewing with the fancybox app, and all file names of the resize are named "onlineimageresize_com_" followed by the original file name. For example, the thumbnail for "acoustic.jpg" is named "onlineimageresize_com_acoustic.jpg" after running it through the downsize web app aforementioned.

1."acoustic.jpg" taken from https://trilliumfamily.org/advocacy-platform/look-keep-oregon-well-with-third-eye-blind-in-the-skype-live-studio-photos-video/

2."screamer_tour.jpg" taken from https://loudwire.com/third-eye-blind-fall-2019-tour/

3."band_bw.jpg" taken from https://www.billboard.com/articles/news/7834041/third-eye-blind-summer-gods-EP-album-tour-interview

4."band_bw_dopamine.jpg" taken from https://crypticrock.com/third-eye-blind-dopamine-album-review/.

5."sj_hand.jpg" taken from https://www.rollingstone.com/music/music-features/third-eye-blind-frontman-on-the-desperation-behind-hit-debut-250843/.

6. "3eb_back.jpg" taken from https://www.impconcerts.com/event/1820799-third-eye-blind-jimmy-eat-columbia/.

7."group_hug.jpg" taken from https://spectrumculture.com/2019/06/20/concert-review-third-eye-blind-jimmy-eat-world/

8."acoustic_2.jpg" taken from https://splice-mediagroup.com/jimmy-eat-world-along-with-third-eye-blind-light-up-freedom-hill/2019.

9."3eblogo.png" used in the navbar was taken from the Third Eye Blind Facebook group site.

Used https://wpshout.com/quick-guides/create-text-outline-css/ to create a black outline border on the navbar title "Third Eye Blind" and the navbar dropdown, to create separation from the background upon landing and scrolling the page for viewability with the light blue color used.

I utilized a third party library for the image gallery on the page. This is called "Fancybox" and can be seen from visiting: http://fancyapps.com/fancybox/3/docs/#introduction .

Used this demo to display more than one item in the carousel at a time on large screens. Must utilize media queries to sort out smaller screens though. 
https://medium.com/wdstack/bootstrap-4-custom-carousel-94a537364fde

## Testing
Deleted "background-attachment: fixed" in my css for both background images. They were showing up on my iphone as 'zoomed in' and pixelated. So I deleted that, and reloaded the page on my iphone 6 and it rendered correctly.

As I worked through the project, I primarily tested the site on mobile by using my own iPhone 6s (Safari 13). This helped me immensely and helped to cover some of the smallest screen sizes needed to be covered in my project. 

Browsers I tested the site on include: Chrome Version 76.0.3809.100 (Official Build) (64-bit), Firefox Quantum 69.0.1 (64-bit), Safari Version 13.0.1 (14608.2.11.1.11) and Opera Version:63.0.3368.94. I was unable to test on Microsoft versions of browsers (Edge, IE) because I don't own any Microsoft products. But in hind sight, I could have gone to Best Buy to test on their sample models.



## Bugs/Fixes:

Collapsible navbar dropdown code found here:
https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click
Since I created a single-page app, the default navbar wasn't enough. The default navbar expects when you are clicking to go to a different segment of the page, that you'll be reloading the entire site and navigating elsewhere. For a single-page app, additional code was needed.

I received help from Anthony O'Brien, a channel lead for "User Centric Front-End": he let me use some javascript for the main dropdown menu to collapse after clicking on one of the menu elements, since the entire project is a singe-page HTML project. The default dropdown menu wasn't sufficient for use with a single-page element because it only disappears because we are navigating to a different page and it is reloading an entire page. I have a single-page web app, so after you click the dropdown, it navigates to a different page section, and also collapses with the javascript implementation.

### Acknowledgements
I received inspiration for a more "modern" look and "minimal" look by looking at the highest graded Milestone project submitted by Haley Schafer.
