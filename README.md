# Studio Website & Component Library

A responsive, accessible web application built using semantic HTML5, CSS3 with Modern Layout techniques (Flexbox & CSS Grid), CSS Variables, and CSS-only interactive components.

---

## 🚀 Live Demo & Repository Links

* **Live Site (GitHub Pages):** [https://ibrahimalla286-del.github.io/lab2-studio-expanded/](https://ibrahimalla286-del.github.io/lab2-studio-expanded/)
* **GitHub Repository:** [https://github.com/ibrahimalla286-del/lab2-studio-expanded](https://github.com/ibrahimalla286-del/lab2-studio-expanded)

---

## ✨ Features & Technical Implementation

1. **Semantic HTML5 Structure:**
   * Uses clear semantic tags (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`) ensuring compliance with W3C validation standards.

2. **Responsive Layouts (Flexbox & Grid Breakpoints):**
   * **Navigation & Header:** Flexible navigation bar built with CSS Flexbox.
   * **Main Grid Layout:** Responsive multi-column layout using CSS Grid:
     * **Mobile:** 1 Column
     * **Tablet:** 2 Columns
     * **Desktop:** 3 Columns

3. **Component Library Expansion (`components.html`):**
   * **Design Tokens:** Displaying CSS Variables for colors (`--primary`, `--bg`, `--text`).
   * **Buttons:** Standard, Hover, and Disabled state styling.
   * **Responsive Table:** Horizontal scroll wrapper with zebra rows and status badges.
   * **Form Elements:** Custom-styled input fields, labels, and select dropdowns.
   * **Alerts & Notifications:** Feedback message boxes for user alerts.
   * **Pure CSS Modal:** Fully functional interactive modal window built using the CSS `:target` pseudo-class (without JavaScript).

4. **Dark Mode Support:**
   * Automatic color theme adaptation based on system preferences using `@media (prefers-color-scheme: dark)` media query and CSS Variables.

5. **Accessibility Optimization:**
   * Optimized contrast ratios, semantic form labels (`for` & `id` pairing), and keyboard navigability achieving **90+ Accessibility Score** on Google Chrome Lighthouse Audit.

---

## 📂 Project Structure

```text
lab2-studio-expanded/
│
├── index.html         # Homepage with hero section & responsive feature cards
├── components.html    # Style guide & component library
├── contact.html       # Contact form page
├── about.html         # Project information section
├── style.css          # Central stylesheet (Variables, Flexbox, Grid, Dark Mode)
└── README.md          # Project documentation
