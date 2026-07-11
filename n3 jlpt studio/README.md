# N3 Compass

A mobile-first, offline-friendly study companion for two N3 learners. It focuses on short retrieval practice, natural-speed listening, reading for details, and spoken shadowing.

## Run it locally

This is a static web app. Open it through any local web server, or install Node.js and run `npm install` followed by `npm run dev`.

## Use it on iPhone

1. Create a new GitHub repository named `n3-compass` and upload this entire folder, including `.github`.
2. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **GitHub Actions**.
3. The included deployment workflow will publish the app after every change pushed to the `main` branch. Wait for the green Pages workflow, then open the URL it displays.
4. Open the site in Safari, tap Share → **Add to Home Screen**, and launch it from the new icon.
5. Open once while online; the essential app shell will then be available without a connection.

The speech playback uses the device voice. Browser speech recognition support varies on iOS, so the speaking activity includes a graceful fallback to the keyboard microphone.

## Add your own material

The starter content is in `src/main.js`. Add flashcards to `cards`, or replace the `listening` and `reading` objects with your own short dialogues and notices. Keep content you own or are licensed to use.

The N3 session timing and practice mix reflect the official JLPT test sections: Vocabulary (30 minutes), Grammar/Reading (70 minutes), and Listening (40 minutes).
