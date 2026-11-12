# Program flow control — the order code runs in

## Do it first

Think of your morning: wake up, wash, eat breakfast, brush your teeth — one step after another. Now think of a rainy morning: IF it rains, you take a different road. And think of washing ten cups: the same wash, again and again. You have just named the three ways a program can flow. Watch the GIF: one dot runs straight, one splits, one loops.

## Sub lesson 1 — Three ways code can flow

**Flow control** is the order in which a program's code executes. Three constructs regulate it:

- **Sequential** — a simple list of statements executed in the order given. Variables, printing and keyboard input are sequential work.
- **Branching (conditional)** — the program tests a condition and chooses which block runs next.
- **Loop (iteration)** — a block runs again and again, a fixed number of times or until a condition is satisfied.

Every program you will ever write is built from these three. This unit teaches branching and loops in Python; sequential work you already know.

[Picture 31700 — one program path shown three ways — straight, branching, looping back]

[GIF 31720 — an execution dot travelling straight, then splitting, then looping]

## Sub lesson 2 — Syntax and semantics

A language's **syntax** is its set of rules defining how instructions are written. Its **semantics** is the meaning of those rules — what a correctly written instruction actually does.

Think of grammar: an English statement must end with a full stop — that is syntax. What the sentence means is its semantics. In Python, writing `print` without its brackets breaks the rules and gives a syntax error; the meaning of the correct command `print("Hello")` is that whatever sits inside the quotes is displayed on screen, without the quotes.

Two Python facts to hold: Python relies on **indentation** to define scope — which lines belong to a block — and on **new lines** to complete a command.

An **expression** is a statement that evaluates to a value or to true/false. All expressions are statements, but not all statements are expressions. Logical expressions use `or`, `not` and `and`; comparison expressions use `>`, `<` and `==`.

## Say it to your companion

Tell your companion the three constructs in order, give a morning-routine example of sequential flow, and explain syntax versus semantics with the full-stop example.

## Do It Yourself

1. Sort six morning actions into order and say which flow construct a plain morning uses.
2. Write one real-life example each of branching and of looping.
3. Run `print("Hello")` in the shell, then run it without the brackets and name the kind of error.
