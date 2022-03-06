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

![screenshot of final solution](https://imgur.com/LzwsXgm)

Screenshot of my solution to this challenge - any tips or comments greatly appreciated (pls be constructive!)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process
- Started with [HTML](index.html) and set links to fonts in `<head>` tags and corrected/redirected links to images folder
- Deleted `<style>` tags and created separate [stylesheet](styles/styles.css)
- added a level one heading and paragraph dividing text areas appropriately
- created `div` tags encassing text and to layout and give structure to content of page: 
  - `qr-container`
  - `qr-img`
  - `qr-text`
### Built with

- Semantic HTML5 markup
- CSS custom properties

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Struggled with alignment and CSS - need to review `display` and [css box model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)

centered elements with use of `display: block;` and `text-align: center` *(see code snippet below)*
```css
.qr-container {
    background-color: white;
    display: block;
    width: 20%;
    height: auto;
    margin: 100px auto 100px auto;
    text-align: center;
    border-radius: 10px;
    padding: 10px;
}
``` 

### Continued development

Definitely still struggled with alignment as a whole and simplifying aspects of CSS to limit repetitiveness - will need to practice more on this to make concepts stick.

### Useful resources

- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS) - Absolutely crucial in the entirety of this challenge as reading the documentation makes a world of difference when struggling with concepts

## Author

- Github - [@calicocoffins](https://github.com/calicocoffins)
- Frontend Mentor - [@calicocoffins](https://www.frontendmentor.io/profile/calicocoffins)
- Twitter - [@calicocoffins](https://www.twitter.com/calicocoffins)