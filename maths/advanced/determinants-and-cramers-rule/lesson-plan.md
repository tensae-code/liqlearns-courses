# Lesson plan — Determinants and Cramer's Rule

**Course:** Maths · **Stage:** Stage 12 — Advanced Mathematics · **Lesson:** Determinants and Cramer's Rule
**Place in the curriculum:** Level 93 of 136, in Stage 12 — Advanced Mathematics (maths/CURRICULUM.md).
**The one thing this lesson teaches:** determinants of order 2×2 and 3×3, and the three ways they solve linear systems — Cramer's rule, the inverse-matrix method AX = B ⇒ X = A⁻¹B, and the determinant tests for no solution and dependent systems — closing with matrices used for codes.
**This lesson's own level:** it stands on the matrices lesson — the learner can already add and multiply matrices and knows what a system of linear equations is. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the
exact places marked below, the lesson page carries an add-on — an
image, a GIF, a video, an audio. Every slot is written as **"a picture
of …" in words, plus one little line saying what the student does
with it**. The words carry the picture while the course is built and
while the AI learns from the books; on the website the real add-on is
dropped into that slot and the little explanation stays as the
student's guide. Images follow the picture rule (a real photograph,
or real art, with its source). GIFs come first where a thing must be
shown changing.

## Before this lesson
- Recommended first: the matrices lesson (a determinant belongs to a square matrix, and Cramer's rule divides one determinant by another), and solving simultaneous equations (Cramer's rule is a new way to do an old job). Recommended, never forced.
- A soft hint: if you know how to solve two equations in two unknowns by elimination, this course will be easier for you — you might try it first. Recommended, never forced.

## What the learner can do when it ends
1. Find a 2×2 determinant, the way Kuwait's Grade 10 Term 2 book teaches it inside identity and inverse matrices (Unit 7, Lesson 7-4, printed pp.74–78) and Egypt's Secondary 1 Term 2 book teaches determinants (Unit 1, Lesson 1-4, contents p.22).
2. Find a 3×3 determinant by Sarrus' rule and by cofactor expansion, the way Nicaragua's Grade 10 book teaches both (Sarrus' rule, printed pp.233–234; minors and cofactors, printed pp.227–244) and Cambodia's Grade 11 Basic book teaches determinants of order 3 (Chapter 4, Lesson 2, printed pp.130–138).
3. Find the area of a triangle from a determinant, the way Egypt's book teaches it (Lesson 1-4, contents p.22).
4. Solve two equations in two unknowns by Cramer's rule and by the inverse matrix, the way Kuwait's book teaches both in one lesson (Lesson 7-5, printed pp.79–82) and Egypt's book teaches them (Lesson 1-5, contents p.30).
5. Solve three equations in three unknowns by Cramer's rule, the way Cambodia's book works it in full (printed p.135: D = 12, D_x = 4, D_y = −20, D_z = 20) and Nicaragua's book works it (printed pp.235–238).
6. Read what D = 0 means — no solution when a numerator determinant is non-zero, a dependent system when the books show one — the way Cambodia's book works both cases (printed p.135).
7. Solve a system written AX = B as X = A⁻¹B, the way Laos's Grade 12 book states it (Chapter 3, Lesson 8, p.67; Lesson 10, p.96 — the same formula its cover previews).
8. Encode and decode a short message with a matrix and its inverse, the way Nicaragua's Grade 10 book closes the determinants unit (printed pp.243–244).

## What you need
Paper and a pencil. A 3×3 grid drawn big, for Sarrus' rule.

## The run of the lesson (in order)
1. **Do it first** — the learner solves x + y = 3 and x − y = 7 by elimination, then is shown the same answer falling out of three determinants (lesson/lesson.md).
2. **The explanation** — the 2×2 determinant; the 3×3 determinant by Sarrus and by cofactors; area from a determinant; Cramer's rule for two unknowns; the inverse-matrix method; Cramer's rule for three unknowns; the D = 0 cases; matrices for codes (lesson/lesson.md).
   - ADD GIF at the Sarrus part: a picture of a 3×3 grid with its first two columns copied again on the right, the three down-diagonals lighting up, then the three up-diagonals — the student follows which products are added and which are subtracted.
   - ADD IMAGE at the Cramer part: a picture of one system of equations beside three determinant boxes — the coefficient box in the middle, and the x-box and y-box with one column swapped for the answers — the student says which column is swapped in each box.
   - ADD GIF at the codes part: a picture of two letters turning into two numbers, being multiplied by a coding matrix into two new numbers, then multiplied by the inverse matrix back into the letters — the student follows the message out and back.
3. **Say it to your companion** — give your companion a 2×2 system and answer their questions in whole sentences (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — determinants and Cramer's rule in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — find determinants, solve systems two ways, and encode a two-letter message (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of Sarrus' rule with the copied columns and the six diagonals lighting in turn → the student follows the added and subtracted products.
- IMAGE — a picture of a system beside its three Cramer determinant boxes → the student says which column is swapped in each.
- GIF — a picture of letters becoming numbers, coded by a matrix and decoded by its inverse → the student follows the message out and back.
- VIDEO — the video-script filmed (made later) → the student works a determinant along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Gets the 2×2 sign wrong → a determinant is main diagonal minus other diagonal: ad − bc, in that order (Kuwait, Grade 10 Term 2, Lesson 7-4).
- Expands a 3×3 along a row and forgets the checkerboard signs → lay the + − + / − + − / + − + board over the grid first; Nicaragua's book builds the 3×3 from minors and cofactors exactly this way (printed pp.227–244).
- Divides by D without checking it → if D = 0 there is no Cramer quotient: look at the numerator determinants, as Cambodia's book does — a non-zero numerator means no solution (printed p.135).
- Confuses the inverse method with Cramer → they are two roads to the same answer: X = A⁻¹B uses the inverse once and answers every B; Cramer rebuilds a determinant per unknown (Laos, Grade 12, Lesson 10, p.96; Kuwait, Lesson 7-5).
- This lesson's next door: De Moivre's theorem (Level 94) — a change of topic, back to complex numbers in trigonometric form.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Egypt Secondary 1 Term 2, Unit 1; Cambodia Grade 11 Basic Chapter 4; Kuwait Grade 10 Term 2 Unit 7 — 2×2 only, as filed; Laos Grade 12 Chapter 3; Nicaragua Grade 10, determinants unit including the codes application on printed pp.243–244). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
