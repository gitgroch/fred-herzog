<!-- Insert Mobile responsiveness picture here -->

# **Discover Fred Herzog**

![screenshot of site from https://ui.dev/amiresponsive.](/assets/documents/amiresponsive.jpg)


## **Overview**

Discover Fred Herzog is a website for people who wish to find more information about the photographer Fred Herzog

**Target Audience:**

- Existing fans of Fred Herzog
- People discovering Fred Herzog for the first time 
- People who need a point of reference for upcoming events and exhibitions of Fred Herzog 
- People who wish to purchase publications by fred herzog

The website aims to be a one stop destination for everything they need to know about Herzog, showcase his work, where to find his exhibitions and where to buy his publications.

The website can be accessed here: https://gitgroch.github.io/fred-herzog/



## **Planning** 

### **WireFraming** 

I used Balsamiq to roughly plan out some of the initial features and layout of the pages. Desktop and Mobile versions were wireframed side by side which helped me to decide early on how I wanted to approach responsiveness. On the whole, the final design reflects the wireframes, in particular the responsive navigation features in the header and footer of each page. 


![Screenshots of initial wireframe designs made with balsamiq](/assets/documents/wf_bfr_scrn_1.png)
![Screenshots of initial wireframe designs made with balsamiq](/assets/documents/wf_bfr_scrn_2.png)

I would later import some screenshots of the partially built site to help refine some ideas and make notes:

![Screenshots of wireframe design refinements made with balsamiq](/assets/documents/wf_after_scrn_1.png)
![Screenshots of wireframe design refinements made with balsamiq](/assets/documents/wf_after_scrn_2.png)

	
### **Color Schemes** 

I love the aesthetics of Fred Herzog’s book “Modern Color” and wanted to choose a color scheme that reflected that work while still adhering to accessibility guidelines in relation to contrast. I used the tool [coolors.co](https://coolors.co) to generate several color schemes until I arrived at something that met my criteria: 

![screenshot of chosen color scheme](/assets/documents/fh_colorscheme_500px.jpg)

As I wanted the work of Herzog to be the focal point of the page, I decided to use just 3 of the colors out of the scheme to maintain that photography book minimalist feel. 

## **Universal Features** 

### **Typography**

I looked for fonts that complement each other, minimalist and something that the user would expect to find in a Photography book. 

**Fonts:**
- For Headers: [Montserrat](https://fonts.google.com/specimen/Montserrat?query=montserrat)
- For Body text: [Darker Grotesque](https://fonts.google.com/specimen/Darker+Grotesque?)

The fonts are sourced from Google fonts.

**Font Colors**
- Font colors are split into Primary, Secondary, and a Light Option. 
- The Primary color is used for most of the Text including Headers and paragraph texts
- The secondary color is used for accent (e.g. text shadow) or for hover effects 
- The light color is used anywhere text appears on a dark background, e.g. the footer
- Primarily, a darker shade of color is used as the text becomes larger

### **Header Navigation Menus**

The website employs two header navigation menus:

**Desktops and larger screens:**

![screenshot of desktop navigation menu](/assets/documents/desktop_nav_menu.png)

- A standard navigation menu with hover effects to confirm user interaction 


**Mobile and Smaller Screens:**

![screenshot of mobile navigation menu](/assets/documents/mobile_nav_menu.png)

- A hamburger drop down menu that most users would expect from a mobile responsive site.
- The break point of 1000px was chosen to switch menus as this was the screen size that the Desktop nav menu began to overlap with the logo. 
- The nav menus are fixed and appear across all pages on the site to ensure consistency.


### **Footer** 

To maintain the minimalist feeling of the website, the footer consists of just 2 elements Social media Links, and another navigation menu:

![screenshot of footer menu on larger screens](/assets/documents/desktop_footer.jpg)

![screenshot of footer menu on mobile screens](/assets/documents/mobile_footer.jpg)

- Recogniseable social Icons to bring the user (in a new tab) to the relevant social sites with hover effect to confirm interaction.
- Another navigation menu as a quality of life feature for the user to continue to navigate the site when they have reached the bottom of the page.
- The footer is fixed and appears on all pages. 
- A contrasting background color was chosen to confirm the user had reached the end of the page and seperate the footer from other content. 


### **Page Topper:** 

Originally created as hero section for the Gallery page, the design element was converted to a Static “Page Topper” that appears on all other pages which contains the title of each page confirming the user has navigated to the right place.

![screenshot of the page topper from the biography page](/assets/documents/page_topper.jpg)


## **Home Page** 

### **Hero Section**

- The video background is meant to serve as a a wow factor for the user when they landed on the page to draw them into the subject
- The video shows off the work of our subject as well as the man himself, which immediately gives the user an Idea of what to expect 
- The most important element of the hero section i the explore button, flex was used to ensure that the button remained visible as soon as the user lands, regardless of the screen size

![screenshot of the explore button visible when testting with iphone SE template in dev tools](/assets/documents/explore_btn_iphoneSE.jpg)

### **Explore section** 

- A static “Explore” section was created to anchor the Hero Button and bring the user to the relevant section of the site. 
- The Main section consists of 4 cards that gives the user the choice of where to go next with information describing each section. 
- The user can either click on the “Learn More” button or click on the image which has a hover effect applied to confirm that they can do so. 
- Flex was used in this section to maintain responsiveness on all screen sizes 

![screenshot of the explore section](/assets/documents/explore_section.jpg)

#### **Bugs:** 
- On some screen sizes the 4th flex box will position below the other three and expand across the page. Everything remains fully functional, but the aesthetic is a bit weird. I beleive this is just a consequence of using flex, and as it affects a small number of users and is not app breaking, this will be a future fix 

#### **Future Enhancements:**
- Animations could be given to each card when they appear on screen to make them more appealing, either a fade in, or an expand effect


## **Biography Page** 

![screenshot of text wrapping around image on the Biography page](/assets/documents/biography.jpg)

- The biography page consists of 3 sections providing information about the life of fred herzog. 
- Each section of text is paired with an image that is relevant to what the user has read. 

#### **Bugs:** 
- No current bugs 

#### **Future Enhancements:**
- The Biography page could be more interactive.
- Making the images clickable to expand would provide a more satisfying user experience.
- Adding external links to the text to provide more content would make the Biography page more interactive.

## **Gallery Page** 

![screenshot of a lightbox used in the gallery page](/assets/documents/gallery_lightbox.jpg)

- The gallery page consists of 11 selected images from Herzog’s catalogue 
- The images have a hover effect applied to confirm to the user that they can be clicked. 
- Clicking the image will make it larger and show some text describing the image or more information about Herzog. 

#### **Bugs:** 
- When expanded, the portrait cards allow for only limited amount of text before the layout is broken.
    -  As adding the lighthouse feature was ambitious to start with, and works as intended, this fix is out of scope for this iteration of the project and can be addressed in future updates.
- The Gallery page only scores 54 for mobile devices and 79 for Desktop.
    - Lighthouse recommends implementing an efficient cache policy to resolve this issue, this is something that currently falls outside the scope of this project and can be added as further fix
#### **Future Enhancements:**
- Better arrangement of Images in the Gallery
- Add an information section to give context to the Gallery 
- Add additional media queries to serve resized images for mobile devices to enhance performances 
- Add caching policy to enhance performance 

## **Contact Page** ##

- A very simple contact page was created to submit questions to the website operators 
- As we are working only on the front end, this is form does not "POST" any data, and instead redirects the user to a form submission page to mimic how it should work.

#### **Bugs:**
- None Identified 
#### *Future Enhancements:**  
- The form page is functional but quite sparse, future iterations could add aditional style elements to make the page more attractive

## **Testing:**

A seperate document has been created to detail Testing, Validation, Bugs and Fixes, which can be forund [here](/FIXLOG.md).

- [FIXLOG](/FIXLOG.md)

## **Future Enhancement**



## **Deployment** 

The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://gitgroch.github.io/fred-herzog/

## **Credits, Acknowledgements and Notes on Development** 

### **Development Notes**

#### **Use of Variables** 

- One of the most important things I learned during the development of the site, was CSS variables. It gave me the ability to define colors, font families, font sizes, font weights etc. at the beginning of the project and then call on them throughout the project. 

- For example for each color chosen as part of the scheme, I created three shades that could be used for different purposes such as headers subheaders and body text.

![screenshot of some of the css variables used in the project](/assets/documents/variables.JPG)

- I feel that this enabled me to maintain a consistent theme throughout the project, and saved a huge amount of time. 



#### **Cube CSS** 

- Like discovering variables, discovering that there were different methodologies in arranging CSS code was a bit of a revelation. I discovered the [CUBE (Composition Utility Block Exception) CSS](https://cube.fyi/) methodology about half way through development and tried to implement it into my workflow
- While I didn’t implement everything from the process, it definitely helped with the remainder of my work, and will be something I will research more and implement for future projects. 


### **Credits and Acknowledgements** 

I made use of numerous tutorials and guides in the creation of this project. No code was taken verbatim from these tutorials, instead they were used to write code that adapted to my project. Special mention goes to [Kevin Powell's](https://www.youtube.com/kepowob) Youtube channel as he was a wealth of information which helped expand on what I learned in the course. 

#### General Tutorials 

- [CUBE CSS Methodology Guide by Andy Bell](https://cube.fyi/)
- [CSS Clamp Tutorial by Andy Bell](https://piccalil.li/tutorial/fluid-typography-with-css-clamp/)
- [Learn CSS Grid the easy way by Kevin Powell](https://youtu.be/rg7Fvvl3taU)
- [Layouts with CSS Grid by Kevin Powell](https://youtu.be/S-5bGqNcNcU)
- [CSS Variables - An introduction to CSS custom properties by Kevin Powell](https://youtu.be/PHO6TBq_auI)

#### Utility Specific Tutorials

- Applying Video as Background: [How to create a background video by Kevin Powell](https://youtu.be/RIDA6elhmBU)
- Applying Video as Background: [Create a Website With Video Background | HTML & CS by Traversy Media](https://youtu.be/8MgpE2DTTKA)
- Hover Effects and Before & After Use: [CSS Before and After pseudo elements explained by Kevin Powell](https://youtu.be/djbtPnNmc0I)
- Navbar : [Create a responsive navigation nav with no JS! - By Kevin Powell](https://youtu.be/8QKOaTYvYUA)
- Gallery Page Lightbox: [Create a CSS only lightbox! by Kevin Powell](https://youtu.be/6j5q-hP8sfk)

#### Media & Content
- Background Video: [A Window Looking In: Fred Herzog by Imagine Create](https://vimeo.com/22104316)
- Photographs used throughout [The Estate of Fred Herzog](https://www.equinoxgallery.com/our-artists/fred-herzog/)
- Biography [Fred Herzog - Wikipedia](https://en.wikipedia.org/wiki/Fred_Herzog)