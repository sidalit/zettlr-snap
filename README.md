<div align="center">

<img src="snap/gui/zettlr.png" alt="Zettlr logo" width="128" />

# Zettlr

**Markdown editor and publication workbench for academic writing**

[![zettlr](https://snapcraft.io/zettlr/badge.svg)](https://snapcraft.io/zettlr)
[![Base: core26](https://img.shields.io/badge/Base-core26-2C8C3C?logo=canonical&logoColor=white)](https://snapcraft.io/core26)
![Confinement: strict](https://img.shields.io/badge/Confinement-strict-2C8C3C)
[![Maintainer: sidaliteir](https://img.shields.io/badge/Maintainer-sidaliteir-2C8C3C?logo=snapcraft&logoColor=white)](https://snapcraft.io/publisher/sidaliteir)
![Architectures: amd64 and arm64](https://img.shields.io/badge/Architectures-amd64%20%7C%20arm64-2C8C3C?logo=linux&logoColor=white)

[Getting Started](#getting-started) · [Configure](#configure) · [Limitations](#limitations) · [Build](#build) · [Support](#support) · [License](#license)

Unofficial snap packaging for [Zettlr](https://github.com/Zettlr/Zettlr), a Markdown editor for notes, Zettelkasten and academic writing.

</div>

---

## Getting Started

<a href="https://snapcraft.io/zettlr"><img alt="Get it from the Snap Store" src="https://snapcraft.io/en/dark/install.svg" width="180"></a>

```bash
sudo snap install zettlr
zettlr
```

## Configure

Use the application's preferences. There are no `snap set` options.

```bash
sudo snap connect zettlr:removable-media    # optional: workspaces on /media, /mnt
```

## Limitations

- Notes, citation libraries and attachments must be in your home directory or on connected removable storage. Hidden folders in your home directory are not accessible.
- Application updates are managed by snapd, and the update check is disabled.

## Build

```bash
git clone https://github.com/sidalit/zettlr-snap.git
cd zettlr-snap
sudo snap install snapcraft --classic
snapcraft pack
```

## Support

- **Installation or snap issues:** [open a packaging issue](https://github.com/sidalit/zettlr-snap/issues).
- **Application bugs:** [report them upstream](https://github.com/Zettlr/Zettlr/issues).

## License

Snap packaging: [MIT](https://github.com/sidalit/zettlr-snap/blob/main/LICENSE).
