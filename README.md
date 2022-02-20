# Frontend Mentor - Order summary card solution

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

-This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

- Build it to look as close as possible to the design provided.

Users should be able to:

- See hover states for interactive elements

### Screenshot

![active-states](https://user-images.githubusercontent.com/49578782/152716898-26f162e9-81f7-4897-8fb5-ce3d250a1737.jpg)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/order-summary-card-scss-and-flexbox-dicpalbNt
- Live Site URL: https://order-summary-card-732.pages.dev/

## My process

- Go over the design images and visualize how i want to build it
- Set up the HTML using proper semantics and meaningful naming for the classes
- Start with mobile layout first then desktop layout going from top to bottom
- use devtools in browser to test responsiveness
- load the website in different browsers to make sure no odd behaviors occur

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Sass

### What I learned

- I learned sass and this was my first project using it.
- How to create mixin, function, variables and more
- How to break down my project into different modules(artials) which i really like, it makes things less confusing when going over my codes after i'm done

```scss
@mixin flex($direction) {
  display: flex;
  align-items: center;
  flex-direction: $direction;
}

@mixin responsive($breakpoint) {
  @if $breakpoint == desktop {
    @media only screen and (min-width: 62rem) {
      @content;
    }
  }
}

@function weight($weight-name) {
  @return map-get($font-weights, $weight-name);
}
```

### Continued development

- I want to continue to learn more about sass and how to nest my styles correctly without overdoing it

- I want to get a better understanding of functions and in which situations it's needed to be used.

- With @import being replaced by @use/@forward i want to get a broader understanding on how or when to use @forward which is not clear to me yet

### Useful resources

- [https://www.youtube.com/watch?v=nu5mdN2JIwM&t=2048s] - Learned Sass with this crash course from Traversy media. His teaching method is very clear which helped me get started with Sass pretty quick.

- [https://www.youtube.com/watch?v=CR-a8upNjJ0] [https://www.youtube.com/watch?v=dOnYNEXv9BM&t=1012s]- Found these two videos while researching about sass where i learned about @use/@forward replacing @import in sass, very helpful as they also demo how to use them.

## Author

- Frontend Mentor - [@Dblack84](https://www.frontendmentor.io/profile/Dblack84)
- Twitter - [@D_Black84](https://www.twitter.com/D_Black84)
