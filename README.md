# XPTouch JC8048W550 Pixel Clock Fix

## What is this?
This is a pre-compiled firmware binary for [XPTouch](https://github.com/tac5551/xptouch) with a single modification: the pixel clock frequency has been set to **14.5MHz** to fix display issues on certain JC8048W550 boards.

## Who is this for?
Users with a **Guition JC8048W550** (5.5 inch ESP32-S3 display) who experience:
- White or grey screen after flashing XPTouch
- Flickering or unstable display

## How to install
1. Download `firmware.bin` from this repository
2. Copy it to the **root** of your SD card
3. Insert the SD card into your screen
4. Reboot the device
5. XPTouch will automatically detect and flash the firmware
6. After flashing completes, delete `firmware.bin` from the SD card

## Notes
- This is otherwise stock XPTouch firmware — no other changes have been made
- You will still need to set up your `xtouch.json` or `provisioning.json` as normal
- OTA updates will overwrite this firmware with stock XPTouch — disable OTA in settings after flashing

## Credits
- Original XPTouch project by [tac5551](https://github.com/tac5551/xptouch)
- Pixel clock fix discovered by the XPTouch Discord community
