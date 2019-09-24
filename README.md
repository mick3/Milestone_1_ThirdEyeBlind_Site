# UserCentricFrontendDevelopmentMilestoneProject
User Centric Frontend Development Milestone Project

User Stories:

I want my website to be able to provide the nostalgia of past successes of the band Third Eye Blind (be able to view past music videos, for example) while also informing a new fan of the great music that they create to this day.


I utilized a third party library for the image gallery on the page. This is called "Fancybox" and can be seen from http://fancyapps.com/fancybox/3/docs/#introduction .

Used this demo to display more than one item in the carousel at a time on large screens. Must utilize media queries to sort out smaller screens though. 
https://medium.com/wdstack/bootstrap-4-custom-carousel-94a537364fde

Media
image used for background found at: https://substreammagazine.com/2019/07/third-eye-blind-summer-gods-tour-photo/
took an image from https://www.paradiso.nl/nl/programma/third-eye-blind/62618/ to use on the "tour dates" section of the page. Named it "Stephan_Jenkins.jpg"

Changed "<" and ">" arrows on carousel colors because they are not noticeable by default. Also, changed the visibility of the 
indicators that show which area in the available carousel slides are shown. Used these resources: https://stackoverflow.com/questions/46249541/change-arrow-colors-in-bootstraps-carousel
https://stackoverflow.com/questions/17872913/carousel-indicators-not-showing-up-on-white-background-on-slides-custom-style-o

Used https://wpshout.com/quick-guides/create-text-outline-css/ to create a black outline border on the navbar title "Third Eye Blind" to create separation from the background upon landing and scrolling the page. 

Testing
Deleted background-attachment: fixed in my css for both background images. They were showing up on my iphone as 'zoomed in' and pixelated. So I deleted that, and reloaded the page on my iphone 6 and it rendered correctly.

Bugs/Fixes:
Sep 21, 2019: I added to the CSS rule "@media (max-width: 575px)" a media query that would make the Title Text "Third Eye Blind" in the navbar, on smaller screens, a smaller font-size so that the title wouldn't push the navbar dropdown to the second-line of the navbar. Shortly after this, I noticed on updated viewing of the Github pages "live page" of the project that it had totally removed the title altogether. I also had added a span element to the h5 element of the title. Upon seeing this I tried to revert my repository to an earlier version of the project. So far, I have not been able to get the title back, despite the html5 code still remaining. Meaning, the title has completely disappeared from the project. 

Collapsible navbar dropdown code found here:
https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click