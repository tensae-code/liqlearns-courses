# Side Effects of Subprograms

## Do it first

Grade 12's subprogram chapter turns detective. A subprogram is contracted to work through its parameters; some quietly work elsewhere too. Those uncontracted changes have a name, a literature of bugs, and a discipline.

## Sub lesson 1 — What a side effect is — the uncontracted change

A **side effect** is any change a subprogram makes **outside its contract**: altering a **global variable**, writing to a **file or the screen**, moving a device — anything besides computing its return value and its agreed (variable) parameters. The function's offence is subtle: its heading **promises** a clean exchange, so a caller reading the call sees only the exchange — the side effect is invisible exactly where decisions about it would be made. Two calls that look identical can do different amounts of hidden work.

[Picture — What a side effect is — the uncontracted change]

## Sub lesson 2 — The discipline — declare, isolate, or refuse

The chapter's discipline has three moves. **Name it**: a subprogram whose job *is* an effect (printing, saving) should be a **procedure** with the effect in its understood purpose, not a function moonlighting. **Isolate it**: pass what is needed as parameters instead of reaching for globals, so the whole influence crosses the visible border. **Refuse it** in functions: a function should compute its value from its parameters alone, so it can be used inside any expression safely — called twice, called never, without the world changing. Programs stay readable exactly as far as their effects stay visible.

[Picture — The discipline — declare, isolate, or refuse]

## Say it to your companion

Tell your companion, in your own words: A **side effect** is any change a subprogram makes **outside its contract**: altering a **global variable**, writing to a **file or the screen**, moving a device — anything besides computing its return value and its agreed (variable) parameters. The function's offence is subtle: its heading **promises** a clean exchange, so a caller reading the call sees only the exchange — the side effect is invisible exactly where decisions about it would be made. Two calls that look identical can do different amounts of hidden work. The chapter's discipline has three moves. **Name it**: a subprogram whose job *is* an effect (printing, saving) should be a **procedure** with the effect in its understood purpose, not a function moonlighting. **Isolate it**: pass what is needed as parameters instead of reaching for globals, so the whole influence crosses the visible border. **Refuse it** in functions: a function should compute its value from its parameters alone, so it can be used inside any expression safely — called twice, called never, without the world changing. Programs stay readable exactly as far as their effects stay visible. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A change a subprogram makes outside its contract — to globals, files, the screen — beyond its return and agreed parameters. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The heading promises a clean exchange — the extra change is invisible at the call. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Global variables, files, and the screen (also: devices). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Yes — exactly that invisibility is the danger. Do this with a real example of your own and write or say how you know it is right.
