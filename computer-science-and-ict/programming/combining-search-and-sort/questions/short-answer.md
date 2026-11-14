# Combining Search and Sort — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What are the combination's two stages?**
**Answer: Sort the list, then binary-search it**

**2. (Sub lesson 1) What joins the stages?**
**Answer: The sort's guarantee — binary search demands order, and the sort supplies it**

**3. (Sub lesson 1) Which searches can the second stage use?**
**Answer: Binary search — the ordered list is what it needs**

**4. (Sub lesson 1) In pseudocode, how is the combination written?**
**Answer: The two algorithms one after the other, the sorted list handed over**

**5. (Sub lesson 1) What is done once, and what per question?**
**Answer: Sorting is done once; searching is done per question**

**6. (Sub lesson 2) When does the combination pay?**
**Answer: When many searches follow one sort**

**7. (Sub lesson 2) Why does it lose for a single search?**
**Answer: Sorting the whole list costs more than one linear search**

**8. (Sub lesson 2) What is Malaysia's judgement rule?**
**Answer: Count the questions first — one question, search as it stands; a season of questions, sort once**

**9. (Sub lesson 2) What does each later search cost after sorting?**
**Answer: Halving-work instead of whole-list work**

**10. (Sub lesson 2) What does the sort's cost get shared across?**
**Answer: All the searches that follow it**

