# Handling Input Errors with Try and Except — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is validation?**
**Answer: Checking input before the program trusts it**

**2. (Sub lesson 1) Name validation's three checks**
**Answer: Something is there, it is the right kind, and it is in the allowed range**

**3. (Sub lesson 1) What does each failed check earn?**
**Answer: A clear message and another chance**

**4. (Sub lesson 1) Why is a silent wrong answer worse than a message?**
**Answer: It corrupts — the program continues on bad data as if it were good**

**5. (Sub lesson 1) What does try/except do?**
**Answer: Runs risky lines in a try block and jumps to the except block if one raises an error, instead of crashing**

**6. (Sub lesson 2) What can the except block do?**
**Answer: Respond — a message, a default, another attempt — and let the program continue**

**7. (Sub lesson 2) How much code belongs in a try block?**
**Answer: The few lines that can fail — no more**

**8. (Sub lesson 2) Why name the specific error where you can?**
**Answer: So the response fits the fault, and unrelated bugs are not hidden**

**9. (Sub lesson 2) What must an except block never do?**
**Answer: Swallow a fault silently**

**10. (Sub lesson 2) How do Egypt's two error lessons divide the work?**
**Answer: The debugger finds the program's faults; try/except survives the user's**
