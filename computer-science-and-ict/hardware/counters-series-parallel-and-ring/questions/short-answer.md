# Counters — Series, Parallel and Ring — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Why can a long ripple counter briefly show a wrong number during counting?**
**Answer: Because the stages change one after another as the change ripples down the chain: between the first stage flipping and the last stage settling, the outputs pass through combinations that are not the true next count. Anyone reading exactly in that instant reads a wrong value.**

**2. (Sub lesson 2) A machine must switch on one of ten lamps in turn, one per pulse, each lamp driven directly by one wire. Which counter fits, and what does it cost?**
**Answer: A ring counter with ten flip-flops: the single circulating 1 gives one active output per state, and each lamp is wired to its own output with no decoder between. The cost is flip-flops — ten cells for ten states, where a binary counter would need only four cells (16 states) plus a decoder.**
