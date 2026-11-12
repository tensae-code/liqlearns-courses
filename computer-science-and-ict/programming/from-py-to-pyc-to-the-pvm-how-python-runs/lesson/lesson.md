# From .py to .pyc to the PVM — how Python runs

## Do it first

Save a one-line program as `hello.py` and run it. You never made a second file — yet inside the interpreter, your source was translated and carried out by a machine that does not exist as metal. Follow the GIF: `hello.py` becomes bytecode, and the bytecode runs. Three stages, one invisible pipeline — this lesson makes it visible.

## Sub lesson 1 — Source to bytecode — .py becomes .pyc

The process, in the book's steps:

1. You **write and save source code** with the **`.py`** extension.
2. That source **compiles** — a simple translation — into **bytecode**.
3. The bytecode is usually stored in a **`.pyc`** file, which **can be updated when necessary**.

You do not run the .py file directly on the hardware — the bytecode is what travels onward.

[Picture 31716 — a three-stage pipeline — source file, bytecode file, virtual machine executing]

[GIF 31729 — a file transforming .py to .pyc to running output]

## Sub lesson 2 — The PVM — bytecode executed one instruction at a time

The bytecode is **loaded into the Python runtime** and interpreted by the **Python Virtual Machine (PVM)** — the **runtime powerhouse** that **reads each bytecode instruction one by one and executes the operation it indicates**.

Three closing facts:

- Bytecode interpretation is **automatic** — you never trigger it by hand.
- The PVM is **part of the installed Python system**.
- **Running the program is the last step** of the interpreter process.

## Say it to your companion

Walk your companion through the pipeline with the GIF: source saved, bytecode compiled, PVM executing one instruction at a time.

## Do It Yourself

1. Draw the pipeline .py → .pyc → PVM → output and label who does each step.
2. Explain why the .pyc file 'can be updated when necessary' — what changes it? (The source.)
3. Say the PVM's job in one sentence from memory.
