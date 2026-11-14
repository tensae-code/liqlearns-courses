# Video script — Defining Your Own Function — DEF FN

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Built-in functions cover the work everybody needs; **DEF FN** covers yours. With `DEF FN` the programmer **defines her own function**: a name beginning with **FN**, a variable in brackets, and the formula the name stands for — `10 DEF FNA(X) = X * X + 1`. From that line on, the program may write `FNA(3)` anywhere a value is wanted, and BASIC works out 10. Sudan's book gives defined functions the final section of its BASIC course: the learner stops only using the language and starts extending it.
The worth of a defined function is the worth of every function: the formula is written **once** and **used many times**, with a fresh value each time — `FNA(3)`, `FNA(7)`, `FNA(T)` — and if the formula must change, it changes in the one DEF line, not in every place it was used. A defined function also names an idea: a program that computes a tax, a mean or a conversion reads like its subject when the work hides behind FN names the reader understands.
