Spin Goals
===

* tiling window manager by default
* convenience integrations on par with gnome spin (eg laptop buttons, network manager, etc)
* targeted at minimal computing environments
* sensible defaults

***

Which wm?
-
 * i3
 * i3-gaps (?) (is that still a thing?)
 * xmonad

Integrations
-
 * laptop buttons
 * some kind of hotkey configuration? (having to edit a text file to set keybindings is kind of a drag for novice users)
 * some sort of minimal window panel
  * dzen2?
  * not sure what Manjaro i3 uses but it does work well and worth looking into

Defaults
-
* terminal
* launcher
 * dmenu?
 * Rofi? (it's really cool!)
* gui network manager
 * Yes, please! This is the biggest reason I cannot use i3 on Fedora at the moment: Setting up networking just too difficult for me; I use Manjaro i3 primarily because it comes with a minimal taskbar already configured for basic functions like sound control, network management, clipboard management, etc.
* gui audio interface
* firefox
* mousepad text editor (?)
 * know it's from XFCE, but Bryan uses this on Manjaro i3 because it allows hiding of the menubar for frame-only text editing window (bliss)
* Suggestions CLI applications pre-installed
 * abcde (audio extractor if people want this? It rocks)
 * w3m (best-in-class CLI browsing!)
 * nano (curses-based text editing)
 * irssi (IRC? necessary?)
 * newsboat (CLI RSS and a daily go-to for Bryan)
 * midnight commander (file management at terminal—can access remote systems via SSH and SFTP)
 * cmus (best CLI music manager and player!)
 * moc (people tend to like this CLI music manager/player but I think cmus is better)
 * wordgrinder (CLI word processor and the very best one at that)

Design Inspirations
---
* Current Fedora recommendations
 * Fedora Magazine offers this tutorial for installing and configuring i3, but the result is fairly barebones and lacks polish; still useful however for seeing the settings and applications the author recommends
* Regolith Linux
 * Seems close to Michael's vision for this Fedora spin (robust GNOME base with tiling wm on top, sane defaults, neat customizations like a launcher and color-coded desktops), but almost appears too bloated (all the GNOME software is there on fresh install) and maybe a little too resource intensive; it's simply built on Ubuntu; lots of neat little enhancement here (keybindings are custom and very straightforward, for example, in well-commented i3 config file)
* Manjaro i3
 * Much more minimal implementation; some of the defaults are questionable (Pale Moon browser? The GIMP by default?), but it's closer to the minimalistic implementation that Michael describes; built on Arch as base so pretty overwhelming to non-technical users (says this non-technical user!); uses Ranger file manager (did not like; installed midnight commander immediately)
* Gnome Material Shell
 * Looks like an attempt to introduce tiling into Gnome via plugin/extension

