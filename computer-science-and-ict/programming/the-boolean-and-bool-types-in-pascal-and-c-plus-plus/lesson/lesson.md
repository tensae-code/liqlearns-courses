# The Boolean and bool Types in Pascal and C++

## Do it first

The smallest type returns in two spellings. Grade 10 aligns boolean with bool — and warns where C++'s older habits make its truth leak into numbers.

## Sub lesson 1 — Two values in two languages

Pascal's **boolean** and C++'s **bool** hold the same two values — Pascal writes **true/false**, C++ writes **true/false** as keywords too. Both are born mainly from **comparisons** (a > b, x == y — note C++'s double equals for comparison against its single = for assignment, the most punished confusion in the language), and both feed the same **logical operations**: Pascal's and/or/not are C++'s &&, ||, !. Same algebra, two notations — by now the course's refrain.

In your mind's eye: two values in two languages.

## Sub lesson 2 — The numeric trap — C++'s loose truth

C++ carries an older inheritance: in a condition, **any non-zero value counts as true and 0 as false**, so an int can stand where a bool belongs — and the assignment `if (x = 5)` compiles, assigns, and reads as true, hiding a bug in plain sight. Pascal's strictness forbids the mixture: a condition must be boolean, full stop. The section's rule for the pair: write booleans as booleans in both languages; the loose reading is a trap to recognise in others' code, never a style to adopt.

In your mind's eye: the numeric trap — C++'s loose truth.

## Say it to your companion

Tell your companion, in your own words: Pascal's **boolean** and C++'s **bool** hold the same two values — Pascal writes **true/false**, C++ writes **true/false** as keywords too. Both are born mainly from **comparisons** (a > b, x == y — note C++'s double equals for comparison against its single = for assignment, the most punished confusion in the language), and both feed the same **logical operations**: Pascal's and/or/not are C++'s &&, ||, !. Same algebra, two notations — by now the course's refrain. C++ carries an older inheritance: in a condition, **any non-zero value counts as true and 0 as false**, so an int can stand where a bool belongs — and the assignment `if (x = 5)` compiles, assigns, and reads as true, hiding a bug in plain sight. Pascal's strictness forbids the mixture: a condition must be boolean, full stop. The section's rule for the pair: write booleans as booleans in both languages; the loose reading is a trap to recognise in others' code, never a style to adopt. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: true and false — in both languages. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Comparisons. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: == — double; single = is assignment (the most punished confusion). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Pascal and/or/not = C++ &&, ||, !. Do this with a real example of your own and write or say how you know it is right.
