# Encoders and Decoders — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) The decimal-to-BCD encoder is built from OR gates.**
**Answer: True** — Each output bit is 1 for several different keys, so it is the OR of those key lines — read off the BCD table's columns.

**2. (Sub lesson 1) A simple encoder gives a trustworthy code when two keys are pressed at the same time.**
**Answer: False** — It assumes one active input; two keys OR into a mixed code that names neither key.

**3. (Sub lesson 2) A decoder can have more outputs than the input code has patterns.**
**Answer: False** — With n inputs there are only 2ⁿ patterns; each output needs its own pattern, so outputs cannot exceed 2ⁿ.

**4. (Sub lesson 2) A memory chip uses a decoder to select exactly one stored row from a binary address.**
**Answer: True** — Address decoding is the decoder's classic job: the address code wakes one row and no other.
