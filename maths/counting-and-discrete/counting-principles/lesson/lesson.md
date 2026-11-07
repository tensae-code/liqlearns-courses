# Counting Principles — the lesson

Course: Maths · Stage: Stage 14 — Counting and Discrete Mathematics · Lesson: Counting Principles
Built from: Pakistan, Class 11 Mathematics (PECTAA) — Kuwait, Grade 8 Term 2; Grade 10 Term 2; Grade 11 Term 2 — Yemen, Grade 12 Science; Grade 12 Literary — Vietnam, Grade 10 Volume 2 — Indonesia, Grade 12 — China, Grade 3 Volume 2 — Laos, Grade 11 — Armenia, Grade 12 teacher's guide (teacher evidence) — Mauritania, 3AS; 5AS-M; 5AS-D; 6AS-M; 6AS-C; 6AS-D; 6AS-LM; 7AS-LM — Iran, Mathematics (1) Grade 10; Discrete Mathematics Grade 12; Mathematics and Statistics (3) Grade 12 — Egypt, Pure Mathematics Grade 11 Term 2; General Mathematics Grade 11 Term 2 — Cambodia, Grade 10 Part 2; Grade 12 Probability booklet (PRIVATE) — Kazakhstan, Grade 9 Algebra (four books); Grade 6 option-tree books — Nicaragua, Grade 10; Grade 11 — Iraq, Grade 9; Grade 11 Scientific; Grade 12 Literary — Jordan, Grade 11 Term 1; Grade 8 Term 2 — Ethiopia, Grade 11 — South Sudan, Secondary 4

## Do it first
You have 3 shirts and 2 pairs of trousers. How many different
outfits can you wear? Do not reach for a rule. Draw it: from each
shirt, two trousers hang below it. Count the ends of your drawing:
6. Yemen's Grade 12 Literary book opens counting with exactly this
small count — 3 × 2 = 6 (Unit 1, pp.6–16). You have just used the
biggest idea of this lesson. Now we name it and grow it.

## Then the explanation
**The fundamental counting principle.** If one step can be done in
m ways and the next step in n ways, the two steps together can be
done in m × n ways — and the same for any number of steps.
Pakistan's Class 11 book states this principle and proves it with
tree diagrams: the branches are the choices, and the leaves of the
tree are the outcomes, so counting outcomes is counting leaves —
and leaves multiply (Unit 7, pp.123–132). Kuwait's Grade 8 Term 2
book starts the same climb from small choice situations
(L8-1, pp.180–191), and Vietnam's Grade 10 Volume 2 book builds its
counting chapter on the same two rules — multiply for steps done
one after another, add for cases done one instead of another
(Ch.VIII, pp.60, 66).

Tip — from us, not from the books. Steps in a row multiply; cases side by side add. If you can say "and then" between the choices, multiply. If you can say "or instead", add.

**Factorials.** Arranging n different things in a line: n choices
for the first place, n−1 for the next, and so on down to 1. By the
fundamental principle the total is n × (n−1) × … × 1, written n!
and read "n factorial". Pakistan's Class 11 book fixes the
notation, with 0! = 1 by definition (Unit 7, pp.123–132). So
4! = 24 — Yemen's Grade 12 Literary book checks the same fact as
P(4,4) = 24 (Unit 1, pp.6–16).

**Permutations — order matters.** A permutation is an arrangement:
who is first, who is second. Choosing and ordering r things from n
different things gives

ⁿPᵣ = n! / (n−r)!

Pakistan's Class 11 book builds ⁿPᵣ this way and then handles
arrangements with restrictions — a letter fixed first, vowels kept
together — by counting the restricted places first (Unit 7,
pp.123–132). Yemen's Grade 12 Science book runs the same
permutation course in its counting unit (Unit 2, pp.45–55), and
Indonesia's Grade 12 books give the full treatment in their
counting chapter (Bab 3, pp.89–148; Revisi Bab 3, pp.81–122).

**Repeats, and objects not all different.** Two different "repeat"
ideas live here, and the books keep them apart. First, repeats
allowed: a 3-digit code from digits 0–9 has 10 choices for every
place, so 10 × 10 × 10 = 1,000 codes — Kuwait's Grade 10 Term 2
book practises this case (10-4, pp.183–191), and Kuwait's Grade 11
Statistics Term 2 book returns to it (5-1, pp.52–62). Second,
objects not all different: arranging letters where one letter
appears twice over-counts by the swaps of those identical letters,
so you divide: arrangements of n things with repeats of p, q, …
identical things are n! / (p! q! …). Pakistan's Class 11 book
teaches this case in the same unit (pp.123–132).

