

# LOOPS



## For loop

    for(;;) {}

The keyword **for** is used to describe a loop that is controlled by a counter. The parentheses enclose three expressions that initialize, check and update the variable used as counter. The body defined by curly braces encloses the statements that are executed at each pass of the loop.

    for(int i = 0; i <= 99; i++) { aFunction(); }

The execution of a single pass or the whole loop can be aborted by using a continue or a break statement respectively.



## While loop

    while() {}

The keyword **while** is used to describe a loop that is controlled by a condition. The parentheses enclose the expression that defines the condition. The body defined by curly braces encloses the statements that are executed at each pass of the loop.

    while(i <= 99) { aFunction(); }

The execution of a single pass or the whole loop can be aborted by using a continue or a break statement respectively.



## Do-while loop

    do {} while();

The keyword **do** is used in combination with **while** to describe a loop that is controlled by a condition. The body defined by curly braces encloses the statements that are executed at each pass of the loop. The parentheses enclose the expression that defines the condition.

    do { aFunction(); } while(i <= 99);

The execution of a single pass or the whole loop can be aborted by using a continue or a break statement respectively.

In contrast to a simple while loop the body is always executed at least one time even if the expression evaluates to false from the beginning.



## Abort a single pass of a loop

    continue;

The keyword **continue** is used inside the body of a loop to abort a single pass of the loop. All statements in the body after the continue statement are ignored and the next iteration of the loop is executed immediately.



## Abort a loop

    break;

The keyword **break** is used inside the body of a loop to abort the whole loop. All statements in the body after the break statement are ignored and the loop is exited without executing any further iteration.
