# BNF Metalanguage — Describing a Language's Syntax

## Do it first

Grade 10's programming becomes formal. Before the languages' own rules can be stated precisely, the book teaches the language for stating rules: BNF, the metalanguage in which Pascal's and C++'s grammars are written.

## Sub lesson 1 — A language about languages — the metalanguage

A **metalanguage** is a language used to describe another language. **BNF (Backus–Naur Form)** is the standard metalanguage for syntax: it defines each construction of the language by a **production** — a name, the sign **::=** ('is defined as'), and its definition. The names being defined, written in **angle brackets** like <identifier>, are **nonterminals** — constructions that unfold further; the language's own symbols in a definition are **terminals** — they stand as themselves.

[Picture — A language about languages — the metalanguage]

## Sub lesson 2 — Alternatives and repetition — reading a production

A definition may offer **alternatives**, separated by **|**: <digit> ::= 0 | 1 | … | 9. Reading BNF is unfolding: start from a nonterminal, replace it by one of its alternatives, and continue until only terminals remain — a legal text of the described language. <identifier> ::= <letter> | <identifier> <letter> | <identifier> <digit> unfolds letter by letter into names of any length: the production is **recursive**, and recursion here is what lets a finite grammar describe infinitely many texts.

[Picture — Alternatives and repetition — reading a production]

## Say it to your companion

Tell your companion, in your own words: A **metalanguage** is a language used to describe another language. **BNF (Backus–Naur Form)** is the standard metalanguage for syntax: it defines each construction of the language by a **production** — a name, the sign **::=** ('is defined as'), and its definition. The names being defined, written in **angle brackets** like <identifier>, are **nonterminals** — constructions that unfold further; the language's own symbols in a definition are **terminals** — they stand as themselves. A definition may offer **alternatives**, separated by **|**: <digit> ::= 0 | 1 | … | 9. Reading BNF is unfolding: start from a nonterminal, replace it by one of its alternatives, and continue until only terminals remain — a legal text of the described language. <identifier> ::= <letter> | <identifier> <letter> | <identifier> <digit> unfolds letter by letter into names of any length: the production is **recursive**, and recursion here is what lets a finite grammar describe infinitely many texts. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A language used to describe another language. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Backus–Naur Form — it describes a language's syntax. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 'Is defined as' — it joins a construction's name to its definition. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Constructions in angle brackets that unfold further, like <identifier>. Do this with a real example of your own and write or say how you know it is right.
