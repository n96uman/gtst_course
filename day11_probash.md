1. ==Regular expression in Linux==/regex/:most filter validation on any platform done by regex. 
(it is pattern).
regex are used on linux tools called grep, awk and sed.
- in python it is import re.
### metacharacter 
- dot(). : all the line except new line
- ^ :assertion used to filter a line start with pattern.
    - syntax : ^pattern
- $ : assertion used to filter a line that end with pattern.
- * : with all conditions .
    sytnax:^hellos*
- + : quantity to find a pattern that occurs 1 or more times.
- ? : only ones or not at all.
- {min,max}: to get line that occur min and max.
- [] : custom pattern. used to create your own patterns. [a-z].
- ()
- \w :to get alphanumeric (only text and numbers) if it is small w. if it is uppercase the opposite of the above.
- \s : only tab
- \d : only numbers
- \metacharacter: it is called escape.
- pip( | )-or: used to search two different things.
## bash For regex
we use =~ operator for regex check with if condition statements. we are using double brackets.