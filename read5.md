





## USING IF ... ELSE STATEMENTS 


if ... e 1 se statement allows you
to provide two sets of code:
1. one set if the condition
evaluates to true
2. another set if the condition is
false 

Note that the statements inside
an if statement should be
followed by a semicolon, but
there is no need to place one
after the closing curly brace of
the code blocks.


## SWITCH STATEMENTS 

A switch statement starts with a
variable called the switch value.
Each case indicates a possible
value for this variable and the
code that should run if the
variable matches that value.
Here, the variable named 1 eve l is the switch value.
If the value of the l eve 1 variable is the string One,
then the code for the first case is executed. If it is
Two, the second case is executed. If it is Three, the
third case is executed. If it is none of these, the code
for the defaul t case is executed.
The entire statement lives in one code block (set
of curly braces), and a colon separates the option
from the statements that are to be run if the case
matches the switch value.
At the end of each case is the break keyword. It tells
the JavaScript interpreter that it has finished with
this switch statement and to proceed to run any
subsequent code that appears after it.


** like this **
switch (level) {
case 'One ':
title= 'Level 1 ' ;
break;
case 'Two':
tit 1 e = ' Level 2 ' ;
break;
case ' Three' :
title = 'Level 3' ;
break ;
default :
title= 'Test';
break; 


