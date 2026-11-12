# Python comments - notes inside code

## Do it first

Read this line of code: `area = 3.14 * radius ** 2`. Now imagine the person who wrote it left you a note right inside the code: *# ** means power*. Would the note change what the program does - or only what YOU understand? That difference is this short lesson's whole content.

## Comments - the # lines

A **comment** is a **note written inside code to explain it**. In Python a comment **begins with the hash symbol `#`**:

```python
# Find the area of a circle
radius = 3
area = 3.14 * radius ** 2   # ** means power
print(area)
```

Python **never executes** comment lines. They are **skipped** - written for the human reader, not for the machine. The program above runs exactly as it would without them, and still prints 28.26.

Use comments to say *why* a line is there, or what a hard part means - future readers, including future you, will be grateful.

[Picture 18117 - a short program with its greyed comment lines marked not run]

## Say it to your companion

Tell your companion: what a comment is, the symbol it begins with, and what Python does with it. Then add a comment of your own to one line of the circle script and read the pair aloud - line, then note.

## Do It Yourself

1. Add a comment above every line of the circle script explaining what the line does. Cover the comments and check: the program's output is unchanged - 28.26.
2. Write a misleading comment on purpose, then fix it. A wrong comment is worse than none - say why in one sentence.
3. Find the two comments in this lesson's code block and write what each one explains.
