# Root, elements and data — the XML tree

## Do it first

Take the athletes document — people, person, name, first, last, and the names themselves. Draw it as boxes joined by lines, with the biggest box at the top. This lesson names every part of what you drew, and gives the drawing its name.

## Sub lesson 1 — Content, root, tags, elements, data

The content parts of a document, one by one.

- The **content**, or information set, is **the information the elements convey** — what the document actually says.
- The **root element** is the **single** element that **encloses everything** — in the athletes document, **people**.
- A **start tag** opens an element and an **end tag** closes it, and the end tag's name must **exactly match** the start tag's.
- The **element** itself runs **from its start tag to its end tag** — it is the **basic building block**, identifying and describing data.
- The **data** is what is **held between the tags** — the names themselves.

[Picture 30903 — an XML document beside its upside-down tree with root at the top]

## Sub lesson 2 — The upside-down tree — and what XML still needs

Put the parts together and they form a **hierarchy**: the root containing **sub-elements**, which contain **further sub-elements and data**. Drawn, that hierarchy is an **upside-down tree** — root at the top, branches growing downwards, data at the ends. Watch the GIF: the document unfolds into its tree.

One limit to hold: **XML alone is not a finished document.** Combined with **other resources, such as a style sheet**, it becomes one — the XML holds the structured data, the other resource presents it.

[GIF 30920 — a document unfolding into its tree, the hierarchy appearing level by level]

## Say it to your companion

Tell your companion the parts in order from root to data, and draw the tree as you speak.

## Do It Yourself

1. Draw the tree of the books record from the earlier lesson.
2. Write one element in full and label its start tag, data and end tag.
3. Say what must be added to XML to make a finished document.
