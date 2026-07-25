<h1 align="center"> Personal AI Portfolio Website</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Deployed-GitHub_Pages-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square"/>
</p>

<p align="center">
  <a href="https://miranamoh.github.io/portfolio/"><strong> Live Demo → miranamoh.github.io/portfolio</strong></a>
</p>

<img width="1882" height="866" alt="Screenshot 2026-07-25 222930" src="https://github.com/user-attachments/assets/ced3a94e-cff1-4854-86a9-edc7034b7a56" />

---

##  Overview

A personal portfolio website built from scratch using pure HTML, CSS, and JavaScript — no frameworks, no libraries. Designed to present my AI/ML background, technical stack, and featured projects to recruiters and cooperative training committees in a clean, modern, dark-mode interface.

---

##  Live Site

**[https://miranamoh.github.io/portfolio/](https://miranamoh.github.io/portfolio/)**

Hosted via **GitHub Pages** — deployed directly from the `main` branch, no build step required.

---

##  Goals

- Present my AI/ML projects and technical skills professionally
- Build and deploy a real website without relying on templates or site builders
- Practice front-end development (HTML, CSS, JavaScript) 
- Create a shareable link 

---

##  Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 (semantic elements: `<nav>`, `<header>`, `<section>`, `<article>`, `<footer>`) |
| Styling | CSS3 (custom properties, gradients, flexbox, grid, media queries, animations) |
| Interactivity | Vanilla JavaScript (Intersection Observer API, scroll events, smooth navigation) |
| Fonts | Google Fonts — Inter + Poppins |
| Deployment | GitHub Pages |

---

##  Design Decisions

### Color System
A dark-mode-first palette built around three accent colors that reflect the visual language of data science tools:

| Variable | Hex | Role |
|---|---|---|
| `--primary` | `#6366f1` | Main actions, links, active states |
| `--secondary` | `#ec4899` | Section labels, highlights, project badges |
| `--accent` | `#14b8a6` | Technology tags, secondary elements |
| `--background` | `#0f172a` | Base dark background |

### Typography
Two complementary Google Fonts:
- **Poppins** (800 weight) — headings and the logo, for strong visual hierarchy
- **Inter** (300–800) — body text and UI elements, for readability at all sizes

### Layout
- **CSS Grid** for the skills section and project cards
- **Flexbox** for navigation, hero buttons, skill tags, and contact cards
- **Responsive breakpoints** at 768px and 900px for mobile and tablet layouts

### Animations & Interactions
All animations are CSS-based or driven by vanilla JS — no animation libraries:

| Effect | Implementation |
|---|---|
| Hero gradient orb | CSS `@keyframes float` — slow, looping vertical drift |
| Section content reveal | CSS `@keyframes slideUp` with staggered `animation-delay` per card |
| Nav underline on hover | CSS `::after` pseudo-element with `width` transition |
| Skill tags scale on hover | CSS `transform: scale(1.05)` |
| Project cards lift on hover | CSS `transform: translateY(-5px)` + `box-shadow` |
| Hero gradient parallax | JS `scroll` event — translates the orb at 50% scroll speed |
| Active nav link tracking | JS `scroll` event — highlights current section link |
| Smooth page scroll | JS `scrollIntoView({ behavior: 'smooth' })` |

---

##  Project Structure

```
portfolio/
├── index.html    # Full page structure and content
├── style.css     # All styling, design tokens, and animations
├── script.js     # Scroll tracking, parallax, smooth navigation
└── README.md
```

---

##  Page Sections

| Section | Content |
|---|---|
| **Hero** | Name, title, tagline, two CTA buttons |
| **About** | Short bio + three focus domain cards (Time-Series, CV, Deep Learning) |
| **Skills** | Five categorized skill groups with interactive tags |
| **Projects** | Three cards, each split into "The Challenge" and "The Solution" |
| **Contact** | Email and GitHub links |

### Projects Showcased
1. **Saudi Unemployment Rate Forecasting** — SARIMA, Random Forest, Streamlit dashboard
2. **Beauty Salon Database System** — MySQL, 3NF normalized schema, aggregate queries, views
3. **Flower Image Classification** — MobileNetV2 transfer learning, 92% test accuracy


---

*This project was developed for academic purposes and personal branding. All rights reserved.*
