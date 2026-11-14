# Video script — Python Exceptions — Try and Except

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

When a Python program meets an operation it cannot do, it **raises an exception** — it stops and reports the failure's kind: a ValueError for the un-number-like text, a ZeroDivisionError for the division by zero. Uncaught, the exception **ends the program** where it stands, mid-work. Naming failures is Python's honesty: the program does not pretend the bad thing worked — but honesty that kills the program is only half a virtue.
**try** wraps the dangerous lines: 'try this'; **except** stands beneath with the rescue: 'if that failure happens, do this instead' — explain, ask again, use a safe value — and the program **continues** past the caught failure. The book's set build is the **school-trip cost-sharing calculator**: its inputs are pupils' typed numbers, so its divisions are wrapped, and a nonsense entry earns a message and another chance instead of a corpse of a program. The habit is the lesson: dangerous ground is crossed inside try, everywhere in the course after this.
