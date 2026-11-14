# Video script — Data Exchange Formats

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Programs store data in their own internal shapes, which other programs cannot read. A **data exchange format** is an agreed public shape for handing data over: both sides know how the data is laid out, so the receiver can rebuild it. The simplest is **plain text**; a table travels as **CSV** (values separated by commas, one row per line). Armenia's Grade 6 book teaches 'general concepts of data exchange formats' as its own lesson (§17) — the concept before the tools.
Data with inner structure travels in **XML** (data wrapped in named tags, like <name>…</name>) or **JSON** (data written as name–value pairs and lists, borrowed from JavaScript). Both are text, so humans can read and debug them; both need the two sides to agree on the names. Choosing a format asks: Is it a flat table (CSV), a structured document (XML), or program data (JSON)? Is it readable by people? Will the receiver's program accept it?
