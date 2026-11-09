# Exam Timer

A single-file rotation timer for lab exams where students move between hand samples or stations on a fixed interval. Use it at <https://sentinelsilber.github.io/exam-timer/> or open `index.html` locally in any modern browser. No install, no network, no dependencies.

## Setup

- **Total loops** – number of samples or stations.
- **Interval per loop** – seconds each loop lasts.
- **Different intervals for specific loops** – optional per-loop overrides, with a ↓ button that copies a value to every later loop (for example, longer first loops while students settle in).
- **Allow adjusting time during the timer** – enables the live adjustment controls below.
- **Chime** – soft chime, single ping, bell, double beep, wood block, or silent. Tones are synthesized in the browser and kept short.
- **Volume** and an optional distinct tone when the last loop ends.
- **Counter label** and dark or light theme.

Settings are remembered in the browser between sessions.

## While running

The display shows only the loop counter, the countdown, and a thin progress line. Controls fade in when the mouse moves and fade out after a few seconds. The screen is kept awake while the timer runs.

| Key | Action |
| --- | --- |
| Space | Pause / resume |
| N | End the current loop now and move to the next |
| ↑ / ↓ | Add or remove 5 s from the current loop (Shift: 30 s) |
| F | Toggle fullscreen |
| Esc, twice | Stop and return to setup |

With live adjustment enabled, the toolbar also offers −10 / −5 / +5 / +10 s buttons for the current loop, a “carry to remaining loops” option so a nudge shifts every later loop too, and a field to set all remaining loops to a new interval without stopping the timer.
