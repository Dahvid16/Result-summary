# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](assets/completed/Capture.PNG)


### Links

- Live Site URL: (candid-alpaca-2eec89.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework


### What I learned

-I learnt how to center a div to the center of a web page in a desktop mode. it was difficult to get it done but with trial and error i was able to.
```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

-I learnt how to size our desired webpage to any device.
```css
@media only screen and (max-width:100px) {
    .card {
        height: 90%;
        width: 90%;
}
}
```

-I also learnt alot of patience and trust in m codes.
-I also learnt how to import font from my library.
```css
@font-face {
    font-family: myfont;
    src: url(Font/HankenGrotesk-VariableFont_wght.ttf);
}
```


### Continued development

I will love to focus more on sizing a webpage to be accessible to all devices.


### Useful resources

- [Example resource 1] (youtube.com) - This helped me for all my difficulties. I really liked this pattern and will use it going forward.


## Author

- Website - [David Akpom](https://www.your-site.com)
- Frontend Mentor - [@Dahvid16](https://www.frontendmentor.io/profile/Dahvid16)
- Twitter - [@joh_nobody](https://www.twitter.com/joh_nobody)


## Acknowledgments

Acknowledgment goes firstly to God for the insight to making this a success
Secondly my guys "PSN" for being m 3rd eyes in seeing the project.
Lastly to frontendmentor for the wonder mockup set by them, anticipating more in the nearest future.