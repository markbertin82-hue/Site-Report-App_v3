# Site Job Reporter V4 - AI-assisted report drafting

New: technical and customer report types, export prompt to ChatGPT by clipboard, paste/edit/save separate drafts, print-ready PNE branded report preview, cropped logo.

## How to use
Open a job > Report > choose report type > Prepare AI prompt > Copy prompt. Paste into ChatGPT. Review the generated text, copy it back into the app's report editor, and Save report draft. Print / Save as PDF from the report tab. Switch report type to save a separate draft.

Voice recordings and photo image contents are not automatically sent to ChatGPT; the prompt includes metadata only. The user must transcribe or attach them separately if appropriate.

## Update
Back up jobs first. Replace existing GitHub Pages root files with this package's files, including company-logo.png and sw.js. Remove old company-logo.jpeg if desired. Keep the same repository and URL. Wait for deployment, reopen app online, and allow cache refresh. Never clear site data to force an update.

## Privacy
The app does not call an AI API. Copying a prompt to ChatGPT sends information to a third party when pasted. Do not use real confidential work data without employer approval. Each device retains separate IndexedDB data. There is no OneDrive sync or automatic cloud backup.
