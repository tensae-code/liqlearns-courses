# Video script — Working with the Screen in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The Crt unit's **ClrScr** clears the text screen; **GotoXY(x, y)** puts the cursor at a column and row, so the next write lands exactly there. With these two, output stops being a scroll and becomes a layout: headings at the top, results in their places. The lesson follows dialogue input in the book — first the program hears the user, now it arranges what the user sees.
**TextColor** and **TextBackground** set the colours of letters and the screen behind them. Restraint is the lesson's taste rule: one colour for headings, one for results, the rest plain — a screen is read, not decorated. The book repeats this lesson before linear programs, because every program after it is expected to present its work arranged, not spilled.
