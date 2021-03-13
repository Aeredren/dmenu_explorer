## dmenu_explorer ##

A file explorer for dmenu.

Dependence :
Any Posix compliant shell
Base-utils
xdg-open to open files
dmenu

## CHANGELOG ##
0.1 :
	- Open selected file with xdg-open

0.2 :
	- Add commands
		'.' show / hide hidden files
		'\' enter explorer mode (dmenu_explore)
		':' enter command mode (dmenu_explorer_command)
	- Add commands mode
		First screen (red) : choose a command to run, eventually adding parameters and entering with 'shift + return'
		Second screen (blue): choose arguments for the command (multiple arguments can be specified with 'ctrl + return')
		'shift + control + return' is also working
	- Change behavior of ./ entry
		./ open the current directory with xdg-open in explorer mode
		./ add the current directory to command's arguments in command mode
	- Add GPLv3 licence

Open Bug / feature to develop :
	- Selecting multiple files in explorer mode does not open multiple files (crash)
		(Adapt some of the shenanigans in dmenu_explorer_command to achieve it)
	

~Aeredren
