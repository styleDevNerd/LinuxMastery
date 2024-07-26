# LinuxMastery

## Keywords

- **shell** - it's a programming language which is used to take some commands from keyboard and passes to the OS
- **CLI (command line interface)** - it's a tool that accepts text input to excute OS functions
- **~** - is user's home folder of the current directory
- **/** - forward slash stands for root

## Commands

- `uptime` - tells how much time your server is up
- `users` - the name of the users
- `hostname` - hostname of the OS/system
- `pwd` - (print working directory) it displays the current directory
- `ls` - list all the files in current directory
- `ls /etc/` - will display all files in the etc directory
- `ls -l /etc/` - will show all files within the etc directory along with all details and size in bytes
- `ls -l -h /etc/` - will show all files within the etc directory along with all details and size in KB
- `clear` - to clear the screen in terminal
- `cd /etc/` - (change directory) it will change the directory to etc
- `cd ../` - it will go back to the previous directory
- `cd ../../` - it will take you to the root directory
- `ll /var/` - display all files within the directory along with all details of the files (`ll` is alias of `ls -l /var/`)
- `alias` - will list all alias
- `alias eshgin=pwd` - create your own alias (alias new command = old command)
- `unalias eshgin=pwd` - remove your own alias (unalias new command = old command)
- `history` - it will list all the commands we have used so far
    - press Ctrl/Cmd+R - type the command and it will search the command for you
    - press Ctrl/Cmd+R - `!81` 81 is the line number of that command from history
- `history -c` - it will clear the history
