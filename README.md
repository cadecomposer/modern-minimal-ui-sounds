# Modern Minimal UI  

Minimalistic UI sounds adhering to the freedesktop naming standard, made in [REAPER](https://www.reaper.fm/) using the [Vital VST](https://vital.audio/). This is meant to be a drop-in replacement for the default [Ocean](https://github.com/KDE/ocean-sound-theme) theme on Plasma 6.    

These sounds are designed for use with compatible Linux desktops, namely GNOME and KDE Plasma 6+. Feel free if you would like to use them on Windows and the like, however you will have to manually select the sounds in the settings as I will not be providing a .bat script for that.

## How to install on Linux

1. Make the directory ~/.local/share/sounds if it does not already exist, and `cd` into it

`mkdir -p ~/.local/share/sounds`  
`cd ~/.local/share/sounds`

2. Clone the repository

`git clone https://github.com/cadecomposer/modern-minimal-ui-sounds.git`

3. Enable the sound theme
  - In KDE Plasma 6, in Settings under Appearance & Style, click on Colors & Themes > System Sounds and select "Modern Minimal UI"
  - In GNOME, install `gnome-tweaks` package for your distribution, then open Tweaks and go to Sound > System Sound Theme and select "Modern Minimal UI"
  - Cinnamon (Linux Mint) doesn't use the same method because of the way its sound theme is handled, so you will have to go into the Sound settings and set each sound manually. There may be a way to script this, but I am not confident enough to write a script to do that (I'm not much of a programmer).

NOTE: If you cannot open the REAPER project file, you may need to install [Reapack](https://reapack.com/) with [BirdBird's Global Sampler JSFX](https://forum.cockos.com/showthread.php?p=2506514), as well as [SWS extensions](https://www.sws-extension.org/). I have not tested this on other computers, so let me know if you run into any issues and I can try to help.

---

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
