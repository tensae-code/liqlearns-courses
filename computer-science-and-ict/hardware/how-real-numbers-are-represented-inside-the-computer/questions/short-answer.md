# How Real Numbers Are Represented Inside the Computer — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What are a stored real's three fields?**
**Answer: Sign, exponent and mantissa**

**2. (Sub lesson 1) What formula gives the value?**
**Answer: sign × mantissa × 2^exponent**

**3. (Sub lesson 1) What does normalisation fix?**
**Answer: The mantissa's first digit is 1**

**4. (Sub lesson 1) What do more exponent bits buy, and more mantissa bits?**
**Answer: Wider range; finer precision**

**5. (Sub lesson 1) Why is the total a budget?**
**Answer: The bit count is fixed — each field's share is taken from the others'**

**6. (Sub lesson 2) What are the representation's two edges?**
**Answer: Range (overflow and underflow) and precision (values sharing one stored neighbour)**

**7. (Sub lesson 2) Why is 0.1 stored approximately?**
**Answer: Its binary mantissa does not terminate — the stored value is a close neighbour**

**8. (Sub lesson 2) Where do long computations' errors come from?**
**Answer: Accumulated rounding at the precision limit**

**9. (Sub lesson 2) Which later lessons grow from this?**
**Answer: Grade 12's lessons on calculation errors**

**10. (Sub lesson 2) Is floating point a failure?**
**Answer: No — a chosen compromise: range and honesty about precision in one row of bits**
