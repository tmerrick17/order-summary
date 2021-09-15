# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements
- See focus states for interactive elements for accessability

### Screenshot

![](/design/Final-Screenshot-Order-Summary-Card.png)

### Links

- Solution URL: [My Solution Page at Frontend Mentor](https://www.frontendmentor.io/solutions/mobile-ready-first-page-using-bem-and-accessibility-in-consideration-L8LKAFviv)
- Live Site URL: [Live Site](https://tmerrick17.github.io/order-summary/)

## My process

With the HTML basic content provided, worked on:
  - assigning CSS class names using the BEM method
  - creating variables in CSS for color schemes
  - adding Google Font provided
  - a quick CSS reset with a couple lines of CSS

Next worked on:
  - built mobile first
  - Adding background image for header in the card
  - Figuring out where to use Flex vs Grid (used both)
  - Worked on media query for desktop

Finally worked on:
  - Hover states, matching the screenshot provided
  - Additionally worked on Focus states for accessability, making them more noticeable.
  - Creating a Table of Contents for my CSS file.
  - Minifying my CSS file.

### Built with

- Semantic HTML5 markup
- CSS custom properties and variables
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

A lot of this was review and putting in the work.  I did learn some interesting bits of CSS like using the focus state effectively and differently then the hover state.  Here is an example.

Using the box-shadow I was able to create an outline around a button that was pleasing to the eye and even more noticeable then just using the hover state for people who have accessability needs.

```CSS sample 
/* * Primary Button Focus Styles */
.card__prim-btn:focus {
	background-color: var(--primary__alt);
	box-shadow: 
		0 0 0 5px #FFF,
		0 0 0 10px var(--primary__alt)
	;
}
```

### Continued development

From this exercise I see multiple cards and using CSS Grid to make them responsive to mobile, tablet, and desktop views would be fun.  

Also making sure my BEM method is sound with having multiple cards to see if there would be any cases where I would need to refine them.

### Useful resources

- [Kevin Powell Youtube Channel](https://www.youtube.com/kepowob) - I watch this guys stuff constantly.  He has one of the best consistent channels mostly concentrating on CSS.  Wonderful resource.
- [DesignCourse Youtube Channel](https://www.youtube.com/user/DesignCourse) - Another great resource with design tips and tricks and more CSS knowledge.

## Author

- Website - [Trevor Merrick](https://trevormerrick.com)
- LinkedIn - [@trevormerrick](https://www.linkedin.com/in/trevormerrick/)
- GitHub - [@tmerrick17](https://github.com/tmerrick17/order-summary-component-main)
- Frontend Mentor - [@tmerrick17](https://www.frontendmentor.io/profile/tmerrick17)
- Twitter - [@tcmerrick](https://www.twitter.com/tcmerrick)


