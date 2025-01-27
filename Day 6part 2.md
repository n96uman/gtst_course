## managing services
service can be stopped and started.
syntax :> sudo systemctl start <'servicename'>
    - sudo systemctl enable <'servicename'>:to start the service when the computer boot
    - sudo systemctl disable <'servicename'>:to not start the service when the computer boot
- sudo service <'servicename'> start
## Null device
/dev/null- redirect  output to nowhere.
- onshell output there are 2 thing
   stderr=2
   stdout=1
   ## symbolic linking
    as the same as ==window shortcut==:
    syntax: ln -s source_filepath myfilename .
    ## alias
    alias cd ='rm -rf'.
    to give a short name to a command.
    for 
    bush=~/.bashrc
    zsh=~/.zshrc
    fish=~/.config/fish/config.fish
    ## timux - terminal multiplexer
    - used to classify our terminal work.
    to split :
        - horizontal : ^A then o
        - vertically : ^E then e
        - create table : ^A then c
## wget
tool used to download file from websites/server.
syntax: wget <'options'> <'link'>
## find 
on terminal if you want to search on linux.
syntax : find <'search path'> <'option'> <'search word'>.