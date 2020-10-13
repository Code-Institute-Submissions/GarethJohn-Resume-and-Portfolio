# **Gareth John – Professional Portfolio and Resume**

The purpose of this website is to create an online presence for the person to highlight skills, experience, work history and to showcase their projects to potential employers in a visually appealing format, which enables them to easily navigate and locate the information

The ultimate aim is to assist the individual (me in this case) to secure employment as a software developer at some stage in the near future.

Table of contents

## **UX**

My aim is to provide a simple yet intuitive user experience, which requires the minimum amount of scrolling to locate information. I see this as particularly important on mobile screens.

For this reason I had elected to maintain a fixed menu bar at the top of the screen.

**User Stories**

1. _ **As a** _job seeker, _ **I need to** _promote my skills and experience in an efficient and visually appealing way; _ **in order to** _increase my chances of being interviewed and ultimately employed.

1. _ **As a** _Hiring Manager/HR, _ **I need to** _quickly establish if the candidate has the required skills and experience; _ **in order to** _recommend them to the business and select them for interview

1. _ **As a** _Technical Manager, _ **I need to** _determine technical proficiency and if the candidate has the skills and experience, I am looking for; _ **in order to** _bring them into my team be confident they can add value

1. _ **As a** _Recruiter, _ **I need to** _quickly establish if the candidate has the required skills and experience; _ **in order to** _increase my chances of successfully placing the candidate with my portfolio of clients.

There is a deliberate change to the &quot;CONTACT&quot; section on the contact.html page. Given that this page will have all the necessary contact information on it I decided to change the footer section to &quot;ABOUT ME&quot;
 In all other pages it makes sense to have the contact info displayed; and equally here the user is reminded of the candidates key skills (as opposed to doubling up the contact information).

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## **Features**

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### **Existing Features**

- Navbar – I have selected a bootstrap responsive navbar to achieve plug and play functionality.
 Despite having a logo I have chosen to keep the &quot;Home&quot; as this is a link to reduce confusion
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### **Features Left to Implement**

- Another feature idea

## **Technologies Used**

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- HTML5
- CSS3
- Bootstrap 4
- Font Awesome
- Google Fonts
- JQuery
- The project uses JQuery to simplify DOM manipulation.

## **Testing**

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you&#39;ve done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:

i. Go to the &quot;Contact Us&quot; page

ii. Try to submit the empty form and verify that an error message about the required fields appears

iii. Try to submit the form with an invalid email address and verify that a relevant error message appears

iv. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven&#39;t addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## **Bugs &amp; Issues**

- Initially the collapsed Menu items would not appear and disappear when clicking the &#39;burger&#39;.
  - The solution to this was found in the Slack community (); and was simply a case of relocating one of the bootstrap CDN links to the \&lt;head\&gt; section


- While building the navbar toggler, the menu items would only appear on the right.
  - The solution was provided on stackoverflow ([https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393](https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393))
- My navbar had a small amount of whitespace on the right-hand side.
  - The solution to remove this was again found on stackoverflow: ([https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687](https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687))
-

## **Deployment**

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## **Credits**

### **Content**

- The text for section Y was copied from the Wikipedia article Z

### **Media**

The photos used in this site were obtained from:

- Image of the Rig – Was taken by me on a visit to West Texas in 2018
- Pexels

### **Code Snippets**

- Bootstrap responsive navbar
- While building the navbar toggler, the menu items would only appear on the right.
  - The solution was provided on stackoverflow ([https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393](https://stackoverflow.com/questions/47518911/boostrap-4-navbar-collapse-menu-right-align/50881393))
- My navbar had a small amount of whitespace on the right-hand side.
  - The solution to remove this was again found on stackoverflow: ([https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687](https://stackoverflow.com/questions/48510609/remove-white-space-from-the-sides-and-top-of-my-navbar/48510687))
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

- I&#39;d like to thank my mentor Sinead O&#39;Brian for her advice in the run up, and during this project.

- Further inspiration came from the UCD-Resume project in the CI User Centric Frontend module. I particularly identified with the thirds concept for separating the content.

- I&#39;d like to acknowledge the guidance we received in an MS-1 planning call with :-

- Jim Morel

- John Traas

- Anthony O&#39;Brien

…the information they presented was invaluable.
