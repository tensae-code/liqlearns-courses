# ON DELETE Actions — SET NULL and CASCADE — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What problem do ON DELETE actions answer?**
**Answer: What happens to child rows when their parent is deleted**

**2. (Sub lesson 1) What does SET NULL do to the children?**
**Answer: Empties their foreign key — the rows stay, pointing at nothing**

**3. (Sub lesson 1) When does SET NULL fit?**
**Answer: Where the child's existence does not depend on the parent**

**4. (Sub lesson 1) What does CASCADE do on delete?**
**Answer: Deletes the children with the parent**

**5. (Sub lesson 1) When does CASCADE fit?**
**Answer: Where a child is meaningless alone — an order's lines without the order**

**6. (Sub lesson 2) Name an alternative besides these two.**
**Answer: Refusing/restricting the deletion while children exist (NO ACTION / RESTRICT)**

**7. (Sub lesson 2) When is the children's fate chosen?**
**Answer: When the table is created — in its FOREIGN KEY declaration**

**8. (Sub lesson 2) What is NULL, here?**
**Answer: No value — honestly unassigned**

**9. (Sub lesson 2) Why not improvise on deletion day?**
**Answer: The fate must be a designed rule, not a panic decision**

**10. (Sub lesson 2) Which book teaches this?**
**Answer: Kuwait Grade 11 Information Technology Term 2, Unit 1 Lesson 6**
