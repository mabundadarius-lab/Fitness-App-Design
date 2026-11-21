# PulseFit: Fitness App Design

A dark-mode fitness app UI built with plain HTML, CSS and JavaScript. No build step or dependencies.

## Screens

- **Home:** concentric progress rings (steps, calories, active minutes), today's workout with a video preview, and quick health stats
- **Workouts:** routine list with video-style previews and category filters (Strength, Cardio, Yoga)
- **Workout player:** step-by-step walkthrough with a step progress ring; finishing a workout updates the Home rings
- **Plan:** monthly workout calendar with planned, completed and rest days
- **Stats:** weekly calorie chart plus weight, resting heart rate, workout and streak cards

## Design notes

- Dark theme with a lime primary accent; coral and cyan used for secondary data
- Sora typeface for a consistent, energetic look
- Bottom tab navigation sized for thumb reach on mobile; shown inside a phone frame on larger screens
- Accessible: real buttons, visible focus rings, labelled controls, 44px+ touch targets, reduced-motion support

## Customise

All sample data (workouts, exercise steps, weekly calories, goals) sits in plain objects at the top of the script in `index.html`.

## Run locally

Open `index.html` in any browser.

## Deploy

- **GitHub Pages:** Settings > Pages > deploy from the `main` branch, root folder.
- **Vercel / Netlify:** import the repository; no build settings needed.
