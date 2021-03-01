# Milestone Project 1

## Christine Clyde Dog Walking

![responsive image](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Multidevicespic.png)

[link to live project](https://github.com/whatnote/MileStoneOneDogServices)

## Project Summary

This project is my Milestone 1 I’ve decided to couple it with a new site for my Partner's dog walking business. Due to covid-19, the world has changed; home working has meant the need for dog walking isn't what it once was, but there has been a steep increase in people and families getting dogs; especially puppies.

With this my partner, Chrissy, has taken to opportunity to retrain and up-skill her dog walking business and extend it to include puppy and dog training. Chrissy has completed one diploma, and to is now well underway in her dog behavioural diploma.

Once the new normal is establish, the new online presence should prove a vital tool in finding new clients.

## Contents

- [User Experience Design](#User-Experience-Design)
  - [User Stories](#User-Stories)
  - [Structure](#Structure)
  - [Design](#Design)
    - [Colour Scheme](#Colour-Scheme)
    - [Typography](#Typography)
    - [Wireframes](#Wireframes)
- [Features](#Features)
- [Technologies Used](#Technologies-Used)
- [Testing](#Testing)
- [Deployment](#Deployment)
- [Credits](#Credits)

# User Stories

# User Experience Design

## Target Audience:

- Letting existing client, both old and current, of Chrissy's skill set.
- People with new puppies who require training.
- People with new dogs/ dogs who require training.
- People with new puppies who require walking.
- People with new dogs/ dogs who require walking.

## User Stories

- Will want to be able to see the services available.
- See opening times.
- See costs for walks and dog training.
- See current client reviews.
- See information about insurance.
- See information about qualifications.
- See information about dog walking licence
- See information about DBS check
- have a contact us form
- have a an email option
- have a mobile number displayed.

## Design

### Colour Scheme

- I opted for a simple black and white, the picture of the dogs would add the needed colour.

## Typography

- I opted to use Yantramanav font for the Title, nav bar and headings, I augmented the paragraph text with, roboto as it is still very readable at small size, ideal for mobile screens.

## Wireframes

Mobile <br>
![Mobile Wireframe](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/wireframes/Mobile.png)<br>

Destop Page<br>
![Desktop Wireframe](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/wireframes/Desktop.png)<br>

# Features

# Technologies Used

- [Html](https://www.w3schools.com/html/) - Hyper Text Markup Language, used for creating the website.
- [Css](https://www.w3schools.com/css/) - Cascading Style Sheet, used for styling the website.
- [Bootstrap](https://getbootstrap.com/) - Bootstrap grid system, navigation bar.
- [Font Awesome](https://fontawesome.com/) - Font awesome Icons are used for the Social media links contained in the Footer section of the website.
- [Google Fonts](https://fonts.google.com/) - Google fonts are used in the project to import the Yantramanav and Open Sans.
- [Balsamiq](https://balsamiq.com/) – Used for creating the wireframes.
- [Git](https://git-scm.com/) - Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.
- [GitHub](https://github.com/) - GithHub is the hosting site used to store the source code.
- [Gitpod](https://www.gitpod.io/) - Development environment where the site was built.
- [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools) -
- [W3C HTML validator](https://validator.w3.org/) - Used to test the html code.
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/) - Used to test the CSS code.

# Testing

## Code Testing

### HTML Testing

I began testing my html, using [W3C HTML validator](https://validator.w3.org/), the initial test noted 26 errors.

![HTML Testing 26 error](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/htmltest26error.jpg)<br>

The most numerous error was \ being used instead or // for the img src links, this is note worth as I was pulling the relative file path via the right click from github ide. So worth noting this is not the necessary the best way to do this.

Another error were styling items on the google iframe element, I moved these to the CSS file and that fixed those errors.

The last two errors were:

![The last two errors](https://github.com/whatnote/MileStoneOneDogServices/blob/master/assets/images/Testing/htmllasttwoerrors.jpg)<br>

The last two errors to resolve was having and a tag and a child of the button class, I struggled to find a solution wanting to have a button to ring a number or send an email, and when I experimented with the a element in the button element, and it worked I was very pleased, but just because it works doesn't mean it’s a good idea.

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

# Credits

## Code

- [Bootstrap Nav Bar with Links](https://getbootstrap.com/docs/4.5/components/navbar/).

- W3 Schools [How To Place Images Side by Side](https://www.w3schools.com/howto/howto_css_images_side_by_side.asp).

- Bootstrap Grid System [Grid system](https://getbootstrap.com/docs/4.0/layout/grid/)

## Content

- The copy is written by me, and at this stage is more as placeholder text than the finished article.

## Media

- Most of the images of the dogs are my own apart from Remy the dog, that was taken by [icephotography](https://www.icephotography.co.uk/)

- the silluettes of the dogs are free to use pics from

- documents used are either the geniun article of dummy versions if the orginal contains too much infoamtion. Eg the Puiblic Liability policy doesn't provide a PL certificate in the same way an Employer;s Liability policy does. The PL schedule details everything, including the premium paid and staff discount obtained. So I made the decision to provide a dummy certificate.

## Acknowledgements

- I'd like to thank my mentor Spencer Barriball for his patience and guidance throughout my project.

- I'd also like to think my Partner Chrissy for putting up with the long nights infont of the computer.
