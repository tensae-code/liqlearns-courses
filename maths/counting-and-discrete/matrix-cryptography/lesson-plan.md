# Lesson plan — Matrix Cryptography

**One thing:** hiding a message with a matrix — turn letters into numbers with a letter–number table, group the numbers in pairs, multiply each pair by a 2×2 coding matrix to get the cryptogram, and undo it at the other end with the coding matrix's inverse.

**Stage:** Counting and Discrete Mathematics (Stage 14). **Level 149** (Rwanda merge, 2026-11-07).

**Why this lesson exists:** Rwanda's Senior Six Advanced Learner's Book opens its matrices-transformation unit with a worked matrix cryptogram — encoding and decoding a message with a 2×2 coding matrix. Nothing else in the read set uses matrices to encode information, and the matrices lesson's work is transformations and systems, not codes. Under the everything-goes-in ruling (2026-11-06), it gets its own lesson. The source is one short section of two printed pages, so the lesson is honestly small. S5/S6 books in this set are the Advanced Mathematics stream, and this lesson says so. If you know the matrices lesson already, this lesson will be easier for you — you might try it first; it is a soft hint, never a gate.

## The climb

1. **Letters into numbers** — the letter–number table (A = 1, B = 2, …, Z = 26); the book's printed table mislabels two entries, taught corrected (10 = J, 11 = K).
2. **Encoding** — split the number stream into pairs, write each pair as a column, and multiply by the 2×2 coding matrix; the results are the cryptogram.
3. **Decoding** — the coding matrix must have an inverse (its determinant must not be 0); multiply the cryptogram's pairs by the inverse matrix to recover the numbers, then read the numbers back through the table as letters.

## Add-on slots

- slot-crypto-0 (IMAGE): a picture of the letter–number table with the J and K entries highlighted at 10 and 11. What the student does: says the numbers for J and K and why the printed table's "7 = J, 8 = K" must be wrong (7 and 8 are already G and H).
- slot-crypto-1 (IMAGE): a picture of the pair (8, 9) — the word HI — entering a box labelled with the coding matrix and coming out as the pair (25, 17). What the student does: carries out the multiplication by hand before the answer is shown.
- slot-crypto-2 (GIF, 1–2 s): a strip showing a cryptogram pair passing through a box labelled with the inverse matrix and the letters H, I reappearing. What the student does: watches, then states what made decoding possible — the inverse exists.
