# Video script — Creating an SQLite Database from Python

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Python carries the **sqlite3** module built in. The program **imports** it and **connects** to a named file — the course's running example, **Kuwait_landmarks.db**. If the file does not exist, the connection **creates it automatically**: an empty database, ready for tables. The connection is the program's doorway: through it travel every CREATE, INSERT and SELECT of the course, and it is closed when the work is done.
Real programs fail politely or not at all. Kuwait creates the database **safely, with exceptions**: the connecting code is wrapped so that if the file cannot be made or opened — a wrong place, a locked file — the program **catches the error and reports it** instead of dying mid-work with the data half-kept. Safe creation is the course's first professional habit: the database is the memory of everything after it, and its birth is guarded.
