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
- [`curl`](https://archlinux.org/packages/core/x86_64/curl/) (URL downloader)

## Development

- [`base-devel`](https://archlinux.org/groups/x86_64/base-devel/) (Basic Build Tools)
- [`clang`](https://archlinux.org/packages/extra/x86_64/clang/) (C/C++/ObjC Compiler)
- [`rustup`](https://archlinux.org/packages/community/x86_64/rustup/) (Rust Toolchain Installer)
- [`stack`](https://archlinux.org/packages/community/x86_64/stack/) (Haskell Build Tool)
- [`swi-prolog`](https://archlinux.org/packages/community/x86_64/swi-prolog/) (Prolog)

## Internet

- [`firefox`](https://archlinux.org/packages/extra/x86_64/firefox/) (Web Browser)
- [`thunderbird`](https://archlinux.org/packages/extra/x86_64/thunderbird/) (Mail Client)
- [`discord`](https://archlinux.org/packages/community/x86_64/discord/) (Voice and Text Chat)
- [`signal-desktop`](https://archlinux.org/packages/community/x86_64/signal-desktop/) (Messenger)
- [`mattermost-desktop-bin` (AUR)](https://aur.archlinux.org/packages/mattermost-desktop-bin) (Text Chat)
- [`zulip-desktop-bin` (AUR)](https://aur.archlinux.org/packages/zulip-desktop-bin) (Text Chat)

## Audio

- [`pipewire`](https://archlinux.org/packages/extra/x86_64/pipewire/) (Audio processor/router)
- [`pipewire-pulse`](https://archlinux.org/packages/extra/x86_64/pipewire-pulse/) (PulseAudio replacement)
- [`pipewire-jack`](https://archlinux.org/packages/extra/x86_64/pipewire-jack/) (JACK replacement)
- [`vlc`](https://archlinux.org/packages/extra/x86_64/vlc/) (Multimedia player)
- [`mixxx`](https://archlinux.org/packages/community/x86_64/mixxx/) (DJing)
- [`spotify` (AUR)](https://aur.archlinux.org/packages/spotify) (Music streaming)
- [`audacity`](https://archlinux.org/packages/community/x86_64/audacity/) (Audio editor)
- [`ardour`](https://archlinux.org/packages/community/x86_64/ardour/) (DAW)
