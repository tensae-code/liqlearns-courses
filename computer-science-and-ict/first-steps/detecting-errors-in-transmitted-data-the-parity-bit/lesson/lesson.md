# Detecting Errors in Transmitted Data — The Parity Bit

## Do it first

A message crosses a noisy wire and one bit flips on the way. The receiver gets a wrong letter — and no alarm rings. Before reading on: what cheap trick could make the wrongness visible at the other end?

## Sub lesson 1 — One extra bit that watches the others

The **parity bit (bit de parité)** is one extra bit sent with each group of data bits, chosen so the total count of 1s is **even** (even parity) — or odd, if the two sides agreed odd. The receiver counts again: if the parity is wrong, something flipped on the journey. The inquiry's experiment is the whole idea in miniature: send, flip one bit in secret, and watch the count expose it.

In your mind's eye: one extra bit that watches the others.

## Sub lesson 2 — What parity can and cannot do

Parity **detects** a single flipped bit — it cannot say which bit flipped, so it cannot correct the error, only declare the group suspect. Two flips restore the parity and slip past unseen: parity is a cheap alarm, not a guard. Real systems stack stronger checks on the same idea — more check bits, cleverer counts — but every error-detecting code is parity's descendant: spare a little data to watch the rest.

In your mind's eye: what parity can and cannot do.

## Say it to your companion

Tell your companion, in your own words: The **parity bit (bit de parité)** is one extra bit sent with each group of data bits, chosen so the total count of 1s is **even** (even parity) — or odd, if the two sides agreed odd. The receiver counts again: if the parity is wrong, something flipped on the journey. The inquiry's experiment is the whole idea in miniature: send, flip one bit in secret, and watch the count expose it. Parity **detects** a single flipped bit — it cannot say which bit flipped, so it cannot correct the error, only declare the group suspect. Two flips restore the parity and slip past unseen: parity is a cheap alarm, not a guard. Real systems stack stronger checks on the same idea — more check bits, cleverer counts — but every error-detecting code is parity's descendant: spare a little data to watch the rest. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: One extra bit sent with each group of data bits. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Even. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It counts again — wrong parity means something flipped. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Even or odd parity. Do this with a real example of your own and write or say how you know it is right.
