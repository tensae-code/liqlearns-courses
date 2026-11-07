# Matrix Cryptography

## You do it first

Write down a two-letter word. Now suppose you must send it so that anyone who intercepts the message sees only numbers — and the numbers must not be the letters' own positions, or the code is no code at all.

A matrix can scramble the numbers for you, and its inverse can unscramble them. That is the whole of this short lesson — the opening worked example of Rwanda's Senior Six **Advanced** matrices unit. If you know the matrices lesson already, this lesson will be easier for you — you might try it first; that is a soft hint, never a gate. (Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 7, printed pp. 345–346.)

## Step 1 — Letters into numbers

The code starts with a **letter–number table**: A = 1, B = 2, C = 3, and so on to Z = 26. (The book's printed table mislabels two entries — it prints "7 = J" and "8 = K". Taught corrected: **10 = J and 11 = K**; 7 and 8 are already G and H.) A message becomes a stream of numbers: HI becomes 8, 9. (Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 7, printed p. 345.)

## Step 2 — Encoding with the coding matrix

Split the number stream into **pairs**, write each pair as a column, and multiply every pair by the same secret 2×2 **coding matrix**. With the coding matrix

    C = [2 1]
        [1 1]

the pair for HI is encoded as:

    [2 1] [8]   [2×8 + 1×9]   [25]
    [1 1] [9] = [1×8 + 1×9] = [17]

The pair (25, 17) is the **cryptogram** for HI. A longer message is encoded pair after pair with the same matrix: MATH becomes 13, 1 and 20, 8, encoded as (27, 14) and (48, 28). Anyone intercepting the cryptogram sees numbers that are not letter positions — the multiplication has mixed each pair together. (Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 7, printed pp. 345–346.)

## Step 3 — Decoding with the inverse

Decoding is the same road backwards, and it needs the coding matrix's **inverse**. That is why a coding matrix must be chosen with a **non-zero determinant**: no inverse, no decoding. Here det C = 2×1 − 1×1 = 1, and

    C⁻¹ = [ 1 −1]
          [−1  2]

Apply it to the cryptogram pair:

    [ 1 −1] [25]   [25 − 17]   [8]
    [−1  2] [17] = [−25 + 34] = [9]

Back come 8 and 9 — and the table reads them as H and I. Whoever holds the matrix (or its inverse) holds the key; whoever holds only the cryptogram holds arithmetic they cannot undo without it. (Rwanda, Advanced Mathematics, Learner's Book, Senior Six, Unit 7, printed p. 346.)

> **Tip — from us, not from the books:** decode one pair and read it before decoding the rest. If the first pair does not come back as a sensible letter pair, the inverse is wrong — and finding that out after one pair is far cheaper than after twenty.

## Say it to your companion

Explain to your companion the full round trip — letters, numbers, pairs, coding matrix, cryptogram, inverse, numbers, letters — and have them explain back why the coding matrix's determinant must not be zero.

## Do It Yourself

1. Write GO as numbers, then encode it with the coding matrix C above.
2. Decode the cryptogram pair (27, 14) using C⁻¹ above, and read the word.
3. A cryptogram pair under a different coding matrix decodes to the numbers 10 and 11. What two letters were sent?
