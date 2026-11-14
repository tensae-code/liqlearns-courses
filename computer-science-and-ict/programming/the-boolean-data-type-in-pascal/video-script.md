# Video script — The Boolean Data Type in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **boolean** type, named for George Boole, holds exactly two values: **true** and **false**. It is the type of answers: is the number bigger, is the password right, has the list ended. Declaration: `var ok: boolean;`. Booleans are most often **born from comparisons** — `n > 5` is not an instruction but a boolean expression whose value is true or false the moment it is worked out. Where integer counts and real measures, boolean **decides** — it is the type the if and loop conditions of later lessons are made of.
Booleans combine with three operations. **and** gives true only when **both** sides are true; **or** gives true when **at least one** side is true; **not** flips the value — not true is false. With them, compound questions become single expressions: `age >= 18 and hasTicket` asks both admission questions at once. The order of working follows brackets first, then not, and, or — and a table of the few cases (there are only four for two inputs) proves any combination before a program trusts it.
