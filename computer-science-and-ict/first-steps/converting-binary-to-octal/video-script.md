# Video script — Converting Binary to Octal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Starting at the **right-hand end** of the binary number, split the bits into **groups of three**. Grouping must start from the right because the places run from the right; grouping from the left would misplace every value. If the last group on the left has only one or two bits, it still counts as a group — think of it as filled with leading zeros (10 is 010) without changing the number's value.
Read **each group as one octal digit** (000→0 up to 111→7) and write the digits in order: 100111₂ → groups 100 | 111 → 4, 7 → **47₈**. The binary number 101010₂ → 101 | 010 → **52₈**. Malaysia teaches the two directions together: octal-to-binary spreads each digit into three bits; binary-to-octal gathers three bits into each digit — inverse roads over the same kinship.
