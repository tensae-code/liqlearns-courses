# Cache Memory

## Do it first

The processor is fast and main memory is slower — left alone, the fastest part of the machine would spend its time waiting. Laos's Grade 8 hardware chapter solves the waiting with a memory it gives its own section: the cache. This lesson explains the trick.

## Sub lesson 1 — What cache is and where it sits

**Cache memory** is a **very small, very fast memory** sitting **between the processor and main memory (RAM)** — in modern machines, inside or immediately beside the CPU itself. It holds **copies of the data and instructions the processor is using most, or is about to need again**. Smallness is not its failure but its price: cache is made of fast, expensive memory, so only a little of it can be afforded — just enough to hold the work's hot centre.

In your mind's eye: what cache is and where it sits.

## Sub lesson 2 — How cache speeds the machine

When the processor needs data, it looks in the **cache first**: if the data is there — a **hit** — it is delivered at cache speed and no wait happens. If it is not — a **miss** — the processor fetches from the slower RAM, and a copy is left in the cache against the next asking. The trick works because programs are loyal: they return again and again to the same instructions and nearby data. Laos names cache inside its memory section because it is memory doing a different job — not holding the most, but standing closest, so the processor almost never waits.

In your mind's eye: how cache speeds the machine.

## Say it to your companion

Tell your companion, in your own words: **Cache memory** is a **very small, very fast memory** sitting **between the processor and main memory (RAM)** — in modern machines, inside or immediately beside the CPU itself. It holds **copies of the data and instructions the processor is using most, or is about to need again**. Smallness is not its failure but its price: cache is made of fast, expensive memory, so only a little of it can be afforded — just enough to hold the work's hot centre. When the processor needs data, it looks in the **cache first**: if the data is there — a **hit** — it is delivered at cache speed and no wait happens. If it is not — a **miss** — the processor fetches from the slower RAM, and a copy is left in the cache against the next asking. The trick works because programs are loyal: they return again and again to the same instructions and nearby data. Laos names cache inside its memory section because it is memory doing a different job — not holding the most, but standing closest, so the processor almost never waits. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A very small, very fast memory between the processor and main memory. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Inside or immediately beside the CPU. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Copies of the data and instructions used most, or needed again soon. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It is made of fast, expensive memory — only a little can be afforded. Do this with a real example of your own and write or say how you know it is right.
