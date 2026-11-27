# Records in Pascal and C++

## Do it first

An array gathers manyness of one kind; real data is manyness of many kinds. A pupil is a name (string), a mark (integer) and a fee paid (boolean) at once. Grade 11's answer is the record.

## Sub lesson 1 — Fields — different types under one datum

A **record** is a structured type whose parts — its **fields** — may be of **different types**, each with its own **name**: Pascal's `type TPupil = record name: string; mark: integer; paid: boolean; end;`, C++'s `struct`. A field is reached through the record variable with a **dot**: `p.mark := 9;` — the dot reads 's: the mark of p. The whole record can also be **assigned at once** to another of the same type, copying every field — the structure acting simple for one act.

In your mind's eye: fields — different types under one datum.

[Picture 47563 — fields — different types under one datum]

## Sub lesson 2 — Records at work — tables of honest data

Records earn their keep where the world is tabular: a **class of pupils** is an array of records; a **library** is a file of them. The working patterns assemble the chapter's structures: loop the array, test a field, gather by another field — 'print the names of pupils with mark ≥ 9 and paid = true'. A record also models **one honest thing** — a date (day, month, year as three fields of fitting subranges), a point, a book — which is why the type definition reads like the thing's description: fields are the datum's anatomy, written down.

In your mind's eye: records at work — tables of honest data.

[Picture 47564 — records at work — tables of honest data]

## Say it to your companion

Tell your companion, in your own words: A **record** is a structured type whose parts — its **fields** — may be of **different types**, each with its own **name**: Pascal's `type TPupil = record name: string; mark: integer; paid: boolean; end;`, C++'s `struct`. A field is reached through the record variable with a **dot**: `p.mark := 9;` — the dot reads 's: the mark of p. The whole record can also be **assigned at once** to another of the same type, copying every field — the structure acting simple for one act. Records earn their keep where the world is tabular: a **class of pupils** is an array of records; a **library** is a file of them. The working patterns assemble the chapter's structures: loop the array, test a field, gather by another field — 'print the names of pupils with mark ≥ 9 and paid = true'. A record also models **one honest thing** — a date (day, month, year as three fields of fitting subranges), a point, a book — which is why the type definition reads like the thing's description: fields are the datum's anatomy, written down. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A structured type whose named fields may be of different types. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Through the record variable with a dot — p.mark. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: type TPupil = record name: string; mark: integer; paid: boolean; end;. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: struct. Do this with a real example of your own and write or say how you know it is right.
