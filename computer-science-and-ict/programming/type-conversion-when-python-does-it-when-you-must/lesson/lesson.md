# Type conversion - when Python does it, when you must

## Do it first

Try to add, in your head, the word "five" to the number 3. Your head protests - they are different kinds of thing. Python protests too, out loud, with an error. But sometimes Python quietly fixes a mixed sum by itself. This lesson is the line between the two: when Python converts for you, and when you must convert yourself. Do the worked clash at the end with your own hands.

## Sub lesson 1 - Implicit conversion - Python does it itself

**Type conversion** changes a value **from one type to another**.

**Implicit conversion** is done **by Python itself, without the programmer** - and it is done **to avoid losing data**:

```
>>> 3 + 2.5
5.5
```

Adding an **int to a float yields a float**. Why not an int? Because forcing 5.5 into an int would **lose part of it** - so Python promotes the result to the type that keeps everything.

## Sub lesson 2 - Explicit conversion - you do it, with int(), float(), str()

**Explicit conversion** is done **by the programmer**, using the **built-in functions named for the target type**:

- `int()` - converts to a whole number: `int("5")` is `5`.
- `float()` - converts to a decimal: `float("2.5")` is `2.5`.
- `str()` - converts to text: `str(8)` is `"8"`.

The function's name IS the destination type.

## Sub lesson 3 - The clash and its fix - a string meets an integer (doing)

Now the clash. Python **refuses to add a string to an integer**:

```
>>> "5" + 3
TypeError: can only concatenate str (not "int") to str
```

The error is honest: a string's `+` joins, and an int cannot be joined. **The fix:** explicitly **convert the string's value to int before adding**:

```
>>> int("5") + 3
8
```

Convert first - then the two sides are the same type, and the operation runs clean.

[Picture 18113 - a string and a number colliding with an error, then passing through a converter and adding cleanly]

## Say it to your companion

Tell your companion: the two kinds of conversion and who does each; why int + float becomes a float; and walk them through the "5" + 3 clash - the error, then the int() fix, then the answer 8.

## Do It Yourself

1. Convert "12" to an int and add 8. Write the line and the result.
2. 3 + 2.5 - which kind of conversion happens, who does it, and what type is the result? Write all three answers.
3. str(8) gives what, exactly - and how can you tell it is a string now?
