# Install prerequisites
```
flatpak install --user flathub org.freedesktop.Platform//24.08 org.freedesktop.Sdk//24.08 flathub org.flatpak.Builder
```

# Build and install (using the flatpak version of flatpak-builder)
```
flatpak run org.flatpak.Builder --disable-rofiles-fuse --force-clean build-dir com.realvnc.viewer.yml
flatpak run org.flatpak.Builder --user --install --force-clean build-dir com.realvnc.viewer.yml
```
