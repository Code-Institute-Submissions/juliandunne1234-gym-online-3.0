<h1 align="center">Gym Online 3.0</h1>
A website to subscribe to an online gym. Created as part of the Code Institue Portfolio 1: HTML and CSS Essentials Milestone Project.

***
![Responsive images of website](assets/images/responsive-images/intro-webpage-responsive.jpg)
***

## Introduction
Nowadays people have access to so much information that filtering this information can be quite time consuming. Online media platforms are great but sometimes you have to watch the entire video to decide if the content is actually what you want.<br>

Finding 1-2 hours a day to go to a gym is not possible or even appealing to everyone. Anyone that has an interest in physical activity, whether that is 10-30 minutes or longer should have immediate access to a workout plan that will suit their requirements. <br>

This gym concept is suitable for everyone. From the beginner doing their first pushup to the more advanced user. It can be done at home or in the park, all you need is the ground beneath your feet. The use of actual equipment is optional as there is always a substitute readily available.
***

## Table of Contents
* [Features](#Features)
* [Testing](#Testing)
* [Validator Testing](#validator-testing)
* [Technologies](#Technologies)
* [Deployment](#Deployment)
* [Issues List](#Issues-List)
* [Credits](#Credits)
***

## Features

### Header & Navigation
* In the header the "Gym Online 3.0" anchor tag is featured at the top of the page and can be selected from any page to return to the home page.
* There is also a navigation menu in the header of each website page. It includes Home, Select a Plan and a Sign Up options. An active underline is used to display the current page.
![Navigation menu header screenshot](assets/images/responsive-images/header-nav-menu.jpg)
***

### Footer & Contact Details
* Social media accounts have not been created. The social media icons displayed in the footer are for aesthetic reasons and include links to website homepages only.
* Contact details for the online gym including email and phone number have also been included for aesthetic purposes only.
![Navigation menu header screenshot](assets/images/responsive-images/footer-contact-detail.jpg)
***

### Homepage
![Navigation menu header screenshot](assets/images/responsive-images/homepage-responsive.jpg)

* Fictional reviews for the online gym are displayed on top of a hero image. The primary reason for the hero image is to show the color profile used throughout the website. On smaller screen sizes only one review is displayed and the other is hidden.
![Navigation menu header screenshot](assets/images/responsive-images/homepage-intro-review.jpg)

* The online gym offers three different training plans. The homepage subscriber plan section provides high level overview of what each plan includes. Gradient background colors consistent with website are visible and on smaller screen sizes each plan is changed to stacking format instead of side by side.
![Navigation menu header screenshot](assets/images/responsive-images/homepage-plan-option.jpg)

* Anchor elements styled as buttons are used for navigation purposes to get to the Select a Plan and Sign Up pages. A hover color effect has been implemented. On smaller screen sizes the anchor styled buttons are changed to a stacking format instead of side by side.
![Navigation menu header screenshot](assets/images/responsive-images/nav-anchor-style-button.jpg)
***

### Select a Plan
![Navigation menu header screenshot](assets/images/responsive-images/select-a-plan-responsive.jpg)

* Similiar to the homepage the select-a-plan page contains three training plans. The subscriber plan detail section provides lower level information on what each training plan entails. The same layout as the homepage is used with gradient background colors.
 ![Navigation menu header screenshot](assets/images/responsive-images/select-a-plan-detailed-option.jpg)

* On smaller screen sizes each plan is changed to stacking format instead of side by side.
 ![Navigation menu header screenshot](assets/images/responsive-images/select-a-plan-detailed-option-small.jpg)

* Additional subscriber reviews section including images of fictional subscribers working out at home and a video showing a person walking through an old gym door is for motivational purposes. Layout changes as screen sizes reduce where the video is hidden and the subscriber reviews and images change.
![Navigation menu header screenshot](assets/images/responsive-images/select-a-plan-subscriber-review.jpg)

* Anchor elements styled as a button used for navigation purpose to get to the Sign Up page. A hover color effect has been implemented.
![Navigation menu header screenshot](assets/images/responsive-images/select-a-plan-nav-style-button.jpg)
***

### Sign Up
![Navigation menu header screenshot](assets/images/responsive-images/signup-responsive.jpg)

* The Sign Up page includes a subscription form that interested subscribers to the online gym can complete. Each input box is required to be complete before the Subscribe Now button to submit the data can be select without generating a fill in empty fields warning.
* The background image includes an athletic looking person. At larger image sizes an additional background coloring has been added to extend the background image. This is to reduce automatic image resizing.
![Navigation menu header screenshot](assets/images/responsive-images/signup-full-screen.jpg)

* On smaller screen sizes only a background color is used with the subription form displayed.
![Navigation menu header screenshot](assets/images/responsive-images/signup-small-screen.jpg)
***

## Testing
* Testing was done to confirm each page in this website works as expected using Google Chrome and Edge browsers. 
* Devtools device toolbar was used to confirm website is responsive and remains asthetically pleasing for the different standard screen sizes.
* Navigation menu items, anchor tags and form inputs have all been tested to confirm everything functions as required.   
***

## Validator Testing
* HTML - no errors found when passing index.html, select-a-plan.html and signup.html content through the [W3C validator](https://validator.w3.org/nu/#textarea)

* CSS - no errors found when passing style.css content through the [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator)

* Accessibility - Website accessibility is a key part of the project criteria. Devtools Lighthouse was used to confirm the colors and fonts used in each page are easy to read and accessible.

    * Homepage
    ![Navigation menu header screenshot](assets/images/responsive-images/homepage-lighthouse-result.jpg)

    * Select a Plan
    ![Navigation menu header screenshot](assets/images/responsive-images/select-a-plan-lighthouse-result.jpg)

    * Sign Up
    ![Navigation menu header screenshot](assets/images/responsive-images/signup-lighthouse-result.jpg)
***

## Technologies Used
### Languages
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS](https://en.wikipedia.org/wiki/CSS)

### Libraries
* [Google Fonts](https://fonts.google.com/) - Import 'Open Sans' and 'Roboto'
* [Font Awesome](https://fontawesome.com/) - version 5.15.4

### Framework
* [GitHub](https://github.com/juliandunne1234/gym-online-3.0.git) - Gym Online 3.0 project repository
* [Gitpod](https://www.gitpod.io/) - open source developer platform used to create the website for the project
***

## Deployment
* The site was deployed to GitHub pages using the following steps: 
    * Open the GitHub repository and select Settings tab
    * Select Master Branch from the source section drop down menu
    * Live link - [Gym Online 3.0](https://juliandunne1234.github.io/gym-online-3.0/)
***

## Issues List
* Open Issues:
    * Setting relative and absolute positioning on each web page so that the full screen size is used by the page. Instead there is whitespace remaining at the bottom of the pages.
<br><br>
* Resolved Issues:
    * Using images so that the required content is displayed for each screen size.
    * Maintaining detailed gym plans so that content within each plan remains clear to the reader for each screen size. 

***

## Credits
### Content

* The Love Running walkthrough project with Code Institute was very helpful to use as a starting point for this project. In particular when trying to create the navigation menu layout and for using the social media icons
* Additionally the Love Running project was helpful as a point of reference when creating the subscriber form with text input requirements and form validation
* README file structure adapted from Code Institute sample project [README.md](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSSE_PAGPPF+2021_Q2/courseware/66cf361c769a41d496f5001fae6f9be7/3b5cd5dc8313462aa5975a3c9b9a1a3c/)
* Tutor support was also very helpful and advice taken from mentor sessions was used during development of the website 

### Media
* All images and the video used in this project were found on the [pexels](https://www.pexels.com/) website
* Fonts used were imported from [Google Fonts](https://fonts.google.com/)
* Gym dumbell icon used throughout the website is taken from [Font Awesome](https://fontawesome.com/)
***