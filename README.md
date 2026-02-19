# 🗓️ 100 Days Progress Tracker

A beautiful, fully offline progress tracker to help you complete your 100-day challenge — one day at a time.

![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square)
![Offline](https://img.shields.io/badge/Works-Offline-green?style=flat-square)
![No Install](https://img.shields.io/badge/No%20Install-Required-blue?style=flat-square)

---

## ✨ Features

- **100 day grid** — tap any day to mark it as complete
- **Confirmation popup** — asks you to confirm before saving, so no accidental clicks
- **Live stats** — see days done, days remaining, and your percentage at a glance
- **Animated progress bar** — fills up as you make progress
- **Fully offline** — no internet, no server, no account needed
- **Auto-saves** — progress is stored in your browser and survives closing the tab
- **Works on mobile** — responsive layout for phones and tablets
- **Single file** — everything is in one `.html` file, nothing else needed

---

## 🚀 Setup — How to Use

### Option 1 — Run it locally (simplest)

1. Download `100days_tracker.html` from this repository
2. Double-click the file to open it in your browser
3. Start checking off your days!

No Python, no Node.js, no installs — just a browser.

---

### Option 2 — Use it as a live website (via GitHub Pages)

You can host this for free using GitHub Pages so you can open it on any device with a link.

1. **Fork or clone** this repository to your own GitHub account
2. Go to your repository on GitHub
3. Click **Settings** → scroll to **Pages** in the left sidebar
4. Under "Branch", select **main** and click **Save**
5. Wait about 1 minute
6. Your tracker will be live at:

```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/100days_tracker.html
```

Bookmark that link and open it any time — no downloads needed.

---

## 💾 How Data is Saved

Progress is stored in your **browser's localStorage** — a built-in, offline database that every browser supports. This means:

- ✅ Works completely offline
- ✅ Data persists after closing the browser
- ✅ No account or login required
- ⚠️ Data is tied to the browser you use — switching browsers (e.g. Chrome → Firefox) will show a fresh tracker
- ⚠️ Progress does not sync between devices automatically

**Tip:** Pick one browser on one device as your main tracker and stick to it.

---

## 📁 File Structure

```
100-days-tracker/
│
├── 100days_tracker.html   ← The entire app (open this in your browser)
└── README.md              ← This file
```

---

## 🛠️ Built With

- **HTML / CSS / JavaScript** — no frameworks or dependencies
- **localStorage** — browser-native offline storage (acts like a local database)
- **Google Fonts** — Playfair Display, DM Sans, DM Mono

---

## 📄 License

Free to use and modify for personal use.
