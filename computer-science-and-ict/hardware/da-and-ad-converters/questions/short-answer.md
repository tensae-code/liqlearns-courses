# DA and AD Converters — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) A 4-bit DAC has Vref = 8 V. What output does the code 1011 give, and what is one step worth?**
**Answer: One step is Vref/2ⁿ = 8/16 = 0.5 V. The code 1011 is 11, so the output is 11 × 0.5 = 5.5 V.**

**2. (Sub lesson 2) Match converters to jobs and justify: (a) a greenhouse temperature logger recording once a minute; (b) a studio audio recorder. State what each needs more — bits or speed — and why.**
**Answer: The logger's signal changes extremely slowly and temperatures need only modest fineness, so almost any slow, cheap ADC serves — speed is worthless to it. The studio recorder faces the fastest-changing, finest-detailed signal there is in this course — audio — so it needs both: conversion fast enough for the sampling theorem at audio rates, and many bits (CD uses 16) to keep quantisation noise inaudible.**
