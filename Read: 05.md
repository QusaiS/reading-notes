##  **Loops and iteration**
> Loops offer a quick and easy way to do something repeatedly.

There are many different types of loops, but they all essentially do the same thing: they repeat an action some number of times.


* we will talk about for loop statement 

### For Loop statement

*The for statement creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement (usually a block statement) to be executed in the loop.*

![Using For](https://media.geeksforgeeks.org/wp-content/uploads/loop2.png)

**Using For:**

___ 1- Initialization condition: Here, we initialize the variable in use. It marks the start of a for loop. An already declared variable can be used or a variable can be declared, local to loop only.___

_2- Testing Condition: It is used for testing the exit condition for a loop. It must return a boolean value. It is also an Entry Control Loop as the condition is checked prior to the execution of the loop statements._

_3- Statement execution: Once the condition is evaluated to true, the statements in the loop body are executed._

_4- Increment/ Decrement: It is used for updating the variable for next iteration._

_5- Loop termination:When the condition becomes false, the loop terminates marking the end of its life cycle. _

<script type = "text/javaScript">
// JavaScript program to illustrate for loop
  
    var x;
  
    // for loop begins when x=2
    // and runs till x <=4
    for (x = 2; x <= 4; x++) 
    {
        document.write("Value of x:" + x + "<br />");
    }
  
< /script>


** Output:**

Value of x:2
Value of x:3
Value of x:4



