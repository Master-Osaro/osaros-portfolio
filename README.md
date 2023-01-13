# Frontend Mentor - Project tracking intro component

![Design preview for the Project tracking intro component coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Create the background shape using code



### Links

- Live Site URL: [Live Demo](https://project-tracking-intro.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox

### What I learned

- Simple mobile nav with css checkbox

```html
    <label for="menu__checkbox">
        <div class="nav__ham-menu"></div>
    </label>
    <input type="checkbox" name="" id="menu__checkbox">
    <div class="nav-list__wrapper">
        <ul class="nav-list">
            <li><a href="">Product</a></li>
            <li><a href="">Features</a></li>
            <li><a href="">Pricing</a></li>
        </ul>
    </div>
```

```css
    #menu__checkbox{
        display: none;
    }

    #menu__checkbox:checked ~ .nav-list__wrapper{
        display:block;
    }

```





## Author
- Frontend Mentor - [@Master-Osaro](https://www.frontendmentor.io/profile/Master-Osaro)
- Twitter - [@iyoha_osaro](https://www.twitter.com/yourusername)

**Had fun building!** 🚀
