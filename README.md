# LinuxMastery

## Keywords

- **shell** - it's a programming language which is used to take some commands from keyboard and passes to the OS
- **CLI (command line interface)** - it's a tool that accepts text input to excute OS functions
- **~** - is user's home folder of the current directory
- **/** - forward slash stands for root
- **/bin** - it contains binary or executable files which are necessary for the OS
- **/sbin** - files under /sbin should be run or executed by the root user
- **/lib** - it contains library files which contain code that your application can use
- **/usr** - /usr/bin and /usr/lib are for all executables and libraries except the ones that are required for booting
- **/etc** - it contains configuration files
- **/home** - it contains home directories of all users on the system
- **/dev** - it contains all device files
- **/opt** - it contains software that you compiled. Software that you build yourself from a source code
- **/var** - it contains variable files such as log files
- **/tmp** - it contains temporary files


## Commands - Command Line Interface

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
- `type pwd` - it will tell if a command is built-in or external binary file
- `which pwd` - it's used to locate the executable file associated with given command
- `echo PATH` - it will display whatever you want to display on the screen
- `echo $PATH` - it will add the PATH as a variable
- `export PATH=/home/udemy1/.local/bin:/home/udemy1/bin:/usr/local/bin:/usr/local/sbin:/usr/sbin` - it will remove the path you want to remove
- `ls --help` - to get the help about the command with all available options
- `man echo` - will show traditional system-wide manual pages for commands and configurations
- `env` - it will show all the environment variables
- `CATALINA_HOME=/home/udemy1/tomcat` - this will set the variable CATALINE_HOME with the path mentioned
- `export CATALINA_HOME` - to add any variable to the environment variable list you have to export it
- `unset CATALINA_HOME` - to remove any variable to the environment variable list you have to export it

## Commands - File Management

