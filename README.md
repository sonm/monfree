# MonFree – Audio Sequencer

MonFree is a sample based audio sequencer.

## Specifications

### Sequencer
- 32 Pads
- 16 Steps per Pattern
- 32 Patterns

### Samples
- 32 Samples
- Max 10 seconds per Sample
- WAV format

### Effects / Options
- Pattern & Song Effects: Gain, BPM, High Pass, Low Pass, EQ Pre, Compressor, Saturator, EQ Post
- Pad & Step Effects: Gain, Pitch, High Pass, Low Pass, EQ Pre, Compressor, Saturator, EQ Post

### Presets
- LoFi, EDM, Hardstyle, Phonk, Trap

### Resampling
- Mono Mix, Reverse, 8 bit 10 kHz

### Export
- WAV

### Controls & Shortcuts
- Play/Stop: Spacebar
- For fast, hands-on pad control, use your computer keyboard: 1 2 3 4 | q w e r | a s d f | z x c v

### Screenshots
| Main |
| :---: |
| ![Main](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-00.png) |


| Pad Mode | Step Mode | Patt. Mode | Song Mode |
| :---: | :---: | :---: | :---: |
| ![Pad](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-01.png) | ![Step](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-02.png) | ![Pattern](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-03.png) | ![Song](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-04.png) |

### Installation

Installation files for MonFree audio sequencer (Android and Linux).

### Linux (Snap)

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/monfree)

The easiest way to install MonFree on Ubuntu, Debian, Fedora, and other distributions is via the Snap Store:

```bash
sudo snap install monfree
```

Uninstallation:

```bash
sudo snap remove monfree
```

### Linux Native (.deb)
The native way to install MonFree on Ubuntu, Debian, Mint:

```bash
# 1. Add the official repository
curl -1sLf \
  'https://dl.cloudsmith.io/public/4or2une/monfree/setup.deb.sh' \
  | sudo -E bash
# 2. Install the application
sudo apt-get install monfree
```

Uninstallation:

```bash
# 1. Remove the application: 
sudo apt remove monfree
# 2. (Optional) Remove the repository and GPG keys:
sudo rm /etc/apt/sources.list.d/4or2une-monfree.list
sudo rm /usr/share/keyrings/4or2une-monfree-archive-keyring.gpg
sudo apt update
```

### Linux System Requirements
- **Ubuntu:** 22.04 (Jammy) or newer.
- **Debian:** 12 (Bookworm) or newer.
- **Architecture:** x86_64 (64-bit Intel/AMD).
*Note: For older distributions or ARM-based systems, please use the **Snap** version, as it bundles its own compatible libraries.*

### Donate
If you find this sequencer useful, consider supporting development via Binance:

* **Binance Pay ID:** `817510590`
* **BNB / USDT (BEP20):** `0xdb3e0a2e6c2342b9371b762d659e7edbe3fc7cf3`

![Binance QR Code](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/binance_qr.png)

## License

**Copyright (c) 2026 mon. All rights reserved.**

This software is provided as **Freeware** for personal and commercial musical use. 

### Terms of Use
* **Closed Source:** You may not decompile, reverse engineer, or modify the software binaries.
* **Distribution:** You may not sell, rent, or lease this software. 
* **Framework:** This application is built using the **JUCE Framework** (juce.com) and is subject to the JUCE End User License Agreement.

### Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. THE AUTHOR SHALL NOT BE LIABLE FOR ANY DAMAGES OR DATA LOSS ARISING FROM THE USE OF THIS SOFTWARE.
