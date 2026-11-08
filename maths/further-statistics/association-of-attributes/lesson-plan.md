<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Association of Attributes

**Course:** Maths · **Unit:** Unit 16 — Further Statistics and Probability · **Lesson:** Association of Attributes
**Place in the curriculum:** Level 123 of 136, the seventh lesson of Unit 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** when the data are qualities, not measurements — literate or not, vaccinated or not — how to lay them in a 2×2 table, test whether the two attributes are independent, measure their association with Yule's Q, run the chi-square test of independence (with Yates' correction), and summarise a bigger table with the contingency coefficient.
**This lesson's own level:** it stands on Collecting and Showing Data (Unit 11) — tables of counts — and on Hypothesis Testing (Level 121, same unit) for the test's shape: a claim, a statistic, a decision. It needs nothing else.

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

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **Attributes and the 2×2 Table** — sort by two attributes in the (A)/(α), (B)/(β) notation, build the 2×2 table with its totals, and tell class frequencies from ultimate frequencies. (Was depth Level 1.)
2. **Independence and Yule's Q** — apply the independence criterion (AB) = (A)(B)/n, call an association positive, negative or complete, and compute and interpret Yule's Q. (Was depth Level 2.)
3. **The Chi-Square Test and the Contingency Coefficient** — build expected frequencies for an r×c table, run the chi-square test with Yates' correction where it applies, compute the contingency coefficient C, and state the recorded boundary — the source book teaches no goodness-of-fit test. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Collecting and Showing Data (Unit 11) — an attribute table is a table of counts, and its row and column totals run everything that follows. Recommended, never forced.
- Recommended first: Hypothesis Testing (Level 121, same unit) — the chi-square test of independence is a hypothesis test: independence is the claim being tested. Recommended, never forced.
- Recommended first: Correlation and Regression (Level 122, same unit) — the same "are these linked?" question, there for measurements, here for qualities. Recommended, never forced.

## What the learner can do when it ends
1. Sort a population by two attributes into the (A)/(α), (B)/(β) notation and build the 2×2 table, with class frequencies and ultimate frequencies kept apart (Pakistan Statistics Class 12, Ch. 15, pp.215–216).
2. Check a table for consistency, and state the independence criterion: A and B are independent exactly when (AB) = (A)(B)/n (Pakistan, Ch. 15, pp.217–219).
3. Say whether an association is positive, negative or complete, and measure it with Yule's coefficient Q = ((AB)(αβ) − (Aβ)(αB))/((AB)(αβ) + (Aβ)(αB)), knowing Q = ±1 is complete association and Q = 0 is independence (Pakistan, Ch. 15, pp.219–220).
4. Build a general r×c contingency table and its expected frequencies e_ij = (row total)(column total)/n — the descriptive ground Greece's book also teaches (Pakistan, Ch. 15, p.223; Greece W11, Units 2.5–2.6, pp.88–119).
5. Run the chi-square test of independence, χ² = ΣΣ(o − e)²/e with df = (r − 1)(c − 1), obeying the expected-frequency ≥ 5 rule with pooling where needed (Pakistan, Ch. 15, pp.224–232).
6. Apply Yates' correction in a 2×2 table — replace |o − e| by |o − e| − 0.5 before squaring — and say why a 2×2 table needs it (Pakistan, Ch. 15, pp.224–232).
7. Compute the coefficient of contingency C = √(χ²/(n + χ²)) and say what it adds beyond the test's yes/no (Pakistan, Ch. 15, p.226 as filed within pp.224–232).
8. State plainly what this lesson does **not** contain: Pakistan's book teaches **no chi-square goodness-of-fit test** — its χ² is for independence only — and never claim one for it (Pakistan, Ch. 15, as filed; the book's honest negatives).

## What you need
Paper and a pencil.
A calculator.
A chi-square table — Pakistan's book prints its χ² quantiles in its appendix tables (Table 11, printed pp.298–299 of the Class 12 book).

## The run of the lesson (in order)
1. **Do it first** — the learner sorts a small class of people by two yes/no qualities into four boxes, totals the rows and columns, and guesses whether the qualities travel together — before any notation is given (lesson/lesson.md).
2. **The explanation** — attributes and dichotomy; the 2×2 table and its notation; consistency; the independence criterion; positive, negative and complete association; Yule's Q; contingency tables; the chi-square test of independence with the ≥ 5 rule and Yates' correction; the contingency coefficient; and the recorded boundary — no goodness-of-fit test in the source book (lesson/lesson.md).
   - ADD IMAGE at the 2×2 part: a picture of a 2×2 table drawn as four boxes inside a bigger square split by the two attributes — the student points to the box that is (Aβ) and says who lives there.
   - ADD GIF at the independence part: a picture of the (AB) box swelling and shrinking while the row and column totals stay fixed — the student watches independence sit exactly at (A)(B)/n.
   - ADD IMAGE at the chi-square part: a picture of an observed table and its expected twin side by side, cell by cell — the student finds the cell where the two disagree most.
3. **Say it to your companion** — name the four boxes of a fresh example in the (A)/(α)/(B)/(β) language, and defend a Q value's sign and size in whole sentences (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — attributes, Q and the chi-square test in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — one full table worked end to end: independence check, Q, χ² with and without Yates' correction, and C (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a 2×2 table as four boxes inside a split square → the student names each box in the (A)/(α) notation.
- GIF — a picture of the (AB) box swelling and shrinking at fixed totals → the student spots the independence size.
- IMAGE — a picture of observed and expected tables side by side → the student finds the most-disagreeing cell.
- VIDEO — the video-script filmed (made later) → the student builds the table along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Mixes up class frequencies and ultimate frequencies → (A) counts everyone with A, including those also in B; (AB) is the ultimate box where the two meet. Pakistan opens the chapter on exactly this distinction (Ch. 15, pp.215–216).
- Tests independence by eye → there is a formula and it is exact: compare (AB) with (A)(B)/n. Equal means independent; (AB) above it leans positive, below it negative (pp.217–220).
- Forgets Yates in a 2×2 → a 2×2 table has df = 1, where the continuous χ² curve fits the discrete counts worst; subtract 0.5 from |o − e| in every cell first (pp.224–232).
- Uses the test when an expected frequency is tiny → the rule is expected ≥ 5; pool small rows or columns together before computing, or the statistic cannot be trusted (pp.224–232).
- Asks for the goodness-of-fit test → it is not in this lesson because it is not in the source: Pakistan's Ch. 15 uses χ² only for independence, and the filing records the goodness-of-fit test as absent. Say so plainly rather than borrowing it from elsewhere.
- Looks for a second full source → there is none: Greece's W11 teaches contingency tables descriptively only (Units 2.5–2.6), with no test and no Q. This lesson is honest about standing on one full source.
- This lesson's next door: Time Series (Level 124, same unit) — from "are these linked?" to "how does this change over time?"

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Statistics Class 12, Ch. 15 — the sole full source: attributes and the 2×2 table, the independence criterion, Yule's Q, the chi-square test of independence with the ≥ 5 rule and Yates' correction, and the contingency coefficient; Greece W11, Units 2.5–2.6 — contingency tables and comparing characteristics across categories, descriptive only, no inference of any kind as filed). One recorded boundary is part of the lesson itself: Pakistan's book teaches no chi-square goodness-of-fit test, and none is claimed anywhere in this lesson. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
