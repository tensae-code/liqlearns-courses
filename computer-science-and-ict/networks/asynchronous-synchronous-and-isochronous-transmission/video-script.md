# Video script — Asynchronous, Synchronous and Isochronous Transmission

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Asynchronous transmission** sends each character in its own envelope: a **start bit** announces 'a character begins', the data bits follow, and **stop bits** close it. No shared clock runs between characters — the line may idle any length of time — so it suits irregular traffic like a keyboard's. The price is the envelope itself: extra bits on every character, a tax that grows heavy on long fast streams.
**Synchronous transmission** drops the per-character envelopes: sender and receiver share a **clock**, and data flows in large **blocks** with small control frames — the tax paid once per block, so fast bulk transfer runs efficiently. **Isochronous transmission** adds the strictest promise: bits are delivered at a **guaranteed rate with bounded delay**, because live voice and video cannot wait for late bits — a late syllable is a lost syllable. The three are one idea at three prices: agree loosely per character, agree by clock per block, or agree on time itself for streams that live or die by it.
