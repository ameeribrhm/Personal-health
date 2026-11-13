# Personal Health — GitHub Pages PWA

A mobile-friendly personal wellness tracker. It is designed to be hosted free with GitHub Pages.

## Upload and publish

1. Download and unzip `personal-health-github-files.zip`.
2. Create a new repository on GitHub (for example, `personal-health`).
3. Upload **all files inside this folder** to the repository root. Keep `index.html`, `style.css`, `app.js`, `manifest.json` and `sw.js` together.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub to publish the site. Open the Pages URL on your iPhone.
7. In Safari, tap **Share → Add to Home Screen** to install it.

## Included

- Overview with daily, weekly and monthly completion summaries, plus target-weight progress and weekly weigh-ins.
- Intermittent fasting tracker with 16:8, 18:6, 20:4, 24h, 36h, 48h, 72h, alternate-day example and custom fasts; editable start times, live elapsed/remaining time, completion history and an evidence-informed physiology guide.
- Monthly routine library: workouts, cardio, stretching, meditation, and skin/hair care.
- Workout exercise builder with sets, reps, load, unit and per-exercise notes.
- Run/walk cardio logs with distance, pace, duration and incline; calorie and average-heart-rate estimates.
- HIIT interval builder and a guided timer with start, pause, reset, next-exercise sound cues, and optional save-after-session.
- Timed meditation sessions.
- Weekly daily-habit planner, routine picker, custom habits, reordering, editing, deletion and previous-week carry-forward.
- Daily checklist/log, reminders, daily journal, profile settings.
- JSON backup and restore.

## Important limitations

- **Reminders:** browser notifications are supported while the app is open and permission has been granted. Browsers and iOS may suspend a hosted web app in the background. Reliable scheduled notifications when the app is closed require a push service/backend or an external calendar/reminder integration; this project does not pretend otherwise.
- **Fasting education:** physiological stages are broad explanations, not hour-by-hour guarantees. There is no reliable universal hour at which autophagy begins. The app does not medically recommend prolonged fasts.
- **Heart rate:** average heart rate is a rough age/intensity estimate, not measured heart rate. It is clearly labelled as estimated. Use a wearable for actual readings.
- **Calories:** activity calories are approximate, based on entered duration/distance and body weight.
- **Storage:** data is kept in local browser storage on the device. Clearing browser data or changing devices can remove it. Export a JSON backup regularly.
- **Privacy:** no account or server database is used. Do not use this as a medical record or emergency tool.

## Update later

Replace the files in the GitHub repository with the newer versions and commit the changes. Your browser's local data should remain on that device, but export a backup before major updates.
