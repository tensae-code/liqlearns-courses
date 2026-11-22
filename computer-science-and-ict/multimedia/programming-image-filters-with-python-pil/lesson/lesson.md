# Programming Image Filters with Python PIL

## Do it first

Here is an image so small you can hold it: nine pixels, each written as its RGB triple — (200, 60, 40), (30, 90, 160), and so on. A grey pixel is one whose three numbers are equal. Invent a rule that turns any triple into a fair grey triple, and apply it to all nine pixels by hand. It took you a minute for nine pixels; a phone photo has twelve million. Keep your rule — the lesson shows the program that applies exactly your rule to every pixel of a real image, and the library that makes it a few lines long.

## Sub lesson 1 — Opening an image and reaching its pixels

The library is **Pillow**, the modern form of **PIL** (the Python Imaging Library). With it, an image file stops being a sealed object: `Image.open("photo.jpg")` loads it as an **image object** that knows its **size** (width and height in pixels) and its **mode** (for a colour photo, "RGB"). Calling `load()` on it gives the program the pixels themselves, arranged as a grid addressed by coordinates: `pixels[x, y]` returns the RGB triple at that column and row — and the same address accepts a new triple, which changes the image. That is the whole doorway: read a triple, write a triple. Everything else is walking the grid.

[Picture — a photo beside a magnified corner where the pixels show as a grid of RGB triples, one cell highlighted at its (x, y) address]

## Sub lesson 2 — Building filters pixel by pixel

A **filter** is a rule applied to every pixel, and two nested loops do the applying: for each column x, for each row y, read the triple, compute the new one, write it back. The rules are arithmetic on the triple. **Greyscale:** replace the three numbers by their average — (200, 60, 40) becomes (100, 100, 100), a grey of the same brightness. **Negative:** subtract each number from 255 — (200, 60, 40) becomes (55, 195, 215). **Darken:** multiply each by the same fraction. **Threshold:** if the average passes a limit, write white, else black — a two-tone image. France's SNT book has you build these in the photography theme's En codant strand, on real photos, and the discipline it teaches matters as much as the effects: work on a copy, and **save under a new name**, because a filter destroys the numbers it replaces — the original photo, once overwritten, does not come back.

[Picture — one photo shown four times: original, greyscale, negative, threshold — with the rule for each written underneath]

## Say it to your companion

Tell your companion, in your own words: Pillow opens an image as a grid of RGB triples a program can read and write by coordinates; a filter is a rule plus two loops over all the pixels; greyscale averages the triple, negative subtracts from 255; and you always save under a new name. Apply the greyscale rule to one triple aloud as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: open an image with Pillow and state its size and mode. Do this with a real example of your own — in a real Python program with Pillow, on a photo of your own — and write or say how you know it is right.
2. Show it, don't just say it: read the RGB triple at a chosen (x, y) position and write a new triple there. Do this with a real example of your own — in a real Python program with Pillow, on a photo of your own — and write or say how you know it is right.
3. Show it, don't just say it: write the two loops that visit every pixel of an image. Do this with a real example of your own — in a real Python program with Pillow, on a photo of your own — and write or say how you know it is right.
4. Show it, don't just say it: build and run a greyscale filter and a negative filter, saving each result under a new name. Do this with a real example of your own — in a real Python program with Pillow, on a photo of your own — and write or say how you know it is right.