**Circular permutations.** Around a round table, rotating everyone
one seat changes nothing — the neighbours are the same. So one
seat is fixed first, and the rest arrange in a line: (n−1)! ways.
If the circle can also be flipped over — a necklace, a garland —
each arrangement has been counted twice, giving (n−1)!/2.
Kuwait's Grade 11 Term 2 book teaches circular permutation as its
own lesson (11-1, pp.152–161); Pakistan's Class 11 book states
both forms (Unit 7, pp.123–132).

**Combinations — order does not matter.** A combination is a
choice: a team, a committee, a handful. Choosing r things from n,
where swapping two chosen things gives the same outcome, divides
the permutation count by the r! orders of the chosen things:

ⁿCᵣ = n! / (r! (n−r)!)

Pakistan's Class 11 book proves ⁿCᵣ from ⁿPᵣ exactly this way, adds
the mirror fact ⁿCᵣ = ⁿCₙ₋ᵣ — choosing the r you take is choosing
the n−r you leave — and works teams, committees, polygon diagonals,
passwords and song selection (Unit 7, pp.133–139). One warning from
that same book, taught corrected: its worked example on p.134
prints 36,960; the correct value is **6,160** — the printed answer
is a book error, and this lesson uses 6,160. Laos's Grade 11 book
carries the same combinations lesson in its counting chapter
(Ch.6 L27, p.169). Armenia's Grade 12 teacher's guide plans the
same ground — arrangements and permutations in Chapter 2 §2,
combinations in §3 — as teacher evidence: Armenia's Grade 12
student book is not held, so the guide shows what is taught, not
the pupil's own page.

**The same climb in more countries.** Mauritania returns to
counting again and again: a first counting-and-probability chapter
in 3AS (Ch.13, p.255), then a Dénombrement chapter in streamed
book after streamed book — 5AS-M (Ch.14, p.155), 5AS-D (Ch.11,
p.89), 6AS-M (Ch.12, p.171), 6AS-C (Ch.13, p.192), 6AS-D (Ch.VIII,
p.147, opening with set language and an urn-draw model), 6AS-LM
(Ch.4, p.67) and 7AS-LM (Ch.6, p.81). Iran teaches it three
times over. Its Grade 10 Mathematics (1) book gives the addition
and multiplication principles, then permutations
P(n,r) = n!/(n−r)! and combinations as r-subsets, keeping the two
apart with paired examples — choose 4 of 6 books against arrange
4 of 6 books (Ch.6, pp.118–140). Its Grade 12 Humanities book,
Mathematics and Statistics (3), starts again from everyday
choices: n! proved from the multiplication principle, combinations
introduced by listing the 3-subsets of {1, 2, 4, 6} — there are
4 = C(4,3) — and a 6-person volleyball team chosen from 9
(Ch.1 L1, pp.2–11). And its Grade 12 Discrete Mathematics book
pushes further than any other book here: permutations with
repetition, where identical objects divide the count, and
distributing identical objects — the non-negative solutions of
x₁ + x₂ + x₃ = 7 counted by a flower-selection model, the
stars-and-bars idea (Ch.3, pp.56–61).

Egypt runs the course in one Grade 11 Term 2 unit in both its
tracks: counting principle, factorial and permutations, then
combinations (Pure Mathematics, Unit 2, pp.49–63; the abridged
General Mathematics, Unit 2, lessons at pp.38, 41 and 46). Cambodia's Grade 10
Part 2 book does the same in Chapter 8: the multiplication
principle first (§1.1, p.62), then P(n,r) = n!/(n−r)! with
repetition and circular arrangements (§1.2, p.66), then
C(n,r) = n!/[r!(n−r)!] and its applications (pp.76–90). A second
Cambodian source, the Grade 12 Probability booklet — a PRIVATE
booklet by Khem Putthi, not a MoEYS textbook — works the same
ground as exam practice: counting principles (pp.17–20),
permutations including 8 students in a row, 8! = 40,320
(pp.22–27), and combinations, choosing 8 students from 20:
C(20,8) = 125,970 (p.28). One warning from that booklet, taught
corrected: its repeated-items formula on p.23 prints a factorial
sign after the denominator's closing bracket; the denominator is
the product of the factorials, n₁! × n₂! × … × n_p!, with no
extra factorial — and that corrected form is what this lesson
uses.

