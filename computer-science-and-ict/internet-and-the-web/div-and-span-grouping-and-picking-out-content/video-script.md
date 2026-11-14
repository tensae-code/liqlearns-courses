# Video script — Div and Span — Grouping and Picking Out Content

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **<div>** element groups **block-level content** — paragraphs, headings, images — into one unit: a section, a card, a column. A div means nothing and displays nothing by itself; its power arrives with an attribute — a class or id — that CSS and scripts use to take hold of the whole group at once: style this section, move that card. Modern pages are built as trees of divs, each a named region of the page — the nesting lesson's boxes, given their working form.
The **<span>** element is div's inline twin: it picks out a **run of text inside a block** — one word, a price, a name — without breaking the flow or starting a new line. With a class, that run can be coloured, enlarged or scripted while its sentence flows on around it. The pair divide the world cleanly: **div for blocks, span for words inside blocks** — and choosing wrongly (a div where a span belongs) breaks the line the reader was following, which is how you know the division matters.
