# GG Studio 0.8.6

- **Dark footage no longer comes out nearly black.** The DLSS 5 game looks now keep your clip's brightness. Two things were darkening it: the neural rendering stage (Call of Duty ran it twice, which halved the brightness) and the game colour looks, which crushed the shadows. Call of Duty now runs one neural pass (also faster), and every game look makes up for the neural stage and keeps shadow detail. On a night scene from the MW4 trailer, brightness went from about a third of the original to the same as the original.
- **4K and 4K · 120 FPS work on vertical and phone-size clips.** Clips bigger than 1080p (for example 1440×2560 or 1330×2560) were upscaled past 4K (up to 2880×5120), which the graphics card's video encoder can't save ("Open NVENC: Function not implemented"). The upscale is now picked per clip so the result fits in 4K: 2160×3840 for vertical clips, 3840×2160 for landscape.
- Results bigger than 4096 pixels on a side are saved as H.265 automatically.
- Settings saved by older versions update themselves the first time you open the DLSS tab.
