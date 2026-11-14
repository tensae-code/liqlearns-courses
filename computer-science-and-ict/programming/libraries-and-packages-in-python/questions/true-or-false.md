# Libraries and Packages in Python — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) Any `.py` file you write is itself a module.**
**Answer: True** — A module is a single Python file of code; yours count, not only the famous ones.

**2. (Sub lesson 1) pandas is part of Python's standard library and never needs installing.**
**Answer: False** — pandas is an added library; the standard library is what arrives with Python itself.

**3. (Sub lesson 2) After plain `import math`, calling bare `sqrt(16)` works.**
**Answer: False** — The call must go through the module's name: `math.sqrt(16)`. The bare name needs `from math import sqrt`.

**4. (Sub lesson 2) Importing a module copies its code into your file.**
**Answer: False** — Import loads and links the module; the code stays in its own file and is shared.
