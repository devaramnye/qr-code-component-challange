# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/devaramnye/qr-code-component-challange]
- Live Site URL: [https://devaramnye.github.io/qr-code-component-challange/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I learned today that I should avoid setting heights in my CSS as it loses responsivness. I tryed to start with Mobile-first workFlow. Using percentage in widths in relative to the parent is a good way to work responsive. I learned from Grace-Snow to use (rem) for max-width as it makes better experience for user who change their device/browser font-size. As well I learned to never use px for font-size, so in this project and in the future I will use rem for font-size. I played a little abit with margin and padding which gave me a deeper dive of understanding.


```html
<body>
  <main>
    <div class="qr-card">
      <img class="qr-code" src="./images/image-qr-code.png" alt="a QR-Code which brings you to frontend-mentor page">
      <h1 class="heading">Improve your front-end skills by building projects</h1>
      <p class="paragraph">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
   </div>
  </main>
</body>
```
```css
* { box-sizing: border-box; }

body {
    margin: 0;
    background: hsl(212, 45%, 89%);
    font-family: "Outfit", sans-serif;
    min-height: 100vh;
    display: grid;
    place-content: center;
}

main {
    max-width: 18rem;
    margin: 1rem auto;
    background: hsl(0, 0%, 100%);
    border-radius: 20px;
    padding: 1rem;
}

.qr-code {
    width: 100%;
    border-radius: 15px;
}

.heading, .paragraph {
    text-align: center;
}

.heading {
    color: hsl(218, 44%, 22%);
    font-weight: 800;
    font-size: 1.25rem;
}

.paragraph {
    font-size: 0.9rem;
    color:  hsl(220, 15%, 55%);
    margin: 0 0.1rem;
}
```

### Continued development

I am currently working on responsive coding. Currently doing the 21 challange from Kevinpowell. Day one started (03.08.2023) and already day one helped me extremly by understanding that CSS is responsive by default and we are mainly causing the problems of the responsive threatment of CSS. I will continue working on my knowledge of grid and flexbox.