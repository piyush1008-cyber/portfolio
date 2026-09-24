<div align="center">

# 🌐 Peeyoosh Kangle — Developer Portfolio & Interactive Resume

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://piyush1008-cyber.github.io/portfolio/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-blue.svg?style=for-the-badge)](#)

<p align="center">
  <strong>A high-performance, dark-mode, glassmorphic portfolio and interactive resume engineered with vanilla web technologies.</strong>
</p>

<p align="center">
  <a href="https://piyush1008-cyber.github.io/portfolio/"><strong>Explore Live Website »</strong></a>
  •
  <a href="https://piyush1008-cyber.github.io/portfolio/resume.html"><strong>View Interactive Resume »</strong></a>
  •
  <a href="#-key-features">Key Features</a>
  •
  <a href="#-local-development-setup">Run Locally</a>
  •
  <a href="#-contact--connect">Get In Touch</a>
</p>

---

</div>

## 📌 Overview

This repository hosts the official personal portfolio and interactive resume for **Peeyoosh Kangle** — an aspiring **Systems & Infrastructure Software Engineer** and **Data Science & AI/ML Specialist**. 

Built with zero external frameworks or heavy dependencies, the portfolio delivers an ultra-fast, smooth, and visually engaging experience. It showcases technical proficiencies, featured engineering projects (including low-level systems programming, concurrent applications, and predictive ML pipelines), detailed professional experience, and an interactive resume with print-ready A4 formatting.

