# Auralo Drip downloads

Installers for **Auralo Drip**, the desktop water buddy from Auralo, on Windows and Linux.
Get them at **https://drip.auralo.fit**, or from the [latest release](../../releases/latest).

| File | For |
|---|---|
| `AuraloDrip-Setup.exe` | Windows 10 and 11 (installer) |
| `AuraloDrip.msi` | Windows (MSI, for managed installs) |
| `auralo-drip_amd64.deb` / `auralo-drip_arm64.deb` | Ubuntu, Debian, Mint, Pop!_OS |
| `auralo-drip.x86_64.rpm` / `auralo-drip.aarch64.rpm` | Fedora, openSUSE, RHEL |
| `AuraloDrip.flatpak` | Any Linux distribution with Flatpak (x86_64): `flatpak install --user AuraloDrip.flatpak` |
| `AuraloDrip.AppImage` / `AuraloDrip-aarch64.AppImage` | Any Linux distribution, nothing to install: `chmod +x` and run |
| `auralo-drip_x86_64.tar.gz` / `auralo-drip_aarch64.tar.gz` | Anything else: unpack and run `usr/bin/auralo-drip` (needs WebKitGTK 4.1) |

Arch Linux: download `PKGBUILD` and run `makepkg -si` in the same folder. (On the AUR as `auralo-drip-bin` once AUR registration reopens.)

Each release lists SHA-256 checksums in `SHA256SUMS.txt`. Releases are published automatically by the build.
