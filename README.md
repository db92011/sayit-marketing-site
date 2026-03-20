# SayIt Marketing Site

This is the standalone marketing site for SayIt!.

## Structure

This repo contains only the marketing layer:

- `index.html` → main marketing page
- `styles.css` → styling
- `assets/` → images and icons

## What this site does

This site:
- explains SayIt!
- routes users into the install flow

This site does NOT:
- run the app
- contain app logic
- handle billing

## Install Flow

The Download button sends users to:

https://sayitapp.pages.dev/?source=pwa

From there:
- the standalone app opens
- users install via "Add to Home Screen"

## Architecture

- Circle homepage → entry point
- This site → marketing + routing
- SayIt app → https://sayitapp.pages.dev

## Important Rules

- Do NOT add app code here
- Do NOT embed scripts from `/sayit/app.js`
- Keep this repo lightweight and static

This is a clean separation layer between marketing and the app.
