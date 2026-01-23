# DroidNet Signal Booster - Releases

This repository contains release artifacts for DroidNet Signal Booster devices.

## For Users

### Supported Hardware

| Pi Model | Support Level | Notes |
|----------|---------------|-------|
| **Pi Zero 2 W** | ✅ Recommended | Best balance of size and performance |
| **Pi 3** | ✅ Recommended | Full performance, larger form factor |
| **Pi 4** | ✅ Recommended | Maximum performance |
| Pi Zero W | ⚠️ Limited | See warning below |

> **⚠️ Pi Zero W Notice**
>
> While we continue to provide images for the original Pi Zero W, **we do not recommend it for new installations** due to its single-core processor and limited RAM. Users may experience:
> - Slower web interface responsiveness
> - Longer firmware flash times
> - Reduced performance with multiple USB devices
> - Some features may be restricted or unavailable
>
> For the best experience, we recommend the **Pi Zero 2 W** which offers significantly better performance in the same form factor.

### Fresh Install (New Devices)

Download the appropriate image for your Raspberry Pi model from the [latest release](https://github.com/travisccook/DroidNetSignalBooster-releases/releases).

| Pi Model | Image |
|----------|-------|
| Pi Zero 2 W | `droidnet-lite-zero2-w-vX.X.img` |
| Pi 3 | `droidnet-lite-pi3-vX.X.img` |
| Pi 4 | `droidnet-lite-pi4-vX.X.img` |
| Pi Zero W ⚠️ | `droidnet-lite-zero-w-vX.X.img` |

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
