# User-Defined Functions in Python

## Do it first

In every program so far, the same few lines keep coming back: greet the user, check a number, work out a total. Imagine copying those lines in ten places — and then finding a mistake in them. This lesson teaches the way out: write the job once, give it a name, and call the name.

## Sub lesson 1 — Writing your own function with `def`

Python comes with functions already made — `print`, `input`, `len` — called **built-in functions**. A **user-defined function** is one the programmer makes: a named block of code, written once, that does one job. You make it with the word **`def`**, the function's name, brackets, and a colon; the lines of the job go under it, **indented**:

```
def greet():
    print("Hello! Welcome to the program.")
```

Writing the function only *teaches Python the name* — nothing runs yet. The job runs when the function is **called**, by writing its name with brackets:

```
greet()
greet()
```

Two calls, two greetings, one written block. That is the function's bargain: write once, call anywhere, and when the job must change, change it in **one place** and every call follows.

[Picture — a picture of a Python function drawn as a labelled machine: the `def` line as its name plate, the indented body as the works inside, an arrow marked "call" going in and an arrow marked "return" coming out]

## Sub lesson 2 — Values in, a result back — parameters and `return`

A function that can only ever do exactly the same thing is useful, but a function that works on **values it is handed** is far stronger. The names in the `def` brackets are **parameters** — empty slots waiting for values. At each call, the values you pass are the **arguments**, and they fill the slots for that run:

```
def square(number):
    return number * number

print(square(3))
print(square(10))
```

The word **`return`** hands a result back to the place that called the function. What comes back can be printed, as above, or stored — `area = square(5)` — and used in more work. Notice the difference from the first part: `print` *shows* a value and it is gone; `return` *hands it back* so the program can keep it. Same body, different arguments, different results: that is a function earning its name.

[Picture — a picture of one function called three times with three different values going in, and three results coming back]

## Say it to your companion

Tell your companion, in your own words: a user-defined function is a job you write once with `def` and an indented body, then call by name as often as you like; parameters are the slots values go in through at each call, and `return` hands the result back to be stored and used. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: write a function with `def` and an indented body, and call it twice. Do this with a real example from your own home, school or street, and write or say how you know it is right.
2. Show it, don't just say it: explain why defining a function does not run it. Do this with a real example from your own home, school or street, and write or say how you know it is right.
3. Show it, don't just say it: write a function with a parameter and call it with two different arguments. Do this with a real example from your own home, school or street, and write or say how you know it is right.
4. Show it, don't just say it: use `return` to hand a result back, store it in a variable, and use it in one more line. Do this with a real example from your own home, school or street, and write or say how you know it is right.
