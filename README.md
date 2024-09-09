# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview 👀


This is a product preview page, it has an image of the product and next to it its description, containing:

- Product type
- Product name
- Description
- Price and discount
- Add to cart button


### The challenge 🥇🏆

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

***Time Spent: ~2 hours***

## Preview 📖

### Desktop

![Desktop preview](./src/video/desktop-preview.gif)

### Mobile

![Mobile preview](./src/video/mobile-preview.gif)

### Responsivity

![Responsivity](./src/video/responsivity.gif)

### Links 🚀

- Solution URL: [https://www.frontendmentor.io/solutions/-html5-e-css-5-newbie-product-preview-card-component-QxrJu793kS]
- Live Site URL: [https://ramon-alvez.github.io/Frontend-Mentor-HTML-CSS-Newbie-Product-Preview-Card/]

## My process 💻

### Built with 🔨

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned 🎓

I really liked the fact that you used pseudo classes and elements to style some parts, like the description and the add to cart button.


Here are some code snippets:

```css
.price 
    p:first-child{
        color: var(--Details);
        font-family: var(--ProductTitle);
        font-weight: 700;
        font-size: 40px;
}

.price
    p:last-child{
        margin-left: 15px;
        text-decoration: line-through;
}
```

```css
.button::before{
    content: '';
    display: inline-block;
    width: 15px;
    height: 16px;
    background: url(../images/icon-cart.svg) no-repeat;
    position: relative;
    margin-right: 12px;
}
```

### Continued development 


I intend to continue doing the frontend mentor challenges until I finish them all.

### Useful resources

These links helped me clear up a doubt about pseudo classes and elements.

- [Developer.Mozilla/Pseudo-class](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Pseudo-classe)
- [Developer.Mozilla/Pseudo-elements](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Pseudo-elements)


## Author 

- GitHub - [Ramon Alvez](https://github.com/Ramon-Alvez)
- Frontend Mentor - [@Ramon Alvez](https://www.frontendmentor.io/profile/Ramon-Alvez)
- LinkedIn - [@Ramon Alvez](https://www.linkedin.com/in/ramon-alvez/)
