# Welcome to my very first website [Sparrow's Nest](https://maya-claveau.github.io/PP1-Sparrows-Nest/)

<img src="assets/images/responsive-mockup.png" width="800">

This website is for a holiday accommodation based in Larnaca Cyprus, intend for people who love travelling either for leisure or work, or for no special reason at all, you just want to be on this beautiful island. It is aiming to provide,

- information about this accommodation including size, facilities and furnitures
- communication channel of being able to send request or any message to the owner
- phone number that people can call
- direction to the location, to make the journey smooth
- better idea of how it looks inside with lots of pictures

------

## Why This

The reason I chose to build this website is because Sparrow’s Nest belongs to my best friends, and this place holds a special place in my heart. In May 2018, we were facing one of the most difficult moments of our life as a family, and this place was offered to us for an unlimited time, for free. Calling it our safe boat is understatement. In fact, we had created countless happy moments together with my best friend's family. We bonded after 10 years of being apart. Our kids also became very close. My son was 6 at the time, enjoyed the adventures we embarked together. He is calling them “my old best friends” to this day. This project is dedicated to my lifelong friends(in no preferential order), David, Elina, Jada and Daniel.

------

## Features:
### Existing Features:
#### Home page:

When you land on the website, first you see the name of the accommodation on the top left. On the right hand side you will find navigation links including Gallery, Booking and Contact. Followed by a picture of the front door of the accommodation. There is also a Booking button at the bottom of the image. When it's clicked, it will take you to the booking page.

<br>
<img src="assets/images/features-landing-page.png" width="800">
<br>

Next section contains useful information about the accommodation, aiming to let users know what to expect. As well as the location and brief description of the surrounding area. 

For those who are curious of what other people think of this place, there is a link below the location, when it’s clicked it will take you to an external website: booking.com. 

Pretty cool place right? Wanna know where is it exactly? No worries, you will find a good map to help you locate the place easily right below the review link.
 
On the right side of the map, there is also a request form in place. The intention is to create a communication channel if the users have any questions, requests or just wishing to be added on the mailing list.

<br>
<img src="assets/images/features-desc-direction-form.png" width="800">
<br>

You have reached the footer of the website, here you will find information about contact numbers, address, opening hours, and social media links if you would like to follow us on facebook, instagram, twitter or our youtube channels.

<br>
<img src="assets/images/features-footer.png" width="800">
<br>

### Gallery page

When you head to our gallery page, you will see pictures of the accommodation both from inside and outside. It is aiming to provide a clear picture of the accommodation on top of the description on the home page, so users know exactly what to expect.From here, you can easily go back to home or any other pages using the navigation links on the top right side. The footer containing contact info can be spotted easily as well. 

<br>
<img src="assets/images/features-gallery-page.png" width="800">
<br>

### Booking Page

When you click on the “Book Now” button on the landing image or the Booking on the navigation bar, it will take you to the booking form page. To keep the procedure simple, all you need to do is fill in the name, mail address, dates for check in and out, the number of guests (please note that due to the fact that this accommodation is only 23 sqm, the options are only between 1-3, more than that is not realistic). And here you will have another option to send a message to the owner if you would like. Both navigation links at the top and contact info at the bottom are visible as well from this page.

<br>
<img src="assets/images/features-booking-page.png" width="800">
<br>

Finally when you send a message or the booking request, after you have hit the send button, you will land on a page which confirms that your form is received. With a complimentary picture of Cavo Greco in Cyprus, just to give you an idea of where you could go and visit once you are here. Both navigation links at the top and contact info at the bottom are visible as well from the confirmation page.

<br>
<img src="assets/images/features-confirmation-page.png" width="800">
<br>

### Features to be added in the future

- On the booking form, the date element is only validated by “required”, no other validation method is used at this point, since this website is build with only html and css. Once I am equipped with the relevant knowledge, I am planning to add it.
- I didn't have time to do the 404 page, would be nice to have it
- Chatbox could be also useful for instant communication
- The website also needs a privacy and terms page
- Add information of the surrounding area, especially somewhere you could walk/bike to
- Add local events
- Add bus routes to other cities
- Add taxi offices contacting numbers and prices
- Add more pictures 

------

## Testing:

I used google dev tools heavily for testing purposes. I discovered:

1. Home page has a mysterious extra width. After countless hours of battle, with my amazing mentor’s hint, I finally figured out that the cause was the image. Once I fix that, it looks all fine and sleek as it should look in my head. See screenshot below:

Before <img src="assets/images/testing-home-page-issue-before.png" width="150"> After <img src="assets/images/testing-home-page-issue-after.png" width="150">

