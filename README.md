# Hamsat Jabal

**Hamsat Jabal** is a simple workout tracking web app designed to work as a PWA on iPhone through Safari. It can be added to the Home Screen and used like a standalone app.

## Project Idea

The idea came from a common problem during gym sessions:

* Not knowing how long the workout actually takes.
* Forgetting the weights used for each exercise.
* Not knowing whether performance improved compared to last week.
* Needing a quick and simple way to record exercises, reps, and weights.
* Not knowing the daily protein target or how much protein has already been consumed.

Hamsat Jabal was built to make workout tracking easier, clearer, and more organized.

## Problem Statement

Many gym users train without accurately tracking:

* How long they stayed in the gym.
* Their average workout time.
* The weights they used in previous sessions.
* Whether their performance improved, stayed the same, or decreased.
* Their current working weights for each exercise.
* Their daily protein needs based on their goal.
* How much protein they have already consumed during the day.

This app solves that problem by storing workout and nutrition-related data in the cloud and displaying it in a simple, easy-to-read interface.

## Main Features

* Weekly workout schedule tracking.
* Exercise, weight, and reps logging.
* Comparison between today's performance and last week's performance.
* Performance status display:

  * Improved
  * Same performance
  * Decreased
* Today's workout time tracking.
* Average workout time calculation based only on actual workout days.
* Workout session history with dates.
* Body stats tracking:

  * Current body weight
  * Height
  * Body fat percentage
* Daily protein needs calculator based on body weight and training goal.
* Daily protein intake tracker with progress percentage.
* Current working weights summary for all exercises.
* Achievements checklist for daily and weekly progress.
* 60 color themes.
* Export and import backup support.
* Works through Safari and can be added to the iPhone Home Screen.

## Protein Calculator

The app estimates daily protein needs based on the user’s current body weight and selected goal:

* Cutting: higher protein range to help preserve muscle during a calorie deficit.
* Maintenance: moderate range to maintain muscle mass and support training.
* Bulking: range suitable for supporting muscle growth with a calorie surplus.

The app also allows the user to enter how much protein they have eaten today and shows progress toward the daily target.

## Data Storage

The app saves data automatically to a Supabase cloud database. Users create a simple account with a username and password to use the app, and their data is accessible from any device using the same account.

IndexedDB is also used locally for caching and achievements. Export and import backup is available for extra safety.

## Hosting

The app runs on GitHub Pages as a static website. GitHub Pages is used only to host the app files. The cloud database, Supabase, handles all user data storage.

The app is live at:

```text
https://faisalalshehri-1.github.io/hamsat-jabal
```

## Core Files

* `index.html`
* `manifest.webmanifest`
* `apple-touch-icon.png`
* `icon-512.png`
* `icon-192.png`
* `favicon.png`

## How to Use

Open the website link in Safari on iPhone, then:

1. Tap the Share button.
2. Select **Add to Home Screen**.
3. Open the app from the iPhone Home Screen.
4. Create an account or log in to start tracking your workouts.
