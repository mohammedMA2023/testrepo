# Mohammed's website for Project Testrepo


![amiresponsive](docs/amiresponsive.PNG)

[View the deployed website here](https://mohammedma2023.github.io/testrepo/)


## User Experience (UX)

### Initial Discussion

 The goal of the project N is to create a website for a local club. This club would like a website to provide information on their activities . The goal of this website is to give  our users a clear understanding of what activities are available and what they can do to take part in them. My goal for this project was to make a responsive, professional and accessible website for a chosen club.
I chose to make my site about a games club held in Shipley College.
The site was then going to be hosted somewhere (github pages for now) and possibly given some backend code.
This would help develop my skills.


 #### Key information for the site:

 * Project Testrepo is a clas assignment for my Year 2 PDD class.
 * This project will be worked on by me, Mohammed.

.

### User Stories

TBC

### User Goals

#### Project Goals:

* The ability to view the website to get information on what the Games Club does.
* To make the site understandable for first-time users and to make the purpose clear.
* To provide clear and easy-to-notice contact information, including address.
* To make the content easy to read and accessible to all visitors.

#### First-Time Visitor Goals:

* To find out what Project Games Club is.
* To be able to easily navigate through the website on various devices.
* To visit our social media pages.

#### Returning Visitor Goals:

* Fill out the contact form and sign up for the newsletter.
* To start answering any questions users may have.

#### Frequent Visitor Goals:

* Our frequent visitors should be those who to check out the latest about the Games Club.

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




### W3C Validator

The W3C validator was used to validate the HTML and CSS pages.

* [HTML Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fshipleysteve.github.io%2F)
* [CSS Validation](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fshipleysteve.github.io%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

These are some issues that were found when I used the W3C Validator:
Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 4, column 5; to line 4, column 28

head>↩    <meta charset="utf-8" />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 5, column 5; to line 5, column 92

8" />↩    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 6, column 5; to line 6, column 249

o" />↩    <meta name="description" content="Welcome to the Games Club at Shipley College! Join us to experienc…ion, and Xbox. Engage in discussions about the best and favorite video games with fellow gamers." />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 7, column 5; to line 7, column 37

." />↩    <meta name="author" content="" />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 9, column 5; to line 9, column 72

itle>↩    <link rel="icon" type="image/x-icon" href="assets/controller.png" />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 12, column 5; to line 12, column 89

ts-->↩    <link href="https://fonts.googleapis.com/css?family=Varela+Round" rel="stylesheet" />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 13, column 5; to line 13, column 146

t" />↩    <link href="https://fonts.googleapis.com/css?family=Nunito:200,200i,300,300i,400,400i,600,600i,700,700i,800,800i,900,900i" rel="stylesheet" />↩    <

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 17, column 5; to line 17, column 58

p)-->↩    <link href="assets/css/styles.css" rel="stylesheet" />↩</hea

Error: Bad value 100% for attribute width on element img: Expected a digit but saw % instead.

From line 64, column 13; to line 64, column 127

          <img width=100% height=auto class="img-fluid" src="assets/img/controller.jpg" alt="Image of an Xbox controller." />↩     

Error: Bad value auto for attribute height on element img: Expected a digit but saw a instead.

From line 64, column 13; to line 64, column 127

          <img width=100% height=auto class="img-fluid" src="assets/img/controller.jpg" alt="Image of an Xbox controller." />↩     

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 64, column 13; to line 64, column 127

          <img width=100% height=auto class="img-fluid" src="assets/img/controller.jpg" alt="Image of an Xbox controller." />↩     

Error: Bad value 100% for attribute width on element img: Expected a digit but saw % instead.

From line 75, column 48; to line 75, column 169

col-lg-7"><img width=100% class="img-fluid mb-3 mb-lg-0" src="assets/img/gamingworld.jpg" alt="Image of different gaming worlds." /></div>

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 75, column 48; to line 75, column 169

col-lg-7"><img width=100% class="img-fluid mb-3 mb-lg-0" src="assets/img/gamingworld.jpg" alt="Image of different gaming worlds." /></div>

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 85, column 39; to line 85, column 198

col-lg-6"><img src="assets/img/gametogether.jpg" alt="Two people sitting together and playing video games using Xbox 360 controllers" style="width: 100%; height: 100%;"/></div>

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 123, column 46; to line 123, column 226

ass="col"><input class="form-control" id="emailAddress" type="email" placeholder="Enter your email address..." aria-label="Enter your email address..." data-sb-validations="required,email" /></div>

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 151, column 29; to line 151, column 55

          <hr class="my-4 mx-auto" />↩     

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 163, column 29; to line 163, column 55

          <hr class="my-4 mx-auto" />↩     

Error: Bad value mailto: enquiries@shipley.ac.uk for attribute href on element a: Illegal character in scheme data: space is not allowed.

From line 164, column 74; to line 164, column 115

ion-none"><a href="mailto: enquiries@shipley.ac.uk">Email 

Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 173, column 29; to line 173, column 55

          <hr class="my-4 mx-auto" />↩     

Error: Bad value 100% for attribute width on element iframe: Expected a digit but saw % instead.

From line 192, column 13; to line 192, column 446

          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2354.3302160237336!2d-1.790938922…to" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></ifra

Error: Bad value auto for attribute height on element iframe: Expected a digit but saw a instead.

From line 192, column 13; to line 192, column 446

          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2354.3302160237336!2d-1.790938922…to" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></ifra

Error: Element script must not have attribute async unless attribute src is also specified or unless attribute type is specified with value module.

From line 204, column 6; to line 204, column 19

 -->↩     <script async>↩     

Warning: Consider using the h1 element as a top-level heading only (all h1 elements are treated as top-level headings by many screen readers and other tools).

From line 90, column 33; to line 90, column 72

          <h1 class="text-white font-weight-bold">Discov

Warning: Consider using the h1 element as a top-level heading only (all h1 elements are treated as top-level headings by many screen readers and other tools).

From line 78, column 25; to line 78, column 64

          <h1 class="text-black font-weight-bold">Level 

Warning: Consider using the h1 element as a top-level heading only (all h1 elements are treated as top-level headings by many screen readers and other tools).

From line 104, column 33; to line 104, column 55

          <h1 class="text-white">Join O

### Fixed Bugs

I have fixed all known bugs for this site.

There was an issue loading my scripts.js file. This was because I used the wrong path for the file. This file is used to change the look of the navigation bar based on where the user is on the page. The bug was causing this functionality to be removed. This issue no longer exists.

Another issue was that the website was trying to retrieve a bootstrap resource using an incorrect link. This was causing more errors to appear in the console. I removed this from the HTML file, which did not change how the page looks. However, it stopped these errors.

I fixed the issue with the illegal character on line 164. There was a space character after "mailto:". I removed the space.  
### Test Cases

I have fully tested the website using Google Chrome, Safari, Microsoft Edge and Firefox on desktop (Comoputer details go here) and mobile (mobile device details here). 

It was ensured that through the testing process content was responsive using the Google Developer Tools. 

#### Home page

Once I was on the home page (https://mohammedma2023.github.io/testrepo/)
* Next, I scrolled down to see if all of the images and all content loaded correctly.
* I ensured that from the Home page - all navbar links lead to the right page.
* Lastly, I checked if the social links in the footer element work correctly as well.
* Form
  * I clicked on the "SUBSCRIBE NOW" button - nothing happened. This is because the button is disabled unless a valid email has been entered.
  * Next, I filled in the email field with a valid field (124403@shipley.ac.uk). This message appeared when I clicked on "SUBSCRIBE NOW" button: "Thank you for subscribing!
Stay updated on the latest gaming news and events.", indicating the form works.
  
  # A valid email needs to contain both a "@" and "." symbols. It also seems that it would work as long as you something between and around those symbols, so the email doesn't truly need to be valid.

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
2. Find the repository for this project, "mohammedma2023.github.io/testrepo/".
3. Click on the Settings link.
4. Click on the Pages link in the left-hand side navigation bar.
5. In the Source section, choose main from the drop-down select branch menu. Select Root from the drop-down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

Fork the Project N repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, mohammedma2023.github.io/testrepo/.
3. Click the Fork button in the top right corner.

\#### How to Clone

Clone the mohammedma2023.github.io/testrepo/ repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, mohammedma2023.github.io/testrepo/.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Credits
* Main Developer: Mohammed Bin Aamir. Keep in mind that I did not develop the Startbootstrap Greyscale template, I just used it.

### Background Images

* email.jpg (). This image was used in the background of the newsletter sign up form.

* location.jpeg (https://1drv.ms/i/s!AkpC1RL9orDRyQ-J9XqxIu1vZUg8?e=zcjA1Z). This image was used as the background image of the top part of the website, the header. 
* 

- - -

## Acknowledgements


People:
*Tutor: Steve Mullarky
Libraries/Frameworks/Tools
* Bootstrap 5
* Fontawsome
* Favicon
* GitHub DeskTop
* Github
* amiresponsive
* W3C validator 
* DevTools
* Template used: Startbootstrap greyscale (https://startbootstrap.com/theme/grayscale)
