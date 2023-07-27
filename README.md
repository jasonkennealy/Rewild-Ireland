This is the README for my Rewild reland Repository.

The main goal of this website is to educate children and adults on

![Rewild Ireland displayed on various devices](documentation/responsive.png)

[Live Rewild Ireland site](<https://github.com/jasonkennealy/Rewild-Ireland>))

## CONTENTS

- [CONTENTS](#contents)
- [Design](#design)
  - [Color Scheme](#color-scheme)
  - [Typography](#typography)
  - [Imagery](#imagery)
  - [Features](#features)
    - [Existing Features](#existing-features)
    - [Home page](#home-page)
  - [Features Left to Implement](#features-left-to-implement)
  - [Accessibility](#accessibility)
- [Technologies Used](#technologies-used)
  - [Languages Used](#languages-used)
  - [Frameworks, Libraries \& Programs Used](#frameworks-libraries--programs-used)
- [Deployment](#deployment)
- [Testing and Solved Bugs](#testing-and-solved-bugs)
  - [Validator Testing](#validator-testing)
  - [Lighthouse](#lighthouse)
    - [Home page](#home-page-1)
    - [About Checkup Dublin Center page](#about-checkup-dublin-center-page)
    - [Services page](#services-page)
    - [Contact us page](#contact-us-page)
    - [Thank you page](#thank-you-page)
  - [Full Testing](#full-testing)
- [Credits](#credits)
  - [Code Used](#code-used)
  - [Content](#content)
  - [Media](#media)
  - [Acknowledgments](#acknowledgments)

- - -

## Design

### Color Scheme

The colors I chose were essential to the website. I chose something professional and sleek looking which is easy to read and does not distract.

The subtle gray is calming and makes any text on it stand out.


### Typography

I used Google Fonts for this website. 

Oxygen for titles and Quicksand for the main text sections.

### Imagery

The website uses a small amount of imagary which I feel drives home the message of the main hero image. It stands out as soon as you arrive at the homepage and it is clear in its message. The 'Our courses' section, uses vibrant and concise imagary which coverys what to expect from each course.

### Features 

The website is made up of 3 pages. A navigation menu which can bring the users to anywhere in the site. The first feature on the main page is the hero image which is overlaid with the words of the sites ethos 'Educate, Rewild, Reconnect which leads into the section below which elaborates on each of these sections.

Below this we find the 'Our Courses' section which displays a grid of courses which can be selected. This will bring you to a form where you can enter your details to find out more about the courses and enrol.

There is also a second form that allows users to request that we plant a tree in their name.

Below all this we have a foote where users can find a link to social media accounts.

#### Existing Features

Every page on the website has:

- __Navigation Bar__

  - Found at the top of the page is a fully responsive navigation bar where users can jump to the different sections of the site. When users hover over these selections, they are highlighted with a background color.

![Navigation bar](documentation/screens/navigation-bar.png)

- __Footer__ 

  - The footer has links to social media. I did not use icons as I thought the 'mirror' effect with the header was visually appealing. The links open in new windows to not distract users from the main site.

![Footer](documentation/screens/footer.png)

#### Home page

- __The home page image__

-  On the homepage,users are instantly met with a striking image of a child in the woods. It heavily features a selection of greens and is interesting to look at. It instantly converys the meaning of the site and welcomes the user, it has the keywords of the sites ethos overlaid on top of the image which further drives home the sites meaning.

![Landing page image](documentation/screens/landing-page.png)

- __Our goals section__

  - The our goals section features 3 sections each with one of the keywords of the ethos as a heading and elaborates on them in an easy to read and educational way.

![About us](documentation/screens/about-us.png)

- __Our Courses section__

  -  This is a 4x2 grid where users can browse what courses we have on offer. They each have their own image which conveys what to expect on the course and a text box whihc contains the course title. They also have a clickable link 'Enquire' that brings them to our course form.

![Our Services](documentation/screens/our-services.png)

- __Course form section__

  -  Here the users can enter their detials into our form and we will give them more details about their selected course

![Testimonials](documentation/screens/testimonials.png)

- __Plant a tree form section__

  - Here the users can enter their detials into our form and we will plant a tree of their choice in their name.

![Welcome](documentation/screens/welcome.png)



### Features Left to Implement

- 
- Add submit page for forms rather than the Code Institute submit page taken from Love Running

### Accessibility

I have been attentive to make the website as accessible-friendly as possible through the following measures:

* Utilizing semantic HTML to provide meaningful structure and enhance accessibility.
* Incorporating descriptive alt attributes for images on the site to provide alternative text for screen readers.
* Ensuring an adequate color contrast across the site to improve readability for users with visual impairments. I employed the contrast checker provided by [WebAIM](https://webaim.org/resources/contrastchecker/) to validate the contrast ratio between the selected foreground color and background color.
* Making menus accessible by indicating the current page as "current" for screen readers, aiding navigation and orientation.

By implementing these considerations, I have strived to enhance the overall accessibility of the website.

- - -

## Technologies Used

### Languages Used

This website was created using HTML and CSS.

### Frameworks, Libraries & Programs Used

Codeanywhere was used to vreate this code. On 20th of July 2023, i ran out of workspace credits which was quickly solved by Rebecca from student support.

Github was used to store files for site

Google Fonts was where i  got the fonts used on the website.

I used Font Awesome For icons

I also used Google Dev Tools to help identify bugs and for debugging.

[Am I Responsive?](http://ami.responsivedesign.is/) To display the website on different devices

- - -

## Deployment

- The site was deployed using github and the live link can be viewed  here - [Rewild IrelandI als](https://github.com/jasonkennealy/Rewild-Ireland)  

- - -

## Testing and Solved 


Tests for bugs was done consistently through making this site to catch and deal with them early

In my mid project meeting with Elaine Roche, the floowing problems were brought up and have been corrected:

responsiveness - maybe consider flexbox for courses at the bottom of the 

get nav  the links working

fix 404 on click on main title

get the hero image to load

footer on homepage - maybe add some blank space under it

distinguish the 2 different forms and add a phrase/blurb to drive home to the user the purpose of each

resize the form input area / fields so that they don't take up the full width of the screen

move down the submit buttons on the forms

add comments to html files

use header tag



### Validator Testing 

- HTML: No errors were returned when passing through the official W3C validator.
  * [Index Page HTML](documentation/testing/w3c/w3c-index.png)
  * [About CheckUp Dublin Center Page HTML](documentation/testing/w3c/w3c-about.png)
  * [Services Page HTML](documentation/testing/w3c/w3c-services.png)
  * [Contact us Page HTML](documentation/testing/w3c/w3c-contact.png)
  * [Thank you Page HTML](documentation/testing/w3c/w3c-thankyou.png)
 
- CSS: No errors were found when passing through the official Jigsaw validator.
   * [style.css](documentation/testing/w3c/w3c-css.png)

### Lighthouse

I utilized Lighthouse, a tool available in the Chrome Developer Tools, to assess the performance, accessibility, best practices, and SEO aspects of the website.

#### Home page
- Desktop: [Home page - desktop](documentation/testing/lighthouse/home-desktop.png)
- Mobile: [Home page - mobile](documentation/testing/lighthouse/home-mobile.png)

#### About Checkup Dublin Center page
- Desktop: [About CheckUp Dublin Center page - desktop](documentation/testing/lighthouse/about-desktop.png)
- Mobile: [About CheckUp Dublin Center page - mobile](documentation/testing/lighthouse/about-mobile.png)

#### Services page
- Desktop: [Services page - desktop](documentation/testing/lighthouse/services-desktop.png)
- Mobile: [Services page - mobile](documentation/testing/lighthouse/services-mobile.png)

#### Contact us page
- Desktop: [Contact us page - desktop](documentation/testing/lighthouse/contact-desktop.png)
- Mobile: [Contact us page - mobile](documentation/testing/lighthouse/contact-mobile.png)

#### Thank you page
- Desktop: [Thank you page - desktop](documentation/testing/lighthouse/thankyou-desktop.png)
- Mobile: [Thank you page - mobile](documentation/testing/lighthouse/thankyou-mobile.png)

### Full Testing

To make sure my website works properly, I tested it on different web browsers like Google Chrome and Microsoft Edge, and also on different devices such as a Dell Inspiron 15-inch laptop and a Samsung A52S smartphone.

Additionally, I inspected each page using Google Chrome Developer Tools to ensure that they appeared correctly and were responsive on various screen sizes.

Links:

- I conducted link testing on the index page, about us page, services page, contact us page, and thank you page. During the testing, it was confirmed that all the links on these pages operated as expected. Additionally, any links that directed to external pages successfully opened in separate browser tabs.

Contact Us Form:

1. The contact us form was tested by submitting it without filling in any input fields. The form correctly prompted the user to fill in the First Name field. After filling in the first name and submitting the form, the form directed the user to fill out the Last Name field. Upon completing the last name and submitting the form, the user was prompted to fill in the Email field. Finally, after filling in the first name, last name and email, the form successfully submitted and opened the thank you page in the same browser window, considering the phone number and message fields as optional.
2. A test was performed by submitting the form with only the email address. The form correctly directed the user to fill in the First Name field. After providing the first name and email, the form prompted the user to fill out the Last Name field. Upon completing the first name, last name, and email, the form successfully submitted and opened the thank you page in the same browser window.
3. Another test was conducted by submitting the form with only the message field filled in. The form correctly directed the user to fill in the First Name field and then the Last Name field. After providing the first name, last name, and message, the form prompted the user to fill in the email field. Finally, after filling in the first name, last name, email, and message, the form successfully submitted and opened the thank you page in the same browser window.

- - -

## Credits 

### Code Used

- [Structural inspiration taken from LoveRunning source code from Code Institute](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode)
- [README.md template from Code Institute](https://github.com/Code-Institute-Solutions/readme-template)
- [README template from Izabella Lopes](<https://github.com/IzabellaLopes/checkup-dublin/blob/main/README.md?plain=1>)

### Content 

- Content for the website was written by Jason Kennealy.
- Some additional content for the paragraphs and text sections were written by [ChatGPT](https://chat.openai.com/), an AI language model developed by OpenAI.

### Media

 Home page:
 
- Background
    - [hero-image](https://www.istockphoto.com/photo/close-up-of-a-stethoscope-and-digital-tablet-with-virtual-electronic-medical-record-gm1369987284-439639988?phrase=medicine+background) - Credit to everything possible, iStock.
 
- Our services
    - [complete checkup](https://www.istockphoto.com/photo/doctor-writing-a-medical-prescription-gm1319031310-405998329?phrase=physical+examination) - Credit to demaerre, iStock. 
    - [clinical investigations](https://www.istockphoto.com/photo/professional-doctor-preparing-patient-for-procedure-gm627290560-111071371?phrase=Clinical+investigations) - Credit to YakobchukOlena, iStock
    - [exams](https://www.istockphoto.com/photo/detail-of-computer-ultrasound-with-x-ray-in-modern-medicine-gm941578476-257350996?phrase=ultrasound+device) - Credit to Vladimir_Timofeev, iStock.
 
- Testimonials
    - [testimonial-1](https://lexica.art/prompt/a2c059db-d517-4f22-ae91-cbaa919a63ee) - Credit to Lexica.
    - [testimonial-2](https://lexica.art/prompt/9edb0923-b474-4c74-b11b-28d9f889714d) - Credit to Lexica.
    - [testimonial-3](https://lexica.art/prompt/cc910fc1-bde8-4df2-98e8-587ccd41bb56) - Credit to Lexica.
    - [testimonial-4](https://lexica.art/prompt/0175a75b-41b8-4024-89af-492bde6523bf) - Credit to Lexica. 

About CheckUp Dublin Center page:

- Welcome
    - [welcome](https://www.istockphoto.com/photo/reception-and-armchairs-in-hospital-hall-gm1223999858-359731228?phrase=clinic%2Breception%2Bdesk) - Credit to ismagilov, iStock.

- Our Team
    - [our-team-1](https://lexica.art/prompt/7c2c4250-0675-4b96-b507-47a96905968e) - Credit to Lexica.
    - [our-team-2](https://lexica.art/prompt/7bd0447d-9020-4137-94a9-9489eb117e96) - Credit to Lexica.
    - [our-team-3](https://lexica.art/prompt/ed4d8873-e9a7-49e0-a411-1fd7d976040d) - Credit to Lexica.
    - [our-team-4](https://lexica.art/prompt/c01b134c-472b-4425-a353-d8da33843866) - Credit to Lexica.

Services page:

- Gallery
    - [gallery-1](https://lexica.art/prompt/0decd297-34db-4af5-99e9-441292db1824) - Credit to Lexica.
    - [gallery-2](https://www.istockphoto.com/photo/nurse-and-doctor-team-meeting-collaboration-gm1272197465-374537275) - Credit to AndreyPopov, iStock.
    - [gallery-3](https://unsplash.com/pt-br/fotografias/Y-3Dt0us7e0) - Credit to Patty Brito, Unsplash.
    - [gallery-4](https://www.istockphoto.com/photo/elderly-patient-with-bp-heart-rate-digital-pulse-check-equipment-for-medical-gm1177942982-329043762) - Credit to Chinnapong, iStock.
    - [gallery-5](https://www.istockphoto.com/photo/making-ultrasound-check-up-gm895702826-247446807) - Credit to shironosov, iStock.
    - [gallery-6](https://www.istockphoto.com/photo/bone-density-hip-and-lumbarspine-result-osteoporosis-gm1165489459-320715536) - Credit to Tonpor Kasa, iStock.
    - [gallery-7](https://www.istockphoto.com/photo/young-caucasian-man-standing-against-wall-while-doctor-using-x-ray-machine-scan-him-gm1266813630-371478609?phrase=chest+xray) - Credit to Inside Creative House, iStock.
    - [gallery-8](https://unsplash.com/pt-br/fotografias/QsBfOwMoPNY) - Credit to Towfiqu barbhuiya, Unsplash. 


### Acknowledgments

- My family, for their strong support during my transition and development of a new career. Their names are featured in the testimonials and our team section of the CheckUp Dublin Center webpage as a way to honor them and show my appreciation.
- Jubril Akolade, my Code Institute Mentor, for providing valuable advice.
