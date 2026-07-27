# PRODIGY_WD_01 — Responsive Landing Page with Interactive Navigation

A fully responsive landing page built as **Task 1** of the Prodigy InfoTech Web Development Internship. The project features a fixed navigation bar that changes style on scroll, smooth hover interactions, and a fully accessible mobile hamburger menu — built entirely with vanilla HTML, CSS, and JavaScript (no frameworks or libraries).

**🔗 Live Demo:** [https://mhamadaub.github.io/PRODIGY_WD_01/](https://mhamadaub.github.io/PRODIGY_WD_01/)

---

## 📋 Features

- **Fixed navigation bar** that stays visible while scrolling
- **Scroll-triggered style change** — navbar transitions from transparent to a solid background with shadow after scrolling past a threshold
- **Animated hover effects** on navigation links (underline reveal on hover)
- **Fully responsive layout** using Flexbox and CSS Grid, with fluid typography via `clamp()`
- **Accessible mobile hamburger menu** — animates into an "X" icon, slides in an off-canvas menu, and updates `aria-expanded` for screen readers
- **Smooth scrolling** to in-page sections via anchor links
- Clean, semantic HTML5 structure (`header`, `main`, `section`, `footer`)

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup
- **CSS3** — Flexbox, Grid, custom properties (variables), media queries, transitions
- **JavaScript (ES6+)** — DOM manipulation, event listeners, no external libraries or frameworks

---

## 📁 Project Structure

```
PRODIGY_WD_01/
│── index.html
│── README.md
│
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
```

---

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/MhamadAub/PRODIGY_WD_01.git
   ```
2. Open the project folder in VS Code.
3. Install the **Live Server** extension (if not already installed).
4. Right-click `index.html` → **"Open with Live Server"**.

No build tools, dependencies, or package managers required — this is a pure static site.

---

## 🎯 What I Learned

Building this project reinforced several core front-end concepts:

- How `position: fixed` removes an element from document flow, and how to compensate for the resulting content overlap using padding.
- The difference between toggling classes via JavaScript (for state/logic) versus defining the actual visual states in CSS (separation of concerns).
- How CSS specificity and the cascade can cause unintended side effects — for example, a generic base style unexpectedly affecting a section that needed different behavior (solved by scoping full-width vs. constrained-width styles to inner content wrappers).
- Building an accessible mobile navigation menu using semantic `<button>` elements, `aria-label`, and `aria-expanded`, rather than relying on non-semantic clickable `<div>`s.
- Writing focused, conventional Git commits (`feat:`, `fix:`, `style:`, `chore:`) to keep a clean, readable project history.

---

## 👤 Author

**Mhamad El Ayoubi**
- GitHub: [@MhamadAub](https://github.com/MhamadAub)
- LinkedIn: [mhamad-el-ayoubi](https://www.linkedin.com/in/mhamad-el-ayoubi-253158360/)

---

## 📄 Part of

This project was built for the **Prodigy InfoTech Web Development Internship** — Task 1.