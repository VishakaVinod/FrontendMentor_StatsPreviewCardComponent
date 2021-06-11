# Frontend Mentor - Stats preview card component solution

<!-- Add screenshot img -->
![](images/mobile-screenshot.jpeg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Users should be able to view the optimal layout depending on their device's screen size

### Links

- Solution URL: [https://github.com/VishakaVinod/FrontendMentor_StatsPreviewCardComponent]
- Live Site URL: [https://vishakavinod.github.io/FrontendMentor_StatsPreviewCardComponent/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Google fonts
- Mobile-first workflow

### What I learned

- understood box-sizing property
  ```css
  * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
  }
  ```
- was introduced to the picture tag
  ```html
  <picture>
    <source media="(min-width: 700px)" srcset="images/image-header-desktop.jpg">
    <img src="images/image-header-mobile.jpg" alt="image-header">
  </picture>
  ```

- learnt how to add overlays to background images


### Useful resources

<!-- - [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward. -->

## Author

- Frontend Mentor - [@VishakaVinod](https://www.frontendmentor.io/profile/VishakaVinod)
