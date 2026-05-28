# Hamsat Jabal

**Hamsat Jabal** is a simple workout tracking web app designed to work as a PWA on iPhone through Safari. It can be added to the Home Screen and used like a standalone app.

## Project Idea

The idea came from a common problem during gym sessions:

- Not knowing how long the workout actually takes.
- Forgetting the weights used for each exercise.
- Not knowing whether performance improved compared to last week.
- Needing a quick and simple way to record exercises, reps, and weights.

Hamsat Jabal was built to make workout tracking easier, clearer, and more organized.

## Problem Statement

Many gym users train without accurately tracking:

- How long they stayed in the gym.
- Their average workout time.
- The weights they used in previous sessions.
- Whether their performance improved, stayed the same, or decreased.
- Their current working weights for each exercise.

This app solves that problem by storing workout data locally and displaying it in a simple, easy-to-read interface.

## Main Features

- Weekly workout schedule tracking.
- Exercise, weight, and reps logging.
- Comparison between today’s performance and last week’s performance.
- Performance status display:
  - Improved
  - Same performance
  - Decreased
- Today’s workout time tracking.
- Average workout time calculation based only on actual workout days.
- Body stats tracking:
  - Current body weight
  - Height
  - Body fat percentage
- Current working weights summary for all exercises.
- Multiple color themes.
- Automatic local data saving using IndexedDB.
- Export and import backup support.
- Works through Safari and can be added to the iPhone Home Screen.

## Data Storage

The app uses **IndexedDB** to save data locally on the same device and browser.

This means the user’s data is saved automatically without requiring an account or login.

> Note: If Safari website data is deleted, the app data may also be removed. For safety, it is recommended to export a backup from time to time.

## Hosting

The app is designed to run on **GitHub Pages** as a static website.

GitHub Pages is used only to host the app files. It does not store user data.

The app is live at:
https://faisalalshehri-1.github.io/hamsat-jabal

## Core Files

- `index.html`
- `manifest.webmanifest`
- `apple-touch-icon.png`
- `icon-512.png`
- `icon-192.png`
- `favicon.png`

## How to Use

Open the website link in Safari on iPhone, then:

1. Tap the Share button.
2. Select **Add to Home Screen**.
3. Open the app from the iPhone Home Screen.
