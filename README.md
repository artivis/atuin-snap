# atuin-snap

The [Atuin](https://atuin.sh/) application packaged as a snap.

[![Get it from the Snap Store](https://snapcraft.io/en/dark/install.svg)](https://snapcraft.io/atuin)
[![atuin](https://snapcraft.io/atuin/badge.svg)](https://snapcraft.io/atuin)
[![atuin](https://snapcraft.io/atuin/trending.svg?name=0)](https://snapcraft.io/atuin)

> [!IMPORTANT]
> Due to Snap confinement, the 'scripts' functionality is **not** available.

## Install

To install the snap from the store:

```bash
snap install atuin
```

## Notes

For bash users, the Snap bundles both `ble.sh` & `bash-preexec`.
They can be found in `/snap/atuin/current/usr/share/`.

The Snap has only really been tested for bash.
Please do report any issue on the [GitHub repo](https://github.com/artivis/atuin-snap/issues).
Conversely, reports that the snap is working fine with other shells is appreciated.

## Development

Make sure that snapcraft is [installed and set up](https://snapcraft.io/docs/snapcraft-setup).

To build the snap use:

```bash
snapcraft pack
```

To install the locally built snap use:

```bash
snap install --dangerous atuin_*.snap
```
