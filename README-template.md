# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

### Overview

### Screenshot

![Desktop design](design\screenshot-desktop-design.jpg)
![Mobile design](design\screenshot-mobile-design.jpg)

### Links

- Live Site URL: [LiveSite] (https://qr-code-frontendmentor-solution.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned to make the html take the whole space in the screen, and also, aligment an element in the center.

```css
img {
    max-width: 100%;
    width: 100%;
    border-radius: 1rem;
}
.container {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
```


### Useful resources

- [Netlify](https://app.netlify.com/) - This helped me for deployment my project.
- [Setting the HTML & Body](https://www.freecodecamp.org/espanol/news/html-vs-body-como-configurar-el-ancho-y-el-alto-para-el-tamano-de-la-pagina-completa/) - This is an amazing article which helped me finally understand how to take all the space in the screen when you have few elements in your html. I'd recommend it to anyone still learning this concept.

## Author

- GitHub - [Rosa Urrea](https://github.com/rosa-urrea)
- Frontend Mentor - [@rosa-urrea](https://www.frontendmentor.io/profile/rosa-urrea")
