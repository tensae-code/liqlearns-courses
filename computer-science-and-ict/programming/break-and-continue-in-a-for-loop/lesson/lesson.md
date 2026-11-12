# break and continue — leave early, or skip one

## Do it first

Two programs, one list, opposite tricks. Run both:

```python
for lang in ["Amharic", "Python", "English"]:
    if lang == "Python":
        break
    print(lang)
```

```python
for lang in ["Amharic", "Python", "English"]:
    if lang == "Python":
        continue
    print(lang)
```

First prints only `Amharic` — the loop LEFT at Python. Second prints `Amharic` and `English` — Python was SKIPPED, the loop carried on. Watch the GIF: a runner exits at break, then hops one item at continue.

## Sub lesson 1 — break — stop the loop now

The **`break`** keyword stops a loop **before it has looped through all items**. In the program above, the loop exits the moment the loop variable's value is the language `"Python"` — English is never visited. Output: `Amharic` only — verified.

[Picture 31710 — a loop track with an exit gate labelled break and a hop-over labelled continue]

[GIF 31726 — a loop runner exiting at break, then in a second pass hopping one item at continue]

## Sub lesson 2 — continue — skip this one, carry on

The **`continue`** keyword stops **only the current iteration** and continues with the next item. Python is skipped; English still prints. Output: `Amharic`, `English` — verified.

break leaves the track. continue hops one hurdle and keeps running.

## Say it to your companion

Act out both keywords for your companion with the GIF: exit the track at break; hop and continue at continue.

## Do It Yourself

1. Modify the earlier string program so it breaks at a chosen letter.
2. Modify the language program so continue skips a different language.
3. Predict, then run: break at the FIRST item — what prints? (Nothing.)
