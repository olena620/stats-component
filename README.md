# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

While working through this project I gained experience in positioning child elements relative to the parent container. I found the right fonts, connected it, and set the necessary font-size, letter spacing etc. for all text elements. In this project I had a chance to use a display-flex,which allowed me to arrange the items inside the container flexibly and responsively. When working on the desktop version I distributed the elements along the axis x, horisontally and then when I needed tyo adapt the project to the mobile version I applied a column direction to ensure all elements align proportionally and fit within the specified dimentions. I also implemented background image layering combined with gradients to match the desired tint from the layout. To obtain the desirable effect I also used background-blend-mode, a CSS property that determines how an element’s background layer should be blended with its background color or other background layers. 

Below are some featured snippets that represent my best work on this project:

```html
 <ul class="flx">
                <li>
                  <h3>10k+</h3>
                  <p class="lexend-deca">companies</p>
                </li>
                <li>
                  <h3>314</h3>
                  <p class="lexend-deca">templates</p>
                </li>
                <li>
                  <h3>12m+</h3>
                  <p class="lexend-deca">queries</p>
                </li>
              </ul>
```
```css
.decor {
        background-color: #AB5CDB;
        background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)),
            url(../images/bg.png);
        background-blend-mode: multiply;
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover;
        max-width: 540px;
        width: 100%;
        min-height: 446px;
    }
```

### Continued development

 In the future I wopuld like to continue focusing on the adaptive design, because I would like to become more proficient and I want to further refine my ability to optimize content across various screen dimensions and master the strategic use of breakpoints.

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/background-image) - I really like this website! It offers a lot of programming information and provides many explanations with code examples.



## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
