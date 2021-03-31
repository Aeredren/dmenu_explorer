# dmenu_explorer

A file explorer for dmenu.

Dependencies :
- Any Posix compliant shell
- Base-utils
- xdg-open to open files
- dmenu

## 2 modes

- explorer mode
	- Open selected file with xdg-open
- commands mode
	- First screen (red) : choose a command to run, eventually adding parameters here
	- Second screen (blue): choose arguments for the command (multiple files from multiple directories can be specified)

## Shortcuts
- . -> show / hide hidden files
- \\ -> enter explorer mode (dmenu_explorer)
- : -> enter command mode (dmenu_explorer_command)

## Other

./ is always treated as a file. (Open with xdg-open in explorer mode, add to arguments in command mode)

To select multiple item use ctrl+return, to select what is in the input bar use shift+return. (See dmenu man page; ctrl+shift+return is also working)

Written in Posix compliant shell script - tested with dash and bash - GPLv3 licence

This is a micro file explorer which has been code for educational purpose. Nevertheless, it is working and feel free to use it if you like it.
It is now consider complete in term of feature. I'll be glad to include code improvement and bugfixes but nothing else.
For a more complete alternatives checkout dmenufm or terminal based file managers (lf, nnn, ranger, ...).

~Aeredren
