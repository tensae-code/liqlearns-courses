# Video script — Integer Representation and Data Range

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

With **n bits** a type can hold **2ⁿ different patterns**. An unsigned type spends them all on 0 and positives (8 bits: **0 to 255**); a signed type spends about half on negatives (8 bits: **−128 to 127**). Bigger types widen the range: more bits, astronomically more values. Choosing a type is choosing a range big enough for the job — and no bigger than needed.
Signed integers are stored in **two's complement**, the scheme that lets the same addition circuits work for negative and positive numbers. The danger at the edges is **overflow**: add 1 to the maximum and the value wraps to the minimum — 127 + 1 in a signed byte becomes **−128** — with no error message. Programs that count people, money or measurements must use types whose range the data can never outgrow.
