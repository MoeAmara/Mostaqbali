# مستقبلي — Mostaqbaly v3.0

A personal goal tracking and rewards PWA (Progressive Web App) in Arabic.

## Project Structure

```
server.py          — Python HTTP server on port 5000
public/
  index.html       — Full single-page app
  manifest.json    — PWA manifest
  sw.js            — Service worker for offline use
  logo-dark.png    — White logo (for dark mode / splash)
  logo-light.png   — Blue logo (for light mode)
```

## Running

```bash
python server.py
```

Serves on port 5000.

## Features

- **PIN screen** with 4-digit security code
- **Splash screen** with logo (dark/light mode adaptive)
- **Prayer tracking** with location-based prayer times, streak, commit grid
- **Courses** — dynamic, user-adds with milestones and rewards
- **University** — user-defined subjects with midterms, quizzes, section, lab
- **Gym** — attendance calendar with user-set days/week and absence limits
- **Recovery** — track addiction recovery streaks with daily check-in
- **Rewards** — fully custom, emoji picker, condition-based unlock system
- **Settings** — theme toggle, PIN change, notifications, data export
- **PWA** — installable, offline-capable, service worker

## Data Storage

All data stored in `localStorage` under key `mq_v3`. No backend required.

## Theme

- Dark mode: `--bg: #070c18`, gold accent, white logo
- Light mode: `--bg: #f0f3ff`, blue accent, blue logo
