scripting are made with scripting language
1. ==script installation==: git clone <'link'>
2. ==script module==: 
    python:  pip install  .modulename
    for requirement file -> pip install -r <'requirement'>
    go: go install modulename
    ruby: gem install mofulename
3. man: the manual about he commands.
### Linux processes and service
- processes : running instance of program.
- services : background program that start automatically.(daemons)
- to get the process running
    - ps ['options'].
#### managing processes
- to stop process
    - kill <'options'> <'pid'>
    - killall
- more on kill
    - kill -19 pid-> to stop the process
    - kill -18 pid->to resume the process we stopped
    - kill -9 pid -> to process immediately