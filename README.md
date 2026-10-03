<div align="center">
  <a href="https://www.anannochowdhury.com/">
    <img src="https://capsule-render.vercel.app/api?type=rect&height=150&color=0:0b1020,60:1a1240,100:5a46e0&text=ANANNO%20CHOWDHURY&fontColor=ffc857&fontSize=44&fontAlignY=45&desc=Personal%20Portfolio%20Website&descColor=e8ebf7&descSize=16&descAlignY=72" alt="Ananno Chowdhury Portfolio" width="100%"/>
  </a>

<br/>

<a href="https://github.com/ANANNOCHOWDHURY">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=5A46E0&center=true&vCenter=true&width=640&lines=%24+whoami;Cybersecurity+student+%C2%B7+Dhaka%2C+Bangladesh;Student+today%2C+Defender+tomorrow.">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=FFC857&center=true&vCenter=true&width=640&lines=%24+whoami;Cybersecurity+student+%C2%B7+Dhaka%2C+Bangladesh;Student+today%2C+Defender+tomorrow." alt="$ whoami" />
  </picture>
</a>

<br/>

<img src="https://img.shields.io/badge/status-live-0b1020?style=for-the-badge&labelColor=0b1020&color=5a46e0" alt="status: live"/>
<img src="https://img.shields.io/badge/type-static%20site-0b1020?style=for-the-badge&labelColor=0b1020&color=5a46e0" alt="static site"/>
<img src="https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20JS-0b1020?style=for-the-badge&labelColor=0b1020&color=5a46e0" alt="HTML CSS JS"/>

</div>

<br/>

## `> about`

This is the source code for my personal portfolio site, **[anannochowdhury.com](https://www.anannochowdhury.com/)**. Single-page, plain HTML/CSS/JS, no framework, no build step. Introduces me as a cybersecurity student from Dhaka, Bangladesh, with links to my security practice profiles, education, projects, and contact details.

The page also has a WebGL background (Three.js) with a rotating wireframe globe, floating DNA-style strands, drifting code snippet panels, and a "Matrix"-style letter rain spelling out my name.

> This is my personal site's repo, not a template — kept here mainly for my own reference and version history.

## `> sections`

| Section | What's there |
|---|---|
| `#top` (hero) | Intro tagline and call-to-action buttons |
| `#about` | A short bio |
| `#skills` | Rotating 3D skill tiles (languages, tools, OS) |
| `#security` | Links to TryHackMe, Hack The Box, LetsDefend, KC7, CyberDefenders |
| `#education` | Academic background, from primary school to university |
| `#projects` | Project showcase (placeholders — update with real repos) |
| `#contact` | Email, WhatsApp, LinkedIn, GitHub links |

## `> features`

- 🎨 **Light/dark theme aware** — follows system `prefers-color-scheme`, with a manual theme toggle via `data-theme`
- 🧊 **3D skill cube animation** — custom inline SVG icons on a swaying CSS 3D cube, no external icon library
- 🌌 **Three.js WebGL background** — globe, DNA helixes, floating code panels, and letter-rain, all drawn on `<canvas id="gl">`
- 📱 **Fully responsive** — safe-area insets for notches, mobile-friendly nav and bottom theme switcher
- ♿ **Accessible** — `prefers-reduced-motion` support, focus-visible outlines, semantic sections
- ⚡ **Zero dependencies at build time** — only runtime CDN scripts (Google Fonts, Three.js via cdnjs), no bundler needed

## `> tech stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,threejs&perline=4&theme=dark" alt="Tech stack" />

</div>

- **HTML5** — single-page semantic markup
- **CSS3** — custom properties (CSS variables) for theming, grid/flex layout, no framework
- **Vanilla JavaScript** — IIFEs for the Three.js scene and the skills grid, no build tooling
- **[Three.js r128](https://threejs.org/)** — loaded from cdnjs for the WebGL background
- **Google Fonts** — Bricolage Grotesque (display) and JetBrains Mono (code)

## `> project structure`

```bash
.
├── index.html      # Entire site: markup, inline <style>, inline <script>
└── README.md
```

Everything (HTML, CSS, JS, inline SVG icon defs) lives in a single `index.html` file — there's no separate `/css` or `/js` folder and nothing to compile.

## `> deploy`

Live at **[anannochowdhury.com](https://www.anannochowdhury.com/)**. Single static file, deployed with zero build step.

## `> contact`

<div align="center">

<a href="mailto:mdnowmihayatchowdhuryananno@gmail.com"><img src="https://img.shields.io/badge/Email-8b7bff?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/ananno-chowdhury-6482a3378"><img src="https://img.shields.io/badge/LinkedIn-0b1020?style=for-the-badge&logo=linkedin&logoColor=ffc857" alt="LinkedIn"/></a>
<a href="https://github.com/PK-BIGBOY"><img src="https://img.shields.io/badge/GitHub-0b1020?style=for-the-badge&logo=github&logoColor=ffc857" alt="GitHub"/></a>
<a href="https://www.anannochowdhury.com/"><img src="https://img.shields.io/badge/Portfolio-0b1020?style=for-the-badge&logo=googlechrome&logoColor=ffc857" alt="Portfolio"/></a>

<br/><br/>

```bash
ananno@bigboy:~$ echo "Student today. Defender tomorrow."
Student today. Defender tomorrow.
```

<a href="https://www.anannochowdhury.com/">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=60&color=0:5a46e0,40:1a1240,100:0b1020&section=footer" width="100%" alt="" />
</a>

</div>
