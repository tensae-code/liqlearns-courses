# Ordinal Data Types in General

## Do it first

After meeting the simple types one by one, Grade 10 steps back and names their family. Five types that look unrelated share a deep property — and the property, once seen, organises half the language.

## Sub lesson 1 — What makes a type ordinal — a countable order

A type is **ordinal** when its values can be **counted in a fixed order**: each value (except the last) has a definite **next** one. Integer counts by 1; char by code; boolean is the pair false < true; an enumeration by its list; a subrange inherits its host's order. Real is the great **non-ordinal**: between any two reals there is another, so no 'next real' exists. Ordinality, not size, is the property the languages' rules keep asking about.

[Picture — What makes a type ordinal — a countable order]

## Sub lesson 2 — The family's shared tools — ord, succ, pred, for, case

Ordinal types share an instrument set. **ord(x)** gives a value's position number; **succ(x)** and **pred(x)** give its neighbours; **for** loops may be steered by any ordinal variable; **case** selectors must be ordinal; and enumerations/subranges in Pascal and their kin obey the family's comparisons. Learn a type's ordinality and its allowed tools follow without memorising lists: the rules of for and case — which puzzled as arbitrary in Grade 8 — stand revealed as one rule: **these constructions count, so their steersman must be countable**.

[Picture — The family's shared tools — ord, succ, pred, for, case]

## Say it to your companion

Tell your companion, in your own words: A type is **ordinal** when its values can be **counted in a fixed order**: each value (except the last) has a definite **next** one. Integer counts by 1; char by code; boolean is the pair false < true; an enumeration by its list; a subrange inherits its host's order. Real is the great **non-ordinal**: between any two reals there is another, so no 'next real' exists. Ordinality, not size, is the property the languages' rules keep asking about. Ordinal types share an instrument set. **ord(x)** gives a value's position number; **succ(x)** and **pred(x)** give its neighbours; **for** loops may be steered by any ordinal variable; **case** selectors must be ordinal; and enumerations/subranges in Pascal and their kin obey the family's comparisons. Learn a type's ordinality and its allowed tools follow without memorising lists: the rules of for and case — which puzzled as arbitrary in Grade 8 — stand revealed as one rule: **these constructions count, so their steersman must be countable**. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its values can be counted in a fixed order — each has a definite next. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Integer, char, boolean, enumerations and subranges. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Between any two reals there is another — no 'next real' exists. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: false < true. Do this with a real example of your own and write or say how you know it is right.
