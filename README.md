# ChromeOS theme

ChromeOS is a [Material Design](https://material.io) theme for GNOME/GTK based desktop environments.

## Requirements

- GTK `>=3.20`
- `gnome-themes-extra` (or `gnome-themes-standard`)
- Murrine engine — The package name depends on the distro.
  - `gtk-engine-murrine` on Arch Linux
  - `gtk-murrine-engine` on Fedora
  - `gtk2-engine-murrine` on openSUSE
  - `gtk2-engines-murrine` on Debian, Ubuntu, etc.
- `bc` — build dependency

## Installation

### Manual Installation

Run the following commands in the terminal:

```sh
./install.sh
```

> Tip: `./install.sh` allows the following options:

```
-d, --dest DIR          Specify destination directory (Default: /usr/share/themes)
-n, --name NAME         Specify theme name (Default: Materia)
-c, --color VARIANT...  Specify color variant(s) [standard|dark|light] (Default: All variants)
-s, --size VARIANT      Specify size variant [standard|compact] (Default: All variants)
-g, --gdm               Install and apply GDM theme (for advanced users)
-h, --help              Show help
```

> For more information, run: `./install.sh --help`

