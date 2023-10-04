# LiveSplit.Kaizo.USB2SNES
This Repository is to help gather, create new, and improve existing Configuration files for the Livesplit USB2SNES Autosplitter.
Most of the files in this repositiory were started by NecroSky90 on SMWCentral (https://www.smwcentral.net/?p=profile&id=43932)
After discovering these last year, and this year (2022) started building my own, I wanted somewhere we could easily add more configurations to.
Please feel free to fork this repo, make your own, or improve the configs here, and pull request back. the more the merrier.

# What is the USB2SNES Autosplitter
A livesplit component for splitting various kaizo romhacks automatically via USB2SNES, based on the work of tewtal and Skarsnik
Check out their work here: https://github.com/usb2snes/LiveSplit.USB2SNESSplitter

# What do you need?
- LiveSplit
- QUsb2Snes (You can get the latest version here: https://github.com/usb2snes/usb2snes/releases)
- Or USB2SNES (http://usb2snes.com/)
- One of the supported devices
- One of the supported romhacks
- Splits for the romhack

# Supported devices

- Fxpak Pro (Install firmware based on these instructions: http://usb2snes.com/)
- SNES Classic (See installation guide here: https://github.com/Skarsnik/QUsb2snes/blob/master/README.md#snes-classic-called-also-snes-mini)

## Unsupported, but tested
- QUSB2SNES software running, set up for LUA Bridge (Deprecated)
    - ![image](https://github.com/Chsbrgr/LiveSplit.Kaizo.USB2SNES/assets/1546349/1952e3f5-d6cb-4a90-aaa2-d3accaf3cd4e)
- SNES9x-rr - a fork of SNES9x with support for Lua Scripts (https://github.com/gocha/snes9x-rr/releases)

# Installation

- Copy "LiveSplit.USB2SNESSplitter.dll" to your LiveSplit-folder "LiveSplit/Components"
- In Livesplit -> Edit Layout… 
- Add -> Control -> USB2SNES Auto Splitter
- Connect your device via USB with your computer and start QUsb2Snes
- Layout Settings (lower left corner) -> choose tab 'USB2SNES Auto Splitter'
- Click 'Autodetect' next to Device to find your device (if it is not detected, make sure the correct firmware is installed, connection is working and QUsb2Snes is running)
- Config file: Choose the config file corresponding to the hack. A config file works for all categories of a romhack.
- Set correct exits for your splits. Default settings for hacks are level names (followed by (S) for secret exits). Settings can be changed in the config file or through the drop-down menus next to your splits in Layout Settings

**Attention: For a hack to be recognized correctly, the correct Game Name has to be set in LiveSplit (Best done with Autocomplete in 'Edit Splits...')**
