# **Gareth John – Professional Portfolio and Resume**

The purpose of this website is to create an online presence for an individual (myself in this case) to highlight skills, experience, work history and to showcase projects to potential employers. This must be achieved in a visually appealing UXD, which enables the user to easily navigate and locate the information irrespective of the device they are using.
The ultimate aim is to assist the individual to secure future employment opportunities as a software developer, by showcasing acquired skills of the technologies used.


Table of contents

______

## **UX**

My aim is to provide a simple yet intuitive user experience, which requires the minimum amount of scrolling to locate information. I see this as particularly important on mobile screens.

For this reason I had elected to maintain a fixed menu bar at the top of the screen.

### **User Stories**

1. **_As a_** job seeker, **_I need to_** promote my skills and experience in an efficient and visually appealing way; **_in order to_** increase my chances of being interviewed and ultimately employed.

1. **_As a_** Hiring Manager/HR, **_I need to_** quickly establish if the candidate has the required skills and experience; **_in order to_** recommend them to the business and select them for interview

1. **_As a_** Technical Manager, **_I need to_** determine technical proficiency and if the candidate has the skills and experience, I am looking for; **_in order to_** bring them into my team be confident they can add value

1. **_As a_** Recruiter, **_I need to_** quickly establish if the candidate has the required skills and experience; **_in order to_** increase my chances of successfully placing the candidate with my portfolio of clients.

#### **Strategy**  
As previously stated, the aim of this project is 3 fold:
 - To create an online presence
 - To highlight skills, and work experience 
 - To showcase projects  
 ... all with the aim of increasing the individuals employability
 
The intention is to draw the user in and make access to the key information easily accessible through an intuitive and repeating UX design. The intention is to provide multiple routes top the skills, experience and work history as well as multiple links to the downloadable CV.
- Multiple links to Experience section from Landing page.
- Consice listing of skills
- Abridged version of work history
- Multiple links to a downloadable CV
- Portfolio page with Porject summaries and links to the deployed pages

#### **Scope**  
I want to challenge myself to produce something I was proud to put my name on, without overextending myself and causing scope creep. I was aware that I needed to keep the content within the scope of my current knowledge, this would be critical if I encountered any issues during the build and needed to troubleshoot on the fly. 

#### **Structure**  
I plan to maintain a common navbar and footer section throughout the website to create an intuitive UX.  
 - In the end, there was a deliberate change to the &quot;CONTACT&quot; section on the contact.html page. Given that this page will have all the necessary contact information on it I decided to change the footer section to &quot;ABOUT ME&quot;
In all other pages it makes sense to have the contact info displayed; and equally here the user is reminded of the candidates key skills (as opposed to doubling up the contact information). 

I liked the idea of splitting the information into two sections 1/3 and 2/3 widths respectively, and intend to borrow this layout from the UCD Resume Walkthrough project. I intend to recreate this structure without copying the code from that exercise.
I wanted to list the shorter strings of data which could be bulletted and short paragraphs in the left hand (1/3 section), and reserve the main portion of the page for the bulk of the information. 
 - I believe I have achieved this whithout directly copying the code. 

#### **Skeleton** 
Website comprising four main pages navigable through the 'navbar': 
- Home | Experience | Portfolio | Contact 

A Footer section with links to social media sites and email, and a download link for the CV. I have also included a copyright statement.  
A Download link incorporated into both 'navbar' and footersections.

#### **Surface**
I had intended to use a darker colour scheme for this website. However as the build progressed it just didn't seem to suit; being too cold and serious. Of all aspects of this build I will freely admit this was the area I struggled with the most.  
In the end I sought inspiration from two websites  
https://www.shutterstock.com/blog/10-gorgeous-color-schemes-for-websites?kw=&gclsrc=aw.ds&gclid=Cj0KCQjw2or8BRCNARIsAC_ppyaGHtDUv5oNSHP0th9gb8N6VBiGFAq-pYu1cFQFW5szceQETvoAnKgaAhwPEALw_wcB)  

https://www.quicksprout.com/trending-website-color-schemes/  
 - I am pleased with the result; it isn't too playful or childish, yet isn't cold and boring. It provides a decent amount of contrast.  
##### **Typography**  

