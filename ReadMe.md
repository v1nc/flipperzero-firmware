# v1nc flipper zero firmware
<img src="https://raw.githubusercontent.com/v1nc/flipperzero-firmware/dev/logo.png" width="200" />

This is a fork of the [unleashed firmware](https://github.com/Eng1n33r/flipperzero-firmware).

It is intended to be as vanilla as possible, with functional additions but no deeper changes to the flipper software.

For any problem create an issue or check out the original firmware repo.

## Installation:
* download from [releases](https://github.com/v1nc/flipperzero-firmware/releases)
* [build](https://github.com/v1nc/flipperzero-firmware/blob/dev/documentation/HowToBuild.md) it yourself

## Fork changes:

### BadUSB support for different layouts:

The great user [dummy-decoy](https://github.com/dummy-decoy) implemented loading layout files from the SD card, which was merged into the unleashed firmware. He also has a [good way](https://github.com/dummy-decoy/flipperzero_badusb_kl) to generate layout files. Because of this, the `DUCKY_LANG` support was removed. Maybe it will be added again in the future. You can find the last release supporting `DUCKY_LANG` [here](https://github.com/v1nc/flipperzero-firmware/releases/tag/v0.63.1.1-v1nc).

### additional plugins:
* [MouseJiggler](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/mouse_jiggler)
* [WAV Player](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/wav_player)

### additional games:
* [CHIP8 Emulator](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/chip8)
* [Flappy Bird](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/flappy_bird)
* [Video Poker](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/VideoPoker)
* [2048](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/game2048)
* [Game of Life](https://github.com/RogueMaster/flipperzero-firmware-wPlugins/tree/unleashed/applications/game_of_life)

### This software is for experimental purposes only and is not meant for any illegal activity/purposes. <br> We do not condone illegal activity and strongly encourage keeping transmissions to legal/valid uses allowed by law. <br> Also this software is made without any support from Flipper Devices and in no way related to official devs. 
### Please use for experimental purposes only!

## Support Unleashed Firmware developers so they can buy equipment and develop new features

* ETH/BSC/ERC20-Tokens: `0xFebF1bBc8229418FF2408C07AF6Afa49152fEc6a`
* BTC: `bc1q0np836jk9jwr4dd7p6qv66d04vamtqkxrecck9`
* DOGE: `D6R6gYgBn5LwTNmPyvAQR6bZ9EtGgFCpvv`
* LTC: `ltc1q3ex4ejkl0xpx3znwrmth4lyuadr5qgv8tmq8z9`

_logo generated with DALLE-2_
