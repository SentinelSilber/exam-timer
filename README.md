# Exam Timer

A single-file rotation timer for lab exams where students move between hand samples or stations on a fixed interval. Use it at <https://sentinelsilber.github.io/exam-timer/> or open `index.html` locally in any modern browser. No install, no network, no dependencies.

## Setup

- **Total rounds** – number of samples or stations.
- **Interval per round** – seconds each round lasts.
- **Different intervals for specific rounds** – optional per-round overrides, with a ↓ button that copies a value to every later round (for example, longer first rounds while students settle in).
- **Allow adjusting time during the timer** – enables the live adjustment controls below.
- **Chime** – soft chime, single ping, bell, double beep, wood block, or silent. Tones are synthesized in the browser and kept short.
- **Volume** and an optional distinct tone when the last round ends.
- **Counter label** and dark or light theme.

Settings are remembered in the browser between sessions.

## While running

Continue opens the timer with round 1 at its full time; nothing counts down until you press Start or Space. The display shows only the round counter, the countdown, and a progress line. Start, Reset and Stop sit directly under the countdown; Next Round, Fullscreen, a volume slider and the time adjustments are in a toolbar at the bottom. While paused, the digits pulse and a Paused badge is shown. All controls fade in when the mouse moves and fade out after a few seconds while the timer is counting. The screen is kept awake while the timer runs.

| Key | Action |
| --- | --- |
| Space | Start, pause or resume |
| N | End the current round now and move to the next (before Start, moves to the next round without starting) |
| R | Reset the current round to its full time and wait for Start; later rounds are untouched |
| ↑ / ↓ | Add or remove 5 s from the current round (Shift: 30 s) |
| F | Toggle fullscreen |
| Esc, twice | Stop and return to setup |

With live adjustment enabled, the toolbar also offers −10 / −5 / +5 / +10 s buttons for the current round, and a field to set all remaining rounds to a new interval without stopping the timer.
