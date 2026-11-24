# The Real and float Types in Pascal and C++

## Do it first

Grade 10's dual types continue with the fractions. Both languages store a real the same scientific way — a mantissa carried by an exponent — and both therefore inherit the same beautiful flaw: approximation.

## Sub lesson 1 — Mantissa and exponent — how a real is stored

A real value is stored in two parts: the **mantissa** — the value's significant digits — and the **exponent** — the power of two (or ten, in the written E form) that places the point. Pascal's **real** and C++'s **float** are the school sizes; C++ adds **double**, with roughly twice the mantissa bits — **double precision**. More mantissa bits mean **more exact digits**; more exponent range means larger and smaller magnitudes. No size escapes the principle: between any two stored neighbours, infinitely many true values share the same stored one.

In your mind's eye: mantissa and exponent — how a real is stored.

## Sub lesson 2 — Approximation in practice — the pair's shared rules

Because storage is approximate, the pair shares its commandments. **Never test reals for exact equality** — test that their difference is small. **Expect accumulation**: many small additions drift. **Format your output**: digits beyond the type's precision are noise the type never stored. And choose float against double by the data: measurements with five honest digits gain nothing from double's fifteen, while money and long computations argue for the wider mantissa. Grade 12's error chapters are this section, grown up.

In your mind's eye: approximation in practice — the pair's shared rules.

## Say it to your companion

Tell your companion, in your own words: A real value is stored in two parts: the **mantissa** — the value's significant digits — and the **exponent** — the power of two (or ten, in the written E form) that places the point. Pascal's **real** and C++'s **float** are the school sizes; C++ adds **double**, with roughly twice the mantissa bits — **double precision**. More mantissa bits mean **more exact digits**; more exponent range means larger and smaller magnitudes. No size escapes the principle: between any two stored neighbours, infinitely many true values share the same stored one. Because storage is approximate, the pair shares its commandments. **Never test reals for exact equality** — test that their difference is small. **Expect accumulation**: many small additions drift. **Format your output**: digits beyond the type's precision are noise the type never stored. And choose float against double by the data: measurements with five honest digits gain nothing from double's fifteen, while money and long computations argue for the wider mantissa. Grade 12's error chapters are this section, grown up. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The mantissa (significant digits) and the exponent (the power placing the point). Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Pascal's real and C++'s float. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Roughly twice the mantissa bits — double precision: more exact digits. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Range — larger and smaller magnitudes. Do this with a real example of your own and write or say how you know it is right.
