# Alauddin Khan – Portfolio

A one-page, responsive personal portfolio for Alauddin Khan, a Computer Science student at COMSATS University Islamabad. Built for the Looponics "Build Something With AI" challenge.

**Live website:** https://my-ai-portfolio-two.vercel.app/
**Source code:** https://github.com/taqekhanzakinoor-debug/my-ai-portfolio

## Overview
The site uses a bento-grid layout of glass-style tiles. It introduces me, my skills and interests, and my projects, and it has a playable Connect 4 board in the first screen.

**Sections:** Hero (intro, photo, status), About, Skills and Interests, Projects, Contact, Footer.

**Features**
- Navigation bar and tiles that link to each section, with smooth scrolling
- Responsive layout for mobile and desktop
- Dark and light mode, saved in the browser
- Live clock showing Pakistan time
- Playable Connect 4 mini-game with win detection and a reset button
- Keyboard focus styles and reduced-motion support
- Basic SEO metadata

## Tools used
- Claude (AI assistant) for planning, code generation and review
- HTML, CSS and vanilla JavaScript (no frameworks or build step)
- Google Fonts (JetBrains Mono)
- Git and GitHub for source control
- Vercel for hosting

## Run locally
No install is needed.

1. Download or clone the repo: `git clone https://github.com/taqekhanzakinoor-debug/my-ai-portfolio.git`
2. Open the folder and double-click `index.html` to open it in your browser.

Optional local server (from inside the folder):
```
python -m http.server 8000
```
Then visit http://localhost:8000.

## Project structure
```
my-ai-portfolio/
├── index.html          # the whole website (HTML, CSS, JS)
├── assets/photo.webp    # portrait used in the hero
├── screenshots/        # desktop and mobile screenshots
├── project-plan.md     # idea, audience, goals, design plan
├── prompts.md          # prompts used and their results
├── testing-report.md   # checks performed and fixes
└── README.md
```

## Deployment
Pushing to the `main` branch on GitHub triggers an automatic redeploy on Vercel.

## Contact
- Email: taqekhanzakinoor@gmail.com
- GitHub: https://github.com/taqekhanzakinoor-debug
- LinkedIn: https://www.linkedin.com/in/alauddin-khan-50ba9333a/
