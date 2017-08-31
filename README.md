Suru Icon Theme
================

Suru is a FreeDesktop icon theme whose design is based upon and around the original Suru icon guidelines for Ubuntu mobile applications.

Many of the original Ubuntu generic app icons and Unity8 symbolic icons have been repurposed for desktop use, however the icon set has extensive additions such as icons for folders, devices, file types, application categories, and other system toolbar and status icons.

## Notes

 - This set is designed for desktop environment coverage only, pull requests or issues regarding branded icons or theming third-party applications (for example, Firefox) will be rejected.
 - Any issues or pull requests regarding icons specifically for desktop environments, such as MATE, XFCE, etc., will be attended to as they come.
 - A theme that includes icons for third-party apps and branded icons is under development but is separate from this set.

## Copying or Reusing

This project is licenced under the terms of the [GNU General Public License, version 3](https://www.gnu.org/licenses/gpl-3.0.txt), so you are free to copy and reuse accordingly.

## Installing & Using

There are no official packages or releases (yet) but you can install this theme from source with the provided [Makefile](/Makefile) and a few commands.

First clone this repositoy and from the root directory, run `make install` to install Suru to your home folder or to install system-wide you can run `sudo make install-root`.

After which you should be able to choose the theme in a Tweak tool or set with:

    gsettings set org.gnome.desktop.interface icon-theme Suru
    
Uninstallation is as easy as `make uninstall` or `sudo make uninstall-root` depending on where you installed it.
