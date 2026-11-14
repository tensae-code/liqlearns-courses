# The Empty Instruction in Pascal — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is the empty instruction?**
**Answer: The absence of an instruction where one is grammatically allowed — it does nothing**

**2. (Sub lesson 1) Where can it appear?**
**Answer: Between two semicolons, after begin, or before end**

**3. (Sub lesson 1) Is the semicolon a terminator in Pascal?**
**Answer: No — it is a separator between instructions**

**4. (Sub lesson 1) Name an honest use of the empty instruction.**
**Answer: A loop whose work is all in its condition (or a placeholder while building)**

**5. (Sub lesson 1) Does the empty instruction change the program's state?**
**Answer: No — no action, no state change**

**6. (Sub lesson 2) In 'if x > 0 then ; writeln(x)', what is the if's body?**
**Answer: The empty instruction — so writeln runs always**

**7. (Sub lesson 2) Why does 'while not eof do ;' hang?**
**Answer: Its body is empty, so nothing ever changes its condition**

**8. (Sub lesson 2) What is the defence against the trap?**
**Answer: Reading with attention — a semicolon before a body that matters should ring a bell**

**9. (Sub lesson 2) Is the empty instruction a compiler error?**
**Answer: No — it is legal; that is what makes it a trap**

**10. (Sub lesson 2) Who is at fault in the trap — machine or writer?**
**Answer: The writer — the machine executes what is written**
