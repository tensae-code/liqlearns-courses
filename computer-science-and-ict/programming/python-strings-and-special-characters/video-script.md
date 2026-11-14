# Video script — Python Strings and Special Characters

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **string** is text held as a value: letters, digits, spaces and marks in quotes, which the program can join (+), repeat (*), measure (len) and ask about. Jordan's Grade 11 lesson meets strings inside the data-structures run because a string behaves like a quiet sequence — its characters have positions, and the string itself is **immutable**: programs build new strings rather than editing old ones, a fact whose reasons the special characters now make practical.
**Special (escape) characters** are written with a backslash followed by a letter or mark: backslash-n writes a new line, backslash-t a tab, a doubled backslash writes a backslash itself, and backslash-quote writes a quote inside its own quoting. The backslash is Python's way of saying 'the next character is special, not literal' — and forgetting it is a family of classic faults: a Windows path whose folder names begin with n or t can run away into newline and tab escapes. The lesson's craft: read every backslash in a string as a deliberate act, and use raw strings where the text is mostly literal, as with file paths.
