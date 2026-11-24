# The Integer and int Types in Pascal and C++

## Do it first

Grade 7 met integer alone; Grade 10 takes it up in both languages at once. The family is larger than one type: sizes, signs and remainders all differ between the pair — and the differences are examinable.

## Sub lesson 1 — A family of sizes — and the sign choice

Both languages offer whole numbers in **several sizes**: Pascal's family runs from shortint and byte through **integer** to longint; C++'s from short through **int** to long. Each size fixes a **range** (2ⁿ patterns). Every size also offers an **unsigned** twin (Pascal's byte/word; C++'s unsigned int) that spends all its patterns on 0 and positives, doubling the top at the price of negatives. Choosing a whole-number type is choosing **range and sign** together — and knowing both before the data arrives.

In your mind's eye: a family of sizes — and the sign choice.

## Sub lesson 2 — Integer arithmetic in the pair — division's two answers

The pair agrees on +, −, * and disagrees, instructively, on division. Pascal splits it: **/** gives a real, **div** the whole quotient, **mod** the remainder. C++'s **/** on two ints *is* Pascal's div — the whole quotient, fraction discarded — and **%** is its mod: 7 / 2 is 3 in C++ integers, 7 % 2 is 1. The same symbols, different contracts: the dual course's recurring lesson — **the type and the language together fix what an operator does**, never the symbol alone.

In your mind's eye: integer arithmetic in the pair — division's two answers.

## Say it to your companion

Tell your companion, in your own words: Both languages offer whole numbers in **several sizes**: Pascal's family runs from shortint and byte through **integer** to longint; C++'s from short through **int** to long. Each size fixes a **range** (2ⁿ patterns). Every size also offers an **unsigned** twin (Pascal's byte/word; C++'s unsigned int) that spends all its patterns on 0 and positives, doubling the top at the price of negatives. Choosing a whole-number type is choosing **range and sign** together — and knowing both before the data arrives. The pair agrees on +, −, * and disagrees, instructively, on division. Pascal splits it: **/** gives a real, **div** the whole quotient, **mod** the remainder. C++'s **/** on two ints *is* Pascal's div — the whole quotient, fraction discarded — and **%** is its mod: 7 / 2 is 3 in C++ integers, 7 % 2 is 1. The same symbols, different contracts: the dual course's recurring lesson — **the type and the language together fix what an operator does**, never the symbol alone. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: shortint, byte, integer, longint. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: short, int, long. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A range — 2ⁿ patterns. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: 0 and positives only — doubling the top at the price of negatives. Do this with a real example of your own and write or say how you know it is right.
