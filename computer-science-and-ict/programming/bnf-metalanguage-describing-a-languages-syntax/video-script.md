# Video script — BNF Metalanguage — Describing a Language's Syntax

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **metalanguage** is a language used to describe another language. **BNF (Backus–Naur Form)** is the standard metalanguage for syntax: it defines each construction of the language by a **production** — a name, the sign **::=** ('is defined as'), and its definition. The names being defined, written in **angle brackets** like <identifier>, are **nonterminals** — constructions that unfold further; the language's own symbols in a definition are **terminals** — they stand as themselves.
A definition may offer **alternatives**, separated by **|**: <digit> ::= 0 | 1 | … | 9. Reading BNF is unfolding: start from a nonterminal, replace it by one of its alternatives, and continue until only terminals remain — a legal text of the described language. <identifier> ::= <letter> | <identifier> <letter> | <identifier> <digit> unfolds letter by letter into names of any length: the production is **recursive**, and recursion here is what lets a finite grammar describe infinitely many texts.
