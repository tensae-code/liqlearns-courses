# Mathematical investigations — the lesson

Course: Maths · Stage: Stage 14 — Counting and Discrete Mathematics · Lesson: Mathematical investigations
Built from: China, Grade 5, second volume — China, Grade 6, second volume — the sole source country for this lesson, as filed

## Do it first
Here are 9 coins. One is a fake — it is a little lighter than the others, but they all look the same. You have a balance: two pans, no weights, no numbers — it only tips or stays level. Find the fake in as few weighings as you can. Most people start by splitting 4 and 4 — and need 3 weighings. China's Grade 5 book (second volume, Maths corner — Finding the defective product, p.111) knows a better way, and it is the first investigation of this lesson. Every part of this lesson comes from China's primary books, as filed: investigations are where those books teach you to make a strategy, not just an answer.

## Then the explanation
**The balance search: split in THREE.** Put 3 coins on the left pan, 3 on the right, and leave 3 aside. If a pan rises, the fake is in that light pile of 3. If the balance stays level, the fake is in the pile aside. Either way, ONE weighing cuts 9 suspects down to 3. Repeat on the pile of 3 — 1 against 1, 1 aside — and the second weighing names the fake. **Two weighings find one lighter product among 9.** The method works because a balance has three outcomes, so the suspects should be split into three groups, not two. China's book builds the guarantee table (p.111): the most products one search can handle in k weighings is 3ᵏ, so the guaranteed numbers are — **2–3 products: 1 weighing; 4–9: 2 weighings; 10–27: 3 weighings; 28–81: 4 weighings; 82–243: 5 weighings**. Read it both ways: 50 products need 4 weighings (27 is too few for 3), and 3 weighings can guarantee success up to 27 products.

**The phone-call tree: doubling.** China's Grade 5 book's Making phone calls lesson (p.102) asks for the fastest way to notify a whole team: one person is told first; each minute, everyone who already knows calls one person who does not. The numbers who know grow: after 1 minute, 2; after 2 minutes, 4; then 8, 16, 32… **After n minutes, 2ⁿ people know.** Drawn as a tree, each knower branches into a new knower — the tree doubles at every level. The investigation skill is the same as the balance's: draw the small cases, tabulate them, and let the pattern (here ×2, there ×3) state the rule.

Tip — from us, not from the books. In every investigation here, the winning move is the same: shrink the problem until it is tiny, solve the tiny ones in a row, and write the answers in a table. The pattern in the table IS the solution to the big problem.

**Painted cubes.** China's Grade 5 Exploring figures activity (p.44) paints a big cube and cuts it into small cubes, then counts by how many faces are painted. For a 3×3×3 cube (27 small cubes): the **8 corner** cubes have **3 painted faces**; the **12 edge** cubes (not corners) have **2**; the **6 face-middle** cubes have **1**; and the **1 centre** cube has **0** — the paint never reached it. The counts are found by WHERE a small cube sat, not by painting and pulling apart every time: corners, edges, face middles, inside. The same homes give the 4×4×4 counts: 8 corners with 3 faces, 24 edge cubes with 2, 24 face middles with 1, and 8 inside cubes with 0.

**Counting segments.** Put n points on a line. How many segments do they determine? China's Grade 6 book returns to this in its general review's mathematical-thinking part (second volume, pp.100–104). Fix the points one at a time: from the first point, n − 1 segments run to the others; from the second, n − 2 NEW segments; and so on down to 1. Total: **1 + 2 + … + (n − 1) = n(n − 1)/2 segments**. Check the ladder: 2 points → 1; 3 → 3; 4 → 6; 5 → 10; 6 → 15. The review sets the same counting beside logic tables, substitution puzzles and a short proof — investigations as a habit, not a chapter.

## Say it to your companion
Explain: "A balance has three outcomes, so split in three — that is why 2 weighings search 9 products." Your companion explains the phone tree back to you: why it is 2ⁿ and not 2n after n minutes. Then swap roles for the painted cube: one of you names a small cube's home — corner, edge, face middle, centre — the other says its painted-face count.

## Do It Yourself
1. Among 27 identical bottles, one is lighter. Show the three weighings that guarantee finding it (China, Grade 5, p.111).
2. Use the guarantee table: what is the smallest number of weighings that guarantees finding one lighter fake among 60 coins? Among 200? (China, Grade 5, p.111.)
3. A phone tree starts with 1 person told. How many know after 6 minutes? After how many minutes do at least 500 people know? (China, Grade 5, p.102.)
4. A 5×5×5 painted cube is cut up. Count the small cubes with 3, 2, 1 and 0 painted faces, by their homes (China, Grade 5, p.44).
5. How many segments are determined by 10 points on a line? By 20? (China, Grade 6, pp.100–104.)
