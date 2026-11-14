# Digitising an Analogue Signal — short answer

Answer in your own words, in one or two sentences.

**1. (Sub lesson 1) Why does a cheap voice recorder sound thin even when its samples are perfectly kept?**
**Answer: Because it samples slowly and coarsely by design — a low rate (missing high frequencies, against the Nyquist bargain) and often a small bit depth (large quantisation error). Nothing later can restore frequencies never sampled or levels never distinguished.**

**2. (Sub lesson 2) A student proposes digitising music at 10 kHz 'to save space'. Use the sampling theorem to respond.**
**Answer: Music contains frequencies well above 5 kHz, and the theorem demands a rate at least twice the highest frequency. At 10 kHz everything above 5 kHz is lost or alias-folded into false lower tones — the saving is real but the copy is no longer faithful; telephony accepts exactly this trade for voice, music does not.**
