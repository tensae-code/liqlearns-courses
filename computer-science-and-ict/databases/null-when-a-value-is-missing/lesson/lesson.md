# Null — When a Value Is Missing

## Do it first

A form has a blank: the student has no phone. The database must store that blank honestly. Type 0 and you have invented a phone number that rings nobody; type a space and you have invented a name of nothing. Databases keep a special marker for the honest blank — and this lesson is about it.

## Sub lesson 1 — Null — missing, not zero

**Null** means **no value is stored** — the value is unknown, or the field does not apply to this record. Null is not **zero** (zero is a real amount) and not an **empty string** (that is a real, if short, text): a salary of 0 says the person earns nothing; a salary of null says we do not know, or the question does not arise. Queries must respect the difference: counting records with a value skips the nulls, and a comparison with null never comes out true — unknown compared to anything is still unknown.

[Picture — Null — missing, not zero]

## Sub lesson 2 — The primary key is never null

One field may never hold the blank: the **primary key**. The key's whole job is to identify the record — the National ID of the companion lesson — and a record whose identifier is missing cannot be found, joined or told apart from another blank. So the DBMS enforces **entity integrity**: every primary key value exists and is unique. When you design a table, you decide field by field which may be null — a phone may be missing; an identity may not — and that decision is part of the table's honesty about the world.

[Picture — The primary key is never null]

## Say it to your companion

Tell your companion, in your own words: **Null** means **no value is stored** — the value is unknown, or the field does not apply to this record. Null is not **zero** (zero is a real amount) and not an **empty string** (that is a real, if short, text): a salary of 0 says the person earns nothing; a salary of null says we do not know, or the question does not arise. Queries must respect the difference: counting records with a value skips the nulls, and a comparison with null never comes out true — unknown compared to anything is still unknown. One field may never hold the blank: the **primary key**. The key's whole job is to identify the record — the National ID of the companion lesson — and a record whose identifier is missing cannot be found, joined or told apart from another blank. So the DBMS enforces **entity integrity**: every primary key value exists and is unique. When you design a table, you decide field by field which may be null — a phone may be missing; an identity may not — and that decision is part of the table's honesty about the world. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: No value is stored — unknown, or not applicable. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: No — zero is a real amount. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: No — an empty string is a real text. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: We do not know, or the question does not arise. Do this with a real example of your own and write or say how you know it is right.
