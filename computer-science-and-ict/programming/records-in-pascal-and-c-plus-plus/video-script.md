# Video script — Records in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **record** is a structured type whose parts — its **fields** — may be of **different types**, each with its own **name**: Pascal's `type TPupil = record name: string; mark: integer; paid: boolean; end;`, C++'s `struct`. A field is reached through the record variable with a **dot**: `p.mark := 9;` — the dot reads 's: the mark of p. The whole record can also be **assigned at once** to another of the same type, copying every field — the structure acting simple for one act.
Records earn their keep where the world is tabular: a **class of pupils** is an array of records; a **library** is a file of them. The working patterns assemble the chapter's structures: loop the array, test a field, gather by another field — 'print the names of pupils with mark ≥ 9 and paid = true'. A record also models **one honest thing** — a date (day, month, year as three fields of fitting subranges), a point, a book — which is why the type definition reads like the thing's description: fields are the datum's anatomy, written down.
