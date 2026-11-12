# What XML is used for

## Do it first

Describe a book you have read on a trip — or one you would take — using only labelled tags: the book, its title, its author, its type. Keep the tags nested, like boxes inside a box. This lesson shows that same record, and names the jobs XML is used for.

## Sub lesson 1 — The books example — a vacation book in tags

A pupil describing a vacation book does it with **nested custom tags** — an outer element holding an inner one, which holds the details:

```xml
<books>
  <book>
    <title>Vacation Stories</title>
    <author>Example Author</author>
    <type>story</type>
  </book>
</books>
```

Read the nesting: **books** holds **book**; **book** holds **title**, **author** and **type**. Nothing here says how the record should look on a screen — every tag says what its piece of data *is*. That is the shape XML is used in.

[Picture 30901 — a small nested book record beside a database with a "not suited here" sign]

## Sub lesson 2 — Two useful areas

Two useful areas are named.

**1. Structuring data for storage where a relational database is inappropriate.** That means **small quantities of data**, or **data lacking relational structure** — data that does not fall naturally into linked tables. In those cases programmers **prefer their own format**, and XML is that format.

**2. The presentation of web pages alongside other resources.** XML works together with other resources to present web pages — it supplies the structured data; the other resources do the presenting.

Hold the boundary: a large store with a clear relational shape belongs in a database (Unit 3's ground). XML's storage job is the other corner — small, or shapeless for tables.

## Say it to your companion

Tell your companion the two jobs XML is used for, using the book record as your example.

## Do It Yourself

1. Write a book record of your own: books, book, title, author, type.
2. Give one small collection from home that has no table shape and would suit XML storage.
3. Say, in one sentence, why a huge, neatly-related store belongs in a database instead.
