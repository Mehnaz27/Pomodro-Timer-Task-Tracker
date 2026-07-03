# Focusroom — Pomodoro Timer & Task Tracker

A single-page Pomodoro focus timer paired with a task list, styled like an analog darkroom timer. Built with plain HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies other than two Google Fonts.

## Features

- 25-minute focus timer with Start / Pause / Reset
- Automatically switches to a 5-minute break after each focus session
- Session counter tracking how many focus sessions you've completed today (resets at midnight)
- A to-do list — add, complete, and delete tasks
- Tasks and today's session count persist in `localStorage`, so they survive a page refresh
- A sound (Web Audio beep) and a full-screen flash when a timer phase ends
- An Info / Help tab explaining the Pomodoro Technique and how to use the app

## Files

- `index.html` — the entire app (markup, styles, and script in one file)
- `README.md` — this file

## Run it locally

Just open `index.html` in any modern browser. No server or build tools required.

## Hosting on GitHub Pages

1. Create a **public** GitHub repository.
2. Upload `index.html` and `README.md` to the root of the repository.
3. Go to the repository's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose **main** and folder **/ (root)**, then click **Save**.
6. Wait a minute or two, then refresh the Pages settings page — your live URL will appear at the top, in the form:
   `https://<your-username>.github.io/<your-repo-name>/`
