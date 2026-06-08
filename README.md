# DSA Tracker — NeetCode 150

A minimal, dark-themed tracker for DSA revision using spaced repetition.

## Features

- Add problems with topic and difficulty
- Auto-schedules revision on Day 3, Day 7, Day 14
- Shows what needs revision today
- Tracks streak, mastered problems, and NeetCode 150 progress
- Filter by topic
- All data stored in browser localStorage — no backend needed

## How to use

Just open `index.html` in any browser. No install, no setup.

## Deploy on GitHub Pages

1. Push this repo to GitHub
2. Go to Settings → Pages
3. Set source to `main` branch, `/ (root)`
4. Your tracker will be live at `https://<your-username>.github.io/<repo-name>`

## Spaced repetition schedule

| Revision | When |
|----------|------|
| 1st | Day 3 after solving |
| 2nd | Day 7 after solving |
| 3rd | Day 14 after solving |

After all 3 revisions, the problem is marked as **Mastered**.
