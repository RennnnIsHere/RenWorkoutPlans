# 🏋️ Home Gym Trainer

A lightweight, zero-dependency workout tracking web app for a 4-day hypertrophy split using dumbbells, resistance bands, and bodyweight.

## Features

- **Set Counter** — Track completed sets for each exercise per workout
- **Workout Streaks** — See your current streak, longest streak, and total workouts
- **14-day Calendar** — Visual dot grid showing your recent workout history
- **Mark Day Done** — Log each workout day with one click
- **Coaching Tips** — Form cues for every exercise
- **Science Tab** — Evidence-based training principles
- **Volume Tracker** — Weekly sets per muscle group

## Tech Stack

- Pure HTML + CSS + JavaScript (no frameworks, no build step)
- `localStorage` for persistent data (counters, streaks, dates)
- Google Fonts (Syne + DM Mono)
- Tabler Icons (CDN)

## Getting Started

### Option 1: Open locally
Just open `index.html` in your browser — no server needed.

### Option 2: Deploy on GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://your-username.github.io/workout-app/`

### Option 3: Deploy on Netlify / Vercel

Drop the `index.html` file (or this whole folder) into [Netlify Drop](https://app.netlify.com/drop) — instant live URL, no account needed.

## Program Details

| Day | Focus | Duration |
|-----|-------|----------|
| Day 1 | Push (Chest, Shoulders, Triceps) | ~50 min |
| Day 2 | Pull (Back, Biceps, Rear Delts) | ~50 min |
| Day 3 | Legs (Quads, Hams, Glutes, Calves) | ~55 min |
| Day 4 | Upper (Full upper body re-stimulus) | ~50 min |

**Rep range:** 8–15 (hypertrophy zone)  
**Sets per session:** 16–20  
**Equipment:** Dumbbells, Resistance Bands, Bodyweight

## Data Storage

All data is saved to `localStorage` in your browser under keys prefixed with `hgt_`. Clearing your browser data will reset streaks and counters.

## License

MIT
