# Job Keeper

A **lightweight, offline-first web app** to track jobs, assign names, mark completion status, and generate boss-ready updates. Designed for **iPhone, iPad, and desktop browsers**, fully PWA-enabled for a native “app” experience.

---

## Features

- Add jobs with **job number**, **name(s)**, and **completion status**.
- **Mark jobs complete or incomplete** and toggle status with one click.
- **Search and filter** jobs by number, names, or status.
- **Delete or edit** any job entry.
- **Boss Update** generator:
  - Select **start and end dates** with calendar pickers.
  - Generate a text summary of completed and pending jobs.
  - **Copy** to clipboard or **send via text** directly from the app.
- **Local storage** keeps your data on your device (no account required).
- **Export/Import** jobs as JSON backups.
- **PWA-ready**: add to your home screen for a native app experience.
- Fully **mobile-friendly**, optimized for iPhone viewing.

---

## Installation / Usage

### GitHub Pages

1. Clone or download this repository.
2. Open `index.html` in your browser or deploy via GitHub Pages:

   - Go to **Settings → Pages → Source → main branch / root folder**.
   - Your app will be available at:  
     ```
     https://YOURUSERNAME.github.io/job-keeper/
     ```

### Add to Home Screen (iOS)

1. Open the app in Safari.
2. Tap **Share → Add to Home Screen**.
3. The app will now appear like a native app with its icon.

---

## File Structure

job-keeper/
├─ index.html # Main app file
├─ manifest.webmanifest # PWA manifest
├─ sw.js # Service worker for offline support
└─ README.md

---

## Usage Tips

- **Date range in Boss Update** defaults to the last 7 days.
- **Pending jobs** appear in red, **completed** jobs appear in green.
- Export your jobs regularly for backup.
- Works fully **offline**, thanks to PWA support.

---

## Future Enhancements

- Quick preset ranges (This Week / Last Week) for boss update.
- Auto-formatting of job numbers.
- Optional cloud sync for shared teams (currently local-only).

---

## License

MIT License – free to use, modify, and distribute.
