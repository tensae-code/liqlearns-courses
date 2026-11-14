# Libraries and Packages in Python — short answer

Answer in a sentence or two, in your own words — or in code where the question asks for code.

**1. (Sub lesson 1) Put the three bundles in growing order and say what each holds.**
**Answer:** Module, package, library. A module is one Python file of code; a package is an organised folder of related modules; a library is the whole collection of packages and modules a programmer draws on.

**2. (Sub lesson 2) A program has `import math` at the top and then calls `sqrt(25)`. It fails with a name error. Give both fixes.**
**Answer:** Either call it through the module — `math.sqrt(25)` — or change the import to `from math import sqrt`, after which the bare call `sqrt(25)` works.

**3. (Sub lesson 2) A programmer uses pandas to handle data files instead of writing the file-handling code themselves. What does using the library save them, in one or two sentences?**
**Answer:** It saves writing a whole file-reading and table-handling tool from nothing: pandas' makers wrote and tested that code once, and every program that imports pandas builds on it instead of starting again.
