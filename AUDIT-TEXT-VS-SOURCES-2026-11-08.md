# Audit — lesson text vs the lesson's own sources (2026-11-08)

Ordered after the Counting fault (see README, "Where provenance lives,
and the whole-arc rule", 2026-11-08): a lesson's text must not stop
short of what its own `lesson/sources.md` stocks.

**Scope:** the ORIGINAL lessons only — the 52 original Maths lessons
and the 51 original English lessons (including the 2 Pencil and Lines
lessons), identified as the lesson folders created on or before
2026-11-05, before the catch-up build and the country merges.
**Checked: 103 lessons.**

**Method:** for each lesson, the part descriptions in sources.md's
provenance table were compared against the lesson text two ways —
(1) range/arc check: the biggest range stocked in the rows vs the
biggest range the text actually teaches; (2) row-coverage check:
rows whose content words never appear anywhere in the lesson text.
Every lesson either check flagged, and every borderline lesson, was
then read by hand (text sections against the flagged rows) and
judged: a sources row about a topic that belongs to a NEIGHBOUR
lesson is recorded as covered-elsewhere, not as a fault. Lessons
under both thresholds were not re-read in full; their tables match
their texts on both checks.

## Headline results

- **Faults found: 11** (including Counting, fixed the same day).
- **Noted, not faults: 2** (mild range gap where the text teaches
  the general rule — see below).
- **Clean: 90.**

## The faults

### 1. maths — numbers/counting — FIXED 2026-11-08 (commit 9ea95e60)
The case that ordered this audit. Text stopped at an uncited
"Counting Past 100" while its sources stocked counting in hundreds
to 1,000, thousands to 10,000, groups of 10,000/100,000 to
1,000,000, and reading numbers to billions. Extended to 6 sub
lessons from the stocked rows; see the lesson's plan for the map.

### 2. english — word/numbers
Text stops at "Numbers by Tens to 100" (sub lessons: 1–10, 11–20,
tens to 100). Its own sources stock the climb past 100 and never
teach it:
- Jordan G5: "Big numbers as their own set: a hundred, five
  hundred, a thousand, five thousand, ten thousand, fifty
  thousand, a hundred thousand, a million" (Unit 3, pp.32–41).
- Iraq G4: the "Big Numbers" rhyme teaching 100–1000 and numbers
  to 3000 (Unit 2, printed pp.22–37).
- Greece G7 Workbook: big numbers matched whole — "Thirteen
  thousand, six hundred and seventeen" to 13,617 (Appendix Task
  46, printed p.138).
- Nepal G3: number words to three figures — 514 "five hundred and
  fourteen" through 799 (Unit 3, printed pp.18–24).
- Afghanistan G7: ordinal numbers listed whole, 1st to 100th
  (Unit 15, Lesson 3, printed pp.147–148) — no ordinal teaching
  appears in the text either.

### 3. english — phonics/two-letter-sounds
Text teaches ai oa ie ee or ng oo ch sh th qu ou oi ue er ar (and
names ck only in its "Built from" line). Stocked in its sources
but never taught in the text:
- **wh** (what, when, wheel, whistle, whale) — several books.
- **ph** (phone, shop/photo, graph — initial and final positions).
- **ck** as a taught pair (clock, black, backpack, truck).
- **kn** (silent k) and **wr** — "Digraph lessons worked from the
  block's own story or poem: kn · ph · wr · sh · th".
- **ir / ur** — the r-controlled ladder is stocked as a system
  (er · ir/ur/er · ar/al · or · le); the text carries er, ar, or
  only.
- Long-vowel spellings stocked as pairs: **ay** beside ai, **ea**
  beside ee, **igh / ie** for long i, **ow** beside oa for long o,
  **ue / ui** for long u (the text teaches ue inside the Unit 8
  set but not the stocked pairings as spelling patterns).

### 4. maths — numbers/factors-multiples-and-primes
Text teaches factors/multiples, prime/composite, HCF and LCM. The
word "divisibility" never appears in the text, while its sources
stock the divisibility tests as a named part of this topic:
- Ethiopia G6 ch. 1 "divisibility of whole numbers": rules for 2,
  3, 4, 5, 6, 8, 9, 10 (printed pp.1–28).
- South Sudan PB3 1.6 (tests for 2, 5, 10), PB5 1.2 (3, 4, 6, 9),
  PB6 1.2 (8 and 11).
- Yemen G4 Part 1 Unit 4: divisibility rules for 10, 5, 2 and 3
  (printed pp.104–108).
- Armenia Mathematics 5, Chapter 5 is itself named "Divisibility"
  (§5.1–§5.3, pp.114–121).
- Also stocked only: GCD by successive division (the Euclidean
  algorithm, worked scheme GCD(195, 104) = 13) — the text's HCF
  part does not carry this method.

