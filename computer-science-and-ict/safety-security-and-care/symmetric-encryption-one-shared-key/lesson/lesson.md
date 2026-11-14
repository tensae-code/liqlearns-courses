# Symmetric Encryption — One Shared Key

## Do it first

Write a note you would not want read aloud, fold it, and imagine it passing through twenty hands to reach your friend. Every hand could open it. The oldest fix in secret writing is to scramble the message so only someone holding the key can unscramble it. This lesson works that fix properly — symmetric encryption — with the simplest real cipher, and then stares at its catch: how does your friend get the key?

## Sub lesson 1 — One key, both ways — the shift cipher at work

**Encryption** turns readable **plaintext** into unreadable **ciphertext** using a **key**; **decryption** turns it back. In **symmetric** encryption, one and the same key does both jobs — like one padlock key that both locks and unlocks.

The book's hands-on example is the oldest cipher in the story: the **shift cipher** of Julius Caesar. The key is a number, say 3. To encrypt, move every letter 3 places forward in the alphabet (wrapping Z back round to A): H → K, A → D, L → O, so HALLO becomes KDOOR. To decrypt, the receiver — who must know the key is 3 — moves every letter 3 places back. Same key, both directions: that is the meaning of symmetric, and every modern system keeps the shape. Today's working symmetric cipher, **AES**, scrambles whole blocks of bits through many rounds of mixing directed by a key of 128 bits or more — but sender and receiver still hold *the same* key, exactly as with Caesar.

[Picture — symmetric-shift-wheel: two alphabet rings, the inner turned by three, with H pointing to K]

A bigger key is the difference between a toy and a tool. A shift key has only 25 possible values — an attacker tries them all in a minute. An AES key has more possible values than there are atoms in the Earth, so trying them all is not a plan; the mathematics, not secrecy about the method, is what protects the message. The method is public. The **key** is the secret.

## Sub lesson 2 — The catch — getting the key there

Symmetric encryption has one great strength: it is **fast**, so it carries the world's bulk traffic — whole disks, video calls, long files. And it has one famous problem, named every time this strand is taught: **key distribution**.

Before the first secret message, both sides must hold the same key. But how does the key travel? Send it with the message and an interceptor takes both. Send it earlier by the same unsafe channel and it can be taken then. The key needs a safe channel — but a safe channel is exactly what encryption was supposed to create. For two thousand years the practical answers were physical: a trusted courier, a meeting in person, code books carried by hand. They work for generals; they cannot work for you buying something from a shop's website you have never visited, in another country, in the next ten seconds.

[Picture — symmetric-key-problem: two people with one padlock key each and a thief watching the road the spare key must travel]

Hold the problem clearly, because the next lesson exists to solve it: **asymmetric encryption**, with two keys instead of one, is the answer the 1970s found — and real systems then marry the two: asymmetric encryption carries a fresh symmetric key safely, and symmetric encryption carries the heavy data fast. Neither half is the whole story; this lesson is the half that does the heavy lifting.

## Say it to your companion

Tell your companion, in your own words: symmetric encryption uses one shared key to lock and unlock; it is fast and carries bulk data; its problem is getting that key to both sides safely before anything travels. Encrypt a three-letter word for your companion as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: encrypt and decrypt a short message with a simple shift (Caesar) key. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: say what makes an encryption symmetric, and name its great strength. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: explain the key-distribution problem in your own words. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
