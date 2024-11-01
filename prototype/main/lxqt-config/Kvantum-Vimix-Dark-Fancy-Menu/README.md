

# Lxqt Config

* [Config File Path](#config-file-path)
* [Ubuntu Package](#ubuntu-package)
* [Usage](#usage)



## Explore

run

``` sh
apt-cache search aurorae
```

show

```
arc-kde - Port of the popular GTK theme Arc for Plasma 5
materia-kde - Port of the popular GTK theme Materia for Plasma 5
orchis-kde - Port of the popular GTK theme Orchis for Plasma
```




## Config File Path

* [lxqt](#lxqt)
* [kwin](#kwin)
* [kvantum](#kvantum)
* [Trolltech.conf](#trolltechconf)
* [gtk2](#gtk2)
* [gtk3](#gtk3)
* [default-cursor-theme](#default-cursor-theme)
* [mimeapps.list](#mimeappslist)
* [pcmanfm-qt](#pcmanfm-qt)
* [qterminal](#qterminal)
* [sakura](#sakura)
* [thunar](#thunar)
* [xfce4-terminal](#xfce4-terminal)




### lxqt

| Config File Path |
| --- |
| [~/.config/lxqt/globalkeyshortcuts.conf](./asset/overlay/etc/skel/.config/lxqt/globalkeyshortcuts.conf) |
| [~/.config/lxqt/lxqt.conf](./asset/overlay/etc/skel/.config/lxqt/lxqt.conf) |
| [~/.config/lxqt/lxqt-runner.conf](./asset/overlay/etc/skel/.config/lxqt/lxqt-runner.conf) |
| [~/.config/lxqt/panel.conf](./asset/overlay/etc/skel/.config/lxqt/panel.conf) |
| [~/.config/lxqt/session.conf](./asset/overlay/etc/skel/.config/lxqt/session.conf) |




### kwin

| Config File Path |
| --- |
| [~/.config/kwinrc](./asset/overlay/etc/skel/.config/kwinrc) |




### kvantum

| Config File Path |
| --- |
| [~/.config/Kvantum/kvantum.kvconfig](./asset/overlay/etc/skel/.config/Kvantum/kvantum.kvconfig) |




### Trolltech.conf

| Config File Path |
| --- |
| [~/.config/Trolltech.conf](./asset/overlay/etc/skel/.config/Trolltech.conf) |




### gtk2

| Config File Path |
| --- |
| [~/.gtkrc-2.0](./asset/overlay/etc/skel/.gtkrc-2.0) |




### gtk3

| Config File Path |
| --- |
| [~/.config/gtk-3.0/settings.ini](./asset/overlay/etc/skel/.config/gtk-3.0/settings.ini) |
| [~/.config/gtk-3.0/gtk.css](./asset/overlay/etc/skel/.config/gtk-3.0/gtk.css) |
| [~/.config/gtk-3.0/vte-terminal.css](./asset/overlay/etc/skel/.config/gtk-3.0/vte-terminal.css) |




### default-cursor-theme

| Config File Path |
| --- |
| [~/.icons/default/index.theme](./asset/overlay/etc/skel/.icons/default/index.theme) |




### mimeapps.list

| Config File Path |
| --- |
| [~/.config/mimeapps.list](./asset/overlay/etc/skel/.config/mimeapps.list) |




### pcmanfm-qt

| Config File Path |
| --- |
| [~/.config/pcmanfm-qt/default/settings.conf](./asset/overlay/etc/skel/.config/pcmanfm-qt/default/settings.conf) |




### qterminal

| Config File Path |
| --- |
| [~/.config/qterminal.org/qterminal.ini](./asset/overlay/etc/skel/.config/qterminal.org/qterminal.ini) |




### sakura

| Config File Path |
| --- |
| [~/.config/sakura/sakura.conf](./asset/overlay/etc/skel/.config/sakura/sakura.conf) |




### thunar

| Config File Path |
| --- |
| [~/.config/xfce4/xfconf/xfce-perchannel-xml/thunar.xml](./asset/overlay/etc/skel/.config/xfce4/xfconf/xfce-perchannel-xml/thunar.xml) |
| [~/.config/Thunar/uca.xml](./asset/overlay/etc/skel/.config/Thunar/uca.xml) |
| [~/.config/Thunar/accels.scm](./asset/overlay/etc/skel/..config/Thunar/accels.scm) |




### xfce4-terminal

| Config File Path |
| --- |
| [~/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-terminal.xml](./asset/overlay/etc/skel/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-terminal.xml) |
| [~/.config/xfce4/terminal/accels.scm](./asset/overlay/etc/skel/.config/xfce4/terminal/accels.scm) |




## Ubuntu Package

| Ubuntu Package |
| --- |
| [lxqt](https://packages.ubuntu.com/oracular/lxqt) |


| Ubuntu Package |
| --- |
| [kwin](https://packages.ubuntu.com/oracular/kwin) |
| [kwin-x11](https://packages.ubuntu.com/oracular/kwin-x11) |
| [kwin-common](https://packages.ubuntu.com/oracular/kwin-common) |
| [kwin-data](https://packages.ubuntu.com/oracular/kwin-data) |
| [kwin-addons](https://packages.ubuntu.com/oracular/kwin-addons) |
| [kwin-decoration-oxygen](https://packages.ubuntu.com/oracular/kwin-decoration-oxygen) |




## Usage


### install

run

``` sh
./install.sh
```

or run

``` sh
make install
```


### package-install

run

``` sh
./package-install.sh
```

or run

``` sh
make package-install
```


### asset-install

run

``` sh
./asset-install.sh
```

or run

``` sh
make asset-install
```


### config-install

run

``` sh
./config-install.sh
```

or run

``` sh
make config-install
```
