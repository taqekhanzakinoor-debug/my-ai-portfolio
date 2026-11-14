# Testing Report

**Site:** https://my-ai-portfolio-two.vercel.app/
**Tested:** 14 Nov 2026. Automated checks used headless Chromium (Playwright) on the local files at 1366px (desktop) and 375px (mobile). Manual checks are listed separately below.

## Automated checks

| Check | How tested | Result |
|---|---|---|
| Page loads | Opened `index.html` at desktop and mobile sizes | Pass |
| Console errors | Listened for console and page errors | Only a Google Fonts request failed, because the test machine had no internet. The CSS has monospace fallback fonts. No script errors |
| No horizontal scrolling | Compared page scroll width with viewport width | Pass: 1366/1366 and 375/375 |
| Nav links scroll to sections | Clicked the Projects link | Pass: page scrolled to the Projects section |
| Dark/light switch | Clicked the switch and read the theme value | Pass: theme changed to light |
| Connect 4 board accepts input | Clicked a column | Pass: no errors |
| Photo loads | Checked the image's natural width | Pass: 900px wide |
| Layout on mobile | Reviewed a 375px screenshot | Tiles stack in one column; text readable |

## Manual checks (to confirm on the live site)

| Check | Status |
|---|---|
| Open the live URL on a real phone | Not yet recorded |
| Email button opens the mail app | Not yet recorded |
| GitHub, LinkedIn and "Play it live" links open the right pages | Not yet recorded |
| Play a full Connect 4 game to a win | Not yet recorded |
| Keyboard navigation (Tab through the page) | Not yet recorded |
| Test in a second browser | Not yet recorded |

## Issues found and fixed

| # | Issue | Fix |
|---|---|---|
| 1 | The Email and GitHub buttons in the Contact section looked dim | Removed the transparency that was applied to the buttons |
| 2 | White Connect 4 discs were hard to tell from empty cells | Changed the empty cells to a darker shade so discs stand out |
| 3 | The main headline wrapped onto too many lines beside the board | Reduced the headline size and rebalanced the layout |
| 4 | The first redesign left an empty gap in the intro tile | Moved the Connect 4 board into the gap |
| 5 | `git push` was rejected because the GitHub repo already had a commit | Ran `git pull origin main --allow-unrelated-histories`, then pushed |
| 6 | Typing `it push` instead of `git push` ran a PowerShell testing command | Re-ran the command as `git push` |
| 7 | Photo changed format when the transparent version was added | Replaced `photo.jpg` with `photo.webp` and updated the README |

## Notes
- The site uses no API keys, passwords or tokens.
- All images are my own or created for this project, and the layout was inspired by, not copied from, a public template.
