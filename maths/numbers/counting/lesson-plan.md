<!--
TEMPLATE — units/sub-lessons restructure (pilot, 2026-11-08)

This lesson is the template for rolling the 2026-11-08 ruling
(README: "Units, Lessons and Sub Lessons") out to every other
lesson. A rollout agent repeats exactly these moves, without
re-deciding anything:

1. NAMES. Cut the lesson's parts at the topic's NATURAL JUMPS —
   the places where the content itself steps up (here: the count
   leaves single digits, then runs by tens, then passes 100).
   Name each sub lesson plainly for the thing it covers, in the
   shape "<Lesson thing> <the band/part>" (here: "Counting 1 to
   10"). Never name a sub lesson after a book's unit, a story, or
   a level number. The numbers in a name follow THIS lesson's
   real content — do not copy another lesson's bands.
2. THE LIST. lesson-plan.md carries a "## Sub lessons" section
   listing the sub lessons IN ORDER, each with its name and one
   line saying what it covers and which old depth layer it was.
   This list is what the app renders: the learner sees ALL of
   them from the start, locked ahead, opening in order (gate
   spec in README).
3. THE TEXT. lesson/lesson.md is sectioned under the sub-lesson
   names, in order, as "## Sub lesson N — <name>" headings over
   the part's existing text, moved VERBATIM — nothing dropped,
   nothing rewritten, every book+page citation stays inside its
   part. Lesson-level sections that are not a part (the opening
   "Do it first", the closing companion work and "Do It
   Yourself") stay OUTSIDE the sub-lesson sections, before the
   first and after the last, unchanged.
4. DEPTH. levels.md becomes the sub-lesson depth record: retitle
   it, give one section per sub lesson IN ORDER, and carry the
   old layer's pass mark / depth wording into its sub lesson's
   section. Record the mapping (old layer -> sub lesson) in the
   file's opening lines. If one old layer covers two sub
   lessons, split its pass mark at the same natural jump and say
   so. The old layer NUMBER survives only inside that mapping
   note — everywhere else the sub lesson is the unit of depth.
   (The learner skill number and the lesson's own level — the
   lesson=level design — are NOT touched by this restructure.)
5. QUESTIONS. Questions stay in questions/, one file per type.
   Every item's marker names its sub lesson: "(Sub lesson N)".
   Where a file already groups items by the old layers, map the
   groups onto the sub lessons and SAY SO in a header line at
   the top of the file, including any split (an old layer whose
   items divide between two sub lessons is split item by item,
   by what the item actually asks). Items never move between
   type files, and no item's wording or answer changes.
6. SOURCES. lesson/sources.md is not restructured: add nothing,
   remove nothing. If a sources file names its parts, align the
   part names to the sub-lesson names; if it does not (this
   pilot's does not — its provenance table rows are per-country
   content lines), leave it exactly as it is.
7. GROUPING LABEL. The lesson's header lines that name its
   course grouping follow the rename: "Stage" -> "Unit" (Maths)
   in the plan and the lesson text. Nothing else in the headers
   changes — the lesson's own level ("Place in the curriculum:
   Level 2") is the lesson=level design and stays.
8. WHEN PARTS DON'T CUT CLEANLY. If a part mixes two bands (an
   explanation that runs 1–20 in one breath), keep the text in
   the EARLIER sub lesson and note the overlap in the plan's
   Sub lessons list — do not split a paragraph mid-thought and
   do not invent a cut the content does not make. If a sub
   lesson ends up with no questions of its own in some type
   file, that is fine (a type file exists only for types the
   sub lesson has); but if a NON-LAST sub lesson has no
   questions in ANY file, say so plainly in the rollout report
   — the gate draws its prove-it set from that sub lesson.
9. GATE SANITY CHECK (run before committing): the Sub lessons
   list is complete and in order; every sub lesson except the
   last has questions of its own somewhere in questions/; the
   question items' markers cover every item exactly once; any
   hardness ranking the files carry is still present, untouched.
-->

# Lesson plan — Counting

**Course:** Maths · **Unit:** Unit 1 — Numbers · **Lesson:** Counting
**Place in the curriculum:** Level 2, the first lesson of Unit 1 — after Pencil and Lines (Level 1, the shared course) (maths/CURRICULUM.md).
**The one thing this lesson teaches:** counting — one number for each thing, in order, with the count told whole — from 1 to 10 up the whole climb the books teach: tens to 100, hundreds to 1,000, thousands to 10,000, and big numbers read to 1,000,000 and beyond.
**This lesson's own level:** it stands on Pencil and Lines (Level 1, the shared course) — the learner can already make marks and lines. It needs nothing else.

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

1. **Counting 1 to 10** — one number for each thing, touching
   each thing once, the count told whole. (Was depth Level 1.)
2. **Counting 11 to 20** — the line keeps going one by one;
   running it forward and back. (Was depth Level 2.)
3. **Counting by Tens to 100** — the tens line in jumps, and
   things grouped in tens: ten bundles of ten is one hundred.
   (Was the first half of depth Level 3.)
4. **Counting in Hundreds to 1,000** — the ones fill in between
   the tens past 100, then the hundreds line in jumps: ten
   hundreds is one thousand. (The old Sub lesson 4, "Counting
   Past 100" — the second half of depth Level 3 — folds into
   this one: its fill-in content opens the hundreds climb. The
   part was EXTENDED 2026-11-08 under the whole-arc rule: the
   old text stopped at "110, 120, 130 …" with no book cited,
   while the lesson's own sources stock the hundreds climb —
   Yemen Grade 2, Ethiopia Grade 2, Kuwait Grade 2.)
5. **Counting in Thousands to 10,000** — the thousands line in
   groups of 1,000, the fill-in between thousands, and reading
   and writing numbers to 100,000. (NEW 2026-11-08, whole-arc
   rule — stocked by Nicaragua Grade 3 counting in groups of
   1,000, Ethiopia Grade 3, Yemen Grade 3, Syria Grade 3;
   reading/writing to 100,000 from Indonesia Grade 5.)
6. **Counting Big Numbers to 1,000,000 and Beyond** — counting
   in groups of 10,000 and 100,000 to 1,000,000, reading and
   writing to a million, and reading numbers on to billions.
   (NEW 2026-11-08, whole-arc rule — stocked by Nicaragua
   Grade 4, Ethiopia Grade 4, Tanzania Standard Five, Indonesia
   Grade 5, and Yemen Grades 4–6 to billions.)

Gate pool: all questions of the sub lesson (no hardness ranking
is written in this lesson's question files).

## Before this lesson
- Recommended first: Pencil and Lines (Level 1, the shared course) — counting needs marks and fingers to count on. Recommended, never forced.
- Counting is the base of the whole course: every later lesson counts on it. Nothing here is adding or taking away — that is Unit 2's home.

## What the learner can do when it ends
1. Count 1–10 on real things, touching each thing once, the way Libya's Grade 1 book starts (numbers 1 to 10, p.21).
2. Count 11–20 and 21–100 in order, counting in tens as well as ones (Greece's Grade 1 numbers to 20; Libya's numbers to 100).
3. Count in tens to 100 and group things in tens (Sierra Leone's Primary lesson plans group in 10s with piles of counters).
4. Count anything in the room and report the count in a whole sentence: "There are 14 chairs."
5. Count in hundreds to 1,000 and say how many hundreds make a thousand (Yemen's Grade 2 "Numbers within 1000"; Ethiopia's Grade 2 counting by hundreds).
6. Count in thousands to 10,000, and read and write numbers to 100,000 (Nicaragua's Grade 3 groups of 1,000; Indonesia's Grade 5 reading and writing).
7. Count in groups of 10,000 and 100,000 to 1,000,000, and read big numbers in groups — ones, thousands, millions, billions (Ethiopia's Grade 4; Yemen's climb to billions).

## What you need
Things to count — fingers first, then stones, spoons, pencils, bottle tops.
Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — the learner counts their fingers, then the chairs in the room, in their own language; the lesson gives the count in numbers (lesson/lesson.md).
2. **The explanation** — 1–10 on real things; 11–20; the tens to 100; the hundreds to 1,000; the thousands to 10,000; big numbers to 1,000,000 and beyond (lesson/lesson.md).
   - ADD GIF at the 1–10 part: a picture of stones landing in a row, one per second, the figure growing with each landing — 1, 2, 3… — the student counts aloud with the landings.
   - ADD IMAGE under 11–20: a picture of a classroom number line, 1 to 20, with 11–20 standing big → the student reads the line forward, then back from 20.
   - ADD IMAGE in the tens part: a picture of ten bundles of ten sticks, each bundle tied, making 100 → the student counts the bundles: ten, twenty, thirty … one hundred.
   - ADD IMAGE in the hundreds part: a picture of ten flat squares of 100 dots standing beside one big cube of 1,000 → the student counts the flats: one hundred, two hundred … one thousand.
   - ADD IMAGE in the big-numbers part: a picture of ten packages, each marked 100,000, stacked into one block marked 1,000,000 (Tanzania's packages) → the student counts the packages to a million.
3. **Say it to your companion** — count real things for your companion and answer their How-many questions in whole sentences (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — the counting chant in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — count five things in your home, write each count, and count in tens to 100 (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- GIF — a picture of stones landing one by one, the figure growing with each → the student counts aloud with the landings.
- IMAGE — a picture of a 1–20 number line → the student reads it forward and back.
- IMAGE — a picture of ten bundles of ten sticks → the student counts the bundles to 100.
- IMAGE — a picture of ten flats of 100 beside a 1,000 cube → the student counts the flats to one thousand.
- IMAGE — a picture of ten 100,000 packages making 1,000,000 → the student counts the packages to a million.
- VIDEO — the video-script filmed (made later) → the student counts along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Counts the things but loses the line → Libya's and Sierra Leone's method: touch each thing as you count it, and move it aside; a thing touched is a thing counted once.
- Skips numbers in the teens → count the 1–20 line on the number line every day, forward and back, until the line is one piece.
- Counts past 100 and gets lost → count in tens first (10, 20, 30 …), then fill in the ones between the tens.
- Loses the place in a big number → read it in groups of three figures from the right: ones, thousands, millions (Indonesia's Grade 5 reading rule).
- This lesson's next door: Place-value (same unit) — the tens you counted become the tens place.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Libya Grade 1; Greece Grade 1 Teuxos A; Sierra Leone Primary lesson plans — teacher evidence; Ghana DL teacher guides — teacher evidence; Kazakhstan Grade 1; South Africa Grade 1 Workbook 1). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
