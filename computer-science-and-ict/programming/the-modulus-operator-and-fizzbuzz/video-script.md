# Video script — The Modulus Operator — and FizzBuzz

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **modulus operator %** gives the **remainder** of an integer division: 17 % 5 is **2**, 10 % 2 is **0**, 7 % 10 is **7**. Its superpower is the zero case: **a % b == 0** tests divisibility exactly — even or odd (n % 2), leap years, every third or fifth thing — questions that are painful with division and one line with modulus. It also wraps circles into lines: hours on a clock face (13 % 12 = 1), days of the week, positions in a ring — anywhere the world is round, modulus is the translator.
**FizzBuzz** counts from 1 upward, replacing: multiples of **3** with **Fizz**, multiples of **5** with **Buzz**, multiples of **both** (of 15) with **FizzBuzz**, and leaving the rest as numbers. Its craft is the order of tests: the both-case must be tested **first** (or as % 3 and % 5 combined), for a multiple of 15 passes the 3-test and would be stolen by Fizz before Buzz is ever asked. Small as it is, FizzBuzz holds modulus, selection order, and loops in one page — which is why interviewers and the HSC book alike keep it: a programmer's whole honesty, in miniature.
