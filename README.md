# Awesome Wayland

A curated list of [Wayland](https://gitlab.freedesktop.org/wayland/wayland) code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

  - [Brightness Control](#brightness-control)
  - [Browsers Without X Library Dependency](#browsers-without-x-library-dependency)
  - [Clipboard Managers](#clipboard-managers)
  - [Compositors](#compositors)
  - [Display Configuration](#display-configuration)
  - [Image Viewers](#image-viewers)
  - [Launchers](#launchers)
  - [Libraries](#libraries)
  - [Notifications](#notifications)
  - [PDF Viewers](#pdf-viewers)
  - [Screen Locking](#screen-locking)
  - [Screencasting](#screencasting)
  - [Screenshots](#screenshots)
  - [Session Management](#session-management)
  - [Status Bars](#status-bars)
  - [Terminal Emulators](#terminal-emulators)
  - [Tools](#tools)
  - [Video Players](#video-players)
  - [Wallpaper](#wallpaper)
  - [License](#license)

## Brightness Control

No Wayland-specific requirements, so you can use your xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl), [brillo](https://gitlab.com/cameronnemo/brillo), [light](https://github.com/haikarainen/light), or just directly manipulate `/sys/class/backlight`.

* [Wlsunset](https://sr.ht/~kennylevinsen/wlsunset/) - Day/night gamma adjustments for Wayland compositors supporting wlr-gamma-control-unstable-v1.

## Browsers without X library dependency

* QtWebEngine
    * [Crusta](https://github.com/Tarptaeya/Crusta) - Fast, modern and minimal desktop web browser with rich features
    * [Dooble](https://textbrowser.github.io/dooble/) - The weather bug browser. Minimal, cute, and unusually stable
    * [Falkon](https://www.falkon.org/) - KDE web browser
    * [Viper Browser](https://github.com/LeFroid/Viper-Browser) - A lightweight browser using QtWebEngine

* WebKit2GTK
    * [Surfer](https://github.com/nihilowy/surfer) - Simple keyboard based webkit2gtk browser
    * [wyeb](https://github.com/jun7/wyeb) - A vim-like webkit2gtk browser

## Clipboard Managers

* [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command-line copy/paste utilities for Wayland
* [clipman](https://github.com/yory8/clipman) - A simple clipboard manager for Wayland

## Compositors

* [Cagebreak](https://github.com/project-repo/cagebreak) - A Wayland tiling compositor inspired by Ratpoison
* [Cardboard](https://gitlab.com/cardboardwm/cardboard) - A scrollable tiling Wayland compositor
* [hikari](https://hikari.acmelabs.space/) - A hybrid stacking/tiling Wayland compositor
* [labwc](https://github.com/johanmalm/labwc) - A stacking Wayland compositor with look and feel of openbox
* [river](https://github.com/ifreund/river) - A dynamic tiling Wayland compositor
* [Sway](https://github.com/swaywm/sway) - i3-compatible Wayland compositor
* [Waybox](https://github.com/wizbright/waybox) - An openbox clone on Wayland
* [Wayfire](https://github.com/WayfireWM/wayfire) - 3D Wayland compositor
* [Weston](https://gitlab.freedesktop.org/wayland/weston/) - Reference compositor for Wayland
* [Mutter](https://wiki.gnome.org/Projects/Mutter/) - A window and compositing manager that displays and manages your desktop via OpenGL.

## Display Configuration

* [Kanshi](https://github.com/emersion/kanshi) - Dynamic display configuration
* [Wallutils](https://github.com/xyproto/wallutils) - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers
* [wdisplays](https://github.com/cyclopsian/wdisplays) - GUI display configurator for wlroots compositors
* [wlay](https://github.com/atx/wlay) - Graphical output management for Wayland
* [wlr-randr](https://github.com/emersion/wlr-randr) - An xrandr clone for wlroots compositors

## Image Viewers

* [imv](https://github.com/eXeC64/imv) - A command line image viewer for X11/Wayland
* [mvi](https://github.com/occivink/mpv-image-viewer) - A command line image viewer utilizing mpv

## Launchers

* [bemenu](https://github.com/Cloudef/bemenu) - Dynamic menu library and client program inspired by dmenu
* [dmenu-wayland](https://github.com/nyyManni/dmenu-wayland) - dmenu-wl is an efficient dynamic menu for wayland (wlroots)
* [fuzzel](https://codeberg.org/dnkl/fuzzel) - Application launcher for wlroots based Wayland compositors, similar to rofi's `drun` mode
* [LavaLauncher](https://git.sr.ht/~leon_plickat/lavalauncher) - A simple launcher panel for Wayland desktops
* [Mauncher](https://github.com/mortie/mauncher) - A GTK-based alternative to dmenu for Wayland which supports display scaling
* [nwg-launchers](https://github.com/nwg-piotr/nwg-launchers) - A GTK-based application grid launcher, button bar and dmenu for Wayland
* [sirula](https://github.com/DorianRudolph/sirula) - Simple app launcher for Wayland written in Rust
* [wldash](https://github.com/kennylevinsen/wldash) - Wayland dashboard and launcher written in Rust
* [Wofi](https://hg.sr.ht/~scoopta/wofi) - A launcher/menu program for wlroots based Wayland compositors such as sway
* [yofi](https://github.com/l4l/yofi) - A minimalistic menu for wayland
* [rofi](https://github.com/lbonn/rofi) - A fork of rofi with Wayland support

## Libraries

* [client toolkit](https://github.com/Smithay/client-toolkit) - A toolkit for writing Wayland clients in Rust
* [swc](https://github.com/michaelforney/swc) - A library for making a simple Wayland compositor
* [wlroots](https://github.com/swaywm/wlroots) - Pluggable, composable, unopinionated modules for building a Wayland compositor
* [wob](https://github.com/francma/wob) - A lightweight overlay volume/backlight/progress/anything bar for Wayland

## Notifications

* [fnott](https://codeberg.org/dnkl/fnott) - Keyboard driven and lightweight Wayland notification daemon for wlroots-based compositors
* [Mako](https://github.com/emersion/mako) - A lightweight Wayland notification daemon

## PDF Viewers

* [zathura](https://git.pwmt.org/pwmt/zathura) - A document viewer

## Screen Locking

* [swayidle](https://github.com/swaywm/swayidle) - Idle management daemon for Wayland
* [swaylock](https://github.com/swaywm/swaylock) - Screen locker for Wayland
* [swaylock-effects](https://github.com/mortie/swaylock-effects) - A fork of swaylock with effects such as a blurred screenshot as background or a clock on the lockscreen
* [waylock](https://github.com/ifreund/waylock) - A simple screenlocker for Wayland compositors

## Screencasting

* [ssr-wlroots](https://github.com/foxcpp/ssr-wlroots) - A version of SimpleScreenRecorder with support for `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`). Doesn't support recording area selection and has issues with multiple screens. 
* [wf-recorder](https://github.com/ammen99/wf-recorder) - A utility program for screen recording of `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`)
* [wlrobs](https://hg.sr.ht/~scoopta/wlrobs) - An obs-studio plugin that allows you to screen capture on wlroots based wayland compositors
* [wshowkeys](https://git.sr.ht/~sircmpwn/wshowkeys) - Displays keys being pressed on a Wayland session

## Screenshots

* [Grim](https://github.com/emersion/grim) - Grab images from a Wayland compositor
* [Slurp](https://github.com/emersion/slurp) - Select a region in a Wayland compositor
* [Swappy](https://github.com/jtheoof/swappy) - A Wayland-native snapshot editing tool, inspired by Snappy on macOS

## Session Management

* [wlogout](https://github.com/ArtsyMacaw/wlogout) - A Wayland-based logout menu

## Status Bars

* [i3status-rust](https://github.com/greshake/i3status-rust) - Very resource-friendly and feature-rich replacement for i3status, written in pure Rust
* [rootbar](https://hg.sr.ht/~scoopta/rootbar) - Root Bar is a bar for wlroots based Wayland compositors such as sway
* [sfwbar](https://github.com/LBCrion/sfwbar) - Sway Floating Window Bar is a taskbar for Sway, focused on a stacking layout workflow
* [waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors
* [yambar](https://codeberg.org/dnkl/yambar) - Modular status panel for X11 and Wayland, inspired by polybar

## Tools

* [wtype](https://github.com/atx/wtype) - A Wayland tool that allows you to simulate keyboard input like [xdotool](https://github.com/jordansissel/xdotool)
* [ydotool](https://github.com/ReimuNotMoe/ydotool) - A generic Linux command-line automation tool for Wayland

## Terminal Emulators

* [Alacritty](https://github.com/alacritty/alacritty) - A cross-platform, GPU-accelerated terminal emulator
* [Ate](https://github.com/andir/ate) - Awesome terminal emulator
* [Foot](https://codeberg.org/dnkl/foot) - A fast, lightweight and minimalistic Wayland terminal emulator
* [Germinal](https://github.com/Keruspe/Germinal) - Minimalist vte-based terminal emulator
* [GNOME Terminal](https://wiki.gnome.org/Apps/Terminal) - A terminal emulator for GNOME
* [Havoc](https://github.com/ii8/havoc) - A minimal terminal emulator for Wayland
* [Kitty](https://github.com/kovidgoyal/kitty) - A cross-platform, fast, feature-full, GPU-based terminal emulator
* [Termite](https://github.com/thestinger/termite) - A keyboard-centric VTE-based terminal, aimed at use within a window manager with tiling and/or tabbing support
* [wterm](https://github.com/majestrate/wterm) - An [st](https://st.suckless.org/) fork for wayland

## Video Players

* [mpv](https://github.com/mpv-player/mpv) - Command line video player

## Wallpaper

* [oguri](https://github.com/vilhalmer/oguri) - A very nice animated wallpaper daemon for Wayland compositors
* [mpvpaper](https://github.com/GhostNaN/mpvpaper) - A video wallpaper program for wlroots based wayland compositors
* [swaybg](https://github.com/swaywm/swaybg) - A wallpaper utility for Wayland compositors
* [Wallutils](https://github.com/xyproto/wallutils) - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
