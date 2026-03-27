# Alarm-clock
A full alarm clock app., a self-contained HTML file with rich UI, a Python script for Windows users, a preview image generator, and an index.html with Open Graph tags for Facebook sharing.

# ⏰ Khairandaish — Alarm Clock

A sleek, retro-digital alarm clock that runs entirely in your browser.  
No install, no server, no data sent anywhere — just open and use.

## ✨ Features

- **Live digital clock** — hours, minutes, seconds with blinking separator
- **Multiple alarms** — set as many as you need
- **Custom labels** — name each alarm (e.g. "Wake up", "Meeting")
- **4 alarm sounds** — Classic Beep, Soft Chime, Alert Siren, Digital Pulse  
  *(all synthesised in-browser via Web Audio API — no audio files needed)*
- **Repeat days** — choose which days of the week to repeat, or set a one-time alarm
- **Enable / disable toggle** — per alarm, without deleting it
- **Snooze** — +5 minutes with one tap
- **Browser notifications** — fires even when the tab is in the background
- **Persistent storage** — alarms survive page refresh via `localStorage`
- **Fully offline** — works without an internet connection once loaded
- **Self-download button** — visitors can save the app as a single `.html` file

---

## 🚀 How to Use

### Option A — Download & run locally (no internet needed)
1. Visit https://ShahidAziz-2026.github.io/Alarm-clock/
2. Click the **⬇ Download** link at the bottom of the page
3. Open the saved `chrono-alarm-clock.html` by double-clicking it — runs in any browser

### Option B — Clone & open directly
```bash
git clone https://github.com/ShahidAziz-2026/Alarm-clock.git
# Then just open index.html in your browser — no server required
```

---

## 📁 File Structure

```
Alarm-clock/
├── index.html     ← The entire app (HTML + CSS + JS, self-contained)
├── preview.png    ← Facebook / Open Graph link preview image (1200×630)
└── README.md      ← This file
```

> **That's it.** The whole app is one HTML file. No frameworks, no build step,
> no dependencies. The preview.png sits next to it purely for the Facebook link card.

---

## 🛠️ Tech Stack

| Layer         | Technology                                               |
|---------------|----------------------------------------------------------|
| UI            | HTML5 + CSS3 (custom properties, flexbox, animations)   |
| Logic         | Vanilla JavaScript (ES2020)                              |
| Audio         | Web Audio API — tones generated in code, no files needed |
| Storage       | `localStorage` — alarms persist across refreshes         |
| Notifications | Notifications API — works when tab is in background      |

---

## 📜 Licence

MIT — free to use, modify, and share.
