# Type conversion - when Python does it, when you must - multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** Type conversion is -
a) renaming a variable  b) changing a value from one type to another  c) deleting a value  d) printing a value
**Answer: b) changing a value from one type to another** - one type becomes another.

**2. (Sub lesson 1)** Implicit conversion is done by -
a) the programmer  b) Python itself, without the programmer  c) the teacher  d) IDLE's editor
**Answer: b) Python itself, without the programmer** - Python does it on its own.

**3. (Sub lesson 1)** Adding an int to a float yields a float because -
a) floats are prettier  b) forcing the result into int would lose part of it  c) ints cannot be added  d) the interpreter prefers decimals
**Answer: b) forcing the result into int would lose part of it** - implicit conversion exists to avoid losing data.

**4. (Sub lesson 1)** 3 + 2.5 gives -
a) 5 as an int  b) 5.5 as a float  c) an error  d) "5.5" as a string
**Answer: b) 5.5 as a float** - the result is promoted to float.

**5. (Sub lesson 2)** Explicit conversion is done with -
a) print() and input()  b) the built-in functions int(), float() and str()  c) the Run menu  d) an assembler
**Answer: b) the built-in functions int(), float() and str()** - each function is named for its target type.

**6. (Sub lesson 2)** int("5") gives -
a) "5"  b) 5  c) 5.0  d) an error
**Answer: b) 5** - the string's value becomes the whole number 5.

**7. (Sub lesson 3)** "5" + 3 in Python -
a) gives 8  b) gives "53"  c) raises an error - Python refuses to add a string to an integer  d) gives 5
**Answer: c) raises an error - Python refuses to add a string to an integer** - the clash is refused, out loud.

**8. (Sub lesson 3)** The fix for "5" + 3 is -
a) add 0 first  b) convert the string's value to int before adding: int("5") + 3 = 8  c) put quotes around the 3 and accept text  d) restart IDLE
**Answer: b) convert the string's value to int before adding: int("5") + 3 = 8** - convert first, then add.
