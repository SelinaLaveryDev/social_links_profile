# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social links profile on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

In this small project, you'll build out your social link-sharing profile. 

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](https://sel-dev-bucket.s3.us-east-1.amazonaws.com/Frontend-mentor/blog-preview-2.png)

### Links

View my solution [here](https://selinalaverydev.github.io/blog-preview-card/)

## My process

- Revised the instructions and design documents
- Defined CSS variables for text presets set out in the figma file
- Wrote up semantic HTML
- Used flexbox for responsiveness

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how quickly Figma can help define CSS variables for text presets.

```css
:root {
  /* colours */
  --grey-900: #141414;
  --grey-800: #1f1f1f;
  --grey-700: #333333;
  --green-100: #c4f82a;

  /* typography */
  --inter-reg: "Inter-Regular";
  --inter-semibold: "Inter-SemiBold";
  --inter-bold: "Inter-Bold";
  --text-24: 2.4rem;
  --text-14: 1.4rem;
}
```

Created classes using the variables to match with the Figma design styles

```classes
.text-preset-1 {
  font-family: var(--inter-semibold);
  font-size: var(--text-24);
  color: white;
}

.text-preset-2 {
  font-family: var(--inter-reg);
  font-size: var(--text-14);
  color: white;
}

.text-preset-2-bold {
  font-family: var(--inter-bold);
  font-size: var(--text-14);
}

.text-preset-1,
.text-preset-2,
.text-preset-2-bold {
  line-height: 1.5;
  text-align: center;
}
```

Here, I used @font-face to use the font file in assets:

```@font-face {
  font-family: "Inter-Bold";
  src: url("/assets/fonts/static/Inter-Bold.ttf") format(opentype);
}

@font-face {
  font-family: "Inter-Regular";
  src: url("./assets/fonts/static/Inter-Regular.ttf") format(opentype);
}

@font-face {
  font-family: "Inter-SemiBold";
  src: url("./assets/fonts/static/Inter-SemiBold.ttf") format(opentype);
}

```

## Author

- [My Portfolio Website](https://selinalaverydev.github.io/selina-dev-portfolio/)
- [My Frontend Mentor Profile](https://www.frontendmentor.io/profile/SelinaLaveryDev)
- [My Github Profile](https://github.com/SelinaLaveryDev)
