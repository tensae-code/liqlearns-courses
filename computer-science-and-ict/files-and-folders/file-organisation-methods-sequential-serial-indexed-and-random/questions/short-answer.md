# File Organisation Methods — Sequential, Serial, Indexed and Random — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 2) A bank must answer a balance question for one account out of two million, instantly. Which organisation fits, and why do the others fail?**
**Answer: Random (direct) organisation: the account number is hashed to an address and the record is read in one jump. Serial and sequential files would need reading from the start until the account appears — far too slow; indexed-sequential would work but is slower than the direct jump and its order is not needed for this job.**
