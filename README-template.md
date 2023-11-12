# QR code component solution

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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot
![](./design/desktop-design.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="content">
  <img src="./images/image-qr-code.png" alt="qr image code">
  <h1>
    Improve your front-end skills by building projects
  </h1>
  <p>
  Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
</p>
</div>

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="winfohouse.blogspot.com">Md Hasanur Jaman</a>.
  </div>
```
```css
@keyframes animetion-content {
    0% {
        height: 17em;
        overflow: hidden;
        transform:
            translate(-50%, -50%) scale(3);
    }

    20% {
        height: 17em;
        box-shadow: 0 0 9em #0008;
        overflow: hidden;
        transform:
            translate(-50%, -50%) scale(2.7);
    }

    100% {
        height: 26em;
        box-shadow: 0 0 0.9em #0008;
        overflow: hidden;
        transform:
            translate(-50%, -50%) scale(1);
    }
}

:root {
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(212, 45%, 89%);
    --grayish-blue: hsl(220, 15%, 55%);
    --dark-blue: hsl(218, 44%, 22%);
    --pfont-size: 15px;

    --ani-time: 3s;
}

body {
    background: var(--light-gray);
}


.content {
    width: 17em;
    height: 26em;
    border-radius: 1em;
    padding: 1em;
    box-sizing: border-box;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: var(--white);
    box-shadow: 0 0 0.9em #0008;
    /* animation: animetion-content var(--ani-time); */
}

.content img {
    width: 15rem;
    border-radius: .5em;
    transition:
        position 1s,
        width 1s;
}


h1 {
    text-align: center;
    font-family: outfit-bold;
    font-size: 20px;
}

p {
    text-align: center;
    font-family: outfit-regular;
    font-size: 15px;
}

.attribution {
    display: none;
}
```
```js
const proudOfThisFunc = () => {
  console.log('no needed')
}
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Project Preview](./README.md) - This helped me see how the project is. And I really liked this pattern and will use it going forward.
- [Style-guide](./style-guide.md) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- Website - [MD Hasanur Jaman](https://www.winfohouse.blogspot.com)
- Frontend Mentor - [@hasanur82](https://www.frontendmentor.io/profile/hasanur82)
- Facebook - [@hasanur82](https://www.facebook.com/hasanur82)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

