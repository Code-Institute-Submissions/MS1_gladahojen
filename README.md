# Milestone project 1 - Glada Hojen
### Goal: Build a new webpage to [Glada Hojen](https://gladahojen.se/) (current webpage) motorcycle workshop.
#### (For refrence I have also added a link to the current webpage in the navbar logo instead of linking it back to index.html.)

My version (http--link--)

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

Images, text, lists, a form, external links

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
* [Gitpod](https://gitpod.io/)
was used for coding the project
* [Github](https://github.com/)
after being pushed in Gitpod the project was saved and stored on GitHub.

## Testing

* [W3C Markup Validator](https://validator.w3.org/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

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