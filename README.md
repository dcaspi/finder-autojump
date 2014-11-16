finder-autojump
===============

Tiny automator scripts to add autojump support to OS X's Finder.app.

# Description
- Built on top of the great [autojump] module for the shell.
- Currently contains 2 scripts - `finder-autojump` and `finder-add-to-autojump`.
- `finder-autojump` shows a text box in which you can enter your query - part of the folder's name that you want to open in finder. It will then query `autojump` and will open that folder in Finder. As simple as that. The dialog also supports jumping to any folder by supplying its full path (not only folders known to autojump).
- `finder-add-to-autojump` adds the current Finder folder to autojump's db. This is done manually since (a) there's currently no way in OS X to add every folder visited by Finder to autojump's db and (b), even if there were one, I'm not sure it will be a good idea, since browsing unimportant folders through Finder seems more prevalent than through the terminal.

# Installation
1. Have [autojump] working on your mac.
2. Get the automator scripts, either by cloning this repository or by downloading its content as .zip file.
3. Double click both automator scripts to install them.
4. While both scripts could be launched from OS X's drop-down menus, it is highly recommended to set up a keyboard shortcut for them through `Settings` > `Keyboard` > `Shortcuts` > `Services`. Mine are ⌘+⌥ +⌃+g for jumping and ⌘+⌥ +⌃+a for adding.

# Usgae
Pretty simple - just hit your predefined keyboard shortcut to pop up the text box or add the current folder to autojump (or, if you're doing it wrong, use the drop-down menu).

**autojump in finder, Hell Yeah!**

[autojump]:https://github.com/joelthelion/autojump