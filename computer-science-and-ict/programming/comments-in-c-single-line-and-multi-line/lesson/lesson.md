# Comments in C — Single-Line and Multi-Line

## Do it first

The compiler ignores them completely. Your future self, reading the program in six months, will bless or curse you by them. Comments are the part of a C program written entirely for people — and C gives them two shapes, one for the margin note and one for the whole paragraph.

## Sub lesson 1 — Two shapes — // and /* */

A **single-line comment** begins with **//** and runs to the line's end: `// read the marks` — the margin note, for one statement's reason. A **multi-line comment** opens with **/\*** and closes with **\*/** and may span many lines — the paragraph at a function's head, the licence, the explanation of a hard algorithm. Both are removed before compilation as surely as Python's # comments (the comments lessons of other languages agree on the purpose while differing in dress): the machine never sees them.

In your mind's eye: two shapes — // and /* */.

[Picture 46891 — two shapes — // and /* */]

## Sub lesson 2 — Writing comments that earn their place

A good comment says **why**, or what the code below must never break — never merely repeats the code in words ('add 1 to i' above `i = i + 1` is noise wearing a comment's coat). Comments also carry the working programmer's second tool: **commenting out** — wrapping a troublesome block in /* … */ to silence it while debugging, instead of deleting what may be innocent. And a rotten comment is worse than none: a note that lies about the code below it will be believed once, at the worst moment — so comments are maintained like code, changed when the code changes, or struck out with it.

In your mind's eye: writing comments that earn their place.

[Picture 46892 — writing comments that earn their place]

## Say it to your companion

Tell your companion, in your own words: A **single-line comment** begins with **//** and runs to the line's end: `// read the marks` — the margin note, for one statement's reason. A **multi-line comment** opens with **/\*** and closes with **\*/** and may span many lines — the paragraph at a function's head, the licence, the explanation of a hard algorithm. Both are removed before compilation as surely as Python's # comments (the comments lessons of other languages agree on the purpose while differing in dress): the machine never sees them. A good comment says **why**, or what the code below must never break — never merely repeats the code in words ('add 1 to i' above `i = i + 1` is noise wearing a comment's coat). Comments also carry the working programmer's second tool: **commenting out** — wrapping a troublesome block in /* … */ to silence it while debugging, instead of deleting what may be innocent. And a rotten comment is worse than none: a note that lies about the code below it will be believed once, at the worst moment — so comments are maintained like code, changed when the code changes, or struck out with it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: //. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: To the end of the line. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: /* and */. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — they are removed before compilation. Do this with a real example of your own and write or say how you know it is right.
