# operators
operators in python
Python Operators in general are used to perform operations on values and variables. These are standard symbols used for the purpose of logical and arithmetic operations. In this article, we will look into different types of Python operators. 

OPERATORS: Are the special symbols. Eg- + , * , /, etc.
OPERAND: It is the value on which the operator is applied.
Arithmetic Operators:
Arithmetic operators are used to performing mathematical operations like addition, subtraction, multiplication, and division.
+	Addition: adds two operands	x + y
–	Subtraction: subtracts two operands	x – y
*	Multiplication: multiplies two operands	x * y
/	Division (float): divides the first operand by the second	x / y
//	Division (floor): divides the first operand by the second	x // y
%	Modulus: returns the remainder when the first operand is divided by the second	x % y
**	Power: Returns first raised to power second	x ** y
Comparison Operators:
Comparison of Relational operators compares the values. It either returns True or False according to the condition.
>	Greater than: True if the left operand is greater than the right	x > y
<	Less than: True if the left operand is less than the right	x < y
==	Equal to: True if both operands are equal	x == y
!=	Not equal to – True if operands are not equal	x != y
>=	Greater than or equal to True if the left operand is greater than or equal to the right	x >= y
<=	Less than or equal to True if the left operand is less than or equal to the right	x <= y
is 	x is the same as y	x is y
is not	x is not the same as y	x is not y
= is an assignment operator and == comparison operator.
Logical Operators:
Logical operators perform Logical AND, Logical OR, and Logical NOT operations. It is used to combine conditional statements.
and	Logical AND: True if both the operands are true	x and y
or	Logical OR: True if either of the operands is true 	x or y
not	Logical NOT: True if the operand is false 	not x
Bitwise Operators:
Bitwise operators act on bits and perform the bit-by-bit operations. These are used to operate on binary numbers.
&	Bitwise AND	x & y
|	Bitwise OR	x | y
~	Bitwise NOT	~x
^	Bitwise XOR	x ^ y
>>	Bitwise right shift	x>>
<<	Bitwise left shift	x<<
Assignment Operators :
Assignment operators are used to assign values to the variables.
=	Assign value of right side of expression to left side operand 	x = y + z
+=	Add AND: Add right-side operand with left side operand and then assign to left operand	a+=b     a=a+b
-=	Subtract AND: Subtract right operand from left operand and then assign to left operand	a-=b     a=a-b
*=	Multiply AND: Multiply right operand with left operand and then assign to left operand	a*=b     a=a*b
/=	Divide AND: Divide left operand with right operand and then assign to left operand	a/=b     a=a/b
%=	Modulus AND: Takes modulus using left and right operands and assign the result to left operand	a%=b     a=a%b
//=	Divide(floor) AND: Divide left operand with right operand and then assign the value(floor) to left operand	a//=b     a=a//b
**=	Exponent AND: Calculate exponent(raise power) value using operands and assign value to left operand	a**=b     a=a**b
&=	Performs Bitwise AND on operands and assign value to left operand	a&=b     a=a&b
|=	Performs Bitwise OR on operands and assign value to left operand	a|=b     a=a|b
^=	Performs Bitwise xOR on operands and assign value to left operand	a^=b     a=a^b
>>=	Performs Bitwise right shift on operands and assign value to left operand	a>>=b     a=a>>b
<<=	Performs Bitwise left shift on operands and assign value to left operand	a <<= b     a= a << b
Identity Operators:
is and is not are the identity operators both are used to check if two values are located on the same part of the memory. Two variables that are equal do not imply that they are identical. 
is          True if the operands are identical 
is not      True if the operands are not identical 
Membership Operators:
in and not in are the membership operators; used to test whether a value or variable is in a sequence.
in            True if value is found in the sequence
not in        True if value is not found in the sequence
Precedence and Associativity of Operators
Precedence and Associativity of Operators: Operator precedence and associativity determine the priorities of the operator.
Operator Precedence
This is used in an expression with more than one operator with different precedence to determine which operation to perform first.
Precedence and Associativity of Operators
Precedence and Associativity of Operators: Operator precedence and associativity determine the priorities of the operator.
Ternary operators:
Ternary operators are also known as conditional expressions are operators that evaluate something based on a condition being true or false. It was added to Python in version 2.5. 
It simply allows testing a condition in a single line replacing the multiline if-else making the code compact.
 '''When condition becomes true, expression [on_false]
   is not executed and value of "True and [on_true]"
   is returned.  Else value of "False or [on_false]"
   is returned.
   Note that "True and x" is equal to x. 
   And "False or x" is equal to x. '''
[expression] and [on_true] or [on_false] 

