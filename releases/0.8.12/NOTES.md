# GG Studio 0.8.12

- **DLSS 5 GG Booster works on RTX 20 and 30 series cards with Frame Generation turned on.** DLSS Frame Generation needs an RTX 40 or 50 series card. On older RTX cards the enhance used to stop with "DLSS Frame Generation is unavailable after NGX initialization". GG Studio now spots these cards and skips Frame Generation, then runs every other stage as usual and says so in the progress line. If the error still shows up (for example with an old NVIDIA driver), the clip is enhanced again without Frame Generation automatically.
- The Frame Generation stage now says which cards it needs.
