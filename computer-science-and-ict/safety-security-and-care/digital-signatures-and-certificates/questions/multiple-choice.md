# Digital Signatures and Certificates — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) A digital signature is made by encrypting the message's fingerprint with the sender's —**
a) Public key  b) Private key  c) The receiver's public key  d) A symmetric key
**Answer: b) Private key** — Only the owner can sign; anyone can check — private locks, public checks.

**2. (Sub lesson 1) The fingerprint of a message is its —**
a) First line  b) Hash — a short number computed from the whole message  c) Signature  d) Certificate
**Answer: b) Hash — a short number computed from the whole message** — One changed letter changes the fingerprint completely — that is its use.

**3. (Sub lesson 1) A valid signature proves —**
a) The message is secret  b) The named sender sent it, and it was not changed  c) The message is true  d) The receiver read it
**Answer: b) The named sender sent it, and it was not changed** — Authorship and integrity — proof, not secrecy and not truth.

**4. (Sub lesson 1) A signature does NOT —**
a) Prove authorship  b) Detect changes  c) Hide the message  d) Need the private key
**Answer: c) Hide the message** — Signing is not encrypting; the message travels readable unless separately encrypted.

**5. (Sub lesson 2) A certificate binds together —**
a) Two messages  b) A name and its public key, signed by a certificate authority  c) A password and a user  d) A shop and its prices
**Answer: b) A name and its public key, signed by a certificate authority** — The CA's signature is the trust: this key really belongs to this name.

**6. (Sub lesson 2) The attack a certificate defeats is —**
a) Spam  b) Impersonation — an attacker publishing their own key under your name  c) Viruses  d) Slow networks
**Answer: b) Impersonation — an attacker publishing their own key under your name** — Without certificates, the name tag on a key can lie; the CA's check is the defence.
