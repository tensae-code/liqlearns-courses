# Well-formed XML — root, case and nesting rules

## Do it first

Here is a short document with five faults hidden in it: two roots fighting, a closing tag in the wrong case, two elements overlapping, an attribute with no quotes, a broken comment. Find as many as you can. This lesson names the five rules you were using — and the guide's corrected documents show the same fault families fixed (teacher guide — evidence).

## Sub lesson 1 — One root, matching case, proper nesting (doing)

A document that follows the syntax rules is **well formed**. The first three rules, each with its wrong and right form:

1. **One root only.** The root must **start and end with the same tag**, and it is the only root — everything lives inside it.
2. **Case sensitive.** Elements are **case sensitive**: a start tag and its end tag must match in case **exactly**. `<name>…</Name>` is broken; `<name>…</name>` is right.
3. **Proper nesting.** Elements **must not overlap** and must be **properly nested** inside each other — a child closes before its parent closes, never across it.

Worked fix, from the guide's corrected set (teacher guide — evidence): a birth-date element whose opening and closing tags disagree in case is corrected by making the two tags **match exactly**.

[Picture 30906 — five wrong/right pairs, each wrong one crossed and each right one ticked]

## Sub lesson 2 — Quoted values and correct comments — and the error families (doing)

Two more rules:

4. **Attribute values must always be quoted** — single or double quotes, but always quotes.
5. **Comments use the HTML-like comment syntax** — `<!--` to open, `-->` to close, nothing else.

Now hunt like the guide's corrected exercise does (teacher guide — evidence): **every piece of XML in that exercise contains an error**, and the families to look for are named — **root/parent errors, attribute errors, case-sensitivity errors and special-symbol errors**. Its corrected models include a **student element carrying an ID attribute** (quoted, as rule 4 demands) and a **full-name element** written whole. Check your own document family by family, in that order.

## Say it to your companion

Tell your companion the five rules in order, with one broken example and its fix for each.

## Do It Yourself

1. Write a well-formed note document and check it against all five rules.
2. Take a partner's document, plant one fault, and swap back to find each other's.
3. Rewrite this broken line correctly: an element opened as <Name> and closed as </name>. Correct form: <Name>…</Name> — matching case.
