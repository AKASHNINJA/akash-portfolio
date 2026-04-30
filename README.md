# Akash Premkumar — Portfolio

Personal portfolio of **Akash Premkumar**, Implementation Manager at Rippling.  
Live at: [akashninja.github.io/akash-portfolio/project/portfolio.html](https://akashninja.github.io/akash-portfolio/project/portfolio.html)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Tailwind CSS (CDN), custom CSS (liquid-glass, animations) |
| Fonts | Google Fonts — Instrument Serif (headings), Barlow (body) |
| Icons | Inline SVG (no icon library dependency) |
| Interactivity | Vanilla JavaScript — IntersectionObserver scroll reveals, video fade loop |
| Hosting | GitHub Pages |

No build step, no framework, no bundler — single `portfolio.html` file.

---

## Page Map

```
┌─────────────────────────────────────────────┐
│  HERO                                        │
│  Full-viewport looping background video      │
│  Gradient nav bar: Schooling · Work          │
│  Experience · Projects · Contact Me          │
│  GitHub + Email icons (top right)            │
│  "Akash Premkumar" heading                   │
│  Scroll Down indicator (bottom)              │
├─────────────────────────────────────────────┤
│  SCHOOLING                                   │
│  Two cards side by side:                     │
│  • The Hindu Colony Chellammal Vidyalaya     │
│    (2004–2019, CBSE, 10pts, 94.6%, Karate)  │
│  • SSN College of Engineering                │
│    (2019–2023, B.E. EEE)                    │
├─────────────────────────────────────────────┤
│  EXPERIENCE — intro                          │
│  "Three companies. One throughline."         │
├─────────────────────────────────────────────┤
│  EVERSTAGE  (Jan 2023 – Sep 2024)            │
│  Deep navy gradient background               │
│  Role cards: Intern → Solution Specialist    │
│  Brand logo card                             │
├─────────────────────────────────────────────┤
│  CHARGEBEE  (Sep 2024 – Mar 2026)            │
│  Warm coral gradient background              │
│  Role card: Implementation Consultant        │
│  Brand logo card                             │
├─────────────────────────────────────────────┤
│  RIPPLING  (Mar 2026 – Present)              │
│  Deep purple gradient background             │
│  Role card: Implementation Manager (US)      │
│  Brand logo card                             │
├─────────────────────────────────────────────┤
│  PROJECTS                                    │
│  2×2 grid of clickable cards:               │
│  01 RevRec Simulator (link)                  │
│  02 Language Pack Translator (link)          │
│  03 AI-driven Config Automation              │
│  04 Bulk Coupon Uploader (link)              │
├─────────────────────────────────────────────┤
│  SKILLS                                      │
│  "Technical depth. Operator instincts."      │
│  4 skill cards + scrolling marquee           │
│  (SQL · REST APIs · Data Migration · etc.)   │
├─────────────────────────────────────────────┤
│  CONTACT                                     │
│  "Let's build something good."               │
│  Email Me → opens Gmail compose              │
└─────────────────────────────────────────────┘
```

---

## Content Summary

The portfolio covers Akash's full career trajectory across three companies in the SaaS/HR tech space:

- **Everstage** — Started as a Solution Specialist Intern, grew to leading SMB and Enterprise onboardings end-to-end (1 yr 9 mos).
- **Chargebee** — Implementation Consultant on subscription billing and revenue management. Built internal tooling (RevRec Simulator, Language Pack Translator, Bulk Coupon Uploader) that reduced setup time by 35% and manual config effort by 40%.
- **Rippling** — Current role as Implementation Manager on the US Accountant IM pod, delivering HR, Payroll, Benefits and IT platform implementations for US clients.

The **Skills** section reflects an Implementation Manager / Forward Deployed Engineer profile: SQL, REST APIs, Webhooks, Data Migration, Solution Architecture, Postman, Jira, Workflow Automation, Change Management, Python, and more.

---

## Project Structure

```
akash-portfolio/
├── README.md
└── project/
    ├── portfolio.html       # Single-file portfolio
    ├── tweaks-panel.jsx     # Design-time tweaks panel (not used in production)
    └── assets/
        ├── everstage-logo.jpg
        ├── chargebee-logo.png
        ├── rippling-logo.webp
        └── akash.png
```

---

## Security

- No API keys, tokens, or credentials anywhere in the codebase.
- All external links use `rel="noopener"` to prevent tab-napping.
- Email link uses a Gmail compose URL — no server-side form handling required.