### 5. english — conversation/how-old-are-you
Text teaches the exchange and the full "years old" form, from
Libya and Egypt only. Its sources stock two parts of the age
topic the text never teaches:
- **Birthdays:** "When is your birthday? — My birthday is on
  April 4th", with a class birthday role-play and the "How old
  are you?" song with birthday dates (March 21st, June 22nd,
  September 23rd, December 24th) — stocked from several books.
  (Days and months as words live in days-and-months next door;
  the birthday EXCHANGE is stocked here and taught nowhere in
  this lesson.)
- **Third person:** "How old is he / Raju? — He's nineteen", the
  age question turned to family members, with numbers to twenty
  in use.

### 6. english — conversation/how-are-you
Text teaches "How are you?" with three answers (very well / fine /
not very well) and asking it back. Its sources stock the feelings
deepening of the same exchange, never taught:
- "The feelings frame 'How are you feeling? I am feeling…' over
  seven feeling cards — HAPPY, EXCITED, SAD, ANGRY, SCARED,
  SURPRISED, SHY".
- "How do you feel?" and "What's wrong?", over a taught feelings
  set — angry, afraid, sad, worried, happy, ill.
- "Are you happy? Yes, I am. What's the matter? I'm thirsty…"
Covered-elsewhere (not faults): the same table's restaurant
ordering, making-plans, offers/promises with *will* and
apologising rows belong to their own later lessons.

### 7. english — conversation/whats-his-and-her-name
Text teaches the question and states the answer "is just the
name — not the full 'My name is' sentence". Its sources stock
the full-form answer across books, never taught:
- "The frame itself, in the opener's grammar: 'What's his/her
  name? / His/Her name's…'"
- "'What's her/his name?' with she's/he's answers, inside the
  first unit's naming work", and **he is / she is** description
  chains.
The text's name-only rule is one book's version (Libya G2);
the stocked full form (His/Her name's + name) is a part of this
topic the learner never meets here.

### 8–11. maths — the four operations stop at three digits
One family, same shape as Counting but milder: the METHOD is
taught whole; the size climb the books make is not carried.
- **addition**: sub lesson 3 is "Addition Three Digits and
  Checking" (Libya to 10,000 mentioned in text). Sources stock
  worked column addition to 100,000 (Indonesia G5 Ch. 1), to
  1,000,000 (Ethiopia G4 ch. 2; North Macedonia G5), "beyond
  1,000,000 with carrying across periods" (Rwanda P6 Unit 1) —
  carrying across periods is a taught point in the books that
  the text never names.
- **subtraction**: text caps at three digits / borrowing across
  zero; sources stock subtraction to 1,000,000 in five rows
  (incl. Ethiopia G4 ch. 2, printed pp.29–50).
- **multiplication**: sub lesson 3 is "Three Digits, Tens and
  Hundreds". Sources stock multiplying to 10,000 (Ethiopia G3
  ch. 5), "to 1,000,000 with 2-digit and larger multipliers"
  (Ethiopia G4 ch. 4), and "numbers beyond 1,000,000 by a
  multi-digit multiplier using partial products" (Rwanda P6).
- **division**: text stops at introductory columns and checking.
  Sources stock "long division of numbers beyond 1,000,000 by
  2- and 3-digit divisors" (Rwanda P6 Unit 1) and worked long
  divisions such as 564,923 ÷ 8 (Ethiopia G4 teacher guide).

## Noted — not counted as faults

- **maths — numbers/comparing-and-ordering**: worked examples
  reach 200,000; sources stock comparing to 1,000,000 and beyond
  (Indonesia G5; Rwanda P6). The text teaches the deciding rule
  ("The Biggest Place Decides") as a general rule with no size
  cap stated, and place-value carries numbers to 1,000,000 —
  recorded as a mild range gap, not a stop-short fault.
- **maths — numbers/place-value**: text works numbers to about
  902,415 against a stocked 1,000,000 — the full place system is
  taught; effectively complete.

## Covered-elsewhere — recorded so they are not re-flagged

- counting's sources stock permutations/combinations rows
  ("fundamental principle of counting") — that is
  counting-principles' topic, filed here by the merges; not a
  Counting part.
- hello-and-your-name's uncovered rows are the same exchange in
  other books' wording, plus "Let's…" suggestions and
  occupations rows — neighbour lessons' topics.
- answering-from-the-text and telling-a-story-back: their
  uncovered rows are individual stocked reading texts and
  stories (practice instances for the skill), not untaught
  topic parts.
- introducing-a-friend: uncovered rows are wording variants of
  the taught introductions plus family-presentation rows (the
  family lessons' topic).

## Note on the-big-reading

Its sources table (8 rows) matches its text. The known open
judgment calls about it (the bound-in readers from Pakistan,
Sudan, Kuwait and Syria, and three Malaysia tales held out under
its filed bar) live in the country filings, not in a text-vs-
sources gap, and are already with the user for ruling.
