# Bits, Bytes and Number Systems

## Do it first

Inside a computer there are no letters, no photographs, no tunes — there are only two signs, 0 and 1, repeated billions of times. That sounds like far too little to hold a film or a song. This lesson — the book's 'what the computer understands' — shows how two signs are enough: how they are bundled into bytes, how counting works when you may only use two digits, and how quickly the bundles climb from one bit to a whole library.

## Sub lesson 1 — Bits and bytes — the computer's two-sign code

The computer's code has exactly two signs. A **bit** is a single one of them — 0 or 1 — physically one switch off or on, one magnetised spot one way or the other. One bit can say only two things (yes/no, off/on), but bits are never alone for long.

Eight bits in a row make one **byte**, and a byte is the computer's working bundle: 8 two-way choices give 2 × 2 × 2 × 2 × 2 × 2 × 2 × 2 = **256 different patterns**, enough to give every letter, digit and punctuation mark its own pattern, as character codes like ASCII do — the letter A lives in machines as the byte 01000001.

[Picture — bits-and-byte: eight switches in a row, some on and some off, spelling one byte, with the letter it stands for beside it]

From the byte the sizes climb a staircase, each step 1,024 of the step below (about a thousand): **kilobyte (KB)** ≈ a page of text; **megabyte (MB)** ≈ a photo; **gigabyte (GB)** ≈ a film; **terabyte (TB)** ≈ a whole library shelf of films. When a phone says '128 GB', it is counting these bundles — some 128 billion bytes, over a trillion bits, all of them just 0s and 1s.

## Sub lesson 2 — Number systems — counting in twos, tens and sixteens

Decimal counting is one choice among many. A **number system** is fixed by its **base** — how many digits it has — and every place is worth the base times the place before it. Decimal (base 10) has places 1, 10, 100. The computer counts in **binary** (base 2): digits only 0 and 1 (the bits themselves), places 1, 2, 4, 8, 16, 32.

Reading binary is adding the places that carry a 1: 1101₂ = 8 + 4 + 0 + 1 = **13**. Writing decimal in binary runs the other way: take away the largest power of two that fits, mark 1 at that place, continue with what is left. For 13: take 8 (place marked 1), 5 remains; take 4 (1), 1 remains; take 1 (1), the 2-place gets 0 — 1101₂ again, checked both ways.

[Picture — binary-place-values: the number 13 built three ways — thirteen stones, decimal digits over places 10 and 1, binary digits over places 8, 4, 2, 1]

Binary numbers grow long, so the people who work close to machines write them in **hexadecimal** (base 16): digits 0–9 plus letters A–F for ten to fifteen. Its one convenience rules them all: **one hexadecimal digit is exactly four bits** (2⁴ = 16), so a byte is always exactly two hex digits — 01000001 is 41 in hex, and the letter A in ASCII is '41' in the machine's shorthand. Same numbers, three sets of clothes; converting never changes the value, only its writing.

## Say it to your companion

Tell your companion, in your own words: a bit is one of the computer's two signs; eight bits make a byte with 256 patterns; sizes climb KB, MB, GB, TB; and number systems differ by base — binary counts in twos, hexadecimal writes four bits as one digit. Count to ten in binary on your fingers as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a bit and a byte are, and count in binary up to at least 31. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: convert small numbers between binary and decimal using place values. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: climb the size staircase — bit, byte, KB, MB, GB, TB — and say roughly what each holds. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
