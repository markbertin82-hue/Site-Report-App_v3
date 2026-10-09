# Site Job Reporter V3.1
Updates: PNE Controls Ltd logo in header, redundant top New Job button removed, photo gallery mobile overflow fix, 3 job action buttons aligned, search improvements. Existing V3 features retained.

## Update GitHub Pages
Upload ALL files from this folder to the ROOT of the same GitHub repository and overwrite the previous files. Include `company-logo.jpeg`, updated `index.html`, and `sw.js`. Do not create a nested directory.
Wait for GitHub Pages deployment, then close and reopen the installed app while online. If the old screen remains, reload the page from the browser URL. Do not clear website data: that may delete saved jobs.

## Data safety
Export a JSON backup before upgrading. This release uses the same IndexedDB name as V3 and does not intentionally delete existing data. Data stays on each device; there is no OneDrive sync.
