Old Menu - Classic Side-Menu
============================

Fixed Width Version, Menu on the left side for [owncloud](http://owncloud.org/).

Advantages compared to the default menu of owncloud / nextcloud are reduced clicks to open an application, as the sidebar is always visible on wide screens (wider than 1100px). Otherwise on smaller screens the standard drop-down menu is available. It lays the focus more on all installed apps and not only on the files app.

Forked by Michael Träger from https://github.com/SansPseudoFix/Old_menu. This version is without the tiny Icons (therefore normal sized) and with a fix max-width of 100px for the Menu. It looks like the original old menu.


## How to

* download zip
* go to /apps folder
* unzip
* change name to `old_menu`
* activate Old Menu

Alternative
* git clone this repo to /apps direcotry with `git clone https://github.com/mtraeger/own-nextcloud_old_menu.git old_menu`
* activate in app menu

## Complications

Problems could arise when using this app with the original old_menu app.

## Change Menu Color

For use with NextCloud-Blue use 
```
background-color: #0082c9; 
```
instead of `#1d2d44` for Owncloud.

You can remove this line also for dark grey.

## Possible Problems

On upgrades of owncloud / nextcloud the acces rights have to be correct. If you cloned or extracted with wrong user permissions, you have to chown (and maybe also chmod +w) the installation directory of this app.

## TODOs

* Change Name/AppID to old_menu_fixed
* Enable / Disable this feature in user settings 
* Change Color of sidebar in admin settings

