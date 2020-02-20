# ChromeOS theme

ChromeOS is a [Material Design](https://material.io) theme for GNOME/GTK based desktop environments.
Based on nana-4 -- [materia-theme](https://github.com/nana-4/materia-theme)

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
-n, --name NAME         Specify theme name (Default: ChromeOS)
-c, --color VARIANT...  Specify color variant(s) [standard|dark|light] (Default: All variants)
-s, --size VARIANT      Specify size variant [standard|compact] (Default: All variants)
-h, --help              Show help
```

> For more information, run: `./install.sh --help`

## Firefox theme
[Intall Firefox theme](src/firefox)

![01](src/firefox/preview01.png?raw=true)
![02](src/firefox/preview02.png?raw=true)

## Preview
![1](https://cdn.pling.com/img/9/2/b/e/0f3bbcad86f2b4baee71ca3f12117ebf4d5a.jpg?raw=true)
