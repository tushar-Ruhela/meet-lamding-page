# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshots

#### Desktop 

![Desktop Screenshot](image.png)

#### Tablet 

![Tablet Screenshot](image-1.png)

#### Mobile
![Mobile Screenshot](image-2.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/learning-paths/building-responsive-layouts--z1qCXVqkD/steps/66aa80b2e2150da4c497dbfa/challenge/refactor)
- Live Site URL: [Demo](https://petrihcour.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Tailwind CSS](tailwindcss.com) - CSS Framework

## Author

- Website - [My Portfolio](https://vanessagarcia.netlify.app/)
- Frontend Mentor - [@petrihcour](https://www.frontendmentor.io/profile/petrihcour)
tailwind.config = {
      theme: {
        extend: {
          colors: {
            // Cyan
            "cyan-600": '#4D96A9',
            "cyan-300": "#8FE3F9",
            // Purple
            "purple-600": "#855FB1",
            "purple-300": "#D9B8FF",
            // Slate
            "slate-900": "#28283D",
            "slate-600": "#87879D",
            "slate-300": "#D1D1DF",
            // White
            "white": "#FAFAFA",
          },
          fontFamily: {
            "red-hat-display": ["Red Hat Display", "sans-serif"],
          },
          fontSize: {
            // Text Preset 1
            "6xl": ["64px", {
              lineHeight: "110%",
              fontWeight: "900",
            }],
            // Text Preset 2
            "4xl": ["40px", {
              lineHeight: "110%",
              fontWeight: "900",
            }],
            // Text Preset 4
            "lg": ["18px", {
              lineHeight: "110%",
              fontWeight: "500",
            }],
            // Text Preset 4 and 5
            "base": ["16px"]
          }
        }
      }
    }
  </script>
