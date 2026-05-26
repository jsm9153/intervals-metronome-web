# Intervals Metronome — Web

A single-file, dependency-free web metronome built with the Web Audio API. The
web companion to the Intervals Metronome iOS app.

- **Radial dial:** outer ring = beats, inner ring = subdivisions. Tap a dot to
  cycle it through main → accent → silent.
- **Three voices** (beat / subdivision / steady quarter) with synthesized sounds
  (bass, woodblock, click, bell, claves, cowbell, rim), per-voice volume + mute.
- Tempo, time signature, subdivisions, **13 themes**, and saveable templates
  (stored in your browser via `localStorage`).
- Press **Space** to start/stop.

Everything lives in `index.html` — no build step, no dependencies. Open it
locally or visit the GitHub Pages site.
