# Video script — Arduino C Program Structure — setup() and loop()

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An Arduino program — a **sketch** — is written in **C**, and every sketch, from a blinking light to the smart bin, has the same basic structure (struktur dasar): two functions the board's system calls. **`void setup()`** holds what happens **once**, when the program starts: setting pin modes, starting the serial connection, preparing the parts. **`void loop()`** holds the program's life: when it finishes, the board calls it again, forever, until power ends. Indonesia's Grade 12 course teaches the skeleton before the commands, because every later line of Arduino code is filed in one of these two rooms.
The structure disciplines the writing: a command belongs in setup() if it must happen exactly once, in loop() if it is the behaviour repeated. The text rules of Arduino C ride on the skeleton — statements end with **semicolons**, blocks live inside **curly braces**, and `void` names a function that returns nothing. The beginner's standing fault is a one-time act written in loop() (a pin re-set a thousand times a second) or a behaviour trapped in setup() (run once, then silence). Read any sketch by its rooms and the program's whole shape is visible at a glance.
