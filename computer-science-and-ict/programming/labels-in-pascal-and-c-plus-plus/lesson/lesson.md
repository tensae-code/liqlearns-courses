# Labels in Pascal and C++

## Do it first

Every vocabulary chapter must account for the language's smallest citizens. The label is one: a mark placed on an instruction, existing for one purpose — to be jumped to.

## Sub lesson 1 — A label — a name stuck on an instruction

A **label** is a **mark attached to an instruction**, written before it and separated by a colon: `10: writeln(x);`. In Pascal, labels are **unsigned integer constants** (or identifiers where dialects allow) and must be **declared** in a `label` declaration before use; in C++, labels are **identifiers** needing no declaration. A label has no value and does no work: it is an address in the text, a place other instructions can name — built entirely for the goto instruction that §3.17 will judge.

[Picture — A label — a name stuck on an instruction]

## Sub lesson 2 — Why labels are taught — and rarely used

Labels belong to the vocabulary because the grammar includes them, but the course's posture is the profession's: **structured instructions (if, while, for, repeat) have made labels nearly unnecessary** — every honest loop and branch has its structured form, which reads in order. The labelled jump survives at the edges (leaving deep nests at once, machine-generated code). Learning labels is learning to *recognise* them — and to know why the programs in this course almost never wear one.

[Picture — Why labels are taught — and rarely used]

## Say it to your companion

Tell your companion, in your own words: A **label** is a **mark attached to an instruction**, written before it and separated by a colon: `10: writeln(x);`. In Pascal, labels are **unsigned integer constants** (or identifiers where dialects allow) and must be **declared** in a `label` declaration before use; in C++, labels are **identifiers** needing no declaration. A label has no value and does no work: it is an address in the text, a place other instructions can name — built entirely for the goto instruction that §3.17 will judge. Labels belong to the vocabulary because the grammar includes them, but the course's posture is the profession's: **structured instructions (if, while, for, repeat) have made labels nearly unnecessary** — every honest loop and branch has its structured form, which reads in order. The labelled jump survives at the edges (leaving deep nests at once, machine-generated code). Learning labels is learning to *recognise* them — and to know why the programs in this course almost never wear one. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A mark attached to an instruction — an address in the program text. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Before its instruction, separated by a colon — 10: writeln(x);. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Unsigned integer constants, declared in a label declaration. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Identifiers — no declaration needed. Do this with a real example of your own and write or say how you know it is right.