> [!TIP]
> **Live Deployment:** Experience the live production site hosted on GitHub Pages:  
> 🔗 **[https://piyush1008-cyber.github.io/portfolio/](https://piyush1008-cyber.github.io/portfolio/)**

---

## 📑 Table of Contents

- [📌 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🛠️ Tech Stack \& Architecture](#️-tech-stack--architecture)
- [📂 Repository Structure](#-repository-structure)
- [💻 Local Development Setup](#-local-development-setup)
- [📸 Screenshots \& UI Showcase](#-screenshots--ui-showcase)
- [🎯 Performance \& Engineering Highlights](#-performance--engineering-highlights)
- [📄 License](#-license)
- [📬 Contact \& Connect](#-contact--connect)

---

## ✨ Key Features

### 🌌 1. Interactive HTML5 Canvas Particle Mesh
- Custom physics-based particle network rendered directly to an HTML5 `<canvas>`.
- Responsive auto-resizing canvas listener.
- Dynamic proximity-based node connections with real-time vector distance calculation.
- Interactive mouse hover repellent effect for smooth user engagement.

### ⌨️ 2. Dynamic Typewriter Effect
- Pure vanilla JavaScript typewriter engine cycling through professional titles:
  - *Systems & Infra Engineer*
  - *Data Science Enthusiast*
  - *AI/ML Developer*
  - *Problem Solver*
  - *Automation & Test Engineer*
- Realistic variable typing speeds and pause timings with cursor blinking animation.

### 🎨 3. Cyber Glassmorphism & Modern Dark UI
- High-contrast, dark aesthetic (`#0a0a0f` deep space canvas) designed for technical clarity.
- Frosted glass cards using `backdrop-filter: blur()`, subtle linear borders, and dynamic multi-color radial glows.
- Smooth CSS custom properties (`var(--accent-1)`, `var(--gradient-primary)`) for coherent theme scalability.

### 📱 4. Fully Responsive & Mobile-First Navigation
- Fluid typography and layout scaling across ultra-wide monitors, laptops, tablets, and smartphones.
- Mobile drawer navigation menu with animated hamburger-to-cross transformation toggle.
- Scroll-aware sticky navbar with dynamic background opacity transitions upon scroll offset.

### 📄 5. Standalone Interactive Resume Page (`resume.html`)
- Dedicated, printable web resume formatted strictly to standard A4 proportions.
- Integrated profile toggler for switching domain focus (Systems/Infrastructure vs. Data Science/Analytics).
- High ATS compatibility, clean typographic hierarchy, and quick-print CSS media queries (`@page { size: A4; margin: 0; }`).

### 📊 6. Scroll-Driven Animations & Counter Statistics
- Implemented with native `IntersectionObserver` API for maximum 60fps rendering performance.
- Staggered hero load animations.
- Dynamic odometer-style stat counter animations triggered only when cards scroll into viewport.

### ✉️ 7. Direct Contact Form & Mailto Fallback
- Accessible form validation for Name, Email, and Message.
- Real-time client-side feedback state with automated fallback to the default system mail client.

---

## 🛠️ Tech Stack & Architecture

| Layer | Technology | Description |
| :--- | :--- | :--- |
| **Markup** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Semantic HTML5 structure, SEO OpenGraph tags, and accessible ARIA attributes |
| **Styling** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Modern CSS Grid, Flexbox, custom CSS variables, keyframe animations, and Glassmorphism |
| **Logic** | ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Vanilla ECMAScript (ES6+) for DOM manipulation, Canvas 2D particle simulation, and observers |
| **Typography**| [Inter & JetBrains Mono](https://fonts.google.com/) | Modern sans-serif paired with developer-focused monospace typography |
| **Hosting** | ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=github&logoColor=white) | Continuous static deployment with automated SSL certification |
| **Icons** | SVG Vector System | Inline lightweight SVGs for instant zero-latency icon rendering |

---

## 📂 Repository Structure

```plaintext
portfolio/
├── 📄 index.html          # Main landing page (Hero, About, Skills, Projects, Experience, Contact) [~41 KB]
├── 📄 resume.html         # Interactive, print-ready ATS resume with profile selector [~50 KB]
├── 🎨 style.css           # Complete design system, glassmorphism, responsive breakpoints [~24 KB]
├── ⚡ script.js           # Particle canvas engine, typewriter, scroll observers, contact handler [~9 KB]
└── 📖 README.md           # Repository documentation and recruiter showcase
```

### File Breakdown:
- **`index.html`**: Houses the main single-page application structure. Contains semantic landmarks (`<nav>`, `<section>`, `<footer>`), metadata for search engines and social sharing, inline SVG icons, and content sections.
- **`resume.html`**: Complete standalone curriculum vitae page with dedicated styling for screen display, role-based profile toggles, and A4 print media stylesheets.
- **`style.css`**: Centralized stylesheet utilizing CSS variables for theme palette, responsive grid layouts, card elevations, glowing hover states, and keyframe animations.
- **`script.js`**: Pure JavaScript containing the Canvas particle simulation, dynamic text typewriter, mobile hamburger handler, `IntersectionObserver` scroll listener, and contact form dispatch.

---

## 💻 Local Development Setup

No node modules, build steps, or bundle tools required! You can run this repository locally with any standard web browser or static server.

### Option 1: Quick Start (Direct File)
1. Clone the repository:
   ```bash
   git clone https://github.com/piyush1008-cyber/portfolio.git
   cd portfolio
   ```
2. Double-click `index.html` or open it with your favorite browser:
   ```bash
   # On Windows PowerShell
   Start-Process index.html
   ```

### Option 2: Using VS Code Live Server
1. Open the project folder in **Visual Studio Code**:
   ```bash
   code .
   ```
2. Install the **Live Server** extension (`ritwickdey.LiveServer`).
3. Right-click `index.html` and select **"Open with Live Server"** (or click `Go Live` on the bottom toolbar).
4. Browser opens automatically at `http://127.0.0.1:5500/`.

### Option 3: Python Built-In HTTP Server
```bash
# Python 3.x
python -m http.server 8000

# Open in browser: http://localhost:8000
```

### Option 4: Node.js `npx serve`
```bash
npx serve .
```

---

## 📸 Screenshots & UI Showcase

<div align="center">

| Section | Preview | Description |
| :--- | :---: | :--- |
| **Hero & Particle Canvas** | <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600&auto=format&fit=crop&q=80" width="380" alt="Hero Section Preview" /> | Interactive dark-mode hero featuring glowing particle grid and dynamic typewriter |
| **Projects Showcase** | <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=600&auto=format&fit=crop&q=80" width="380" alt="Projects Showcase Preview" /> | Filterable glassmorphic project cards highlighting systems engineering & AI/ML |
| **Interactive Resume** | <img src="https://images.unsplash.com/photo-1586281380349-632531db7ed4?w=600&auto=format&fit=crop&q=80" width="380" alt="Resume Page Preview" /> | A4-compatible ATS resume layout with dynamic profile switching |

*(Note: Replace preview images with local repository screenshots as needed)*

</div>

---

## 🎯 Performance & Engineering Highlights

- ⚡ **Zero External Framework Overhead:** Pure HTML5, modern CSS, and vanilla JS ensure sub-second First Contentful Paint (FCP).
- 📦 **Extremely Lightweight:** Complete payload (code + styles + logic) is under 130KB uncompressed.
- 🎯 **Hardware-Accelerated Transitions:** Uses CSS `transform` and `opacity` properties to prevent DOM layout thrashing and maintain 60 FPS scrolling.
- ♿ **Accessibility First:** Semantic HTML tags, clear contrast ratios meeting WCAG guidelines, and keyboard navigable links.
- 🖨️ **Print Optimized:** Dedicated CSS `@media print` rules ensure the resume prints cleanly to physical PDF/paper without web chrome clutter.

---

## Featured Engineering Projects Highlighted

1. **[Jarvis-AI Voice Assistant](https://github.com/piyush1008-cyber/jarvis-voice-assistant)**: Multi-threaded local voice assistant running concurrent processes for audio recording, expression tracking, and semantic search via socket loops and local LLM APIs.
2. **[SmartCrop Recommendation Engine](https://github.com/piyush1008-cyber/crop-recommendation)**: Serialized machine learning predictive pipeline with clean data validation checks, pickle model persistence, and automated accuracy threshold testing.
3. **Student App**: Full-stack MVC CRUD system with structured database models, security rules, and comprehensive Postman test suite.
4. **News Daily AI**: Modular Python news parsing pipeline consuming external REST APIs over HTTP with Object-Oriented patterns.
5. **Exploratory Data Analysis**: In-depth exploratory data analysis on real-world datasets using Pandas, NumPy, Matplotlib, and Seaborn.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details. You are free to use, modify, and distribute this portfolio code for personal and commercial projects.

---

## 📬 Contact & Connect

**Peeyoosh Kangle**  
*Aspiring Systems / Infrastructure Software Engineer & Data Science Enthusiast*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Peeyoosh_Kangle-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/peeyoosh-kangle-652694383/)
[![GitHub](https://img.shields.io/badge/GitHub-piyush1008--cyber-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/piyush1008-cyber)
[![Email](https://img.shields.io/badge/Email-piyushkangle%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:piyushkangle@gmail.com)

---

<div align="center">
  <sub>Designed & Built with ❤️ by <a href="https://github.com/piyush1008-cyber">Peeyoosh Kangle</a>. Hosted on GitHub Pages.</sub>
</div>
