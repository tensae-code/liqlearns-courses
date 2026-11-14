# Video script — Constants — TRUE/FALSE, HIGH/LOW, INPUT/OUTPUT

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **constant** is a name whose value is fixed before the program runs and never changes inside it. Arduino C hands the programmer a pocketful of them, and Indonesia's Grade 12 course names them as their own lesson because sketches are unreadable without them. The logic pair: **TRUE** and **FALSE** — the two answers of every test in the program, written as names instead of the numbers (1 and 0) they stand for, so a condition reads as it means.
The pin pairs complete the set. **HIGH** and **LOW** name a pin's two levels — the voltage present or absent — used with digitalWrite and returned by digitalRead. **INPUT** and **OUTPUT** name a pin's two directions, given to pinMode. Four names, and the whole conversation with the board is written in them: set this pin OUTPUT, write it HIGH, read that INPUT pin until it is TRUE-ly pressed. Constants are the language keeping its promises: HIGH means the same in every sketch ever written, which is why programs use the names and never the bare numbers.
