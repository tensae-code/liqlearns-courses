# Video script — Compiling and Debugging Programs in Pascal and C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Compilation** translates the whole program text into the machine's language before any of it runs: the **compiler** checks the text against the language's grammar, and a text with **syntax errors does not compile at all** — the compiler lists the errors, by line, in its own terse tongue the annexes teach to read. The translated parts are then **linked** with the libraries' ready pieces into one executable file. Compile-time is the grammar's judgement; a clean compile says the text is *legal* — it does not yet say the program is *right*.
The errors that remain are **runtime and logic errors**: the program runs, and divides by zero, or answers wrong, or loops forever. **Debugging (depanare)** hunts them with a method: **reproduce** the failure on the smallest input, **watch** the values (by inserted prints, or the debugger's stepping and breakpoints — pausing the run at a chosen line to inspect the state), **locate** the first moment the state goes wrong, **fix**, and **test again**. The annexes' stance is the profession's: debugging is not shame — it is half the craft, practised by method, not by staring.
