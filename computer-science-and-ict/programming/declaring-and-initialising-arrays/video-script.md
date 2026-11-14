# Video script — Declaring and Initialising Arrays

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The declaration **int a[5];** reserves five integer elements. The **size** must be a whole number known when the program is written (in this book's C++, a constant). Declaring alone leaves the elements **uninitialised** — they hold whatever was in memory — so a careful program never reads an element before giving it a value.
**int a[5] = {10, 20, 30, 40, 50};** fills the elements **in order**. A **shorter list** fills the front and **zeroes the rest**: {10, 20} leaves 10, 20, 0, 0, 0. **int a[] = {7, 8, 9};** omits the size and the list sets it to 3. Listing **more** values than the size is an error the compiler catches.
