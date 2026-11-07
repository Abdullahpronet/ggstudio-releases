# GG Studio 0.10.2

- **Pick your apps.** The installer has checkboxes for After Effects and Premiere Pro: tick one or both. It pre-ticks the apps found on the PC (or your last choice). A one-app install gets that app's own signed package, so GG Studio only shows up where you want it.
- **Updates keep your choice.** A one-app copy downloads that app's small signed manifest with each update (`variants` in latest.json), so an update never adds GG Studio back to the other app.
- **Much faster setup.** The GG Booster engine (Visual Enhancer by Merserk, ~850 MB) now downloads with Windows' own curl: 25 s on the test PC, down from 18 min. A progress window shows MB, speed and time left, with a Skip button. Unzipping is faster too.
- If GitHub can't be reached but a Visual Enhancer is already in Documents, the installer keeps it instead of failing.
- To add or remove an app later, run the installer again.
