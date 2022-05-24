# [Notes 6](https://codewithharry.com/videos/c-language-tutorials-in-hindi-6)


### Declaration
We cannot declare a variable without specifying its data type. The data type of a variable depends on what we want to store in the variable and how much space we want it to hold. The syntax for declaring a variable is simple:

the data type can be int, float, char, depending on what kind of value we want to store.

### Naming a Variable
A variable name can be of anything we want to call out variable. Yet there are specific rules we must follow while naming a variable: 

- A variable name can contain alphabets, digits, and underscore (-) only.
- The starting letter can not be a digit.
- White spaces cannot be used.
- The name should not be reserved keyword or special character.
- We can declare and assign value to a variable in two ways.

### Variable  
A variable as it names define can be altered, or its value can be changed, but same is not true for its type. If a variable is of integer type, then it will only store an integer value, which means that we cannot assign a character type value to an integer variable. We can not even store a decimal value into an integer variable.

 #
DATA TYPE | MEMORY (BYTES) | RANGE
--| -- | --
Char | 1 | -128 to 127
signed char | 1 | -128 to 127
unsigned char | 1 | 0 to 255
short int | 2 | -32,768 to 32,767
unsigned short int | 2 | 0 to 65,535
unsigned int | 4 | 0 to 65,535
int | 2 | --32,768 to 32,767
long int | 4 | -2,147,483,648 to 2,147,483,647
unsigned long int | 4 | 0 to 4,294,967,295
float | 4 | 
double | 8 | 
long double | 10 | 

