# Comments — the # that the interpreter ignores

## Do it first

Run this program:

```python
# print("world")
print("hello")
```

Only `hello` prints — verified. The first line is fully written Python, yet it does nothing, because it begins with `#`. It is a **comment** — a note for human eyes that the interpreter steps over. Now comment out the second line too and run again: nothing prints at all.

## Sub lesson 1 — What a comment is — text for humans, ignored by the machine

**Comments** are descriptive text in source code that compilers and interpreters **ignore**. They are **not executable** and **not part of the program**. Their job is human: they make code more readable by **explaining what each part does**, serving as **notes or reminders** to the writer.

Earlier programs in this unit already carry comments inside working code — you have been reading them all along.

[Picture 31713 — a program with grey # lines the interpreter steps over, and an empty output beside a fully commented copy]

## Sub lesson 2 — Writing comments — every line starts with #

In Python every comment is denoted by the **hash symbol `#`** — anything after `#` on a line is ignored. A comment may be a **single line**, or **several lines provided every line starts with #**.

The taught uses:

1. **describing** code;
2. improving **readability**;
3. **preventing execution** of parts of code while testing.

The proof of the third use: a program in which **every line is commented out produces no output at all** when run — there is no executable statement left. Where only part is commented out, only the uncommented part executes. A good comment is **concise and clear**, saying what the program or that part does or outputs — the model: a one-line comment stating that the code prints 1 up to 5 and then exits the loop.

## Say it to your companion

Tell your companion what a comment is, its symbol, its three uses — and what a fully commented program prints.

## Do It Yourself

1. Add a describing comment above the even/odd program and run — output unchanged.
2. Comment out every line of a short program, run it, and write what prints (nothing).
3. Write the model-style comment for the count program: one line, concise, saying what it prints.
