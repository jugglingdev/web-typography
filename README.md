# Interneting Is Hard - Web Typography

This is a solution to the [Web Typography tutorial No. 14 of HTML & CSS Is Hard](https://www.internetingishard.com/html-and-css/web-typography/).

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshots

![Web Typography screenshot](./screenshots/web-typography.png)
![History screenshot](./screenshots/history.png)
![Indents screenshot](./screenshots/indents.png)
![Alignment screenshot](./screenshots/alignment.png)
![Spacing screenshot](./screenshots/spacing.png)
![Line Length screenshot](./screenshots/line-length.png)

### Links

- Solution URL: [Web Typography solution](https://github.com/jugglingdev/web-typography)
- Live Site URL: [Web Typography live site](https://jugglingdev.github.io/web-typography/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

This tutorial started with a brief history of web fonts, which was helpful.  The web went from roughly a dozen web safe fonts to custom web fonts with 4 different file formats (.svg, .eot, .ttf, and .woff) to standardized .woff and .woff2 fonts.

Next, this tutorial covered the two ways to add web fonts to a site:  locally or externally.

For a locally hosted web font, you download a web font from a site like [Font Squirrel](https://www.fontsquirrel.com/) and add it to your project.  Then, you embed the font at the top of your stylesheet as in this code:

```css
@font-face {
  font-family: "Roboto"
  src: url("Roboto-Light-webfont.woff") format("woff");
}
```
Now that the font is embedded, you can apply it to your site in the stylesheet!



*Font Families and Font Faces*

*Put Externally Hosted Web Fonts above previous section*


### Continued development

Use

### Useful resources

- [Bulletproof @font-face Syntax](https://www.paulirish.com/2009/bulletproof-font-face-implementation-syntax/) - Great resource for @font-face definitions.
- [Font Squirrel](https://www.fontsquirrel.com/) - Free fonts for commerical use.  Big selection with some good fonts to dig for.
- [Google Fonts](https://fonts.google.com/) - Another resource for good quality free fonts.
- [Fontspring](https://www.fontspring.com/) - For projects with a bigger budget, Fontspring is worth looking at.  Huge selection of excellent fonts.

## Author

- GitHub - [@jugglingdev](https://github.com/jugglingdev)

- freeCodeCamp - [@jugglingdev](https://www.freecodecamp.org/jugglingdev)

- Frontend Mentor - [@jugglingdev](https://www.frontendmentor.io/profile/jugglingdev)

- LinkedIn - [Kayla Paden](https://www.linkedin.com/in/kayla-marie-paden)

## Acknowledgments

Shoutout to Oliver James for his dedication to publishing and maintaining InternetingIsHard.com.  His tutorials were the first that really clicked for me.