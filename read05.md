# Loops and iteration  

A Loop  can be explained as telling the computer to keep processing the equation untill an answar is found and there are many different kinds of loops, but they all essentially do the same thing they repeat an action some number of times.


The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

# Operators
in todays lecture we learned
## AND ** (AND &)**  
The logical AND operator is evaluated left to right, it is tested for possible short-circuit evaluation using the following rule:

(some falsy expression) && expression is short-circuit evaluated to the falsy expression;

Short circuit means that the expression part above is not evaluated, hence any side effects of doing so do not take effect example if expression is a function call, the calling never takes place

The logical AND assignment (x &&= y) operator only assigns if x is truthy.


x &&= y


## OR   **(or ||)**

**(	x ||= y)**

 
The logical OR operator short-circuits: the second operand is only evaluated if the first operand doesn’t already determine the result.

Logical OR assignment short-circuits as well, meaning it only performs an assignment if the logical operation would evaluate the right-hand side

The logical OR assignment (x ||= y) operator only assigns if x is falsy

