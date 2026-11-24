# Asynchronous, Synchronous and Isochronous Transmission

## Do it first

Serial bits arrive one after another — but how does the receiver know where one character ends and the next begins, or even when each bit starts? Sender and receiver must agree on time itself. There are three classic agreements, and this lesson walks them in order of strictness.

## Sub lesson 1 — Asynchronous — start and stop bits

**Asynchronous transmission** sends each character in its own envelope: a **start bit** announces 'a character begins', the data bits follow, and **stop bits** close it. No shared clock runs between characters — the line may idle any length of time — so it suits irregular traffic like a keyboard's. The price is the envelope itself: extra bits on every character, a tax that grows heavy on long fast streams.

In your mind's eye: asynchronous — start and stop bits.

## Sub lesson 2 — Synchronous — blocks under one clock; isochronous — time itself guaranteed

**Synchronous transmission** drops the per-character envelopes: sender and receiver share a **clock**, and data flows in large **blocks** with small control frames — the tax paid once per block, so fast bulk transfer runs efficiently. **Isochronous transmission** adds the strictest promise: bits are delivered at a **guaranteed rate with bounded delay**, because live voice and video cannot wait for late bits — a late syllable is a lost syllable. The three are one idea at three prices: agree loosely per character, agree by clock per block, or agree on time itself for streams that live or die by it.

In your mind's eye: synchronous — blocks under one clock; isochronous. Time itself guaranteed.

## Say it to your companion

Tell your companion, in your own words: **Asynchronous transmission** sends each character in its own envelope: a **start bit** announces 'a character begins', the data bits follow, and **stop bits** close it. No shared clock runs between characters — the line may idle any length of time — so it suits irregular traffic like a keyboard's. The price is the envelope itself: extra bits on every character, a tax that grows heavy on long fast streams. **Synchronous transmission** drops the per-character envelopes: sender and receiver share a **clock**, and data flows in large **blocks** with small control frames — the tax paid once per block, so fast bulk transfer runs efficiently. **Isochronous transmission** adds the strictest promise: bits are delivered at a **guaranteed rate with bounded delay**, because live voice and video cannot wait for late bits — a late syllable is a lost syllable. The three are one idea at three prices: agree loosely per character, agree by clock per block, or agree on time itself for streams that live or die by it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The receiver knowing where each bit and character begins. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A start bit and stop bits. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Irregular traffic like a keyboard's. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Extra bits on every character. Do this with a real example of your own and write or say how you know it is right.
