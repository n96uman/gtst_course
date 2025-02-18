## special file permissions
there are 3 special permission(sudo +s filename)
- SUID bits(s)- set user ID bit-add 4 infront of our numeric
- SGID bits(S)-set group ID bit-add 2 infront of our numeric
- sticky bits(t)-set other ID bit-add 1 infront of our numeric
## package installation on linux
- all linux to install software uses package manager.
- the package manager called 'apt' also there is another called 'dpkg'
- ==repository==:package installation server.
### advanced package tool / apt /
- sudo apt update 
- sudo apt search <'softwarename'>
- sudo apt install <'software'>
- sudo apt remove <softwarename'>
- sudo apt upgrade
- sudo apt purge <'sofwarename>
### package dependencies
software can be built based on another program called "module".
### common linux repository error
1. could not get lock/var/lib/apt/lists/lock
2. could not open lock/var/lib/dpkg/lock-fronted
3. unable to locate package
repository error, if this happened you can fix it using
    - sudo apt edit-sources
## DPKG /debian package manager/
is an offline package manager.
have an extension '.deb'
syntax
  - sudo dpkg -i <'packagename'>
  - sudo dpkg -r <'packagename'>
  - sudo dpkg -p <'packagename'>