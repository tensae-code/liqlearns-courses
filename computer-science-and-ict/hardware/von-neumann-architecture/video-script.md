# Video script — Von Neumann Architecture

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In the **von Neumann architecture** the computer keeps **both** in the **same memory**: the **data** being worked on and the **program** — the list of instructions that says what to do with it. Because the program itself is stored, it can be loaded, changed and replaced like any other data, which is why one machine can run many different programs. The memory is a row of numbered cells (addresses), and each instruction or value sits in a cell the processor can name.
The **central processing unit (CPU)** works in a steady cycle: **fetch** the next instruction from memory, **decode** it (work out what it asks for), then **execute** it — with the **control unit** directing the traffic and the **arithmetic-logic unit (ALU)** doing the sums and comparisons. Registers hold the instruction being carried out and the values in play. The single shared path between processor and memory is the design's famous narrow point — the von Neumann bottleneck.
