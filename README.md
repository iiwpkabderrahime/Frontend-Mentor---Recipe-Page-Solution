# Frontend Mentor - Recipe Page Solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR83yS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.
## Overview

### The challenge

Users should be able to:
- View the optimal layout for the interface depending on their device's screen size.

### Links

- Solution URL: [MyGitHub](https://github.com/iiwpkabderrahime/your-repo-name)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts (Young Serif & Outfit)

### What I learned

During this project, I practiced implementing responsive layouts using CSS Media Queries. I focused on maintaining a clean vertical rhythm and ensuring that the typography remained legible across different screen widths.

One of the key takeaways was managing table layouts on mobile devices:
```css
@media (max-width: 375px) {
    table {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}
