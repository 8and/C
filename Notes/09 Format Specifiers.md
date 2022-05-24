# [Notes 9](https://codewithharry.com/videos/c-language-tutorials-in-hindi-9)


### Format specifier in C
The format specifier in C programming is used for input and output purposes. Through this, we tell the compiler what type of variable we are using for input using scanf() or printing using printf(). Some examples are %d, %c, %f, etc.

The %c and %d used in the printf( ) are called format specifiers. Format specifier tells printf( ) to print the value, for %c, a character will printed, and for %d, a decimal will be printed. 

Here is a list of format specifiers.

Format Specifier | Type
-- | --
%c | Used to print the character
%d | Used to print the signed integer
%f | Used to print the float values
%i | Used to print the unsigned integer
%l | Used to long integer
%lf | Used to print the double integer
%lu | Used to print the unsigned int or unsigned long integer
%s | Used to print the String
%u | Used to print the unsigned integer

>rounding up is done while using format specifiers

(%6.4f)
- 4.0f ~ 4.0000
- 7.333 ~ 7.3330  
(%2.4f)
- 23.4 ~ 23.4000  
(%.2f)
- 3.445 ~ 2.44
- 3 ~ 3.00  
(%4f)
- 4 ~ (three spaces here) 4
- 4.3432 ~ 4.343

### Escape Sequence in C  

Many programming languages supports the concept of Escape Sequence. An escape sequence is a sequence of characters which are used in formatting the output. They are not displayed on the screen while printing.

## Types of Escape Sequence in C


Escape Sequence | Description
-- | --
\t | Inserts a tab
\b | Inserts a backspace
\n | Inserts a newline.
\r | Inserts a carriage return.
\f | Inserts a form feed.
\’ | Inserts a single quote character.
\” | Inserts a double quote character.
\\ | Inserts a backslash character.