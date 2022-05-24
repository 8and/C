# [Notes 7](https://codewithharry.com/videos/c-language-tutorials-in-hindi-7)

## Arithmetic operators
 Arithmetic operators are used to perform mathematical operations such as addition, subtraction etc. Few of the simple arithmetic operators are :

Addition, Subtraction, Multiplication, Division, Modulus  


## Relational Operators
Relational operators are used for the comparison between two or more numbers. Same as Java, C also has six relational operators and their return value is in Boolean i.e. either True or False (1 or 0).

Operators: Greater than, Less than, Greater than or equal to, Less than or equal to, Is equal to, Is not equal to


## Logical Operators
There are three logical operators i.e. AND, OR and NOT. They can be used to compare Boolean values but are mostly used to compare conditions to see whether they are satisfying or not. 

AND: it returns true when both operators are true or 1.

OR: it returns true when either operator is true or 1.

Not: it is used to reverse the logical state of the operand.



## Bitwise Operators
To perform bit level operations, bitwise operators are used. They convert the values we provide to them in binary format and then compare them to provide us the results.

 

Symbols | Operators
-- | --
& | Bitwise AND
straight line | Bitwise OR
^ | Bitwise XOR
~ | Bitwise complement
"<<" | Shift left
">>" | Shift right

## Assignment Operators
Assignment operators are used to assign values. They are going to be used in each and every one of our program.

    int a = 0;
    int b = 1;
>Equal to (=) is the assignment operator here, assigning 0 to a and 1 to b.


Operator | Description
-- | --
= | Assigns values from right side operands to left side operand
+= | It adds the right operand to the left operand and assign the result to the left operand.
-= | It subtracts the right operand from the left operand and assigns the result to the left operand.
*= | It multiplies the right operand with the left operand and assigns the result to the left operand.
/= | It divides the left operand with the right operand and assigns the result to the left operand.

## Conclusion
These are few of the important operators that you should know about before starting actual programming. There are also many other operators such as &, % or *(pointer).

## Operator Precedence  

Category | Operator | Associativity
-- | -- | --
Postfix | () [] -> . ++ - - | Left to right
Unary | + - ! ~ ++ - - (type)* & sizeof | Right to left
Multiplicative | * / % | Left to right
Additive | + - | Left to right
Shift | << >> | Left to right
Relational | < <= > >= | Left to right
Equality | == != | Left to right
Bitwise AND | & | Left to right
Bitwise XOR | ^ | Left to right
Bitwise OR | or | Left to right
Logical AND | && | Left to right
Logical OR | oror | Left to right
Conditional | ?: | Right to left
Assignment | = += -= *= /= %=>>= <<= &= ^= or= | Right to left
Comma | , | Left to right