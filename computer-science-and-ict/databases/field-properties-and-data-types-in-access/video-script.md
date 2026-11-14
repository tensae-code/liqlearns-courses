# Video script — Field Properties and Data Types in Access

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In Access, a table is built in **design view**: each **field** is given a name and a **data type** — the kind of value it may hold. The book's types include **Short Text** for names, **Number** for amounts, **Date/Time** for days, **Currency** for money and **Yes/No** for answers that are one of two. The type is a guard: a Number field refuses letters, and a Date field refuses a word like “soon”. Sudan's Grade 7 book sets types inside the one pupils-and-subjects database its whole first half builds.
Under the type, design view lists the field's **properties** — the fine rules for that one field: its **field size** (how long a text or how big a number may be), its **format** (how the value is shown), a **default value** that appears before anything is typed, and whether the field is **required** — must be filled — or may stay empty. Properties are set field by field, and together with the types they decide what a table will accept before a single record is entered. Set them first; correct them rarely.
