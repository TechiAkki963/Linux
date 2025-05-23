# Linux

Shortcut to open terminal.
ctrl + alt + T

Install terminator 
> sudo apt update && sudo apt install terminator

- man command - help with the command manual
- man [command]

> man -k ls


Keyboard Shortcuts 
- ctrl + L - clears the screen
- ctrl + D - to close the current shell
- ctrl + A - to move to start of the line
- ctrl + E - to move to end of the line
- ctrl + Z = to pause any activity in the terminal
- ctrl + C - to stop an activity in the terminal

* Mastering the terminal THE BASH HISTORy *

 > cat .bash_history
 > echo $HISTFILESIZE
 > history

 - to remove a command
 > history -d 107
  
 - to clear the entire history
 > history -c

- running command without leaving a trace
  space and then the command
  so the command is not caught in the system

  - to view the history with time
    >HISTTIMEFORMAT="%d/m//y %T"
  - set history with time in permenant setting
    >echo "HISTTIMEFORMAT="%d/m//y %T"" >> .bashrc
    - to check the command is registered in bashrc file
      >cat .bashrc

  * # Root

    - to create a temporary root user
      >sudo su

    - to create password for root
      >sudo passwd root
      - New password : admin@369

    - to acess root user
      >su

*  ls /  vs ls /root/
      - the ls / - it is the top most directory in the linux system.
      - ls /root/ - it is root directory 
