# Video script — Coding Trees — Shorter Codes for the Most Frequent Symbols

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Compression's cleverest trick, met in the Zip la marmotte activity, is unfair on purpose: **the most frequent symbols get the shortest codes**, and rare symbols pay with long ones. Because the frequent symbols dominate the text, the total shrinks — even though some codes grew. A code where lengths follow frequency can beat every fixed-length code on real text, whose letters are never equally frequent.
The codes are drawn as a **coding tree (arbre de codage)**: from the root, each branch is a step — left for 0, right for 1, say — and each symbol sits at a leaf; its code is the path from root to leaf. Frequent symbols sit near the root (short paths); rare ones hang deep. The tree also guarantees decoding: since no symbol sits on another's path, a stream of bits can be cut back into symbols in exactly one way.
