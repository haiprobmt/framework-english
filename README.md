# Fluent at Work

A phone app for C1-level professional English: sentence frames for meetings, presentations and emails, IPA pronunciation under every word, spaced review, a repetition radar, and an AI conversation partner you can talk to out loud.

## Install on Android

1. Open the app's GitHub Pages address in **Chrome**.
2. Tap **Install app** in the top bar, or Chrome's **⋮ menu → Install app**.
3. Open **Settings** in the app, paste your Claude API key (from console.anthropic.com) and tap **Save and test**.
4. Allow the microphone when Chrome asks.

## Privacy

- Your progress, drafts and API key are stored only on your phone (browser storage).
- Your messages go to Anthropic's Claude API for feedback and replies.
- Voice input uses Chrome's built-in speech recognition, which sends audio to Google's speech service.

## Files

- `index.html`: the whole app (HTML, CSS and JavaScript in one file)
- `manifest.webmanifest`, `icons/`: install metadata and icons
- `sw.js`: service worker for offline loading. Bump `CACHE` when you change the app.
