# Milestone project 1 - Glada Hojen
### Goal: Build an alternative webpage to [Glada Hojen](https://gladahojen.se/) (current webpage) motorcycle workshop.
Worth to mention is that "glad" in swedish means "happy". So the english name for the
workshop would be "Happy Bike".
 
(For refrence I have also added a link to the current webpage in the navbar logo instead of linking it back to index.html.)

#### In consent with my mentor Akshat Garg I made this website in swedish.

**[My version](https://mjau83.github.io/MS1_gladahojen/?fbclid=IwAR2RnCUgmlylK_fVtRZSxlSKZdpiTHcssyOuu2Z3wjswQJ4FooHudN7BB-M)**

[Glada Hojen mockup](https://photos.app.goo.gl/DLUQdvRh9YQzbDCb7)

## User Experience (UX)

* First Time Visitor Goals
    * As a first time visitor I want to know what kind of services they offer.
    * As a first time visitor I want to be able to navigate the site in a easy way.
    * As a first time visitor I want to know where the workshop is located and how to get in touch.
    * As a first time visitor I want to know what kind of experince the mechanic have.
* Returning Visitor Goals
    * As a returning visitor I want to know what parts I can order for my motorcycle.
    * As a returning visitor I want to find social media links so I can get to know the workshop better.
    * As a returning visitor I want to be able to contact the workshop in a easy way.

**Who is it for?**
Current and new customers and bike riders.

**What is it?** 
A webpage that describes the different services and products provided.

**Why am I building it?**
The current webpage isn't really good or up to date, and the workshop's web presence today is
instagram and facebook, but customers are mostly around their 40's and up. My assumtpion
is that they usually don't hang out as much on social media.

## Design

**Color:** 
* Gray 
* Oranges

**Fonts:**
* Chakra Petch, sans-serif
* Roboto, sans-serif

**Images:**
All images are either my own or provided by Glada Hojen.
They are edited in **Gimp** to black and white to follow the gray theme.
Background image in contact.html is taken from : https://unsplash.com/photos/v6uiP2MD6vs


## Wireframes
Desktop:
[Index](https://photos.app.goo.gl/ZnuYT3W1KZNcp9HT6)
[Workshop](https://photos.app.goo.gl/TAHpGiwGp4nJ83NKA)
[Motorcyle](https://photos.app.goo.gl/TUTmegNW8cFPZfAn8)
[Rider](https://photos.app.goo.gl/aDZ3U8jNHidXgCgK9)
[Contact](https://photos.app.goo.gl/qYi1C6ZnGCSDGyG78)

Smartphone: 
[Index](https://photos.app.goo.gl/M9U8SNhhVyx5xVXD7)
[Workshop](https://photos.app.goo.gl/KVswwAns8CraeJRd6)
[Motorcyle](https://photos.app.goo.gl/sCvV6yzWUdax5jqD6)
[Rider](https://photos.app.goo.gl/ev7XjbKEAnKXbJ8C8)
[Contact](https://photos.app.goo.gl/8jyh12pczwNWhVYK8)


## Structure
Non-linear

    - Home page
    - Workshop / About page
    - Store
        Motorcyle 
        Rider
    - Contact (email form)

## Navigation design: 
A fixed navbar at the top with a dropdown menu under the **BUTIK** (store) section, 
where the user can brows to motorcycle parts or riding gear. A footer with adress, 
phone number and social media links at the bottom. Both on evey page of the site.
I used a navbar from [Boostrap](https://getbootstrap.com/docs/5.0/components/navbar/).
When viewed on a mobie device the menu changes into an burger menu.

### Hierachy information
Navbar left to right:

* **Home** - A short describtion of the workshop and what's avaible.

* **Workshop / About** - I choose the put the workshop information first because that's whats
people probably wants to know first. After that they can learn more about the company background
and experince.

* **Shop (dropdown menu)** 
    * Motorcyle - A short describtion of parts and brands that are used. And a reseller
        sub section for Royal Enfield and ZARD Exhaust system.

    * Clothes - A short describtion of what's avaible in store or for order.

* **Contact** - Email form to get in touch, ans a sub section with opening hours and a location map

### Features
* Responsive on desktop, tablet and smartphone
* Email form 

### Technologies Used
#### Languages
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)
#### Frameworks, Libraries, Programs
* [Balsamic Images](https://balsamiq.com)
 was used to create wireframes in the beginning of the project
* [Gimp](https://www.gimp.org/)
was used to edit photos to black and white.
* [Google Fonts](https://fonts.google.com/)
was used to import the fonts mentioned above in the project.
* [Font Awsome](https://fontawesome.com/)
was used to import the icons used in this project.
* [Boostrap v.5.0](https://getbootstrap.com/)
was used to design some of the styling and for the responsive features
* [Stackoverflow](https://stackoverflow.com/)
was used to design some of the styling
* [Material.io](https://material.io/resources/color/#!/?view.left=1&view.right=0&primary.color=42A5F5&secondary.color=7B1FA2)
was used to make sure that color contrast was ok
* [Am I Responsive](http://ami.responsivedesign.is/)
was use to make the mockup
* [Webformatter](https://webformatter.com/html)
was used to beautify the code
* [Gitpod](https://gitpod.io/)
was used for coding the project
* [Github](https://github.com/)
after being pushed in Gitpod the project was saved and stored on GitHub.

## Testing

* [W3C Markup Validator](https://validator.w3.org/) 
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

### Testing User Stories from User Experience (UX) Section

* **First Time Visitor Goals**
    * As a first time visitor I want to know what kind of services they offer.
        1. When entering the website the user is welcomed by a image slider that shows motorcycles, tools and tires.
        2. The under the welcome image is a short paragraph text that describes what is kind of work and services
        they do at the workshop.

    * As a first time visitor I want to be able to navigate the site in a easy way.
        1. When the user enters the site the navbar indicates that they are on the home page.
        It changes if the user click on an other page.
        2. The navbar is fixed and visable to the user even if they scroll down on the page.
    
    * As a first time visitor I want to know where the workshop is located and how to get in touch.
        1. The adress is found in the footer on all pages.
        2. The phone number is found in the footer on all pages.
        3. On the Contact page the user can send a email using a form.
        4. On the Contact page the user will find a map and opening hours underneath the email form.
    
    * As a first time visitor I want to know what kind of experince the mechanic have.
        1. On the Workshop page the user can find an About section which describes the working history of the 
        owner and mechanic.

* Returning Visitor Goals
    * As a returning visitor I want to know what parts I can order for my motorcycle.
        1. On the motorcycle page the user can find a short describtion and a list of examples of
        various parts that are either in store or can be ordered.
        2. On the motorcycle page the user can find links to different brands that are either in store or can be ordered.

    * As a returning visitor I want to find social media links so I can get to know the workshop better.
        1. Links to social media can be found in the footer on every page.

    * As a returning visitor I want to be able to contact the workshop in a easy way.
        1. The adress is found in the footer on all pages.
        2. The phone number is found in the footer on all pages.
        3. On the Contact page the user can send a email using a form.

### Futher testing
* The website was tested on Chrome and on Android (Samsung and Xperia)
* The links was tested to ensure that they worked probably.
* The different inputs in the form was tested to ensure that they worked probably.
* A lot of time was spent testing the resposive design for desktop, 
tablet and smartphone as each section was coded.

### Buggs

* **Navbar** - Underline hover animation doesn't work properly on all pages. The dropdown arrow disappered, and the beginning of the
underline is visable even when not hovering over BUTIK. Keep it or discard?
Code from: https://stackoverflow.com/questions/40242378/underline-from-left-to-right-on-hover-in-and-out

    1. Validation comes out ok.
    2. Used Diffcheck to see if there was any differnce in the code. No errors.
    3. Tried to comment out the < li > with a dropdown class to see if the dropdown was the issue. It wasn't.
    4. Change the z-index value between (-2, -1, 1, 2). Still only worked on index.html.
    5. After talking to Tutor Support it turned out that I was loading the CSS befor the Bootstrap on the
    other pages. After moving the CSS below it works on the other pages too. 
    6. To get the animation to work on the dropdown I was adviced to try to target < li class=" nav-item dropdown " > 
    instead of the < a > tag with the .underline.
    7. The dropdown arrow becomes visable but I don't get any underline animation or a dropdown menu. It is
    also moved out of place.
    8. After tring to find answers on Goggle and Youtube without succes I decided to comment out the
    code, and in the end to discard this funtion.

* **Carousel** - Used Bootstrap to add a carousel in the header. Wouldn't start.
    
    1. Googled "how to create a bootstrap carousel". Both sites 
    https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-carousel.php
    and
    https://www.w3schools.com/bootstrap/bootstrap_carousel.asp
    said that the code used to activate the carousel is *data-ride="carousel"* The original code
    was data-bs-ride. Deleted the -bs-. Carousel works.

Even though all photos in the carousel have the same height, an extra space is created 
underneath the image befor tires_bw.jpg and tools_bw.jpg. This makes the section below move 
up and down when it changes image. 
    1. Manage to change the background-color, but haven't figured out how to get rid of the extra space. Maybe a "marign-bottom"...?
    2. Added the w-100 class to css and set the height to 400px and object-fit to cover. Now the dead 
    space under is gone on all devices.

**Image sizeing** - the welcome image in index.html  
    1. Googled "change image size css"
    https://stackoverflow.com/questions/15685666/changing-image-sizes-proportionally-using-css    

**Opaque-overlay** - The overlay in workshop_about.html workshop section overlays the paragraph text 
instead of only the image. 
    1. Used the Updating Our Callout-video as a guide, but it didn't came
    out right.
    2. Tried adding z-index with different positive vaules, but still the same.
    3. Asked Tutor Support and got the suggestion to try with negative values.But then the opaque overlay disappered compleatly.
    4. After adding a z-index: -2; to .main-workshop, then adding z-index: -1; it worked.

**Resell .card** - The .cards are stacked but not centered when viewed on mobile or tablet. 
    1. I have tried changing the padding and margins. But it didn't help.
    2. I tried to use display:flex on both .resell-row and .col, nothing happens.
    3. After asking on Slack I got the advice from Zac Warner to try margin:auto on .resell-row, but it just moved the card 
    slightly to the right, but it was far from centered.
    4. After rewatching the the video about Responsive Gallery and used column-count: 1; and changed the
    padding in @media för mobile I got it centered.

**A mysterious white space**  - ...that isn't a margin along the right side. The space creaties a scrollbar at the
bottom in the motorcycle.html and on a smartphone all pages are to wide.
    1. I tried experimenting with the right margin and padding on different sections, and googleing but came 
    out empty handed.
    2. After some time of frustration, and just clicking through every part of motorcycle.html in develpoer tools and
    reading all the code, I found that Bootstrap seems to add a gutter to the row class. Which isn't visable in the
    HTML. So after setting  --bs-gutter-x to 0 the white space disappered.

**Footer** - responsive design won't work. 
    1. Tried targeting different classes. 
    2. Asked on Slack, and got the advice from Richard Ash to try wrapping three "col-sm" divs inside a "row".
    still didn't work as I wanted.
    3. Contacted Tutor Support and got this link https://www.w3schools.com/bootstrap4/bootstrap_grid_basic.asp
    After rreading through it I realized that I had added a mix of different classes.
    4. So I started fresh on the footer and redid the classes. 
    Now the footer is responsive. This also made me realize how to make the main content resposive on the other pages. 


## Deployment

### GitHub Pages
This project was deployed using Github pages.

1. Go to [Github](https://github.com/)
2. Log in and find the repository
3. Find the "Settings" (with a gear icon)
4. Scroll down on the page until you find the "Github Pages" section
5. Under "Source" you'll find a dropdown which is set to "none"
6. Change it to "Master"
7. The page refresh on its own
8. Scroll back down to "Github Pages" 
9. A green alert box will now tell you that your site been published and provide you a link to the site.


## CREDITS 

**Content**

The text in the history section and in index.html was inspired from the [current website](https://gladahojen.se/)

**Media**
* Some of the images on the site was provided by Glada Hojen.
* The rest of the images are my own.

**Acknowledgements**

* Tutor Support at Code Institute
* My Mentor Akshat Garg, for giving feedback and advice
* Helpful people on Slack, especially Eventyret_mentor for giving some last minute feedback.
* My friend Christoffer Nicklasson, for helping me read through the code when I got stuck.
* My friend and employer Magnus Glad owner of Glada Hojen, for giving me material and giving med the 
consent to build an alternative website.