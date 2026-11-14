# Binary Search — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What does binary search demand of the list?**
**Answer: It must already be in order**

**2. (Sub lesson 1) What is checked first?**
**Answer: The middle item**

**3. (Sub lesson 1) The target is smaller than the middle. What is discarded?**
**Answer: The right half — whole**

**4. (Sub lesson 1) When does the hunt answer 'not found'?**
**Answer: When the field shrinks to nothing**

**5. (Sub lesson 1) About how many checks does 1,000 items need at most?**
**Answer: About 10 — each check halves the field**

**6. (Sub lesson 2) What two values track the field?**
**Answer: low and high — the ends of the surviving field**

**7. (Sub lesson 2) How is middle worked out?**
**Answer: (low + high) ÷ 2, as a whole number**

**8. (Sub lesson 2) Target smaller: how does high move?**
**Answer: high = middle − 1**

**9. (Sub lesson 2) Target larger: how does low move?**
**Answer: low = middle + 1**

**10. (Sub lesson 2) What happens on an unordered list?**
**Answer: It can throw away the half that holds the target — the speed is bought by the order it demands**