Kazakhstan's four Grade 9 algebra books each carry a full
combinatorics chapter: the sum and product rules first
(Yelemessov, Ch.2, pp.44–52; Shynybekov, Ch.2, pp.46–53;
Abylkasymova, Ch.II, pp.73–88; Soltan, Ch.II, pp.63–78, where the
product rule is derived from pair tables and the rules are also
reached through route graphs and family trees). Long before the
formulas, Kazakhstan's Grade 6 books count by drawing the whole
tree: the duty order of three pupils gives 6 variants, and the
segments joining 5 points give 4 + 3 + 2 + 1 = 10
(Aldamuratova, §8.3, p.141); numbers built from the digits
3, 5, 7, 9 and ending in 5 are listed from an option tree —
six numbers (Abylkasymova, §47, p.118). Nicaragua's Grade 10
book teaches the fundamental principle, permutations with and
without repetition and combinations with repetition
(Unit 1, pp.23–37); its Grade 11 book teaches it all again with
two pictures to keep: a book cover chosen as title colour ×
background colour, 2 × 4 = 8 combinations (p.118), and circular
permutation as a taught lesson — 4 people around a table sit in
(4−1)! = 6 ways, and 6 trees around a Managua roundabout in
5! = 120 ways (Unit 6, pp.118–129).

Iraq meets counting at three levels: permutations and
combinations with factorial, P(n,r) and C(n,r) in Grade 9
(6-3, p.147); a full Grade 11 Scientific chapter that runs from
3 × 4 × 6 = 72 through P(8,3) = 336 to C(7,3) = 35 and
C(10,3) = C(10,7) = 120 (Ch.8, pp.190–201); and a Grade 12
Literary chapter that opens with bicycles counted by the
fundamental principle — 5 types × 3 sizes × 6 = 90 — and suits
at 5 × 10 × 7 = 350 (Ch.1, pp.6–23). Jordan's Grade 11 Term 1
book places permutations and combinations inside its probability
unit (Unit 3 L1, p.120), while its Grade 8 Term 2 book starts
one step earlier, with counting outcomes and the sample space
of an experiment (Unit 9 L3, p.161). Ethiopia's Grade 11 book
gives the fundamental principle of counting, permutations and
combinations inside its Probability unit (Unit 8, pp.413–479).
South Sudan's Secondary 4 book states the permutation and
combination formulae, works examples, and then tests them with
30 multiple-choice questions (Unit 3, pp.56–59).

**Check by listing.** Before trusting a formula, the youngest book
in this lesson checks a small case by hand: China's Grade 3
Volume 2 book lists the matches when 4 teams each play each other
once and counts 6 (Unit 8, pp.101–105). And C(4,2) = 6. Yemen's
Grade 12 Literary book does the same check at its level:
C(4,2) = 6 (Unit 1, pp.6–16). Formula and list agree — that
agreement is how you know you chose the right count.

## Say it to your companion
Explain the swap test to your companion: "Swap two of the chosen
things. If the outcome changed, it was a permutation. If nothing
changed, it was a combination." Give one example of each from your
own life — a race order and a team picked. Then your companion
gives you three counting questions and you say, before computing,
which kind each one is and why.

## Do It Yourself
1. A menu offers 4 starters and 5 main dishes. How many
   starter-and-main pairs are there? Use the fundamental principle.
2. Compute 6! and 0! and say, in one sentence, why 0! = 1 is set
   by definition.
3. In how many ways can 5 different books stand on a shelf? Now
   in how many ways if one named book must stand first?
4. A lock has 4 rings, each with digits 0–9, repeats allowed. How
   many codes are there?
5. Six people sit around a round table. In how many ways can
   they sit? How many if the seating is a necklace pattern that
   can be flipped over?
6. From a class of 12, choose a team of 5. How many teams are
   there? Check your method on the small case first: C(4,2) by
   listing.
7. How many diagonals does an octagon have? (Pakistan's Class 11
   book counts polygon diagonals as a combination problem,
   pp.133–139 — count the segments between vertices, then take
   away the sides.)
