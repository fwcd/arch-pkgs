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
- [`whois`](https://archlinux.org/packages/extra/x86_64/whois/) (Whois client)

## Development

- [`base-devel`](https://archlinux.org/groups/x86_64/base-devel/) (Basic Build Tools)
- [`visual-studio-code-bin` (AUR)](https://aur.archlinux.org/packages/visual-studio-code-bin) (Editor/IDE)
- [`cmake`](https://archlinux.org/packages/extra/x86_64/cmake/) (Meta Build Tool)
- [`ninja`](https://archlinux.org/packages/community/x86_64/ninja/) (Build System)
- [`clang`](https://archlinux.org/packages/extra/x86_64/clang/) (C/C++/ObjC Compiler)
- [`sqlite`](https://archlinux.org/packages/core/x86_64/sqlite/) (Embedded Database)
- [`nodejs`](https://archlinux.org/packages/community/x86_64/nodejs/) (JS runtime)
- [`npm`](https://archlinux.org/packages/community/any/npm/) (Node.js package manager)
- [`jdk-openjdk`](https://archlinux.org/packages/extra/x86_64/jdk-openjdk/) (Java)
- [`ruby`](https://archlinux.org/packages/extra/x86_64/ruby/) (Scripting Language)
- [`rustup`](https://archlinux.org/packages/community/x86_64/rustup/) (Rust Toolchain Installer)
- [`go`](https://archlinux.org/packages/community/x86_64/go/) (Go compiler)
- [`stack`](https://archlinux.org/packages/community/x86_64/stack/) (Haskell Build Tool)
- [`dotnet-sdk`](https://archlinux.org/packages/community/x86_64/dotnet-sdk/) (.NET Core)
- [`swi-prolog`](https://archlinux.org/packages/community/x86_64/swi-prolog/) (Prolog Environment)
- [`valgrind`](https://archlinux.org/packages/extra/x86_64/valgrind/) (Memory debugger)
- [`visualvm`](https://archlinux.org/packages/extra/x86_64/visualvm/) (JVM profiler)

## Containers

- [`podman`](https://archlinux.org/packages/community/x86_64/podman/) (OCI container runner)
- [`podman-compose`](https://archlinux.org/packages/community/any/podman-compose/) (Compose file runner)
- [`buildah`](https://archlinux.org/packages/community/x86_64/buildah/) (OCI container builder)
- [`kubectl`](https://archlinux.org/packages/community/x86_64/kubectl/) (Kubernetes API client)
- [`helm`](https://archlinux.org/packages/community/x86_64/helm/) (Kubernetes package manager)

## Sysadmin

- [`ansible`](https://archlinux.org/packages/community/any/ansible/) (IT automation, infrastructure as code)

## Server

- [`traefik`](https://archlinux.org/packages/community/x86_64/traefik/) (Reverse proxy)
- [`nginx`](https://archlinux.org/packages/extra/x86_64/nginx/) (Web server)
- [`samba`](https://archlinux.org/packages/extra/x86_64/samba/) (SMB server)

## Desktop

- [`xorg-server`](https://archlinux.org/packages/extra/x86_64/xorg-server/) (Display server)
- [`sddm`](https://archlinux.org/packages/extra/x86_64/sddm/) (Display manager)
- [`plasma`](https://archlinux.org/groups/x86_64/plasma/) (Desktop environment, KDE)
- [`kde-applications`](https://archlinux.org/groups/x86_64/kde-applications/) (Desktop apps, choose what you need)

## Daemons

- [`earlyoom`](https://archlinux.org/packages/community/x86_64/earlyoom/) (OOM daemon)
- [`cronie`](https://archlinux.org/packages/core/x86_64/cronie/) (Cron daemon)

## Internet

- [`firefox`](https://archlinux.org/packages/extra/x86_64/firefox/) (Web Browser)
- [`thunderbird`](https://archlinux.org/packages/extra/x86_64/thunderbird/) (Mail Client)
- [`discord`](https://archlinux.org/packages/community/x86_64/discord/) (Voice and Text Chat)
- [`signal-desktop`](https://archlinux.org/packages/community/x86_64/signal-desktop/) (Messenger)
- [`mattermost-desktop-bin` (AUR)](https://aur.archlinux.org/packages/mattermost-desktop-bin) (Text Chat)
- [`zulip-desktop-bin` (AUR)](https://aur.archlinux.org/packages/zulip-desktop-bin) (Text Chat)
- [`zoom` (AUR)](https://aur.archlinux.org/packages/zoom) (Video Conferencing)
- [`wireshark-qt`](https://archlinux.org/packages/community/x86_64/wireshark-qt/) (Traffic analyzer)

## Bluetooth

- [`bluez`](https://archlinux.org/packages/extra/x86_64/bluez/) (Bluetooth daemons)

## Productivity

- [`okular`](https://archlinux.org/packages/extra/x86_64/okular/) (Document Viewer)
- [`cups`](https://archlinux.org/packages/extra/x86_64/cups/) (Printing System)
- [`cups-pdf`](https://archlinux.org/packages/extra/x86_64/cups-pdf/) (PDF Printing)
- [`texlive-most`](https://archlinux.org/groups/x86_64/texlive-most/) (LaTeX)
- [`libreoffice-fresh`](https://archlinux.org/packages/extra/x86_64/libreoffice-fresh/) (Office Suite)
- [`zotero` (AUR)](https://aur.archlinux.org/packages/zotero) (Bibliography Manager)

## Fonts

- [`ttf-liberation`](https://archlinux.org/packages/community/any/ttf-liberation/) (Arial/Times New Roman/Courier New replacement)
- [`ttf-jetbrains-mono`](https://archlinux.org/packages/community/any/ttf-jetbrains-mono/) (Typeface for developers)
- [`ttf-font-awesome`](https://archlinux.org/packages/community/any/ttf-font-awesome/) (Icon font)

## Audio/Video

- [`pipewire`](https://archlinux.org/packages/extra/x86_64/pipewire/) (Audio processor/router)
- [`pipewire-pulse`](https://archlinux.org/packages/extra/x86_64/pipewire-pulse/) (PulseAudio replacement)
- [`pipewire-jack`](https://archlinux.org/packages/extra/x86_64/pipewire-jack/) (JACK replacement)
- [`helvum`](https://archlinux.org/packages/community/x86_64/helvum/) (PipeWire patchbay)
- [`ffmpeg`](https://archlinux.org/packages/extra/x86_64/ffmpeg/) (Audio/video converter)
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
