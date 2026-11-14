Desktop

Compositor: Niri

Terminal: Alacritty

Bar: Waybar

Font: Go Mono

Shell: Bash

Editor: Neovim

Fetch: Fastfetch

Wallpaper: swaybg

Colours

Element

Hex

Background

#242620

Foreground

#D6CFB8

Accent

#85866F

Inactive

#55574E

Installation

Install the required applications using your distribution's package manager.

Clone the repository:

git clone https://github.com/mxzei/navi-dotfiles.git

Restore the configurations:

cd navi-dotfiles
mkdir -p ~/.config
cp -r niri alacritty waybar fastfetch ~/.config/

Font

Download Go Mono from the official Go repository:

https://github.com/golang/image/tree/master/font/gofont/ttfs

Place the font inside ~/.local/share/fonts/ and run:

fc-cache -f

Wallpaper

Stored privately on Google Drive.

Restore to:

~/Downloads/walls/maingentoo.jpg

Check the wallpaper path in Niri's configuration.

Hardware

Panasonic Let's Note CF-SV9.

Internal display: 1920×1200

External display: 1920×1080 @ 144 Hz

External monitor positioned on the left

Check output names with niri msg outputs before applying monitor settings.
