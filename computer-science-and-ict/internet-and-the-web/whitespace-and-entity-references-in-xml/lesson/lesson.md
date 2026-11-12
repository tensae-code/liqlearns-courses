# Whitespace and entity references in XML

## Do it first

Type this as content in a document: `5 < 6`. Save it, open it — and meet an error. The parser read your less-than sign as the start of a new element. This lesson teaches the swap that fixes it, and one more rule about the spaces in your lines.

## Sub lesson 1 — Whitespace — XML keeps it all (doing)

Space first. **XML does not truncate multiple white spaces** — a run of spaces in your content stays a run of spaces when the document is processed.

**HTML does the opposite**: it **collapses** multiple white spaces **to one**. The same typed line therefore keeps its wide gaps in XML and loses them in HTML. When the spacing is part of the data, XML preserves it; write your content knowing the spaces will survive.

[Picture 30907 — a sentence keeping all its spaces, beside a < being swapped for its reference]

## Sub lesson 2 — Entity references — the five predefined swaps (doing)

Characters with **special meaning** must be replaced by **entity references**. A `<` inside content is read by the parser as **a new element's start** — and errors. So it is written as the reference for less than: `&lt;`.

The **five predefined references**:

- `&lt;` — less than `<`
- `&gt;` — greater than `>`
- `&amp;` — ampersand `&`
- `&apos;` — apostrophe `'`
- `&quot;` — quotation mark `"`

Only **`<` and `&` are strictly illegal** as themselves — but replacing **`>`** too is **good habit**, so do it.

## Say it to your companion

Tell your companion the whitespace rule, then recite the five references and what each stands for.

## Do It Yourself

1. Write `Tom & Jerry <3` as safe XML content, using references.
2. Write a line with a wide gap of spaces and say what XML does with it.
3. List the five references from memory and check them.
