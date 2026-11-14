# Video script — Cache Memory

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Cache memory** is a **very small, very fast memory** sitting **between the processor and main memory (RAM)** — in modern machines, inside or immediately beside the CPU itself. It holds **copies of the data and instructions the processor is using most, or is about to need again**. Smallness is not its failure but its price: cache is made of fast, expensive memory, so only a little of it can be afforded — just enough to hold the work's hot centre.
When the processor needs data, it looks in the **cache first**: if the data is there — a **hit** — it is delivered at cache speed and no wait happens. If it is not — a **miss** — the processor fetches from the slower RAM, and a copy is left in the cache against the next asking. The trick works because programs are loyal: they return again and again to the same instructions and nearby data. Laos names cache inside its memory section because it is memory doing a different job — not holding the most, but standing closest, so the processor almost never waits.
