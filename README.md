# Frontend Mentor - Product Preview Solution

Hi, Niels here.
This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).
[Hosted on GH Pages](https://nielsfechtel.github.io/frontendmentor_2_four_cards/).

## Table of contents

- [Frontend Mentor - Product Preview Solution](#frontend-mentor---product-preview-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### Screenshot

![](./Screenshot.png)

### What I learned

Honestly, I was mostly fighting with grid-auto-placement, but I don't think that's compatible with the way you can place items over multiple rows with `template-area`. Maybe this should just have been a wrapping flexbox. It's also not really responsive on smaller sizes, but I'm kinda done with this for now. At least I learned about placing content with `template-area`:

```css
grid-area: 1 / 1 / 2 / 3;
```

## Author

- Website - [Niels Fechtel](https://niels-fechtel.com)
