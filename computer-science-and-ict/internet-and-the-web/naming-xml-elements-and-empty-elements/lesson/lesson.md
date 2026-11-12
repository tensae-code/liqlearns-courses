# Naming XML elements — and empty elements

## Do it first

Six names, your judgement: `first_name`, `1stname`, `xmlData`, `my name`, `_mark`, `grade-level`. Which could be element names, and which could not? No rules have been given yet — go on feel. This lesson lists the rules that decide all six.

## Sub lesson 1 — Elements, empty elements, and what an element can contain (doing)

An **element is everything from its start tag to its end tag**. An element with **no content** is an **empty element**, and it can be written **either way**:

```xml
<marker></marker>
<marker/>
```

— an open-and-close pair, or a **single self-closing tag**. Both are the same empty element.

What can an element contain? **Text, attributes, other elements, or a mix.** The bookstore record shows the whole set in one place: **title, author, year and price hold text**; **bookstore and book hold elements**; and **book carries a category attribute**:

```xml
<bookstore>
  <book category="cooking">
    <title>Example Title</title>
    <author>Example Author</author>
    <year>2020</year>
    <price>100</price>
  </book>
</bookstore>
```

[Picture 30908 — a bookstore record opened up to show text-holding, element-holding and attribute-carrying parts]

## Sub lesson 2 — Naming rules (doing)

Element names follow rules — judge every name against this list:

- Names are **case sensitive**.
- A name **must start with a letter or underscore**.
- A name **cannot start with the letters XML**.
- A name **may contain letters, digits, hyphens, underscores and periods**.
- A name **cannot contain spaces**.
- **No words are reserved except XML.**

Now the six names from the start: `first_name` legal; `1stname` illegal (starts with a digit); `xmlData` illegal (starts with XML); `my name` illegal (a space); `_mark` legal (underscore start); `grade-level` legal (hyphen inside).

## Say it to your companion

Tell your companion the naming rules in order, then judge three new names your companion invents.

## Do It Yourself

1. Write one empty element as an open-and-close pair, then as a self-closing tag.
2. Judge these names: `Book`, `book_name`, `2books`, `xml`, `my-book`. Say the rule each verdict uses.
3. In the bookstore record, point to one element holding text, one holding elements, one carrying an attribute.
