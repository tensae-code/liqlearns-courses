# Separators in Pascal and C++

## Do it first

A program text is a stream of characters until separators cut it into pieces the compiler can read. Grade 10's vocabulary study ends with the cutters themselves.

## Sub lesson 1 — Cutting the text — what separators are

**Separators** divide program text into its units: **blanks and line breaks** separate words; **commas** separate lists (parameters, values); **brackets** group; and the **semicolon** separates — in Pascal, instructions from each other; in C++, it **ends** each instruction as its terminator. The compiler reads separators before meaning: two programs with the same words and different separators are different programs, or one is no program at all. Whitespace beyond separation is free — indentation is written for people, paid for by nobody.

[Picture — Cutting the text — what separators are]

## Sub lesson 2 — One sign, two grammars — the semicolon's two jobs

The semicolon is the pair's emblematic difference. In **Pascal**, because it separates, the last instruction before **end** needs none — and an extra one only plants an empty instruction. In **C++**, because it terminates, a missing semicolon is an immediate error, and an extra one is an **empty statement** with the same traps (the stray `if (x>0);`). Reading separators is reading grammar: the same text, cut differently by the two languages, means differently — the vocabulary chapter's last proof that syntax is real.

[Picture — One sign, two grammars — the semicolon's two jobs]

## Say it to your companion

Tell your companion, in your own words: **Separators** divide program text into its units: **blanks and line breaks** separate words; **commas** separate lists (parameters, values); **brackets** group; and the **semicolon** separates — in Pascal, instructions from each other; in C++, it **ends** each instruction as its terminator. The compiler reads separators before meaning: two programs with the same words and different separators are different programs, or one is no program at all. Whitespace beyond separation is free — indentation is written for people, paid for by nobody. The semicolon is the pair's emblematic difference. In **Pascal**, because it separates, the last instruction before **end** needs none — and an extra one only plants an empty instruction. In **C++**, because it terminates, a missing semicolon is an immediate error, and an extra one is an **empty statement** with the same traps (the stray `if (x>0);`). Reading separators is reading grammar: the same text, cut differently by the two languages, means differently — the vocabulary chapter's last proof that syntax is real. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: They divide program text into its units — words, lists, groups, instructions. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Blanks and line breaks. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It separates instructions from each other. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It terminates — ends — each instruction. Do this with a real example of your own and write or say how you know it is right.
