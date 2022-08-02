# Ramen addict

![Ramen addict mockup img](assets/redmefiles/mockup.jpg)

Ramen addict is a made-up blogger who wants to create a community for ramen lovers. This is a page that will bring the history of ramen and connect the blogger's audience to the community and social media accounts.

Visit the deployed website [here](https://cbergane.github.io/ramenaddic/).

## Table of Contents

1. [User Experience UX](#user-experience-ux)
    1. [Project goals](#project-goal)
    2. [Audience story](#Audience-story)
    3. [Color scheme](#color-scheme)
    4. [Typography](#typography)
    5. [Wireframes](#wireframes)
2. [Featured Design](#featured-design)
    1. [General](#general)
    2. [Landing Page](#landing-page)
    3. [Gallery Page](#gallery-page)
    4. [Sign Up Page](#sign-up-page)
3. [Technologies Used](#technologies-used)
    1. [Languages Used](#languages-used)
    2. [Frameworks, Libraries and Programs Used](#frameworks-libraries-and-programs-used)
4. [Testing](#testing)
    1. [Testing audience stories](#testing-audience-stories)
    2. [Code validation](#code-validation)
    3. [Accessibility](#accessibility)
    4. [Tools Testing](#tools-testing)
    5. [Manual Testing](#manual-testing)
5. [Finished Project](#finished-project)
6. [Deployment](#deployment)
    1. [GitHub Page](#github-page)
7. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)
    3. [Code](#code)
8. [Acknowledgments](#acknowledgments)

***

## User Experience UX

### Project goals

* This website is acting like a hub for the user to educate about ramen history and direct its audience to the community.
* To give a sample of some of its content on social media.
* To provide a way for the audience to sign up for more content of their choice.

### User Story

* As an audience, it should be easy to navigate through the site and get a grip of what it is about.
* As an audience, you should easily find the user's social media profiles.
* As an audience, you should find sample content on social media easily.

### Color Scheme
![Color Scheme image](assets/readmefiles/color-palette.jpg)
                        
These colors are used to make a simple but clear color scheme, in Japanese, the simpler the better. I chose pink cherry blossom pink #ffb7c5 since it represents cherry blossom. And a charcoal black #212121 for a base color for most text and color of gray #fafafa, gray98 for areas where charcoal black is hard to read, such as overlapping images.

### Typography

The main font is Karla with a fallback font of Sans-Serif in case Karla is not being imported correctly.
### Wireframes

[Balsamiq](https://balsamiq.com) was used to build the wireframes to showcase the elements of the site.

Page | Desktop version | Mobile version |
--- | --- | --- | ---|
Index | ![Desktop index wireframe image](assets/wireframes/index.html.png) | ![Mobile index wireframe image](assets/wireframes/Phone%20main.png)
Gallery | ![Desktop gallery wireframe image](assets/wireframes/Gallery.html.png) | ![Mobile gallery wireframe image](assets/wireframes/Phone%20gallery.png)
Sign up | ![Desktop sign-up wireframes image](assets/wireframes/Sign%20up.png) | ![Mobile sign-up wireframes image](assets/wireframes/Sign%20up_2.png)
Tablet | ![Desktop tablet wireframe image](assets/wireframes/Tablet.png)

[Back to top ⇧](#Ramen-addict)

## Featured Design

### General
* Responsive design across all platforms and devices.
* The colors are the same across the site.
* **Header**
![Header image](assets/readmefiles/header.jpg)

    - The header image contains the page title and a nav bar and is responsive to the top of the page.
    - The title contains a link back to index.html.
    - The nav bar is identical across the site and responsive to smaller screens. It contains hover effects to make it easier to navigate to the desired content. And it contains fontawesome icons for the content of choice.

* **Footer**
![Footer image](assets/readmefiles/footer.jpg)

    - The footer contains social media links and a hover effect for the fontawesome icons to highlight the audience's choice.

### Landing Page

* **Hero image**
![Hero image](assets/readmefiles/hero-img.jpg)

    - The hero image contains a background image and a message about the purpose of the page.

* **Main Page**
![Main page](assets/readmefiles/index.jpg)

    - The main page contains the history of ramen and its origin and a fixed background that is fixed across the three sections of history.

### Gallery Page

* **Gallery**
![Gallery image](assets/readmefiles/gallery-grid.jpg)

    - The gallery page contains a sample of the social media content that the audience can expect. The images contain hover effects and a short text to describe the image.

### Sign Up Page

* **Sign up page**
![Sign-up image](assets/readmefiles/sign-up.jpg)

    -The sign-up page contains a fixed background image and a form with inputs of first, last name and a email input. They are required so you can't leave them empty. Radio buttons for the subscriber's choice of content and a submit button.

## Technologies Used

### Languages Used
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks Libraries And Programs Used

* [Google Fonts](https://fonts.google.com/)
    - Google Fonts was used to import the fonts Lato and Karla into the style.css stylesheet. These fonts are used throughout the site.

* [Font Awesome](https://fontawesome.com/)
    - Font Awesome was used throughout all pages to add icons to create a better visual experience for UX purposes.

* [VS Studio Code](https://code.visualstudio.com)
    - Vs Studio Code was used to write the code and to commit and push content to github.

* [GitHub](https://github.com/)
     - GitHub was used to store the project after pushing.

* [Balsamiq](https://balsamiq.com/)
     - Balsamiq was used to create the wireframes during the design phase of the project.

* [Am I Responsive?](http://ami.responsivedesign.is/#)
    - Am I Responsive was used to see responsive design throughout the process and to generate a mockup image.

* [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
    - Chrome DevTools was used during the development process for code review and to test responsiveness.

* [W3C Markup Validator](https://validator.w3.org/)
    - W3C Markup Validator was used to validate the HTML code.

* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
    - W3C CSS Validator was used to validate the CSS code.

[Back to top ⇧](#ramen-addict)

## Testing

### Testing audience story

* When visiting the website I want a clear understanding of the content.
    - Nav bar is clearly in the corner and easily understood. And is in the same place on all the pages.
* As an audience, I want to find more content on social media easily.
    - Social media links are clearly at the bottom of all the pages.
* As an audience, I want to find a way to get more relevant content from the author.
    - The sign-up page s a quick way for the audience to take part in any specific content.

### Code Validation

* The [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator) services were used to validate all pages of the project to ensure there were no syntax errors.

    - W3C CSS Validator found no errors or warnings on my HTML.
    [W3C Markup Validator index](assets/readmefiles/validator.w3.org-nu-index.png)
    [W3C CSS Validator gallery](assets/readmefiles/validator.w3.org-nu-gallery.png)
    [W3C CSS Validator sign-up](assets/readmefiles/validator.w3.org-nu-sign-up.png)

    - W3C CSS Validator found no errors or warnings on my CSS.
    [W3C CSS Validator](assets/readmefiles/jigsaw.w3.org-css-validator.png)

### Accessibility

* Used lighthouse to measure accessibility in Chrome DevTools.

* Lighthouse reports.

    - Landing page.
    ![Lighthouse report for landing page](assets/readmefiles/index-preformence.jpg)

    - Gallery page.
    ![Lighthouse report for gallery page](assets/readmefiles/gallery-preformence.jpg)

    - Sign up page.
    ![Lighthouse report for sign up page](assets/readmefiles/sign-up-preformence.jpg)

* Responsiveness
    
    - [Am I Responsive?](http://ami.responsivedesign.is/#) was used to check the responsiveness of the site pages across different devices.

    - Chrome DevTools was used to test responsiveness in different screen sizes during the development process.

### Manual Testing

* Browser Compatibility

    - The website has been tested on the following browsers:

    **Google Chrome**
        
        No appearance, responsiveness nor functionality issues.

    **Safari**
        
        No appearance, responsiveness nor functionality issues.

* Device compatibility

    - The website has been tested on the following devices:

    **MacBook Air**

    No appearance, responsiveness nor functionality issues.

    **iPhone 12pro**

    No appearance, responsiveness nor functionality issues.

    **Ipad mini**

    No appearance, responsiveness nor functionality issues.

* Common Elements Testing.

    - All Pages.
        
        **Header**
        - Clicking the main logo will bring you back to the main page.

        **Navigation bar**
        - Hovering over the navigation bar will highlight the choice you will make.
        - The active page is always highlighted.
        - Clicking the navigation bar will bring you to the desired page.

        **Footer**
        - Clicking the social media button will bring you to the social media page of your choice.
        - Hovering on the icons will highlight the icons.

    - Index page.

        **Main Section**
        - A section of ramen history in 3 sections, they all share a fixed background image.

    - Gallery pages.

        **Gallery**
        - The gallery is displayed in a responsive grid.
        - All images have hover effects.
    
    - Sign Up page.

        **Sign Up**
        - The form section has 3 input fields and all are required to sign up.
        - The input field for email is set to email so an @ is needed to send in.
[Back to top ⇧](#ramen-addict)

## Finished Project

Page | Desktop version | Mobile version
--- | --- | ---
Index | ![Desktop version screenshot](assets/readmefiles/ramen-addic-index-desktop.png) | ![Mobile version screenshot](assets/readmefiles/ramen-addict-index-mobile.png)
Gallery | ![Desktop version screenshot](assets/readmefiles/ramen-addic-gallery-dektop.png) | ![Mobile version screenshot](assets/readmefiles/ramen-addict-gallery-mobile.png)
Sign Up | ![Desktop version screenshot](assets/readmefiles/ramen-addic-sign-up-desktop.png) | ![Mobile version screenshot](assets/readmefiles/ramen-addict-sign%20up-mobile.png)

[Back to top ⇧](#ramen-addict)

## Deployment
* This website was developed using [GitPod](https://www.gitpod.io), which was then committed and pushed to GitHub using the GitPod terminal.

### Githup Pages

* I followed these steps to deploy my site on GitHub.
    1. Log in to GitHub and locate the [GitHub Repository](https://github.com/).
    2. At the top of the Repository, locate the Settings button on the menu.
    3. Scroll down the Settings page until you locate the Pages section.
    4. Under Source, click the dropdown called None and select Master Branch.
    5. The page will refresh automatically and generate a link to your website

[Back to top ⇧](#ramen-addict)

## Credits

### Content

- All content is written by the developer.

### Media

* Own pictures
    - Gallery images of ramen bowls are taken from vacation in Japan.

* [Pixabay](https://pixabay.com)
    - Hero image: Chef making ramen by Vardan Sevan.

* [Rawpixel](https://www.rawpixel.com)
    - Origin: An image report of the Russo-Japanese War, number one (1904) by Kogyo Tsukioka. Original from The Rijksmuseum. Digitally enhanced by rawpixel.
    - Sign up: Mt. Fuji from Tagonoura, Snow Scene (1932) print in high resolution by Hiroaki Takahashi. Original from The Los Angeles County Museum of Art. Digitally enhanced by rawpixel.
    - Ramen restaurant: Several people eating at a counter in an Asian café. Original public domain image from Wikimedia Commons.
    - Ramen bowl vegan: Free vegan ramen image, public domain food CC0 photo.
    - Woman eating ramen: By Tanasiri, Asian woman eating instant noodles during coronavirus quarantine.

* [Unsplash](https://unsplash.com)
    - Ramen noodles: Taken by Jakub Dziubak
    - Tonkotsu ramen: Taken by Kim Daeyoung
    - Spicy noodles: taken by M. W.
### Code

* [Stack Overflow](https://stackoverflow.com/), [Traversy Media](https://www.youtube.com/c/TraversyMedia), [dcode](https://www.youtube.com/c/dcode-software), [Love Running](https://codeinstitute.net/) were used for inspiration and guidelines to get the structure of the project.

[Back to top ⇧](#ramen-addict)

## Acknowledgments

* To my wife and son for letting me accomplish this on our vacation.

* Code Institute and its amazing Slack community for their support and for providing me with the necessary knowledge to complete this project.

* My mentor Marcel for giving quick guidance and feedback.

[Back to top ⇧](#ramen-addict)