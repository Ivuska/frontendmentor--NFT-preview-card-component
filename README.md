# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Code in GitHub](https://github.com/Ivuska/frontendmentor-NFT-preview-card-component/tree/NFT-component-v1)
- Live Site URL: [Live solution on GitHub pages](https://ivuska.github.io/frontendmentor-NFT-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Pseudo-element
- pseudo-class
- Mobile-first workflow

### What I learned

I tried to use pseudo-elements with pseudo-classes and trained flex-box in which I have almost lost myself.

I also saw some useful videos and learned a lot context about CSS itself. 

#### My Learning notes from this challenge and from community's feedback

**flexbox**
- It does not make much sense to apply flexbox to elements like img, h, p etc. 
- Flexbox does not have margin collapse (so the margins of two flexbox items are added up).
- Flexbox is always used on the nearest child element not on the content of this 
  child element (if I set display: flex on a div, it controls positioning of elements inside 
  this div, but not content of those elements).
- [Kevin Powell- Learn flexbox easy](https://www.youtube.com/watch?v=u044iM9xsWU)

**pseudo-classes**
- I can use pseudo-classes also on any CSS selector (p, .footer, div>h2.test,...).
- Do not hesitate to use HTML elements in selectors !!

**pseudo-elements**
- Pseudo-element always needs property content (it can be empty string).
- I always need to use absolute position on the pseudo element and 
- 'img' is inline element so we need to display it block because it leads to baseline alignment
  of both images.

**best practice and notes**
- Never add 'width' and 'height' properties to the html element, set it in CSS.
- I can put svg elements in the img tag and use src="" for adding the svg to the layout.
- Padding is something like stuffing - it is better to set it on this whole section 
  element, because this automatically limit all the other children elements in this 
  element -> I can set width of all these children elements to 100% and they will never
  overflow.
- Padding is not collapsing, so it means that if two element have 10px padding it will 
  result in 20px padding together on the other hand margin has top and bottom collapsing 
  so if I set margin to 10px on one element and 5px to other element it leads to 10px space.
- Check contrast of the page with DevTools in Chrome.
- Transition works as simple animation.

**feedback from the community**
- For any decorative images, each img tag should have empty alt="" and aria-hidden="true"attributes to 
  make all web assistive technologies such as screen reader ignore those images in alt="Price:", 
  alt="Remaining time:"
- The link should be wrapping the original image and either have Sr-only text, an aria-label or alt text 
  that says where that link takes you.

### Continued development

I got almost totally lost in flexbox so I need to practice, practice and practice. 
Globally I need, plan and I am looking forward to the next frontendmentor challenges :-D 
I also plan to see some videos about some tips and good practices in CSS and HTML itself (I found out that many things can be made 'only' with CSS, without using JS.)

### Useful resources

- [Before and After pseudo elements explained - part one: how they work](https://www.youtube.com/watch?v=zGiirUiWslI)

- [CSS Before and After pseudo elements explained - part two: the content property](https://www.youtube.com/watch?v=xoRbkm8XgfQ)

- [CSS Before and After pseudo elements explained - part three: as design elements](https://www.youtube.com/watch?v=djbtPnNmc0I)

I met with Kevin Powell's video thanks to an recommendation from @pazspera and I found them really great and well understandable.I am well aware that I need a lot of practice but thanks to his videos i think and trust that I understand at least the basics rules of this topic. 

- [Accessibility: Image Alt text best practices](https://help.siteimprove.com/support/solutions/articles/80000863904-accessibility-image-alt-text-best-practices)

- [Main landmark must not be contained in another landmark](https://dequeuniversity.com/rules/axe/3.5/landmark-main-is-top-level)

## Author

- Frontend Mentor - [@Ivuska](https://www.frontendmentor.io/profile/Ivuska) 