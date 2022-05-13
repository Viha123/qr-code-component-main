# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

  ![](images\qr-code-desktop.PNG)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- First, I worked on the mobile version, and then I realized that the main part of the card was the same thing. 
-So all I had to do was change the margin for the smaller and bigger one. 
-Learned basic stuff, I have a feeling that I hardcoded this, so I want to see other solutions to guage the proper way so that it works on all kinds of screens. 
### Built with

- Semantic HTML5 markup
- CSS


### What I learned

I only used basic CSS such as margins, padding, font size and border-radius. I learned how to use that to make a cool looking webpage that was already designed for me. 


```css
@media screen and (max-width: 375px){
    .inner-card{
        margin-top: 25%;
        margin-left: 10%;
        margin-right: 10%;
        border-radius: 5%;
        background: hsl(0, 0%, 100%);
    }
}
```

### Useful resources

- [Example resource 1](https://www.w3schools.com/) - This helped me learn the media queries part, to be able to do both the mobile and desktop component. 


## Author

- Website - [Add your name here](https://viha123.github.io/index.html)
- Frontend Mentor - [@Viha123](https://www.frontendmentor.io/profile/Viha123)


## Acknowledgments

Thank you to Kevin Powell from CSS tips and tricks to introduce me to Frontendmentor to improve my skills.

