# Encryption and RSA Public-Key Cryptography — short answer

Answer each question in a few sentences.

**1. (Sub lesson 1) A friend says: 'If your public key is public, anyone can read your mail.' Correct the mistake in two sentences.**
**Answer:** The public key can only lock messages, never unlock them. Only the private key — which never leaves its owner — can open what the public key locked, so publishing the public key is safe.

**2. (Sub lesson 2) Why would RSA collapse if factoring large numbers suddenly became fast?**
**Answer:** Because the private key is derived from the two primes, and the public key reveals their product. If anyone could factor that product quickly, they would recover the primes, rebuild the private key, and unlock every message locked to that public key.
