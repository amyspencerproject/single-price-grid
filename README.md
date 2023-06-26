# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.jpg)

### Links

- Github Repo URL: [Single Price Grid Repo](https://github.com/amyspencerproject/single-price-grid)
- Live Site URL: [Single Price Grid Page](https://amyspencerproject.github.io/single-price-grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variables
- CSS Flex
- Mobile-first workflow

### What I learned

- Still unsure when to use CSS Grind and when to use Flex. I am have a few resouces bookmarked that come reccomended by other dev folks. I am just going to read or watch a video every time I have to decide and then just experiment. There is not one answer! The point is to just understand both and gain insight into when to use one over the other. Best way to get that insight is by trial and error 😅
- Quote from Adi Purdila Grid + Flex Tutorial "When deciding which tool to use you must decide on the desired behavior."

  "Do you want to let the content shape your layout? _Use Flex_."

  "Or do you want your layout to shape your content? _Use Grid_."

- The layout, the size/spacing of elements are defined by the content in Flex. The larger amount of text in a cell will result in a larger div for that element.
  ![](./flex-layout-screenshot.png)

- With Grid the layout defines where the content is contained. This example is for a three column grid with 1fr each. The shape of the content is defined by the sizing of the grid layout. The content must adapt to the layout.
  ![](./grid-layout-screenshot.png)

- Hayden Pickering responsive grid layout technique. Set `grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr))`. This code says I want as many columns as possible with a minimum width of 20rems. Large viewports will have many columns and smaller viewports will only have one or two columns.

- Decided to go with Flex for this component 😃

### Continued development

### Useful resources

- [CSS Grid vs. Flexbox](https://webdesign.tutsplus.com/articles/flexbox-vs-css-grid-which-should-you-use--cms-30184) - This article was suggested to me by someone from FEM. It has other resources inside of it explaining even more aspects to consider.
- [Grid + Flex Tutorial with Adi Purdila](https://youtu.be/18VLSXfsj94) - This video was very clear and had great examples of using Grid and using Flex.

## Author

- Website - [Amy Spencer](https://spencerproject.com/)
- Frontend Mentor - [@amyspencerproject](https://www.frontendmentor.io/profile/amyspencerproject)
- Linkedin - [amyspencercodes](https://www.linkedin.com/in/amyspencercodes/)
