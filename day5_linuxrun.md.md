1. ==password change in user==: sudo passwd username.
2. ==to change user id==: sudo usermod -u new_id username.
3. ==delete user==:sudo userdel -r username
4. ==to change users on terminal==:su -username.
5. ==add user add users to home==:sudo mkhomedir_helper your username.
6. ==change the shell type==:sudo usermod your username -s /bin/shell.
7. ==create new grouop==:sudo groupadd groupname.
8. ==adduser to the group==:sudo usermod -aG <'groupname'><'username'>.
9. ==verify the membership ==:group <'username'>.
10. ==remove user from group==: group <username'>.
11. ==sudoers file==:a file to give permission to users to use 'sudo'.commands= sudo visudo
12. ==linux file permission==: it have four part .
    - ==permission==: read(r)=4,write(w) =2 and execute(e)=1.different the permission 'd'(begin) and '-' (in the middle).have five part
        - user (u).power of the user.
        - group(g): power of the group.
        - other(o): power of other user.
        - all(a): power of all which can be found in the 3 above onwers.
    - ==owners:== the file creater. username and group .
        - to change owner command : sudo chown <'username>:<group name'> <'filename>.
        ==CHMOD==: CHANGE permission. sudo chmod u+PERMISSIONTYPES <'FILENAME>
    - size
    - date
    - filname
