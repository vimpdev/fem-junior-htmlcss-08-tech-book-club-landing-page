# 🚀 Tech book club landing page

![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-live-2ea44f)

![](./docs/preview-github.png)

The main focus was building a responsive layout, handling interactive states, and organizing CSS using `@layer` and custom properties.

This is a solution to the [Tech book club landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73).

---

## 🔗 Links

- 🌎 [Live site](https://vimpdev.github.io/fem-junior-htmlcss-08-tech-book-club-landing-page/)
<!-- - 📌 [Frontend Mentor solution]() -->

---

## 🎬 Demo

![](./docs/demo.gif)

---

## 📸 Screenshots

| 📱 Mobile | 📲 Tablet |
| --- | --- |
| ![](./docs/mobile-default.avif) | ![](./docs/tablet-defatult.avif) |

| 🖥️ Desktop | 🖱️ Interaction |
| --- | --- |
| ![](./docs/desktop-default.avif) | ![](./docs/desktop-interaction.avif) |

---

## 🧩 Features

- Responsive layout (mobile → desktop)  
- Accessible `hover` and `focus-visible` states  
- Clean and scalable CSS structure  

---

## 🛠️ Built with

- Semantic HTML5
- CSS custom properties (design tokens)
- Flexbox & CSS Grid
- Mobile-first workflow
- CSS `@layer` for structure

---

## 💡 What I learned

- Structuring CSS with `@layer` (base, layout, components, states)  
- Handling `:focus-visible` for better accessibility  
- Creating hover effects with pseudo-elements instead of changing background directly  
- Reducing specificity issues by organizing styles properly  

Example:

```css
.btn::after {
  opacity: 0;
  transition: opacity var(--transition-fast);
}

.btn:is(:hover, :focus-visible)::after {
  opacity: 1;
}
```

---

## 🤖 AI Collaboration

AI was used during development to:

- Reviewing semantic HTML structure
- Debug CSS issues and clarify unexpected behavior
- Better understand selectors like `:is` and `:not`
- Refine small implementation details  

It was mainly helpful for quick feedback and iteration.

---

## 👩‍💻 Author

- Frontend Mentor – [@vimpdev](https://www.frontendmentor.io/profile/vimpdev)

---