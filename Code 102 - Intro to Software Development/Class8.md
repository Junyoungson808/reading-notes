# Class 8: Operators and Loops

## Comparison Operators & Assignment Operators
    Comparison Operators: Compares its operands and returns a logical value based on whether the comparison is true. 
    The operands can be numerical, string, logical, or object values. 
        ** const var1 = 3;
        ** const var2 = 4;

    | Operator                | Description                                     | Examples                                 |
    | Equal             (==)  | returns true if op are =                        | 3 == var1  //  "3" == var1 // 3 == '3'   |
    | Not Equal         (!=)  | returns true if op are **not** =                | var1 !=4  //  var2 !="3"                 |
    | Strict Equal      (===) | returns true if op are = of same type           | 3 === var1                               |
    | Strict Not Equal  (!==) | returns true if op are same type but **not** =  | var1 !=="3"  //  3 !== '3'               |
    | Greater Than      (>)   | returns true if the left op is > right op       | var2 > var1 //  "12" > 2                 |
    | Greater Than or = (>=)  | returns true if the left op is >= right op      | var2 >= var1                             |
    | Less Than         (<)   | returns true if the left op is < right op       | var1 < var2                              |
    | Less Than or =    (<=)  | returns true if the left op is <= right op      | var1 <= var2                             |

    Assignment Operator: An assignment operator **assigns** a value to its left operand based on the value of its right operand. 
    The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. 
    That is, x = f() is an assignment expression that assigns the value of f() to x.

    | Name                      | Shorthand Operator         | Meaning               |
    | Assignment                | x = f()                    | x = f()               |
    | Addition Assignment       | x += f()                   | x = x + f()           |    
    | Subtraction Assignment    | x -= f()                   | x = x - f()           |  
    | Multiplication Assignment | x *= f()                   | x = x * f()           |
    | Division Assignment       | x /= f()                   | x = x / f()           |    
  
## Loops and Iteration
    Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.
    You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

        **Example:**
            for (let step = 0; step < 5; step++) {
            // Runs 5 times, with values of step 0 through 4.
            console.log('Walking east one step');
            }

## For Statement
    A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
        1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, 
            but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
        2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. 
            Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
        3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
        4. If present, the update expression incrementExpression is executed.
        5. Control retuns to Step 2

        **Example**
            for ([initialExpression]; [conditionExpression]; [incrementExpression])
            statement
