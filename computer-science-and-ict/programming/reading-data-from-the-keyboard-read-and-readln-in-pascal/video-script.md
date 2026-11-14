# Video script — Reading Data from the Keyboard — read and readln in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**read** takes the next values typed at the keyboard and stores them into the variables named in its brackets: `read(a, b)` waits, takes two values and places them. **readln** does the same and then **skips to the end of the input line**, discarding whatever else was typed on it — the safer default for line-by-line data. When a read executes, the program **waits**: execution pauses until the user types and presses Enter. C++ reads with `cin >>`.
Interactive programs follow a courtesy protocol this section makes explicit: **prompt first** (writeln what you ask for — the user cannot guess), **read second**, **echo or use third** (show what was taken, so mistyping is caught at once). Numbers are typed separated by spaces or Enter; characters read raw, one by one, including spaces — so reading a name with readln into a string differs from reading numbers. Input is a contract: the program states the order and kinds it expects, the user supplies exactly those.
