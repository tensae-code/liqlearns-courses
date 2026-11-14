# Digital Signatures and Certificates

## Do it first

Encryption answers 'can anyone else read this?' Two other questions matter just as much in real life: 'did this truly come from who it claims?' and 'was anything changed on the way?' A forged message in perfect secrecy is still a forgery. This lesson — the book's 'signing digitally' — answers both questions with the key pair run backwards, and then faces the question underneath them all.

## Sub lesson 1 — Signing — the pair run backwards

A **digital signature** starts not with the whole message but with its **fingerprint** — a short number, called a **hash**, computed from the message by a public rule with two properties: the same message always gives the same fingerprint, and changing even one letter changes the fingerprint completely. The sender then encrypts that fingerprint with their **private key**. The encrypted fingerprint, sent along with the message, is the signature.

Checking runs the pair in reverse. The receiver computes the fingerprint of the message that arrived, and decrypts the signature with the sender's **public key**. If the two fingerprints match, two things are proven at once. **Authorship**: only the holder of the private key could have made a signature that this public key opens — so the named sender really sent it. **Integrity**: the fingerprint of what arrived matches the fingerprint of what was signed — so nothing was changed on the way, not one letter.

[Picture — signature-check: a message, its fingerprint, the fingerprint locked by a private key, and the receiver comparing two fingerprints side by side]

Notice what a signature does **not** do: it hides nothing. The message itself travels readable (unless it is also encrypted, which is a separate step with the keys in the other direction). Secrecy and proof are different jobs; this strand now holds the tool for each.

## Sub lesson 2 — Certificates — whose key is this, really?

Every check in the last part leaned on one quiet assumption: that the public key you hold really belongs to the person named. A public key is only a number — nothing in it says whose it is. An attacker can generate a fresh pair, publish the public half **under your name**, and then 'your' signatures verify beautifully — for messages the attacker wrote. The signature machinery is perfect; the name tag was the lie.

A **certificate** is the fix: a small document holding a name and that name's public key, **signed by a certificate authority (CA)** — an organisation whose own job is checking, before signing, that the key truly belongs to that name (that the applicant controls the shop's domain, is the bank it claims, and so on). Your browser and phone carry the public keys of the established CAs built in. When a website presents its certificate, the device checks the CA's signature on it — the same fingerprint-and-key check as before, one level up — and only then trusts the key inside for the connection.

[Picture — certificate-chain: a shop's certificate signed by a CA, and the browser checking the CA's signature before trusting the key]

So the strand's ideas stack: fingerprints and private keys make signatures; signatures by authorities make certificates; certificates make the public keys of strangers trustworthy — and trustworthy public keys are what the last lesson's secret-writing to strangers stood on all along.

## Say it to your companion

Tell your companion, in your own words: a signature is a message's fingerprint locked with the sender's private key, checkable by anyone with the public key — it proves who sent it and that nothing changed; a certificate is a trusted authority's signature binding a public key to a name. Sign a one-line message with a toy fingerprint together as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: walk through how a digital signature is made and checked, key by key. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: say the two things a valid signature proves, and the one thing it does not do. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: explain what a certificate is, who issues it, and the attack it defeats. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
