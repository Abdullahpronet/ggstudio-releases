# GG Studio 0.10.10

- **DLSS 5 GG Booster: fewer graphics-card crashes.** The live preview's engine now stops (and fully quits) before "Enhance selected clips" or "Preview 3 s" starts, so two engines never use the graphics card at the same time. No new live frame starts until the render is over.
- **Automatic retry after a driver reset.** If the graphics card driver resets mid-render ("device removed", "engine poisoned", CUDA errors), GG Booster waits for it to recover and tries the clip once more with lighter settings (anything above 1080p goes in at 1080p, DLSS brings it back to full size) before showing an error.
- Clearer message if it still fails: close games, OBS or other programs using the graphics card, restart the PC and update the NVIDIA driver.
