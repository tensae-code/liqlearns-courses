# Parallel and Serial Transmission

## Do it first

Eight messengers run side by side, each carrying one letter of a word. Or one messenger runs eight times. Both deliver the word — but the roads, the cost and the failures differ completely. Data transmission makes the same choice, and this lesson compares its two answers.

## Sub lesson 1 — Parallel — many bits at once

**Parallel transmission** sends a whole group of bits **at the same time**, each on its own wire — eight wires carry a byte in one step. It is fast per step and simple in idea, but expensive in road: many wires, and over distance the bits drift out of step (**skew**) until the group arrives ragged. Parallel therefore lives at **short distances** — inside the computer and to nearby devices — where its wires are short and its speed is real.

In your mind's eye: parallel — many bits at once.

[Picture 46141 — parallel — many bits at once]

## Sub lesson 2 — Serial — one bit after another

**Serial transmission** sends bits **one after another** along a single channel: slower per step, but one road serves any distance, the bits cannot fall out of step because they queue, and the cost stays low. Nearly everything that travels far is serial — network cables, internet links, the connections of this whole title. The comparison closes the lesson: parallel wins the sprint inside the machine; serial wins every journey beyond it — which is why the modern world is built serial, and why the next lesson's question — how the receiver keeps time with the sender — matters at all.

In your mind's eye: serial — one bit after another.

[Picture 46142 — serial — one bit after another]

## Say it to your companion

Tell your companion, in your own words: **Parallel transmission** sends a whole group of bits **at the same time**, each on its own wire — eight wires carry a byte in one step. It is fast per step and simple in idea, but expensive in road: many wires, and over distance the bits drift out of step (**skew**) until the group arrives ragged. Parallel therefore lives at **short distances** — inside the computer and to nearby devices — where its wires are short and its speed is real. **Serial transmission** sends bits **one after another** along a single channel: slower per step, but one road serves any distance, the bits cannot fall out of step because they queue, and the cost stays low. Nearly everything that travels far is serial — network cables, internet links, the connections of this whole title. The comparison closes the lesson: parallel wins the sprint inside the machine; serial wins every journey beyond it — which is why the modern world is built serial, and why the next lesson's question — how the receiver keeps time with the sender — matters at all. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A whole group of bits, each on its own wire. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Eight. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Bits drifting out of step over distance. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Short distances — inside the computer and to nearby devices. Do this with a real example of your own and write or say how you know it is right.
