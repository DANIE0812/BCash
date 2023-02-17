# BCash

Frontend Project

## The Project

Recreate Blinkcash website https://my.blinkcash.ng/

## Welcome! 👋

Worked on the QR-code component challenge on Frontend Mentor. This was very existing and my first front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

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

The challenge was to build out a QR code component and get it looking as close to the mobile and desktop design in the starter kit provided.

### Screenshot

![](./images/my_solution-preview.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/qr-code-component-9WAn0C5aOM]
- Live Site URL: [https://danie0812.github.io/QR-code-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

- Using a level-one heading (h1) even though it wasn't a full-page challenge. I  created an h1 element within the main element that was hidden visually but visible and readable by screen readers. The class sr-only hid the content visually.

- Don't skip heading levels; Always start from h1, followed by h2, and so on up to h6 (h1,h2,...,h6). 

- If the image is not a decoration like in the case of this project, it must have an alt attribute. The alt attribute should explain its purpose.

- Instead of using pixels in font-size, used relative units (em or rem). The font-size in absolute units like pixels does not scale with the user's browser settings. This can cause accessibility issues for users who have set their browser to use a larger font size. More about this [here](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/)

Code snippets:

```html
<h1 class="sr-only">QR Card Component</h1>
```
```css
.sr-only:not(:focus):not(:active) {
    clip: rect(0 0 0 0); 
    clip-path: inset(50%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap; 
    width: 1px;
}
```
### Continued development

- Responsive Web Design
- Web accessibility

### Useful resources

- [Resource 1](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) - I learned that if you want to build the most-accessible product possible, you need to use both pixels and ems/rems. It's not an either/or situation. There are circumstances where rems are more accessible, and other circumstances where pixels are more accessible.

- [Resource 2](https://developer.mozilla.org/en-US/docs/Glossary/Screen_reader) - In terms of web accessibility, most user agents provide an accessibility object model and screen readers interact with dedicated accessibility APIs, using various operating system features and employing hooking techniques.

## Author

- GitHub - [@Danie0812](https://github.com/DANIE0812)
- Twitter - [@MrEffiom](https://twitter.com/MrEffiom)

## Acknowledgments

Special thanks to Melvin Aguilar 🧑🏻‍💻 (@MelvinAguilar) on frontend mentor for the corrections and insights.
