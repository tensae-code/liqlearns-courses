# Video script — Keyboard Input and Output in Java

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Java's printing workhorse is **System.out.println** — print this, then move to a new line; its sibling **System.out.print** stays on the same line. What is printed can be text in quotes, a variable's value, or the two joined with **+**: System.out.println("Mark: " + mark);. Output is where the program's inside becomes visible — Malaysia's programs print prompts as well as answers, because a silent program leaves the user not knowing it is waiting, or for what.
Keyboard input in Malaysia's Java work uses a **Scanner** on System.in: the program is set up with a Scanner, then reads with its methods — **nextInt()** for a whole number, **nextDouble()** for a decimal, **nextLine()** for a line of text. Each read **waits** until the user types and presses Enter, then hands the typed value over in the type the method promises — asking nextInt() for letters is a run-time fault. The chapter's shape for every such program is the conversation itself: prompt, read, process, print — the same input–process–output the course has used since pseudocode.
