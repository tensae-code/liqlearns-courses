# Video script — Database Models — Hierarchical, Network, Relational, Object-Oriented

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **hierarchical model** organises records as a **tree**: each record has one **parent** and may have many **children** (a school → classes → pupils). It is fast down its paths but rigid — a pupil in two classes has no honest place in one tree. The **network model** loosens the tree into a **web**: a record may have **several parents**, joined by named links, so many-to-many facts fit — at the cost of a structure only programmers can navigate, record by record.
The **relational model** stores data in **tables** of rows and columns, joined not by stored links but by **matching values** — keys — worked out when a question is asked. It is the model of this whole course: simple to see, flexible to question. The **object-oriented model** stores **objects** — data together with the actions that belong to it (a Pupil object that holds its marks and can print its own report) — suiting programs built from objects, at the cost of a smaller, more specialised world of tools. Malaysia's comparison ends where its course stands: relational, because school and business data is tabular, shared, and questioned in ways no tree foresaw.
