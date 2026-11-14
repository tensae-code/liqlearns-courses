# Video script — Python Dictionaries — Keys and Values

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **dictionary** keeps **pairs**: a **key** and its **value**, written in curly brackets — `student = {"name": "Hamad", "grade": 10}`. A value is reached by its key — `student["grade"]` — the way a person looks a word up by its spelling, not by its page position. Keys are the dictionary's index and its meaning in one: a record's fields are **named**, so the program reads like the record it holds.
Dictionaries are **mutable** in the record-keeper's ways: assigning to a **new key adds** a pair; assigning to an **existing key changes** its value; **del** and **pop** remove pairs; and the dictionary answers questions — its **keys**, its **values**, whether a key is present at all. The warning travels with the power: asking for a key that is **absent raises an error**, so careful programs test before they ask — the dictionary's version of looking before leaping.
