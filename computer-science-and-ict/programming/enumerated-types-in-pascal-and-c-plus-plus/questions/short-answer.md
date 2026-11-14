# Enumerated Types in Pascal and C++ — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) How does each language define an enumeration?**
**Answer: Pascal: type TDay = (Mon, …, Sun); C++: enum TDay {Mon, …, Sun};**

**2. (Sub lesson 1) What are the members underneath?**
**Answer: Integers numbered from 0 in order**

**3. (Sub lesson 1) How do members compare?**
**Answer: By their hidden numbers**

**4. (Sub lesson 1) Can a value outside the list enter?**
**Answer: No — the set stays closed**

**5. (Sub lesson 1) What is the name for the programmer?**
**Answer: The reading of a stored integer**

**6. (Sub lesson 2) How strict is Pascal's enumerated type?**
**Answer: Strict — its variables take only its own members**

**7. (Sub lesson 2) What does classic C++ enum allow?**
**Answer: Members leak into scope as plain integers and mix with int arithmetic**

**8. (Sub lesson 2) What problem do two C++ enums share?**
**Answer: Same-named members collide in the shared scope**

**9. (Sub lesson 2) What was enum class invented to do?**
**Answer: Withdraw those freedoms — restore strictness and scope**

**10. (Sub lesson 2) What is the section's lesson in one line?**
**Answer: The concept is shared; the protection is a language choice**