##### **Imagery** 
I want the images to convey my journey from working on oil rigs to coding websites and have attempted to pick appropriate iamges.
However, given the intended purpose of this site is to convey my skills, experience and work history I have limited the use of images, prefering to focus on these aspects.  
I have attempted to sneak in the odd image where appropriate - particularly in the portfolio section, where I wanted to shoe a preview of the various projects landing pages.
______

## **Features**

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### **Existing Features**
- Website comprising four distict pages linked by the use of a navbar.
- Navbar – I have selected a bootstrap responsive navbar to achieve plug and play functionality. 
  - Despite having a logo I have chosen to keep the 'Home' link to reduce confusion
- Resume page with links to individual companies websites - enables the user to learn more. 
  - An 'accordion' feature which enables the user to find out a little more about each role in the work histry section.
- Portfolio page with links to individual projects. Links have been disabled where appropriate.
- Contact page with a google map iframe and a contact form (currently linked to the CI form dump)
- ...

### **Features Left to Implement**

- I would eventually like to complete the Contact form so it is connected to an email API (currently lacking the JavaScript skills).

______

## **Technologies Used**  

This static website has been built using the following core technologies:

Core coding languages

- ![alt text](https://github.com/GazzaJ/GarethJohn-Resume-and-Portfolio/blob/master/readme-images/html5-logo.png "HTML5 logo") HTML5
- CSS3

Intergrations

- Bootstrap 4
- Font Awesome
- Google Fonts
- JQuery
- The project uses JQuery to simplify DOM manipulation.
- Hover.css for button hover effects

Version Control, storage and hosting

- Gitpod
- Git
- GitHub

Other

- Word to Markdown Converter
______

## **Testing**

The philosophy I have used throughout this build is to build and test each part of the website as I progressed, relying heavily on Google Dev tools throughout.

There are two key elements in the 'user stories'

1. Highlighting skills and experience
2. Ensuring easy access of the data

 **Highlighting Skills and Experience** 

I'd like to think I have achieved this by locating my key skills and experience under a clearly defined 'Experience' page accessible via the 'navbar' or a button towards the bottom of the landing page.
 The intention of the landing page was to have sufficient information and imagery to incite curiosity in the user to want to learn more.

I have located the progress bars, key skills and experience down the left hand 1/3 of the page. I am happy with the aesthetics of this section, and believe it achieves the goal. In using this layout, I have bucked some CV conventions by intentionally having the bulleted skills and experience display first. I believe this is what recruiters/employers will want to quickly ascertain, before reading any further.
 The remaining 2/3 of the page comprises the Work history. There is a danger, with 25yrs experience, is this could take up too much space and simply be a mass of text, most users won't want to scroll through. Therefore, I decided early on to only provide a brief overview of each position and locate this in such a way the user could chose what, or how much they wanted to read.

 **Ensuring Easy Access to Information** 

To ensure quick and easy access to the important information like skills, experience and work history, I wanted multiple links to the 'Experience' page. Thus I located a button to link to the 'Experience page' as an quick link to the information, saving the user from having to scroll back up to the menu.
 There is also a link to this page in the 'navber'.
 For a deeper understanding of the candidates skills and experience I provided Download links to a PDF of the full CV in both the 'navbar' and footer section of each page, which when clicked, open up a new tab displaying the full CV.

- Repeatedly tested the 'navbar' links throughout development to ensure correct navigation.
- I used DevTools extensively during development, changing devices, to ensure the desired responsive behaviour was achieved.
  - This helped to highlight an issue I had with Divs and whitespace on the right hand side.
- Once roughly 50% complete I deployed the website to Git Pages and viewed the output on several real devices:
  - Samsung Galaxy S9
  - Samsung Tab A10
  - HP Laptop with attached monitor
- I tested the functionality of the 'accordion' feature on the Experience page on these devices to ensure aesthetics and functionality were maintained.
- Tested all links to ensure they function and correctly open up the required sites in new browser tabs.
- Tested Social Media icon to ensure they also link to the correct sites and open in new browser tabs.
- I have tested email links to ensure they open up the default email application and insert the email address.
  - Works on Samsung S9 – opening Gmail
  - Laptop – opening Outlook
- Tested the contact form on the Contact page to ensure correct functionality. This was linked to the CI Form dump page so I could verify the data sent.
- Testing of the 'required' attribute which ensures all contact form field get filled in before the data can be sent.
- I have tested the email address entry on the Contact form to ensure correctly formatted email addresses can be entered _e.g_ [_name@something.com_](mailto:name@something.com)
- Accessibility Test
  - Highlighted potential issue with the choice text color on the navbar
  - Highlighted an issue with the contrast of the text with links.
- HTML Validation
- CSS Validation
- CSS Auto Prefixer
- Mobile Friendly
- Website speed test
  - Passed in all but Security
- I forwarded the link to the website to friends to view and provide feedback. This was initially done at about 75% complete and again once 100% complete.

______

## **Bugs and Issues**

- Initially the collapsed Menu items would not appear and disappear when clicking the 'burger'.
  - The solution to this was found in the Slack community (); and was simply a case of relocating one of the bootstrap CDN links to the 'head'


- While building the navbar toggler, the menu items would only appear on the right.
  - The solution was provided on stackoverflow ([https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393])([https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393])


- My navbar had a small amount of whitespace on the right-hand side.
  - The solution to remove this was again found on stackoverflow: ([https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687])([https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687])


- When I initially created cards for my portfolio projects each one was sized dependent on the content, which was undesirable. I found a solution to this here: ([https://www.codeply.com/go/jbcgzs2Nzq])  

- I used the code listed on this site to push the card button down to the bottom of the card. ([https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card])

- Throughout the build I had an issue with there being whitespace down the right hand side of my pages. The issue wasn't immediately obvious, until I created boxes around every element; which highlighted some divs were wider than the remainder of the page.
 This was a useful method to visualise the interaction of all page elements.([https://stackoverflow.com/questions/46630191/white-space-on-right-side-of-page/46630298])

______

## **Deployment**

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

______

## **Resources**

I have attempted to work as independently as much as possible while building this website, choosing to solve my own issues using web resources wherever possible. Thus my main resource throughout this project was the trusty Google search.
 Aside from Google I have made use of the following resources:-

- Balsamiq – Wireframing Tool
- Free Logo Maker - Simple drawing tool used to create a brand logo
- Code Institute course material and Walkthrough projects
- Google DevTools - for trouble shooting and 
- StackOverFlow – Web based 
- CSS Tricks – Web
- W3C –
- Pexels – Licence free image repository
- TinyPNG – Application for compressing image files
- Color Picker – HTML &amp; CSS color codes
- Shutterstock: 10 Gorgeous Color Schemes for Websites
- 10 Trending 2020 Website Color Schemes
- Am I responsive?

______

## **Credits**

### **Content**

- The text for section Y was copied from the Wikipedia article Z

### **Media**

The photos used in this site were obtained from:

- Image of the Rig – Was taken by me on a visit to West Texas in 2018
- The remaining images were downloaded from the Pexels App.

### **Code Snippets**

- Bootstrap responsive navbar
- While building the navbar toggler, the menu items would only appear on the right.
  - The solution was provided on stackoverflow ([https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393](https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393))
- My navbar had a small amount of whitespace on the right-hand side.
  - The solution to remove this was again found on stackoverflow: ([https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687](https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687))
- Image carousel on the landing page was copied from Bootstrap 4.
- **Progress bars**
The progress bars used in resume.html were taken from Bootstrap 4
- **Accordion Feature**
I copied the accordion feature fromthe tutorial provided on this webpage[**https://supfort.com/font-awesome-accordion-arrow-css**](https://supfort.com/font-awesome-accordion-arrow-css) **.**
The reason for not using the standard Bootstrap accordion was that I wanted to visually indicate there was additional content hidden within each role.
- **Unordered list icons
 The code to achieve better looking bullets was taken from Bootstrap**[**https://fontawesome.com/how-to-use/on-the-web/styling/icons-in-a-list**](https://fontawesome.com/how-to-use/on-the-web/styling/icons-in-a-list)

### **Acknowledgements**

- The idea for this project originally came from a basic Resume exercise to illustrate ordered and unorder I had worked on while using the Mimo app&#39; (https://getmimo.com/playgrounds/812454) prior to starting the Full Stack Software Development course at the Code Institute.

I subsequently expanded the basic exercise to create an online resume.

- I'd like to thank my mentor Sinead O'Brian for her direct feedback and advice in the run up to, and during this project.

- Further inspiration came from the UCD-Resume project in the CI User Centric Frontend module. I particularly identified with the thirds concept for separating the content.

- I'd like to acknowledge the guidance we received in an MS-1 planning call with :-

- Jim Morel

- John Traas

- Anthony O'Brien

…the information they presented was invaluable.
______
