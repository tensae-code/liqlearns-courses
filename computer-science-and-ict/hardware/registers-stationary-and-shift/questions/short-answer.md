# Registers — Stationary and Shift — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Why do all the flip-flops of a stationary register share one clock line instead of having separate clocks?**
**Answer: So that every bit of the word is copied at the same instant; separate clocks could tick at slightly different moments and tear the word into pieces from different times. One shared tick keeps the word one word.**

**2. (Sub lesson 2) A serial line delivers one bit per tick. After how many ticks can a 6-bit SIPO register present the complete word, and why?**
**Answer: After 6 ticks: the register has six flip-flops, each tick shifts one new bit in and moves the gathered bits along, so six ticks are needed for all six bits of the word to be standing in the row together.**
