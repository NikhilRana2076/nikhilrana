# nikhilrana.com.np

Personal portfolio of **Nikhil Rana**, MSc Artificial Intelligence, University of West London.

Live site: https://nikhilrana.com.np/

## Structure
- `index.html`: the whole site (HTML, CSS and JS in one file, with no external libraries)
- `images/travel.jpg`: photo used in the "Beyond the desk" section
- `assets/Nikhil_Rana_CV.pdf`: downloadable CV. Replace this file to update the CV.
- `assets/fonts/`: self-hosted fonts (Inter Tight, Instrument Serif, JetBrains Mono; SIL Open Font License)
- `CNAME`: custom domain for GitHub Pages

## Features
- A "Hi, I'm Nikhil Rana" hero with a wave button (greetings in 10 languages) and a rotating tagline.
- **Background:** the Himalaya as a ridgeline chart. The cursor disturbs it and a click sends a sound wave. It is frame-capped for smooth cursor movement.
- **Role lens:** 8 roles (Responsible AI, ML, Data Science, Data Eng, DB/SQL, Analyst, Finance, Ops) that retailor the page.
- **Research tabs:**
  - Ask the filing (replays real Vodafone, Tesco, Lloyds and Sainsbury's results)
  - Anatomy of an iXBRL tag
  - Fact or fabrication? (7 questions)
  - Results chart
- **FPL captaincy lab:** sliders, radar chart, score and verdict.
- **BSc module explorer**, **relocation radar** and **tools filter**.
- **Explorer badges** (11) saved in localStorage, optional **ambient sound** (Web Audio singing bowl + wind), **quick menu** (Ctrl/⌘ K), **Calm mode** and a hidden sunrise easter egg.

## Private visitor statistics (Umami Cloud)
1. Create a free account at https://cloud.umami.is and add the website `nikhilrana.com.np`.
2. Copy the Website ID and paste it into `window.UMAMI_WEBSITE_ID = ""` near the top of `index.html`.
3. Push. Your dashboard (visitors, page views, visit duration, countries, devices and referrers) is private to your login.

Custom events are already tagged: `cv-download`, `email-copy`, `email-click`, `linkedin`, `github`, `blog`, `project`,
`lens`, `city`, `research-tab`, `bot-ask`, `game-finish`, `quiz-share`, `fpl`, `semester`, `badge`, `sound`, `wave`, `palette-open`, `sunrise` and `contact-form`.
Umami is cookie-free, so no cookie banner is needed.

## Updating the FPL season snapshot
The FPL site blocks other websites from loading its data directly, so the "My FPL season in data" panel is a snapshot. To update it, edit the `PTS` and `RANK` arrays (search for `FPL season charts`), the KPI tiles and the "Snapshot after Gameweek N" line in `index.html`. You can also ask Claude to do it from your `/api/entry/2290455/history/` JSON.
