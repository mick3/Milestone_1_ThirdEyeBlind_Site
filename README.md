# Milestone_1_ThirdEyeBlind_Site
#By: Mike Webber
User Centric Frontend Development Milestone Project

## UX
This website is for new fans of the band, old fans, and people who have just now heard of the band. The site has everything you'd want to get to know the sound of the band and the look of the band members. The only thing the site doesn't have is a store to buy merchandise. I wanted to implement a very simple and straight forward navigating experience. Starting off on the landing page with a 'hero' image of the lead singer, once you get to this point, you know you're in the right place. The site is a single-page app navigable from the dropdown menu or scrollable.

## The main wireframe for the conception of this project was created using Balsamiq Mockups 3, and is viewable from the main file structure of the repository. Other images used to design and 'flesh out' the site design are also viewable from the repository. The images are pictures of a note pad that were written up during the project to get over idea blockages.

## User Stories:
1. As a longtime fan of Third Eye Blind, I can navigate to this site and listen to their entire playlist on spotify.
2. As a new fan of Third Eye Blind, I can go to this site to find all their music and listen to it.
3. As a concert goer who wants to see Third Eye Blind live, I can come to this site to view upcoming tour date times and locations, as well as purchase tickets from external sites.
4. As someone who wants to host the band at an event, I can fill out the form at the bottom of the page and someone will contact me about that event in the future.

# Features
The first thing we see when we navigate to the page is a hero image of the lead singer. The second section is a tour date list and ways to purchase tickets. The third part of the project is where you can listen to music by the band or watch a music video. The next section is an Image Gallery. The section after that is a booking form you can use to book the band for an event. And in the footer there are more ways to follow the band or listen to more of their music on other web services.

### Features left to implement:
I would like to somehow include more music videos on the site, but for the sake of brevity, I selected videos "throughout" the career of the band, providing an oversight of their music.

I would like to implement a newsletter sign up also, perhaps.

## Technologies used
  ### HTML 5
  ### CSS3
  ### Javascript
  ### Fancybox
  ### Bootstrap 4.3.1
  ### Font Awesome


I utilized a third party library for the image gallery on the page. This is called "Fancybox" and can be seen from visiting: http://fancyapps.com/fancybox/3/docs/#introduction .

Used this demo to display more than one item in the carousel at a time on large screens. Must utilize media queries to sort out smaller screens though. 
https://medium.com/wdstack/bootstrap-4-custom-carousel-94a537364fde

Media
image used for background found at: https://substreammagazine.com/2019/07/third-eye-blind-summer-gods-tour-photo/
took an image from https://www.paradiso.nl/nl/programma/third-eye-blind/62618/ to use on the "tour dates" section of the page. Named it "Stephan_Jenkins.jpg"

All images in Image Gallery were downsized at http://www.onlineimageresize.com/. Images used for the Image gallery were resized to be small for thumbnail viewing with the fancybox app, and all file names of the resize are named "onlineimageresize_com_" followed by the original file name. For example, the thumbnail for "acoustic.jpg" is named "onlineimageresize_com_acoustic.jpg".

1."acoustic.jpg" taken from https://trilliumfamily.org/advocacy-platform/look-keep-oregon-well-with-third-eye-blind-in-the-skype-live-studio-photos-video/

2."screamer_tour.jpg" taken from https://loudwire.com/third-eye-blind-fall-2019-tour/

3."band_bw.jpg" taken from https://www.billboard.com/articles/news/7834041/third-eye-blind-summer-gods-EP-album-tour-interview

4."band_bw_dopamine.jpg" taken from https://crypticrock.com/third-eye-blind-dopamine-album-review/.

5."sj_hand.jpg" taken from https://www.rollingstone.com/music/music-features/third-eye-blind-frontman-on-the-desperation-behind-hit-debut-250843/.

6. "3eb_back.jpg" taken from https://www.impconcerts.com/event/1820799-third-eye-blind-jimmy-eat-columbia/.

7."group_hug.jpg" taken from https://spectrumculture.com/2019/06/20/concert-review-third-eye-blind-jimmy-eat-world/

8."acoustic_2.jpg" taken from https://splice-mediagroup.com/jimmy-eat-world-along-with-third-eye-blind-light-up-freedom-hill/2019.

9."3eblogo.png" used in the navbar was taken from the Third Eye Blind Facebook group site.

Used https://wpshout.com/quick-guides/create-text-outline-css/ to create a black outline border on the navbar title "Third Eye Blind" and the navbar dropdown, to create separation from the background upon landing and scrolling the page. 

Testing
Deleted "background-attachment: fixed" in my css for both background images. They were showing up on my iphone as 'zoomed in' and pixelated. So I deleted that, and reloaded the page on my iphone 6 and it rendered correctly.

Bugs/Fixes:
Sep 21, 2019: I added to the CSS rule "@media (max-width: 575px)" a media query that would make the Title Text "Third Eye Blind" in the navbar, on smaller screens, a smaller font-size so that the title wouldn't push the navbar dropdown to the second-line of the navbar. Shortly after this, I noticed on updated viewing of the Github pages "live page" of the project that it had totally removed the title altogether. I also had added a span element to the h5 element of the title. Upon seeing this I tried to revert my repository to an earlier version of the project. So far, I have not been able to get the title back, despite the html5 code still remaining. Meaning, the title has completely disappeared from the project. 

Collapsible navbar dropdown code found here:
https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click

I received help from Anthony O'Brien, a channel lead for "User Centric Front-End": he let me use some javascript for the main dropdown menu to collapse after clicking on one of the menu elements, since the entire project is a singe-page HTML project. The default dropdown menu wasn't sufficient for use with a single-page element because it only disappears because we are navigating to a different page and it is reloading an entire page. I have a single-page web app, so after you click the dropdown, it navigates to a different page section, and also collapses with the javascript implementation.

