KisekiOS Training Counter

A static HTML training timer and counter app with persistent browser memory. Styled against the Solitude Design Language (SDL) dark/Imperial Violet tokens — Geist type, hairline borders, tabular-numeral mono digits. No build step.

Three sections: Timer, Track, and Exercises.

Timer

Simple stopwatch

EMOM timer with configurable rounds, round length, and countdown, in a collapsible settings group

HIIT timer with configurable work/rest intervals, rounds, and countdown, in a collapsible settings group

CrossFit-style Web Audio beeps: 3-second countdown beeps, round/phase change tones, and a finish chime

Sound on/off toggle persisted in localStorage

Exercises

An MVP library across two categories: Cardio (Running, Walking, Cycling, RowErg, SkiErg) and Cross-Training (Pull-up, Ring Row, Push-up, Pike Push-up, Air Squat, Burpee Broad Jump, Hollow-body Hold)

Each exercise has a measurement type — repetitions, distance, or duration — with distance stored in meters and displayed intelligently (750 m stays meters, 1,000 m+ shows as km)

Exercises with common variations (Pull-up, Ring Row, Push-up) let you pick a variation instead of creating separate trackers

Add a custom exercise with your own name, category, and measurement type

Apple-style horizontally scrolling category chips with native momentum, snapping, and a persisted last-selected category

Tap an exercise to configure its default quick-add increment, optional daily/weekly goal, and reset schedule, then add it to Track

Track

Shows only exercises explicitly added from the Exercises tab — the full library stays in Exercises

Each card shows today/week/lifetime counts (unit-formatted), an optional goal line, and a single configurable quick-add button

Daily and weekly counters reset automatically at midnight / week start

Browser-local persistence with localStorage for counters, timer settings, and sound preference

Missed reset catch-up when the app is reopened

Deploy

Push this folder to GitHub, then import the repo into Vercel.

Vercel settings:

Framework Preset: Other

Build Command: leave blank

Output Directory: leave blank

The app entry point is index.html.
