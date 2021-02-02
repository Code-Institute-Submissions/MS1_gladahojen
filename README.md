# My 1st milestone project
## Building a new webpage to Glada Hojen motorcycle workshop

[Glada Hojen](https://gladahojen.se/) current webpage

My version (http--link--)

        -----------mockup img goes her--------

........
User Experience (UX)

    First Time Visitor Goals
    Returning Visitor Goals

### ___ *STRATEGY* ___

Who is it for? 
    Current and new customers and bike riders.
What is it?
    A webpage that describes the different services and products provided.
Why am I building it?
    The current webpage isn't really good or up to date, and the workshop's web presence today is
    instagram and facebook, but customers are mostly around their 40's and up. My assumtpion
    is that they usually don't hang out as much on social media.


..........
Design
### ___ *SCOPE* ___

What does the content look like?
    Images, text, lists, a form, external links


.........
Wireframes
    destop
    smartphone
### ___ *STRUCTURE* ___

Non-linear

    - Home page
    - Workshop / About page
    - Store
        Motorcyle 
        Rider
    - Contact (email form)



### ___ *SKELETON* ___

Navigation design: 
    A navbar at the top with a dropdown menu, and a footer with adress and phone number
    at the bottom. Both on evey page of the site.
    I used a navbar from Boostrap.

Hierachy information:
    Navbar left to right:
    Home - a short describtion of the workshop
    Workshop / About - I choose the put the workshop information first because that's whats
        people probably wants to know first. After that they can learn more about the
        company background.
    Shop (dropdown menu) 
        Motorcyle - a short describtion of parts and brands that are used. And a reseller
        sub section for Royal Enfield and ZARD Exhaust system.
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
    They are edited in Gimp to black and white to follow the gray theme.
    
    https://unsplash.com/photos/v6uiP2MD6vs

.........
Features
    responsive on all devices

............
Technologies Used

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
Gitpod



............
Testing

    W3C Markup Validator - Results
    W3C CSS Validator - Results

Testing User Stories from User Experience (UX) Section
    First Time Visitor Goals
    Returning Visitor Goals
### ___ BUGGS ___

Navbar - Underline hover animation doesn't work on all pages and the dropdown disappered. Keep it or discard?
    Code from: https://stackoverflow.com/questions/40242378/underline-from-left-to-right-on-hover-in-and-out

    Validation comes out ok.
    Used Diffcheck to see if there was any differnce in the code. No errors.
    Tried to comment out the <li> with a dropdown class to see if the dropdown was the issue. It wasn't.
    Change the z-index value between (-2, -1, 1, 2). Still only worked on index.html.
    After talking to Tutor Support it turned out that I was loading the CSS befor the Bootstrap on the
    other pages. After moving the CSS below it works on the other pages too. 

    To get the animation to work on the dropdown I was adviced to try to target <li class="nav-item dropdown"> 
    instead of the <a> tag with the .underline.
    The dropdown arrow becomes visable but I don't get any underline animation or a dropdown menu. It is
    also moved out of place.

Carousel - Used Bootstrap to add a caarousel in the header. Wouldn't start.
    Googled "how to create a bootstrap carousel". Both sites 
    https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-carousel.php
    and
    https://www.w3schools.com/bootstrap/bootstrap_carousel.asp
    said that the code used to activate the carousel is *data-ride="carousel"*
    Change the code. Carousel works.

    Even though all photos in the carousel have the same height, an extra space is created 
    underneath the image befor tires_bw.jpg and tools_bw.jpg. This makes the scetion below move 
    up and down when it changes image. 
    Manage to change the background-color, but haven't figured
    out how to get rid of the extra space. Maybe a "marign-bottom"...?
    Added the w-100 class to css and set the height to 250px and object-fit to cover. Now the dead 
    space under is gone on all devices.

Image sizeing - Googled "change image size css"
    https://stackoverflow.com/questions/15685666/changing-image-sizes-proportionally-using-css    

Opaque-overlay - The overlay in workshop_about.html workshop section overlays the paragraph text 
    instead of only the image. Used the Updating Our Callout-video as a guide, but it didn't came
    out right.
    Tried adding z-index with different positive vaules, but still the same.
    Asked Tutor Support and got the suggestion to try with negative values.
    But then the opaque overlay disappered compleatly.
    After adding a z-index: -2; to .main-workshop, then adding z-index: -1; it worked.

Resell .card - The .cards are stacked but not centered when viewed on mobile or tablet.
    I have tried changing the padding and margins. But it didn't help.
    I tried to use display:flex on both .resell-row and .col, nothing happens.
    And margin:auto on .resell-row just moves the card slightly to the right, but it was far from centered.
    After rewatching the the video about Responsive Gallery and used column-count: 1; and changed the
    padding in @media för mobile I got it centered.

A mysterious white space  - ...that isn't a margin along the right side. The space creaties a scrollbar at the
    bottom in the motorcycle.html and on a smartphone all pages are to wide.
    I tried experimenting with the right margin and padding on different sections, and googleing but came 
    out empty handed.
    After some time of frustration, and just clicking through every part of motorcycle.html in develpoer tools and
    reading all the code, I found that Bootstrap seems to add a gutter to the row class. Which isn't visable in the
    HTML. So after setting  --bs-gutter-x to 0 the white space disappered.

Footer - responsive design won't work. Tried targeting different classes. 
    Asked on Slack, and got the advice from Richard Ash to try wrapping three "col-sm" divs inside a "row".
    still didn't work as I wanted.
    Contacted Tutor Support and got this link https://www.w3schools.com/bootstrap4/bootstrap_grid_basic.asp
    After rreading through it I realized that I had added a mix of different classes.
    So I started fresh on the footer and redid the classes. 
    Now the footer is responsive. 
    This also made me realize how to make the main content resposive on the other pages. 

.............
Deployment
    GitHub Pages


### ___ CREDITS ___

Christoffer Nicklasson