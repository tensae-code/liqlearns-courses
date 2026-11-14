# Video script — Linear vs Pipelined Processing

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In **linear (sequential) processing**, an instruction passes through **all** the machine's stages — fetch, decode, execute — and is **completely finished** before the next instruction is fetched. The picture is a single-file queue: at every moment, only **one stage is working** on the one instruction, and the other stages wait idle. Linear processing is simple to build and easy to reason about — and it wastes the machine: three stages, two always waiting.
**Pipelining** overlaps the stages: while instruction 1 is being **executed**, instruction 2 is being **decoded** and instruction 3 is being **fetched** — like an assembly line, every stage working at once, each on a different instruction. After the line fills, one instruction **finishes on every cycle**, though each still takes its full path through the stages: pipelining raises **throughput** (instructions per time), not the speed of any single instruction. Malaysia's comparison keeps the honest cost: the line stumbles when an instruction needs a result the line has not finished yet — the neat overlap has a traffic problem at its heart, which real processors spend much of their cleverness managing.
