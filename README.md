# PoktCode Releases

Public release artifacts for **PoktCode** (Flatpak / Linux binaries).

The application source code remains private. This repository only publishes packaged builds and AppStream screenshots used by Flathub.

## Install (sideload Flatpak)

```bash
flatpak install --user https://github.com/poktweb/poktcode-releases/releases/download/v0.1.0/PoktCode-0.1.0-linux-x86_64.flatpak
flatpak run com.poktweb.poktcode
```

## Flathub

Flatpak builds on Flathub download the `linux-unpacked` archive attached to each GitHub Release.
