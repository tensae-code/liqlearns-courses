# Variables - storing values in memory

## Do it first

A program adds two numbers a user types, then needs the total again three steps later. Where does the total live in between? It cannot float in the air - it must be kept somewhere, with a name so the program can find it again. That named somewhere is this lesson's one thing. Do the first assignment in your head now: `x = 5` - what is stored, and where?

## Sub lesson 1 - What a variable is

A **variable** is a **computer memory location for storing data**. Use one whenever **user data** or **intermediate results** must be **kept** - a typed radius, a half-finished total, an area waiting to be printed.

Think of a labelled box in memory: the label is the name, the thing inside is the value.

[Picture 18109 - a labelled memory box whose contents change as assignments run]

## Sub lesson 2 - Assignment - the = operator

In Python a variable is **created together with its value** - there is no empty box first. The tool is the **assignment operator, `=`**:

```
>>> x = 5
```

Read it in its true direction: `=` **puts the value or expression on its right** - here 5 - **into the variable named on its left** - here x. The right side is worked out first; the left side receives it.

## Sub lesson 3 - Seeing the value - and replacing it

To see what a variable holds, **type its name alone at the prompt**:

```
>>> x
5
```

And a variable can later be **reassigned a different value**:

```
>>> x = 9
>>> x
9
```

The new assignment **replaces** the old value - the box now holds 9, and the 5 is gone.

[GIF 18110 - a box's contents being replaced by a new assignment]

## Say it to your companion

Tell your companion: what a variable is; how `x = 5` is read (right side into the left name); how to see a variable's value; and what `x = 9` after `x = 5` leaves in the box.

## Do It Yourself

1. Create a variable age with your own age, using =. Then show its value by name alone.
2. Start with score = 10. Reassign score to 25. What does typing score show now, and what happened to the 10?
3. A program must keep a user's typed name and a half-finished total. How many variables does it need, and why?
