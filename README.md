# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

The challenge was to recreate a profile card with a series of social media links.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Here's a screenshot of a mobile view of my solution](https://github.com/WeatherheadOnline/fem_Social-links-profile/blob/main/project%20screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [weatherheadonline.github.io/fem_Social-links-profile/](https://weatherheadonline.github.io/fem_Social-links-profile/)

## My process

I started by adding some CSS rules based on the design file: variables for colors and spacing, and text preset classes incorporating the specified font and font weights. Then I looked at the design and tried to separate it out into sections. I added HTML containers, with class tags designed to be re-used for any additional user profile cards. Once the HTML was set up, I added basic rules for each section: CSS for background colors and text colors; and text preset classes in HTML text containers. 

Next I started adding more quantitative style rules, using a mobile-first approach and then going back afterwards to add media queries as needed for desktop and tablets. To achieve the desired vertical spacing, I grouped elements into nested flex boxes, gave each element `margin: 0`, and used the flexbox `gap` property to set the vertical spacing between elements.

At that point, the vertical spacing I'd used didn't match up to the visual appearance of the design file, because the design file puts a small vertical margin on all text elements. I added a small margin to the top and bottom of each of my text elements to try to match the design.

Lastly, I added media queries to target desktop screens (using `hover`) and tablet screens (using `min-width` combined with `any-hover: none`). Media queries were used to control the width and padding of the profile card.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to include tablets when designing for responsiveness. In the past I had only differentiated between desktop and smartphone screens; now I know better, and have had some practice at it.

And I learned that text in the Figma design file has a small margin and that the spacing in the final product should be adjusted to account for the extra space.

### Continued development

I would like to continue gaining experience in more sophisticated media queries that respond well on tablet screens in addition to desktop and smartphone screens.

## Author

- Website - [www.weatherheadonline.com](www.WeatherheadOnline.com)
- Frontend Mentor - [@WeatherheadOnline](https://www.frontendmentor.io/profile/WeatherheadOnline)
- LinkedIn - [@eddieweatherhead](https://www.linkedin.com/in/eddieweatherhead/)