Hamsat Jabal
Hamsat Jabal is a simple workout tracking web app designed to work as a PWA on iPhone through Safari. It can be added to the Home Screen and used like a standalone app.
Project Idea
The idea came from a common problem during gym sessions:

Not knowing how long the workout actually takes.
Forgetting the weights used for each exercise.
Not knowing whether performance improved compared to last week.
Needing a quick and simple way to record exercises, reps, and weights.

Hamsat Jabal was built to make workout tracking easier, clearer, and more organized.
Problem Statement
Many gym users train without accurately tracking:

How long they stayed in the gym.
Their average workout time.
The weights they used in previous sessions.
Whether their performance improved, stayed the same, or decreased.
Their current working weights for each exercise.

This app solves that problem by storing workout data in the cloud and displaying it in a simple, easy-to-read interface.
Main Features

Weekly workout schedule tracking.
Exercise, weight, and reps logging.
Comparison between today's performance and last week's performance.
Performance status display:

Improved
Same performance
Decreased


Today's workout time tracking.
Average workout time calculation based only on actual workout days.
Workout session history with dates.
Body stats tracking:

Current body weight
Height
Body fat percentage


Current working weights summary for all exercises.
Achievements checklist for daily and weekly progress.
60 color themes.
Export and import backup support.
Works through Safari and can be added to the iPhone Home Screen.

Data Storage
The app saves data automatically to a Supabase cloud database. Users create a simple account (username and password) to use the app, and their data is accessible from any device using the same account. IndexedDB is also used locally for caching and achievements. Export and import backup is available for extra safety.
Hosting
The app runs on GitHub Pages as a static website. GitHub Pages is used only to host the app files. The cloud database (Supabase) handles all user data storage.
The app is live at: https://faisalalshehri-1.github.io/hamsat-jabal
Core Files

index.html
manifest.webmanifest
apple-touch-icon.png
icon-512.png
icon-192.png
favicon.png

How to Use
Open the website link in Safari on iPhone, then:

Tap the Share button.
Select Add to Home Screen.
Open the app from the iPhone Home Screen.
Create an account or log in to start tracking your workouts.
