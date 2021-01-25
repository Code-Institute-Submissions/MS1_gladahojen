# My 1st milestone project
## Building a new webpage to Glada Hojen motorcycle workshop

[Glada Hojen](https://gladahojen.se/) current webpage

My version (http--link--)

### ___ *STRATEGY* ___

Who is it for? 
    Current and new customers and bike riders.
What is it?
    A webpage that describes the different services and products provided.
Why am I building it?
    The current webpage isn't really good or up to date, and the workshop's web presence today is
    instagram and facebook, but customers are mostly around their 40's and up. My assumtpion
    is that they usually don't hang out as much on social media.


### ___ *SCOPE* ___

What does the content look like?
    Images, text, lists, a form, external links



### ___ *STRUCTURE* ___

Non-linear

    - Home page
    - Workshop / About page
    - Store
        Motorcyle parts
        Riding gear
    - Contact (email form)



### ___ *SKELETON* ___

Navigation design: 
    A navbar at the top with a dropdown menu, and a footer with adress and phone number
    at the bottom. Both on evey page of the site.

Hierachy information:
    Navbar left to right:
    Home - a short describtion of the workshop
    Workshop / About - I choose the put the workshop information first because that's whats
        people probably wants to know first. After that they can learn more about the
        company background.
    Shop (dropdown menu) 
        Motorcyle - a short describtion of parts and brands that are used.
        Clothes - a short describtion of what's avaible in store or for order.
    Contact - Email form to get in touch.


### ___ *SURFACE* ___

*Color: 
    Grays 
    Oranges
*Fonts:
    Font-family: Chakra Petch, sans-serif and Roboto, sans-serif
*Order of apperance
*Images:
    All images are either my own, provided by or taken with permisson from Glada Hojen.
    They are edited to black and white to follow the gray theme.


### ___ Technology ___

#### Languages
HTML5
CSS3
#### Frameworks, Libraries, Programs
Balsamic Images
Gimp
Boostrap v.5.0
Google Fonts
Font awsome
Github


### ___ BUGGS ___

Navbar - Underline hover animation doesn't work on all pages and the dropdown disappered. Keep it or discrd?
    Code from: https://stackoverflow.com/questions/40242378/underline-from-left-to-right-on-hover-in-and-out

Footer - responsive design won't work. Tried targeting classes. Asked on Slack

Carousel - Used Bootstrap to add a caarousel in the header. Wouldn't start.
    Googled "how to create a bootstrap carousel". Both sites 
    https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-carousel.php
    and
    https://www.w3schools.com/bootstrap/bootstrap_carousel.asp
    said that the code used to activate the carousel is *data-ride="carousel"*
    Change the code. Carousel works.

    Even though all photos in the carousel have the same height, an extra space is created 
    underneath the image befor tires_bw.jpg and tools_bw.jpg. This makes the scetion below move 
    up and down when it changes image. Manage to change the background-color, but haven't figured
    out how to get rid of the extra space. Maybe a "marign-bottom"...?

Image sizeing - Googled "change image size css"
    https://stackoverflow.com/questions/15685666/changing-image-sizes-proportionally-using-css    

Opaque-overlay - The overlay in workshop_about.html workshop section overlays the paragraph text 
    instead of only the image. Used the Updating Our Callout-video as a guide, but it didn't came
    out right.
    Tried adding z-index with different positive vaules, but still the same.
    Asked Tutor Support and got the suggestion to try with negative values.
    But then the opaque overlay disappered compleatly.
    After adding a z-index: -2; to .main-workshop, then adding z-index: -1; it worked.


### ___ TESTING ___

### ___ CREDITS ___
