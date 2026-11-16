# Budget & Expense Tracker — GitHub PWA

This folder is prepared to publish the HTML tracker as an installable, offline-friendly web app.

## Publish it with GitHub Pages
1. Sign in to GitHub and create a new repository. A name such as `budget-tracker` is fine.
2. Set the repository to **Public** (the free GitHub Pages option is simplest with a public repository).
3. Upload **all the contents of this folder** to the repository's root. Make sure `index.html`, `manifest.webmanifest`, and `sw.js` are at the top level, and keep the `icons` folder.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then Save.
7. Wait for GitHub Pages to publish. Your site address will look like:
   `https://YOUR-USERNAME.github.io/budget-tracker/`

## Install it on Android
1. Open the published address in Google Chrome while online.
2. Wait for the page to finish loading. If Chrome offers **Install app**, tap it. Otherwise open Chrome's ⋮ menu and choose **Add to Home screen** (the wording can vary).
3. Confirm installation. Find **Budget Tracker** on your home screen or app list.
4. Open it once while online, then test it in Airplane mode. It should open in its own app-style window and work offline.

## Important data and offline notes
- The tracker stores entries in this browser app's local storage on this device. It does not automatically sync between devices.
- Keep regular backups using **Settings → Backup & restore → Create backup text**. Store the backup somewhere safe.
- Do not clear Chrome/site data or uninstall the app without first backing up; doing so may erase locally stored entries.
- GitHub Pages needs internet for the first visit and installation. After the app shell has been cached, it can open offline.
- The original Google Fonts download was removed so the app does not need that external font to render offline.
- The service worker caches the app shell. Publish future code changes to GitHub; the app may need to be opened online once to receive updates.
