# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size (mobile and desktop)
- See the 3-column grid layout for the cards on larger screens

### Screenshot

![Screenshot img](/images/screenshot.png)

### Links

- Solution URL: [https://github.com/Segarur21/Four-card-feature-section-master](https://github.com/Segarur21/Four-card-feature-section-master)
- Live Site URL: [https://segarur21.github.io/Four-card-feature-section-master/](https://segarur21.github.io/Four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Logical Properties 
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project, I focused on building a layout using **CSS Grid** and `grid-template-areas`. My primary learning objective was structuring the layout so that on desktop screens, the first and last cards are vertically centered relative to the two middle ones, while also achieving optical vertical alignment across the main container using `padding-block-end`.

Here is a snippet of the desktop grid structure:

```css
@media (min-width: 76.8rem) {
  .cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-areas:
      "supervisor team       calculator"
      "supervisor karma      calculator";
    gap: 2rem;
  }

  .card-supervisor { grid-area: supervisor; align-self: center; }
  .card-team       { grid-area: team; }
  .card-karma      { grid-area: karma; }
  .card-calculator { grid-area: calculator; align-self: center; }
}
```
### Continued development

In future projects, I want to keep focusing on:

- Mastering advanced CSS Grid techniques for responsive layouts.

### Useful resources


### AI Collaboration

I used artificial intelligence as an assistant throughout the development of this project. Through various prompts and queries, I relied on AI to answer technical questions, structure the code, and—most importantly—generate and integrate all the animations from scratch. Since CSS animation is a topic I haven't mastered yet, I delegated the technical implementation entirely to AI simply to add that extra layer of dynamism and interactivity to the site.

## Author

- Frontend Mentor - [@Segarur21](https://www.frontendmentor.io/profile/Segarur21)
- GitHub - [@Segarur21](https://github.com/Segarur21)

## Acknowledgments

Thanks to the Frontend Mentor community for providing practical challenges that help developers hone their real-world layout skills step by step.