# Make It Real - NFT preview card component

This is a solution to the NFT preview card component project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- A preview-card is created using HTML and CSS, following the BEM methodology.
- It is made with a responsive design for mobile devices.

### Screenshot

![image](https://github.com/user-attachments/assets/f9a8944e-b2ce-46ac-91e1-db27290817bf)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to effectively use the BEM (Block, Element, Modifier) methodology to structure and organize my CSS code. BEM helps create a clear, maintainable, and scalable structure by breaking down each component into reusable blocks, elements, and modifiers. Here's how the methodology is applied in the following code snippet:

```css
/* BEM Element: card__time */
.card__time {
  color: hsl(215, 51%, 70%);
  font-weight: 400;
  justify-content: center;
}

/* BEM Element: card__creator */
.card__creator {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 10px;
}

hr {
  border-color: #314d71;
}

/* BEM Element: card__creator-avatar */
.card__creator-avatar {
  width: 30px;
  height: 30px;
  border-radius: 50%;
}
```


### Continued development
In future projects, I want to continue focusing on a few key areas:

- Responsive Design: While I have successfully created responsive layouts for mobile devices, I want to refine my understanding of more advanced responsive techniques. This includes improving my knowledge of media queries for different screen sizes and optimizing layouts for tablet and desktop resolutions.
- CSS Grid & Flexbox: I found Flexbox useful for aligning elements, but I want to deepen my understanding of combining Flexbox with CSS Grid for more complex layouts. It will help me become more proficient in creating advanced layouts without relying heavily on custom spacing or positioning.

### Useful resources

- [BEM](https://animaticss.com/articulo/que-es-bem-css/) - This was an excellent resource for learning how to structure CSS classes following the BEM methodology. It helped me understand the naming conventions and how to break down components into Blocks, Elements, and Modifiers.
- [CSS Flexbox Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - his guide helped me better understand Flexbox and how to use it to align elements efficiently. I used it to align content in my card layout, especially for positioning details like the price and time within the .card__details class..


## Acknowledgments

I would like to give a special thanks to the CSS and frontend development community for their invaluable resources and examples. Their tutorials and guides helped me improve my skills in both BEM methodology and responsive design. Additionally, I'd like to acknowledge my peers and mentors who provided feedback and inspiration throughout this project.
