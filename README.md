# ttf-apple-emoji template for Void Linux.
Apple Emojis adapted for installation via xbps-src for the Void Linux distribution.

## Installation steps.
1. Download this repo as a zip.
2. Extract the content.
3. Rename the folder ```ttf-apple-emoji-main``` to ```ttf-apple-emoji```.
4. Move the folder to ```void-packages/srcpkgs```.
5. Execute ```./xbps-src pkg -j$(nproc) ttf-apple-emoji```. # remember to stay in the void-packages directory.
6. Install the package by executing ```xi ttf-apple-emoji```.


## Credits.
- [apple-emoji-linux](https://github.com/samuelngs/apple-emoji-linux)
- [ttf-apple-emoji](https://aur.archlinux.org/packages/ttf-apple-emoji)
- [xbps-src](https://github.com/void-linux/void-packages)
