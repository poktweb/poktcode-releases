# PoktCode Releases

Public release artifacts for **PoktCode** (Flatpak / Linux binaries).

The application source code remains private. This repository only publishes packaged builds and AppStream screenshots used by Flathub.

## Install (sideload Flatpak)

```bash
curl -L -o PoktCode-0.1.0-linux-x86_64.flatpak \
  https://github.com/poktweb/poktcode-releases/raw/v0.1.0/dist/PoktCode-0.1.0-linux-x86_64.flatpak
flatpak install --user ./PoktCode-0.1.0-linux-x86_64.flatpak
flatpak run com.poktweb.poktcode
```

## Artifacts (v0.1.0)

| File | Purpose |
|------|---------|
| `dist/PoktCode-0.1.0-linux-x86_64.tar.xz` | `linux-unpacked` archive for Flathub builds |
| `dist/PoktCode-0.1.0-linux-x86_64.flatpak` | Sideloadable Flatpak bundle |
| `screenshots/*.png` | AppStream / Flathub screenshots |

## Flathub

Submission PR: https://github.com/flathub/flathub/pull/11051
