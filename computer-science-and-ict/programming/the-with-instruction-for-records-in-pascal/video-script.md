# Video script — The With Instruction for Records in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **with** instruction names a record once and opens its fields for a block: `with p do begin name := 'Ana'; mark := 9; paid := true; end;` — inside, the fields are written **bare**, without the `p.` prefix. Several records can be opened together (`with p, q do`), their fields nested by the order given. With changes nothing the program does — it is a **writing** instruction, a shorthand whose whole effect is on the text's length and reading.
The danger: inside the block, a bare name is the **field if the record has such a field** — even when the programmer meant an outside variable of the same name. A global `mark` and p's field `mark` cannot both be seen inside `with p do` — the field **shadows** the variable, silently. The section's counsel is the profession's: use with for **short, single-record work**; in long blocks or with overlapping names, write the prefixes and keep every name honest. A shorthand that hides meaning has charged more than it saved.
