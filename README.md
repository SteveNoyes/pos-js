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
- [License](#license)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Github](https://github.com/SteveNoyes/faqAccordionCard)
- Live Site URL: [Github Pages](https://stevenoyes.github.io/faqAccordionCard/)

## My process

### Built with

- HTML5 
- JavaScript
- CSS
- Mobile-first workflow
- [SCSS](https://blog.logrocket.com/the-definitive-guide-to-scss/)

### Notes

```html
/* (D) RECEIPT */
#posreceipt { display: none; }
```
```css
/* (D) RECEIPT */
#posreceipt { display: none; }
```
```js
 // (C1) GENERATE RECEIPT
  var wrapper = document.getElementById("posreceipt");
  wrapper.innerHTML = "";
  for (let pid in cart.items) {
    let item = document.createElement("div");
    item.innerHTML = `${cart.items[pid]} X ${products.list[pid].name}`;
    wrapper.appendChild(item);
  }
```

### Continued development



### Useful resources

- [w3schools](https://www.w3schools.com/howto/howto_js_accordion.asp) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Reset CSS](https://meyerweb.com/eric/tools/css/reset/) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@SteveNoyes](https://www.frontendmentor.io/profile/SteveNoyes)
- Website - [Portfolio](https://www.stevenmnoyes.com)
- LinkedIn - [Steven Noyes](https://www.linkedin.com/in/steven-noyes/)

## License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
