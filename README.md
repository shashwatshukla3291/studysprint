# Study Sprint

A four-step study planner that turns one task into a focused sprint, records completed sessions, and offers a timed mini-game break.

## What it does

- Choose a task and use a 5, 15, 25, or 40 minute preset, or set a custom sprint from 1 to 60 minutes
- Start, pause, resume, and reset the timer
- Pick a soft chime, double beep, bright bell, uploaded audio file, or silent completion setting; preview sounds before a sprint
- Upload a personal audio alarm (up to 1.5 MB); it stays in this browser
- Optionally get a five-minute heads-up and a browser notification when a sprint ends
- Review completed sessions, this week's focus time, and your most frequent task
- Download your session history as a CSV file
- Take a 5- or 10-minute reward break with Flappy-ish, Crossy Road, Snack-size Racer, or Boop the Hamster
- Return to Study Sprint from the arcade's full-screen break-end reminder
- Save sessions, preferences, and game high scores locally without an account or backend

## Run it locally

Open `index.html` in a browser. The arcade lives in `break/index.html`; open it from Study Sprint's final progress screen with **Take a game break**. Keep the page open while a timer is running. Browser notifications require permission, and sound may require you to start the timer or preview a tone first.

## Publish it

Upload the full contents of this folder to the GitHub repository, including the `break` folder and its `index.html`, `styles.css`, and `app.js` files. Then enable GitHub Pages from the repository's Settings → Pages, or import the repository into Vercel. Keeping the arcade folder inside the repository makes both links work on the published site.

## Privacy

Session history, preferences, uploaded sound, and arcade high scores stay in the browser's local storage. They do not sync between devices. Export a CSV if you want a separate copy of your session history.

## Built with

HTML, CSS, JavaScript, and Canvas.
