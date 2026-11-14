# Testing Report

Automated checks run on 14 Nov 2026 with headless Chromium (Playwright) at 1366px and 375px widths, on the bento-grid version. Still to do by me: test on a real phone and in a second browser.

| Check | How tested | Result | Fix |
|---|---|---|---|
| Page loads | Opened index.html at desktop and mobile size | Pass | None |
| Console errors | Listened for console and page errors | Only a Google Fonts request failed, because the test machine had no internet. Fonts fall back to system fonts | Fallback fonts are set in the CSS |
| No horizontal scroll | Compared scrollWidth to viewport at 1366px and 375px | Pass (1366/1366, 375/375) | None |
| Mobile menu | Clicked Menu, then a nav link at 375px | Pass: menu opens, then closes after a link is clicked | None |
| Nav links scroll to sections | Clicked Projects link on mobile | Pass | None |
| Contrast of contact buttons | Viewed screenshot | Buttons looked dim | Removed the opacity applied to the buttons |
| Dark/light toggle | Not yet tested by hand | TODO | |
| Email and GitHub links | Not yet clicked | TODO | |
| Connect 4 live link | Not yet clicked | TODO | |
| Keyboard (Tab) navigation | Not yet tested | TODO | |
