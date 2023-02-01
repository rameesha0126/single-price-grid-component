# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Single price grid component solution](#frontend-mentor---single-price-grid-component-solution)
  - [Table of contents](#table-of-contents)
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

### Screenshot

[Mobile View](./../Mobile-view.png)
[Desktop View](./../Desktop-view.png)

### Links

- Solution URL: [Solution](https://github.com/rameesha0126/single-price-grid-component.git)
- Live Site URL: [Live site URL](https://rameesha0126.github.io/)

## My process

Created the mobile view first then using Grid view created the desktop view

### Built with

- Semantic HTML5 markup
- CSS Grid
- Mobile-first workflow

### What I learned

Using CSS Grid view to createmultiple columns that respond to screen width. 

```html
<div class="card-component">
  <section id="part-1">
    <h1>Join our community</h1>
    <h2>30-day, hassle-free money back guarantee</h2>
    <p>Gain access to our full library of tutorials along with expert code reviews. Perfect for any developers who are serious about honing their skills.</p>
  </section>
  <section id="part-2">
    <h1>Monthly Subscription</h1>
    <p><span>&dollar;29</span> per month</p>
    <h2>Full access for less than &dollar;1 a day</h2>
    <button>Sign Up</button>
  </section>
  <section id="part-3">
    <h1>Why Us</h1>
    <p>Tutorials by industry experts <br>
      Peer &amp; expert code review <br>
      Coding exercises <br>
      Access to our GitHub repos <br>
      Community forum <br>
      Flashcard decks <br>
      New videos every week</p>
  </section>
</div>
```
```css
@media only screen and (min-width: 600px) {
    .card-component {
        max-width: 750px;
        display: grid;
        grid-template-columns: 50% 50%;
    }
    
    #part-1 {
        grid-column-start: 1;
        grid-column-end: 3;
        border-radius: 1rem 1rem 0 0;
    }
}

```

### Continued development

Using CSS Grid in a more responsive manner 

### Useful resources

- [W3schools CSS Tutorial](https://www.w3schools.com/css/default.asp)

## Author

- Github - [Rameesha0126](https://github.com/rameesha0126)
- Frontend Mentor - [@rameesha0126](https://www.frontendmentor.io/profile/rameesha0126)
