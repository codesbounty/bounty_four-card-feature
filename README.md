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
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview
Four Card Feature Section
A responsive feature showcase component built with HTML, CSS Grid, and Flexbox. Features a unique hub-style desktop layout that transforms into a clean mobile stack.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./four-card-feature.png)

### Links

- Solution URL:()
- Live Site URL:()

## Features 
-Responsive Design: Mobile-first approach with desktop enhancements
-CSS Grid Mastery: Complex 2D positioning on desktop
-Flexible Layout: Smooth transition from flex to grid
-Modern Styling: Color-coded borders and custom icons
-Accessible: Semantic HTML and proper contrast ratios
-Performance: Lightweight CSS with efficient layouts

### Built with
-HTML5:Semantic markup structure 
-CSS3:Modern layout techniques
-Flexbox(Mobile)
-CSS Grid(Desktop)
-Custom properties
-Media Queries
-Google fonts:inter font family 
-Mobile-first workflow

### What I learned
Key CSS Techniques i am proud of:
-Responsive Layout Transformatrfion
/* Mobile: Simple flex stack */
.cards-grid {
    display: flex;
    flex-direction: column;
}

/* Desktop: Complex grid positioning */
@media (min-width: 768px) {
    .cards-grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(4, 1fr);
    }
    
    .card.supervisor {
        grid-column: 1;
        grid-row: 2 / 4;  /* Spans 2 rows */
    }
}
-Flexible Card Content 
.card-content {
    display: flex;
    flex-direction: column;
    height: 100%;  /* Essential for consistent card heights */
}
If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development
I want to study grid positioning more in order to understand complex layouts





## Author

- Website - [Ofe Bounty Uko](https://portfolio-by-bounty.vercel.app)
- Frontend Mentor - [@ ofe Bounty Uko ](https://www.frontendmentor.io/profile/Ofe Bounty Uko)
- Twitter - [@3EDesigner](https://www.twitter.com/3EDesigner)


