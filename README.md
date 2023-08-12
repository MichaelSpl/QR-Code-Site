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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](/images/final-qr-page.JPG)

### Links

- Solution URL: https://github.com/MichaelSpl/QR-Code-Site
- Live Site URL: https://michaelspl.github.io/QR-Code-Site/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned how to center div's and objects within div's, the various measurements used in CSS, how to use imported custom fonts on a website, and how two display a website on different screens.

```CSS
@font-face {
    font-family: "Outfit";
    src: url(fonts/Outfit-VariableFont_wght.ttf);
}

@media screen and (max-width: 500px) {
    .code {
        width: 300px;
        height: 480px;
    }

    .code img {
        width: 260px;
    }

    .first {
        font-size: 19px;
    }

    .second {
        font-size: 16px;
    }
}
```

The @font-face and @media were definitely the most interesting pieces of code I had to work with.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I definitely want to focus on making websites more dynamic using features like @Media. I'm also going to try using different measurements thatn px more often.

### Useful resources

- (https://www.freecodecamp.org/news/css-unit-guide/) - This reasource was very helpful in understanding various CSS units.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@MichaelSpl](https://www.frontendmentor.io/profile/yourusername)
