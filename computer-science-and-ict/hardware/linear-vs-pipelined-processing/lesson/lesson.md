# Linear vs Pipelined Processing

## Do it first

A processor that finishes each instruction entirely before touching the next is leaving most of itself idle most of the time. Malaysia's architecture chapter sets that waste against its cure. In this lesson you compare linear processing with pipelining — stage by overlapping stage.

## Sub lesson 1 — Linear processing — one at a time, whole

In **linear (sequential) processing**, an instruction passes through **all** the machine's stages — fetch, decode, execute — and is **completely finished** before the next instruction is fetched. The picture is a single-file queue: at every moment, only **one stage is working** on the one instruction, and the other stages wait idle. Linear processing is simple to build and easy to reason about — and it wastes the machine: three stages, two always waiting.

[Picture — Linear processing — one at a time, whole]

## Sub lesson 2 — Pipelining — stages overlapping

**Pipelining** overlaps the stages: while instruction 1 is being **executed**, instruction 2 is being **decoded** and instruction 3 is being **fetched** — like an assembly line, every stage working at once, each on a different instruction. After the line fills, one instruction **finishes on every cycle**, though each still takes its full path through the stages: pipelining raises **throughput** (instructions per time), not the speed of any single instruction. Malaysia's comparison keeps the honest cost: the line stumbles when an instruction needs a result the line has not finished yet — the neat overlap has a traffic problem at its heart, which real processors spend much of their cleverness managing.

[Picture — Pipelining — stages overlapping]

## Say it to your companion

Tell your companion, in your own words: In **linear (sequential) processing**, an instruction passes through **all** the machine's stages — fetch, decode, execute — and is **completely finished** before the next instruction is fetched. The picture is a single-file queue: at every moment, only **one stage is working** on the one instruction, and the other stages wait idle. Linear processing is simple to build and easy to reason about — and it wastes the machine: three stages, two always waiting. **Pipelining** overlaps the stages: while instruction 1 is being **executed**, instruction 2 is being **decoded** and instruction 3 is being **fetched** — like an assembly line, every stage working at once, each on a different instruction. After the line fills, one instruction **finishes on every cycle**, though each still takes its full path through the stages: pipelining raises **throughput** (instructions per time), not the speed of any single instruction. Malaysia's comparison keeps the honest cost: the line stumbles when an instruction needs a result the line has not finished yet — the neat overlap has a traffic problem at its heart, which real processors spend much of their cleverness managing. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Only after the current one is completely finished. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Fetch, decode, execute. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: One — the others wait idle. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Each stage works on a different instruction — execute, decode and fetch overlap. Do this with a real example of your own and write or say how you know it is right.