2. Footer, sticky footer, unsprisinly, it was one of the challenges I faced. After many videos, tutorios, reading articles and trying different methods, I finally managed with the help of flexbox, thanks to Jim from Code Institute who shared this super easy to understand post on Slack. 

Before <img src="assets/images/testing-footer-issue-before.png" width="150"> After <img src="assets/images/testing-footer-issue-after.png" width="150">


3. The final version of Navigation bar on the mobile version wasn’t looking the same with my original plan from the wireframes. Because I didn’t think of the functionality other than the design itself. With my mentor’s suggestion, this is how the final version looks like. More user friendly compared to my first plan. 

Before <img src="assets/images/testing-mob-v-navbar-before.png" width="150"> After <img src="assets/images/testing-mob-v-navbar-after.png" width="150">


4. The website took it's shape as I was working on it, an example below is the direction and request form section, you can see the jorney it took to progress. 

<img src="assets/images/testing-dir-reqform-v1.png" width="150"> <img src="assets/images/testing-dir-reqform-v2.png" width="150"> <img src="assets/images/testing-dir-reqform-vfinal.png" width="150">

------

## Validator Testing"
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/#validate_by_input)
  <br>
  <img src="assets/images/validation-html-index-page.png" width="150"> <img src="assets/images/validation-html-gallery-page.png" width="150"> <img src="assets/images/validation-html-booking-page.png" width="150"> <img src="assets/images/validation-html-action-page.png" width="150">

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/#validate_by_input). Please note that warnings on CSS I tried to fix them, but the remaining 4 warnings is the code I borrowed from someone else, therefore I left it there, since I don't have the knowledge to fix it at this point.
  <br>
  <img src="assets/images/validation-css.png" width="150"> <img src="assets/images/validation-css.png" width="150">

------

## Language used:

- HTML
- CSS

------

## Tools used: 

- [Google Fonts](https://fonts.google.com/) for selecting the fonts for the project 

- [Font Color](https://mycolor.space/?hex=%232E2E2E&sub=1) I used colorspace to pick the highlight palettes, which in my opinion is nice and simple. <img src="assets/images/color-palette.png" width="150">

- [Am I Responsive](http://ami.responsivedesign.is/) for making the responsive screenshot

------

## Deployment
[Gidhub Pages](https://pages.github.com/) was used to deploy the project, in the following steps:

1. On the Github repository, click on Settings
2. Then click on Page from the lower left of the screen
3. Select Main and click Save

<img src="assets/images/github-deployment-step1.png" width="150"> <img src="assets/images/github-deployment-step2.png" width="150"> <img src="assets/images/github-deployment-step3.png" width="150">

Then a link will be generated for live view, it can be found [here](https://maya-claveau.github.io/PP1-Sparrows-Nest/)


------

## Things I tried but didn't work

1. The main image on the home page, what I wanted to do involved JavaScript (see screenshot wireframe), so I changed to a more simple layout for this project.
2. On the forms I wanted to use the fieldset element along with legend element, but it didn't work with the structure that I have.

------

## Difficulties that I manage to overcome: 

1. on the main-outlayer has a big gap of blue, I manage to remove it. 
2. When I create a form what database do I use for the action attribute? 
Solution: I created a simple thank you page, that way if the form is correctly completed, they get the thank you message. (credit to fellow student Matt Bodden_5P who shared this idea on slack)
3. The biggest challenge for me was the responsive design. I spend way too many hours on it. A note to myself, next time around I start from the mobile version and then expand to bigger screens and see how it works for me.

------

## Credits:
- [Code Institute's Love Running project](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode)
- [W3C Schools](https://www.w3schools.com), [Mozilla Developer](https://developer.mozilla.org) and [Stackoverflow](https://stackoverflow.com/) for countless different elements and how to use them 
- [Dev Ed channel](https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q) for styling the input element
- [CSS Tricks](https://css-tricks.com/css-basics-styling-links-like-boss/) for styling the links
- [CSS tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) for learning how to use flexbox
- [CSS Gradient](https://cssgradient.io/blog/css-gradient-text/) for change the font color of the logo
- [Michael Polla](https://gist.github.com/MichaelPolla/a65ac84286ab523603e64549f9850223) for resize the images/screenshots in README.md file
- [Pexels](https://www.pexels.com/photo/blue-body-of-water-373409/) for downloading the stunning picture of Cavo Greco in Cyprus. Other images used were sent by the owner of Sparrow's Nest. 

------

## Acknowledgments
My amazing mentor for continuous and structured feedback.

Tutor support at Code Institute for their support.

Fellow students and Code Institute at Slack community for their generous sharing of information and ideas.

A special shout out to Scott Böning who helped me to save my work on Git when I messed up the README version on Github and Gitpod on a Saturday evening.

So THANK YOU ALL! Without your help my project wouldn't be the same. 




