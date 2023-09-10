# Mohammed's website for Project Testrepo


![amiresponsive](docs/amiresponsive.PNG)

[View the deployed website here](https://mohammedma2023.github.io/testrepo/)


## User Experience (UX)

### Initial Discussion

 The goal of the project N is to create a website for a local employer. Nicola would like a website to provide information on her services . The goal of this website is to give  our users a clear understanding of what  service are available and what she can do to help clients. My goal for this project was to make a responsive, professional and accessible website for a chosen club.
I chose to make my site about a games club held in Shipley College.
The site was then going to be hosted somewhere (github pages for now) and possibly given some backend code.
This would help develop my skills in development.


 #### Key information for the site:

 * Project Testrepo is a clas assignment for my Year 2 PDD class.
 * This project will be worked on by me, Mohammed.

.

### User Stories

TBC

### User Goals

#### Project Goals:

* The ability to view the website to get information on services provided.
* To make the site understandable for first-time users and to make the purpose clear.
* To provide clear and easy-to-notice contact information, including address.
* To make the content easy to read and accessible to all visitors.

#### First-Time Visitor Goals:

* To find out what Project N is.
* To be able to easily navigate through the website on various devices.
* To visit our social media pages.

#### Returning Visitor Goals:

* Fill out the contact form and get in touch with us regarding doing business together.
* To start collaboration and answer any questions potential clients may have.

#### Frequent Visitor Goals:

* Our frequent visitors should be our business partners.

- - -

## Design

### Colour Scheme

 The website mainly follows Google's Material design philosophy.


### Typography 

The font used is the one supplied with the BootStrap theme used.

### imagery

All images were taken from the Google website and reference was provided where applicable.

### Wireframes

Wireframes were created for desktop view. 

### Features

This website has a few features:
* Viewing the games club location. The user can view the location of the games club (which is located in the Shipley College Exhibition Building). This works by bringing up a pop up after the button within the "Address" container is pressed. This will display a popup which contains an iframe. This iframe contains the location of the Exhibition Building. The user can then press "CLOSE" button.

* The user has access to social media links. These links will redirect the user to the respective social media pages (YouTube, Instagram and Twitter).
* Allowing the user to enter an email. The user can enter their email to sign up for a newsletter. There is no backend code to send emails to the user's entered email address. However, this can be implemented later.
* Information. Perhaps this is not a feature, but the website does give information about the Games Club to all users. It does this in a clear and concise way by separating it into different sections which discuss different topics.

### Accessibility 

It was ensured that the website is accessible and as user-friendly as possible. This has been achieved by: 

* Using semantic HTML.
* Using descriptive alt attributes on images on the site.
* Ensured that there is a sufficient colour contrast throughout the site. 
* Ensured that all the links have descriptive names. 

- - -

## Technology

### Languages Used

 HTML, CSS and JavaScript were used for this site.

### Frameworks, Libraries & Programs Used

* Balsamiq - Wireframes.

* GitHub Desktop - Version control.

* GitHub - To save and store the files for the website.

* Bootstrap v5.2 - a framework used for the website. Used when creating rows and columns. Most text containers and divs on the page use Bootstrap. This entails styling of text colour, font and positioning. Also, the form element was almost entirely created using this framework, with the support of standard CSS3 code to override certain styles.

* Font Awesome - For the iconography on the website.

* Google Dev Tools - Troubleshooting, testing features and solving issues with responsiveness and styling.

* [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.
* [Favicon.io](https://favicon.io/) To create favicon.

- - -

## Testing

Testing progressed at every stage of this project. This ensured that most issues were fixed before the website was finished. Chrome DevTools were utilised when building the website to help with troubleshooting as the website transformed. 

The following issues were raised during my project meeting with the client:
* issue 1
* issue 2


### W3C Validator

The W3C validator was used to validate the HTML and CSS pages.

* [HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fshipleysteve.github.io%2F)
* [CSS Validation](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fshipleysteve.github.io%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)



### Fixed Bugs

I have fixed all known bugs for this site.

There was an issue loading my scripts.js file. This was because I used the wrong path for the file. This file is used to change the look of the navigation bar based on where the user is on the page. The bug was causing this functionality to be removed. This issue no longer exists.

Another issue was that the website was trying to retrieve a bootstrap resource using an incorrect link. This was causing more errors to appear in the console. I removed this from the HTML file, which did not change how the page looks. However, it stopped these errors.


### Test Cases

I have fully tested the website using Google Chrome and Mozilla Firefox on desktop (Comoputer details go here) and mobile (mobile device details here). 

It was ensured that through the testing process content was responsive using the Google Developer Tools. 

#### Home page

* I began by clicking on the "home" link and the logo to see if the homepage loads correctly.
* Next, I scrolled down to see if all of the images and all content loaded correctly.
* I ensured that from the Home page - all navbar links lead to the right page.
* Lastly, I checked if the social links in the footer element work correctly as well.
* Form
  * I clicked on the "Submit" button - Error message appeared "Please fill in this field" - As expected.
  * Next, I filled in the required field (email) - The same error message should appear indicating that the "Your name" field must be completed before submitting the form.
  * The same process was repeated for the Your Email, Subject and Message fields.
  * When all fields are completed, the "Submit" button should display a "thank you" message without any errors on the form.

### Supported Screens and Browsers

* Browsers - It is recommended that you use the latest version of one of the following:

  * [Apple Safari](https://www.apple.com/safari/)
  * [Google Chrome](https://www.google.com/chrome/)
  * [Microsoft Edge](https://www.microsoft.com/en-us/edge?form=MA13FJ)
  * [Mozilla Firefox](https://www.mozilla.org/pl/firefox/)

* Screens

  * This website is suitable for mobile devices including Samsung and iPhone (Devices of the same width are also suitable).
  * Tablets.
  * Desktops.

- - -

## Deployment & Local Development

### Deployment

GitHub Pages was used to deploy the live website. Instructions:

1. Log in (or sign up) to Github.
2. Find the repository for this project, "ShipleySteve.github.io".
3. Click on the Settings link.
4. Click on the Pages link in the left-hand side navigation bar.
5. In the Source section, choose main from the drop-down select branch menu. Select Root from the drop-down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

Fork the Project N repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, ShipleySteve.github.io.
3. Click the Fork button in the top right corner.

#### How to Clone

Clone the ShipleySteve.github.io repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, ShipleySteve.github.io.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Credits

### Background Images

* email.jpg (). This image was used in the background of the newsletter sign up form.

* location.jpeg (https://1drv.ms/i/s!AkpC1RL9orDRyQ-J9XqxIu1vZUg8?e=zcjA1Z). This image was used as the background image of the top part of the website, the header. 
* 

- - -

## Acknowledgements


TBC