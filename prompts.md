# Prompts Used

These are the prompts I used with Claude while building this portfolio, what each one produced, and what I learned. Prompts are lightly cleaned up for spelling.

## Prompt 1: Start from the challenge brief
**Prompt:** I attached the Looponics challenge PDF and the workshop slides, and wrote: "I want to make my portfolio according to this."

**Result:** Claude read both files and summarized the requirements, then produced a first one-page site (hero, About, Skills, Projects, Contact, footer) plus starter `project-plan.md`, `prompts.md`, `testing-report.md` and `README.md`. Because I had not given personal details yet, it used clearly marked placeholders.

**What I learned:** Attaching the brief gave the AI the rubric and required features, so the first version already matched them. A prompt with no personal facts led to placeholders, which was safer than invented content.

## Prompt 2: Personalize it from my CV
**Prompt:** I attached my CV and wrote: "This is my CV, make according to this." After that I sent my four projects, my interests, and my GitHub and Connect 4 links.

**Result:** Claude filled in my name, education, skills and contact details. It left my home address and phone number off the public page and pointed out that my CV named two different universities. It also fixed typos such as "Phyton".

**What I learned:** AI will fill gaps if you let it, so I had to check each fact. The university mismatch showed why I must review everything it writes about me. I corrected my location and university in a later prompt.

## Prompt 3: Redesign from a reference screenshot
**Prompt:** I attached a screenshot of a bento-style portfolio and wrote: "I want to make it like this."

**Result:** Claude rebuilt the page as a bento grid of frosted tiles with a status tile, theme switch, clock and section links. Instead of copying the photo tile, it placed my playable Connect 4 board in the hero so the design shows my work.

**What I learned:** A visual reference communicates layout much better than words. I also learned to take structure and ideas from a reference without copying its assets.

## Prompt 4: Raise the quality
**Prompt:** "I have to make it more perfect and awesome."

**Result:** Claude added one standout feature, the Connect 4 board that drops discs on load and can be played, with win detection, a reset button, keyboard-accessible columns and a reduced-motion option. It also tested the page in a headless browser.

**What I learned:** "Make it awesome" is vague. The result was better when the AI chose one clear idea tied to my project instead of adding many effects. A sharper prompt would name the feeling and the one thing to improve.

## Prompt 5: Add my photo and update my details
**Prompt:** I attached a portrait, then a transparent-background version, and asked to add it. Later I asked to add my LinkedIn, rewrite the About section professionally, and change my location to Islamabad and my study to Computer Science at COMSATS.

**Result:** Claude cropped and compressed the photo (84 KB, then about 70 KB as WebP), placed the cutout on a gradient backdrop, added alt text, added LinkedIn to the intro and contact sections, and rewrote the About text.

**What I learned:** Image size and format affect speed, and a transparent PNG needs a backdrop to look good. When I said both "Software Engineering" and "Computer Science", the AI used one and told me about the conflict, so I should be consistent in my instructions.

## Prompt 6: Design concepts in Google Stitch
**Prompt:** In Stitch I asked for a desktop version of my developer portfolio, then asked it to "generate the project detail modal or screen for Connect 4", and later for a mobile version. (Add your first Stitch prompt here if it was different.)

**Result:** Stitch produced a dark, developer-style project detail screen for Connect 4, with a project header, stat cards, a game board, a code panel and an architecture section. It also suggested next screens for my other projects.

**What I learned:** Stitch is quick for exploring layouts. However, it invented technical details and numbers about my project, such as performance figures, that I never gave it. I used the designs for visual ideas only, and I will not publish any claim I cannot back up.

## A stronger version of my prompts
Using the workshop's prompt formula, a better first prompt would have been:

> **Role:** You are a front-end developer. **Goal:** build a one-page portfolio for a CS student. **Audience:** internship recruiters. **Content:** my CV (attached) and four projects. **Style:** dark bento-grid tiles, monospace type, one accent color. **Behavior:** responsive, dark/light mode, working nav. **Rules:** no invented facts, no personal address on the page. **Check:** list anything you were unsure about.

**Takeaway:** My early prompts were short and worked because I iterated. Giving role, goal, audience, style, rules and a final check from the start would have saved several rounds.
