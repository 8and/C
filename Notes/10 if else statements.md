# [Notes 10](https://codewithharry.com/videos/c-language-tutorials-in-hindi-10)

Sometimes we want a set of instructions to be executed if certain condition is satisfied and an entirely different set of instructions to be executed if the condition does not fulfil. This kind of situation is dealt in C language using a decision control instruction. 

Like other programming languages, C also uses the if keyword to implement the decision control instruction. The condition for the if statement is always enclosed within a pair of parentheses. If the condition is true, then the set of statements will execute. If the condition is not true then the statement will not execute, instead the program skips that part.

We express a condition for if statements using relational operators. The relational operators allow us to compare two values to see whether they are equal, unequal, greater than or less than.


Conditions | Meaning
-- | --
a == b | a is equal to b  
a  != b | a is not equal to b
a < b | a is less than b 
a> b | a is greater than b 
a <= b | a is less than or equal to b  
a >= b | a is greater than or equal to b

### The if-else Statement

The statement written in if block will execute when the expression following if evaluates to true. But when the if is written with else block, then when the condition written in if block turns to be false, then the set of statements in the else block will execute.

### Nested If-Else Statements
We can write an entire if-else statement within either the body of the if statement or the body of an else statement. This is called ‘nesting’ of ifs.

### Summary
 If-else statement is used when a program needs to take a certain decision. An if block does not always need to be associated with an else block. However, an else block will always be associated with an if statement.  If the expression in if statement is evaluated to true, statements inside the body of if are executed. And when the test expression is evaluated to false, statements inside the body of if are not executed. If the else is associated with if block, then the statements written in else block will execute.