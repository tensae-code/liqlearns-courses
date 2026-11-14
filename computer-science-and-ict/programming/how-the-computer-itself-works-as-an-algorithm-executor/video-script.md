# Video script — How the Computer Itself Works as an Algorithm Executor

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The computer executes a program by a fixed cycle: **fetch** the next instruction from memory, **decode** it (work out which command of its set it is), **execute** it — then fetch the next. The **processor** runs the cycle; the **program counter** keeps the place, pointing at the next instruction, so sequence is kept even as branches and loops redirect it. Billions of cycles per second are still this same three-step round: the fastest executor is, step by step, the simplest.
Set beside the chapter's other executors, the computer's marks stand out: its **command set** is small and exact (machine instructions), its **obedience** is total (it does what the instruction says, never what was meant), its **speed and endurance** are inhuman, and its **judgement is zero** — it cannot notice a senseless instruction. That is why the algorithm must be **complete and exact before it runs**: the executor that never tires also never thinks. Every later Pascal lesson is written for this executor's character.
