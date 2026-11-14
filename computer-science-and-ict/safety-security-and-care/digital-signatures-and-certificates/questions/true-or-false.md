# Digital Signatures and Certificates — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) Changing one letter of a signed message is detected when the signature is checked.**
**Answer: True** — The arrived message's fingerprint no longer matches the signed fingerprint.

**2. (Sub lesson 1) Anyone who holds the public key can forge the owner's signature.**
**Answer: False** — Forging needs the private key; the public key can only check.

**3. (Sub lesson 2) A certificate is issued by any website for itself, with no checks.**
**Answer: False** — A certificate authority checks the binding of name to key before signing; a self-made claim is not a certificate.

**4. (Sub lesson 2) Browsers carry the public keys of established certificate authorities built in.**
**Answer: True** — That built-in trust is what lets the browser verify a certificate's signature.
