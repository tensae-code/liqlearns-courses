# Defining New Data Types in Pascal and C++ — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does a type definition do?**
**Answer: It gives a name to a type construction, once, for the whole program**

**2. (Sub lesson 1) Where does Pascal gather definitions?**
**Answer: In a type section before the variables**

**3. (Sub lesson 1) How does C++ spell the same act?**
**Answer: typedef (or the newer using)**

**4. (Sub lesson 1) What is C++'s version weaker at?**
**Answer: It makes an alias, not a guarded new kind**

**5. (Sub lesson 1) Give the lesson's Pascal example.**
**Answer: type TMark = 1..10; — a mark as a subrange type**

**6. (Sub lesson 2) Name the four reasons to define types.**
**Answer: Readability, protection, change in one place, honesty of design**

**7. (Sub lesson 2) What protection does TMark carry?**
**Answer: The subrange's guard — a mark of 47 is caught by the type**

**8. (Sub lesson 2) What changes if marks become 1..12?**
**Answer: One definition — the whole program follows**

**9. (Sub lesson 2) What are a program's definitions called in the lesson's phrase?**
**Answer: Its data's manifesto**

**10. (Sub lesson 2) Why is a defined type documentation?**
**Answer: Because the compiler checks it — it cannot drift from the code**
