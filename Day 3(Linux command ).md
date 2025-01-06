==DESKTOP environment:== 

### pre install Tools in Linux 
1. ==information gathering ==: namp , maltego .recon-ng etc...
 2. ==vulnerability analysis==: nikto , nmap  etc...
3. ==web application analysis==: burpsuite , sqlmap , zap  etc..
4. ==Database Assessment ==: sqlmap , jsqlinjection etc...
5. ==password attack ==: Jhon ,ncrack, hydra etc...
6. ==wireless attack==: aircrack-ng , reaver etc...
7. ==Reverse engineering ==: (binary file ) apktools , nasmshell , ghidra etc ...
8. ==exploitation tools==: sqlmap , metasploitable etc ...
9. ==sniffing and spoofing ==: hamster , wireshark ,ettercap etc ...
10. ==post exploitation==: backdoor , 
11. ==forensics==: autopsy , hashdeep etc ...
12. ==reporting tools==: maltego , pipal , recordmydesktop etc ...
13. ==social engineering ==:backdoor , maltego etc ...
### folder manager 


# Terminal
==has 5 parts ==
username , Hostname , current directory , priviledge  $(user) , #(root) and command place.

Home directory denoted by [~]== /home/<username>
local directory  denoted by [.]
all directory denoted by [*]

### Linux commands
there are more than 1000 commands and every one of them have option and argument .

1. ==ls/list directory== : ls [option]  [filename] .
    - ls -l : with permission.
    - ls -a: hidden (they start with dote).
    - ls [filename]: to list the file  .
    - ls -R : id gone list every thing in all folder until it finished all the folder.
1. ==tree==: it kind ls but use tree structure .
2. ==cd/change directory==: cd [directory]
    - cd / => root
    - cd ..=> 1X back
    - cd => to home directory
    - cd ../.. => 2x back
    if my folder is have spaced add "".cd "folder name";
3. PWD:(print working directory) .pwd [option].
4. echo: echo [string].
5. out put redirecting :'>' echo text>file.txt write the out put to the file.txt.
     - if the file is created first we use ">>" else ">".
6. cat / head / less / tail.
7. touch : crating files .
8. mkdir:
9. rm:
     - rm -r => recursive
     - rm -i => for prompt
     - rm -f => force delet
10.cp | mv: copy and move
       - cp [old fileplace] [newfile].
       - mv [olffileplace] [newfileplace].
       - r [option];
       - cp 'cyber' ../../ tmp
11.grep(global search for regular expression): grep [option] patterns [file];
     options:
     -  -i => case sensetive
     -  -c=>count the number line.
     -  -l=>display filename
     -  -r=>re
     -  -v => to display without this 'term' 
     -  -n=> number
     -  -o=> only the word
12.WC-word count: wc [options] [filename]. -l(line)  -w(word) -c (bytes)
13. multiple command executions: and(&&) both command must work, or(||)  only one the command and pipeing(|) using the first command output is the second command input..

  
   
 