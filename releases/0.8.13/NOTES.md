# GG Studio 0.8.13

- **4K clips no longer crash the graphics card.** On a full 4K clip, the neural stage and DLSS need more graphics memory and time per frame than many cards have. On an RTX 3070 Ti (8 GB), Windows reset the card mid-render ("CUDA 719 … engine poisoned", "NR GPU device removed"). Clips bigger than 1440p are now shrunk to a 1080p copy first. The neural stage, coloring and sharpening run on that copy, and DLSS Super Resolution brings it back to 4K (it is switched on if it was off). This is lighter and faster on every card.
- **Clips that are already 4K skip DLSS Super Resolution** when there is nothing left to upscale, and the progress line says so.
- **Clearer message when the graphics driver crashes:** restart the PC, update the NVIDIA driver, then try Encoding quality Best and the HD quality.
- **Safer updates.** The new version is unpacked while After Effects is still open, so only two quick renames are left when it closes, and each one is retried. A PC restart in the middle of an update can no longer leave GG Studio missing, and a half-finished update is repaired.
