# XML attributes and comments

## Do it first

Look at this element: a name, with `personid="101"` riding inside its start tag. And look at a grey line beginning `<!--`. Neither is the element's content. Guess what each one is doing. This lesson names both.

## Sub lesson 1 — Attributes — a name-value pair on an element

An element can carry **attributes**. An attribute is a **name-value pair** giving **additional information about that element** — it rides inside the element's start tag:

```xml
<name personid="101">Haile</name>
```

Here **personid** is the attribute's name and **"101"** is its value. The rule that never bends: the value **must be quoted**, in **single or double quotes**.

[Picture 30904 — an element wearing a quoted attribute, beside a greyed-out comment line]

## Sub lesson 2 — Comments — notes the parser ignores

A **comment** is a **note describing the code**. It is written with the **HTML-style comment markers**:

```xml
<!-- the athlete's name -->
```

The comment is for the human reader. While the code runs, the **XML parser ignores it** — it is not data, it is not an element, and it never reaches the output. Write comments to explain; never store information in them that the document itself needs.

## Say it to your companion

Tell your companion what an attribute adds to an element, and why a writer adds a comment the reader of the output never sees.

## Do It Yourself

1. Write a name element carrying a personid attribute of "102".
2. Add a comment above it saying whose record it is.
3. Say whether the comment changes the data. It does not — say why.
