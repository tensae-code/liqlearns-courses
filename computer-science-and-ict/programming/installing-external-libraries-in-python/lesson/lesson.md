# Installing External Libraries in Python

## Do it first

Python arrives with a large standard library — but the data unit needs libraries it does not carry. This lesson learns how outside code is brought in, and what to check when it arrives.

## Sub lesson 1 — Why external libraries, and where they live

**External libraries** are packages written by others, beyond the standard library — for data work, the table and charting libraries of this unit. They live in a public **index (PyPI)** — a warehouse of packages, each with a name, versions and authors — and are fetched from it by name. Installing one makes its modules importable like any standard module; the difference is only the journey: standard modules arrive with Python, external ones are fetched, chosen and trusted by you.

In your mind's eye: why external libraries, and where they live.

## Sub lesson 2 — Installing — pip, versions, and care

The installer is **pip**: `pip install <name>` fetches and installs; the import in the program then works as usual. The care around it: install the **named** package (sound-alike names are a known trap — a mistyped name can fetch a stranger's, even a hostile, package), mind **versions** (a program may need the version its book used), install into the environment the work actually uses, and record what was installed so the work can be rebuilt on another machine. Jordan places installing inside the data lesson because the unit's first practical act is exactly this: before the data, the tools; before the tools, the trust.

In your mind's eye: installing — pip, versions, and care.

## Say it to your companion

Tell your companion, in your own words: **External libraries** are packages written by others, beyond the standard library — for data work, the table and charting libraries of this unit. They live in a public **index (PyPI)** — a warehouse of packages, each with a name, versions and authors — and are fetched from it by name. Installing one makes its modules importable like any standard module; the difference is only the journey: standard modules arrive with Python, external ones are fetched, chosen and trusted by you. The installer is **pip**: `pip install <name>` fetches and installs; the import in the program then works as usual. The care around it: install the **named** package (sound-alike names are a known trap — a mistyped name can fetch a stranger's, even a hostile, package), mind **versions** (a program may need the version its book used), install into the environment the work actually uses, and record what was installed so the work can be rebuilt on another machine. Jordan places installing inside the data lesson because the unit's first practical act is exactly this: before the data, the tools; before the tools, the trust. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Packages by others, beyond the standard library. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In a public index — PyPI. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Importable like any standard module. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Standard arrive with Python; external are fetched and trusted by you. Do this with a real example of your own and write or say how you know it is right.
