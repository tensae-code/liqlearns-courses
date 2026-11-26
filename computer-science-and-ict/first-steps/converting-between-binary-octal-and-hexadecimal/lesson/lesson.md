# Converting Between Binary, Octal and Hexadecimal

## Do it first

Converting binary to octal through decimal is honest work — and wasted work. Grade 11 teaches the family shortcut: 8 and 16 are powers of 2, so their digits are binary in bundles.

## Sub lesson 1 — Groups of three — binary and octal

Because 8 = 2³, **every octal digit is exactly three binary digits**. To convert binary → octal: split the binary number into **groups of three from the right** (pad the last group with leading zeros), and write each group's octal digit: 101110₂ → 101 | 110 → **56₈**. Octal → binary is the reverse generosity: each octal digit expands to exactly three bits. No arithmetic occurs anywhere — only **grouping** — which is why programmers read long bit strings in octal or hex rather than raw.

In your mind's eye: groups of three — binary and octal.

[Picture 45032 — groups of three — binary and octal]

## Sub lesson 2 — Groups of four — binary and hexadecimal

Because 16 = 2⁴, **every hexadecimal digit is exactly four binary digits**: split in **fours from the right** — 101110₂ → 0010 | 1110 → **2E₁₆**, hex digits running 0–9 then **A–F** for ten to fifteen. Hexadecimal → binary expands each digit to four bits. Between octal and hexadecimal themselves, binary is the honest broker: octal → binary (threes) → hex (fours). The lesson's number-sense closes Grade 11's base theory: bases are not rivals but **views** — some views group the bits for the hand and eye.

In your mind's eye: groups of four — binary and hexadecimal.

[Picture 45033 — groups of four — binary and hexadecimal]

## Say it to your companion

Tell your companion, in your own words: Because 8 = 2³, **every octal digit is exactly three binary digits**. To convert binary → octal: split the binary number into **groups of three from the right** (pad the last group with leading zeros), and write each group's octal digit: 101110₂ → 101 | 110 → **56₈**. Octal → binary is the reverse generosity: each octal digit expands to exactly three bits. No arithmetic occurs anywhere — only **grouping** — which is why programmers read long bit strings in octal or hex rather than raw. Because 16 = 2⁴, **every hexadecimal digit is exactly four binary digits**: split in **fours from the right** — 101110₂ → 0010 | 1110 → **2E₁₆**, hex digits running 0–9 then **A–F** for ten to fifteen. Hexadecimal → binary expands each digit to four bits. Between octal and hexadecimal themselves, binary is the honest broker: octal → binary (threes) → hex (fours). The lesson's number-sense closes Grade 11's base theory: bases are not rivals but **views** — some views group the bits for the hand and eye. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Because 8 = 2³ — every octal digit is exactly three binary digits. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: In threes from the right, the last group padded with leading zeros. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 56₈ (101 | 110). Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: None — only grouping. Do this with a real example of your own and write or say how you know it is right.
