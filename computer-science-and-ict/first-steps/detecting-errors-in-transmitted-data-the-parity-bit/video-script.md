# Video script — Detecting Errors in Transmitted Data — The Parity Bit

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **parity bit (bit de parité)** is one extra bit sent with each group of data bits, chosen so the total count of 1s is **even** (even parity) — or odd, if the two sides agreed odd. The receiver counts again: if the parity is wrong, something flipped on the journey. The inquiry's experiment is the whole idea in miniature: send, flip one bit in secret, and watch the count expose it.
Parity **detects** a single flipped bit — it cannot say which bit flipped, so it cannot correct the error, only declare the group suspect. Two flips restore the parity and slip past unseen: parity is a cheap alarm, not a guard. Real systems stack stronger checks on the same idea — more check bits, cleverer counts — but every error-detecting code is parity's descendant: spare a little data to watch the rest.
