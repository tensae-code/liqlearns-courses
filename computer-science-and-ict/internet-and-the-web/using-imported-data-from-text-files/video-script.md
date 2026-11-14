# Video script — Using Imported Data from Text Files

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Reading reverses writing: the program **opens** the text file, reads it **line by line** (or reads the whole file as a set of lines), and **splits each line** at the agreed separator into its **fields** — the inverse of the joining that stored it. The newline at each line's end is trimmed, or it rides into the last field and poisons comparisons. Malaysia's discipline is symmetry: the reader is written **from the writer's format agreement** — same separator, same field order — and any change to the stored format must change both, or neither.
With fields in hand, the records become the program's working data: **listed** on a page (the guestbook shows its entries), **searched** (does this name already exist?), **counted and totalled**, and used to **answer** the visitor (a login read against the stored sign-ups). The unit's name for the flow is **imported data**: data made elsewhere — by an earlier visit, another program, or a person typing the file — taken in and used as the program's own. The test of an import is a round trip: store three records by the writing program, import them by the reading program, and the three records that come back must be the three that went in, field for field.
