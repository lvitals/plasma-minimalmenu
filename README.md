# Minimal Menu

<p align="center">
    <img src="assets/0.1.0-crop.jpg" alt="Minimal menu image">
</p>

## A minimal application menu for KDE Plasma
This is a fork of <a href=https://github.com/KDE/plasma-simplemenu>Simple menu</a>.

### Install
Download and install using Plasma Add-On Installer:

Add Widgets... -> Get new widgets -> Download New Plasma Widgets

Then search for "Minimal Menu" and click install. Minimal Menu should then appear
in your installed widgets.

Alternatively download minimalmenu-<version>.plasmoid from
https://www.opendesktop.org/p/1275285/, and extract it (it's a zip file) to
$HOME/.local/share/plasma/plasmoids/com.gitlab.jnuutinen.minimalmenu.

## Known issues

### Application hiding
After selecting "Hide application" from an application's context menu, it will
remain visible. A workaround is to select "Edit application..." from the context
menu for any application after selecting "Hide application" for all the
applications you want to hide. Then in the dialog that opens just click "Ok",
and that should refresh the applications, and hide all applications that were
marked for hiding.
