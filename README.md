# How Nations Began: free launch guide

Files: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, firebase.json.

## Option A: GitHub Pages (easiest, free)
1. Create a free account at github.com and make a new public repository, for example `nations`.
2. Click "Add file" > "Upload files" and upload everything in this folder (not the zip itself). Commit.
3. Open Settings > Pages. Under "Build and deployment" choose Source: "Deploy from a branch", Branch: main, folder: / (root). Save.
4. After about a minute your link is https://YOUR-USERNAME.github.io/nations/

## Option B: Firebase Hosting (free Spark plan)
1. Create a project at console.firebase.google.com (no billing needed).
2. On your computer: install Node.js, then run `npm install -g firebase-tools` and `firebase login`.
3. In this folder run `firebase init hosting`, choose your project, set public directory to `.`, answer No to single-page app and No to overwriting index.html.
4. Run `firebase deploy`. Your link will be https://YOUR-PROJECT.web.app

## Install as an app (free, no store)
Open the link in Chrome on Android, then menu > "Install app". It gets a home-screen icon, opens full screen and works offline after the first visit.

## Direct APK (free, outside the Play Store)
After your link is live, go to pwabuilder.com, paste the link, choose Android and download the package. The APK can be shared directly. Google Play itself still needs the one-time $25 developer fee.

## Bengali
The button at the top switches language. It remembers your choice, and the links #bn and #en open a specific language.
