# Neon Tape Studio — WEB Technologies 1 Midterm Project

Static WEB Technologies 1 midterm website for a fictional indie recording and music production studio in Astana.

---

## 👥 Team Members & Contribution
- **Alikhan Shikhiyev** (IT-2510, 50%): `index.html` (home page & custom CSS mixer console illustration) and `booking.html` (session booking form & guidelines).
- **Abay Amirzhanuly** (IT-2510, 50%): `workflow.html` (5-phase recording roadmap, live signal-chain routing, session accordion) and `equipment.html` (hardware vault table, interactive category filter toolbar, gear package bundles).

---

## 🌐 Pages Overview
1. [`index.html`](index.html) — Home page, studio philosophy, and custom CSS audio mixer console with waveform animation.
2. [`workflow.html`](workflow.html) — 5-phase recording roadmap from voice memo to release-ready master, pro recording checklists, and artist FAQ accordion.
3. [`equipment.html`](equipment.html) — Hardware vault table comparing microphones, audio interfaces, outboard gear, and DAWs with dynamic category filtering and session package bundles.
4. [`booking.html`](booking.html) — Interactive session reservation form with input validation and preparation checklist aside panel.

---

## 🎯 Criteria Checklist Compliance
- **4 Pages for a 2-person team**: Fully satisfied.
- **Shared Navigation**: Consistent sticky translucent navbar on every page.
- **Dark Studio Neon Visual Identity**: Space Grotesk + Inter typography, `#07070B` background, `--cyan: #24F6FF`, `--violet: #9B5CFF`, `--pink: #FF4FD8`.
- **Semantic HTML5**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<table>`, `<form>`, `<footer>`.
- **Bootstrap 5.3 Components**: Grid, navbar collapse, buttons, table styling, and dark accordion.
- **CSS Grid & Flexbox**: CSS Grid powers the mixer console and 5-phase workflow grid; Flexbox powers header, signal chain nodes, and bundle cards.
- **At least one form and one table**: Booking form in `booking.html`; equipment table in `equipment.html`.
- **Multi-Device Responsiveness**: Tested at 375px, 768px, and 1280px without horizontal scroll.

---

## 🚀 Local Run
```bash
python3 -m http.server 8000
# Open http://localhost:8000/friend_midterm/index.html
```
