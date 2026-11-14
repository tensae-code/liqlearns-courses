# Asymmetric Encryption — Two Keys

## Do it first

Remember the circle from the last lesson: to share a secret key you need a safe channel, and the safe channel was the thing you were trying to build. In the 1970s a way out was found, and it still sounds like a trick: give everyone a lock that anybody can snap shut, but that only one key — held by one person, never travelling anywhere — can open. That is asymmetric encryption, the book's 'two keys'.

## Sub lesson 1 — The key pair — a lock anyone can close

In **asymmetric** encryption every person holds not one key but a **pair**, made together and mathematically linked. The **public key** is published — printed on your page, handed to strangers, shouted in the street; its job is to **encrypt messages addressed to you**. The **private key** never leaves you; its job is to **decrypt** what your public key locked. What one key of the pair locks, only the other unlocks — and knowing the public key does not let anyone work out the private one.

Picture it as padlocks. Ana hands out open padlocks — copies of her public key — to the whole world and keeps the only opening key on her own chain. Ben puts his message in a box and snaps Ana's padlock shut. From that moment **nobody can open the box except Ana** — not a thief who steals it, not even Ben, who locked it. There was never a shared secret to intercept: the thing that travelled (the open padlock, the public key) is useless for opening.

[Picture — asymmetric-padlocks: open padlocks handed out to a crowd, one box snapped shut, and the single opening key staying on its owner's chain]

So: to write secretly **to** someone, encrypt with **their public key**. Only **their private key** — which never travelled — can read it. The direction is the whole lesson; get it the wrong way round and the system protects nothing.

## Sub lesson 2 — What two keys buy — and what they cost

The key-distribution problem does not get a better courier here — it **dissolves**. Public keys may travel by any road, however watched, because they can only lock, never unlock. Private keys never travel at all. Two people who have never met can exchange secret messages the day one of them publishes a public key, which is why your browser can open a protected connection to a shop on another continent in under a second — the web's HTTPS begins exactly here.

[Picture — asymmetric-handshake: a browser and a distant shop exchanging a public key openly, then a small symmetric key travelling inside the locked box]

The price is speed: asymmetric operations are heavy mathematics, far too slow to encrypt a film or a disk. So real systems **marry the pair of ideas**, as the last lesson promised: asymmetric encryption is used once, at the start, to carry a freshly made **symmetric key** safely to the other side; then symmetric encryption — fast — carries everything else. And the pair has a second trick, run in the reverse direction: what your **private** key locks, your **public** key can check — which is a signature, and is the next lesson.

## Say it to your companion

Tell your companion, in your own words: each person has a public key for locking messages to them and a private key, never shared, for unlocking; strangers can write secretly with no shared key first; and because the two-key method is slow, it delivers a symmetric key and then steps aside. Mime the padlocks as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say which key of a pair encrypts a message to someone, and which key decrypts it. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: explain how two strangers exchange a secret message with no shared key beforehand. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: say what asymmetric encryption costs (speed) and how real systems marry it to symmetric encryption. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
