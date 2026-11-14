# Video script — Saving Data in Text Files with PHP

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Server data must **outlive** any single page visit: names signed up today are read tomorrow. A **text file** is the unit's store: plain lines of characters, kept in a file on the server, readable by the program and by people. Each **record** is written as **one line**, its **fields separated by a chosen mark** (such as a comma or a | ) — Aina|aina@mail.com|2026 — so the line can later be split back into its fields. The format is an agreement the whole unit keeps: writer and reader must use the same mark and the same field order, or the data reads as nonsense.
In PHP the writing follows a fixed rhythm: **open** the file for appending (so old records are kept), **write** the new record as one formatted line (the fields joined by the mark, ended by a newline), and **close** the file. Appending matters: opening a file for plain writing **replaces** its contents, and the difference between keeping a term's sign-ups and keeping only the last one is that single choice. Malaysia's check is performed by eye: after saving, the file is opened as text and **read** — if the new line does not stand correctly among the old, the writing, not the idea, is repaired.
