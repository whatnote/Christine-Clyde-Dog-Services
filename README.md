# Milestone Project 1

## Christine Clyde Dog Walking

![responsive image](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Multidevicespic.png)

[Link to live project](https://github.com/whatnote/Christine-Clyde-Dog-Services)

[Link to live website](https://whatnote.github.io/Christine-Clyde-Dog-Services/)

## Project Summary

This project is my Milestone 1. I’ve decided to couple it with a new site for my Partner's dog walking business. Due to covid-19, the world has changed; home working has meant the need for dog walking isn't what it once was, but there has been a steep increase in people and families getting dogs; especially puppies.

With this my partner, Chrissy, has taken to opportunity to retrain and up-skill her dog walking business and extend it to include puppy and dog training. Chrissy has started her level three diploma in Canine Behaviour And Animal Welfare.

Once the new normal is established, the new online presence should prove a vital tool in finding new clients.

## Contents

- [User Experience Design](#User-Experience-Design)
  - [User Stories](#User-Stories)
  - [UX](#UX)
    - [Colour Scheme](#Colour-Scheme)
    - [Typography](#Typography)
    - [Wireframes](#Wireframes)
- [Features](#Features)
- [Technologies Used](#Technologies-Used)
- [Testing](#Testing)
  - [User Stories Testing](#User-Story-Testing)
  - [Code Testing](#Code-Testing)
  - [Website Testing](#Website-Testing)
- [Deployment](#Deployment)
- [Credits](#Credits)

# User Stories

# User Experience Design

## Target Audience:

- Letting existing clients, both former and current, know of Chrissy's new skill set.
- People with new puppies who require training.
- People with new dogs/ dogs who require training.
- People with new puppies who require walking.
- People with new dogs/ dogs who require walking.

## User Stories

- Will want to be able to see the services available.
- See opening times.
- See costs for walks and dog training.
- See current client reviews.
- See current qualifications.
- See information about insurance.
- See information about dog walking licence.
- See information about DBS check.
- have a contact us form.
- have a an email option.
- have a mobile number displayed.

## Design

### Colour Scheme

- I opted for a black and white as the main colours. Green was picked as the accent colour, mainly because the pictures of the dogs have a lot of green in them. The Black was not pure black, but a very dark grey, as pure black can be too harsh.

## Typography

- I opted to use Yantramanav font for the Title, nav bar and headings, I augmented the paragraph text with roboto, as it is still very readable at small size, ideal for mobile screens.

## Wireframes

Mobile <br>
![Mobile Wireframe](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/wireframes/Mobile.png)<br>

Destop Page<br>
![Desktop Wireframe](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/wireframes/Desktop.png)<br>

## Differences from the Wireframe.

- Services :
  The services were initially noted as Dog Walks, Doggy Day care and Dog Boarding. But As these services naturally flow from Dog walking the day-care and boarding were dropped, and instead the decision was made to showcase the Training options; Dog Trains and Puppy Training.

# Features

## Existing Features

- Navigation menu is fixed so always remains on top for easy navigation.
- Footer is also fixed meaning the contact is sandwiched between the nav bar and header.
- Three call to actions, the use can call, email or fill out the contact us form from buttons on the hero image.
- About section: contains responsive element, both cert and liability policy disple more info when you hover on them.
- Contact section: has a number and email that will call email when clicked on. Map is an Iframe of location of business.
- Services section: again if you click on the "service" eg Dog Walks, text will scroll up displaying more info about the service.
- Reviews section: Each review is a picture of the dog, when you hover on the picture of the dog, the review text appears.

## Features left to Implement

- Qualifications
- DBS section

both to be added in future updates of the about section.

# Technologies Used

- [HTML](https://www.w3schools.com/html/) - Hyper Text Markup Language, used for creating the website.
- [CSS](https://www.w3schools.com/css/) - Cascading Style Sheet, used for styling the website.
- [Bootstrap](https://getbootstrap.com/) - Bootstrap grid system, navigation bar.
- [Font Awesome](https://fontawesome.com/) - Font awesome Icons are used for the Social media links contained in the Footer section of the website.
- [Google Fonts](https://fonts.google.com/) - Google fonts are used in the project to import the Yantramanav and Open Sans.
- [Balsamiq](https://balsamiq.com/) – Used for creating the wireframes.
- [Git](https://git-scm.com/) - Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.
- [GitHub](https://github.com/) - GitHub is the hosting site used to store the source code.
- [GitPod](https://www.gitpod.io/) - Development environment where the site was built.
- [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools) - Using inspect and also Lighthouse to test the site.
- [W3C HTML validator](https://validator.w3.org/) - Used to test the html code.
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/) - Used to test the CSS code.

# Testing

## User Story Testing

- Will want to be able to see the services available. - **Website has a services tab in the nav bar and section in the site.**

- See opening times. **Opening time is detailed in the contact us section.**

- See costs for walks and dog training.**cost for walks is details the walks card in the services section. Dog training costs are difficult to quantify with the space available.**

- See current client reviews. **Client reviews are appearing when you click on the dog picture.**

- See information about insurance **The about me section contains information about PL insurance.**

- See information about dog walking licence. **The about me section contains information about the dog licence.**

- have a contact us form. **contact form is available on the hero image and also in the contact section.**

- have an email option. **email feature is available in the hero image section and also contact section.**

- have a mobile number displayed. **mobile number is available in the hero section and also the contact section.**

## Code Testing

### HTML Testing

I began testing my html, using [W3C HTML validator](https://validator.w3.org/), the initial test noted 26 errors.

![HTML Testing 26 error](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/htmltest26error.jpg)<br>

The most numerous error was \ being used instead or // for the img src links, this is note worthy as I was pulling the relative file path via the right click from GitHub IDE. So worth noting this is not the necessary the best way to do this.

Another error were styling items on the google iframe element, I moved these to the CSS file and that fixed those errors.

The last two errors were:

![The last two errors](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/htmllasttwoerrors.jpg)<br>

The last two errors to resolve was having and a tag and a child of the button class, I struggled to find a solution wanting to have a button to ring a number or send an email, and when I experimented with the a element in the button element, and it worked I was very pleased, but just because it works doesn't mean it’s a good idea.

The Fix was very easy, when I worked it out, simply keep the styling from the button add the class to the a element, delete the button element. No Errors show.

![The last two errors](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/htmlnoerrors.jpg)<br>

### CSS Testing

The next batch of tests was on the CSS, using [W3C CSS validator](https://jigsaw.w3.org/css-validator/)

Usefully no errors were found.

![CSS Test No errors](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/cssvalidatormperrors.jpg)<br>

### Google Lighthouse

The next test I ran on the deployed site, once loaded in google chrome I looked to lighthouse to run its battery of tests. initial testing was a flop, fortunately I was advised to rerun the tests in incognito mode, so now chrome extensions slow the testing down. This improved things greatly, but still not all was in the top 90.

![Lighthouse not incognito](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/lighthousetest1.jpg)<br>

![Lighthouse in incognito](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/lighthousetest2.jpg)<br>

This noted best practice was low. I'd noted There was an error on the console.log, the small snippet of JavaScript I'd loaded wasn't working like it should, I believed it was necessary for the modal to animate when loading, I decided to comment out the JS code and run the test again, this produced a much better result and the modal still animated in its loading.

![Lighthouse in incognito](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/lighthousetest3.jpg)

This is still not a as good as it could be, and if I get the time I'd look to make the photos of the dogs smaller to further improve the test scores.

### Website Testing

#### Nav Bar Links

The site is just one page, there are no links to other pages in the navigation bar, but the navbar will move the user to the labelled sections. The below is confirmation those links work as they should do.

![Navbar Links](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/navbarlink.jpg)

#### Footer Links

The footer links do take you away from the site, they also work as they should.
![Footer Links](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/footerlink.jpg)

#### Text scroll Animations

The scroll text animations need to work to ensure the extra information will appear the below confirm they do. 
![Text Scroll Animations](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/textscrolls.jpg)

### Mobile First and Media Queries

The website was designed from a mobile first perspective, I've tried to keep media queries to a minimum, but these were necessary to change the size of the paragraph's text.

Without any media queries the following problems resulted when viewed on bigger screens.

![Screen size Testing](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/screensizetests.jpg)

Typical issue was the heading not being in view.
![Screen Pic chevron not working](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/screenshoots6.jpg)

Another issue was the text being too big for the dev.
![Screen Pic text wrong size](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/screenshotp30.jpg)

Once the media queries were deployed the issues noted above were resolved.

### Browsers Tested

The following browsers were tested and all the features deployed worked.

- Chrome

- Safari

- Microsoft Edge

- Mozilla Fire Fox

- Samsung's own browser

- Duck Duck Go

# Deployment

## Git and GitHub

To begin the project a repository was set up in GitHub.

**git init** was the initial command used in the terminal to initialise the git repository.

**git add .** was then used to add the latest small change in the code to the staging area.

**git commit -m'message'** was then used immediately after "git add ." to note the change in the staging area.

**git push** was the final command used to load the local commit to the main repository.

## Deployment via GitHub

[Link to live website](https://whatnote.github.io/Chrissy-Clyde-Dog-Services/)

Navigate to the GitHub [Repository](https://github.com/whatnote/MileStoneOneDogServices)

Go to settings

Scroll down to Git Hub Pages section

Select 'Master Branch' as the source.

Click Save

Click on the link to go to the live deployed page.

## To run Locally

Navigate to the GitHub [Repository](https://github.com/whatnote/MileStoneOneDogServices)

Click the Code drop down menu.

Click the clipboard icon to copy the URL provided

Open your preferred development editor the open a terminal window in a directory you like.

Use "git clone" and paste the copied URL after it.

A clone of the project will be created locally on your machine.


# Credits

## Code

- [Bootstrap Nav Bar with Links](https://getbootstrap.com/docs/4.5/components/navbar/).

- Bootstrap Grid System [Grid system](https://getbootstrap.com/docs/4.0/layout/grid/)

- The slid effect used in both About and Services sections was adapted from this card slide effect. [Card Slide](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_slidebottom)

## Content

- The copy is written by me, and at this stage is more as placeholder text than the finished article.

## Media

- the clipart for the services were purchased from [gograph.com](https://www.gograph.com/)

- Most of the pictures of the dogs are my own apart from Remy the dog, that was taken by [icephotography](https://www.icephotography.co.uk/)

- •	Documents used are either the genuine article or dummy versions. If the original contains too much information, e.g. the Public Liability policy doesn't provide a PL certificate in the same way an Employer's Liability policy does. The PL schedule details everything, including the premium paid and staff discount obtained. So I made the decision to provide a dummy certificate.

## Acknowledgements

- I'd like to thank my mentor Spencer Barriball for his patience and guidance throughout my project.

- I'd also like to think my Partner Chrissy for putting up with the long nights in font of the computer.
