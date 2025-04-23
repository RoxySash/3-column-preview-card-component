# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop View](./images/Desktop%20Screenshot%203%20column%20preview%20card.png)


### Links

- Solution URL: [Github](https://github.com/RoxySash/3-column-preview-card-component.git)
- Live Site URL: [Live Site](https://roxysash.github.io/3-column-preview-card-component/)

## My process

1. Initialized project as a public repository 
2. Configured repository to publish your code to a web address. 
3. Looked through the designs to started planning. 
4. Wrote HTML classes and added divs or sections.
5. Wrote out the base styles for my project, including general content styles, such as `font-family` and `font-size`.
6. Started adding styles to the top of the page and work down. Jumped back and forth for a while. 
7. After using dev tools to check responsiveness on various screen sizes I concluded that the project was complete. 
8. Final Push 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned that the more challeneges I do the faster I get at completing them.

With the breakpoint at 720px it looks terrible on mobile horizontal screen. I decided to point the breakpoint at 800. What I could do is modify the width to be a certain percent width of the screen to ensure less white spaces on the sides.


To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
@media (min-width: 800px) {
  body {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }

  .card__one {
    border-top-right-radius: 0px;
    border-bottom-left-radius: 10px;
  }

  .card__three {
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0px;
  }

}
```


### Continued development

I completed this very quickly compared to the other projects. I want to develop my css style it needs to look more refined.


### Useful resources

- [Josh's CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@RoxySash](https://www.frontendmentor.io/profile/RoxySash)
- Blesky - [@roxanedev.bsky.social](https://bsky.app/profile/roxanedev.bsky.social)



