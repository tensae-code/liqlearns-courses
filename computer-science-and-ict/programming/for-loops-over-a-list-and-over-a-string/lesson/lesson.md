# For loops over a list and over a string

## Do it first

Run both programs and watch the difference:

```python
regions = ["Afar", "Oromia", "Sidama"]
for region in regions:
    print(region)
```

```python
for letter in "Hi":
    print(letter)
```

The first prints whole names — `Afar`, `Oromia`, `Sidama`. The second prints single letters — `H`, then `i`. Same loop, two kinds of sequence. Watch the GIF: characters leave a word one at a time.

## Sub lesson 1 — Over a list — item by item

A for loop over a **list** works item by item. The program walks a list of regional states, assigning each in turn — first **Afar**, last **Sidama** — to the temporary `region` variable and printing it, continuing while an element remains. (This walking-while-items-remain is what the unit calls a condition-controlled loop.)

If a loop never meets a condition that stops it early, it prints **everything** in the list.

[Picture 31709 — a word breaking into single letters passing one by one through a loop, beside a list walked item by item]

[GIF 31725 — characters leaving a word one at a time]

## Sub lesson 2 — Over a string — character by character

Over a **string**, the loop is an iterable walk **character by character**: each iteration stores one character in a `letter` variable and prints it, continuing to the string's last character.

```python
for letter in "Hi":
    print(letter)
```

Output — verified:

```
H
i
```

## Say it to your companion

Tell your companion how the same for shape walks a list of names and a string of letters — and what the temporary variable holds on each pass.

## Do It Yourself

1. Run the regions program and add one more region to the list. Predict the new last line.
2. Print your own first name one letter per line with a for loop.
3. Print the alphabet string one letter per line; then print it on ONE line by changing the print ending.
