# GATE 2027 Tracker — phone app

## Features
- Weekly reports: topics planned/completed, PYQs attempted/correct, revision backlog, study hours, confidence, weak areas and next week's plan.
- Subject-level syllabus progress.
- Dashboard with overall syllabus progress, latest PYQ accuracy, study hours and backlog.
- Report history with edit/delete.
- JSON backup/restore and CSV export.
- Installable/offline-capable PWA.

## Install on Android
For the full installable app experience, publish these files to an HTTPS static host (for example GitHub Pages or Netlify), then open the HTTPS link in Chrome and choose **Install app** or **⋮ → Add to Home screen**. Opening index.html directly from Downloads can show the webpage, but service-worker installation/offline support will not work from a file URL.

Upload all four files: `index.html`, `manifest.webmanifest`, `service-worker.js`, and `icon.svg`.

## Data/privacy
Records are stored in local browser storage on that device. There is no account, server, or automatic sync. Export a JSON backup before changing phones or clearing browser data. CSV can be opened in Excel/Google Sheets.

The topic counts are self-defined tracking fields, not an official syllabus breakdown. Verify topics against the official GATE 2027 syllabus.
