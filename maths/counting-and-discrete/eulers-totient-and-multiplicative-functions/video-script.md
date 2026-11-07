# Video script — Euler's Totient and Multiplicative Functions

Super-simple voice. The tutor talks; the numbers 1 to 12 stay on screen in a row, and the ones with no factor in common with the chosen number light up.

---

Pick a number — say 10. Now count how many numbers from 1 to 10 share no factor with it. 1, yes. 2 shares. 3, yes. 5 shares. 7, yes. 9, yes. Four numbers: 1, 3, 7, 9. That count has a name and a symbol: Euler's function, φ(10) = 4.

A Grade 12 book from North Macedonia prints the whole table up to 12: 1, 1, 2, 2, 4, 2, 6, 4, 6, 4, 10, 4. Look at the primes in the table — 3 gives 2, 5 gives 4, 7 gives 6, 11 gives 10. Always one less. That is a theorem: φ of a prime p is p − 1, because nothing below a prime shares a factor with it.

Now the magic trick. 12 is 3 times 4, and 3 and 4 share no factor. φ(3) is 2, φ(4) is 2, and 2 times 2 is 4 — which is φ(12), straight from the table. A function that splits like this over coprime factors is called multiplicative, and φ is one.

But watch the condition: coprime. The book's theorem, as printed, forgets to say it — it claims the split for all numbers. Its own table catches the slip: φ(4) is 2, but φ(2) times φ(2) is 1 times 1, which is 1. Not equal. 2 and 2 are not coprime, so no split is owed. Put the word "coprime" back — exactly as the book's own proof assumes — and the theorem stands.

Count the coprime ones. Split over coprime factors. Never split over the rest. That is Euler's function.
