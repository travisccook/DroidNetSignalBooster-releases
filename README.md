# DroidNet Signal Booster - Releases

This repository contains release artifacts for DroidNet Signal Booster devices.

## For Users

### Fresh Install (New Devices)

Download the appropriate image for your Raspberry Pi model from the [latest release](https://github.com/travisccook/DroidNetSignalBooster-releases/releases).

| Pi Model | Image |
|----------|-------|
| Pi Zero W | `droidnet-vX.X-pi-zero-w.img.gz` |
| Pi Zero 2 W | `droidnet-vX.X-pi-zero-2.img.gz` |
| Pi 3 | `droidnet-vX.X-pi-3.img.gz` |
| Pi 4 | `droidnet-vX.X-pi-4.img.gz` |

Flash the image to an SD card using [Raspberry Pi Imager](https://www.raspberrypi.com/software/) or similar tool.

### Updating Existing Devices

Devices automatically check for updates and will notify you when one is available. You can also:

1. **Via Web Interface**: Go to Config → System Update → Click "Check for Updates"
2. **Manual Upload**: Download the update package from releases and upload via the web interface

## For Developers

See the [Wiki](https://github.com/travisccook/DroidNetSignalBooster-releases/wiki) for documentation.

## Version Scheme

- **Major versions** (v1, v2, v3) = New images with breaking changes
- **Minor versions** (v1.1, v1.2, v1.47) = Cumulative update packages

Update packages are cumulative - the latest v1.x update brings any v1.0+ installation to current.
