cinnamon-switcher
=================

Description: Allows application switching for the Cinnamon desktop shell similar to the Super+# key bindings in Ubuntu Unity. It does the application switching based on what's in your favorite applications panel within the Cinnamon menu. Application 1 corresponds to the top favorite, application 2 to the next favorite down, etc.

License: GPLv3

Requires: xdotool (Available in the Linux Mint 11, 12 and 13 reporitories)

Installation: Download and put the cinnamon-switcher script somewhere in the PATH. /usr/local/bin is a good choice since it's accessible to other users.

Useage: You can tie this script to a hotkey combo in keyboard preferences, and then pass it the number of the application to launch or switch to. For example, you could bind Ctrl+1 to 'cinnamon-switcher.sh 1'. Then every time you press the Ctrl and 1 keys the first (top) application in the favorites menu panel will be launched if it's not running, or switched to if it is.
