# Flatpak for BreakTimer

## Install

```
flatpak install flathub org.freedesktop.Sdk//26.08 org.electronjs.Electron2.BaseApp//26.08 org.freedesktop.Sdk.Extension.node22//26.08
flatpak-builder --user --install --default-branch stable --force-clean --sandbox build-dir app.breaktimer.BreakTimer.yaml
```
