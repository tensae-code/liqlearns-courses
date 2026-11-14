# Text Files in Pascal and C++ — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is a text file's content?**
**Answer: Characters, organised into lines ended by an end-of-line mark**

**2. (Sub lesson 1) How is a text file declared in Pascal?**
**Answer: As a variable of type text**

**3. (Sub lesson 1) How do write/read aim at a file?**
**Answer: By naming it first — writeln(f, x) writes to f**

**4. (Sub lesson 1) How are numbers stored in a text file?**
**Answer: As their printed characters, not their binary values**

**5. (Sub lesson 1) Why do text files travel so well?**
**Answer: Any editor and any program can read characters**

**6. (Sub lesson 2) What do eof and eoln test?**
**Answer: eof: the end of the file; eoln: the end of the current line**

**7. (Sub lesson 2) Write the canonical reading loop's shape.**
**Answer: while not eof(f) do — readln(f, line), process, repeat**

**8. (Sub lesson 2) What stops the loop exactly right?**
**Answer: eof becomes true after the last line**

**9. (Sub lesson 2) What two standing errors are warned of?**
**Answer: Reading past the end, and numbers misread when spaces are handled wrongly**

**10. (Sub lesson 2) What seals a written file?**
**Answer: close — after the last writeln**
