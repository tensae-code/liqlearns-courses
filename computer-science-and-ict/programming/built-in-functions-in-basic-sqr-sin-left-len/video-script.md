# Video script — Built-In Functions in BASIC — SQR, SIN, LEFT$ and LEN

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

BASIC carries a toolbox of **built-in (reserved) functions**: named pieces of work the language itself performs. You give a function a value and it hands back a result — no program of yours defines how. The mathematical family comes first in Sudan's book: **SQR** gives a number's square root, **SIN** its sine, and their fellows give cosines, tangents, absolute values and whole parts. Writing `LET R = SQR(81)` stores 9 — the root was found by the language, not by your lines.
The second family works on **strings** — text held in string variables. **LEN** counts a string's characters: `LEN("KHARTOUM")` is 8. **LEFT$** cuts from the left: `LEFT$("KHARTOUM", 4)` is "KHAR" — the first four characters. Their partners cut from the right and the middle. A built-in function is recognised the same way in both families: a reserved name, a value in brackets, a single result out. The next lesson turns the idea around — functions the programmer defines for herself.
