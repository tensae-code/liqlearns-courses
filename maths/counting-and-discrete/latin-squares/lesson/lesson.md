# Latin squares — the lesson

Course: Maths · Unit: Unit 14 — Counting and Discrete Mathematics · Lesson: Latin squares
Built from: Iran, Discrete Mathematics, Grade 12 (Mathematical Sciences branch) — the sole source for this lesson, as filed

## Do it first
Take a 3×3 grid. Fill it with the letters A, B and C so that every row contains each letter exactly once, and every column contains each letter exactly once. It can be done — probably in more than one way. What you have built is a Latin square. This whole short lesson comes from one place: the long Latin-squares block in Iran's Grade 12 Discrete Mathematics book (pp.62–71), inside its combinatorics chapter — the book's most distinctive content, as filed. Nothing here is borrowed from any other country's book.

## Then the explanation

## Sub lesson 1 — The Rule and Building a Latin Square

**The definition.** A **Latin square of order n** is an n×n grid filled with n symbols so that each symbol appears **exactly once in every row and exactly once in every column** (Iran, pp.62–71). The symbols can be letters, numbers, colours — anything. The rule is only about positions: no repeats along a row, no repeats down a column.

**Building one: the shift method.** Write the symbols in order as the first row. For each next row, shift the row above by one step (the symbol that falls off the end comes back at the start). For order 4, with symbols 1, 2, 3, 4:

1 2 3 4
2 3 4 1
3 4 1 2
4 1 2 3

Every column also gets each symbol once — the shifting guarantees it. Iran's book builds its squares and then varies them (pp.62–71).

## Sub lesson 2 — Permuting Symbols, Rows and Columns

**Permuting the symbols.** If you rename the symbols everywhere — swap A and C, say — the result is still a Latin square: the once-in-each-row-and-column rule does not care what the symbols are called. Swapping two whole rows, or two whole columns, also keeps the rule true. Iran's book uses these moves — permuting symbols, rows and columns — to pass from one Latin square to others (pp.62–71).

Tip — from us, not from the books. When you check a square, check it in a fixed order: rows top to bottom, then columns left to right, ticking the symbols off. A fixed order is what stops you checking the same row twice and a column never.

## Sub lesson 3 — Orthogonal Latin Squares and Scheduling

**Orthogonal Latin squares.** Take two Latin squares of the same order, in different symbol sets, and lay one on top of the other. Each cell now holds a **pair**. If all n² pairs are different — every possible pair appearing exactly once — the two squares are **orthogonal** (Iran, pp.62–71). Checking orthogonality is mechanical: write out all the pairs and look for a repeat; one repeated pair settles it — not orthogonal. Iran's book checks orthogonality this way and constructs a pair of orthogonal Latin squares of order 5 (pp.62–71).

**What they are for: scheduling.** Iran's application is work scheduling (pp.62–71): suppose workers must rotate through tasks and partners so that every worker meets every partner and every task fairly. An orthogonal pair hands you the rota: rows and columns of the two squares carry the two things being paired, and because every pair occurs exactly once, everyone gets every combination exactly once — no repeats, no one missed out.

**A reading note.** Iran closes the block with a reading note on Euler's 1782 conjecture about orders n = 4k + 2 (6, 10, 14, …): Euler guessed that no pair of orthogonal Latin squares exists for such orders (pp.62–71). It is filed as a reading note, and this lesson keeps it as one.

## Say it to your companion
Say the rule whole: "A Latin square has each symbol exactly once in every row and exactly once in every column." Then show your companion a grid with one column broken and ask them to find the break. Swap: they explain how to test two squares for orthogonality, and you check them.

## Do It Yourself
1. Build a Latin square of order 3 by the shift method, then build a different one by swapping two rows of yours (Iran, pp.62–71).
2. Build a Latin square of order 5 by the shift method (Iran, pp.62–71).
3. Rename the symbols of your order-3 square by A→2, B→3, C→1 and check the rule still holds (Iran, pp.62–71).
4. Lay the two order-3 squares from question 1 on top of each other. List the 9 pairs. Are the squares orthogonal? Say which pair repeats, if one does (Iran, pp.62–71).
5. Explain, in three sentences, how an orthogonal pair would schedule 5 workers through 5 tasks so every pairing happens once (Iran, pp.62–71).
