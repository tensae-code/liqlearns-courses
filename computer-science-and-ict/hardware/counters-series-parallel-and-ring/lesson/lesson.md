# Counters — Series, Parallel and Ring

## Do it first

Tap the desk steadily — one tap per second — and count the taps. Each tap is a pulse, and the count is the number of pulses so far. A machine needs the same ability: count the bottles passing on a belt, count the clock pulses to measure time, count to a number and then act. A chain of toggling flip-flops does it in pure binary, automatically. Montenegro's book builds counters three ways — series, parallel and ring — and the differences between them are a real engineering lesson in speed, simplicity and what a count looks like from outside.

## Sub lesson 1 — Series counters — the ripple chain

Wire three T flip-flops in a chain — call their outputs C, B, A from last to first, and read CBA as a binary number. Give the first flip-flop the incoming pulses as its clock. It toggles on every pulse: 0, 1, 0, 1 — it is counting the ones place. Now clock the *second* flip-flop from the first one's output: it toggles only when the first falls back from 1 to 0 — once per two pulses — the twos place. Clock the third from the second: the fours place. Read the three outputs together and they spell, pulse by pulse: 000, 001, 010, 011, 100, 101, 110, 111 — **binary counting itself**, done by three toggling cells. After 111 the next pulse wraps the whole chain back to 000, and counting starts over. An n-flip-flop counter has **2ⁿ states** and counts **modulo 2ⁿ**: this one is a modulo-8 counter.

[Picture — three T flip-flops chained output-to-clock, with the eight states 000 to 111 written under successive pulses and the wrap back to 000 shown as a curved arrow]

The book's name for this wiring is the **series counter**; its other name tells its weakness — **asynchronous**, or ripple, counter. The pulse does not reach all stages at once: the change *ripples* down the chain, stage by stage, each flip-flop answering a little after the one before. For a few stages nobody notices; for a long chain the last stage settles measurably late, and for a brief moment during each ripple the outputs spell wrong intermediate numbers. Simple and cheap — but speed-limited. That is the trade the next wiring fixes.

## Sub lesson 2 — Parallel counters and ring counters

The **parallel counter** — better named the **synchronous counter** — removes the ripple by one decision: *every* flip-flop receives the **same clock**, the pulse line itself. All stages that must change, change together, in one instant, so the outputs never spell a wrong in-between number, and the counter can run as fast as a single flip-flop can. What decides whether a stage toggles on a given pulse? The counting rule itself: a stage flips exactly when all the stages below it are 1 (that is what makes binary count: the twos place changes only as the ones place falls from 1 to 0 through its carry). Small AND gates watch the lower outputs and arm each stage's toggle — a little more wiring than the ripple chain, buying clean speed. Ripple or parallel: same sequence, same modulus 2ⁿ — the difference is entirely in *when* each stage hears the tick.

[Picture — a parallel counter with one clock line running to every flip-flop and small AND gates watching the lower outputs, beside a ring counter drawn as a circle of flip-flops with a single 1 travelling round it]

The **ring counter** is a different creature: take a shift register, close it into a loop by feeding its last output back into its first input, and start it with **exactly one 1** among 0s. Each pulse shifts the pattern round, so the single 1 circulates: 1000, 0100, 0010, 0001, 1000 again. Four flip-flops give only **four states** — compare the binary counter's sixteen from the same four cells. Why accept so few? Because the ring counter's state needs **no decoding**: exactly one output is active in each state, and that output *is* the answer — the third pulse is simply the moment output 3 stands at 1. Where a machine steps through n actions in turn — first this, then that, then the next — the ring counter hands each action its own private wire, already decoded. Few states, zero translation: another honest trade, and the book teaches all three counters as exactly that — three points on the scale between simple, fast and direct.

## Say it to your companion

Tell your companion, in your own words: a counter is a chain of toggling flip-flops stepping through binary states, one per pulse, modulo 2ⁿ; in a series counter each stage clocks the next so changes ripple and settle late; in a parallel counter all stages share the clock and change together; a ring counter circulates a single 1, giving one active output per state with no decoding needed. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: build the state sequence of a series (ripple) counter and say why the counting change ripples and what that costs. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: state that an n-bit binary counter has 2ⁿ states and counts modulo 2ⁿ. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: explain how a parallel (synchronous) counter clocks all stages together and what its extra gates decide. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: describe a ring counter — a single 1 circulating in a closed shift-register loop — and say why it needs no decoding. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
