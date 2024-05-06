# Frontend Mentor - Dictionary web app solution

This is a solution to the [Dictionary web app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/dictionary-web-app-h5wwnyuKFL). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Search for words using the input field
- See the Free Dictionary API's response for the searched word
- See a form validation message when trying to submit a blank form
- Play the audio file for a word when it's available
- Switch between serif, sans serif, and monospace fonts
- Switch between light and dark themes
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Have the correct color scheme chosen for them based on their computer preferences.
- **Extra Bonus from me**: The user is able to click on synonym-term to get description for the word.

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [View Code](https://github.com/ortalyarts/frontendmentor-dictionary-web-app)
- Live Site URL: [Preview Site](https://frontendmentor-dictionary-web-app.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- Native CSS
- Vanilla JavaScript ES6
- Mobile-first workflow
- font-size: clamp() - for fluid typography
- Dark / Light Theme switch + prefers-color-scheme + Fallback in JavaScript 
- Aria role listbox + option to add accessibility for selecting font-family & synonyms
- Font-family switch
- Form validation
- Fetch API to search for term in [Free Dictionary API](https://dictionaryapi.dev/)
- Audio() constructor [mdn](https://developer.mozilla.org/en-US/docs/Web/API/HTMLAudioElement/Audio) - to play audio file
- Chrome Screen reader - for accessibility check
- Chrome Lighthouse
- PerfectPixel
 
### Useful resources

- [Free Dictionary API](https://dictionaryapi.dev/)
- [Fluid Typography Tool](https://fluidtypography.com/#app-get-started) - I used it to calculate the font-size on smaller screen, to be fluid.
## Author

- OrtalyARTS Portfolio Website - [@ortalyARTS.com](https://ortaly.com/)
- Frontend Mentor - [@ortalyARTS](https://www.frontendmentor.io/profile/ortalyARTS)
- Linkedin - [@ortalyARTS](www.linkedin.com/in/ortalyarts) 

