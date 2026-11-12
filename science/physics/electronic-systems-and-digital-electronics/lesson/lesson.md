# Electronic systems and digital electronics

## Do it first
Before you read: think of a street light that switches itself on at dusk. Something sensed the darkness, something decided, something switched. Name those three somethings as best you can. Then think of a phone counting: it never uses the number seven the way you write it — inside, everything is just two levels, on and off. This lesson gives both ideas their proper names.

## Sub lesson 1 — Electronic systems — input, process, output

Every electronic system has the same skeleton: **input → process → output**. The input block uses a **sensor** to turn a physical quantity into an electrical signal — a light-dependent resistor senses brightness, a thermistor senses temperature, a microphone senses sound, a switch senses a finger. The process block decides what the signal means and what to do — in a simple system a transistor or a comparator circuit; in a larger one a processor following a program. The output block turns the decision back into the world: a lamp, a buzzer, a motor, a heater, a display. The dusk street light is the skeleton in one object: light sensor in, decision in the middle, lamp out.

## Sub lesson 2 — Digital signals — the world in two levels

An analogue signal can take any value in a range, sliding smoothly like the voltage from a microphone. A **digital** signal is restricted to two levels only — high and low, written **1** and **0**, on and off. Two levels are enough to count and to reason: numbers are written in **binary**, place values 1, 2, 4, 8…, so 1011 is 8 + 2 + 1 = 11. Two-level signals are hard to spoil — a little noise cannot turn a clear high into a low — and they can be copied perfectly, stored, and processed by circuits that only ever ask one question: is it 1 or is it 0?

## Sub lesson 3 — Logic gates — deciding with 1s and 0s

The process blocks of digital electronics are built from **logic gates**, circuits with one or two inputs and one output, each following a fixed rule. **NOT**: output is the opposite of the input. **AND**: output is 1 only when input A *and* input B are both 1. **OR**: output is 1 when A *or* B (or both) is 1. Each rule is written completely in a **truth table** — every possible input row with its output. Gates combine: an AND feeding a NOT gives NAND, and whole computers are, at the bottom, millions of such decisions a second. A burglar alarm that sounds when a sensor is 1 AND the system is armed is AND logic doing a real job.

## The key ideas

- An electronic system is input (a sensor) → process (a decision) → output (a lamp, buzzer, motor, display)
- A digital signal has only two levels, 1 and 0; numbers are carried in binary with place values 1, 2, 4, 8…
- NOT inverts, AND needs both inputs 1, OR needs at least one input 1; each gate's whole rule fits in a truth table
- Two-level signals resist noise and copy perfectly — that is why modern processing is digital

## Say it to your companion
Tell your companion: An electronic system is input (a sensor) → process (a decision) → output (a lamp, buzzer, motor, display); A digital signal has only two levels, 1 and 0; numbers are carried in binary with place values 1, 2, 4, 8…; NOT inverts, AND needs both inputs 1, OR needs at least one input 1; each gate's whole rule fits in a truth table; Two-level signals resist noise and copy perfectly — that is why modern processing is digital. If your companion can work the Do It Yourself tasks without looking back, the lesson has landed.

## Do It Yourself
1. Write the numbers 5, 9 and 14 in binary, showing the place values (8, 4, 2, 1) you used for each.
2. Write the full truth table for an AND gate and for an OR gate (inputs A and B, all four rows), and mark the single row where their outputs differ in the AND table's favour — then the rows where OR gives 1 but AND gives 0.
3. Design, in words and a gate name, the logic for a greenhouse fan that must run when the temperature sensor is 1 (too hot) AND the manual enable switch is 1. Which gate, and what happens in each of the four input combinations?
