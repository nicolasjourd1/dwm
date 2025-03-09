# dwm
My build of [dwm](https://suckless.org/dwm), using the [azerty patch](https://dwm.suckless.org/patches/azerty/) and custom scripts for sound/brightness buttons.

# Building
First, install `libx11`, `libxft`, `libxinerama`, `freetype2` and `fontconfig`. Packages namesmay wary depending on your system.

Clone the repository and `sudo make clean install`.

# Using dwm
Depending on your display manager, you may create a desktop entry at `/usr/share/xsessions`
```conf
[Desktop Entry]
Encoding=UTF-8
Name=dwm
Comment=Dynamic window manager
Exec=/usr/local/bin/dwm
Icon=dwm
Type=XSession
```
Or write `exec dwm` in `~/.xinitrc`, further details [here](https://wiki.archlinux.org/title/Xinit).
# Customising
Edit `config.h` for [customising dwm](https://dwm.suckless.org/customisation/).