# Inclusion–Exclusion and Venn Counting — the lesson

Course: Maths · Stage: Stage 14 — Counting and Discrete Mathematics · Lesson: Inclusion–Exclusion and Venn Counting
Built from: Iran, Discrete Mathematics — Laos, Grade 10 — Nepal, Grade 8; Grade 9; Grade 10 — Sierra Leone, SSS1; SSS3 — Kazakhstan, Grade 5; Grade 9 — South Sudan, Secondary 2

## Do it first
In a class, 12 pupils play football and 9 play basketball. A
friend says: "So 21 pupils play a sport." Before any formula —
think. Can that be right if the class only has 25 pupils and some
pupils play neither sport? Where is the mistake?

The mistake: four pupils play **both**. They stand on both lists,
so adding the lists counts them twice. The true count of pupils
who play either sport is 12 + 9 − 4 = 17. You have just used
inclusion–exclusion. Now we build it properly.

## Then the explanation
**The Venn diagram and its regions.** Two overlapping circles
split the world into four regions: in A only, in B only, in both
(the overlap, A∩B), and in neither. Every counting question in
this lesson is a question about one of those regions, or a sum of
them. The working rule of Laos's Grade 10 book, whose survey
problems run through this whole lesson (Ch.II L5, pp.38–48), is:
fill the diagram from the middle out — overlap first, then the
"only" parts, then the outside.

**The two-set formula.** Counting A and counting B counts the
overlap twice. Take away one copy of it:

n(A∪B) = n(A) + n(B) − n(A∩B)

Laos's Grade 10 book states this formula inside its survey
problems (pp.38–48): for example, of 40 people surveyed about two
drinks, the in-either count is the two single counts added, minus
the both count. Kazakhstan's Grade 5 book meets the same overlap
idea early (§5.4), and its Grade 9 books state the formula in
their sets work; South Sudan's Secondary 2 book uses Venn
counting in its sets unit.

Tip — from us, not from the books. Fill the middle first, always. Almost every wrong Venn answer comes from writing a group total into a crescent that should hold only the "only" part.

**Only, both, neither.** From the regions come the three everyday
questions. "Only A" = n(A) − n(A∩B): the group total with the
overlap removed. "Neither" = the whole surveyed group minus
n(A∪B): everyone outside both circles. Nepal's books work this
survey shape at Grades 8 (§10.3), 9 and 10 — and one Nepal value
is taught corrected in this lesson: in the filed Nepal survey
example, the "neither" count is **18**. If your regions are right,
your four regions always add back to the whole group — use that
as your check.

**Three sets.** With three circles there are eight regions, and
the formula grows one more layer. Add the three singles; the pair
overlaps have now been counted twice, so subtract the three pair
overlaps; but the very middle — in all three — was added three
times and subtracted three times, so it has vanished, and must be
added back once:

n(A∪B∪C) = n(A) + n(B) + n(C)
− n(A∩B) − n(B∩C) − n(A∩C)
+ n(A∩B∩C)

Sierra Leone's SSS1 course teaches three sets region by region
(L64–70), and its SSS3 course states the formulae in this form
(L121). The add–subtract–add-back rhythm is the whole method:
each layer corrects the over-count of the layer before it.

**Counting onto functions (the closing part).** Inclusion–
exclusion also counts where no diagram is drawn. A function from
a 4-element set to a 3-element set is **onto** (surjective) if
every target is hit at least once. Iran's Discrete Mathematics
book counts onto functions by inclusion–exclusion (pp.73–78):
count all functions, 3⁴ = 81; take away those missing a named
target — there are 3 choices of the missed target and 2⁴ = 16
functions missing it, so 3 × 16 = 48; but functions missing two
named targets were taken away twice, so add them back: 3 choices
of the missed pair, 1⁴ = 1 function each, so +3. Total onto
functions: 81 − 48 + 3 = 36. Same rhythm as the three circles —
because it is the same principle.

## Say it to your companion
Say the method to your companion in one breath: "Add the groups,
take away the overlap once; with three groups, take away the
pairs and put the middle back." Then your companion gives you a
survey — two groups, an overlap, a total — and you answer three
questions aloud: how many in either, how many in only one named
group, how many in neither. Swap roles with three new numbers.

## Do It Yourself
1. n(A) = 30, n(B) = 25, n(A∩B) = 10. Find n(A∪B) and n(only A).
2. In a group of 50, 28 read the news online, 19 read a paper
   copy, 8 do both. How many read neither?
3. A class of 35: 20 take maths, 15 take physics, 9 take both.
   Draw the Venn diagram, fill it middle-first, and find how
   many take neither.
4. Three clubs in a school of 60 members surveyed: use the
   three-set formula with n(A) = 30, n(B) = 25, n(C) = 20,
   n(A∩B) = 10, n(B∩C) = 8, n(A∩C) = 7, n(A∩B∩C) = 4, and find
   how many are in at least one club.
5. In question 4, how many are in A only? (Take away both pair
   overlaps of A, then put the triple overlap back.)
6. How many functions from a 3-element set to a 2-element set
   are onto? Work it by inclusion–exclusion: 2³ − 2 × 1³.
7. Check question 6 by listing: the only non-onto functions are
   the two constant ones. Do the two methods agree?
