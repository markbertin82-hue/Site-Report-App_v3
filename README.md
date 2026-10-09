# Site Job Reporter V3 — offline PWA test build

## Install on Samsung Android or Windows
This ZIP contains a complete static Progressive Web App (PWA). **Do not open index.html directly from the ZIP or from a file:// URL and expect installation or reliable microphone access.** It must be served over HTTPS (or localhost).

For free testing, host the *contents* of `site-job-reporter-v3` on a free HTTPS static host such as GitHub Pages, subject to your company's policies. Then:
- Android: open the HTTPS address in Chrome or Samsung Internet and choose Install app / Add to Home screen.
- Windows: open the HTTPS address in Edge or Chrome and use Install app.
- Open it once online to cache the app; then test offline using airplane mode.

## Storage and privacy
- Data is saved in IndexedDB on each device. This build stores job snapshots (including media) in IndexedDB, not a separate media-object database.
- The app can export a JSON backup and restore one. Restore **replaces** the current jobs on that device.
- V2.1 jobs are migrated automatically *only if V3 runs under the same browser origin and storage context*. A newly hosted HTTPS app cannot automatically read local file:// browser storage. Export your V2.1 backup and use Restore backup in V3.
- Data is **not** automatically synchronised between phone and laptop. Use export/restore for test data only; restore replaces existing jobs.
- Do not use confidential customer or company records until approved by your employer. Public static hosting distributes app code, not your IndexedDB records, but anyone can access the publicly hosted app files.
- Browsers can still evict local storage. Keep regular backup copies.
- Microphone recording needs HTTPS, browser permission, and device support.
- Do not host backups or job data in the public web folder.

## What's retained
V2.1 jobs, days, notes, checklists, photos, measurements, voice recordings, signature and printable report preview, delete job with confirmation.

## Current limitations
No OneDrive sync, automatic AI report writing, multi-device conflict resolution or server-side backup yet. Offline install must be tested on each device.
