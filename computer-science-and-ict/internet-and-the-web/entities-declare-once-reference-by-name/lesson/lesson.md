# Entities — declare once, reference by name

## Do it first

In a publication block, where the publisher's full name should stand, there is only a short token between an `&` and a `;`. Yet when the document is processed, the full name appears. Where was the full name hiding? This lesson shows the declaration that ties the name to the text.

## Sub lesson 1 — Declaring and using an entity (doing)

An **entity** is a **declared name that stands in place of content or markup**, and it **must be declared before use**.

An **internal parsed entity** refers to **text a processor must parse**. It is declared with an **ENTITY declaration** tying a **name** to **replacement content** — a publisher name tied to a printing company's name:

```xml
<!ENTITY publisher "Printing Company">
```

In the document, the entity is used in its **reference form — the name between `&` and `;`** — inside an author/publication block:

```xml
<publisher>&publisher;</publisher>
```

When the document is processed, **the parser expands the reference into the full text**. Watch the GIF: the short reference grows into the full line.

[Picture 30910 — a short reference token expanding into a full publisher line]

[GIF 30922 — an entity reference expanding into its full text as the parser processes it]

## Sub lesson 2 — The textbook example — author and copyright by entity (teacher guide — evidence)

The guide's complete internal-DTD answer works the same move at book size (teacher guide — evidence): **author** and **copyright** entities are **defined once** in the internal DTD, then **used inside a textbook element**:

```xml
<!ENTITY author "The Book Author">
<!ENTITY copyright "Copyright The Publisher">
```

```xml
<textbook>
  <authorline>&author;</authorline>
  <copyrightline>&copyright;</copyrightline>
</textbook>
```

Processed, the document **assembles the book's author and copyright lines from the entities** — change the declaration once, and every reference in the book follows. That is the whole economy of entities: **declare once, reference by name, everywhere**.

## Say it to your companion

Tell your companion how an entity is declared, how it is used, and what the parser does when it meets the reference.

## Do It Yourself

1. Declare an entity for your school's full name and use it twice in a small document.
2. Write the reference form for an entity named `publisher`.
3. Build a textbook element that uses author and copyright entities, as the guide's answer does (teacher guide — evidence).
