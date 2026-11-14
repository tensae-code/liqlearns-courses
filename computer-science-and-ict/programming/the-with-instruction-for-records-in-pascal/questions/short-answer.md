# The With Instruction for Records in Pascal — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does with do?**
**Answer: It opens a record so its fields can be named bare inside the block**

**2. (Sub lesson 1) Write a with block for pupil p.**
**Answer: with p do begin name := 'Ana'; mark := 9; paid := true; end;**

**3. (Sub lesson 1) Can several records be opened together?**
**Answer: Yes — with p, q do — fields nested by the order given**

**4. (Sub lesson 1) Does with change what the program does?**
**Answer: No — it is a writing shorthand; only the text changes**

**5. (Sub lesson 1) What does the bare name replace?**
**Answer: The p. prefix on each field**

**6. (Sub lesson 2) Which name wins inside with — field or outside variable?**
**Answer: The field — it shadows the outside variable, silently**

**7. (Sub lesson 2) Why is the trap silent?**
**Answer: The program compiles and runs; only the meaning differs from the intent**

**8. (Sub lesson 2) When is with counselled?**
**Answer: For short, single-record work**

**9. (Sub lesson 2) What is advised for long blocks?**
**Answer: Write the prefixes — keep every name honest**

**10. (Sub lesson 2) What is with's trap in one phrase?**
**Answer: A bare name that lies — it names the field when you meant the variable**
