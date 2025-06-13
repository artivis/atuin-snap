# atuin-snap

The [Atuin](https://atuin.sh/) application packaged as a snap.

[![Get it from the Snap Store](https://snapcraft.io/en/dark/install.svg)](https://snapcraft.io/atuin)
[![atuin](https://snapcraft.io/atuin/badge.svg)](https://snapcraft.io/atuin)
[![atuin](https://snapcraft.io/atuin/trending.svg?name=0)](https://snapcraft.io/atuin)

## Install

To install the snap from the store:

```bash
snap install atuin
```

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
