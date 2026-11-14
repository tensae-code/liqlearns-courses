# Dynamic Data Structures in C and C++ — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does new return?**
**Answer: The address of a fresh cell**

**2. (Sub lesson 1) How is the pointed value written?**
**Answer: *p — the dereferenced pointer**

**3. (Sub lesson 1) How is a dynamic array born and freed?**
**Answer: Born with new int[n] — n decided at run time; freed with delete[]**

**4. (Sub lesson 1) What is every new, in the lesson's phrase?**
**Answer: A loan — the system's memory, held until delete**

**5. (Sub lesson 1) How is a pointer declared in C++?**
**Answer: With * on the type or name — int* p;**

**6. (Sub lesson 2) Name the three classic wounds.**
**Answer: Memory leaks, dangling pointers, and wild (unset) pointers**

**7. (Sub lesson 2) What is pointer arithmetic?**
**Answer: Stepping a pointer by cells — p + 1 names the next cell**

**8. (Sub lesson 2) Which language fences pointers more?**
**Answer: Pascal — typed pointers and no pointer arithmetic**

**9. (Sub lesson 2) State the elective's closing rule.**
**Answer: Every new pairs with a delete; every pointer is nil-or-valid; a freed pointer is set to nullptr at once**

**10. (Sub lesson 2) What does a dangling pointer point at?**
**Answer: Freed memory — possibly already reused for other data**
