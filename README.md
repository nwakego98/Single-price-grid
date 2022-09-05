# Single-price-grid
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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Solution URL: 
- Live Site URL:

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
   @media only screen and (min-width: 768px){
        .wrap{
          max-width: 700px;
          grid-template-columns: 50% 50%;
          grid-template-rows: repeat(2, auto);
        }
        .cardone{
          grid-column: 1 / 3;
          grid-row: 1 / 2;
          padding: 1.875rem 2.5rem;
        }
        .cardone h2{
          font-size: 1.125rem;
        }
        .cardone p{
          width: 95%;
          font-size: 1.0625rem;
        }
      
        .cardtwo{
          grid-column: 1 / 2;
          grid-row: 2 / 3;
          border-bottom-left-radius: .3125rem;
          padding: 1.875rem 2.5rem;
        }
        .cardthree{
          grid-column: 2 / 3;
          grid-row: 2 / 3;
          border-bottom-left-radius: 0rem;
          padding: 1.875rem 2.5rem;
        }
      }

      @keyframes fadeRight {
        from{
          opacity: 0;
          transform: translateX(10rem);
        }
        to{
          opacity: 1;
          transform: translateX(0);
        }
      }
      
      @keyframes fadeLeft {
        from{
          opacity: 0;
          transform: translateX(-10rem);
        }
        to{
          opacity: 1;
          transform: translateX(0);
        }
      }

      @keyframes fadeTop {
        from{
          opacity: 0;
          transform: translateY(-10rem);
        }
        to{
          opacity: 1;
          transform: translateY(0);
        }
      }

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.
majorly CSS




## Author
Website -(https://app.netlify.com/teams/nwakego98)
Frontend Mentor - (https://www.frontendmentor.io/profile/nwakego98)
Twitter - (https://www.twitter.com/GlowRee17?t=wvddWNyWznpHL13CvpRMyg&s=08)

