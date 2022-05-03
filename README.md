<!-- Insert Mobile responsiveness picture here -->

# **Discover Fred Herzog**




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

I used Balsamiq to roughly plan out some of the initial features and layout of the pages. I used Balsamiq to plan out Desktop and Mobile versions side by side which helped me to decide early on how I wanted to approach responsiveness. On the whole, the final design reflects the wireframes, in particular the responsive navigation features in the header and footer of each page. 

![Screenshots of initial wireframe designs made with balsamiq](/assets/documents/wf_bfr_scrn_1.png)
![Screenshots of initial wireframe designs made with balsamiq](/assets/documents/wf_bfr_scrn_2.png)

I would later import some screenshots of the partially built site to help refine some ideas and make notes:

![Screenshots of wireframe design refinements made with balsamiq](/assets/documents/wf_after_scrn_1.png)
![Screenshots of wireframe design refinements made with balsamiq](/assets/documents/wf_after_scrn_2.png)

	
### **Color Schemes** 

I love the aesthetics of Fred Herzog’s book “Modern Color” and wanted to choose a color scheme that reflected that work while still adhering to accessibility guidelines in relation to contrast. I used the tool coolors.co to generate several color schemes until I arrived at something that met my criteria: 

![screenshot of chosen color scheme](/assets/documents/fh_colorscheme_500px.jpg)

As I wanted the work of Herzog to be the focal point of the page, I decided to use just 3 of the colors out of the scheme to maintain that photography book minimalist feel. 


## **Universal Features** 

### **Typography**

The fonts chosen complement each other, are minimalist and something that the user would expect to find in a Photography book. 

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

### **Nav menu**

The website employs 2 Nav menus:

- **Desktops and larger screens:**

- A standard navigation menu with hover effects to confirm user interaction 


**Mobile and Smaller Screens:**

- A  hamburger drop down menu that most users would expect from a mobile responsive site

- The break point of <insert media query> was chosen as this was the screen size that the Desktop nav menu began to overlap with the logo. 

- The nav menus are fixed and appear across all pages on the site to ensure consistency 


### **Footer** 

I wanted to maintain the minimalist feeling of the website so the footer consists of just 2 elements:

- **Social Icons:**
    - Recogniseable social Icons to bring the user (in a new tab) to the relevant social sites 
    - Another navigation menu as a quality of life feature for the user to continue to navigate the site when they have reached the bottom of the page
    - The footer is fixed and appears on all pages 
    - A contrasting background color was chosen to confirm the user had reached the end of the page and seperate the footer from other content. 


### **Page Topper:** 

I originally created a hero section for the Gallery page but liked the aethstetic and decided to create a Static “Page Topper” that appears on all other pages which contains the title of each page confirming the user has navigated to the right place.


## **Home Page** 


### **Hero Section**

- I wanted a wow factor for the user when they landed on the page and decided to implement a video that I found as the hero section background. 
- The video shows off the work of our subject as well as the man himself, which immediately gives the user an Idea of what to expect 
- The most important element of the hero section was the explore button and I wanted to be sure that all users regardless of screen size saw this when they landed,  I used flex to achieve the responsiveness required to achieve this 


### **Explore section** 

- A static “Explore” section was created to anchor the Hero Button and bring the user to the relevant section of the site. 
- The Main section consists of 4 cards that gives the user the choice of where to go next with information describing each section. 
- The user can either click on the “Learn More” button or click on the image which has a hover effect applied to confirm that they can do so. 
- Flex was used in this section to maintain responsiveness on all screen sizes 


#### **Bugs:** 
- 

#### **Future Enhancements:**
- 



## **Biography Page** 

- The biography page consists of 3 sections providing information about the life of fred herzog. 
- Each section of text is paired with an image that is relevant to what the user has read. 

#### **Bugs:** 
- 
#### **Future Enhancements:**
- 


## **Gallery Page** 

- The gallery page consists of 11 selected images from Herzog’s catalogue 
- The images have a hover effect applied to confirm to the user that they can cbe clicked. 
- Clicking the image will make it larger and show some text describing the image or more information about Herzog. 

#### **Bugs:** 
- 
#### **Future Enhancements:**
- 

## **Testing:**


Validator Testing 
Unfixed Bugs 
Future Enhancements 

## **Deployment** 

The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://gitgroch.github.io/fred-herzog/

## **Credits, Acknowledgements and Notes on Development** 

## Development Notes 

### **Use of Variables** 

- One of the most important things I learned during the development of the site, was CSS variables. It gave me the ability to define colors, font families, font sizes, font weights etc. at the beginning of the project and then call on them throughout the project. 

- For example for each color chosen as part of the scheme, I created three shades that could be used for different purposes such as headers subheaders and body text.

![screenshot of some of the css variables used in the project](/assets/documents/variables.JPG)

- I feel that this enabled me to maintain a consistent theme throughout the project, and saved a huge amount of time. 



### **Cube CSS** 

- Like discovering variables, discovering that there were different methodologies in arranging CSS code was a bit of a revelation. I discovered the CUBE (Composition Utility Block Exception) CSS methodology about half way through development and tried to implement it into my workflow
- While I didn’t implement everything from the process, it definitely helped with the remainder of my work, and will be something I will research more and implement for future projects. 


## Credits and Acknowledgements 