# XOR and XNOR gates — from basic gates

## Do it first
Build both gates from basic gate chips (or a logic simulator) — begin with the hands-on opening in hands-on.md before reading on. This lesson is the story of that activity.

## Sub lesson 1 — XOR — the difference detector

Exclusive-OR gives output 1 when exactly one input is 1 — when the inputs differ. Its truth table (00→0, 01→1, 10→1, 11→0) makes it the circuit of comparison: adders use it for the sum bit, parity checkers use it to flag a changed bit.

## Sub lesson 2 — XNOR — the agreement detector

Exclusive-NOR is XOR followed by NOT: output 1 when the inputs agree (00→1, 11→1) and 0 when they differ. Put side by side, the pair cover comparison both ways — difference and sameness each get a gate — and PTB teaches them as combinations, not as new primitives.

## Sub lesson 3 — Building them from basics

XOR assembles as (A AND NOT B) OR (NOT A AND B) — an OR of the two differing cases — and XNOR as its inversion, or as (A AND B) OR (NOT A AND NOT B), the two agreeing cases. The lesson's point is architectural: any truth table can be built by OR-ing the cases that give 1, from gates already in hand.

## The key ideas

- Exclusive-OR gives output 1 when exactly one input is 1 — when the inputs differ.
- Exclusive-NOR is XOR followed by NOT: output 1 when the inputs agree (00→1, 11→1) and 0 when they differ.
- XOR assembles as (A AND NOT B) OR (NOT A AND B) — an OR of the two differing cases — and XNOR as its inversion, or as (A AND B) OR (NOT A AND NOT B), the two agreeing cases.

## Say it to your companion
Tell your companion the lesson's one thing in your own words: combining the basic gates builds new logic: the XOR gate outputs 1 when its inputs differ, the XNOR when they agree — and each can be assembled from AND, OR and NOT gates, which is how control circuits are really made. If your companion can work the Do It Yourself items without looking back, the lesson has landed.

## Do It Yourself
1. Write XOR's truth table and state its rule in words.
2. A parity checker flags an odd number of 1s. Which gate chain does it extend?
3. Give the sum-of-cases expression for XNOR.
