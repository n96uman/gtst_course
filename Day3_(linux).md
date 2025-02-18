## sed /stream editor
1. uses for text substitution and replace.
2. deleting and deleting specific file.
3. efficient text manipulation.
syntax : sed [option] 'command' file.
1. substitution
- ==sed s/oldword/newword/==
if there is more than one oldword you want to change.
- ==sed 's/oldword/newword/g'==
2. delete
- sed /pattern/d
## awk
structured txt file. support complex patterns.
- awk 'pattern {action}' file.txt
- awk '{print $1,$3'}' file.txt
- awk # prints columns 1 and 3.
default track of delimiter  by space . if it is by other use the option '-F "sign" '.
### variable
$0 (entire column)
NR: first column data.
NF: last column data.
