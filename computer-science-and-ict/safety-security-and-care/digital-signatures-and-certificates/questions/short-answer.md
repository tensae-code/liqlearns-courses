# Digital Signatures and Certificates — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Why does the signature lock a fingerprint instead of the whole message?**
**Answer: The fingerprint is short, so signing is quick whatever the message's size — and because any change to the message changes its fingerprint, checking the small fingerprint still protects the whole message.**

**2. (Sub lesson 2) An attacker generates a key pair and publishes the public key under a bank's name. Walk through how certificates expose this.**
**Answer: The attacker's key has no certificate from a trusted authority binding it to the bank's name — obtaining one would require passing the authority's check that they are the bank. Browsers therefore refuse to trust the key, however perfectly its signatures verify.**
