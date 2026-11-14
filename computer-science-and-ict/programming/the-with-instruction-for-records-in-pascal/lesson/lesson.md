# The With Instruction for Records in Pascal

## Do it first

A single small instruction, given a section of its own: with is Pascal's shorthand for record work — beloved for its brevity, suspected for its one real danger.

## Sub lesson 1 — with — the record opened

The **with** instruction names a record once and opens its fields for a block: `with p do begin name := 'Ana'; mark := 9; paid := true; end;` — inside, the fields are written **bare**, without the `p.` prefix. Several records can be opened together (`with p, q do`), their fields nested by the order given. With changes nothing the program does — it is a **writing** instruction, a shorthand whose whole effect is on the text's length and reading.

[Picture — with — the record opened]

## Sub lesson 2 — The shadowing trap — when a bare name lies

The danger: inside the block, a bare name is the **field if the record has such a field** — even when the programmer meant an outside variable of the same name. A global `mark` and p's field `mark` cannot both be seen inside `with p do` — the field **shadows** the variable, silently. The section's counsel is the profession's: use with for **short, single-record work**; in long blocks or with overlapping names, write the prefixes and keep every name honest. A shorthand that hides meaning has charged more than it saved.

[Picture — The shadowing trap — when a bare name lies]

## Say it to your companion

Tell your companion, in your own words: The **with** instruction names a record once and opens its fields for a block: `with p do begin name := 'Ana'; mark := 9; paid := true; end;` — inside, the fields are written **bare**, without the `p.` prefix. Several records can be opened together (`with p, q do`), their fields nested by the order given. With changes nothing the program does — it is a **writing** instruction, a shorthand whose whole effect is on the text's length and reading. The danger: inside the block, a bare name is the **field if the record has such a field** — even when the programmer meant an outside variable of the same name. A global `mark` and p's field `mark` cannot both be seen inside `with p do` — the field **shadows** the variable, silently. The section's counsel is the profession's: use with for **short, single-record work**; in long blocks or with overlapping names, write the prefixes and keep every name honest. A shorthand that hides meaning has charged more than it saved. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: It opens a record so its fields can be named bare inside the block. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: with p do begin name := 'Ana'; mark := 9; paid := true; end;. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Yes — with p, q do — fields nested by the order given. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — it is a writing shorthand; only the text changes. Do this with a real example of your own and write or say how you know it is right.
