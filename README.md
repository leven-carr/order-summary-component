# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Setup steps: Create an assets folder containing folders for images and css. Link the favicon, font, and styles.css in the head. Write the custom variables and the universal reset styles in CSS.

Working on the HTML: Create a main element to hold the content, and give it a class of flex-container to be used to center it on the page. Create an article element to be the card, and give it two direct children: an img with a class of hero-img and a div with a class of card-content to hold the textual content of the card. Inside .card-content, put an h1 for the card title, a p for the descriptive text, then a div with a class of plan-tab. This div should have three direct children: first the music icon img, then a div that holds the plan name and price, then the Change link. Outside .plan-tab, create two buttons with classes of payment-btn and cancel-btn, respectively.

Styling: Write the default flexbox styles, then the body styles, including its background-image. Also in the body, include the font-family, font-size, and font-weight to be inherited by most of the elements on the page. Set min-height and padding on the main element. Then move onto styling the card and its descendants, being sure to adjust the flexbox rules for any flexboxes that need a different flex-direction, gap, etc. Write styles for the hover state on interactable elements, and then write media query styles for large screens. Lastly, I went back and added CSS transitions to those styles that adapt to the media query.

### Built with

HTML and CSS, including Flexbox

### What I learned

This was a simple challenge that didn't have anything brand new to me, just practice with HTML and CSS.

### Continued development

Continue practicing writing class names that are concise but still self-explanatory for others viewing my code.

## Author

- Frontend Mentor - [@leven-carr](https://www.frontendmentor.io/profile/leven-carr)
- GitHub - [@leven-carr](https://github.com/leven-carr)
