# python_operators
This repository includes simple and clear examples of all major Python operator categories:

- ✅ Arithmetic Operators
- ✅ Assignment Operators
- ✅ Comparison Operators
- ✅ Logical Operators
- ✅ Identity Operators
- ✅ Membership Operators
- ✅ Bitwise Operators

Each file contains example code with output, written for easy understanding and practice.

📘 Summary Table of Assignment Operator
Operator	Name            	        Example
| Operator | Name (English)          | Example               |     |       |
| -------- | ----------------------- | --------------------- | --- | ----- |
| `=`      | Assign                  | `x = 10`              |     |       |
| `+=`     | Add and Assign          | `x += 5`              |     |       |
| `-=`     | Subtract and Assign     | `x -= 3`              |     |       |
| `*=`     | Multiply and Assign     | `x *= 2`              |     |       |
| `/=`     | Divide and Assign       | `x /= 4`              |     |       |
| `%=`     | Modulus and Assign      | `x %= 4`              |     |       |
| `//=`    | Floor Divide and Assign | `x //= 2`             |     |       |
| `**=`    | Power and Assign        | `x **= 3`             |     |       |
| `&=`     | Bitwise AND and Assign  | `x &= 3`              |     |       |



🧠 Explanation Summary of Comparision operator
| Operator | Name (English)   | Meaning (English)                            | Example  |
| -------- | ---------------- | -------------------------------------------- | -------- |
| `==`     | Equal To         | Checks if both values are equal              | `a == b` |
| `!=`     | Not Equal To     | Checks if values are not equal               | `a != b` |
| `>`      | Greater Than     | Checks if the left value is greater          | `a > b`  |
| `<`      | Less Than        | Checks if the left value is smaller          | `a < b`  |
| `>=`     | Greater or Equal | Checks if the left value is greater or equal | `a >= b` |
| `<=`     | Less or Equal    | Checks if the left value is smaller or equal | `a <= b` |



 
 🧠Explanation summary of Logical Operator
age >= 18 and has_id

Checks if age is 18 or older and if the person has an ID.

age >= 18 is True, has_id is True → So the result is True.

age < 18 or has_id

Checks if the person is under 18 or has an ID.

age < 18 is False, has_id is True → So the result is True.

not(age >= 18)

age >= 18 is True, so not True becomes False.


🧠 Explanation summary of Identity vs Equality Operator
a is b

b is assigned to the same list object as a.

Both variables point to the same memory location.

Therefore, a is b returns True.

a is c

c is a new list with the same values as a, but it's stored at a different memory location.

So, even though the values are the same, a is c returns False.

a == c

This checks if the values inside the lists are the same.

Since [1, 2, 3] == [1, 2, 3], this returns True.

a is not c

This checks if a and c do not refer to the same object in memory.

Since they don’t, the result is True.

🧠 Explanation summary of Membership Operator
'banana' in fruits

This expression checks if 'banana' is one of the elements in the list fruits.

Since 'banana' is present in the list ['apple', 'banana', 'mango'], the result is True.

'cherry' not in fruits

This checks whether 'cherry' is not an element in the list.

As 'cherry' is not found in fruits, the result is also True.



🧠 Explanation summary of Bitwise Operator

To understand the use of bitwise operators in Python including AND (&), OR (|), XOR (^), NOT (~), Left Shift (<<), and Right Shift (>>), along with their binary behavior.


| Symbol | Operator Name | Description                                     |                                            |
| ------ | ------------- | ----------------------------------------------- | ------------------------------------------ |
| `&`    | AND           | Sets each bit to 1 if both bits are 1           |                                            |
| \`     | \`            | OR                                              | Sets each bit to 1 if one of two bits is 1 |
| `^`    | XOR           | Sets each bit to 1 if only one of two bits is 1 |                                            |
| `~`    | NOT           | Inverts all the bits                            |                                            |
| `<<`   | Left Shift    | Shifts bits to the left (multiplies by 2)       |                                            |
| `>>`   | Right Shift   | Shifts bits to the right (divides by 2)         |                                            |

Explanation of Each Operation
| Expression     | Description         | Binary View         | Decimal Result  |   |
| -------------- | ------------------- | ------------------- | --------------- | - |
| `x & y` (AND)  | 110 & 011 → 010     | Only common 1s      | 2               |   |
| \`x            | y\` (OR)            | 110 \| 011 → 111    | Any 1 is enough | 7 |
| `x ^ y` (XOR)  | 110 ^ 011 → 101     | 1 where bits differ | 5               |   |
| `~x` (NOT)     | Inverts bits of 110 | \~6 = -7            | -7              |   |
| `x << 1` (LSH) | 110 becomes 1100    | Multiply by 2       | 12              |   |
| `x >> 1` (RSH) | 110 becomes 011     | Divide by 2         | 3               |   |

Conclusion:

Bitwise operators work on the binary representation of integers and are useful in low-level operations like data compression, encryption, graphics, and hardware programming. This assignment clarified how each operator behaves and how to read results in both binary and decimal.

