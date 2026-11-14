# Libraries and Packages in Python

## Do it first

Your own functions let you reuse *your* code. But a square root, a drawing turtle, a table of data from a file — must every programmer in the world write those from nothing, every time? This lesson opens the shared shelves: code written once by someone, kept in bundles, and brought into your program with one word.

## Sub lesson 1 — Modules, packages and libraries — ready-made code, in growing bundles

Python programmers share code in bundles of three sizes. A **module** is a single Python file holding functions and other code on one theme — `math` is a module of mathematical functions, and any `.py` file you write is a module too. A **package** is the next size up: an organised **folder of related modules**, kept together so a bigger tool stays tidy — one module for reading files, another for working out results, all under one package name. A **library** is the whole collection a programmer draws on: packages and modules gathered and kept ready. Python arrives with a large collection already installed — the **standard library**, holding modules like `math`, `turtle` and `random` — and more libraries can be added, like **pandas**, the library used for handling tables of data from files. Small to large: module, package, library.

[Picture — a picture of the three bundles nested: one module file, a package folder holding several module files, and a library shelf holding several packages]

## Sub lesson 2 — Bringing code in with `import`

Bundled code does nothing for your program until you bring it in, and the bringing word is **`import`**:

```
import math

print(math.sqrt(16))
```

`import math` loads the module. Its functions are then called **through the module's name**, with a dot: `math.sqrt(16)` says "the `sqrt` that lives in `math`" — which keeps things clear when two modules offer functions with the same name. If you want one function by its bare name, bring in just that one:

```
from math import sqrt

print(sqrt(16))
```

Both programs print 4.0; only the *call* differs — dotted through the module, or bare after a `from ... import`. Either way, the square-root code itself was written once, by the library's makers, and is shared by every program that imports it: that sharing is the whole point of libraries.

[Picture — a picture of a program with an arrow marked `import math` bringing a toolbox labelled math into it, and the call `math.sqrt(16)` reaching into the toolbox]

## Say it to your companion

Tell your companion, in your own words: a module is one file of ready-made code, a package is a folder of related modules, and a library is the whole collection — the standard library comes with Python, and libraries like pandas are added; `import` brings a module in, and its functions are called through its name, like `math.sqrt(16)`, unless a `from ... import` brings one in by its bare name. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a module, a package and a library each are, in growing order. Do this with a real example from your own home, school or street, and write or say how you know it is right.
2. Show it, don't just say it: import the `math` module and call one of its functions through the module's name. Do this with a real example from your own home, school or street, and write or say how you know it is right.
3. Show it, don't just say it: bring `sqrt` in with `from math import sqrt` and call it by its bare name. Do this with a real example from your own home, school or street, and write or say how you know it is right.
4. Show it, don't just say it: name one job that a library does for the programmer — pandas and file handling — and say what the programmer is saved from writing. Do this with a real example from your own home, school or street, and write or say how you know it is right.
