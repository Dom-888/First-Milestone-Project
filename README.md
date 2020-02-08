# [**User Centric Frontend Development Milestone Project<br/>The Steve ‘n’ Seagulls Website**](https://dom-888.github.io/First-Milestone-Project/) 

![Band snapshot](https://github.com/Dom-888/First-Milestone-Project/blob/master/assets/images/fire.jpg "Band snapshot")


In this project I have created a website for the cover band The Steve ‘n’ Seagulls, the purpose of the site is to provide fans and potential fans with an easy access to the music produced by the band, as well as key information such as news and tour dates, and finally the possibility to book concerts and buying merchandise, all in one place.
The goal is to keep users coming back for more.
 
## UX

#### User Stories

I Identified two kind of users for this site:
- Existing Fans of The Steve ‘n’ Seagulls
- Potential Fans who have just heard The Steve ‘n’ Seagulls and want to hear more.

##### As a fan of the band I want to...
1. Find out about all the recent news and latest releases.
2. See any upcoming tour dates and be able to book tickets for their concerts.
3. Listen to the most popular Steve ‘n’ Seagulls tracks and watch the related music videos.
4. View photos of the band.
5. Order Steve ‘n’ Seagulls Merchandise
6. Discover tracks that I don't know yet, through two popular media services providers: Amazon Music and Spotify
7. Be able to contact them.
8. Use the site to reach the main social media pages of the band: Facebook, Tweeter, Instagram and Youtube.

##### As a potential fan I want to...
1. Find out who The Steve ‘n’ Seagulls are. 
2. Get an idea of the band's style by listening to a selection of tracks.
3. Return to the site to listen to other songs, get more information about the band and eventually become a fan

#### Strategy

Create an intuitive, responsive and visually pleasing website

#### Scope

##### Content Requirements

Each section of the website must answer a specific requirement

1. Introduce users to The Steve ‘n’ Seagulls 
2. Keep their fans up to date about news related to the band 
3. Allow users to book concerts
4. Show a selection of music videos
5. Show a selection of photo of the band
6. Allow users to buy the band's products
7. Allow users to contact the band

#### Functional Requirements

1. Allow users to navigate easily from one section of the site to another
2. Allow users to access the band social media pages
3. Be fully responsive

#### Skeleton

[Navbar and Footer](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/navbar%26footer.jpg)

[Section 1](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section1.jpg)

[Section 2](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section2.jpg)

[Section 3](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section3.jpg)

[Section 4](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section4.jpg)

[Section 5](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section5.jpg)

[Section 6](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section6.jpg)

[Section 7](https://github.com/Dom-888/First-Milestone-Project/blob/master/wireframes/section7.jpg)

#### Surface

##### Color Palette

For this project I chose rustics, autumn-like colors, that I think may fit well the style of the band

- Dark Brown (#380202): Used for navbar and footer
- Autumn Red (#9A0501): Mostly used to highlight the most important parts of text such: Title, Names of Band Members and Section Headers
- Ultra-Light Gray (#f7f7f7): The site uses an alternation of fixed pictures and light gray as backgrounds for the sections
- Night Blue (#222D5A): Used exclusively for the buttons: "Book now" and "Send". I chose this color to attract the user's attention without clashing too much with the rest of the palette

##### Hover effects

To make navigating the site more pleasant, some hover effects have been added to the following elements:

- Navbar: Hovering on the navbar elements produces a sweep-to-bottom effect that highlights the selected element
- Footer: Hovering on the social media icons of the footer highlight them with the proper social media color
- Buttons: I used the bootstrap buttons but I overwrote the default hover effect with a simple underline, in order to remain consistent with the color palette

## Features

#### Interface

- Mobile-first approach: The site is conceived starting from the smaller screens. Where necessary media queries were then used to adapt or change the content to larger screens

- Semantic HTML: Semantic tags have been used where appropriate

#### Functionality

- Navbar: The site consists of a single scrolling page divided into sections, each of which is accessible at any time thanks to the fixed navbar on top. By default it is compressed into a burger button but expands as soon as there is sufficient space for all its elements.

- Return-to-top button
Note that the navbar lacks the Home button, its function is performed by the Return-to-the-top button.
Since this website is composed of a single scrolling page, the home page corresponds to the top of the page. For this reason instead of the classic upward arrow I used the home icon

#### Features Left to Implement

- Embedded Facebook responsivity must be improved for very small screens (less than 360px width)

- The "sent" button in the contact form should be made functional

- The CSS Property `scroll-behavior: smooth;` was used to smoothly animate the scroll position. This rule is not supported by Internet Explorer, Edge or Safari. JavaScript should be used instead

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 4.3.1 (https://getbootstrap.com/)  was used to create the site layout
- FontAwesome 4.7 (https://fontawesome.com/v4.7.0/) all site icons are taken from fontawesome
- Google Fonts (https://fonts.google.com/) the font used on the site (Ropa Sans) was imported from google fonts
- Iframely (https://iframely.com/) was used to make embedded tweets responsive (I have been authorized to use iframely for free as this project has no commercial purposes)
- Hover.css (http://ianlunn.github.io/Hover/) was used to create the sweep-to-bottom effect in the navbar
- Paint.net (https://www.getpaint.net/) was used for simple image manipulation

## Testing

#### Compatibility

Throughout the development of the project I made extensive use of Chrome DevTools to test the site, with particular focus on responsivity. Before each commit I checked the compatibility of the site with each of the 9 devices simulated by Devtools:
- Galaxy S5
- Pixel 2
- Pixel 2
- Pixel 2 XL
- iPhone 5/SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad
- iPad Pro

In aggiunta ho testato il sito sul mio cellulare: Moto g5s with Android Nougat

#### Content

- Check if all the internal links work (included the return-to-top button) and if they use the smooth scroll behavior correctly
- Check if all the external links work and if they open in a new tab
Form: 
- Test the embedded Twitter tweets an Facebook posts
- Test the embedded Youtube videos
- In the contact form, check if an error message appears if a required field is not entered
- Validate index.html with https://validator.w3.org/

## Deployment

This website was deployed on GitHub from the master branch, it can be accessed from the following Url: https://dom-888.github.io/First-Milestone-Project/

The exact procedure is as follows:
1. Log in to Github
2. Select the repository you want to deploy
3. Under the repository name, click **Settings**.
4. Under "GitHub Pages", use the Source drop-down menu and select the master branch.
5. The message "Your site is ready to be published at *Link* will 
   appear under Github Pages.

In case you want to pull the code from my Github repository:
1. Log in to Github,
2. Navigate to the main page of the repository or click https://dom-888.github.io/First-Milestone-Project/.
3. Under the repository name, click **Clone or download**.
4. To clone the repository using HTTPS, under "Clone with HTTPS", click the clipboard icon. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click **Use SSH**, then click the clipboard icon.
5. Open Git Bash.
6. Change the current working directory to the location where you want the cloned directory to be made.
7. Type git `clone`, and then paste the URL you copied in Step 3.
8. Press **Enter**. Your local clone will be created.

## Credits

#### Text

- The band introduction is from: https://bluegrasstoday.com/steve-n-seagulls-headed-to-the-us-this-summer/

#### Images

The band logo (which is also used for the favicon) is from the official band site: https://stevenseagulls.com/

The landing page was obtained by modifying the poster of the Perunamaa tour with Paint.net

Background images have the following origins:
1. https://twitter.com/
2. https://dice.fm/
3. https://twitter.com/

Gallery images have the following origins:
1. https://www.grimmgent.com/
2. https://twitter.com/
3. https://www.hmschaan.li/
4. https://www.facebook.com/
5. https://www.pinterest.com/
6. https://commons.wikimedia.org/

The image of the cup is from: https://stevenseagulls.merchnow.com/

#### Code

The following elements were copied from getbootstrap.com or w3school.com and then modified to meet the needs of the site
- Navbar: https://getbootstrap.com/docs/4.3/components/navbar/
- Bootstrap buttons: https://getbootstrap.com/docs/4.0/components/buttons/
- Return to the top button: https://www.w3schools.com/howto/howto_js_scroll_to_top.asp
- Tour section: https://getbootstrap.com/docs/4.3/content/tables/
- Gallery: https://getbootstrap.com/docs/4.0/components/carousel/
- Contact: https://www.w3schools.com/css/css_form.asp

Other sources:
- Fixed Backgrounds: https://www.w3docs.com/snippets/css/how-to-change-the-background-image-on-scroll-with-css.html
- Make youtube videos responsive, credit to: https://css-tricks.com/NetMag/FluidWidthVideo/Article-FluidWidthVideo.php 
- Social media color palette: https://brandpalettes.com/

#### Acknowledgements

- Seun Owonikoko: My mentor who helped and supported me throughout the project
- Code Institute tutors: I received a lot of feedback and assistance from them, thanks to which I improved the project


## Final Note

As with many bands, the members have changed over time. This site is about the original founders of the band (2012-2017), not the current ones
