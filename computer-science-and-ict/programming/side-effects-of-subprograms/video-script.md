# Video script — Side Effects of Subprograms

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **side effect** is any change a subprogram makes **outside its contract**: altering a **global variable**, writing to a **file or the screen**, moving a device — anything besides computing its return value and its agreed (variable) parameters. The function's offence is subtle: its heading **promises** a clean exchange, so a caller reading the call sees only the exchange — the side effect is invisible exactly where decisions about it would be made. Two calls that look identical can do different amounts of hidden work.
The chapter's discipline has three moves. **Name it**: a subprogram whose job *is* an effect (printing, saving) should be a **procedure** with the effect in its understood purpose, not a function moonlighting. **Isolate it**: pass what is needed as parameters instead of reaching for globals, so the whole influence crosses the visible border. **Refuse it** in functions: a function should compute its value from its parameters alone, so it can be used inside any expression safely — called twice, called never, without the world changing. Programs stay readable exactly as far as their effects stay visible.
