# GG Studio 0.10.8

- **Live previews on your own clip, in every section.** Select a clip in the timeline and the preview at the top of each tool shows *your* footage at the playhead, following the playhead and every setting change. A "Your clip on/off" switch sits on every preview; the line under it says what it shows.
  - **Animate** (Wipe, Depth reveal, Split reveal, Pixel and Particle dissolve), **Interact** (3D cursor, Click effects, Sound effects) and **Scene** (3D carousel, Ring carousel, Glass panel, Prompt bar scene, Reformat): your selected clips play in the preview (up to 4 for the carousels).
  - **Text**: select a text layer and the preview animates your own words; select a clip too and the captions, kill feed, banners and other overlays play on top of your footage. Text animations and Text presets as well.
  - **Color**: Color correction, Color grading, Color FX, One colour, Deep Glow and Shot match show before/after on your selected clip, or on the whole comp / the clip at the playhead when nothing is selected, like the DLSS 5 GG Booster live preview. Color grading learns each look from its After Effects render, so the preview matches the real look closely.
- Works in After Effects and Premiere Pro. Video frames are read with the GG Booster engine's ffmpeg; without it, After Effects renders the frame itself.
- Nothing is changed in your project by the previews.
