# Writing a simple Python program - input, process, print

## Do it first

Everything in this unit now joins into one whole program - the kind that talks with its user. It will ask a question, wait for an answer, do maths, and report back. Before reading: a user types 3 when the program asks for a radius. Is that 3 a number Python can do maths with straight away? One trap waits there - this lesson springs it and disarms it. Write the program with your own hands, in the book's order.

## Sub lesson 1 - Functions, input() and print()

A **function** is a **piece of code that does a task**, **called by name**, **taking input data** and **optionally returning output**. You have already called two: print() and type(). Now the third:

- **`print()`** displays **any expression's value** - and **several comma-separated values print on one line**: `print("Area:", 28.26)` shows `Area: 28.26`.
- **`input()`** shows its **prompt string**, **waits** for the user to type and press **Enter**, and **returns what was typed - always as a string**.

That last clause is the trap and the key: a typed number arrives as a **string**, so **a needed number must be converted** before maths.

## Sub lesson 2 - The circle program - separate lines (doing)

The worked example reads a circle's radius, converts it, and prints both results - first on **separate lines**:

```python
radius = float(input("Enter the radius: "))
area = 3.14 * radius ** 2
circumference = 2 * 3.14 * radius
print(area)
print(circumference)
```

Run it and type **3**:

```
Enter the radius: 3
28.26
18.84
```

Read the first line slowly: input() returns the string `"3"`, and **float() converts it** inside the same statement - input, conversion, storage in one line.

[GIF 18116 - typing a radius at the prompt and the two answers printing]

## Sub lesson 3 - The same answers on one line each (doing)

Now the **combined form** - each answer **on one line with its label**, using comma-separated values:

```python
print("Area:", area)
print("Circumference:", circumference)
```

```
Area: 28.26
Circumference: 18.84
```

Same program, friendlier output. The closing practice stands ready in the same shape: a **product-of-two-numbers** program, and a **BMI program** from keyboard weight and height.

[Picture 18115 - the circle program as input, process and print]

## Say it to your companion

Tell your companion the whole shape: what a function is; what input() does step by step and what it always returns; why float() wraps the input() call; and the two print forms - separate lines, then label-and-value on one line each.

## Do It Yourself

1. Write the circle program from memory. Run it mentally with radius 2 and write the two outputs (area 12.56, circumference 12.56).
2. Write the product-of-two-numbers program: read two numbers with input(), convert, multiply, print the product.
3. A program does radius = input("Radius: ") and then 3.14 * radius ** 2 - and crashes. Explain the fault and write the fixed first line.
