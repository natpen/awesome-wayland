# Awesome Wayland

A curated list of [Wayland](https://gitlab.freedesktop.org/wayland/wayland) code and resources.

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

  - [Break Notifiers](#break-notifiers)
  - [Brightness Control](#brightness-control)
  - [Browsers Without X Library Dependency](#browsers-without-x-library-dependency)
  - [Clipboard Managers](#clipboard-managers)
  - [Compositors](#compositors)
  - [Display Configuration](#display-configuration)
  - [Email Clients](#email-clients)
  - [Emulation](#emulation)
  - [IM](#im)
  - [Image Viewers](#image-viewers)
  - [Key Binding Management](#key-binding-management)
  - [Launchers](#launchers)
  - [Libraries](#libraries)
  - [Music Players](#music-players)
  - [Notifications](#notifications)
  - [On-screen Keyboards](#on-screen-keyboards)
  - [PDF Viewers](#pdf-viewers)
  - [Screen Locking](#screen-locking)
  - [Screencasting](#screencasting)
  - [Screenshots](#screenshots)
  - [Session Management](#session-management)
  - [Status Bars](#status-bars)
  - [Subtitle Editors](#subtitle-editors)
  - [Terminal Emulators](#terminal-emulators)
  - [Text Editors](#text-editors)
  - [Tools](#tools)
  - [Video Players](#video-players)
  - [Wallpaper](#wallpaper)
  - [License](#license)

## Break Notifiers

* [Ianny](https://github.com/zer0-x/ianny) - Periodically informes user to take breaks by keeping track of usage patterns

## Brightness Control

No Wayland-specific requirements, so you can use your xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl), [brillo](https://gitlab.com/cameronnemo/brillo), [light](https://github.com/haikarainen/light), or just directly manipulate `/sys/class/backlight`.

* [Gammastep](https://gitlab.com/chinstrap/gammastep) - Day/night gamma modifier that adjusts the color temperature of your screen.
* [Wlsunset](https://sr.ht/~kennylevinsen/wlsunset/) - Day/night gamma adjustments for Wayland compositors supporting wlr-gamma-control-unstable-v1
* [Clight](https://github.com/FedeDP/Clight) - Day/night gamma adjustments for Wayland compositors supporting wlr-gamma-control-unstable-v1; automatic screen backlight calibration to match ambient brightness using either webcam or ambient light sensor devices; screen dimming.

## Browsers without X library dependency
* Firefox and forks
    * [Firefox](https://www.mozilla.org/en-US/firefox/new/) - For using Firefox on wayland just add `MOZ_ENABLE_WAYLAND=1` to your environment variables
    * [Librewolf](https://librewolf.net/) - An independent fork of Firefox, with the primary goals of privacy, security and user freedom
    * [Tor Browser](https://www.torproject.org/download/) - Tor Browser Bundle: anonymous browsing using Firefox and Tor 

* QtWebEngine
    * [Crusta](https://github.com/Tarptaeya/Crusta) - Fast, modern and minimal desktop web browser with rich features
    * [Dooble](https://textbrowser.github.io/dooble/) - The weather bug browser. Minimal, cute, and unusually stable
    * [Falkon](https://www.falkon.org/) - KDE web browser
    * [Viper Browser](https://github.com/LeFroid/Viper-Browser) - A lightweight browser using QtWebEngine
    * [Qutebrowser](https://www.qutebrowser.org) - a keyboard-focused browser with a minimal GUI

* WebKit2GTK
    * [Surfer](https://github.com/nihilowy/surfer) - Simple keyboard based webkit2gtk browser
    * [wyeb](https://github.com/jun7/wyeb) - A vim-like webkit2gtk browser

## Clipboard Managers

* [clipman](https://github.com/yory8/clipman) - A simple clipboard manager for Wayland
* [copyq](https://hluk.github.io/CopyQ/) - CopyQ is an advanced clipboard manager with editing and scripting features.
* [wayclip](https://github.com/noocsharp/wayclip) -  Wayland clipboard utility 
* [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command-line copy/paste utilities for Wayland

## Compositors

* [Cagebreak](https://github.com/project-repo/cagebreak) - A Wayland tiling compositor inspired by Ratpoison
* [Cardboard](https://gitlab.com/cardboardwm/cardboard) - A scrollable tiling Wayland compositor
* [dwl](https://github.com/djpohly/dwl) - A rewrite of DWM for Wayland
* [hikari](https://hikari.acmelabs.space/) - A hybrid stacking/tiling Wayland compositor
* [Hyprland](https://github.com/vaxerski/Hyprland/) - Hyprland is a dynamic tiling Wayland compositor that doesn't sacrifice on its looks.
* [japokwm](https://github.com/werererer/japokwm) - A wlroots based dynamic tiling wayland compositor based around creating layouts
* [Kiwmi](https://github.com/buffet/kiwmi) - A fully programmable Wayland compositor
* [KWin](https://invent.kde.org/plasma/kwin) - KDE window manager and compositor
* [labwc](https://github.com/labwc/labwc) - A stacking Wayland compositor with look and feel of openbox
* [Mutter](https://wiki.gnome.org/Projects/Mutter/) - A window and compositing manager that displays and manages your desktop via OpenGL
* [newm](https://github.com/jbuchermn/newm) - A Wayland compositor written with laptops and touchpads in mind
* [river](https://github.com/ifreund/river) - A dynamic tiling Wayland compositor
* [Sway](https://github.com/swaywm/sway) - i3-compatible Wayland compositor
* [tinywl+](https://github.com/keshto/tinywl_plus) - A stacking wayland compositor based on tinywl. Great starting place for compositor development.
* [Velox](https://github.com/michaelforney/velox) - Velox is a simple window manager based on swc, inspired by dwm and xmonad
* [Vivarium](https://github.com/inclement/vivarium) - A dynamic tiling Wayland compositor using wlroots, with desktop semantics inspired by xmonad
* [Waybox](https://github.com/wizbright/waybox) - An openbox clone on Wayland
* [Wayfire](https://github.com/WayfireWM/wayfire) - 3D Wayland compositor
* [Weston](https://gitlab.freedesktop.org/wayland/weston/) - Reference compositor for Wayland
* [Qtile](https://github.com/qtile/qtile) - A full-featured, hackable tiling window manager written and configured in Python, [now supports wayland](https://mcol.xyz/2021/08/qtile-a-wayland-compositor.html)

## Display Configuration

* [Disman](https://gitlab.com/kwinft/disman) - General screen management software for different compositors based on KScreen
* [Kanshi](https://git.sr.ht/~emersion/kanshi) - Dynamic display configuration
* [KScreen](https://invent.kde.org/plasma/kscreen) - KDE's screen management software
* [kscreen-doctor](https://invent.kde.org/plasma/libkscreen) - An xrandr-like utility for Plasma
* [swaymsg](https://github.com/swaywm/sway) - General settings utility for Sway that also manages displays
* [Wallutils](https://github.com/xyproto/wallutils) - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers
* [wayout](https://git.sr.ht/~shinyzenith/wayout) - A Simple tool to set output modes for wlroots compositors implementing zwlr_output_power_management_v1
* [wdisplays](https://github.com/artizirk/wdisplays) - GUI display configurator for wlroots compositors
* [wlay](https://github.com/atx/wlay) - Graphical output management for Wayland
* [wlopm](https://git.sr.ht/~leon_plickat/wlopm) - Wayland output power management tool
* [wlr-randr](https://sr.ht/~emersion/wlr-randr/) - An xrandr clone for wlroots compositors

## Email Clients

* [KMail](https://invent.kde.org/pim/kmail) - Feature-rich email client that supports many protocols
* [Thunderbird](https://www.thunderbird.net/) - Standalone mail and news reader from mozilla.org

## Emulation

* [Waydroid](https://waydro.id/) - A container-based approach to boot a full Android system on GNU/Linux

## IM

* [Neochat](https://invent.kde.org/network/neochat) - A Matrix client made with Kirigami
* [Ruqola](https://invent.kde.org/network/ruqola) - A Rocket.Chat client made with QtQuick/QML

## Image Viewers

* [Gwenview](https://invent.kde.org/graphics/gwenview) - Image viewer by KDE
* [imv](https://github.com/eXeC64/imv) - A command line image viewer for X11/Wayland
* [Koko](https://invent.kde.org/graphics/koko) - Image viewer for desktop and mobile
* [mvi](https://github.com/occivink/mpv-image-viewer) - A command line image viewer utilizing mpv
* [Pix](https://invent.kde.org/maui/pix) - Maui's image viewer for desktop and mobile
* [Swayimg](https://github.com/artemsen/swayimg) -  Image viewer for Sway/Wayland
* [vimiv](https://karlch.github.io/vimiv/) - An image viewer with vim-like keybindings

## Key Binding Management

* [keyd](https://github.com/rvaiya/keyd) - System-wide daemon to remap keys using kernel input primitives (evdev, uinput)
* [swhkd](https://github.com/waycrate/swhkd/) - A display protocol-independent hotkey daemon

## Launchers

* [albert](https://github.com/albertlauncher/albert) - A fast and flexible keyboard launcher 
* [bemenu](https://github.com/Cloudef/bemenu) - Dynamic menu library and client program inspired by dmenu
* [dmenu-wayland](https://github.com/nyyManni/dmenu-wayland) - dmenu-wl is an efficient dynamic menu for wayland (wlroots)
* [fuzzel](https://codeberg.org/dnkl/fuzzel) - Application launcher for wlroots based Wayland compositors, similar to rofi's `drun` mode
* [kickoff](https://github.com/j0ru/kickoff) - Application launcher with a focus on snappyness
* [KRunner](https://invent.kde.org/frameworks/krunner) - Application launcher for Plasma
* [LavaLauncher](https://git.sr.ht/~leon_plickat/lavalauncher) - A simple launcher panel for Wayland desktops
* [Mauncher](https://github.com/mortie/mauncher) - A GTK-based alternative to dmenu for Wayland which supports display scaling
* [nwg-launchers](https://github.com/nwg-piotr/nwg-launchers) - A GTK-based application grid launcher, button bar and dmenu for Wayland
* [sirula](https://github.com/DorianRudolph/sirula) - Simple app launcher for Wayland written in Rust
* [wldash](https://github.com/kennylevinsen/wldash) - Wayland dashboard and launcher written in Rust
* [Wofi](https://hg.sr.ht/~scoopta/wofi) - A launcher/menu program for wlroots based Wayland compositors such as sway
* [yofi](https://github.com/l4l/yofi) - A minimalistic menu for wayland
* [rofi](https://github.com/lbonn/rofi) - A fork of rofi with Wayland support
* [tofi](https://github.com/philj56/tofi) - Tiny dynamic menu for Wayland

## Libraries

* [client toolkit](https://github.com/Smithay/client-toolkit) - A toolkit for writing Wayland clients in Rust
* [Mir](https://github.com/MirServer/mir) - Mir is set of libraries for building Wayland based shells
* [smithay](https://github.com/Smithay/smithay) - A modular smithy for making Wayland compositors in Rust
* [swc](https://github.com/michaelforney/swc) - A library for making a simple Wayland compositor
* [wld](https://github.com/michaelforney/wld) - A primitive drawing library targeted at Wayland
* [wlroots](https://github.com/swaywm/wlroots) - Pluggable, composable, unopinionated modules for building a Wayland compositor

## Music Players

* [Elisa](https://invent.kde.org/multimedia/elisa) - A music player that is simple, reliable, and a joy to use
* [vvave](https://invent.kde.org/maui/vvave) - Maui's music player for desktop and mobile

## Notifications

* [avizo](https://github.com/misterdanb/avizo) - Simple notification daemon, mainly intended to be used for multimedia keys
* [fnott](https://codeberg.org/dnkl/fnott) - Keyboard driven and lightweight Wayland notification daemon for wlroots-based compositors
* [Mako](https://github.com/emersion/mako) - A lightweight Wayland notification daemon
* [dunst](https://github.com/dunst-project/dunst) - A highly configurable and lightweight notification daemon
* [swaync](https://github.com/ErikReider/SwayNotificationCenter) - A simple notification daemon with a GTK gui for notifications and the control center
* [wob](https://github.com/francma/wob) - A lightweight overlay volume/backlight/progress/anything bar for Wayland

## On-screen Keyboards

* [wf-osk](https://github.com/WayfireWM/wf-osk) - A very, very basic on-screen keyboard using gtkmm, virtual-keyboard-v1 and layer-shell protocols 

## PDF Viewers

* [Okular](https://invent.kde.org/graphics/okular) - KDE Document Viewer
* [zathura](https://git.pwmt.org/pwmt/zathura) - A document viewer

## Screen Locking

* [gtklock](https://github.com/jovanlanik/gtklock) - GTK-based lockscreen for Wayland
* [swayidle](https://github.com/swaywm/swayidle) - Idle management daemon for Wayland
* [swaylock](https://github.com/swaywm/swaylock) - Screen locker for Wayland
* [swaylock-effects](https://github.com/mortie/swaylock-effects) - A fork of swaylock with effects such as a blurred screenshot as background or a clock on the lockscreen
* [waylock](https://github.com/ifreund/waylock) - A simple screenlocker for Wayland compositors

## Screencasting

* [GNOME ScreenCast](https://gitlab.gnome.org/GNOME/mutter) - GNOME's default screen recorder embedded in Mutter
* [Green Recorder](https://github.com/mhsabbagh/green-recorder) - Screen recorder for GNOME (unmaintained!)
* [Kooha](https://github.com/SeaDve/Kooha) - Minimalistic screen recorder for GNOME and Plasma using the xdg-desktop-portal ScreenCast protocol
* [OBS Studio](https://github.com/obsproject/obs-studio) - Compositor-independent screen recorder with support for v4l2loopback
* [Peek](https://github.com/phw/peek) - An animated gif recorder for GNOME
* [RecApp](https://github.com/amikha1lov/RecApp) - Simple screen recorder for GNOME
* [ssr-wlroots](https://github.com/foxcpp/ssr-wlroots) - A version of SimpleScreenRecorder with support for `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`) - doesn't support recording area selection and has issues with multiple screens
* [wayfarer](https://github.com/stronnag/wayfarer) - Screen recorder for GNOME
* [wayrec](https://invent.kde.org/bharadwaj-raju/wayrec) - Experimental screen recorder for Wayland using the freedesktop ScreenCast portal
* [wf-recorder](https://github.com/ammen99/wf-recorder) - A utility program for screen recording of `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`)
* [wlrobs](https://hg.sr.ht/~scoopta/wlrobs) - An obs-studio plugin that allows you to screen capture on wlroots based wayland compositors
* [wshowkeys](https://git.sr.ht/~sircmpwn/wshowkeys) - Displays keys being pressed on a Wayland session

## Screenshots

* [Flameshot](https://github.com/flameshot-org/flameshot) - Powerful yet simple to use screenshot software (requires [grim](https://github.com/emersion/grim) on wlroots)
* [Grim](https://github.com/emersion/grim) - Grab images from a Wayland compositor
* [ksnip](https://github.com/ksnip/ksnip) - ksnip the cross-platform screenshot and annotation tool 
* [Shotman](https://git.sr.ht/~whynothugo/shotman) - Uncompromising screenshot GUI for Wayland compositors
* [Slurp](https://github.com/emersion/slurp) - Select a region in a Wayland compositor
* [Spectacle](https://invent.kde.org/graphics/spectacle) - GUI application for capturing screenshots
* [Swappy](https://github.com/jtheoof/swappy) - A Wayland-native snapshot editing tool, inspired by Snappy on macOS
* [Wayshot](https://git.sr.ht/~shinyzenith/wayshot) - A screenshot tool for wlroots compositors implementing zwlr_screencopy_v1.
* [Weye](https://github.com/Yakkhini/Weye) - A lightweight screenshot tool for sway users, written in Rust. This tool uses grimshot commands to screenshot

## Session Management

* [wlogout](https://github.com/ArtsyMacaw/wlogout) - A Wayland-based logout menu

## Status Bars

* [i3status-rust](https://github.com/greshake/i3status-rust) - Very resource-friendly and feature-rich replacement for i3status, written in pure Rust
* [rootbar](https://hg.sr.ht/~scoopta/rootbar) - Root Bar is a bar for wlroots based Wayland compositors such as sway
* [sfwbar](https://github.com/LBCrion/sfwbar) - Sway Floating Window Bar is a taskbar for Sway, focused on a stacking layout workflow
* [waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors
* [yambar](https://codeberg.org/dnkl/yambar) - Modular status panel for X11 and Wayland, inspired by polybar

## Subtitle Editors

* [Subtitle Composer](https://invent.kde.org/multimedia/subtitlecomposer) - Current git builds include an ffmpeg-based video player fully Wayland native

## Terminal Emulators

* [Alacritty](https://github.com/alacritty/alacritty) - A cross-platform, GPU-accelerated terminal emulator
* [Ate](https://github.com/andir/ate) - Awesome terminal emulator
* [Foot](https://codeberg.org/dnkl/foot) - A fast, lightweight and minimalistic Wayland terminal emulator
* [Germinal](https://github.com/Keruspe/Germinal) - Minimalist vte-based terminal emulator
* [GNOME Terminal](https://wiki.gnome.org/Apps/Terminal) - A terminal emulator for GNOME
* [Havoc](https://github.com/ii8/havoc) - A minimal terminal emulator for Wayland
* [Kitty](https://github.com/kovidgoyal/kitty) - A cross-platform, fast, feature-full, GPU-based terminal emulator
* [Konsole](https://invent.kde.org/utilities/konsole) - Terminal emulator by KDE
* [Termite](https://github.com/thestinger/termite) - A keyboard-centric VTE-based terminal, aimed at use within a window manager with tiling and/or tabbing support (Termite is obsoleted by Alacritty!)
* [wezterm](https://wezfurlong.org/wezterm/) - A GPU-accelerated cross-platform terminal emulator and multiplexer
* [wterm](https://github.com/majestrate/wterm) - An [st](https://st.suckless.org/) fork for wayland
* [Xfce Terminal](https://docs.xfce.org/apps/terminal/start) - A graphically-configurable terminal for Xfce

## Text Editors

* [Kate](https://invent.kde.org/utilities/kate) - Modern text editor built on the KDE Frameworks and Qt
* [KWrite](https://invent.kde.org/utilities/kate) - Simple notepad-like editor based on Kate
* [Nota](https://invent.kde.org/maui/nota) - Maui's simple text editor for desktop and mobile

## Tools

* [lswt](https://git.sr.ht/~leon_plickat/lswt) - List Wayland toplevels in both human readable and machine parsable formats
* [waylevel](https://git.sr.ht/~shinyzenith/waylevel) - A simple debugging tool which lists compositor specific information.
* [wev](https://git.sr.ht/~sircmpwn/wev) - A tool for debugging events on a Wayland window, analogous to the X11 tool xev
* [wtype](https://github.com/atx/wtype) - A Wayland tool that allows you to simulate keyboard input like [xdotool](https://github.com/jordansissel/xdotool)
* [ydotool](https://github.com/ReimuNotMoe/ydotool) - A generic Linux command-line automation tool for Wayland

## Video Players

* [Haruna](https://invent.kde.org/multimedia/haruna) - Video player built with Qt/QML and libmpv
* [mpv](https://github.com/mpv-player/mpv) - Command line video player

## Wallpaper

* [oguri](https://github.com/vilhalmer/oguri) - A very nice animated wallpaper daemon for Wayland compositors
* [mpvpaper](https://github.com/GhostNaN/mpvpaper) - A video wallpaper program for wlroots based wayland compositors
* [plasma-apply-wallpaperimage](https://invent.kde.org/plasma/plasma-workspace) - A terminal utility to change wallpaper on Plasma
* [swaybg](https://github.com/swaywm/swaybg) - A wallpaper utility for Wayland compositors
* [swww](https://github.com/Horus645/swww) - A Solution to your Wayland Wallpaper Woes
* [Wallutils](https://github.com/xyproto/wallutils) - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers
* [wpaperd](https://github.com/danyspin97/wpaperd) - Wallpaper daemon that shows random wallpapers from a directory and changes them after some time
* [wbg](https://codeberg.org/dnkl/wbg) - Super simple wallpaper application for Wayland compositors

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
