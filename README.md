# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Screenshot

-[Desktop Version](screenshots/DesktopV.png)
-[Desktop Version Button Hover](screenshots/DesktopV-hover.png)
-[Mobile Version width:375 px](screenshots/MobileV.png)
-[Mobile Version Button Hover width:375 px](screenshots/MobileV-hover.png)


### Links

- [Solution URL](https://github.com/DevCloty/Product-Preview)
- [Solution Live URL](https://devcloty.github.io/Product-Preview/)


## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid
- Responsive
- [Styled Components](https://fonts.google.com/) -Frauces Bold 700 / Montserrat Medium 500 Bold 700


### What I learned

With this challenge I have been able to improve my knowledge about flex and grid behavior.
Also, something new that I have learned is to be able to add several images to an html and activate them through css as it suits me with display attribute.


```html
<div class="image">
  <img src="images/image-product-desktop.jpg" alt="product" class="desktop">
  <img src="images/image-product-mobile.jpg" alt="product" class="mobile">
</div>
```
```css
img.desktop {
  display: inherit;
  max-width: 100%;
}
img.mobile {
  display: none;
}

@media only screen and (max-width: 375px) {
  img.desktop {
    display: none;
  }
  img.mobile {
    display: inherit;
    max-width: 100%;
  }
}  
```


### Useful resources

- [Flexbox and Grid](https://www.youtube.com/watch?v=3elGSZSWTbM) - This video was very useful for me to understand the behavior of flexbox and grid.


## Author

- GitHub - [Claudia Torres](https://github.com/DevCloty)
- Frontend Mentor - [DevCloty](https://www.frontendmentor.io/profile/DevCloty)
