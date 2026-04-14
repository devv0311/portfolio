# 🖥️ Dev Choudhary — Portfolio

**Personal frontend developer portfolio. No templates, no frameworks — built from scratch.**

Live demo → [portfolio-devch.netlify.app](https://portfolio-devch.netlify.app)

---

## Overview

A single-page portfolio site built to present my work, skills, and contact info to potential employers and clients. Dark editorial aesthetic with warm amber accents. Every section is hand-coded in HTML, CSS, and vanilla JavaScript.

---

## Sections

| Section | Description |
|---|---|
| **Navbar** | Sticky header with smooth-scroll links, active state on scroll, and GitHub link |
| **Hero** | Name, role, one-liner positioning statement, and dual CTAs (View Work / Let's Talk) |
| **About** | Personal intro with stat counters — 3 projects live, BCA 2nd year, 2+ years coding |
| **Projects** | Cards for Noir & Brew, FlowBill, and this portfolio — each with live demo link, tech tags, and feature highlights |
| **Skills** | 6-card grid covering HTML5, CSS3, JavaScript, Deployment, Git & GitHub, and Responsive Design |
| **Contact** | Email, location, GitHub, availability status, and a working Formspree contact form |

---

## Features

- Sticky navbar with active section highlighting on scroll
- Scroll reveal animations using `IntersectionObserver`
- Async contact form via Formspree — success state shown without page reload
- Fully mobile-responsive layout
- No frameworks, no libraries, no build tools

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic single-page structure |
| CSS3 | Dark theme, CSS variables, Flexbox/Grid, keyframe animations |
| Vanilla JavaScript | Scroll reveal, active nav, async form submission |
| Formspree | Contact form backend |
| Netlify | Static site deployment |

---

## Project Structure

```
portfolio/
├── index.html
├── style.css
└── script.js
```

---

## Design Decisions

- **Dark editorial theme** — warm amber accent on dark background, influenced by magazine/editorial layouts
- **Stats in the About section** — gives recruiters quick scannable proof points
- **Feature checkmarks on project cards** — mirrors how SaaS landing pages present value; makes the project descriptions easier to skim
- **"Available Now" status badge** — signals to recruiters immediately that I'm open to work

---

## Getting Started

```bash
git clone https://github.com/devv0311/portfolio.git
```

No dependencies, no build step — open `index.html` in a browser.

> **Note:** To enable the contact form, replace `YOUR_FORM_ID` in `index.html` with your actual Formspree form ID.

---

## Author

**Dev Choudhary** — [github.com/devv0311](https://github.com/devv0311) · devx2738@gmail.com
