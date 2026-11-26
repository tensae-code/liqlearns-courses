# Coding Trees — Shorter Codes for the Most Frequent Symbols

## Do it first

In any long text, one letter returns again and again while another barely appears. If every letter cost the same code length, you pay full price for the letter that shows up a thousand times. Before reading on: what would you give the frequent letter instead?

## Sub lesson 1 — Frequent means short

Compression's cleverest trick, met in the Zip la marmotte activity, is unfair on purpose: **the most frequent symbols get the shortest codes**, and rare symbols pay with long ones. Because the frequent symbols dominate the text, the total shrinks — even though some codes grew. A code where lengths follow frequency can beat every fixed-length code on real text, whose letters are never equally frequent.

In your mind's eye: frequent means short.

[Picture 45024 — frequent means short]

## Sub lesson 2 — Reading the tree

The codes are drawn as a **coding tree (arbre de codage)**: from the root, each branch is a step — left for 0, right for 1, say — and each symbol sits at a leaf; its code is the path from root to leaf. Frequent symbols sit near the root (short paths); rare ones hang deep. The tree also guarantees decoding: since no symbol sits on another's path, a stream of bits can be cut back into symbols in exactly one way.

In your mind's eye: reading the tree.

[GIF 45025 — reading the tree]

## Say it to your companion

Tell your companion, in your own words: Compression's cleverest trick, met in the Zip la marmotte activity, is unfair on purpose: **the most frequent symbols get the shortest codes**, and rare symbols pay with long ones. Because the frequent symbols dominate the text, the total shrinks — even though some codes grew. A code where lengths follow frequency can beat every fixed-length code on real text, whose letters are never equally frequent. The codes are drawn as a **coding tree (arbre de codage)**: from the root, each branch is a step — left for 0, right for 1, say — and each symbol sits at a leaf; its code is the path from root to leaf. Frequent symbols sit near the root (short paths); rare ones hang deep. The tree also guarantees decoding: since no symbol sits on another's path, a stream of bits can be cut back into symbols in exactly one way. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The shortest codes. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Long codes. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Because frequent symbols dominate the text. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Every fixed-length code, on real text. Do this with a real example of your own and write or say how you know it is right.
