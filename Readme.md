<div align="center">

<h1>
  <img src="https://readme-typing-svg.demolab.com?font=Bebas+Neue&weight=700&size=48&duration=3000&pause=1000&color=FF2A2A&center=true&vCenter=true&width=600&lines=ROZZ+PORTFOLIO;portfolio-rozz.vercel.app" alt="ROZZ" />
</h1>

<p>
  <a href="https://portfolio-rozz.vercel.app">
    <img src="https://img.shields.io/badge/Live-portfolio--rozz.vercel.app-%23FF2A2A?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Built_With-Zero_Templates-%230a0a0a?style=for-the-badge" />
  &nbsp;
  <img src="https://img.shields.io/badge/License-MIT-%236366F1?style=for-the-badge" />
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

</div>

---

## Overview

Personal developer portfolio for **Roshan S (ROZZ)** — Full Stack Developer and Trainer at Big Bucks Innovation (IIT Delhi IHFC). Built as a production-ready single-file `index.html` with zero frameworks, zero build steps, and zero templates.

Live at → **[portfolio-rozz.vercel.app](https://portfolio-rozz.vercel.app)**

---

## Sections

| # | Section | Description |
|---|---|---|
| 01 | **Hero** | Full-viewport headline, live availability badge, play reel button |
| 02 | **About** | ID badge card, stats, JS code block bio |
| 03 | **Skills** | 4-tier grid — Fluent / Proficient / Learning / AI & APIs |
| 04 | **Projects** | 6 real projects with stacks, status, and live links |
| 05 | **Certifications** | All verified certs, NSS, Rotaract |
| 06 | **Resume** | Preview card + PDF download |
| 07 | **Contact** | Full contact form |

---

## Tech Stack

**No framework. No build tool. No template.**

| Layer | Choice | Why |
|---|---|---|
| Markup | HTML5 | Single-file, zero dependencies |
| Styling | Vanilla CSS (custom properties) | Full control, no class bloat |
| Motion | CSS transitions + IntersectionObserver | No library overhead |
| Fonts | Bebas Neue · DM Sans · JetBrains Mono | Google Fonts CDN |
| Hosting | Vercel | Free, instant CI/CD from GitHub |

---

## Design System

```css
--red:       #ff2a2a   /* Primary accent */
--black:     #0a0a0a   /* Page background */
--off-black: #111111   /* Section alternates */
--charcoal:  #1a1a1a   /* Card backgrounds */
--green:     #10b981   /* Live status / tier dot */

--font-display: 'Bebas Neue'      /* Headlines */
--font-body:    'DM Sans'         /* Paragraphs */
--font-mono:    'JetBrains Mono'  /* Code, labels, tags */
```

---

## Project Structure

```
portfolio-rozz/
├── index.html            # Entire portfolio — all sections, styles, scripts
├── Roshan_S_Resume.pdf   # Linked from the Resume section download button
├── ROZZ.png              # Profile photo (About badge card)
├── reel.mp4              # Intro video (Hero play button)
├── README.md             # This file
└── LICENSE               # MIT
```

---

## Local Setup

No install. No build. Open and done.

```bash
git clone https://github.com/Roshan282005/portfolio-rozz.git
cd portfolio-rozz
# Open index.html in your browser — or use Live Server in VS Code
```

---

## Deploying to Vercel

```bash
# Option 1 — Vercel CLI
npm i -g vercel
vercel

# Option 2 — GitHub Integration
# Push to GitHub → Import repo at vercel.com/new → Deploy
# All subsequent pushes to main auto-deploy
```

---

## Customization Guide

### Swap your photo
In the About section, replace the initials placeholder:
```html
<!-- Find this div -->
<div class="badge-img-inner">RS</div>

<!-- Replace with -->
<img src="ROZZ.png" style="width:100%;height:100%;object-fit:cover;border-radius:12px;" alt="Roshan S" />
```

### Add your intro reel
In the video modal, replace the placeholder with:
```html
<video src="reel.mp4" controls autoplay style="width:100%;border-radius:12px;"></video>
```

### Wire the contact form
Drop-in Formspree (free tier):
```html
<!-- Wrap inputs in a form tag pointing to your Formspree endpoint -->
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Add a new project card
Copy any `.project-card` block and update `proj-num`, `proj-title`, `proj-desc`, `stack-tag` spans, and `proj-status`.

### Add a certification
Copy any `.cert-card` block and update `cert-icon`, `cert-name`, `cert-issuer`, and `cert-year`.

---

## Projects Featured

| Project | Stack | Status |
|---|---|---|
| [Big Bucks Innovation](https://bigbucksinnovation.com) | Next.js 14 · TypeScript · Tailwind · Framer Motion · Vercel | 🟢 Live |
| ARIZE | Next.js · FastAPI · Three.js · Canvas API · Anthropic API | 🔶 Prototype |
| ANNAM | Next.js · Firebase RTDB · Razorpay · Zustand · React Query | 🔶 In Progress |
| TravelGo | PHP · MySQL · Claude API · Google Maps · Azure | ✅ Built |
| AWS URL Shortener | TypeScript · Lambda · DynamoDB · CDK · Jest | ✅ Built |
| n8n Automations @ BBI | n8n · WhatsApp API · Google Calendar · GitHub API | 🟢 Production |

---

## Author

**Roshan S (ROZZ)**
Full Stack Developer · Trainer · Final-year B.Tech IT @ Anna University

<p>
  <a href="https://linkedin.com/in/roshan-s-2ba562332">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/Roshan282005">
    <img src="https://img.shields.io/badge/GitHub-Roshan282005-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:roshan200628@gmail.com">
    <img src="https://img.shields.io/badge/Email-roshan200628%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://portfolio-rozz.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-portfolio--rozz.vercel.app-FF2A2A?style=flat-square&logo=vercel&logoColor=white" />
  </a>
</p>

---

## License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for details.

---

<div align="center">
  <sub>Built with zero templates · Shipped from Chennai 🇮🇳</sub>
</div>