IttaikaOS Training Counter

A static HTML training timer and counter app with persistent browser memory. Styled against the Solitude Design Language (SDL) dark/Imperial Violet tokens — Geist type, hairline borders, tabular-numeral mono digits. No build step.

Features

Simple stopwatch

EMOM timer with configurable rounds, round length, and countdown, in a collapsible settings group

HIIT timer with configurable work/rest intervals, rounds, and countdown, in a collapsible settings group

CrossFit-style Web Audio beeps: 3-second countdown beeps, round/phase change tones, and a finish chime

Sound on/off toggle persisted in localStorage

Up to 10 concurrent trackers

Daily counter with customizable reset time

Weekly counter with customizable reset day and time

Lifetime total

Browser-local persistence with localStorage for counters, timer settings, and sound preference

Missed reset catch-up when the app is reopened

Deploy

Push this folder to GitHub, then import the repo into Vercel.

Vercel settings:

Framework Preset: Other

Build Command: leave blank

Output Directory: leave blank

The app entry point is index.html.
