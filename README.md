# OpenCore for HP Envy x360 15

This repository holds specific OpenCore configuration files that enables my HP Envy x360 15-dr0150nd to run macOS.

## Laptop specs

```
Brand: HP
Model: 15-dr0150nd
CPU: i5-8265U (Whiskey Lake)
GPU: Intel UHD 620
```

## Other info

```
OpenCore version: 0.7.6
macOS version: 12 (Monterey)
Audio: ALC285 layout 66
```

## Things that work

- Keyboard (including some FN keys)
- Keyaboard backlight
- Touchpad
- Speakers
- Headphone jack
- USB-c port
- USB-a ports
- Battery status

## Things that don't work

- Bluetoooth
- Webcam
- Microphone
- Fingerrint reader
- SD card reader

## Not tested

- HDMI port

## Downloads

- OpenCorePkg: [0.7.6](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.6)
- macOS Monterey: `python ./macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 download`

Also reference the Install Guide [here](https://dortania.github.io/OpenCore-Install-Guide/).

## Changelog

### v1.0

- added OpenCore GUI
- disabled debugging

### v0.2

- added support for keyboard and audio
- upgraded to macOS Monterey
- started tracking version history

### v0.1

- initial version with Big Sur, not tracked in this repo
