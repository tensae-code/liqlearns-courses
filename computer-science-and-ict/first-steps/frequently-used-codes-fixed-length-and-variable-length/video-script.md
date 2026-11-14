# Video script — Frequently Used Codes — Fixed-Length and Variable-Length

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **fixed-length code** gives **every character the same number of bits**: with n bits per character, 2ⁿ different characters can be coded — 7 bits for the classic **ASCII** (128 characters), 8 bits for its extended byte forms. The architecture's virtue is simplicity: the third character of a text begins exactly at bit 2n — any place can be **found by counting**, and decoding needs no markers. A **binary alphabet** is its alphabet form: a fixed set of symbols per character, as in **Bacon's code**, where each letter is five symbols drawn from two kinds (a/b) — an early binary code in disguise.
A **variable-length code** gives **frequent characters short code words and rare characters long ones**: Morse code is its grandfather — E (the commonest letter) is one dot, Q is a long dash-dash-dot-dash. The average message then takes **fewer bits** than any fixed-length coding of the same alphabet. The price is decoding discipline: code words must be **prefix-free** (no word is the start of another) and the receiver must find the borders — Morse does it with pauses, computer codes with tree-shaped decodings. Compression begins in this section.
