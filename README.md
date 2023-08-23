# Flatpak manifest for TelloDesk

Manifest for building [fork of TelloDesk](https://github.com/Anty0/tellodesk) for Flatpak.
Made for Steam Deck.

## Build

``` sh
flatpak-builder --repo=repo --force-clean build-dir com.github.Anty0.tellodesk.yml
```

## Install

``` sh
flatpak --user remote-add --no-gpg-verify tellodesk-repo repo
flatpak --user install tellodesk-repo com.github.Anty0.tellodesk
```
