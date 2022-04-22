![1](https://images.pling.com/img/00/00/32/24/44/1335019/a904f566f527ca301f475cce53c13e7c21c9.jpg)

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

## Install from Snap
<a href="https://snapcraft.io/chromeos-themes">
<img alt="Get it from the Snap Store" src="https://snapcraft.io/static/images/badges/en/snap-store-white.svg" />
</a>

You can install the theme from the Snap Store оr by running:

```
sudo snap install chromeos-themes
```
To connect the theme to an app run:
```
sudo snap connect [other snap]:gtk-3-themes chromeos-themes:gtk-3-themes
```

To connect the theme to all apps which have available plugs to gtk-common-themes you can run:

``` for i in $(snap connections | grep gtk-common-themes:gtk-3-themes | awk '{print $2}'); do sudo snap connect $i chromeos-themes:gtk-3-themes; done
```

## Firefox theme
[Intall Firefox theme](src/firefox)

![01](src/firefox/preview01.png?raw=true)
![02](src/firefox/preview02.png?raw=true)
