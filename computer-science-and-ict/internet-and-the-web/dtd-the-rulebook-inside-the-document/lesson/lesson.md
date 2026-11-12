# DTD — the rulebook inside the document

## Do it first

An album record lists its parts in this order: name, singer, release, language. Somewhere a rule says the order should be singer, name, release, language. Is this record acceptable — and who decides? This lesson opens the rulebook that decides.

## Sub lesson 1 — What a DTD is — and where it sits (doing)

A **DTD — Document Type Definition — defines a document's structure and its legal elements and attributes**. With the DTD in hand, an **application can verify that XML data is valid** — that it obeys the rules its own document declares.

An **internal DTD** sits **inside the XML file**, **wrapped in the DOCTYPE definition** — the rulebook travels with the document it rules, in the same file, above the content it checks.

[Picture 30911 — an album record checked line by line against its DTD rules]

## Sub lesson 2 — The album DTD, line by line (doing)

Read the complete album example **line by line**:

```xml
<!DOCTYPE album [
  <!ELEMENT album (singer,name,release,language)>
  <!ELEMENT singer (#PCDATA)>
  <!ELEMENT name (#PCDATA)>
  <!ELEMENT release (#PCDATA)>
  <!ELEMENT language (#PCDATA)>
]>
```

- The **DOCTYPE names the root: album**.
- The album element **must contain singer, name, release and language — in that order**.
- Each of those four is declared as **#PCDATA** — text, with no further elements inside.

A matching document:

```xml
<album>
  <singer>Example Singer</singer>
  <name>Example Album</name>
  <release>2020</release>
  <language>Amharic</language>
</album>
```

Check it against the rulebook: root right, four parts present, order right, leaves holding text. **Valid.**

## Say it to your companion

Tell your companion what a DTD is for, then read the album DTD aloud line by line, saying what each line permits.

## Do It Yourself

1. Write an internal DTD for a simple record of your own: a root, two or three parts in order, leaves as #PCDATA.
2. Break one rule in the matching document, then find and name the broken rule.
3. Say in one sentence what 'valid' means for an XML document.
