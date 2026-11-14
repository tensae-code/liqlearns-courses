# Enumerated Data Types in Pascal — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) How is an enumerated type defined?**
**Answer: By listing its values in brackets in a type definition**

**2. (Sub lesson 1) What values has the lesson's example?**
**Answer: Mon, Tue, Wed, Thu, Fri, Sat, Sun — the type TDay**

**3. (Sub lesson 1) Are the values strings?**
**Answer: No — they are names, not texts in apostrophes**

**4. (Sub lesson 1) What protection does enumeration give?**
**Answer: The compiler checks assignments — a value outside the list is an error at once**

**5. (Sub lesson 1) How is a value assigned?**
**Answer: d := Wed; — with the bare name**

**6. (Sub lesson 2) What does the list's order give the values?**
**Answer: An order — they can be compared and stepped through**

**7. (Sub lesson 2) What do succ and pred give?**
**Answer: The next and the previous value — succ(Wed) = Thu**

**8. (Sub lesson 2) What does ord give?**
**Answer: The value's position counted from 0 — ord(Mon) = 0**

**9. (Sub lesson 2) Is Sat > Fri true?**
**Answer: Yes — enumerated values compare by their list order**

**10. (Sub lesson 2) What kind of sets suit enumeration?**
**Answer: Closed lists that do not grow — months, suits, directions, grades**
