# Procedure Calls in Pascal

## Do it first

A program that repeats the same work inline grows unreadable. Grade 8 and Grade 10 both formalise the alternative as an instruction of its own: the call — say the name, hand over the values, and the named work runs.

## Sub lesson 1 — The call — name plus actual parameters

A **procedure call** is an instruction written as the procedure's **name followed by its actual parameters in brackets**: `PrintRow(i, total);`. Executing the call means: the actual parameters' values are handed to the procedure, its body runs as a composed action, and control **returns to the instruction after the call**. Standard procedures are called the same way — `writeln(x)` is a call to the built-in writing procedure. A call is one instruction in the calling program, however many instructions the called body holds.

In your mind's eye: the call. Name plus actual parameters.

[Picture 47417 — the call. Name plus actual parameters]

## Sub lesson 2 — Why calls rule programs — written once, used everywhere

The call is the hinge of structured programming. Work **written once** as a procedure can be **called from many places** — with different actual parameters each time, so one body serves many data. The main program becomes a readable plan of named deeds: read, compute, print — each name a call. And a fault inside a procedure is fixed **once**, in its body, repairing every call at a stroke. Grade 12 will build the full subprogram theory on this Grade 8 instruction.

In your mind's eye: why calls rule programs — written once, used everywhere.

[Picture 47418 — why calls rule programs — written once, used everywhere]

## Say it to your companion

Tell your companion, in your own words: A **procedure call** is an instruction written as the procedure's **name followed by its actual parameters in brackets**: `PrintRow(i, total);`. Executing the call means: the actual parameters' values are handed to the procedure, its body runs as a composed action, and control **returns to the instruction after the call**. Standard procedures are called the same way — `writeln(x)` is a call to the built-in writing procedure. A call is one instruction in the calling program, however many instructions the called body holds. The call is the hinge of structured programming. Work **written once** as a procedure can be **called from many places** — with different actual parameters each time, so one body serves many data. The main program becomes a readable plan of named deeds: read, compute, print — each name a call. And a fault inside a procedure is fixed **once**, in its body, repairing every call at a stroke. Grade 12 will build the full subprogram theory on this Grade 8 instruction. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The procedure's name followed by its actual parameters in brackets. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The values are handed over, the body runs, and control returns to the instruction after the call. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Yes — a call to the built-in writing procedure. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: One — however many the called body holds. Do this with a real example of your own and write or say how you know it is right.
