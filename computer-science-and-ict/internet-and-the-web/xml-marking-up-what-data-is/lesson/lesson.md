# XML — marking up what data is

## Do it first

Here is one fact, twice. First, styled: a big bold heading that says a book's title. Second, labelled: the same title held between tags that say what it is — a title, inside a book, with an author. Guess which version a computer can search, sort and file more easily. This lesson names that second way.

## Sub lesson 1 — Structure, not looks

**XML** — **eXtensible Markup Language** — is a markup language like HTML: tags written in `<` and `>` define elements in a document and control its structure when a suitable application processes it.

The key idea is what the tags are *about*. Presentational markup languages — RTF, PDF and HTML are the named examples — are powerful for display, but they say nothing about what the data *is*. XML describes **what data is and how it is structured**, for **storage and exchange**. XML does not change how a page looks; it changes how documents are **read, filed and stored**, and data held this way is easier to **organise and search**.

[Picture 30900 — the same page shown twice — styled for display, and labelled for meaning]

## Sub lesson 2 — Your own tags

HTML gives you a **predefined** set of tags — the same set for everyone. XML lets you **define custom tags** that meet your document's exact needs. A school can have `<student>` and `<mark>`; a shop can have `<item>` and `<price>`. Because the tags are yours, they can name the data exactly, which is why the data is easier to organise and search.

HTML and XML are **complements, not replacements**: HTML is about presentation, XML is about structure (teacher guide — evidence).

## Sub lesson 3 — Why XML exists — and Ethiopia structured in tags (teacher guide — evidence)

XML was developed in the **1990s** for a plain reason: HTML does **not allow new text elements to be defined** and is **not extensible** — you cannot add to its tag set (teacher guide — evidence). XML suits data with a **complex structure**, and supports **sharing data, transferring it, changing platforms and making data available**.

See it on home ground. Ethiopia's regions and cities can be structured with invented tags — a country element holding region elements, each region holding its cities:

```xml
<country>
  <region>
    <city>Addis Ababa</city>
  </region>
</country>
```

HTML only offers its standard set of tags for this; XML invents exactly the tags the information needs. One more use: structuring data for **storage where a relational database is inappropriate** — the next lessons return to it.

## Say it to your companion

Tell your companion what XML is, what its tags describe, and one set of tags you would invent for information from your own area.

## Do It Yourself

1. Write tags of your own for one book: a title, an author and a type, nested inside a book element.
2. Write one sentence: what does XML describe — looks, or meaning?
3. Invent tags for a market stall: the stall, and two things it sells.
