<!-- Insert Mobile responsiveness picture here -->

# **Discover Fred Herzog**

![screenshot of site from https://ui.dev/amiresponsive.](/assets/docs/screenshots/amiresponsive.webp)


## **Overview**

Discover Fred Herzog is a website for people who wish to find more information about the photographer Fred Herzog

Target Audience:

- Existing fans of Fred Herzog
- People discovering Fred Herzog for the first time 
- People who need a point of reference for upcoming events and exhibitions of Fred Herzog 
- People who wish to purchase publications by fred herzog

User Stories:

- As a fan of Fred Herzog, I would like a website that will allow me to easily find out more about the photographer and find 
books that I can purchase to enjoy his work in person. I would like the design of the website to be consitent with what I would expect from my knowledge of Fred Herzog. 
- As someone who has just discovered Fred Herzog, I would like a website that I can easily navigate to find out more information and view some of his best work. I would like to be able to contact someone for more information if I had questions about Fred Herzog. 

The purpose of the website is to provide the above target users with:

- A place to learn more about the work of Fred Herzog 
- A sample of Fred Herzogs work 
- A resource for the users to find Books published by or about Fred Herzog 

The development Goals for the Website were to:

-   Create a website that shares the aethstetic of Fred Herzog's Book "Modern Color" - ACHIEVED 
-   Provide a biography page to inform users about Herzog's life - ACHIEVED
-   Provide a gallery with selected works from Herzog - ACHIEVED 
-   Provide a page that users can find a place to purchase related publications - ACHIEVED
-   Provide a means of contacting the curator of the website with any questions about Herzog or his work. - ACHIEVED
-   Provide a resource where users can find information about exhibitions featuring Herzog - NOT ACHIEVED
    -   Due to time restraints this feature is not included in the initial deployment, and not required for a "minimum viable product". This has been added as a future enhancement.


The website can be accessed here: https://gitgroch.github.io/fred-herzog/



## **Planning** 

### **WireFraming** 

I used Balsamiq to roughly plan out some of the initial features and layout of the pages. Desktop and Mobile versions were wireframed side by side which helped me to decide early on how I wanted to approach responsiveness. On the whole, the final design reflects the wireframes, in particular the responsive navigation features in the header and footer of each page. 


![Screenshots of initial wireframe designs made with balsamiq](/assets/docs/screenshots/wf_bfr_scrn_1.webp)
![Screenshots of initial wireframe designs made with balsamiq](/assets/docs/screenshots/wf_bfr_scrn_2.webp)

I would later import some screenshots of the partially built site to help refine some ideas and make notes:

![Screenshots of wireframe design refinements made with balsamiq](/assets/docs/screenshots/wf_after_scrn_1.webp)
![Screenshots of wireframe design refinements made with balsamiq](/assets/docs/screenshots/wf_after_scrn_2.webp)

	
### **Color Schemes** 

I love the aesthetics of Fred Herzog’s book “Modern Color” and wanted to choose a color scheme that reflected that work while still adhering to accessibility guidelines in relation to contrast. I used the tool [coolors.co](https://coolors.co) to generate several color schemes until I arrived at something that met my criteria: 

![screenshot of chosen color scheme](/assets/docs/screenshots/fh_colorscheme_500px.webp)

As I wanted the work of Herzog to be the focal point of the page, I decided to use just 3 of the colors out of the scheme to maintain that photography book minimalist feel. 

## **Universal Features** 

### **Typography**

I looked for fonts that complement each other, minimalist and something that the user would expect to find in a Photography book. 

**Fonts:**
- For Headers: [Montserrat](https://fonts.google.com/specimen/Montserrat?query=montserrat)
- For Body text: [Darker Grotesque](https://fonts.google.com/specimen/Darker+Grotesque?)
- Backup font: Sans Serif

The fonts are sourced from Google fonts.

**Font Colors**
- Font colors are split into Primary, Secondary, and a Light Option. 
- The Primary color is used for most of the Text including Headers and paragraph texts
- The secondary color is used for accent (e.g. text shadow) or for hover effects 
- The light color is used anywhere text appears on a dark background, e.g. the footer
- Primarily, a darker shade of color is used as the text becomes larger

### **Header Navigation Menus**

- The website employs two header navigation menus that include all front facing pages on the website. The navigation menus are fully responsive and change styles depending on the screen size. 
- The menus allow the user to easily navigate across the website, discouraging the use of browser back button.

**Desktops and larger screens:**

![screenshot of desktop navigation menu](/assets/docs/screenshots/desktop_nav_menu.webp)

- A standard navigation menu with hover effects to confirm user interaction 


**Mobile and Smaller Screens:**

![screenshot of mobile navigation menu](/assets/docs/screenshots/mobile_nav_menu.webp)

- A hamburger drop down menu that most users would expect from a mobile responsive site.
- The break point of 1000px was chosen to switch menus as this was the screen size that the Desktop nav menu began to overlap with the logo. 
- The nav menus are fixed and appear across all pages on the site to ensure consistency.


### **Footer** 

- In keeping with the minimilist theme of the site, the Footer contains 2 elements, links to social media sites, as well as an additional navigation menu.
- The social media links are important because they allow the user to easily access more content from Herzog.
    -   Note: Fred Herzog does not have a wide presence on social media bar Instagram, but I still wanted to include this element in the project. With the exception of Instagra, the social media links currently point to their respective home pages. 
- The additional navigation menu is valuable to the user as they do not have to scroll back to the top of the page to continue browsing the site.
- The footer is fixed and appears on all pages. 
- A contrasting background color was chosen to confirm the user had reached the end of the page and seperate the footer from other content. 


![screenshot of footer menu on larger screens](/assets/docs/screenshots/desktop_footer.webp)

- A contrasting background color was chosen to confirm the user had reached the end of the page and seperate the footer from other content. 

![screenshot of footer menu on mobile screens](/assets/docs/screenshots/mobile_footer.webp)


# Features

## **Home Page** 

- The homepage includes a hero section to draw the user in, an information section to inform the user of the sites purpose, and an explore section that describes the pages available to them on the site. 
- The homepage is designed to be minimilist in order to not overwhelm the user with too much information and allow them to decide where theyt would like to go next in comfort.

### **Hero Section**
- The video background is meant to serve as a a wow factor for the user when they land on the page to draw them into the subject.
- The video displays Fred Herzog and his work, which immediately gives the user an idea of what to expect.
- The most important element of the hero section is the explore button, flex combined with media queries is used to ensure that the button remains visible as soon as the user lands, regardless of the screen size.
- The explore button will bring the user to the Explore section of the webpage to allow them to continue to navigate through the website.

![screenshot of the explore button visible when testting with iphone SE template in dev tools](/assets/docs/screenshots/explore_btn_iphoneSE.webp)

### **Explore section** 

- A static “Explore” section was created to anchor the Hero Button and bring the user to the relevant section of the site. 
- The Main section consists of 3 cards that gives the user the choice of where to go next with information describing each section. 
- The user can either click on the “Learn More” button or click on the image which has a hover effect applied to confirm that they can do so. 
- Flex was used in this section to maintain responsiveness on all screen sizes
- This may be an over abundance of navigation options, that clickable images is an expected behaviour, so I decided to keep it.

![screenshot of the explore section](/assets/docs/screenshots/explore_section.webp)

#### **Bugs:** 
- On some screen sizes the 3rd flex box will position below the other three and expand across the page. Everything remains fully functional, but the aesthetic is a bit strange. I believe this is just a consequence of using flex, is not app breaking, this will be a future fix.

#### **Future Enhancements:**
- Animations could be given to each card when they appear on screen to make them more appealing, either a fade in, or an expand effect
- Fix layout at different screen sizes to avoid 3rd box stretching across screen.


## **Biography Page** 

![screenshot of text wrapping around image on the Biography page](/assets/docs/screenshots/biography_exmp.webp)

- The biography page consists of 3 sections providing information about the life of fred herzog. 
- Each section of text is paired with an image that is relevant to what the user has read. 

#### **Bugs:** 
- No current bugs 

#### **Future Enhancements:**
- The Biography page could be more interactive.
- Making the images clickable to expand would provide a more satisfying user experience.
- Adding external links to the text to provide more content would make the Biography page more interactive.

## **Gallery Page** 

- The gallery page allows the user to view a selection of work Herzog’s catalogue, and learn more about them. 
- The images have a hover effect applied to confirm to the user that they can be clicked. 
- Clicking the image will make it larger and show some text describing the image or more information about Herzog. This provides a high level of interactivity for the user and encourages them to spend more time in the gallery. 

![screenshot of a lightbox used in the gallery page](/assets/docs/screenshots/gallery_lightbox.webp)

#### **Bugs:** 
- When expanded, the portrait cards allow for only limited amount of text before the layout is broken.
    -  The feature currently works with the text included, this can be addressed in future updates if the text needs to be updated.
    
#### **Future Enhancements:**
- Better arrangement of Images in the Gallery
- Add an information section to give more context to the Gallery 

## **Publication Page** 
- The publication page allows the user to browsr the available publications featuring Fred Herzog and links to the page where they can be purchased by clicking the buttons on each card (opens in a new tab).

![screenshot of a publication page section displaying a book of fred herzog's work](/assets/docs/screenshots/publication_page.jpg)

#### **Bugs:**
- None Identified
#### **Future Enhancements:**
- None planned at this time

## **Contact Page** 

- This page includes a simple contact form to allow users to submit questions to the website operators or to sign up for the newsletter
    - Note: As we are working only on the front end, this is form does not "POST" any data, and instead redirects the user to a form submission page to mimic how it should work.
- It also includes a call to action to use the form as well as some useful information which allows the user to click on links that bring them to the source of the video from the home page, as well as Herzog's official site at the Equinox Gallery. Both websites open in new tabs when clicked.

![screenshot of the contact form and useful information page](/assets/docs/screenshots/contact_page.JPG)

#### **Bugs:**
- None Identified 
#### **Future Enhancements:**  
- The form page is functional but quite sparse, future iterations could add aditional style elements to make the page more attractive.

## **Testing:**

A seperate document has been created to detail Testing, Validation, Bugs and Fixes, which can be forund [here](/FIXLOG.md).

- [FIXLOG](/FIXLOG.md)

## **General Future Enhancement**

- Add a page to the site to provide information about Exhibitions 
    -   The page should have: Name, Address and Contact Details of the Gallery 
    -   A description of works on Exhibition 
    -   A map to locate the exhibition 
- Replace the CSS "workaround" solutions for the mobile navigation hamburger menu with a JavaScript solution 
- Replace the Gallery CSS Lightboxes with a more apropriate and better performing JavaScript solution 
- Leverage variables with media queries to improve consistency and clarity.


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

![screenshot of some of the css variables used in the project](/assets/docs/screenshots/variables.webp)

- I feel that this enabled me to maintain a consistent theme throughout the project, and saved a huge amount of time. 
- As development progressed I recognised times where I could have created more variables, and also have leveraged them with media queries to help maintain consistency. I will take this learning to future projects. 

#### **Cube CSS** 

- Like discovering variables, discovering that there were different methodologies in arranging CSS code was a bit of a revelation. I discovered the [CUBE (Composition Utility Block Exception) CSS](https://cube.fyi/) methodology about half way through development and tried to implement it into my workflow
- While I didn’t implement everything from the process, it definitely helped with the remainder of my work, and will be something I will research more and implement for future projects. 

#### **CSS Reset**

- I found [Andy Web's CSS reset](https://piccalil.li/blog/a-modern-css-reset/) while researching CUBE CSS and I found it to be a very useful set of Universal defaults that I will continue to use for future projects

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
- [A Modern CSS Reset by Andy Bell](https://piccalil.li/blog/a-modern-css-reset/)
- [How to style forms with CSS by Supun Kavinda](https://blog.logrocket.com/how-to-style-forms-with-css-a-beginners-guide/)

#### Media & Content
- Background Video: [A Window Looking In: Fred Herzog by Imagine Create](https://vimeo.com/22104316)
- Photographs used throughout [The Estate of Fred Herzog](https://www.equinoxgallery.com/our-artists/fred-herzog/)
- Biography [Fred Herzog - Wikipedia](https://en.wikipedia.org/wiki/Fred_Herzog)