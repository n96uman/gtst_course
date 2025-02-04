1. shebang: #!/bin/bash
### ==variable==
if you use single variable you can't use single '.
you can't use space between declaration.
 - name="numan".
if you want to use a variable in the out put
-  echo "your name is ${name}"
set command gone give value position.
### ==system variables==
a variable that is declared by the system
- echo $bash
- echo $bash_version
- echo $pwd
- echo $home
- echo $path
- echo $user
- ${!var[@]}:index
- ${#var[#]}:length
## ==Bash input==
1. Bash read
- read -p "text to display " var
- read -sp "password:"var
2. Arguments 
- syntax : just use $1-$2
- echo "enter your name : $1"
## ==comment==
- '#' for single line
- <<'COMMENTS  COMMETNTS
## sleep
- sleep 5s{}


