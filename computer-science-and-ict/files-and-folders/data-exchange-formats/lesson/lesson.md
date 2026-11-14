# Data Exchange Formats

## Do it first

Two programs that have never met can still swap data — if they agree on a shape. This lesson learns those shapes.

## Sub lesson 1 — Why exchange needs a format — agreement before sending

Programs store data in their own internal shapes, which other programs cannot read. A **data exchange format** is an agreed public shape for handing data over: both sides know how the data is laid out, so the receiver can rebuild it. The simplest is **plain text**; a table travels as **CSV** (values separated by commas, one row per line). Armenia's Grade 6 book teaches 'general concepts of data exchange formats' as its own lesson (§17) — the concept before the tools.

[Picture — Why exchange needs a format — agreement before sending]

## Sub lesson 2 — Structured formats — XML and JSON, and choosing between them

Data with inner structure travels in **XML** (data wrapped in named tags, like <name>…</name>) or **JSON** (data written as name–value pairs and lists, borrowed from JavaScript). Both are text, so humans can read and debug them; both need the two sides to agree on the names. Choosing a format asks: Is it a flat table (CSV), a structured document (XML), or program data (JSON)? Is it readable by people? Will the receiver's program accept it?

[Picture — Structured formats — XML and JSON, and choosing between them]

## Say it to your companion

Tell your companion, in your own words: Programs store data in their own internal shapes, which other programs cannot read. A **data exchange format** is an agreed public shape for handing data over: both sides know how the data is laid out, so the receiver can rebuild it. The simplest is **plain text**; a table travels as **CSV** (values separated by commas, one row per line). Armenia's Grade 6 book teaches 'general concepts of data exchange formats' as its own lesson (§17) — the concept before the tools. Data with inner structure travels in **XML** (data wrapped in named tags, like <name>…</name>) or **JSON** (data written as name–value pairs and lists, borrowed from JavaScript). Both are text, so humans can read and debug them; both need the two sides to agree on the names. Choosing a format asks: Is it a flat table (CSV), a structured document (XML), or program data (JSON)? Is it readable by people? Will the receiver's program accept it? Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Each program stores data in its own internal shape, which others cannot read Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: An agreed public shape for handing data over, so the receiver can rebuild it Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Plain text Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Values separated by commas, one row per line Do this with a real example of your own and write or say how you know it is right.
