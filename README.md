# Desk Hip Protocol

A 15-minute hip mobility routine with a built-in guided timer, designed to be done
at a desk on weekday mornings. Built for hips that sit all day: limited internal
rotation, a habitual toes-out stance, and knees that don't tolerate kneeling.

**Open it:** https://mas00009.github.io/desk-hip-protocol/

## What it does

- **Guided timer.** Runs the full 15:00 sequence, one drill at a time, with per-side
  prompts, cues, a rep counter, and audio plus haptic cues at each transition. The
  clock is derived from timestamps, so it stays accurate even if the screen sleeps
  or the tab is backgrounded.
- **Two modes.** *Floor* uses the full sequence. *No floor* swaps every floor drill
  for a standing or seated equivalent, for open-plan offices and work clothes.
- **Knee-safe throughout.** No kneeling, no deep knee flexion, no couch stretch.
- **Day-aware finisher.** The last two minutes change by weekday, rotating through
  internal-rotation and external-rotation isometrics, hinge holds, single-leg
  balance, and long holds.
- **Works offline.** Installable to the home screen; a service worker caches the
  whole app. It is a single self-contained file with no network dependencies —
  the illustrations are embedded as CSS masks so they take the theme's accent
  colour and stay legible in both light and dark.

Progress notes and session history are stored in `localStorage` on the device only.
Nothing is uploaded anywhere.

## Layout

| File | Purpose |
| --- | --- |
| `index.html` | The whole app — markup, styles, logic, and artwork |
| `sw.js` | Service worker; bump `CACHE` to push an update to installed copies |
| `manifest.webmanifest` | Install metadata |
| `icon-*.png` | Home-screen icons |

## Not medical advice

General mobility guidance. Stop anything that causes knee pain, and see a
physiotherapist if pain persists, if you get sharp or catching pain in the hip
joint, or if things get worse rather than better over three weeks.
