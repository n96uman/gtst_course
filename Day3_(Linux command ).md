==DESKTOP environment:== 

### pre install Tools in Linux 
1. ==information gathering ==: nmap , maltego .recon-ng etc...
 1. ==vulnerability analysis==: nikto , nmap  etc...
2. ==web application analysis==: burpsuite , sqlmap , zap  etc..
3. ==Database Assessment ==: sqlmap , jsqlinjection etc...
4. ==password attack ==: Jhon ,ncrack, hydra etc...
5. ==wireless attack==: aircrack-ng , reaver etc...
6. ==Reverse engineering ==: (binary file ) apktools , nasmshell , ghidra etc ...
7. ==exploitation tools==: sqlmap , metasploitable etc ...
8. ==sniffing and spoofing ==: hamster , wireshark ,ettercap etc ...
9. ==post exploitation==: backdoor , 
10. ==forensics==: autopsy , hashdeep etc ...
11. ==reporting tools==: maltego , pipal , recordmydesktop etc ...
12. ==social engineering ==:backdoor , maltego etc ...
### folder manager 


# Terminal
==has 5 parts ==
username , Hostname , current directory , priviledge  $(user) , #(root) and command place.

Home directory denoted by [~]== /home/<username>
local directory  denoted by [.]
all directory denoted by [*]

### Linux commands
there are more than 1000 commands and every one of them have option and argument .

13. ==ls/list directory== : ls [option]  [filename] .
    - ls -l : with permission.
    - ls -a: hidden (they start with dote).
    - ls [filename]: to list the file  .
    - ls -R : id gone list every thing in all folder until it finished all the folder.
14. ==tree==: it kind ls but use tree structure .
15. ==cd/change directory==: cd [directory]
    - cd / => root
    - cd ..=> 1X back
    - cd => to home directory
    - cd ../.. => 2x back
    if my folder is have spaced add "".cd "folder name";
16. PWD:(print working directory) .pwd [option].
17. echo: echo [string].
18. out put redirecting :'>' echo text>file.txt write the out put to the file.txt.
     - if the file is created first we use ">>" else ">".
19. cat / head / less / tail.
20. touch : crating files .
21. mkdir:
22. rm:
     - rm -r => recursive
     - rm -i => for prompt
     - rm -f => force delet
10.cp | mv: copy and move
       - cp [old fileplace] [newfile].
       - mv [oldfileplace] [newfileplace].
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
23. multiple command executions: and(&&) both command must work, or(||)  only one the command and pipeing(|) using the first command output is the second command input..

  
   
 