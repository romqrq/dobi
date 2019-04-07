# Dobi - Automation Solutions

All the sections and functionalities are easily accessible from the navigation bar and most of them won't take more than 3 clicks/taps from the home page to the end of the process. 

## UX

This project is for a fictional company that offers automation services and products for house and business. The main products are the service packages and secondarily automation hardware kits and individual products such as cameras, sensors and more.

As the products offered, the website orbitates the practicality and functionality of things and all features are intended to be easily accessible, intuitive and visible for the user. The design is responsive, changing the layout according to the size of the screen. Some buttons are shown or hidden depending on the screen resolution to make sure the user has the main actions always available on screen.

-Four main User Stories were used to structure the website:
1. I want a quote so I can decide if it's worth it.
2. I want to know where I can use automation and to know more how it works.
3. I need support so I have my problem sorted.
4. I need to find out more about this company. Is it trustworthy?

for these stories we considered both tech savvy and the average internet user that have an interest in automation but aren't sure of what they need.


## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

 
### Existing Features

1. Header - DOBI logo and when the customer clicks on it, it brings the customer to the home page.
2. Navigation Bar - Navigation bar fixed at the top of the screen keeping always visible the menu, the company logo and social media links. Menu collapsed through all screen sizes to keep a clean, minimalistic visual. 
3. Footer - Gives access to a short description of the company mission and quote button.
4. Home - Carousel with images and text that "talk" to the customer telling what the company does and progressing through different situations where the product can be used and closing saying it is available for "home" or "business".
5. Home - Callout buttons giving enphasis to "free quote", secondly to "tell me more" and thirdly "watch a demo".
6. Home - Cards with main points of the product, responsive design that adjustes itself depending on the screen size.
7. Home - Counter with quotes given, projects finished and projects ongoing.
8. Home - Carousel with customer quotes.
9. Services - Image for home automation content. Images with pulse effect to indicate the possibility of interaction.
10. Services - Image for business automation content. Images with pulse effect to indicate the possibility of interaction.
11. Services - Cards with product advantages. The order of the cards is responsive to screen size changing shape and position of the cards.
12. Services - Home automation section showing positive aspects of home automation.
13. Services - Home automation section showing positive aspects of business automation.
14. Services - How it works section featuring a video showing an example of how home automation can be used.
15. Services - Range - Shows known brands of products the company works on its daily basis.
11 - Support - Form where the customer can fill with their question.
12 - Sign in/Sign up buttons - Allow new and existent users to either sign in or new users to sign up for the service.


### Features Left to Implement
- Animated counter (counting from 0)
- Live chat
- Shopping cart
- Interactive animation where buttons can turn on and off appliances on the screen.


## Technologies Used

- [Mockflow](https://mockflow.com/) - Used to create initial wireframe for the structure.
- [HTML 5](https://en.wikipedia.org/wiki/HTML5) - HTML 5 is the latest version of the Hypertext Markup Language and it is  the standard programming language across the internet for structure and content.
- [CSS 3](https://getbootstrap.com/docs/3.3/) - CSS 3 makes possible to implement responsiveness and style to the HTML document.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Allowed the creation of animations and effects for menus and other features.
- [JQuery 3](https://jquery.com/) - Allowed the creation of animations such as the collapsed button.
- [Font Awesome](https://origin.fontawesome.com/) - It allows the introduction of icons that behave as normal text and are hardwired to users mind across the internet making it more recognizable and requiring minimal effort in understanding.
- [Hover Library](http://ianlunn.github.io/Hover/) - Allows the utilization of pre-made hover effects, accelerating the development and styling process.
- [Google Fonts](https://fonts.google.com/) - Offers a wide variety of font styles.
- [HTML Validator](https://validator.w3.org) - HTML Validator that shows changes necessary for the HTML code to match required standards.


## Testing

During development process, the main tool for tests was the Developer Tools from Google Chrome. 
The website was deployed on GitHub and tested on different screen resolutions and manufacturers (mobile phones).
The link was shared through slack, whatsapp and facebook and we asked the users to fill a form with their feedback from January 28th to February 4th. 

We asked the users doing the test to fulfill the four tasks from our User Stories and their feedback was given through the form. During the period we had 4 answers to the form (not allowing me to reach any concrete conclusion). The small number of responses could be due to restrictions of availability to reinforce the request and the fact that the website and the questionaire are on separate links, asking for an extra effort from the user and maybe reducing the full engagement on the experiment. Despite lack of a solid structure for conclusions, the results of the questionaire follows as an attachment on /assets/survey

The website was also tested through Google Chrome Developer tools - Audits for performance, Progressive web app, best practices, accessibility and SEO, with a simulated fast 3g connection and 4x CPU slowdown.
After the first test, due to technical limitations, we were limited to the improvements we could reach so we adjusted elements to improve mainly loading time and accessibility and then submitted the website to another audit to show the improvements. (Files with the audit results before and after the changes are included on /assets/audits)

Many of the tests were made manually. Using browser "forward and back" arrows for navigating the website, testing the input fields with different formats of data such as email formats and required fields not to be allowed for submition as blank.
We also tested the user stories as test path to ensure they work as desired.

After the tests, we are satisfied with the way the website works on different devices and browsers.

The accessibility features on the code are still a part that we aren't very confident that is implemented correctly but is one of the main priorities on the improvements list as people who have sensorial impairments would be an important part of the potential customer base for the company. 

## Deployment

The project deployment was made using GitHub. 
1. Created the cloud9 environment and files (.html, .css and .jpg)
2. Created the equivalent repository on GitHub. 
3. Pushed the files from cloud9 to the GitHub repository through "bash".
4. On GitHub environment, under the tab "Settings", "github Pages" section, I selected "master branch" and saved.

From this point, all the changes on the pages were made straight from Cloud9 as I pushed the content.

If you wish to run the code locally, it is possible once you have saved the files for the page you wish to run (html, css, images and/or videos).
1. Make sure you have a browser installed on your computer.
2. Find the saved files
3. Right-click (Windows/Linux) or two-finger-click (Mac) on the file and select "Open with" from the action menu.


## Credits


### Content
- The text for About us that talks about Nikola Tesla is a mix of paragraphs from wikipedia (https://en.wikipedia.org/wiki/Nikola_Tesla) and original text to creat a link between Tesla and Dobi.
- 

### Media

The photos used in this site were obtained from:

- Robert Doe - https://pxhere.com/en/photo/1457989
- Doe Family - https://pxhere.com/en/photo/1060077
- Janice Doe - https://pxhere.com/en/photo/1565903
- Nikola Tesla - https://commons.wikimedia.org/wiki/File:Tesla_circa_1890.jpeg
- About us image - https://www.maxpixel.net/Multimedia-Technology-Smartphone-Smart-Home-Home-2769239

The demo video used in this site was obtained from:

- Youtube - https://www.youtube.com/embed/hYMpMt0lwUY

### Acknowledgements

- I got inspiration from  [Apple](www.apple.com), [MEO Smart Home](https://www.meo.pt) and [SB ITAV](https://www.stevenbrennanit.com/smarthome)  and used these websites as visual references and to help me deciding what to include or leave out of my project. I used my experience as user on their website to try to find out which features were attractive and useful for me as a user and potential customer and ultimately bring these conclusions as building blocks for my project.