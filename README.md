# Dhooley Cars — Rent the Road

**Day 8 challenge** of the 30 Days Coding Challenge: a car rental website with **Home**, **Cars**, and **Services** sections, built with plain **HTML, CSS, and JavaScript** — no frameworks, no build step.

---

## Demo / Preview

Open `index.html` in any modern browser. That's it — the site runs fully offline from the local files.

---

## Features

- **Hero section** with headline, live stats ($29+/day · 15 min pickup · 4.9★) and CTAs
- **Deal of the Week card** — Land Cruiser Prado at $59/day (save $11), with countdown note and claim button
- **Fleet of 6 cars** rendered from a JavaScript data array with **category filters** (All / City / SUV / Family–Van)
- **Services grid** — full insurance, airport pickup, driver option, weekly deals
- **How it works** — 3-step process (Choose → Send ID → Drive away)
- **Toast notifications** for Rent / Details / Claim actions
- **Responsive layout** — 3-col → 2-col → 1-col grid, with a mobile hamburger menu
- **Offline-first images** — local photos load first, then upgrade to online (Unsplash) versions when the internet is available, with a `fallback.jpg` safety net
- **Accessibility** — semantic landmarks, `aria-pressed` filter chips, `aria-expanded` menu, visible focus rings, `prefers-reduced-motion` support

## Fleet

| Car | Category | Price / day | Specs |
|---|---|---|---|
| Toyota Vitz | City | $29 | 5 seats · Auto · 1 bag |
| Toyota Corolla | City | $35 | 5 seats · Auto · 2 bags |
| Honda Civic | City | $49 | 5 seats · Auto · 2 bags |
| Toyota RAV4 | SUV | $55 | 5 seats · 4WD · 3 bags |
| Land Cruiser Prado | SUV | $70 (*deal $59*) | 7 seats · 4WD · 4 bags |
| Toyota Hiace | Family / Van | $85 | 14 seats · Manual · 8 bags |

Every rental includes insurance, 200 km/day, and roadside help.

---

## Tech Stack

- **HTML5** — semantic sections, meta tags, accessible markup
- **CSS3** — custom properties (design tokens), CSS Grid, Flexbox, `clamp()` fluid type, sticky blurred nav, media queries
- **JavaScript (vanilla)** — array-driven rendering, event delegation, filter chips, toast system, image fallback logic
- **Google Fonts** — Bricolage Grotesque, Inter Tight, JetBrains Mono

## Project Structure

```
day 8/
├── index.html          # All markup, styles, and scripts (single file)
├── images/             # Local car photos + fallback
│   ├── vitz.jpg
│   ├── corolla.jpg
│   ├── civic.jpg
│   ├── rav4.jpg
│   ├── prado.jpg
│   ├── hiace.jpg
│   └── fallback.jpg
├── day8 challenge.docx # Challenge brief
└── README.md
```

## Getting Started

```bash
# 1. Clone or download the repository
git clone <your-repo-url>

# 2. Open the page (double-click index.html, or serve it)
# Option A — just open it
start index.html

# Option B — serve with a local server (VS Code Live Server, Python, etc.)
python -m http.server 8000
# then visit http://localhost:8000
```

No dependencies to install, no build to run.

## Design Tokens

| Token | Value | Use |
|---|---|---|
| `--asphalt` | `#0E1A2B` | Dark surfaces, buttons |
| `--sand` | `#E8D9B8` | Accent text on dark |
| `--copper` | `#C67A2B` | Primary accent / CTAs |
| `--paper` | `#F6F4EE` | Page background |
| `--steel` | `#4A6A8A` | Secondary UI |
| `--radius` | `18px` | Card corner radius |

---

## Challenge Requirements Checklist

- [x] Car rental website with **Home**, **Cars**, **Services**
- [x] Built with HTML, CSS, and JavaScript
- [x] Clean, attractive, well-organized design
- [x] Fully responsive

## Author

Part of the **30 Days Coding Challenge** — Day 8.

## License

Free to use for learning purposes.
