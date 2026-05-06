# Studex– Study Productivity Landing Page

A responsive landing page built as Week 1 Task for my frontend development internship.

---

## Project Overview

Studex is a mock study productivity tool that helps students study smarter using the Pomodoro technique, AI-generated flashcards, and spaced repetition. This project is a fully responsive marketing landing page for the product.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling, layout, and animations |
| Vanilla JavaScript | Mobile menu interactivity |
| Google Fonts | Typography (Syne + DM Sans) |

**No frameworks or libraries were used** — pure HTML, CSS, and JS only.

---

## Features Implemented

- **Responsive design** — works on mobile, tablet, and desktop
- **CSS Flexbox & Grid** — used for navbar, feature cards, testimonial cards, and footer layout
- **Media queries** — breakpoints at 768px (tablet) and 480px (mobile)
- **Hover effects** — on cards, buttons, nav links, and social icons
- **Clickable buttons** — CTA buttons with smooth scroll navigation
- **Mobile hamburger menu** — collapsible nav for small screens
- **CSS animations** — fade-up entrance animations on hero content

---

## Page Sections

1. **Header / Navbar** — Fixed navigation with logo, links, and CTA button. Collapses to hamburger menu on mobile.
2. **Hero Section** — Bold headline, subtext, two action buttons, and key stats strip.
3. **Features Section** — 6-card responsive grid showcasing product capabilities.
4. **Testimonials Section** — 3 student review cards with star ratings and avatars.
5. **CTA Section** — Email capture box with signup prompt.
6. **Footer** — Brand info, navigation links, copyright, and social icons.

---

## Setup Instructions

No installation required. This is a plain HTML project.

**To run locally:**
1. Download or clone this repository
2. Open the `index.html` file in any web browser
3. That's it — no server or build step needed

**To clone via terminal:**
```bash
git clone https://ubahjoy.github.io/Studex-landing-page-/
open index.html
```

---

## Live Demo

🔗 [View Live Site](https://ubahjoy.github.io/Studex-landing-page-/)

## Key Decisions

**1. Chose a study productivity tool as the product**
This felt relevant and relatable. A productivity tool also gave flexibility to showcase multiple feature categories naturally.

**2. Single-file architecture (index.html)**
For a static landing page at this stage, keeping HTML, CSS, and JS in one file keeps things simple, readable, and easy to deploy without a build tool.

**3. CSS custom properties (variables)**
All colours are defined as CSS variables at the top (`--accent`, `--bg`, `--muted` etc.). This makes the design consistent and easy to theme or change later.

**4. Mobile-first responsiveness**
The layout uses CSS Grid with `auto-fit` and `minmax()` so cards reflow naturally without needing many media query overrides. Media queries only handle edge cases like hiding the navbar links and stacking buttons vertically.

**5. No JavaScript frameworks**
Vanilla JS was used only for the mobile menu toggle. This keeps the page lightweight and avoids unnecessary dependencies for a simple static page.

---

## Author

Built by Ubah Joy — Week 1 Frontend Development Internship Task
