# Encoders and Decoders — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) A classmate says the encoder and decoder are 'the same circuit turned around'. Say what is right and what is missing in that claim.**
**Answer: The directions are indeed opposite — encoder: many lines to a code; decoder: a code to one line. What the claim misses is the insides: the encoder is built from OR gates (each output bit gathers several inputs), the decoder from AND gates with inverters (each output detects one exact pattern).**

**2. (Sub lesson 2) Why does each decoder output need its own AND gate with its own pattern of inverters?**
**Answer: Because exactly one output may be active for each input code. An AND gate with the right plain/inverted inputs fires for exactly one pattern and no other, so giving each output such a gate — one per pattern — guarantees one active output at a time.**
