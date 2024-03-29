<h1 align="center">MerryWash Website</h1>

[View the live project here.](https://baijuka.github.io/MS1-Project/)


This website was developed to create an online presence for MerryWash, an imaginary car valeting business, and thus improve its client base and business. 
MerryWash is a leading car valet business located in Newport South Wales, UK.
This business provides a number of different services to the public based on their requirements and demands.

## UX

### Project Goals

The primary objective of MerryWash is to provide its users a user-friendly, intuitive website capable of providing all required information about the business 
and its services without any hassle. MerryWash focuses on two category of clients as their users and they are:
1.	Car drivers
2.	Mini vehicle (van) drivers

### User objectives as a car driver

- Looking for services available
- Looking for details of each service and its cost
- Looking for other user reviews and feedback
- Looking for opening times
- Looking for how long each service takes to complete the job
- Looking for how they can pay for the job done
- Looking for how can they contact the MerryWash for more information

### User stories

As a taxi driver I need to wash my car regularly and for which:
- I use the help of internet to find a car washing service of my choice
- I need to find out detailed information about services available
- I need to know about how much they charge for their services
- I want to know if the business is open for my choice of time
- I want to find out the information easily
- I want to go to each page with a single click of buttons or links
- I want to know how I can contact the service provider whenever required
- I want to know what other users have said about this particular service provider from their experience


MerryWash has incorporated all these user goals in its website and it:

- has made a custom website to its users according to their need
- has implemented a user centric front-end development approach using five planes
- has made its website is easy to use
- is structured by adding interaction features
- has categorised its content so that users can easily access it depending on their need
- has provided all required information about services and business
- is intuitive, learnable and easy to navigate
- has arranged its patterns, navigation and order of menu items in a way that any one can identify it easily
- is, above all, responsive to various devices such as mobile, tablets and larger screens

### Developer and Business Goals

- Design and develop a well-illustrated website that can be attracted by any user at first sight
- Provide a professional touch in every feature, content and layout
- Implement everything required to make the website easy to use and make users stress free and happy


## Design Choices

This website was designed using user centric approach and for that special attention was given in choosing various elements

### Fonts

-	Primary font: Robot – simple and allowing letters to be settled into their natural width
-	Secondary font: Arimo – Arimo offers improved on-screen readability characteristics and the pan-European WGL character 
    set and solves the needs of developers looking for width-compatible fonts to address document portability across platforms

### Icons 
-	All icons used are relevant to the subject to make navigation easy

### Colors

The two main colours used are yellow and white.  Dark background has been applied to navigation bar and footer.

### Styling

-	Tried to keep consistency in design in order to maintain a feeling of relationship between items  
-	Boxes, images, containers and cards were given round corners to look smooth
-	Both header and footer were given matching color pattern to make it more appealing
-	All icons used were given same color to maintain the consistency

### Background

-	Background: Images of various car valeting procedures were embedded in every page to resemble the nature of the business

## Wireframes

Wireframes were created using Balsamiq Desktop App.
-   Home Page Wireframe -<a href="./assets/wireframes/home.pdf" target="_blank" >Home</a>
-   Services Page - <a href="./assets/wireframes/services.pdf" target="_blank" >Services</a>
-   Testimonials Page - <a href="./assets/wireframes/testimonials.pdf" target="_blank" >Testimonials</a>
-   Contat Page - <a href="./assets/wireframes/contact.pdf" target="_blank" >Contact</a>

### Mock-ups for Mobile and Tabs
-   Home Page - <a href="./assets/wireframes/mockup.pdf" target="_blank" >Home</a>

## Features

### Existing Features

-   Responsive on all device sizes
-   Interactive elements
-	Home page:– Logo, navbar, header and footer
-	Services Page:- Embedded with various services provided, price and time taken to complete the job 
-   Review Page:- User feedback received added in this section
-	Contact Page:- This section features with Name text filed, Email field and comment box text area 
    by which users can communicate with the business. Also has given the contact telephone number and address of the business in the header and footer section.

### Features Left to Implement

-   Online service booking form will be added in the next version

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1.	[Bootstrap Framework](https://getbootstrap.com/)
    -   Bootstrap was used to assist with the responsiveness and styling of the website
1.   [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import 'Roboto' and 'Arimo' fonts into the style.css file which is used on all pages throughout the project
1.   [Font Awesome:](https://fontawesome.com/)
        - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes
1.  [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the wireframes during the design process
1. [Gitpod:](https://www.gitpod.io/)
    - Gitpod was used as a text editor to create and edit files
1. Google Chrome
    - Google Chrome was used to browse the pages

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
-   [W3C Markup Validator](https://validator.w3.org/) - [Results](https://github.com/)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/)
-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone6, Samsung Galaxy A70
-   A large amount of testing was done to ensure that all pages were linking correctly
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues

### Known Bugs

-   Issue -The display of the web pages were different on deployment site
    Fixed - Added a dot in front of the relative path in the link tag: <link rel="stylesheet" href="./assets/css/style.css">
-   Issue - Navbar item color was not changing while mouse however over it
    Fixed - Changed the code in style.css as : 
        li.nav-item a:hover {
        color:orange !important;
        }
-   Issue - Lead images on all pages were stretching beyond the screens
    Fixed - Wrapped the content in div block with a container class

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone', and then paste the URL you copied in Step 3.

    $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


7. Press Enter. Your local clone will be created.

	$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

> Cloning into 'CI-Clone'
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.


Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.


## Credits

### Content

-	The text for service section was created using contents from the following sites:
-	Testimonials - https://www.arnottsvaleting.co.uk/testimonials/
-	Other descriptions - https://www.mobilecarvaleting.co.uk/

### Media

The photos used in site were obtained from
-	[Spray Nozzles](https://www.spray.com)
-	[Goldstar Multi](https://goldstarmulti.co.uk)
-	[Autoguide](https://www.autoguide.com)
-   [Adobe Stock](https://stock.adobe.com/si/search?k=carwash+background)
-   [Psychology Today](https://cdn.psychologytoday.com)
-   [The Conversation](https://images.theconversation.com)
-   [Istock Photo](https://media.istockphoto.com)

### Acknowledgement

-	Mr. Antonio Rodriguez(Mentor) for support and advice.

