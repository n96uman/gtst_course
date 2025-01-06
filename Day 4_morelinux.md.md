Topics
linux file heirarchy
vim
nano
linux user management
## LINUX FILE HEIRARCHY
DIRECTORY STRUCTURE .
### ==system file==
file that are used by the system.
linux: root directory (/)
1. /(root)
    every single file or directory start from root.
2. bin-BINARY Executables
3. /boot-boot loader files: necessary file for run.
4. /dev-essential device files: any device in to  file.
5. /etc-et cetera: contain configuration files.
6. /home-home directory: all user have their personal files(except root).
7. /lib-libraries essential for the binaies in /bin and /sbin:
8. /media- mout points for removable media such sd cd-rom.
9. /mnt-temporarily mounted file.
10. /opt-optional application software packages.
11. /sbin-esential system binaries: need sudo for the command in this directory.
12. /tmp-temporary files: 
13. /usr-user utilities: for second level programs.
## ==text editor==
linux command line text editor
 - VIM
 - Nano
 - Emacs
 - Neovim
 linux graphical text editor
    - sublime
    - vscode
    - gedit
    - pluma
## ==VIM(VI improved)==
 primary editor used on unix.
 it have mainly  to modes
  - command mode: "esc".
    - save: " W "
    - quit: " q "
    - save and quit
    - force quit and save: "=!"
    - undo: ":u".
    - execute
    - add bush command :%!command with no space.
  - input mode: enter "i" to change to input mode.
  - visual mode:
  - normal mode: can do nothing (default vim mode)
  
  