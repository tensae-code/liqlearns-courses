# Binary Arithmetic — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) In 5 bits, write −7 in two's complement, showing both steps.**
**Answer: 7 in 5 bits is 00111. Invert every bit: 11000 (ones' complement). Add 1: 11001. Check: 00111 + 11001 = 100000 — zero in a 5-bit register, as it must be.**

**2. (Sub lesson 2) Why does two's complement let a machine get away with building only an adder, never a subtractor?**
**Answer: Because every subtraction A − B is rewritten as the addition A + (−B), and two's complement is precisely the bit pattern of −B that makes ordinary addition produce the correct difference (with the overflow carry falling off the register's end). One addition circuit then serves both operations.**
