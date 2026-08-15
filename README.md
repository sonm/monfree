# Monfree – Audio Sequencer

Monfree is a sample based audio sequencer.

## Specifications

### Sequencer
- 16-pad grid interface
- 1 to 16 steps per pattern
- 80 patterns total
- One-shot and choke pad play modes

### Samples
- 80 sample slots
- Max 10 seconds per sample
- WAV format

### Effects / Options
- Pattern and Song Effects: Gain, BPM, High Pass, Low Pass, EQ Pre, Compressor, Saturator, EQ Post
- Pad and Step Effects: Gain, Pitch, High Pass, Low Pass, EQ Pre, Compressor, Saturator, EQ Post

### Presets
- LoFi, EDM, Hardstyle, Phonk, Trap

### Converting samples
- Mono Mix, Swap L/R, Reverse, 8 bit 32 kHz, 8 bit 22.05 kHz, 8 bit 16 kHz, 8 bit 12 kHz

### Export
- WAV

### Controls & Shortcuts
- Pad control grid layout:
- Row 1: [ 4 ] [ 5 ] [ 6 ] [ 7 ]
- Row 2: [ r ] [ t ] [ y ] [ u ]
- Row 3: [ f ] [ g ] [ h ] [ j ]
- Row 4: [ v ] [ b ] [ n ] [ m ]
- Board Modes - Pad [ 9 ] Pattern [ 0 ] Step [ - ] Song [ = ]
- Expand: [ i ]  More: [ o ]  Erase: [ p ]  Proj.: [ [ ]
- Convert [ k ]  Save C. [ l ]  Preset [ ; ]  Page [ ' ]
- Prev [ , ]  Next [ . ]  Info [ / ]
- Set sample: [ a ]
- On / Off play samples: [ s ]
- Focus on Bank: [ k ]
- Play modes (Pattern / Song): [ ` ]
- Stop: [ z ]
- Record: [ x ]
- Focus on Pads: [ c ]
- Play / Pause: [ Spacebar ]

### Screenshots
| Main |
| :---: |
| ![Main](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-00.png) |


| Pad Mode | Step Mode | Patt. Mode | Song Mode |
| :---: | :---: | :---: | :---: |
| ![Pad](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-01.png) | ![Step](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-02.png) | ![Pattern](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-03.png) | ![Song](https://raw.githubusercontent.com/sonm/monfree/main/screenshots/pic-monfree-04.png) |

### Installation

Installation files for Monfree audio sequencer (Android and Linux).

### Linux (Snap)

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/monfree)

The easiest way to install Monfree on Ubuntu, Debian, Fedora, and other distributions is via the Snap Store:

```bash
sudo snap install monfree
```

Uninstallation:

```bash
sudo snap remove monfree
```

### Linux Native (.deb)
The native way to install Monfree on Ubuntu, Debian, Mint:

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
