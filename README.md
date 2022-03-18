# Arch Packages

A list of recommendations for Arch Linux packages I find useful. For general instructions on how to set up a new Arch installation, see [the wiki's installation guide](https://wiki.archlinux.org/title/installation_guide).

## Useful Commands

- `pacstrap [root] [pkgs...]` (Install packages into new root)
- `pacman -S [pkgs...]` (Install packages)
- `pacman -Syu` (Update everything)
- `pacman -Q` (List installed packages)
- `pacman -Ql [pkg]` (List files in a package)
- `pacman -Qo [pkg]` (Find out which package owns a file)

## System

Packages for every Arch installation.

- [`base`](https://archlinux.org/packages/core/any/base/) (Basic Utilities)
- [`linux`](https://archlinux.org/packages/core/x86_64/linux/) (Kernel)
- [`linux-firmware`](https://archlinux.org/packages/core/any/linux-firmware/) (Firmware)
- [`grub`](https://archlinux.org/packages/core/x86_64/grub/) (Bootloader)
- [`networkmanager`](https://archlinux.org/packages/extra/x86_64/networkmanager/) (Networking)

## Essential

- [`vim`](https://archlinux.org/packages/extra/x86_64/vim/) (Text Editor)
- [`git`](https://archlinux.org/packages/extra/x86_64/git/) (Version Control)
- [`tmux`](https://archlinux.org/packages/community/x86_64/tmux/) (Terminal Multiplexer)
- [`htop`](https://archlinux.org/packages/extra/x86_64/htop/) (Process Manager)
- [`python`](https://archlinux.org/packages/core/x86_64/python/) (Scripting Language)
- [`sudo`](https://archlinux.org/packages/core/x86_64/sudo/) (Run as Root)
- [`zsh`](https://archlinux.org/packages/extra/x86_64/zsh/) (Shell)
- [`curl`](https://archlinux.org/packages/core/x86_64/curl/) (URL Downloader)
- [`less`](https://archlinux.org/packages/core/x86_64/less/) (Text Viewer)
- [`openssh`](https://archlinux.org/packages/core/x86_64/openssh/) (SSH client)
- [`avahi`](https://archlinux.org/packages/extra/x86_64/avahi/) (mDNS/DNS-SD/Bonjour stack)
- [`yay` (AUR)](https://aur.archlinux.org/packages/yay) (AUR helper)

## CLI Tools

- [`trash-cli`](https://archlinux.org/packages/community/any/trash-cli/) (Trash helper)
- [`tree`](https://archlinux.org/packages/extra/x86_64/tree/) (Directory listing)
- [`jq`](https://archlinux.org/packages/community/x86_64/jq/) (JSON processor)
- [`zip`](https://archlinux.org/packages/extra/x86_64/zip/) (ZIP archiver)
- [`unzip`](https://archlinux.org/packages/extra/x86_64/unzip/) (ZIP unarchiver)

## Development

- [`base-devel`](https://archlinux.org/groups/x86_64/base-devel/) (Basic Build Tools)
- [`visual-studio-code-bin` (AUR)](https://aur.archlinux.org/packages/visual-studio-code-bin) (Editor/IDE)
- [`clang`](https://archlinux.org/packages/extra/x86_64/clang/) (C/C++/ObjC Compiler)
- [`sqlite`](https://archlinux.org/packages/core/x86_64/sqlite/) (Embedded Database)
- [`ruby`](https://archlinux.org/packages/extra/x86_64/ruby/) (Scripting Language)
- [`rustup`](https://archlinux.org/packages/community/x86_64/rustup/) (Rust Toolchain Installer)
- [`stack`](https://archlinux.org/packages/community/x86_64/stack/) (Haskell Build Tool)
- [`swi-prolog`](https://archlinux.org/packages/community/x86_64/swi-prolog/) (Prolog Environment)

## Internet

- [`firefox`](https://archlinux.org/packages/extra/x86_64/firefox/) (Web Browser)
- [`thunderbird`](https://archlinux.org/packages/extra/x86_64/thunderbird/) (Mail Client)
- [`discord`](https://archlinux.org/packages/community/x86_64/discord/) (Voice and Text Chat)
- [`signal-desktop`](https://archlinux.org/packages/community/x86_64/signal-desktop/) (Messenger)
- [`mattermost-desktop-bin` (AUR)](https://aur.archlinux.org/packages/mattermost-desktop-bin) (Text Chat)
- [`zulip-desktop-bin` (AUR)](https://aur.archlinux.org/packages/zulip-desktop-bin) (Text Chat)

## Productivity

- [`texlive-most`](https://archlinux.org/groups/x86_64/texlive-most/) (LaTeX)
- [`libreoffice-fresh`](https://archlinux.org/packages/extra/x86_64/libreoffice-fresh/) (Office Suite)
- [`zotero` (AUR)](https://aur.archlinux.org/packages/zotero) (Bibliography Manager)

## Audio/Video

- [`pipewire`](https://archlinux.org/packages/extra/x86_64/pipewire/) (Audio processor/router)
- [`pipewire-pulse`](https://archlinux.org/packages/extra/x86_64/pipewire-pulse/) (PulseAudio replacement)
- [`pipewire-jack`](https://archlinux.org/packages/extra/x86_64/pipewire-jack/) (JACK replacement)
- [`vlc`](https://archlinux.org/packages/extra/x86_64/vlc/) (Multimedia player)
- [`mixxx`](https://archlinux.org/packages/community/x86_64/mixxx/) (DJing)
- [`spotify` (AUR)](https://aur.archlinux.org/packages/spotify) (Music streaming)
- [`audacity`](https://archlinux.org/packages/community/x86_64/audacity/) (Audio editor)
- [`ardour`](https://archlinux.org/packages/community/x86_64/ardour/) (DAW)
- [`kdenlive`](https://archlinux.org/packages/extra/x86_64/kdenlive/) (Video editor)

## Graphics

- [`gimp`](https://archlinux.org/packages/extra/x86_64/gimp/) (Image editor)
- [`inkscape`](https://archlinux.org/packages/extra/x86_64/inkscape/) (Vector graphics editor)

## Gaming

- [`steam`](https://archlinux.org/packages/multilib/x86_64/steam/) (Game Distribution Platform)
- [`multimc-bin` (AUR)](https://aur.archlinux.org/packages/multimc-bin) (Minecraft Launcher)
