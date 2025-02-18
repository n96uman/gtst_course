### loops
there are 3 type of loop
- for loop :-
    - for condition or (( i=1 ; i<=10; i++ ))
     do
        body
     done
    example : 
        - for num in {1 . . 10 . . 1}
         do
         ECHO $num
         done
- while loop
    - while [[ expression ]] no expression means  infinite loop
      do 
        body
    done
- until loop
    - when the expression is true it exit.
    - until [ expression ]
        do
         body
        done
- function  
    function_name(){
     sum=$($1+$2) they are argument 
     body
    }
    return value = $?. 
## bash and linux
echo * is gone do ls command.
## interaction with linux
use is command /bin/bash