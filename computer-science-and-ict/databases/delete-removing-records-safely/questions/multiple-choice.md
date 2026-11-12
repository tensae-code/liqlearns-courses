# DELETE — removing records safely — multiple choice

Pick the one right answer.

**1. (Sub lesson 1)** After DELETE removes all rows, what remains?
a) nothing — the table is gone  b) the table structure, empty and ready  c) only the key column  d) a backup table
**Answer: b) the table structure, empty and ready** — structure stands; records go.

**2. (Sub lesson 1)** DELETE can remove —
a) half a record's fields  b) whole records only  c) the primary key only  d) columns
**Answer: b) whole records only** — a record goes whole or not at all.

**3. (Sub lesson 2)** The safe WHERE for deleting one student names —
a) FirstName  b) Age  c) StudentID — the primary key  d) Sex
**Answer: c) StudentID — the primary key** — only the key cannot repeat.

**4. (Sub lesson 2)** Two students are named Aster. DELETE … WHERE FirstName = 'Aster' would —
a) delete neither  b) delete both Asters — the wrong-record danger  c) delete the older one  d) ask which one
**Answer: b) delete both Asters — the wrong-record danger** — a repeating field targets every match.

**5. (Sub lesson 3)** To close a department, delete first —
a) the department  b) its many-side records — students, teachers, courses  c) the database  d) the primary keys
**Answer: b) its many-side records — students, teachers, courses** — many side before one side.

**6. (Sub lesson 3)** Deleting a course record does what to its department?
a) deletes it too  b) nothing harmful — a child deletion does not harm its parent  c) orphans the department  d) locks it
**Answer: b) nothing harmful — a child deletion does not harm its parent** — the danger runs the other way.
