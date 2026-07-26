# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Through this project, I deepened my understanding of several core CSS concepts and practices:

1. **Centering elements with Flexbox**  
   I learned how to use `display: flex;` on the parent container (`body`) alongside `justify-content: center` and `align-items: center` to center the content perfectly on the screen.

2. **Image paths and troubleshooting errors**  
   Resolving a `net::ERR_FILE_NOT_FOUND` error helped me understand relative file paths (`./images/`) and directory structures better.

3. **Importing Google Fonts (`Outfit`)**  
   I practiced importing custom web fonts  and setting specific `font-weight` values (400 / 700).

4. **Border radius and layout styling**  
   I learned how to round corners with `border-radius` 

```HTML
      <img 
        class="image"
        src="./images/image-qr-code.png"
        alt="QRコード">
```

```css
@font-face {
    font-family: "Outfit";
    src:url(Outfit-VariableFont_wght.ttf) format("TrueType")

.box{
    display: flex;
    flex-direction: column;
    background-color: white;
    width: 300px;
    height: 500px;
    align-items: center;
    border-radius: 15px;
}
```

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)?
- How did you use them (e.g., debugging, generating boilerplate, brainstorming solutions)?
- What worked well? What didn't?

**Note: Delete this note and the content above if you didn't use AI, or replace with your own experience.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
