#  Operators and Loops 

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

Operator | Description 
--------- | ---------
Equal (==) |Returns true if the operands are equal
Not equal (!=)| Returns true if the operands are not equal.
Strict equal (===)| Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. 
Strict not equal (!==)|	Returns true if the operands are of the same type but not equal, or are of different type.
Greater than (>)	|Returns true if the left operand is greater than the right operand.
Greater than or equal (>=)|	Returns true if the left operand is greater than or equal to the right operand.
Less than (<)|	Returns true if the left operand is less than the right operand.
Less than or equal (<=)	|Returns true if the left operand is less than or equal to the right operand.


## Loops and iteration

> for statement

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

  When a for loop executes, the following occurs:
  1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
  2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
  3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
  4. If present, the update expression incrementExpression is executed.
  5. Control returns to Step 2.

  > while statement

  A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement

  If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.



[refrance:  JavaScript](https://drive.google.com/file/d/1KFKjXZMEVY5OIxIUcUlCzCxCvZvr529K/view)