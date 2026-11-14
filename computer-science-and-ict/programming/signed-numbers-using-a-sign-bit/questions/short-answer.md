# Signed Numbers — Using a Sign Bit — short answer

Answer in a short sentence of your own.

**1. (Sub lesson 1) What is a sign bit?**
**Answer: The first bit, given to the sign — 0 positive, 1 negative**

**2. (Sub lesson 1) What do the other bits hold?**
**Answer: The number's magnitude — its size**

**3. (Sub lesson 1) Write −5 in 8-bit sign-and-magnitude.**
**Answer: 10000101**

**4. (Sub lesson 1) How does a reader read a signed register?**
**Answer: Sign first, then the size**

**5. (Sub lesson 1) What scheme is this called?**
**Answer: Sign-and-magnitude**

**6. (Sub lesson 2) What are the two zeros?**
**Answer: +0 (00000000) and −0 (10000000)**

**7. (Sub lesson 2) Name two troubles the two zeros cause.**
**Answer: A wasted pattern, and confused comparisons**

**8. (Sub lesson 2) Why does ordinary addition fail here?**
**Answer: The sign bit gets added as if it were size**

**9. (Sub lesson 2) What must the better scheme let one adder do?**
**Answer: Serve positive and negative arithmetic alike**

**10. (Sub lesson 2) Which lesson answers this need?**
**Answer: The two's complement lesson**
