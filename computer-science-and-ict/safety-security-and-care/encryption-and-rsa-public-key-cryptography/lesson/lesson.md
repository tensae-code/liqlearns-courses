# Encryption and RSA Public-Key Cryptography

## Do it first

Write a secret on paper and pass it across the classroom: everyone in between can read it. Now imagine the paper scrambles itself for everyone except the one friend it is meant for — even though the 'lock' you used is one you happily shout to the whole class. That impossible-sounding trick exists. It is RSA, and in this lesson you do it with real numbers.

## Sub lesson 1 — Encryption and keys

**Encryption** turns readable text — **plaintext** — into scrambled **ciphertext**, using a **key**: a secret value that steers the scrambling. The receiver uses a key to turn the ciphertext back into plaintext. In **symmetric** encryption one shared key both locks and unlocks, which raises a hard question: how do two people agree that key without an eavesdropper hearing it too? **Asymmetric**, or public-key, encryption answers it by splitting the key in two: a **public key**, shared with the whole world, that only locks; and a **private key**, never shared, that alone unlocks. Anyone can lock a message to you; only you can open it.

[Picture — two keys on a table — one labelled PUBLIC being handed out to a crowd, one labelled PRIVATE going into its owner's pocket — with a padlock snapping shut under the public key and opening only under the private one]

## Sub lesson 2 — RSA — how the two keys work

RSA builds the key pair from two large **prime numbers**, multiplied together. The public key carries the product; the private key is worked out from the primes themselves. Locking a message means doing arithmetic with the product; unlocking needs the primes — and finding them again from the product alone means factoring an enormous number, which no known method can do in useful time. That one-way street is the whole secret: easy to multiply, practically impossible to un-multiply. The book's practical implements RSA in Python with small primes, so the student watches a message become numbers, get locked with a public key, and open again only with the private one.

[Picture — two small primes, 5 and 11, multiplying into 55 with a padlock closing — then a crowd of guesses failing to split 55 back apart before the owner's private key opens it]

## Say it to your companion

Tell your companion, in your own words: encryption scrambles plaintext into ciphertext with a key; symmetric systems share one key, while public-key systems publish a locking key and keep the unlocking key private; RSA's safety rests on multiplication being easy and factoring the product practically impossible. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what plaintext, ciphertext and a key are. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: say how symmetric encryption differs from public-key encryption, and what hard question the public key answers. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: explain RSA's one-way street: primes multiply easily; the product cannot be factored back in useful time. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: follow a small-numbers RSA locking and unlocking, naming what the public and private keys each know. Do this with a real example of your own and write or say how you know it is right.
