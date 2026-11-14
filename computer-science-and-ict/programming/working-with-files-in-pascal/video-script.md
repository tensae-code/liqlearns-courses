# Video script — Working with Files in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

File work starts by joining a **file variable** to a real file with **assign**, then opening it: **reset** opens an existing file for reading, **rewrite** creates or empties a file for writing. Reading and writing then move value by value with read and write on the file. The name on disk and the name in the program are two names for one stream of data.
A reading program cannot know a file's length in advance, so it reads **until eof** — the end-of-file test — is true. Every opened file ends with **close**: closing writes the last values safely and frees the file for others. The book places files after graphics and before procedures — the course's data now outlives the program that made it.
