# The Python shell - first lines with print()

## Do it first

Do it now, on paper if no computer is near: imagine the shell shows `>>>`. You write `5 + 6` and press Enter. What do you think appears - and what appears after it? Then imagine you write `5 +` and press Enter instead. This lesson is those two moments, plus the one function that prints words on the screen: print().

## Sub lesson 1 - The >>> prompt - type, Enter, answer

The interpreter's working face is the **Python shell**. The **`>>>` prompt** is where code is typed. You type a line, **press Enter** - the line **runs** - and the **prompt comes back**, ready for the next line. That rhythm - type, Enter, answer, prompt again - is the whole skill of this place.

[GIF 18106 - typing at the prompt, pressing Enter, the answer appearing]

## Sub lesson 2 - Expressions in the shell - valid and invalid

Type a **valid expression** and the shell **evaluates it and shows its value**:

```
>>> 5 + 6
11
```

Type an **invalid** one and the shell **raises a syntax error** - the rules were broken, so there is no value to show:

```
>>> 5 +
SyntaxError: invalid syntax
```

## Sub lesson 3 - print() - displaying output, and IDLE's colours

Output is produced with the **`print()` function**. Here it displays a **string** - text in quotation marks:

```
>>> print("Selam")
Selam
```

IDLE helps your eyes with a **colour code**: **output in blue, functions in purple, strings in green**.

Your turn, exactly as the practice sets it: use print() to display **your own full name**.

[Picture 18105 - a shell with a typed line, its blue answer, and the prompt waiting again]

## Say it to your companion

Talk your companion through one full shell moment: where you type, what Enter does, where the answer appears, and what returns when it is done. Then show them print() displaying your name, and name IDLE's three colours.

## Do It Yourself

1. On paper, write the shell session that adds 5 and 6 - prompt, your line, the answer, the prompt again.
2. Predict, then write, what the shell does with `5 +`. Name the kind of error.
3. Write the one line that displays your own full name with print(). Say which part IDLE would colour green, and which part purple.
