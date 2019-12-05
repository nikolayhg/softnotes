---
title: Ubuntu
date: {}
published: true
---

# Ubuntu Notes

## Shortcuts

* alt + \` (the key above Tab) - switch between instances of the current application

## Productivity

* [AutoKey](https://github.com/autokey/autokey) - desktop automation utility. Great for text autocompletion like `"brnn" -> "Best Regards, MyName"`

### Workspaces

Use workspaces for different contexts: work, private, etc.

* See your Keyboard shortcuts for moving windows to another workspace.
* Configure the Ubuntu Dock to show windows only from the current workspace:
 * run `gsettings set org.gnome.shell.extensions.dash-to-dock isolate-workspaces true`

## Screenshots

* [Shutter](https://shutter-project.org/) - install with Edit functionality from another PPA: https://www.linuxuprising.com/2018/10/shutter-removed-from-ubuntu-1810-and.html
  * Disadvantage: requires too many clicks for commonly used functionality
* [Flameshot](https://flameshot.js.org/) - has most functionalities, but [crashes after drawing text and saving as file](https://github.com/lupoDharkael/flameshot/issues/667).

## Editors

* [Sublime Text](https://www.sublimetext.com/) - layouts and full screen mode. Lots of packages
  - Packages: [Diagram](https://packagecontrol.io/packages/Diagram), [PlainTasks](https://packagecontrol.io/packages/PlainTasks)

## Issues

* Frozen:
  * single programm, mouse: https://askubuntu.com/a/4412
  * everything: https://askubuntu.com/a/36717 While holding `Alt` and the `SysReq (Print Screen)` keys, type slowly `REISUB`. Let a few seconds pass in between each keypress.

* File System read-only:
  * `sudo ntfsfix /dev/your_drive` and restart
