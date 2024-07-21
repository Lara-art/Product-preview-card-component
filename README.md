# Frontend Mentor - Product preview card component solution

This is my solution to the <a href="https://www.frontendmentor.io/learning-paths/building-responsive-layouts--z1qCXVqkD/steps/669b079685c991733471a1bd/challenge/start"> Product preview card component on Frontend Mentor</a>.<br> Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### 💻 Screenshot

<table>
  <tr>
    <td style="width: 75%;"><img src="https://github.com/Lara-art/Product-preview-card-component/blob/main/screenshot/Desktop.PNG" alt="Vista de Escritorio" style="width: 100%;"/></td>
    <td style="width: 25%;"><img src="https://github.com/Lara-art/Product-preview-card-component/blob/main/screenshot/Mobile.PNG"  alt="Vista Móvil" style="width: 100%;"/></td>
  </tr>
</table>

### 🔗 Links

- Solution URL: [Github](https://github.com/Lara-art/Product-preview-card-component)
- Live Site URL: [Deployed](https://lara-art.github.io/Product-preview-card-component/)

## My process

### 👩‍💻 Built with

- Web font import
- CSS custom properties
- Basic CSS reset
- Base typography settings
- Image styling
- Use of Flexbox
- - Use of Grid
- Mobile-first design


### 📚 What I learned

With this exercise, I learned how to resize the grid in media.


```css
 .grid {
        grid-template-columns: 1fr;
        grid-template-rows: 30vh 50vh; 
        max-height: 800px;
    }


```
Where I had the most trouble was with resizing the image in the @media query because I couldn't get it to be the size I wanted in the grid.

```css
img {
    border-radius: var(--radius-grid) var(--radius-grid) 0 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

```


## ✨ Author

- Github - [Lara](https://github.com/Lara-art)
- Frontend Mentor - [@Lara-art](https://www.frontendmentor.io/profile/Lara-art)

## 📂 Repository

- All the challenges done: [Github](https://github.com/Lara-art/My-Frontend-Mentor-Repository)
