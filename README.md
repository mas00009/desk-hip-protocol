# Desk Hip Protocol

A 15-minute hip mobility routine with a built-in timer, designed to be done at a
desk. Built for hips that sit all day: limited internal rotation, a habitual
toes-out stance, and knees that don't tolerate kneeling.

**Open it:** https://mas00009.github.io/desk-hip-protocol/

One page. A list of ten exercises, each with an illustration of the position and
its sets and timing. Press Start and it counts each set down, names the side or
hold you're on, tracks reps where they matter, beeps and buzzes at every change,
and moves to the next one on its own. Tap any exercise to start from there.

- **Knee-safe.** No kneeling, no deep knee flexion, no couch stretch.
- **Accurate clock.** Timing is derived from timestamps, so it holds even when
  the screen sleeps or the tab is backgrounded. The screen is kept awake while
  a session runs.
- **Works offline.** Installable to the home screen; a service worker caches the
  whole app. It is a single self-contained file with no network dependencies.
  The illustrations are embedded as CSS masks, so they take the theme's accent
  colour and stay legible in both light and dark.

## Layout

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: markup, styles, logic, and artwork |
| `sw.js` | Service worker; bump `CACHE` to push an update to installed copies |
| `manifest.webmanifest` | Install metadata |
| `icon-*.png` | Home-screen icons |

## Not medical advice

General mobility guidance. Stop anything that causes knee pain, and see a
physiotherapist if pain persists, if you get sharp or catching pain in the hip
joint, or if things get worse rather than better over three weeks.
