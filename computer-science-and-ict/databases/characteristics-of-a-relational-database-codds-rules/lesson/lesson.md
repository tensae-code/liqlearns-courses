# Characteristics of a Relational Database — Codd's Rules

## Do it first

Many programs store data in tables; few deserve the title relational database management system. In 1985 Edgar Codd, who invented the relational idea, published the rules that separate the real thing from the imitation. This lesson holds systems up against his list.

## Sub lesson 1 — Codd's rules — the character tests

**Codd's rules** state what a true RDBMS guarantees. Among their heads: all information is held as **values in tables** — nothing hides in pointers the user cannot see; every value is reachable by **table name, key and column name**; **nulls** are handled systematically (the companion lesson); the catalogue describing the database is itself stored as tables and queryable with the same language; and one **comprehensive language** (SQL) does everything — defining, querying, changing. A system failing the heads may be useful, but it is not fully relational.

[Picture — Codd's rules — the character tests]

## Sub lesson 2 — The standard systems — and why the rules matter

The book closes with the **standard RDBMS list** — the systems the world's organisations actually run, from desktop-scale to the engines behind banks and governments, Bangladesh's own NID and passport databases among the companion lesson's examples. The rules matter beyond examinations because they are promises a buyer can test: data independent of the programs that use it, integrity the system itself enforces, and no back doors around the language. Choose a system by Codd's tests and the data will outlive every program written against it.

[Picture — The standard systems — and why the rules matter]

## Say it to your companion

Tell your companion, in your own words: **Codd's rules** state what a true RDBMS guarantees. Among their heads: all information is held as **values in tables** — nothing hides in pointers the user cannot see; every value is reachable by **table name, key and column name**; **nulls** are handled systematically (the companion lesson); the catalogue describing the database is itself stored as tables and queryable with the same language; and one **comprehensive language** (SQL) does everything — defining, querying, changing. A system failing the heads may be useful, but it is not fully relational. The book closes with the **standard RDBMS list** — the systems the world's organisations actually run, from desktop-scale to the engines behind banks and governments, Bangladesh's own NID and passport databases among the companion lesson's examples. The rules matter beyond examinations because they are promises a buyer can test: data independent of the programs that use it, integrity the system itself enforces, and no back doors around the language. Choose a system by Codd's tests and the data will outlive every program written against it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Edgar Codd, the relational idea's inventor. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: As values in tables — nothing hidden in pointers. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: By table name, key and column name. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Systematically — by rule, not by accident. Do this with a real example of your own and write or say how you know it is right.
