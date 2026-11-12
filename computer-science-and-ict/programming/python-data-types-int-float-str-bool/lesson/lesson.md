# Python data types - int, float, str, bool

## Do it first

Here are four values: `7`, `3.14`, `"Selam"`, `True`. They look different because they ARE different kinds of thing - and Python treats each kind differently: you can divide the first two, join the third, and ask questions of the fourth. Those kinds are called data types. Predict before reading: what does `+` do to the first value, and what does it do to the third?

## Sub lesson 1 - int and float - the number types

A **data type** classifies **what values a variable can hold** and **what operations apply** to them.

- **int** - **whole numbers**: 7, -3, 42.
- **float** - **decimal numbers**: 3.14, 2.5.

Both use the **arithmetic operators**: `+` add, `-` subtract, `*` multiply, `/` divide, `//` **floor division**, `%` **modulus**, `**` **exponentiation** (power).

Three of them deserve care:

- `/` **keeps the fraction**: `7 / 2` is `3.5`.
- `//` returns **only the whole part of a quotient**: `7 // 2` is `3`.
- `%` returns **a division's remainder**: `7 % 2` is `1`.

## Sub lesson 2 - str - text, joined with +

**str** is a **sequence of characters in quotation marks** - text: `"Selam"`.

Its operator here is `+`, and on strings `+` **joins** them - **concatenation**: `"Sel" + "am"` gives `"Selam"`.

Hold the contrast tight: **`+` adds numbers but joins strings.** The symbol is the same; the type decides what it does.

## Sub lesson 3 - bool - True or False

**bool** holds exactly two values: **True** or **False**. Its operators are the logic words: **and**, **or**, **not**.

```
>>> type(True)
<class 'bool'>
```

## Sub lesson 4 - type() - and a variable changing type

A variable **takes its type from the value assigned** to it - assign 7 and it is an int; assign 3.14 and it is a float. The **`type()` function reveals** a value's type:

```
>>> x = 7
>>> type(x)
<class 'int'>
```

And a variable can **change type entirely when reassigned** a value of another type:

```
>>> x = "Selam"
>>> type(x)
<class 'str'>
```

[Picture 18112 - the four types and their operators as four clean cards]

## Say it to your companion

Tell your companion the four types with one example each; what /, // and % each return; what + does to numbers and what it does to strings; and how type() settles an argument about a variable's type.

## Do It Yourself

1. Give one value of each type - int, float, str, bool - and write type() beside each with its expected answer.
2. Compute by hand: 7 / 2, 7 // 2, 7 % 2, 2 ** 3. Name the operator in each.
3. x = 10, then x = 10.5. What is type(x) after each line? Explain in one sentence.
