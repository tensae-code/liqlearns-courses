# Statements and expressions - telling them apart

## Do it first

Sort these three lines before reading: `x = 5`, `x + 2`, `print(x + 2)`. One of them silently stores. One of them IS a value waiting to be read. One of them speaks out loud. Which is which - and what single test separates the talker from the value? This lesson names the two families every line of Python belongs to.

## Sub lesson 1 - Statements - instructions that are executed

A **statement** is an **instruction the interpreter executes** - it tells Python to DO something.

Two kinds are taught here:

- The **assignment statement** - `x = 5` - **stores a value and produces no output**. It is silent.
- The **print() statement** - `print(x + 2)` - **displays what it is given**.

Other statement kinds exist - **if, while and for** are named - but they are **Grade 12 material**, left for that year.

## Sub lesson 2 - Expressions - evaluated to a value

An **expression** is **what the interpreter evaluates to a value**. It does not give an order; it IS worth something. Its forms:

- a **literal value**: `7`, `"Selam"`;
- a **variable**: `x`;
- a **complex combination** of literals, variables and operators: `x + 2`, `3.14 * radius * radius`.

## Sub lesson 3 - Shell vs editor - where the value shows

Here is the practical difference, and it explains behaviour you have already seen:

- **Typed into the shell**, an expression **shows its value at once**: type `x + 2` and 7 appears.
- **Written in the text editor**, an expression **shows nothing unless placed inside print()**: a script line of bare `x + 2` runs, evaluates - and displays nothing.

Statements execute in both places; expressions only *show* themselves in the shell.

[Picture 18114 - one script with assignments standing silent and its print lines speaking, expressions circled]

## Say it to your companion

Tell your companion: a statement in one sentence with its two taught kinds; an expression in one sentence with its three forms; and the shell-vs-editor rule for a bare expression.

## Do It Yourself

1. Sort into statement or expression: `radius = 3`, `radius * 2`, `print(radius)`, `3.14`. Write the family beside each.
2. A script contains the line `x + 2` alone and prints nothing when run. Explain why, in two sentences.
3. Write one assignment statement, one print() statement, and one complex expression of your own.
