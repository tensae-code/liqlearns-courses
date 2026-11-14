# Asymmetric Encryption — Two Keys — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Explain to a friend why publishing your public key does not endanger your messages.**
**Answer: The public key can only lock messages addressed to me; it cannot unlock anything, and the private key — which never leaves me — cannot be worked out from it. An attacker holding my public key can do exactly what everyone is invited to do: write to me.**

**2. (Sub lesson 2) Why don't websites simply use asymmetric encryption for everything?**
**Answer: Because it is slow: its mathematics is heavy, so encrypting whole visits or files asymmetrically would crawl. Systems use it once to deliver a symmetric key safely, then let fast symmetric encryption carry the bulk.**
