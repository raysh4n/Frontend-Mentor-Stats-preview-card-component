# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
<br>Mobile <br>
![](./mobile%20Screenshot%202025-01-22%20224317.png)


<br>Desktop <br>
![](./desktop%20Screenshot%202025-01-22%20223625.png)


Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [here](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-component-solution-h7f7JEglPW)
- Live Site URL: [here](https://fem-stats-preview-card-raysh3n.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css

/*applied to fix subpixel rendering where thin line appears, only appear in chrome, not firefox*/
    transform:translateZ(0); 
```

::before and ::after can only be applied to tag that has child element.


linear gradient can be combined with background image to create the overlay effect. and for the /, before the /, it is for background position, after the /, it is for background size. 
```css
    background: linear-gradient(var(--clr-soft-violet-s), var(--clr-soft-violet-s)), url('/images/image-header-mobile.jpg') no-repeat / cover;
    background-size: cover;
```




