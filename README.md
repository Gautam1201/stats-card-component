# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

This is my solution to frontend mentor's challenge "Stats preview card component". I implemented this using CSS Grid and Flexbox.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Design preview for the Stats preview card component](./images/Screenshot-preview-card.jpg)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/mobile-first-statscardcomponent-site-using-css-grid-and-flexbox-_Q5z_eEZF)
- Live Site URL: (https://stats-component-card.netlify.app/)

## My process
First I started with the mobile-view, then proceeded with the desktop-view.
I used the grid layout for the main container so as to position its respective components.
I also used the flexbox to position the stats component.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to overlay a color over an image and also position the items when the size of device's screen changes.

CSS for positioning grid elements: content and image container.

```css
@media only screen and (min-width: 1050px){
  .content{
    padding: 3rem 4rem;
    justify-content: center;
    grid-row-start: 1;
    grid-row-end: 2;
    border-radius: 8px 0 0 8px;
    text-align: left;
    grid-gap: 1rem;
  }
}
```

Specifying grid item's starting and ending position for one container repositions this context container and
which automatically also positions the image container.  

### Useful resources

- [StackOverflow](https://stackoverflow.com/) - This site helped me provide an idea on how to position grid elements.
- [W3schools](https://www.w3schools.com/) - This is an amazing site that helped me rectify any confusion in some topic of HTML or CSS.

## Author

- Frontend Mentor - [@Gautam1201](https://www.frontendmentor.io/profile/Gautam1201)
