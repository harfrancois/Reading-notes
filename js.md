# Control flow
    the order in which computers execute statements in a script.

example:
if (field==empty) {
    promptUser();
} else {
    submitForm();
}

Conditional loops change the structure of the control flow.



# Function
    Functions are code that is grouped together. It usualy has one job.

Function nameOfTheFunction(parameter){codeBlocks}

# Expressions and operators

# Operators
- #### Assignment operators
    Assigns a value to its left operand based on the value of its right operand. simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. looks like this, x = y. Asigning the value of y to x.

    - Return value and chaining retrieving/return x = y value.
    const z = (x = y); // Or equivalently: const z = x = y;
    console.log(z); // Log the return value of the assignment x = y.
    console.log(x = y); // Or log the return value directly.
    - logical assignments, (a + x = y). Chaining these expression, each assignment is evaluated right-to-left.
    
    compound assignment operator listed link.
    https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators

- #### Comparison operators
    Compares its operands and returns a logical value based on whether the comparison is true.
    Example: var var1 = 3;

- #### Arithmetic operators
    Takes numerical values (either literals or variables) as their operands and returns a single numerical value.
    Example: 1 / 2; // 0.5
             1 / 2 == 1.0 / 2.0; // this is true

- #### Bitwise operators
    Treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers.

- #### Logical operators
    Used with Boolean (logical) values; when they are, they return a Boolean value.

- #### String operators
    (+) Concatenates two string values together, returning another string that is the union of the two operand strings.

- #### Comma operator
    (,) Evaluates both of its operands and returns the value of the last operand.

- #### Conditional (ternary) operator
    Requires two operands
    operand1 operator operand2
    example: 3+4 or x*y

- ### Unary operators
    Requires a single operand
    operator operand or operand operator
    example: x++ or ++x

- #### Relational operators  
    Compares its operands and returns a Boolean value based on whether the comparison is true.

# Loops and iteration

# loops
    Loops offer a quick and easy way to do something repeatedly.

#### for loop
    A for loop repeats until a specified condition evaluates to false.
    Example: for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

#### do while 
    The do...while statement repeats until a specified condition evaluates to false.
    Example:
    do
      statement
    while (condition);

#### while
    A while statement executes its statements as long as a specified condition evaluates to true.
    Example:
    while (condition)
    statement

## Table Of Contents

[1 GitHub Pages](https://github.com/harfrancois/Reading-notes)

[2 Terminal](./terminal.md)

[3 HTML](./html.md)

[4 Git](./git.md)

[5 CSS](./css.md)

[6 JS](./js.md) 