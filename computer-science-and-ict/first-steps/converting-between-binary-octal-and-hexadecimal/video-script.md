# Video script — Converting Between Binary, Octal and Hexadecimal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Because 8 = 2³, **every octal digit is exactly three binary digits**. To convert binary → octal: split the binary number into **groups of three from the right** (pad the last group with leading zeros), and write each group's octal digit: 101110₂ → 101 | 110 → **56₈**. Octal → binary is the reverse generosity: each octal digit expands to exactly three bits. No arithmetic occurs anywhere — only **grouping** — which is why programmers read long bit strings in octal or hex rather than raw.
Because 16 = 2⁴, **every hexadecimal digit is exactly four binary digits**: split in **fours from the right** — 101110₂ → 0010 | 1110 → **2E₁₆**, hex digits running 0–9 then **A–F** for ten to fifteen. Hexadecimal → binary expands each digit to four bits. Between octal and hexadecimal themselves, binary is the honest broker: octal → binary (threes) → hex (fours). The lesson's number-sense closes Grade 11's base theory: bases are not rivals but **views** — some views group the bits for the hand and eye.
