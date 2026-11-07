# Hands-on — Quaternions

The lesson followed one extended reading (China, B-edition Compulsory Volume 4, Ch.10, printed pp.47–48).

## The cycle on paper
Draw a triangle with corners i, j, k and arrows running i → j → k → i. Travelling WITH the arrows gives the positive products: ij = k, jk = i, ki = j. Travelling AGAINST them gives the negatives: ji = −k, kj = −i, ik = −j. Cover the table and rebuild all six products from your triangle alone.

## Order matters, in your hands
Compute (1 + i)(1 + j) by expanding: 1 + i + j + ij = 1 + i + j + k. Now compute (1 + j)(1 + i): 1 + j + i + ji = 1 + i + j − k. The two answers differ only in the k term's sign — non-commutativity you produced yourself, not a rule you were told (extended reading, printed pp.47–48).

## Squares that are −1
Verify from the table that i² = j² = k² = −1 is consistent with the cycle: ij = k, so (ij)² = k²; also i(j i)i… — simpler: multiply ij = k on the left by i: i²j = ik, that is −j = ik, matching the table's ik = −j. The reading's rules hang together; check one more link of your own (jk = i, multiply by j on the left).

## Conjugate and length
Take q = 1 + 2i − j + 2k. Write its conjugate (flip the three imaginary signs): 1 − 2i + j − 2k. Compute q times its conjugate part by part as far as the units allow and notice the cross terms in each unit cancel in pairs, leaving a real number: 1 + 4 + 1 + 4 = 10 = |q|², so |q| = √10 — the complex pattern z·z̄ = |z|², one dimension up (extended reading, printed pp.47–48).
