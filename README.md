# Personal Portfolio Website



A sleek, dark-themed personal portfolio built with pure HTML, CSS, and Vanilla JavaScript — no frameworks. It features a cinematic 3D intro animation, smooth scroll-triggered reveals, sticky stacking project cards, and a 3D carousel achievements slider.

**Live Demo:** https://nityaa20.github.io/Portfolio/



## ✨ Highlights

| Feature | Description |
|---|---|
| 🎬 3D Intro Animation | Tumbling "N" logo drawn with SVG stroke animations, particle canvas background |
| 📜 Sticky Scroll Projects | Each project card stacks and pins to the viewport as you scroll |
| 🃏 Flip Skill Cards | 3D flip-on-hover cards revealing tech details on the back |
| 🎠 Achievements Carousel | 3D perspective carousel with left/right navigation |
| 🌊 Wave Text Effect | CSS clip-path water-wave animation on the hero name |
| 🔭 Scroll Reveal | IntersectionObserver-powered fade + slide animations throughout |
| 📱 Fully Responsive | Mobile nav bar, reflow layouts, and touch-friendly interactions |
| ✨ Particle Background | tsParticles integration on the main portfolio view |

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Complete single-file portfolio
└── images/
    ├── prf1.jpeg       # Profile photo
    ├── sslc.jpeg       # SSLC school photo
    ├── hsc.jpeg        # HSC school photo
    ├── ug.jpeg         # College photo
    ├── neuro.jpeg      # Neuro Disease Detection project
    ├── green.png       # Green Plate project
    ├── customer.jpg    # Customer Churn project
    ├── carbon.jpg      # Carbon Tracking project
    ├── credit_card.png # Credit Card Fraud Detection project
    ├── spam.jpg        # SMS Spam Detection project
    └── hospital.jpg    # Hospital Appointment System project
```



## 🚀 Getting Started

No build tools or dependencies to install. Just clone and open.

```bash
git clone https://github.com/Nityaa20/portfolio.git
cd portfolio
```

Then open `index.html` in any browser.

> **Tip:** Use a local server (e.g. VS Code Live Server) to avoid image path issues.



## 🗂️ Sections

### 🎬 Intro Screen
- Animated SVG "N" logo with stroke-dashoffset draw effect
- Canvas particle animation
- Auto-transitions to portfolio after 5.5s, or on any click

### 👩‍💻 About
- Wave fill animation on the hero name
- Word-by-word paragraph reveal on scroll
- Circular profile photo with hover glow

### 🎓 Education
- Vertical timeline with alternating left/right layout
- Each entry slides in from opposite sides on scroll

### 🛠️ Skills
- 5 flip cards: Languages, Frontend, Backend, Concepts, Soft Skills
- Odd cards slide from the left, even from the right on scroll
- Back face reveals skill list on hover

### 💼 Projects (7 total)
Each project uses a sticky scroll frame so cards stack as you scroll:

1. **Neuro Disease Detection** — ML + Python/Tkinter wearable interface
2. **Green Plate Website** — Eco-friendly food delivery site (HTML/CSS/JS + Python)
3. **Customer Churn Prediction** — ML-based retention analytics
4. **Smart Carbon Tracking** — Interactive emissions calculator with charts
5. **Credit Card Fraud Detection** — ML transaction security framework
6. **SMS Spam Detection** — NLP-based classifier with dataset visualizations
7. **Hospital Appointment System** — OOP desktop GUI with Python/Tkinter + MySQL

### 🏆 Achievements
3D perspective carousel featuring:
- SIH'25 Hackathon (Waitlisted)
- Research paper on neurodegenerative disease detection
- AI-ML Internship at TANSAM, Chennai
- Design & Content Lead — College Eco Club
- LeetCode & inter-college coding competitions
- Microsoft/LinkedIn, TCS ION, and Tata GenAI certifications
- Workshops on LLMs, Deep Learning, and Emerging Technologies

### 📬 Contact
- Email, Phone, LinkedIn, and GitHub icon links in the footer



## 🎨 Design System

| Token | Value |
|---|---|
| Primary text | `#ffffff` |
| Accent colour | `#ffb6c1` (soft pink) |
| Background | `#000000` |
| Card background | `#0d0d0d` |
| Border | `rgba(255,255,255,0.15)` |
| Font | Poppins (Google Fonts) |
| Icons | Font Awesome 6.5.1 |



## 📦 External Libraries

All loaded via CDN — no installation needed.

| Library | Purpose |
|---|---|
| [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins) | Typography |
| [Font Awesome 6.5.1](https://fontawesome.com) | Icons throughout |
| [tsParticles 2.12.0](https://particles.js.org) | Background particle effect |



## 📱 Responsive Behaviour

| Breakpoint | Layout |
|---|---|
| Desktop (> 768px) | Side vertical nav, two-column About, alternating timeline |
| Mobile (≤ 768px) | Top horizontal nav bar, single-column About, stacked timeline, project cards reflow vertically |



## 🤝 Connect

- 💼 [LinkedIn](https://linkedin.com/in/nityaa-suresh20/)
- 🐙 [GitHub](https://github.com/Nityaa20)
- 📧 nityaasuresh2005@gmail.com

---

<div align="center">
  Made with 🌸 by <strong>Nityaa S</strong>
</div>
