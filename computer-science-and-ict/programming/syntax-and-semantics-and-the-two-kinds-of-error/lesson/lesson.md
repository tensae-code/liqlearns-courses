# Syntax and semantics - and the two kinds of error

## Do it first

Two cooks follow two recipes. The first recipe says "add two cups of" - and stops. The sentence itself is broken; anyone can see it. The second recipe is written perfectly - but it says salt where it should say sugar. Nobody sees anything wrong until the cake is tasted. Programming has exactly these two kinds of mistake. Learn their names now.

## Sub lesson 1 - Syntax - the rules of the language

Every programming language has **syntax**: its **rules** - the **structure or grammar** that programs must **strictly follow**. Just as a sentence must be built the grammar's way, a program must be built the language's way.

## Sub lesson 2 - Semantics - the meaning

Beside the rules stands **semantics**: the **meaning** of a program's elements, and **what they do**. Syntax asks *is it built correctly?* Semantics asks *does it mean the right thing?*

## Sub lesson 3 - Syntax errors - the translator stops you

Break a syntax rule, and the **compiler or interpreter produces an error message**. That is a **syntax error**. The translator refuses to carry the broken program further - the mistake is announced, with help to find it.

[Picture 18103 - a syntax error stopped, a logic error running to a wrong answer]

## Sub lesson 4 - Logic errors - the quiet wrong answer (teacher guide - evidence)

A program can obey **every** syntax rule, **run** - and still **do the wrong thing**. That is a **logic error**. It is tied to **semantics** - the meaning is wrong, not the building.

**No translator catches it**, and that is why it is **far harder to find and fix**. The unit's own example: a circle's area worked out with the **wrong formula** - the program runs happily and prints a **quietly wrong answer**.

Why is it so much harder? *(Teacher guide - evidence:)* the translator **catches a syntax error and even points to its kind and place**; but a logic error **lets the program run as if nothing were wrong**, so **only a human watching the behaviour** notices it is not what was expected.

## Say it to your companion

Tell your companion: syntax in one sentence, semantics in one sentence, then the two errors - which one is announced by the translator, and which one only a watching human can catch, and why.

## Do It Yourself

1. Write one broken instruction (a syntax mistake in plain English) and one perfectly written but wrong instruction (a logic mistake). Label each.
2. A program prints a circle's area as 12 when the true area is 28.26, and it never showed an error message. Which kind of error is it? Write the name and the reason.
3. In your own words: why does the translator's error message make syntax errors easier to fix?
