# Parts of an XML document — declaration and DTD

## Do it first

Here are the top lines of a document listing two athletes. Before any names or results, there is a line in `<? … ?>`, a line starting `<!DOCTYPE`, and lines starting `<!ELEMENT`. Guess what each kind of line might be for. This lesson names all three.

## Sub lesson 1 — The declaration — version and encoding

A complete document starts with the **XML declaration**, also called a processing instruction:

```xml
<?xml version="1.0" encoding="UTF-8"?>
```

It gives the **version** and the **encoding**. The encoding named is **UTF-8** or **UTF-16** — encoding **converts Unicode characters to their binary equivalent**, so the characters of the document can be stored and read as numbers underneath.

[Picture 30902 — a full XML document with declaration, DOCTYPE and internal declarations bracketed and labelled]

## Sub lesson 2 — The DOCTYPE and the internal DTD subset

Next comes the **Document Type Declaration** — the **DOCTYPE** — describing the document's **structure and restrictions**.

Inside the same file sits the **internal DTD subset**: declarations of what each element may contain. In the athletes document the chain runs: **people** contains **person**; **person** contains **name**; **name** contains **first** and **last**:

```xml
<!DOCTYPE people [
  <!ELEMENT people (person+)>
  <!ELEMENT person (name)>
  <!ELEMENT name (first,last)>
]>
```

Each `<!ELEMENT …>` line is one link of that chain, declared inside the file itself.

## Sub lesson 3 — #PCDATA — parsed character data

The chain ends at **#PCDATA** — **parsed character data**. The first and last name elements are declared as holding #PCDATA:

```xml
<!ELEMENT first (#PCDATA)>
<!ELEMENT last (#PCDATA)>
```

Parsed character data is **the text between a start tag and an end tag** — in the document, the actual names of the two athletes, **Haile Gebrselassie** and **Derartu Tulu**, held as text inside their first and last elements. Where a declaration says #PCDATA, no more elements nest inside; the content is text the parser reads as characters.

## Say it to your companion

Tell your companion the three top parts in order, and what #PCDATA stands in for.

## Do It Yourself

1. Write a declaration for version 1.0 with UTF-8 encoding.
2. Write an internal declaration: an element `team` that contains `player`, and `player` holding #PCDATA.
3. Say what encoding does, in one sentence.
