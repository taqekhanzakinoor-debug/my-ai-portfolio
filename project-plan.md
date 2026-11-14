# Project Plan – Alauddin Khan Portfolio

## Idea
A one-page personal portfolio that introduces me, my skills and my projects. It is meant to be my first professional web presence as a Computer Science student at COMSATS University Islamabad.

## Problem
My CV is a static document. Recruiters and internship hosts cannot see my work or how I think from it. A portfolio site lets them see my projects, reach me in one click, and see that I can build and ship something.

## Audience
- Internship hosts and recruiters looking at student candidates
- Teachers and classmates who want to see my projects
- Small clients who need a simple website

## Goals
1. A visitor understands who I am and what I study within five seconds.
2. A visitor can open my projects, GitHub and LinkedIn, or email me, in one click.
3. The site works well on a small phone and on a desktop.
4. The site shows my interest in AI and web development through its design, not only its text.

## Sections
1. **Hero** (intro tile, photo, status, clock, theme switch)
2. **About**
3. **Skills and Interests** (plus a "Tools I use" tile)
4. **Projects** (Connect 4 / Board Game Hub, Portfolio Generator, Car Rental Management System, Atlas Astrology)
5. **Contact** (email, GitHub, LinkedIn)
6. **Footer**

## Features
- Navigation bar and tiles linking to each section, with smooth scrolling
- Responsive bento-grid layout
- Dark and light mode, saved in the browser
- Live clock (Pakistan time)
- Playable Connect 4 board in the hero
- Email, GitHub, LinkedIn and live project links

**Not included on purpose:** a login, a blog, or a contact form with a backend. A mailto link keeps the site simple and avoids storing anyone's data.

## Design
- **Style:** dark, glass-style tiles in a bento grid, monospace type, one purple accent color.
- **Colors (dark):** background #0a0a0d, text #f3f3f6, accent #8b84ff.
- **Colors (light):** background #e8e8ed, text #111116, accent #4a41e0.
- **Typography:** JetBrains Mono, with system monospace as a fallback.
- **Accessibility:** visible keyboard focus, alt text on the photo, labeled buttons, reduced-motion support.

## Design inspiration
1. Porteix, a Framer portfolio template with a bento layout: https://porteix.framer.website/ . I studied its structure (a grid of rounded tiles with a photo, status, theme switch, and links to sections). I did not copy its design, logo or images.
2. The Looponics workshop slides (slide 8) on design inspiration and contrast. They reminded me to check text contrast for the accent color.

## Wireframe
Concept designs made in Google Stitch (project: "Alauddin Khan Developer Portfolio"):
- `screenshots/wireframe-desktop.png`: desktop project detail screen for Connect 4
- `screenshots/wireframe-mobile.png`: mobile version of the same screen

These are design concepts used for ideas. Stitch generated example numbers and technical details for the project screen, so the live site only shows facts I have confirmed myself.

## Tools
- Claude (AI assistant) for planning, code and review
- Google Stitch for the wireframe
- VS Code, Git and GitHub
- Vercel for hosting

## Timeline
1. Plan and gather content (CV, photo, links)
2. Generate and review the first version with AI
3. Redesign to the bento layout
4. Test on desktop and mobile
5. Deploy to Vercel and write documentation

## Definition of done
- Every nav link and tile link works.
- No horizontal scrolling on mobile.
- No unresolved console errors.
- Email, GitHub and LinkedIn links open the right places.
- The live URL is public: https://my-ai-portfolio-two.vercel.app/
