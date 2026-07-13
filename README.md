# Capy Study 🦫

A cozy study stopwatch and notes app, installable as an iOS home-screen PWA.

## Features

- **Stopwatch** — count-up timer with Start / Pause / Give Up / Save. Pauses automatically when the app is backgrounded, and keeps the screen awake while running.
- **Notes** — quick one-line notes with a date stamp. Entries are permanent (no editing or deleting) so they stay an honest log.
- **Today** — total time studied today plus a session list.
- **Week** — Monday-start bar chart of the week's sessions.
- **Capybara mascot** — a little illustrated companion that breathes while you study and celebrates when you save a session.

All data is stored locally on-device via `localStorage` — nothing is sent anywhere.

## Tech

Single self-contained file: `index.html` (inline CSS + JS, no build step, no framework, no dependencies). `manifest.json` and the two icon PNGs make it installable as a standalone PWA.

## Installing on iPhone

1. Open the deployed URL in Safari.
2. Tap the Share icon → **Add to Home Screen**.

## Running locally

No build step needed — just serve the folder and open it:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in a browser.
