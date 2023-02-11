# FreeCodeCamp - Documentation Page

This is a solution to the "Documentation Page" task on FreeCodeCamp ["Responsive Web Design"](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- Scrollable side menu

### Screenshot

<p align="center">
  <img src="Снимок экрана 2023-02-11 в 12.59.42.png" alt="Project Photo"/>
</p>

### Links

- Live Site URL: [https://yazdrahobycha.github.io/Fake-Documentation-Project/](https://yazdrahobycha.github.io/Fake-Documentation-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

The objective of this project was to design a visually appealing and responsive web page with a scrolling side menu. To achieve this, the "overflow" properties were utilized:

<details>
<summary>Implementation of oveflow side menu</summary>

```html
<nav id="navbar">
            <header>JS Documentation</header>
            <ul>
                <li><a class="nav-link" href="#introduction">Introduction</a></li>
                ...
                <li><a class="nav-link" href="#reference">Reference</a></li>
            </ul>
        </nav>
```

```css
#navbar ul {
    margin: 1rem 0;
    overflow-y: auto;
    overflow-x: hidden;
    height: 207px;
    border: 1px solid;
}
```

</details>

### Continued development

- Write more consice semantic HTML

## Author

- Instagram - [@yazdrahobycha](https://instagram.com/yazdrahobycha?igshid=YmMyMTA2M2Y=)
- Telegram - [Орсен](https://t.me/yazdrahobb)
