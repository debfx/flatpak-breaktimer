# Flatpak for BreakTimer

## Install

```
flatpak install flathub org.freedesktop.Sdk//24.08 org.electronjs.Electron2.BaseApp//24.08 org.freedesktop.Sdk.Extension.node22//24.08
flatpak-builder --user --install --default-branch stable --force-clean build-dir --sandbox app.breaktimer.BreakTimer.yaml
```
