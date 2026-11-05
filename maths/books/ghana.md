# Ghana — Mathematics

**Set, reconciled: 30 record rows → 15 distinct files → 11 distinct works.**
The record is textbooks.tsv alone (the download list is SHS-portal focused
and holds no DL/JICA primary-maths rows; it neither duplicates nor
contradicts the 30 rows). All 30 rows were grabbed from the secured
GitHub library and verified (downloaded bytes match GitHub's own size
for each exact path; every file opens as a PDF; page counts counted
with PyMuPDF): 0 failed grabs, 0 owed, 0 phantom rows, 0 dead links.
The two collapses: (1) 15 rows are byte-identical (SHA-256 verified)
re-filings of the same file under another grade in its span, so 30 rows
= 15 distinct files; (2) the six DL teacher-guide files are sliding
windows of two guides (see correction 2 below), so 15 distinct files =
11 distinct works.

**Proved kinds (from each file's own cover + title page, never from
filenames):** 3 NaCCA curricula, 10 teacher files (6 DL window files =
2 guides + 4 JICA manuals), 2 student workbooks (task sheets only).
**No pupil textbook exists in this set at all.** By row: 6 curriculum
rows, 19 teacher rows, 5 workbook rows. Language as printed: English
throughout. **No real ISBN anywhere in the set** — DL guides and
workbooks print only a placeholder (XXX-XXXX-XXXX-X-X); JICA B5/B6
print placeholder XXXX; the curricula and JICA B3/B4 print no ISBN.

**Grades covered:** Lower Primary Basic 1–3, Upper Primary Basic 4–6,
and a JHS curriculum spanning Basic 7–9. **Distinct-file pages: 2,541**
(Band A 794 + Band B 1,488 + Band C 259).

**Citation checks (checker ≠ reader, all three bands): 295 anchors —
241 passed, 54 corrected in place, 0 not found.** Band A: 117
(105/12/0). Band B: 158 (123/35/0). Band C: 20 (13/7/0). Check blocks
are appended to each band section below.

**What this set is, in one line:** teacher-facing material plus two
task-sheet workbooks and three curriculum maps — there is nothing here
a learner opens and learns from directly. The DL (Differentiated
Learning) guides teach Number only; full four-strand coverage rests
entirely on the JICA teacher manuals, which are teacher board scripts,
not pupil books.

**Gaps proven from the books:**
- No pupil textbook for any grade, and no JHS teacher guide, workbook,
  or pupil textbook for any JHS grade (Grade 7 holds only the B7–B9
  curriculum).
- No Grade 2 file anywhere in the set (the shared Basic 1–3 curriculum
  and guides cover Basic 2 in principle only).
- No JICA manual for Basic 1 or Basic 2 (the series in hand starts
  at B3).
- DL workbook levels missing: Lower Levels 1 and 3, Upper Levels 2
  and 3 — only Lower Level 2 and Upper Level 1 are held, and each held
  workbook covers three modules, not one (see correction 3).
- DL material teaches Number only — no fractions, no money as a taught
  topic, no algebra/patterns, no geometry, no standard measurement,
  no data (money appears only inside workbook word-problem stories;
  the only measurement is non-standard estimation).
- DL guides never assign modules to grades — modules are ability
  levels, not B4/B5/B6 splits; the guides' own foreword targets Basic
  2–6 strugglers against covers saying Basic 1–3 / Upper Primary.
- JICA ceilings: B3 stops at nothing above 10,000, fractions only to
  comparing/ordering and fractions of quantities, no decimals, no
  division with remainders; B4 has no ratio, probability, angle,
  volume, or integers block; B6 has no percentage block and no
  perimeter/area/volume or angle-types block (those are B5 topics).

**Record corrections (load-bearing; full lists in the band sections):**
1. Three rows recorded as `teacher` are **curricula, not teacher
   guides**: the Basic 1–3 curriculum (95 pp., Sept 2019), the Basic
   4–6 curriculum (182 pp., Sept 2019), and the JHS CCP curriculum
   (259 pp., Sept 2020). Filed below as record-only sections — their
   content is NOT filed as taught lessons.
2. **The DL files are NOT "Module 1", "Module 2", "Module 3"
   respectively.** Each is a three-module sliding window of one guide:
   Lower file 1 = Modules 1–3, file 2 = Modules 2–4, file 3 =
   Modules 3–5; Upper Level 1 = Modules 1–3, Level 2 = Modules 2–4,
   Level 3 = Modules 3–5. Distinct DL content per guide = Modules 1–5
   (80 lessons), not 144. Repeated modules were compared lesson by
   lesson and are identical apart from printed pagination.
3. **The workbooks are NOT one module each.** Lower Level 2 holds
   Modules 2, 3 AND 4 (24 lessons); Upper Level 1 holds Modules 1, 2
   AND 3 (24 lessons) — each proved by its own contents page and
   divider pages. Both workbooks are image-only (one raster image per
   body page, no text layer) and were read as page pictures.
4. **JICA B6's contents page is a copy of B5's** and does not map B6:
   actual starts are Fractions L42 (not L43 — the brief's L43 claim was
   disproved against the book: L41 is "Multiply integers", L42 is
   "Make the denominators the same"), Ratios and Proportion L57–70,
   Data L99, Probability L109.
5. **Wrong worked answers in the books — never carry into lessons
   uncorrected:** Lower workbook printed p. 27 says "So, 15 − 3 = 18"
   (correct: 12, as its own chart shows 1 ten 2 ones; the chart is also
   mislabelled "Addition chart"); Upper workbook Module 2 Lesson 8
   chain "17 − 6 = 6" (should be 12 − 6 = 6) and Module 3 Lesson 7
   summary "384 x 4 = 1532" (the lattice is 383); JICA B5 Lesson 79
   prints "−3 + 4 = −1" (correct value 1).
6. CURR-B13's scope table omits Money while its grade sections carry
   nine sub-strands including Money (B1.1.4, B2.1.4, B3.1.4).
7. CURR-JHS's own summary Table 3 (PDF p. 30) undercounts its standards
   (B7 19 / B8 18 / B9 17) against its section tables (B7 21 / B8 18 /
   B9 19); the filing follows the section tables. One of the four
   extra standards, B7.1.1.2, is a full header with exemplars but
   carries no numbered indicator code.
8. DL Modules 4–5 carry "Upper Primary" running heads inside Lower
   Primary covers (kept in Band A where the files sit, flagged wherever
   it matters); Module 5 reaches 3-digit numbers and 2-digit × 1-digit
   multiplication.
9. JICA B4's file version lacks the copyright/contents pages B5/B6
   carry; JICA B3's file version lacks the copyright page.

**Owed / future hunt (not content gaps in what is held):** DL workbook
Lower Levels 1 and 3, Upper Levels 2 and 3; any JICA manual for Basic 1
or 2 (if they exist); any JHS pupil textbook, teacher guide, or
workbook; any Grade 2 file.


## Band A — Lower Primary, Basic 1–3
Country: Ghana. Subject: Mathematics. Band span: Basic 1–3 (Lower Primary).
Language as printed throughout: English. All filing below is in English.
Reading method: every distinct file read in full, page by page. Text-layer files
were read as extracted text, checked against page images where layout was
ambiguous; the workbook, whose body pages carry no text layer, was read as
page pictures (all 68 PDF pages rendered and viewed).

## Band inventory

11 record rows, 6 distinct files. Page totals below are PDF pages.

| Work ID | File (as grabbed) | PDF pp. | Rows it covers |
|---|---|---|---|
| CURR-B13 | grade1_full-year.pdf | 95 | Grade 1 full-year; Grade 3 full-year (byte-identical duplicate row) |
| DL-TG-LOWER (file 1) | grade1_teacher-guide_level-1.pdf | 166 | Grade 1 teacher-guide level-1; Grade 3 teacher-guide level-1 (duplicate row) |
| DL-TG-LOWER (file 2) | grade1_teacher-guide_level-2.pdf | 166 | Grade 1 teacher-guide level-2; Grade 3 teacher-guide level-2 (duplicate row) |
| DL-TG-LOWER (file 3) | grade1_teacher-guide_level-3.pdf | 165 | Grade 1 teacher-guide level-3; Grade 3 teacher-guide level-3 (duplicate row) |
| DL-WB-LOWER-L2 | grade1_student-workbook.pdf | 68 | Grade 1 student-workbook; Grade 3 student-workbook (duplicate row) |
| JICA-B3 | grade3_teacher-manual.pdf | 134 | Grade 3 teacher-manual only |

Total distinct-file pages read: 794 (95 + 166 + 166 + 165 + 68 + 134).
No Grade 2 file exists anywhere in the set: no row is filed under Grade 2,
although the shared Basic 1–3 curriculum and guides cover Basic 2 in
principle. The JICA series in this set starts at Basic 3: there is no JICA
manual for Basic 1 or Basic 2 here.

## Record corrections found while reading

1. **The three DL teacher-guide files are NOT "Module 1", "Module 2" and
   "Module 3" respectively.** Each file is a three-module sliding window of
   one Differentiated Learning (DL) guide, and the windows overlap:
   - file "level-1" (166 pp.): Modules 1, 2, 3 — 48 lessons;
   - file "level-2" (166 pp.): Modules 2, 3, 4 — 48 lessons;
   - file "level-3" (165 pp.): Modules 3, 4, 5 — 48 lessons.
   Each module holds 8 weeks × 2 lessons = 16 lessons. The repeated modules
   were compared lesson by lesson across files: the teaching text is the
   same, differing only in printed pagination (and two extraction artefacts
   where a stray page number lands mid-line). Distinct DL lesson content
   is therefore Modules 1–5 = 80 lessons, not 3 × 48 = 144.
2. **The workbook is NOT "Module 2 only".** The Level 2 learner's workbook
   (68 pp.) contains Modules 2, 3 and 4 of the DL sequence, 8 lessons each
   = 24 lessons (printed pp. 6–68). Its own table of contents lists all
   three modules. Any record describing it as Module 2 only understates it
   by two modules.
3. **Modules 4 and 5 of the DL guide, as printed in files "level-2" and
   "level-3", carry "Upper Primary" running heads** on their lesson pages,
   although both files' covers say Lower Primary, Basic 1–3, and their
   tables of contents present Modules 4 and 5 as continuations of the same
   guide. Module 4–5 lessons mostly run longer than Modules 1–3, but not
   uniformly: Module 4 is 35–40 minutes except Week 1 Lesson 1
   (25 minutes), and Module 5 mixes 20-minute (Week 1, both lessons),
   25-minute (Week 2 Lesson 2, Week 3, Week 4 Lesson 1, Week 6 Lesson 1)
   and 35–40-minute main activities. This reads as Upper Primary guide
   material bound into the Lower Primary files (or a shared cross-phase
   guide); the filing below keeps Modules 4–5 in Band A because that is
   where the files sit, but flags the header mismatch wherever it matters.
   Module 5 reaches 3-digit numbers and 2-digit × 1-digit multiplication,
   which is Upper Primary ground by the curriculum's own progression.
4. **The curriculum rows are not teacher guides.** The "full-year" files
   filed under Grades 1 and 3 are the NaCCA curriculum document itself
   (see the record-only section). They contain standards, indicators and
   teaching exemplars, but no pupil lessons and no exercises.
5. **No pupil textbook (taught lessons for learners) exists anywhere in
   Band A.** The only learner-facing file is the DL workbook, which is
   task sheets only: it teaches nothing by exposition, it sets practice.
   Everything else in the band is teacher-facing (guides, manual,
   curriculum).
6. DL guide ISBN: the printed "ISBN XXX-XXXX-XXXX-X-X" in all three guide
   files and in the workbook is a placeholder, not a usable identifier.
   The JICA B3 file prints no ISBN and no copyright page (contrast the
   Basic 5/6 volumes in Band B, which carry a copyright page).

## Work 1 — CURR-B13 (RECORD ONLY, not taught lessons)

Title as printed: "Mathematics Curriculum for Primary Schools (Basic 1–3)".
Publisher: Ghana Education Service (Ministry of Education); National
Council for Curriculum and Assessment (NaCCA). Date: September 2019.
Copyright: © NaCCA, Ministry of Education 2019. No ISBN printed. 95 PDF
pages = front matter (PDF pp. 1–19; roman pp. iii–xix visible, contents
p. iv) + Basic 1 divider printed p. 1, content pp. 2–18 + Basic 2 divider
printed p. 19, content pp. 20–40 + Basic 3 divider printed p. 41, content
pp. 42–73 + subject panel members printed pp. 74–75, with printed p. 76 a
blank trailing leaf carrying only the folio and copyright line. Contents page lists Basic 1 at printed p. 2, Basic 2 at p. 20,
Basic 3 at p. 42.

What the document is: a standards-based curriculum. It states the
rationale, philosophy (inquiry-based, learner-centred), general and
subject aims, six core competencies (critical thinking and problem
solving; creativity and innovation; communication and collaboration;
cultural identity and global citizenship; personal development and
leadership; digital literacy), three learning domains (knowledge,
understanding and application; process skills; attitudes and values),
values, assessment policy (formative as/for learning, summative of
learning, criterion-referenced sampling of indicators), and pedagogy
(learning-centred classroom, inclusion, differentiation and scaffolding,
ICT as a teaching tool). Suggested time allocation: ten 30-minute periods
a week at Lower Primary, two periods a day.

Structure: four strands in every grade, each split into sub-strands, then
content standards, then learning indicators, each indicator with teaching
exemplars and the competencies it develops. Annotation: class.strand.
sub-strand.standard.indicator (e.g. B3.1.1.1.1). Scope table (printed
p. xix) lists eight rows, each ticked in all three grades — but it omits
Money: the grade sections themselves carry nine sub-strands, Money
included (B1.1.4, B2.1.4, B3.1.4).

- Strand 1 Number: counting/representation/cardinality; operations
  (addition, subtraction, multiplication, division); fractions;
  money.
- Strand 2 Algebra: patterns and relationships (only sub-strand).
- Strand 3 Geometry and Measurement: 2D/3D shapes (called "lines and
  shapes" in the scope table); position/transformation; measurement
  (length, capacity, mass, time).
- Strand 4 Data: collection, organisation, presentation, interpretation
  and analysis (only sub-strand).

Progression in brief (indicators, not lessons — do NOT file as taught
content): Basic 1 counts and compares to 100, adds/subtracts 1- and
2-digit numbers, halves only, Ghanaian coins, repeating patterns, 2D/3D
shape attributes, position language, non-standard measuring, organising
data in pictures/objects. Basic 2 extends counting to 1,000 with place
value, mental strategies to 19, conventional/personal add/subtract
strategies, halves and quarters, coins and notes, increasing/decreasing
patterns, shape features and making 2D shapes, standard units introduced
alongside non-standard, calendar and hour clock, tallies and concrete
graphs/pictographs. Basic 3 extends counting to 10,000, positive and
negative values and opposite directions, column and mental add/subtract
with regrouping and estimation, multiplication (equal groups, arrays)
and division (sharing, grouping, inverse of multiplication), unit
fractions and like denominators, cedi denominations to 50, patterns with
rules, 3D faces/edges/vertices, angles (including square-corner testing
for right angles), rhombus/parallelogram recognition, distance on a
number line, metre/centimetre and kilogram relationships, perimeter,
time duration and calendar, seconds/minutes/hours, gathering data and
drawing/interpreting pictographs.

What it does NOT contain: no pupil-facing explanations, no worked
exercises to hand a learner, no answer sets, no lesson plans. Its
exemplars are teacher guidance ("e.g." activities), not lessons.
Defect: contents page line for the Foreword reads "Error! Bookmark not
defined" — a word-processing artefact; no content is missing (the
foreword itself is present). Otherwise all 95 pages carry text.

## Work 2 — DL teacher guides, Modules 1–5 (teacher guides)

Title as printed: "Differentiated Learning (DL) Mathematics Teachers
Guide for Lower Primary, Basic 1~3". Publisher: Ghana Education Service
/ Ministry of Education (MoE/GES). Date: November 2020. Copyright
© MoE/GES 2020. ISBN: placeholder only (see corrections). Writers and
reviewers are named (UNICEF funded the guides; the programme is an
up-scaling of the STARS targeted-instruction programme). Each file:
front matter (acknowledgement, foreword, abbreviations, development
team, DL introduction, contents) + three modules + an Activity Book
section + a short glossary.

Programme logic (from the foreword and introduction, read in all three
files): DL remediates learners performing below grade level in English
and mathematics, and stretches learners at grade level. Learners are
assessed and grouped into three ability levels and taught at their
level, not their grade level: 1 hour a day, 2 hours a week per subject,
8 weeks a term. The foreword states the target as Basic 2 to Basic 6
learners who are struggling — note this against the covers' "Basic 1~3".
Each lesson is built the same way: a 5-minute mental activity, a
5-minute reinforcement, a main learning activity (25 minutes in
Modules 1–3; mostly 35–40 minutes in Modules 4–5, with the exceptions
noted in correction 3 above), reflection/plenary questions
(often left as "engage learners with reflective questions" rather than
written out), and self-practice referred to a workbook page ("refer to
workbook page" — the workbook page is never numbered in the guide).
The detailed steps live in the Activity Book at the back, cited by
activity number (e.g. Activity 4A, 9C, 11C); lessons cite steps of those
activities. Two cross-reference slips were found: Module 4 Week 7
Lesson 1 cites "Activity 14", which does not exist in the Activity Book
(activities run 1–11); Module 4 Week 4 Lesson 2 cites "Activity 7A
Step 2" for solving addition on the 100-chart, but Activity 7A Step 2
as printed teaches the addition-frame method (12 + 5 = 17) — the chart
method is Activity 4C, so the citation points at the wrong activity
for the procedure named.

The whole DL guide teaches ONE strand only: Number — counting,
representation, place value, estimation, comparison, and the four
operations, all with concrete objects (straws/sticks, bottle caps,
pebbles, beads, beans), bundles of ten, number lines/charts, place-value
mats/frames, the "number wheel" (two concentric floor circles for tens
and ones, pebbles thrown to make a number), and addition/subtraction
frames. There are no fractions, no money as a taught topic (cedis appear
only inside word-problem stories in the workbook), no algebra/patterns
as a topic, no geometry, no standard measurement, no data handling.
The only measurement content is estimation: guessing quantities, and
estimating lengths with body parts (hand span, foot, stride) in
Activity 1C Step 3 / Activity 5A Step 2.

### Module 1 (guide file 1, printed pp. 1–34)

Week 1: counting 1–50 on the number line and number chart (forwards,
backwards, and in different directions — forwards, backwards, diagonal,
top-to-bottom, random). Week 2: reading 1–50 forwards/backwards and in
different directions. Week 3: counting and representing 1–9, then 10–19,
by matching groups of objects to number cards. Week 4: place value
1–50, then 1–20 — bundling loose straws into tens, placing bundles and
loose ones on the place-value mat/frame, and the number wheel. Week 5:
estimating quantities 1–10 ("guess my number" game; spotting errors in
counting sequences). Week 6: comparing 1–9 by one-to-one matching, then
1–20 with >, <, =. Week 7: adding 1-digit numbers (sums to 10), then
1- and 2-digit numbers (sums to 20) with straws on the addition mat.
Week 8: subtracting 1-digit numbers, then 1- and 2-digit numbers to 20
with straws (worked example 18 − 3 = 15).
Slip: the running strand head over Module 1 Weeks 6–8 reads "Number
operations (Multiplication and Division)" although the content is
comparison, addition and subtraction — multiplication and division do
not appear until Module 3.

### Module 2 (guide files 1 and 2, printed pp. 35–68 in file 1)

Same eight-week shape, extended to 100. Week 1–2: counting 1–100 on the
line and chart, forwards/backwards/different directions, including
reading a number "in a different form" (numeral and number name).
Week 3: counting and representing quantities to 100, then counting with
non-standard units (hand span, pencil, feet, straws) to find "how many".
Week 4: place value 1–100 (bundles/mat/frame; number wheel to compare
and order). Week 5: estimating quantities 1–20, including estimating
lengths with body parts. Week 6: comparing 1–100 by one-to-one matching
and with <, >, =. Week 7: adding 1- and 2-digit numbers (1–50 range in
Lesson 1; 1–20 in Lesson 2) with straws. Week 8: subtracting 1- and
2-digit numbers to 20, then two 2-digit numbers to 100, with straws.

### Module 3 (guide files 1, 2 and 3, printed pp. 69–102 in file 1)

Week 1: counting and representing quantities 0–100 — modelling numbers
with bundles and loose ones, reading from the 1–100 chart, and making a
personal 1–100 chart inside the jotter's back cover. Week 2: place value
of 2-digit numbers (mat/frame, then number wheel). Week 3: comparing
2-digit numbers with <, >, = (bundles first, then number wheel;
worked comparisons such as 28 against 15, 25 against 52). Week 4:
adding 1-digit to 2-digit numbers with regrouping — first on the number
chart (26 + 7 = 33 by moving right; 45 + 31 = 76 by moving down for tens
then right for ones), then the same idea restated. Week 5: subtracting
1-digit from 2-digit numbers with regrouping on the number chart
(35 − 4, 86 − 5; then 28 − 15, 84 − 33). Week 6: word problems — addition
to two 2-digit numbers (worked example: 34 boards + 19 boards, solved by
friendly jumps and by partial decomposition: 34 + 19 = 30 + 4 + 10 + 9
= 53) and subtraction word problems (42 learners on a bus, 16 alight).
Week 7: multiplication of two 1-digit numbers — equal grouping/mixing
sets, the "ladder" method (legs and arms crossed, intersections counted
as the product), multiplication chart and area model; learners also
write word problems for given sentences and vice versa. Week 8:
division of 2-digit by 1-digit numbers — sharing, grouping and repeated
subtraction (worked example 18 ÷ 3 = 6 by repeated subtraction);
learners model sentences from word problems and solve.

### Module 4 (guide files 2 and 3; printed pp. 69–102 in file 2)

Repeats the Module 3 arc at a slightly higher pitch, with Upper Primary
running heads (see corrections). Week 1: counting 0–100 with number
names/numerals in order, bundles and the "guess my number" game.
Week 2: place value of 2-digit numbers, represented pictorially,
symbolically and with objects. Week 3: comparing 2-digit numbers with
<, >, = (bundles, then number wheel). Week 4: adding 1-digit to 2-digit
numbers with regrouping — addition frame/mat (21 + 7, 45 + 9, 51 + 8,
74 + 9, 78 + 8) and 100-chart (32 + 9, 68 + 9). Week 5: subtracting
1-digit from 2-digit numbers with regrouping — subtraction frame and
number chart (18 − 5, 35 − 9, 48 − 5 = 43). Week 6: word problems —
addition (34 boards + 9 more) and subtraction (20 learners, 6 alight)
modelled as sentences and solved by any known strategy. Week 7:
multiplication of two 1-digit numbers by grouping and ladder method,
and by multiplication chart. Week 8: division of 2-digit by 1-digit
numbers by sharing, then by grouping (Activity 11C Steps 1 and 3).

### Module 5 (guide file 3 only; printed pp. 69–102 in file 3)

The step up to three digits. Week 1: number names, numeral recognition
and counting sequence 0–999/0–1000 — bundles of tens and loose ones,
modelling 3-digit numbers, reading from a 1–1,000 chart. Slip: Lesson 1's
third outcome reads "read numbers/numerals between 0 and 100" against
the lesson's 0–999 range; Lesson 2 states the range as 0–1000. Week 2:
place value of 3-digit numbers (hundreds/tens/ones frames, place-value
discs 1/10/100/1000, hundreds number wheel). Week 3: comparing and
ordering 3-digit numbers with <, >, = (worked examples 250 against 205,
270 against 240). Week 4: adding two 2-digit numbers, sums to 99
(21 + 43, 45 + 23, 51 + 28, 14 + 39, 48 + 18; chart method 32 + 17,
60 + 29). Week 5: subtracting two 2-digit numbers (frame and chart:
88 − 55, 45 − 23). Week 6: multiplying a 2-digit number by a 1-digit
number by grouping and by multiplication chart. Week 7: the same
(2-digit × 1-digit) by multiplication chart, then division of 2-digit
by 1-digit numbers by sharing. Week 8: division of 2-digit by 1-digit
numbers by grouping, then by repeated subtraction (18 ÷ 3 = 6).

### Activity Book (in each DL file, printed pp. 103–153, Mental Maths
p. 154, Glossary p. 155; file 3: pp. 102–152, Mental Maths p. 153,
Glossary p. 154)

Eleven numbered activities with lettered variants, read in full from
file 1 and spot-checked identical in file 2 (same activity list in all
three files): 1 counting (1A: 1–50 line/chart; 1B: 1–100; 1C: bundles,
estimation games, body-part length estimation, 1–100 chart reading);
2 reading numbers forwards/backwards (2A: 1–50; 2B: 1–100; 2C: place
value of 2-digit numbers with the number wheel); 3 counting quantities
and comparing 2-digit numbers (3A/3B: matching groups; 3C: 28 against
52 with bundles and wheel); 4 place value and chart arithmetic (4A:
bundles and tens/ones frame; 4B: number wheel; 4C: addition on the
100-chart, right = +1, down = +10; 4D: subtraction on the chart,
backwards/upwards); 5 "Guess my number" estimation games (5A: 1–10
quantities and body-part lengths; 5B: 1–20); 6 comparing numbers
(6A/6B: fistful comparison, one-to-one matching, number wheel);
7 addition with the addition frame (7A: 1-digit + 1-digit, e.g. 5 + 4 = 9,
and 2-digit + 1-digit, e.g. 12 + 5 = 17; 7B: e.g. 21 + 7 = 28);
8 subtraction with the subtraction frame (8A: 6 − 3 = 3, 17 − 5 = 12;
8B: 37 − 5 = 32, 58 − 14 = 44); 9 addition/subtraction word problems
(9C: friendly jumps and partial decomposition; number-line jumps
backwards, e.g. 42 − 16 = 26); 10 multiplication (10C: equal groups,
e.g. 3 groups of 2 = 3 × 2 = 6; ladder/legs-and-arms intersections);
11 division as sharing (11C Step 1: sharing, e.g. 18 shared among 3 is
18 ÷ 3 = 6; Step 2: grouping, e.g. 12 ÷ 3 = 4; Step 3: repeated
subtraction, e.g. 18 ÷ 3 = 6). Then a "Mental Maths Activities" page
(guess my number; thinking of a number in tens and ones; describing
numbers in equivalent ways; 5 more or less; doubles; 1 more/less than a
double; skip counting in 2s/5s/10s; chicken-and-legs; pairs summing to
10/20; finding the number to make 100) and a glossary. The glossary is
reading-strategy material carried over from the English side (DRTA,
DRA, K-W-L, story map) — it contains no mathematics definitions, which
is itself a defect for a mathematics guide.

### DL negatives (whole guide)

No fractions, no money teaching, no patterns/algebra, no geometry, no
standard units, no data. No written pupil exposition anywhere: every
lesson is teacher direction plus an activity reference, and self-practice
is always an unnumbered workbook referral. Reflection questions are
frequently unwritten ("engage learners with reflective questions").
Mental-activity codes (M1, M5, M7, M9 …) are cited but never defined in
the guide itself; only the closing mental-maths page explains some of
them. The guide never states which workbook level or module a lesson's
self-practice belongs to.

## Work 3 — DL workbook, Level 2 (student workbook, task sheets only)

Title as printed: "Differentiated Learning (DL) Mathematics Workbook
for Lower Primary, Level 2 — Learner's Workbook (Basic 1~3)". Publisher:
Ministry of Education / Ghana Education Service. Copyright © MoE/GES
2020. ISBN: placeholder only. Writers named on the copyright page
(Isaac Buabeng, Francis Martey Asare, Edward Mills, Eric Osei-Adofo,
Reginald Quartey, Anita Cordei Collison). 68 PDF pages: cover (PDF 1),
title page (PDF 2), copyright/acknowledgement (PDF 3), table of contents
(PDF 4), content printed pp. 6–68 (PDF 5–67), and a final solid-colour
leaf (PDF 68) carrying no task content — no content is lost.
Body pages are one raster image per page with no text layer; read as
page pictures throughout (see method note at top).

Contents (from its own table of contents, verified page by page):
Module 2 (printed pp. 6–28), Module 3 (pp. 29–47), Module 4 (pp. 48–68),
8 lessons each. Each lesson opens with a title and an "Activity" code
and sets 2–4 tasks; there is no teaching text, no worked explanation
beyond a worked example at the head of some tasks, and no answers.

### Module 2 (printed pp. 6–28)

Lesson 1, Counting Numbers (1–50): completing number tracks forwards
and backwards (20 … 26 … 28; 47, 44, 41 … 35 … 29) and number lines in
2s (38, 40, 42, 44 …; 18, 20, 22 … 26, 28; 19, 23, 27 … 35, 39).
Lesson 2, Counting Numbers (1–50): completing 1–50 charts in 2s/5s/3s
(22, 24, 26, 28, 30 …; 5, 10 … 20 … 40 …; 3, 6, 9 … 24 …) and circling
numbers from 30 to 50 in a mixed grid. Lesson 3, Counting and
representing numbers (1–100): matching groups of equal quantity (balls,
drums, pots, buttons, radios, books, sweets, juice boxes), matching
numerals to pictured groups (29, 30, 25, 28; then 12, 11, 13, 9; 16, 20,
18, 11), and — closing the lesson on printed p. 14 — estimating lengths
in non-standard units (table in sharpeners, table in pens, wall in
feet). Slip: the running head on printed pp. 11–13 reads "Counting and
Representing numbers (1–9)" although the lesson title is (1–100).
Lesson 4, Place value (1–100): "how many tens and ones?" from bundles
and loose sticks (3 tens 5 ones; 5 tens 6 ones), then comparing with
<, > or = using tens/ones wheels and place-value tables (worked example
42 > 34). Lesson 5, Making estimates (1–20): estimating counts ("there
are about ___ red tricycles/cups/cars") and estimating sizes ("the
metal bar is about ___ erasers; the stick is about ___ hand spans; the
building is about ___ ladders"). Lesson 6, Comparing numbers (1–100):
"more than / less than / as same as" sentences for pictured sets
(maths sets against bicycles, pencils against books, apples against
oranges), then <, >, = with shapes, number wheels and place-value
tables. Lesson 7, Adding 1-digit and 2-digit numbers: modelling sums
with bundles and loose sticks on addition charts (worked example
13 + 5 = 18; then 15 + 3, 12 + 6, 11 + 8, 5 + 13, 10 + 6, 14 + 4).
Lesson 8, Subtraction of 1-digit numbers from 2-digit numbers:
modelling subtractions the same way (worked example 15 − 3, chart
showing 1 ten 2 ones).
**Content error in the worked example, printed p. 27: the chart shows
1 ten and 2 ones but the text beneath reads "So, 15 − 3 = 18". The
correct answer is 12, as the chart itself shows.** The same example's
chart is also mislabelled "Addition chart" although it is a subtraction.
This is the one outright wrong answer found in Band A; it must not be
carried into lessons uncorrected.

### Module 3 (printed pp. 29–47)

Lesson 1, Counting quantities of objects: counting bundles and loose
ones ("how many tens? how many ones? write the number") and completing
number charts forwards (11–60) and backwards (70–30). Slip: the task
lettering repeats "b)" twice and the first item's second prompt reads
"How many ones? ___ tens" where "ones" is meant. Lesson 2, Place value
(1–100): tens/ones for pictured bundles (worked example 4 tens 2 ones
= 42) and further bundle counts. Lesson 3, Comparing 2-digit numbers:
comparing with <, >, = from bundles (worked example 1 ten 3 ones <
2 tens 0 ones), from number wheels (worked example 13 < 14), and bare
numerals and sums (23 against 25; 30 against 28; 15 + 1 against 12 + 3;
7 + 13 against 10 + 10). Slip: the last task's items are lettered
a, b, c, c (the second "c" should be "d"). Lesson 4, Addition (sum
1–100): solving on the 100-chart (45 + 5, 25 + 9, 26 + 32, 63 + 24).
Lesson 5, Subtraction of 1-digit number from 2-digit number: solving on
the 100-chart (12 − 3, 25 − 8, 76 − 24, 58 − 13). Lesson 6, Addition and
Subtraction of Word Problems: two-part addition stories (Jane's 15
pencils + 12 more; Saratu's class of 25 boys and 28 girls) and
subtraction stories (Adamu's 30 cedis, 12 spent on food; Kwamena's 34
eggs, 15 eaten) with blank working boxes. Money appears here only as
story context (cedis), never as a taught topic. Lesson 7, Multiplication
(1-digit by 1-digit numbers): writing sentences for pictured groups
(worked example 2 groups of 6 = 2 × 6 = 12), the ladder strategy
(worked example 2 × 3 = 6 by intersections; then 4 × 8, 6 × 2), and the
multiplication chart to 12 (5 × 5 asked against a chart showing rows
1–5). Lesson 8, Division of 2-digit numbers by a 1-digit number: equal
sharing (worked example 12 ÷ 2 = 6, "I got 6"; then 15 ÷ 3, 20 ÷ 5),
repeated subtraction (worked example 12 ÷ 2 by subtracting 2 six times;
then 21 ÷ 3, 36 ÷ 4), and a sharing word problem (28 mangoes, 2 people).

### Module 4 (printed pp. 48–68)

Lesson 1, Counting and Representing: tens/ones counts from bundles and
a "cross out to show 34" task (crossing out bundles/ones to leave
3 tens 4 ones). Lesson 2, Place value of 2-digit numbers: grouping
loose sticks and stars into tens and ones, circling named numerals on
the 100-chart (13, 35, 31, 20, 15, 7, 64), completing charts, reading
number wheels (worked example 33) and drawing pebbles on wheels to show
45 and 62. Lesson 3, Comparing 2-digit numbers using < or >: wheels
(worked example 25 < 52), bundles, place-value charts (41 against 36),
and comparing expressions (2 × 6 against 2 + 6; 8 ÷ 2 against 5 × 2) —
the only place in the workbook where multiplication/division facts are
compared against each other. Lesson 4, Adding 1-digit numbers and
2-digit numbers: bundles-plus-loose sums (worked example 3 tens + 5
ones = 35), addition-frame sums, column sums (11 + 8, 24 + 7) and bare
sums (44 + 8, 34 + 6), plus chart jumps (22 + 6). Lesson 5, Subtracting
a 1-digit number from a 2-digit number: subtraction-frame sums (1 ten
6 ones − 4 ones; 2 tens 3 ones − 7 ones), column subtractions (49 − 4,
57 − 7, 38 − 6, 26 − 4) and chart jumps (worked example 48 − 5 = 43 by
hops backwards; then 31 − 8). Lesson 6, Solving the addition word
problems: addition stories (Mrs Mensah's goat meat, 35 kg + 9 kg;
Basic 6 admissions, 36 + 12 learners) with blank working boxes, then
subtraction stories (Papa Kuma's 53 mangoes, 9 sold; 52 party guests,
13 absent). Lesson 7, Multiplication of two 1-digit numbers: grouping
(worked example 4 groups of 6 = 4 × 6 = 24), ladder strategy (worked
example 3 × 4 = 12; then 5 × 6, 7 × 4) and the multiplication chart
(7 × 7 asked against rows 1–7). Lesson 8, Division of 2-digit numbers
by a 1-digit number: equal sharing (worked example 15 ÷ 5 = 3; then
21 ÷ 3, 30 ÷ 2), repeated subtraction (worked example 20 ÷ 4 by
subtracting 4 five times; then 24 ÷ 3), and a sharing story (15 oranges,
5 people). Slips: the running head on printed p. 67 reads
"Multiplication of two 1-digit numbers" although the lesson is division
(the p. 66 opener page itself carries no running head);
and Lesson 8 Task 2 item b is headed "64 ÷ 8 =" but its answer line
reads "So, 32 ÷ 4 =" — the two do not match (both equal 8, but the
question and the answer line disagree).

### Workbook negatives

No fractions, no money teaching, no patterns, no geometry, no standard
measurement, no data. No division with remainders anywhere (every
division divides exactly). No 3-digit numbers (Module 5 has no workbook
in this set). No answers are printed for any task. The workbook never
explains a method: a learner who has not had the matching guide lesson
cannot learn the method from the workbook alone.

## Work 4 — JICA Primary Mathematics Teacher Manual B3 (teacher manual)

Title as printed: "JICA Primary Mathematics Teacher Manual B3".
Developed by the National STEM Resource Unit in GES in collaboration
with the Japan International Cooperation Agency (JICA). Dated April
2025; piloted March 2023–July 2024 in schools, which the manual says
improved achievement. No ISBN printed; no copyright page in this B3
file version. 134 PDF pages: cover + front matter (roman pp. i–viii) +
120 one-page lessons + a five-page annual "Review of B3" (printed
pp. 121–125).

Design (front matter, read in full): two lesson types — normal lessons
(new curriculum topics) and review lessons (previous four lessons;
lesson numbers that are multiples of 5). A week is four normal lessons
plus one review lesson; 120 lessons in the year. Each lesson page has
five parts: (1) basic information — lesson number, the curriculum
reference it serves (e.g. B3.1.1.1.1, with the curriculum's printed page
and exemplar numbers), lesson objective, sample introduction, teaching
tips and teacher's notes; (2) title and Exercise Part 1 (tasks [1],
[1A], [1B] — black answers are worked examples, pink parts are answers
the teacher writes in after learners have worked); (3) Exercise Part 2
(tasks [2], [2A], [2B]; [R] is a review task from the previous lesson);
(4) mental maths (given verbally, never written first; learners memorise
answers, repeating mistakes five times aloud); (5) homework. Lesson
conduct (normal lesson, 60 minutes): 15-minute introduction, 15-minute
Exercise Part 1 with peer marking, 15-minute Exercise Part 2 with peer
marking, 5-minute mental maths (the manual's timings sum to 50 minutes
plus marking time; review lessons run 30 minutes of test, 25 minutes
of correction, 5 minutes mental maths). Rules stressed throughout: the
first sub-task is the check — if more than half the class cannot solve
it, re-explain to the whole class; do not skip tasks unless there is an
obvious mistake; do not write the lesson objective on the board (the
lesson title serves as the learners' objective); write everything in
black before the dotted line, pink answers only afterwards. A sample
scheme of work paces review lessons from 27 September (Lesson 5) to
30 June (Lesson 120), with the rule: if behind schedule, skip the
review lesson, never a normal lesson. A lesson observation sheet and a
note that training videos and downloads sit on the National STEM
Resource Unit website (via QR code) close the front matter. FAQ points
worth keeping: content is deliberately slightly more than the average
learner finishes in the time; fast learners do all tasks, slower
learners need not finish every task; the manual covers the curriculum
in 120 hours, fewer than the total lessons a teacher is expected to
conduct, so unfinished ground is revisited, not skipped.

Sequencing note: the manual deliberately reorders the curriculum. Its
note on Lesson 14 states that the standard-strategy indicators
(B3.1.2.1 and B3.1.2.2) were moved to later lessons (they appear at
Lessons 21, 37–39 and 41) because mental strategies (B3.1.2.3) come first.
Lessons 101–102 (number-line addition/subtraction) are late revisits
inserted between the measurement block and the time block, and
Lessons 118–119 (doubling; multiplication on a number line) sit after
the data block, as late revisits rather than in strand order.

Lesson map (all 120 lessons read; titles are the learners' titles as
printed, objectives paraphrased; "R" = review lesson):

- Number — counting and place value (Lessons 1–13, plus reviews 5, 10):
  skip counting to 10,000 by 10s/50s/100s/500s/1000s, hiding zeros to
  find patterns; number names (typical mistake: writing names the wrong
  way round); modelling numbers to 10,000; place-value tables (e.g. in
  3456, how many thousands/hundreds/tens/ones); decomposing without
  base-ten diagrams (4320 = 4000 + 300 + 20); relative size by start/end
  values; comparing and ordering to 10,000 by place-value rule and by
  number line; opposite directions and negative numbers (opposite game;
  mountain/sea-level picture; "negative shows a value, minus shows an
  operation"); negative values on number lines with calibrations 1, 5, 10.
- Number — mental and written addition/subtraction (Lessons 14–41,
  plus reviews 15, 20, 25, 30, 35, 40): multiples of 10 ± multiples of 10
  and multiples of 100 ± multiples of 100 mentally; 2-digit ± 1-digit and
  ± multiples of 10; part-part-whole relations; making 10s; decomposition
  (234 + 615, 546 − 312); column addition/subtraction without regrouping,
  with regrouping once, with regrouping twice, then any type; making-10s
  compensation with bottle tops; estimating answers by rounding off;
  word problems (including money costs as story context); commutativity
  of addition (two tapes/ropes); unknowns solved by subtraction and by
  addition, then word problems with unknowns in different positions;
  the not-equal sign (≠, e.g. 4 ≠ 5).
- Number — multiplication and division (Lessons 42–65, plus reviews 45,
  50, 55, 60, 65): meaning of multiplication and multiplication sentences;
  modelling with concrete objects and the "fence"/legs-and-arms diagram
  (5 legs and 3 arms = 5 × 3 = 15); times tables 5, 2, 3, 4, then
  commutativity (3 × 2 drawn both ways), then tables 6, 7, 8, 9, each
  applied to a small problem (bofrots in bags, players in teams, eggs in
  trays, cakes in boxes); developing the multiplication chart; division
  as sharing, as grouping and repeated subtraction, "as many as"
  questions by division (32 cm against 8 cm tape); division as inverse
  of multiplication; division by multiplication; sharing and grouping
  word problems.
- Number — fractions (Lessons 66–73, plus review 70): unit fractions by
  folding and dividing circles/rectangles into equal parts (first
  meeting with the word "fraction"; "a quarter is the same as 1 fourth",
  kept because clocks are read in quarters); non-unit fractions with
  several shapes; fractions of a group of objects (bottle tops); fractions
  of lengths (16 cm strips); comparing by fraction charts and by tape
  diagrams/pictorials; fractions on the number line.
- Number — money (Lessons 74–76, plus review 75): different ways to pay
  and give change with cedi denominations (worked with play money;
  e.g. making ¢6 and other amounts several ways). Money is a short
  two-lesson block here, not a running thread.
- Algebra — patterns (Lessons 77–79, plus review 80): extending patterns
  and finding rules, correcting pattern errors, creating a pattern for a
  given rule, finding patterns in a 100-chart (multiples of 10 circled).
- Geometry and measurement — shapes (Lessons 81–93, plus reviews 85, 90):
  regular shapes defined (same angles, same side lengths) among
  triangles, rhombi, rectangles, squares, pentagons, hexagons, octagons;
  angles — right angle from book/ruler edges and folded paper, drawing
  and naming regular polygons by side count; perpendicular and parallel
  lines and their relation; quadrilaterals by pairs of parallel sides
  (trapezoid 1 pair, parallelogram/rhombus/rectangle 2 pairs,
  quadrilateral 0) and by right angles/equal sides (square as both);
  3D objects named (cylinder, prisms, cone, pyramid, sphere, cube) from
  real objects, then drawn from their names. Tension to note: Lesson 83's
  objective names three angle types (acute, right, obtuse) but its own
  teacher's note says "Do NOT teach the term acute angle and obtuse
  angle. They are covered in B5" — the lesson in fact only secures right
  angles and "bigger than a right angle".
- Geometry and measurement — position and measurement (Lessons 94–110,
  plus reviews 95, 100, 105, 110): distance between two points on a
  number line (calibration 1, then bigger than 1); estimating length with
  body parts (finger width ≈ 1 cm, hand span ≈ 10 cm, arm span ≈ 1 m;
  "length" for the longer side, "width" for the shorter); converting
  metres and centimetres (100 cm = 1 m) and choosing referents; perimeter
  of polygons by measuring cut-out shapes; distinguishing capacity and
  mass (pan balance; heavier/lighter chains such as apple > orange >
  banana); converting litres/millilitres (4 × 250 mL = 1 L; 6 × 500 mL
  = 3 L) and kilograms/grams (5 L 40 mL = 5040 mL; 3 kg 50 g = 3050 g);
  personal referents for time (1 minute, 10 minutes, 1 hour), durations
  within and beyond the hour, across a.m./p.m., by number line and
  column method (skip counting in 5s for minutes); calendar by the
  knuckle method, months and days; converting days/hours/minutes/seconds
  (rhyme: 60 seconds = 1 minute, and so on). Note: Lesson 99's title is
  "Understand how heavy it is" but its tasks mix mass comparison (pan
  balance) with litre/millilitre conversion, although its curriculum
  line cites a single indicator (B3.3.3.2.2).
- Data (Lessons 111–117, plus review 115): counting with tallies (bottle
  cap thrown 10 times per partner; rule: strike out each object as its
  tally is drawn, never count first and tally later); tables organising
  data (including multiples tables); interpreting pictographs (key: one
  circle means a stated number) and bar graphs; drawing pictographs and
  bar graphs from tables, with titles and keys checked.
- Late revisits (Lessons 118–120, plus review 120): doubling for
  addition/subtraction, multiplication on a number line, and a final
  review of the block.
- Annual Review of B3 (printed pp. 121–125, five pages, no mental maths,
  but WITH a homework section on each page): column addition/subtraction of 3-digit numbers with and
  without regrouping (247 − 123 = 124; 257 + 368 = 625; 420 − 189 = 231);
  fractions of lengths and diagrams (20 cm tape in quarters; 12 cm bar
  in thirds); sharing/grouping division stories (72 meat pies, 8 per
  box); multiplication and division facts. (Pictograph drawing and
  doubling do NOT appear in the review pages; they belong to Lessons 116
  and 118 respectively.)
  Its objective line reads "topics learnt in P3" on pp. 121–123 and 125
  — a P3/B3 terminology slip — but p. 124 correctly reads "topics learnt
  in B3" (the manual is otherwise consistently B3).

JICA negatives: no geometry beyond the blocks above (no symmetry, no
transformations beyond number-line distance, no area); no algebra beyond
patterns; no statistics beyond tallies/tables/pictographs/bar graphs;
no decimals, no percentages, no ratio; no multiplication beyond the
1–9 tables and 2-digit-by-1-digit division (no 2-digit × 2-digit, no
long division); fractions stop at comparing/ordering and fractions of
quantities — no adding or subtracting fractions, no equivalent
fractions as a method. Every lesson's mental maths is addition,
subtraction, multiplication or division facts only.

JICA slips and defects (small): "quadrilateralls" (Lesson 87 note);
"mulitiplication" (Lessons 63–64 objectives); "the tile of the lesson"
for "title" (FAQ); Lesson 14's note and the actual placement of the
moved indicators differ slightly (note says "lesson 33 onwards"; the
indicators land at Lessons 21, 37–39 and 41); the normal-lesson timings as
printed (15 + 15 + 15 + 5) do not sum to the stated hour until peer
marking is counted. None of these affects the mathematics except where
noted above. No missing lessons: Lessons 1–120 are all present in order,
and the annual review follows Lesson 120.

Cross-check against the curriculum: every JICA lesson cites its
curriculum indicator and printed curriculum page (pp. 42–73, exactly
the Basic 3 span of CURR-B13), so the manual and the curriculum lock
together indicator by indicator. The DL guides cite no curriculum
indicators at all.

## Band A negatives (whole band)

- No pupil textbook with taught lessons. A learner meeting this band
  alone gets task sheets (workbook) and teacher direction (guides) but
  no book that explains anything to them.
- No Basic 1 or Basic 2 pupil-facing material at all: the Basic 1–2
  ground is carried only by the shared curriculum document and by the
  level-based DL material, which is pitched by ability, not by grade.
- No fractions, money teaching, patterns, geometry, measurement or data
  in the DL material; the JICA manual covers all strands but only at
  Basic 3 level, and only the slice listed above.
- The workbook covers DL Modules 2–4 only: there is no workbook in this
  band for DL Modules 1 or 5, and no workbook at all for the JICA manual
  (its exercises are copied from the board into exercise books).
- The curriculum's Basic 1 and Basic 2 indicators have no matching
  teacher manual in this band: the only manual is Basic 3.
- Division with remainders, decimals, and any number above 10,000 do not
  appear anywhere in the band.

## Held-copy defects and slips (summary)

- CURR-B13: contents-page "Error! Bookmark not defined" for the
  Foreword line only; no content missing.
- DL guides: placeholder ISBNs; Module 1 Weeks 6–8 strand head
  mislabelled "Multiplication and Division"; Module 4 Week 7 Lesson 1
  cites non-existent "Activity 14"; Module 4 Week 4 Lesson 2 cites
  "Activity 7A Step 2" for chart addition although that step teaches the
  addition frame (chart addition is Activity 4C); Module 5 Week 1 Lesson 1 outcome range slip
  (0–100 against 0–999); glossary is English reading strategies, not
  mathematics; mental-activity codes cited but not defined in-guide;
  self-practice workbook pages never numbered; Modules 4–5 carry Upper
  Primary running heads inside Lower Primary covers.
- DL workbook: one wrong worked answer — printed p. 27, "So, 15 − 3 =
  18" (correct: 12), with its chart mislabelled "Addition chart";
  running-head slips (pp. 11–13 "(1–9)" for a (1–100) lesson; p. 67
  multiplication head on a division lesson); repeated "b)" lettering
  and a "tens" for "ones" slip (Module 3 Lesson 1); duplicated "c)"
  lettering (Module 3 Lesson 3 Task 3); question/answer-line mismatch
  "64 ÷ 8 =" against "So, 32 ÷ 4 =" (Module 4 Lesson 8 Task 2).
- JICA B3: no copyright/ISBN page in this file version; "P3" for "B3"
  in the annual review objective; Lesson 83 acute/obtuse tension;
  "quadrilateralls", "mulitiplication", "tile" typos; Lesson 14 note's
  "lesson 33 onwards" against actual placement at Lessons 21, 37–39
  and 41;
  lesson timings not summing to the stated hour without peer marking.
  No missing lessons; no wrong mathematics found in sampled worked
  answers (every sampled answer checked against its own working).

## CITATION CHECK — Band A (checker, 2026-11-04)

Method: every anchor below was opened at its exact page in the real PDF
(text-layer files by page extraction; the workbook by its rendered page
pictures in wbimg/). Printed page numbers are the books' own folios, not
PDF counts. Repeated DL modules were compared lesson by lesson across
files after stripping printed pagination: M2 (file 1 vs file 2), M3 (file 1
vs file 2 vs file 3), M4 (file 2 vs file 3) and the Activity Book (all
three files) are text-identical apart from printed page numbers.
A grep for the draft-truncation marker returns zero hits in this draft.
Per-work counts are passed / corrected / not-found. No anchor was
not-found; nothing was deleted silently — every correction below is an
in-place fix to the draft's own claim.

- CURR-B13: 20 anchors — 18 passed, 2 corrected, 0 not-found.
  Anchors: title/publisher/September 2019/© 2019/no ISBN/95 PDF pp.;
  front matter (roman iii–xix visible, contents p. iv); grade spans;
  contents B1 p. 2 / B2 p. 20 / B3 p. 42; rationale + inquiry-based,
  learner-centred philosophy; six core competencies; three learning
  domains; assessment (formative as/for, summative of,
  criterion-referenced sampling); pedagogy (learning-centred, inclusion,
  differentiation, ICT); time allocation (10 × 30 min/week, 2/day,
  printed p. xii); four strands + annotation example; scope table;
  Strand 1 sub-strands incl. Money; Strand 2 patterns only; Strand 3
  sub-strands; Strand 4 data only; B1 progression (to 100, halves only,
  coins); B2 progression (to 1,000, mental to 19, quarters, notes);
  B3 progression (to 10,000, negatives, fractions, money to 50,
  perimeter, pictographs); Foreword "Error! Bookmark not defined"
  with the foreword itself present.
- DL file 1 (Modules 1–3): 20 anchors — 19 passed, 1 corrected,
  0 not-found. Anchors: cover/November 2020/© MoE/GES 2020/placeholder
  ISBN; TOC sliding window M1–M3; foreword (Basic 2–6 target, UNICEF/IPA,
  STARS up-scale); introduction (three ability levels, 1 hr/day,
  2 hrs/week/subject, 8 weeks/term); lesson shape 5 + 5 + 25;
  Module 1 Weeks 1–8 Big Ideas; Module 1 Weeks 6–8 "Multiplication and
  Division" head slip; Module 1 Week 8 worked 18 − 3 = 15; Module 2
  Weeks 1–8 Big Ideas incl. Week 7 ranges (1–50 / 1–20); Module 2 Week 2
  "different form" reading; Module 3 Week 4 chart work (26 + 7 = 33,
  45 + 31 = 76 via Activity 4C); Module 3 Week 6 stories (34 + 19,
  42 learners / 16 alight); Module 3 Week 7 ladder method; Module 3
  Week 8 repeated subtraction 18 ÷ 3 = 6; Activity Book activities 1–11
  with worked examples (3C 28 vs 52, 4C, 7A 5 + 4 = 9 / 12 + 5 = 17,
  8A 6 − 3 = 3 / 17 − 5 = 12, 8B 37 − 5 = 32 / 58 − 14 = 44,
  9C 42 − 16 = 26, 10C 3 groups of 2, 11C sharing/grouping/repeated
  subtraction); Mental Maths page; glossary (DRTA, DRA, K-W-L, no maths
  definitions); Activity Book page span.
- DL file 2 (Modules 2–4): 18 anchors — 16 passed, 2 corrected,
  0 not-found. Anchors: TOC window M2–M4; M2 repeat identical to file 1;
  M3 repeat identical to file 1; Module 4 divider "Upper Primary";
  Module 4 Week 4 examples (21 + 7 … 78 + 8; 32 + 9, 68 + 9);
  Module 4 Week 5 examples (18 − 5, 35 − 9, 48 − 5 = 43);
  Module 4 Week 6 stories (34 boards + 9; 20 learners / 6 alight);
  Module 4 Week 7 Lesson 1 "Activity 14" citation (printed p. 95) with
  no Activity 14 in the book; Module 4 Week 7 main activity 40 minutes;
  Upper Primary heads on Module 4 lesson pages; Activity Book identical
  to file 1; glossary identical; Module 4 lesson count (16);
  Module 4 Week 8 division (Activity 11C); Module 4 main-activity
  timings; Module 4 Week 4 Lesson 2 activity citation.
- DL file 3 (Modules 3–5): 18 anchors — 17 passed, 1 corrected,
  0 not-found. Anchors: TOC window M3–M5; M3 repeat identical to
  files 1–2; M4 repeat identical to file 2; Module 5 divider
  "Upper Primary"; Module 5 Week 1 Lesson 1 outcome slip ("0 and 100"
  against 0–999) and 20-minute main activity; Module 5 Week 3
  comparisons (250 vs 205, 270 vs 240); Module 5 Week 4 sums
  (21 + 43, 45 + 23 …); Module 5 Week 5 subtractions (88 − 55, 45 − 23);
  Module 5 Weeks 6–8 Big Ideas (2-digit × 1-digit, then division);
  Module 5 main-activity timings; Activity Book identical to files 1–2
  (one printed page earlier); glossary; Module 5 lesson count (16);
  Module 5 Week 2 place value of 3-digit numbers; Module 5 Week 1
  Lesson 2 range stated as 0–1000.
- DL-WB-LOWER-L2: 20 anchors — 19 passed, 1 corrected, 0 not-found.
  Anchors: table of contents (Modules 2/3/4, lesson starts pp. 6/29/48);
  Module 2 Lesson 1 printed p. 7 tracks (20 … 26 … 28; 47, 44, 41 … 35 …
  29); Module 2 Lesson 3 running head "(1–9)" on printed pp. 11 and 13;
  Module 2 Lesson 3 closing printed p. 14 (table in sharpeners/pens,
  wall in feet); Module 2 Lesson 4 opener printed p. 15 (3 tens 5 ones,
  5 tens 6 ones); Module 2 Lesson 7 printed p. 25 (worked 13 + 5 = 18;
  tasks 15 + 3, 12 + 6); Module 2 Lesson 8 printed p. 27 wrong worked
  answer ("So, 15 − 3 = 18", chart showing 1 ten 2 ones, chart
  mislabelled "Addition chart"; correct: 12); Module 3 Lesson 1 printed
  p. 30 slips ("How many ones? ___ tens"; second item lettered
  b) b) c)); Module 3 Lesson 3 Task 3 printed p. 36 (a, b, c, c;
  23 vs 25, 30 vs 28, 15 + 1 vs 12 + 3, 7 + 13 vs 10 + 10);
  Module 3 Lesson 6 printed p. 41 stories (Jane 15 + 12; Saratu
  25 boys / 28 girls); Module 3 Lesson 7 printed p. 43 (2 groups of 6
  = 2 × 6 = 12); Module 4 Lesson 2 printed p. 51 (grouping sticks/stars
  into tens and ones); Module 4 Lesson 3 printed p. 53 wheels
  (25 < 52) and printed p. 54 charts (41 vs 36) and expressions
  (2 × 6 vs 2 + 6; 8 ÷ 2 vs 5 × 2); Module 4 Lesson 4 printed p. 56
  (worked 3 tens + 5 ones = 35); Module 4 Lesson 5 printed p. 60
  (column 49 − 4, 57 − 7; chart 48 − 5 = 43; then 31 − 8);
  Module 4 Lesson 8 printed p. 66 opener (15 ÷ 5 = 3; then 21 ÷ 3),
  printed p. 67 multiplication running head, printed p. 68 Task 2b
  ("64 ÷ 8 =" against "So, 32 ÷ 4 =") and sharing story (15 oranges,
  5 people); final PDF p. 68 solid-colour leaf, no content.
- JICA-B3: 21 anchors — 16 passed, 5 corrected, 0 not-found.
  Anchors: cover/April 2025/pilot March 2023–July 2024/no ISBN/no
  copyright page; 134 PDF pp. (cover + 8 front-matter + 120 lessons
  + 5 review; review folios 121–125); five-part lesson structure;
  normal-lesson timings (15 + 15 + peer-marking 5 + 15 + peer-marking 5
  + mental 5 = 60) and review timings (30 + 25 + 5); first-sub-task
  more-than-half rule; black/pink + dotted line + objective not on the
  board + "tile" typo; mental maths verbal-first, mistakes repeated
  five times aloud; do-not-skip rule, fast/slower learners, 120 hours;
  scheme of work (Lesson 5: 27 September → Lesson 120: 30 June; skip
  the review, never a normal lesson); observation sheet + National STEM
  Resource Unit QR note; Lessons 1–13 titles and curriculum refs;
  Lesson 14 note + actual placement of B3.1.2.1/B3.1.2.2; Lessons 14–41
  block (decomposition 234 + 615 / 546 − 312 at Lesson 21,
  commutativity, unknowns, not-equal); Lessons 42–65 block (meaning of
  multiplication, fence 5 × 3 = 15, tables 5/2/3/4, commutativity,
  tables 6/7/8/9 with bofrots/eggs problems, multiplication chart,
  division sharing/grouping/inverse, "as many as" 32 cm vs 8 cm,
  "mulitiplication" typo at Lessons 63–64); Lessons 66–73 fractions
  (first use of the word "fraction", "a quarter is the same as
  1 fourth", 16 cm strips); Lessons 74–76 money (¢6 combinations,
  pay/change); Lessons 77–79 patterns; Lessons 81–93 shapes (Lesson 83
  tension verbatim; "quadrilateralls" at Lesson 87); Lessons 94–110
  measurement (hand span ≈ 10 cm, arm span ≈ 1 m, 100 cm = 1 m,
  perimeter, pan balance, Lesson 99 mix, knuckle calendar, "60 seconds
  make a minute" rhyme); Lessons 111–117 data (bottle cap thrown
  10 times, tally strike-out rule, pictograph/bar interpretation and
  drawing); Lessons 101–102 / 118–119 placement; annual review contents
  and objective line.

Corrections made in place by this check (12):
1. CURR-B13 grade spans: the draft counted each next grade's divider as
   the previous grade's last page. Fixed to: Basic 1 divider p. 1,
   content pp. 2–18; Basic 2 divider p. 19, content pp. 20–40; Basic 3
   divider p. 41, content pp. 42–73; panel pp. 74–75; printed p. 76 is a
   blank trailing leaf (folio + copyright only).
2. CURR-B13 scope table: the eight ticked rows omit Money, while the
   grade sections carry nine sub-strands including Money (B1.1.4,
   B2.1.4, B3.1.4). Sentence fixed to say so.
3. DL timings: Modules 4–5 are NOT uniformly 35–40 minutes. Fixed in
   correction 3 and in the Work 2 introduction: Module 4 is 35–40
   except Week 1 Lesson 1 (25 minutes); Module 5 mixes 20-minute
   (Week 1, both lessons), 25-minute (Week 2 Lesson 2, Week 3,
   Week 4 Lesson 1, Week 6 Lesson 1) and 35–40-minute main activities.
4. DL Activity 7A Step 2: the draft said chart addition "appears as
   both Activity 4C and Activity 7A Step 2". Fixed: Module 4 Week 4
   Lesson 2 cites 7A Step 2 for chart addition, but 7A Step 2 as printed
   teaches the addition-frame method (12 + 5 = 17); the chart method is
   Activity 4C. Same fix applied to the held-copy defects summary.
5. DL Activity Book span: fixed from "pp. 103–154 (file 3: 102–153)" to
   Activity Book pp. 103–153 + Mental Maths p. 154 + Glossary p. 155
   (file 3: 102–152 + 153 + 154).
6. Workbook running-head page: the multiplication head on the division
   lesson is on printed p. 67, not p. 66 (p. 66 is the lesson opener and
   carries no running head). Fixed in the Module 4 section and in the
   held-copy defects summary.
7. JICA Lessons 101–102 placement: they do NOT sit after the data
   block. Fixed: they are late revisits between the measurement block
   and the time block; only Lessons 118–119 follow the data block.
8. JICA annual review homework: the draft said "no homework". Fixed:
   every review page (pp. 121–125) carries a homework section; only
   mental maths is absent ("*No mental maths").
9. JICA annual review contents: pictograph drawing and doubling do NOT
   appear in the review pages (they belong to Lessons 116 and 118).
   Removed from the review list.
10. JICA annual review objective: "topics learnt in P3" appears on
    pp. 121–123 and 125, but p. 124 correctly reads "topics learnt in
    B3". Fixed to say so.
11. JICA Lesson 14 placement: the moved indicators land at Lessons 21,
    37–39 AND 41 (B3.1.2.2.1 at Lesson 41 was omitted). Fixed in the
    sequencing note, the slips section and the defects summary.
12. JICA Lesson 99 wording: its curriculum line cites a single indicator
    (B3.3.3.2.2), so "serves two curriculum indicators at once" was
    replaced with the observable fact: its tasks mix pan-balance mass
    comparison with litre/millilitre conversion.

Flagged claim re-verified (unchanged, correct as drafted): workbook
printed p. 27, "So, 15 − 3 = 18" against its own chart showing
1 ten 2 ones (correct: 12), chart mislabelled "Addition chart".
Also re-verified unchanged: DL sliding-window mapping (file 1 =
Modules 1–3, file 2 = Modules 2–4, file 3 = Modules 3–5; distinct
content Modules 1–5 = 80 lessons); workbook Modules 2, 3 AND 4
(24 lessons); JICA 120 lessons + 5-page review, all present in order.


## Band B — Upper Primary, Basic 4–6
Country: Ghana. Subject: Mathematics. Band: Upper Primary, Basic 4–6 (B4, B5, B6).
Language as printed throughout: English. All maths content below is filed in English.

## Band at a glance

- Record rows in this band: 18 (Basic 4, Basic 5 and Basic 6 filings of the same span-wide works).
- Distinct works read: 8. Each distinct file was read once; duplicate rows are byte-identical
  re-filings under other grades in the span and are listed under the work they duplicate.
- Distinct pages read: 1,488 (182 + 278 + 278 + 277 + 65 + 134 + 137 + 137).
  Row-counted pages (18 rows): 3,648.
- Kinds in this band: 1 curriculum/planning document (record-only), 3 teacher-guide
  volumes, 1 learner workbook, 3 teacher manuals. There is NO pupil textbook in this band.
- Citation shape used below: Ghana + work + Basic span + page (PDF page unless a printed
  page is stated) + year/edition as printed. No real ISBN exists for any work in this band:
  the DL works print only a placeholder, the JICA B5/B6 works print only a placeholder,
  and the curriculum and the JICA B4 file print no ISBN at all.

## Scope facts for the whole band

- The DL (Differentiated Learning) material is remediation/foundational material for
  learners working below or at grade level. It teaches NUMBER only — counting,
  representation, place value, comparing/ordering, and the four operations. It does NOT
  teach fractions, decimals, percentages, algebra, geometry/measurement, or data.
- The JICA manuals are the only works in this band that cover all four curriculum strands
  (Number, Algebra, Geometry and Measurement, Data). They are teacher manuals: board
  scripts with exercises, mental maths and homework — not pupil exposition pages.
- The NaCCA curriculum is a planning document, not taught lessons. Its content is
  recorded in the record-only section at the end and is NOT filed as lessons.
- The DL workbook in the set is the Level 1 workbook. DL workbook Levels 2 and 3 for
  Upper Primary are NOT in the set. (Correction to the brief: the Level 1 workbook file
  itself contains Modules 1, 2 and 3 — see the workbook section and Record corrections.)
- No work in this band teaches: B4–B6 science, or any subject other than mathematics;
  and within mathematics, nothing in this band teaches statistics beyond the data/probability
  blocks listed under the JICA manuals, and nothing teaches formal geometry proofs,
  trigonometry, or secondary algebra.

---

## 1. CURR-B46 — NaCCA Mathematics Curriculum for Primary Schools (Basic 4–6)

- File: grade4_full-year.pdf (duplicate rows: grade5_full-year.pdf, grade6_full-year.pdf).
- Cover title as printed: "MATHEMATICS CURRICULUM FOR PRIMARY SCHOOLS (BASIC 4-6)".
- Publisher: Ghana Education Service (Ministry of Education); National Council for
  Curriculum and Assessment (NaCCA). Dated September 2019. Copyright © NaCCA, Ministry
  of Education 2019. No ISBN printed.
- Pages: 182 PDF pages (printed pp. i–xviii front matter, then printed pp. 1–164 content;
  PDF p. 182 is printed p. 164 and carries only the running footer, no body content;
  there is no missing content page).
- Proved kind: CURRICULUM / PLANNING DOCUMENT, not a textbook and not a teacher guide.
  Recorded in the set-table as generic "teacher"; that recording is corrected here.
- Status in this draft: RECORD-ONLY. See the record-only curriculum section at the end.
  Nothing from this document is filed below as a taught lesson.

## 2. DL-TG-UPPER — Differentiated Learning Mathematics Teachers Guide for Upper Primary

Three distinct files, one shared design. Read as three level volumes, NOT as three
sequential modules (see Record correction 1).

### 2a. Level 1 file (DL-TG-UPPER-M1 in the set-table)

- File: grade4_teacher-guide_level-1.pdf (duplicate rows: grade5, grade6 level-1 filings).
- Cover: "Differentiated Learning (DL) Mathematics Teachers Guide for Upper Primary,
  Basic 4~6", November 2020. Copyright © MoE/GES 2020. ISBN printed only as the
  placeholder "ISBN XXX-XXXX-XXXX-X-X" — no real ISBN.
- Pages: 278 PDF pages (printed pp. 1–102 lesson plans, printed pp. 103–265 Activity
  Book, printed p. 266 Mental Maths Activities, printed p. 267 Glossary).
- Contents of THIS file: lesson plans for Modules 1, 2 and 3 (see module map below),
  then the shared Activity Book (Activities 1–23), Mental Maths Activities, Glossary.

### 2b. Level 2 file (DL-TG-UPPER-M2 in the set-table)

- File: grade4_teacher-guide_level-2.pdf (duplicate rows: grade5, grade6 level-2 filings).
- Same cover, copyright and placeholder ISBN as the Level 1 file. 278 PDF pages.
- Contents of THIS file: lesson plans for Modules 2, 3 and 4, then the SAME Activity
  Book (Activities 1–23, text-identical to the Level 1 file's Activity Book), the same
  Mental Maths Activities page and the same Glossary. Only the lesson-plan window
  differs from the Level 1 file; the back matter does not.

### 2c. Level 3 file (DL-TG-UPPER-M3 in the set-table)

- File: grade4_teacher-guide_level-3.pdf (duplicate rows: grade5, grade6 level-3 filings).
- Same cover, copyright and placeholder ISBN. 277 PDF pages (one page fewer than the
  other two level files; the lesson-plan and Activity Book content is the same in kind,
  with the Activity Book starting one PDF page earlier).
- Contents of THIS file: lesson plans for Modules 3, 4 and 5, then the SAME Activity
  Book, Mental Maths Activities and Glossary as the other two files.

### How the DL programme works (front matter, PDF pp. 6–11)

- DL is remediation: it bridges gaps for learners lagging behind grade-level proficiency
  and also stretches learners at grade level, in English Language and Mathematics.
  Foreword (PDF p. 7) states the programme supports Basic 2 to Basic 6 learners.
- Delivery: learners are assessed and grouped into three learning-ability levels and
  taught at their level, 1 hour a day, 2 hours a week per subject, 8 weeks per term.
  Levels are monitored and learners are re-assessed and moved up where they improve.
- Each level's guide is organised in modules of 8 weeks, 2 lessons per week, 1 hour per
  lesson. Each lesson plan is 2 PDF pages: page 1 gives the strand label, module/week/
  lesson, Big Idea, Learning Outcomes, Key Words and Materials; page 2 gives the
  Teaching Procedure — Mental Activity (5 minutes), Reinforcement (5 minutes), Learning
  Activity (25 minutes in Modules 1–4; 40 minutes in the Module 5 procedures sampled),
  Reflection/Plenary, and Self-Practice ("Refer to workbook page").
- Materials throughout are concrete and low-cost: straws/sticks, bottle caps, pebbles,
  beans, bundles of tens, number charts/frames, number wheels, place-value mats/frames,
  graph sheets, token currency notes.
- Held-copy slips in the front matter (all three level files): the running head on the
  acknowledgement page (PDF p. 6) reads "Mathematics Teachers Guide for Lower Primary"
  inside an Upper Primary guide; the introduction (PDF p. 11) says "The English Teachers
  guide for each level has 16 lessons for each term" inside a Mathematics guide; the
  closing Glossary (PDF p. 278/277) is a reading glossary (DRTA, DRA, K-W-L, story map),
  not a mathematics glossary. None of these affects the lesson content.
- Held-copy defect: one near-blank back-matter page in each file (PDF p. 276 in the
  Level 1 and Level 2 files, PDF p. 275 in the Level 3 file), inside the back matter
  before the glossary ends. No lesson or activity content is lost.

### DL module map — distinct lesson content is Modules 1–5 (80 lessons)

Each module has the same weekly shape in Modules 1–3: Weeks 1–3 counting/representation, place value
and comparing/ordering; Weeks 4–5 addition and subtraction; Weeks 6–8 multiplication,
division and word problems. Modules 4–5 compress it: Module 4 puts place value and
comparing/ordering together in Week 1, then addition (Week 2), subtraction (Week 3),
word problems (Week 4), multiplication (Week 5), multiplication word problems (Week 6),
division (Week 7), division word problems (Week 8); Module 5 likewise gives word-problem
weeks at Weeks 4–5. The number size grows module by module. Most lesson pairs
(Lesson 1 / Lesson 2 of a week) repeat the same Big Idea with a different activity, so
the two lessons of a week are filed together below — exceptions where a pair splits two
topics are Module 1 Week 6 (addition / subtraction word problems), Module 3 Week 7
(multiplication / division), Module 4 Week 1 and Module 5 Week 1 (place value /
comparing-ordering).

MODULE 1 (in the Level 1 file only; PDF pp. 13–44 in the Level 1 file)
- Week 1: Counting numbers 1–50; counting and number names 0–100 (number chart, bundles).
- Week 2: Place value of 2-digit numbers (tens and ones; bundles and loose ones).
- Week 3: Comparing 2-digit numbers with <, > and =.
- Week 4: Adding a 1-digit number to a 2-digit number, with regrouping.
- Week 5: Subtracting a 1-digit number from a 2-digit number, with regrouping.
- Week 6: Addition word problems (two 2-digit numbers); subtraction word problems
  (two 2-digit numbers).
- Week 7: Multiplication of two 1-digit numbers (groups).
- Week 8: Division of a 2-digit number by a 1-digit number (sharing/grouping).

MODULE 2 (in the Level 1 and Level 2 files; identical lesson text apart from printed
page numbers)
- Week 1: Number names, numeral recognition and counting sequence 0–999 (number frame,
  number chart 1–1,000).
- Week 2: Place value of 3-digit numbers.
- Week 3: Comparing and ordering 3-digit numbers with <, > and =.
- Week 4: Addition of two 2-digit numbers (sums up to 99).
- Week 5: Subtraction of two 2-digit numbers.
- Week 6: Multiplication of a 2-digit number by a 1-digit number.
- Week 7: Multiplication of a 2-digit number by a 1-digit number (second activity pair).
- Week 8: Division of a 2-digit number by a 1-digit number.

MODULE 3 (in all three level files; identical lesson text apart from printed page numbers)
- Week 1: Modelling number quantities with graph sheets and token currency; number
  names, recognition and counting sequence 0–1,000.
- Week 2: Place value of a digit in 4-digit numbers.
- Week 3: Comparing and ordering 4-digit numbers with <, > and =.
- Week 4: Addition of 2- and 3-digit numbers (sums up to 9,999), including addition on
  the number chart.
- Week 5: Subtraction of a 2-digit number from a 3-digit number.
- Week 6: Multiplication of two 2-digit numbers (first week) — note the section header
  on the Week 6 Lesson 2 page reads "Addition and Subtraction" above a multiplication
  lesson; the lesson's own Big Idea and outcomes are multiplication (minor header slip).
- Week 7: Multiplication of a 3-digit number by a 1-digit number; division of a 2-digit
  number by a 1-digit number.
- Week 8: Division of a 3-digit number by a 1-digit number.

MODULE 4 (in the Level 2 and Level 3 files; identical lesson text apart from printed
page numbers)
- Week 1: Place value of numbers up to 10,000; comparing and ordering numbers up to
  10,000 in ascending and descending order.
- Week 2: Addition of 3-digit numbers (sums up to 999).
- Week 3: Subtraction of two 3-digit numbers.
- Week 4: Modelling addition word problems; modelling subtraction word problems.
- Week 5: Multiplication of a 3-digit number by a 1-digit number.
- Week 6: Multiplication word problems (3-digit by 1-digit).
- Week 7: Division of a 3-digit number by a 2-digit number.
- Week 8: Division word problems (3-digit by 2-digit).

MODULE 5 (in the Level 3 file only)
- Week 1: Place value of numbers 100,000–1,000,000 (Big Idea as headed; outcomes cover
  0–100,000, comparing and ordering to 100,000); comparing and ordering numbers up to
  100,000.
- Week 2: Addition of a 3-digit number to a 4-digit number (sums up to 9,999).
- Week 3: Subtraction of 3-digit numbers from 4-digit numbers. (Minor heading slip: the
  Week 3 Lesson 1 Big Idea is headed "Addition sum up to 999" although its outcomes are
  subtraction.)
- Weeks 4–5: Addition word problems; subtraction word problems (two parallel weeks).
- Week 6: Multiplication word problems (3-digit by 2-digit).
- Week 7: Division of a 3-digit number by a 2-digit number.
- Week 8: Division word problems (3-digit by 2-digit).

### DL Activity Book (shared, identical in all three level files)

Printed pp. 103–265; PDF pp. 115–275 (Level 1 and Level 2 files) / PDF pp. 114–274
(Level 3 file). Teacher-led group activities that the lesson plans point to. Filed by
activity, in order:

- Activities 1A–1C: Counting and representation 0–100 (bundles of tens and loose ones);
  modelling number quantities 1–1,000.
- Activity 2: "Guess My Number" game (estimating and counting objects).
- Activities 3A–3C: Number names, recognition and counting sequentially (number chart,
  number-square puzzle).
- Activities 4A, 4B, 4D: Place value of 2-digit numbers; making bundles of hundreds,
  tens and ones; place value of numbers 1–10,000 (worked example: 9,042 as "nine
  thousand and forty-two").
- Activities 5A–5E: Modelling and comparing numbers with the number wheel; comparing
  3-digit numbers; modelling/comparing 4-digit numbers; place value of 4-digit numbers
  (pebble-and-circle game); comparing and ordering numbers 1–10,000; comparing 5- and
  6-digit numbers.
- Activities 6A–6E, 7A–7C, 8C, 8E, 9D: Addition — addition frame (1-digit + 2-digit;
  two 2-digit; whole numbers on the frame), number-card game, friendly-jump method on
  the number line, numeral-chart addition, expanded method and decomposition
  (e.g. 457 + 349; 8,457 + 649).
- Activities 10A–10E, 11A, 11B, 11D1, 11D2, 12C–12E, 13E: Subtraction — subtraction
  frame, number-chart subtraction, decomposition/expanded method (e.g. 427 − 349;
  1,427 − 349), friendly jumps on the number line, everyday-life (word) problems
  (e.g. money, mangoes shared among friends).
- Activities 14A, 15A, 16A–16C: Multiplication — group formation (3 groups of 4),
  multiplication tables/charts, 2-digit by 1-digit, 2-digit by 2-digit.
- Activities 17B1, 17B2, 17D, 17E: "Expand and Box" (partial decomposition) method for
  2-digit by 2-digit and 3-digit by 1-digit multiplication (e.g. 815 × 34).
- Activities 18B–18E: Lattice method for 2-digit and 3-digit multiplication
  (e.g. 383 × 4; 119 × 3) and multiplication word problems (3-digit by 1-digit).
- Activities 19A–19C, 20A, 20B, 21B, 21D: Division — grouping/sharing of 2-digit by
  1-digit numbers, including remainders (e.g. 18 ÷ 7 gives 2 remainder 4); division as
  the inverse of multiplication; division word problems (3-digit by 1-digit).
- Activities 22B–22E: Division as repeated subtraction (e.g. 135 − 45 − 45 − 45 = 0).
- Activities 23C–23E: Division by the "Big 7" / scaffolding method for 3-digit by
  1-digit and 3-digit by 2-digit division, including word problems.
- Mental Maths Activities (printed p. 266): "Guess My Number", "Thinking of a number:
  Ones and Tens", "Describing Numbers in Equivalent Ways", "5 more or less than",
  "Doubles", "1 more than double of / 1 less than double of", "Skip Count" (2s, 5s, 10s),
  "Chicken and Legs", "Pairs that sum to 10/20", "Find number to make 100 with …".

### DL honest negatives

- The DL guides teach no fractions, decimals, percentages, ratios, algebra, shapes,
  measurement, time, or data handling at any level or module. A learner taught only from
  these guides would meet none of the curriculum's Algebra, Geometry and Measurement,
  or Data strands.
- The guides never state a grade (B4, B5 or B6) for a module: modules are ability levels,
  not grades. The filing of the same file under Grades 4, 5 and 6 reflects the span
  (Basic 4~6), not a grade split inside the book.
- The lesson plans constantly refer the learner to "workbook page" for self-practice,
  but the workbook in the set is only the Level 1 workbook (see section 3); there is no
  workbook in the set keyed to Levels 2 or 3 or to Modules 4 or 5.

## 3. DL-WB-UPPER-L1 — DL Mathematics Workbook for Upper Primary, Level 1 (Learner's Workbook)

- File: grade4_student-workbook.pdf (duplicate rows: grade5, grade6 student-workbook
  filings).
- Cover: "Differentiated Learning (DL) MATHEMATICS WORKBOOK FOR UPPER PRIMARY — LEVEL 1
  — LEARNER'S WORKBOOK", Basic 4–6, Ghana Education Service (GES) with UNICEF.
  Title page (PDF p. 2) repeats Level 1. Copyright © MoE/GES 2020 (PDF p. 3), ISBN
  printed only as placeholder "ISBN XXX-XXXX-XXXX-X-X". Writers (PDF p. 3): Isaac
  Buabeng, Francis Martey Asare, Edward Mills, Eric Osei-Adolfo, Reginald Quartey,
  Anita Cordel Collison.
- Pages: 65 PDF pages. Body pages are one raster image per page with NO text layer —
  read here as page pictures (rendered and inspected page by page; OCR used only as a
  cross-check). PDF p. 5 is a blank leaf inside the front matter; PDF p. 65 is a solid
  red trailing page with no text or tasks. Neither loses content: the task pages run
  unbroken around them.
- Proved kind: STUDENT WORKBOOK — task sheets for the learner to write in, not a pupil
  textbook with taught explanations. Each lesson opens with a worked example and then
  sets tasks (fill the chart, draw the dots, write the sentence, solve in the box).
- CORRECTION TO THE BRIEF: this file is NOT "Module 1 only". Its own Table of Content
  (PDF p. 4) lists Modules 1, 2 and 3, and all three modules are present in the file:
  Module 1 (PDF pp. 6–25), Module 2 (PDF pp. 26–45), Module 3 (PDF pp. 46–64). Printed
  page numbers restart at each module (Module 1 printed pp. 1–20; Module 2 printed
  pp. 21–40; Module 3 printed pp. 1–19). What is genuinely absent is workbook Levels 2
  and 3 — this is the Level 1 workbook, matching the teacher-guide Level 1 file's
  Modules 1–3.
- Held-copy defects in this file: the Table of Content's Module 2 lesson page numbers
  (7, 10, 12, 14, 16, 20, 22, 24) do not match Module 2's actual printed pagination
  (divider printed p. 21, lessons printed pp. 22–40; Lesson 1 opens on printed p. 22,
  PDF p. 27). Module 1 and Module 3 Table of Content numbers do match their modules.
  Two worked-task misprints, answers unaffected: Module 2 Lesson 8's repeated-subtraction
  chain prints "17 − 6 = 6" for its third step (should be 12 − 6 = 6); Module 3 Lesson 7's
  lattice summary prints "So, 384 x 4 = 1532" although the lattice worked is
  383 × 4 = 1,532.
- Task types throughout: number charts (100-chart and 1,000-chart), place-value mats
  (tens/ones, then hundreds/tens/ones, then thousands/hundreds/tens/ones), number wheels
  (pebble dots for tens/ones, then hundreds, then thousands), bundles-and-loose
  drawings, addition/subtraction frames, friendly jumps and number-line jumps, number
  charts for multiplication tables (up to 12 × 12), lattice boxes, "Expand and Box"
  boxes, grouping drawings, repeated-subtraction chains, "Big 7" scaffolding layouts,
  and word problems with a blank working box. Ghanaian contexts recur: cedi notes and
  coins, mangoes, market selling, Basic 5 class sizes, farm workers' pay.

MODULE 1 — 8 lessons (PDF pp. 6–25; Activities 1A, 4A, 5A, 6A, 10A, 14, 20 as labelled
in the workbook)
- Lesson 1, Counting and Representing Numbers: circle numbers on the 100-chart; complete
  the number chart; count items in boxes; tens/ones bundles; cross out to show 43;
  number-wheel tasks ("What number does the wheel represent?", e.g. wheel showing 32;
  draw pebbles to show 34 and 71).
- Lesson 2, Place value of 2-digit numbers: tens/ones charts from straw bundles and star
  groups ("How many tens and ones can we make?").
- Lesson 3, Comparing 2-digit numbers using <, > or =: compare bundle groups, number
  wheels, and place-value charts (e.g. 79 against 91).
- Lesson 4, Adding 1-digit numbers to 2-digit numbers: bundle addition, addition frame,
  number-chart addition (e.g. 72 + 6, 88 + 4, 25 + 9), column problems (e.g. 34 + 4).
- Lesson 5, Subtracting a 1-digit number from a 2-digit number: subtraction frame,
  number-chart subtraction (e.g. 48 − 5 = 43; 61 − 8), column problems (e.g. 39 − 4).
- Lesson 6, Solving addition and subtraction word problems: market and classroom problems
  (e.g. meat sold at Kotokoraba market, 35 kg + 9 kg; 51 pupils + 7 new pupils; 60
  mangoes, 9 sold; 37 pupils, 8 taken out).
- Lesson 7, Multiplication of 1-digit by 1-digit number: write the multiplication sentence
  for groups of items; ladder (crossed-lines) strategy (e.g. 2 × 3 = 6); number-chart
  multiplication (tables to 12 × 12; e.g. 9 × 7, 6 × 11, 11 × 6).
- Lesson 8, Division of a 2-digit number by a 1-digit number: draw to show the division
  sentence (e.g. 18 ÷ 9); ladder strategy (e.g. 20 ÷ 4); repeated subtraction
  (e.g. 20 ÷ 4 by subtracting 4 five times); word problems (15 oranges shared among
  5 people; cars carrying 4 persons at a time for 20 persons; write a word problem for
  12 ÷ 2).

MODULE 2 — 8 lessons (PDF pp. 26–45; Activities 1B, 4B, 5B, 6B2, 10B, 14B, 18, 19)
- Lesson 1, Number names, numeral recognition, and counting in sequence: place-value
  mats to 3 digits (e.g. 1 hundred, 3 tens, 6 ones = 136); fill missing numbers on
  sequences (210, 260, 310 …; counting backwards 47, 44, 41 …); rearrange numbers into
  a 100–990 chart from smallest to biggest; complete the number chart.
- Lesson 2, Place value of 3-digit numbers: hundreds/tens/ones mats.
- Lesson 3, Comparing and ordering 3-digit numbers using <, > or =: compare mats and
  number wheels; compare numerals directly (e.g. 314 against 298; 357 against 509;
  570 against 909).
- Lesson 4, Addition of two 2-digit numbers: addition mat with bundles; number-wheel
  addition; number-chart addition (e.g. 24 + 5 = 29; 45 + 11); column problems
  (e.g. 64 + 15; 38 + 61; 26 + 39; 45 + 19).
- Lesson 5, Subtraction of two 2-digit numbers: subtraction mat (e.g. 56 − 41); number-
  chart subtraction (e.g. 48 − 5; 61 − 8; 99 − 29).
- Lesson 6, Multiplication — 2-digit number by 1-digit number: grouping strategy
  (e.g. groups of 12); number-chart multiplication (e.g. 12 × 9); "Expand and Box"
  strategy (e.g. 48 × 6 = 288; 55 × 5; 63 × 4).
- Lesson 7, Multiplication and division problems: lattice method for 2-digit by 1-digit
  multiplication (e.g. 38 × 4 = 152; 22 × 5; 14 × 9).
- Lesson 8, Divide a 2-digit number by a 1-digit number: grouping (e.g. 12 straws in
  3s; 35 items in 5s; 72 paper clips); repeated subtraction with counting boxes
  (e.g. 18 ÷ 3; 21 ÷ 7 = 3; 24 ÷ 6 = 4); word problems (44 ÷ 4; write a word problem
  for 80 ÷ 10).

MODULE 3 — 8 lessons (PDF pp. 46–64; Activities 1C, 5C, 6C, 10C, 17B, 18C, 23)
- Lesson 1, Modeling number quantities using Ghanaian currency: value each cedi
  denomination in a pictured set of notes (worked total: GH¢465 from 1 × GH¢5,
  3 × GH¢20, 2 × GH¢50, 1 × GH¢100, 1 × GH¢200 — as printed, the parts as listed sum
  to GH¢465 in the book's own working); write the value of each denomination and the
  total for new sets; complete the number chart (10s to 900s).
- Lesson 2, Place value of a digit in 4-digit numbers: place-value mats with thousands
  (e.g. 1 hundred, 2 tens, 9 ones = 129 in the worked example; 4-digit mats in the
  tasks).
- Lesson 3, Comparing and ordering 4-digit numbers: number wheels with thousands/
  hundreds/tens/ones rings against place-value charts (e.g. wheel = 1,301; chart 2,006;
  chart 4,122).
- Lesson 4, Addition of a 2- and 3-digit numbers: addition mats (hundreds/tens/ones)
  and number-wheel addition.
- Lesson 5, Subtraction of a 2-digit number from a 3-digit number: subtraction mats
  and number-wheel subtraction.
- Lesson 6, Multiplication of a 2-digit number by a 2-digit number: "Expand and Box"
  method (worked: 76 × 34 = 2,584; tasks 34 × 21; 60 × 35) and word problems by the
  same method (21 times as many fowls as a brother's 35; 15 books on each of 22
  shelves).
- Lesson 7, Multiply a 3-digit number by a 1-digit number: lattice method (worked:
  383 × 4 = 1,532; tasks 120 × 4; 455 × 6) and word problems by "Expand and Box"
  (231 rows of 9 sunflowers).
- Lesson 8, Division of 3-digit numbers by a 1-digit number: "Big 7" scaffolding
  strategy (worked: 318 ÷ 3 = 106; tasks 120 ÷ 6; 279 ÷ 9) and division word problems
  by any appropriate strategy (GH¢240 shared among 8 workers; 125 Basic 4 pupils in
  5 equal groups).

### Workbook honest negatives

- No fractions, decimals, percentages, algebra, shapes, measurement, time, or data work
  anywhere in the workbook — it is number-only, like the guides it serves.
- No answers are printed for the learner tasks (worked examples carry answers; the
  tasks themselves are blank for the learner). No teaching text explains a method
  before the tasks: the explanation lives in the teacher guide, not here.
- The workbook's Module 2 and Module 3 lessons go beyond the teacher-guide Level 1
  lesson range in one respect: they practise 3-digit place value, 2-digit by 2-digit
  multiplication and 3-digit division, which the Level 1 guide's Modules 1–3 also
  introduce — the two books are consistent companions for Modules 1–3, not for
  Modules 4–5 (for which no workbook is in the set).

## 4. JICA-B4 — JICA Primary Mathematics Teacher Manual B4

- File: grade4_teacher-manual.pdf. No duplicate rows (grade-specific volume).
- Cover: "JICA Primary Mathematics Teacher Manual B4". Developed by the National STEM
  Resource Unit in GES in collaboration with JICA. April 2025; piloted March 2023–
  July 2024. No copyright page and no ISBN in this file version (contrast B5/B6,
  which carry © 2025 GES and a placeholder ISBN).
- Pages: 134 PDF pages — front matter (PDF pp. 1–9), 120 numbered lessons (PDF pp.
  10–129), 5 Annual Review lessons (PDF pp. 130–134). One lesson per page.
- Lesson design (front matter, PDF pp. 2–9): two lesson types — normal lessons (new
  curriculum topics) and review lessons (the previous four lessons); review lessons
  are the lessons numbered in multiples of 5; a week is four normal lessons plus one
  review lesson; 120 lessons in a year. Each lesson page has five parts: (1) basic
  information (lesson number, corresponding curriculum page, objective, sample
  introduction activities, teaching tips, teacher's notes); (2) title and Exercise
  Part 1 (tasks [1]/[1A]/[1B]; the first sub-task is the evaluation task — if more
  than half the class cannot solve it, the teacher re-explains); (3) Exercise Part 2
  (tasks [2]/[2A]/[2B]; [R] = a task from the previous lesson); (4) Mental Maths
  (memorise addition facts to 20 and multiplication tables to 9 × 9); (5) Homework
  (sample tasks). Lesson conduct: Introduction (15 min, "Show me how"), Exercise
  Part 1 (15 min, "Help me do it"), peer marking (5 min), Exercise Part 2
  ("Let me do it"), Mental Maths. Review lessons: 30 minutes of independent test
  work, then peer marking; no introduction, no homework. Scheme of Work (PDF p. 8)
  paces the 120 lessons from late September to 30 June and says: if behind schedule,
  skip the review lesson, never a normal lesson. A lesson observation sheet is on
  PDF p. 9.
- This file version has no contents page; the strand/lesson map below is derived from
  the lesson headers themselves. Curriculum references on each lesson page point to
  the NaCCA B4–B6 curriculum (e.g. "Curriculum B4.1.1.1.1 (p. 2)").
- Teaching content, by lesson block (normal lessons; every 5th lesson is a review of
  the previous four):
  - Lessons 1–27, Counting, Representation, Cardinality and Ordinality: modelling
    numbers with multi-base diagrams (e.g. 2,400; 32,100); number names and numerals
    to 100,000 (e.g. 23,456); rounding (e.g. 14,500 to the nearest thousand = 15,000);
    multiplication-fact groundwork (2 × 3 by fence/array diagrams; double and half).
    Includes the curriculum's square-number/odd-number relationship material in the
    counting block (B4.1.1.3).
  - Lessons 28–52, Number Operations: decomposing multiplication with diagrams; box
    method (e.g. 214 × 3 = 642; box method flagged as preparation for the column
    method in Basic 5); multiplication and division facts and their inverse
    relationship; division with and without remainders.
  - Lessons 53–61, Fractions: equivalent fractions by folding paper strips
    (1/2, 1/4, 1/8); locating improper and mixed fractions on a number line
    (Lesson 56: draw a number line as shown on the board, then teach the terms
    improper and mixed fractions).
  - Lessons 62–73, Decimal fractions: tenths on the number line (e.g. 5 tenths = 0.5);
    converting decimal fractions to common fractions and vice versa (e.g. 0.5);
    adding decimal fractions (e.g. 1.2 + 2.3 = 3.5; 4.7 + 2.8 = 7.5, Lesson 69) and
    subtracting decimal fractions (e.g. 2.5 − 1.3 = 1.2; 4.7 − 2.8 = 1.9, Lesson 71).
  - Lessons 74–77, Percentage: recognising percent in relation to decimal fractions
    ("cent means 100"); converting decimal and common fractions into percentages.
  - Lessons 78–88, Algebra: patterns in a hundred chart (skip counting by 2s–9s);
    patterns in tables (increasing by 3 with bottle tops); equations by pan-balance
    comparison, guess-and-check, and part-part-whole number bonds
    (e.g. 4 + P = 6; Q + 15 = 21; 15 − X = 8).
  - Lessons 89–107, Geometry and Measurement: symmetry (fold-and-cut paper; lines of
    symmetry of regular and irregular 2D shapes; completing symmetrical figures);
    coordinates (coordinate plane as pairs of numbers for a point's position);
    perimeter of polygons (measuring classroom objects; drawing rectangles of given
    perimeter, e.g. perimeter 20 cm); area (estimating with 1 cm² and 1 m²; area of
    rectangles and combined rectangles, e.g. find the area: 6 × 2 = 12, 12 cm²
    (Lesson 99); draw a rectangle of width 3 cm and area 21 cm² (Lesson 101); three
    rectangles of perimeter 20 m with widths 2, 4 and 5 m have lengths 8, 6 and 5 m
    and areas 16, 24 and 25 m² (Lesson 102)); time (reading analogue and digital clocks, 12-hour and 24-hour, "quarter
    past"/"half past"; durations by column method, e.g. 2:25 to 6:55, 5:40 to 13:15).
  - Lessons 108–115, Data: pictographs (one-to-one and many-to-one correspondence;
    e.g. fruit counts for Ama); bar graphs (drawing a bar graph from a table step by
    step, title and labelled axes; pictograph versus bar graph, e.g. animals on a farm
    with each grid = 10).
  - Lessons 116–119, Revisit: multiplication/division catch-up (box method for
    34 × 27; multiplication facts) explicitly flagged to be taught before later work.
  - Lesson 120: final review lesson.
  - Annual Review Lessons 1–5 (PDF pp. 130–134): no teaching tips, no mental maths;
    objective in each case is to ensure understanding of the topics learnt in B4.
    Review 1 covers adding/subtracting fractions with same and different denominators;
    the remaining reviews revisit the year's operations, fractions, decimals and
    area/perimeter work in the same sample-task format.
- B4 honest negatives: no ratio/proportion block (that arrives in B6); no probability
  block (B4 data is pictographs and bar graphs only — the curriculum's B4 data
  sub-strand has no Chance section, and the manual matches that); no angle measurement
  block (angles arrive in B5); no volume/capacity block (arrives in B5); no integers-
  operations block (negative values are introduced in Lesson 27 inside the counting
  block; adding and subtracting integers is B5's topic). The manual's mental-maths items are the only
  repeated drill: they are addition/subtraction and multiplication facts, not new topics.

## 5. JICA-B5 — JICA Primary Mathematics Teacher Manual B5

- File: grade5_teacher-manual.pdf. No duplicate rows (grade-specific volume).
- Cover: "JICA B5 Primary Mathematics Teacher Manual". Developed by the GES National
  STEM Resource Unit in collaboration with JICA mathematics specialists from Japan;
  acknowledgements (PDF p. 4) thank Prof. Ernest Kofi Davis (Director-General of GES),
  the National STEM Coordinator for mathematics, pilot-school teachers, and the People
  and Government of Japan. © 2025 GES (PDF p. 3); ISBN printed only as placeholder
  "ISBN:XXXX" — no real ISBN. April 2025; piloted March 2023–July 2024 (same series
  note as B4). "About the Book" (PDF p. 137): written in alignment with the NaCCA
  curriculum, for teachers delivering high-quality lessons.
- Pages: 137 PDF pages — front matter and contents (PDF pp. 1–11), 120 numbered
  lessons (PDF pp. 12–131), 5 Annual Review lessons (PDF pp. 132–136), About the Book
  (PDF p. 137). Same five-part lesson design, review-every-5th-lesson rhythm, timing,
  peer marking and mental-maths regime as B4. Contents page (PDF p. 5, printed p. iv)
  lists the strand/lesson map used below; it matches the actual lesson headers in
  this volume, except that its Data entry reads Lesson 107 while table-interpretation
  (data) content already starts at Lesson 106.
- Teaching content, by lesson block:
  - Lessons 1–20, Counting, Representation, Cardinality and Ordinality: modelling
    numbers to 1,000,000 with multi-base diagrams (e.g. 24,000; 321,000); number names
    and numerals to 1,000,000; place value to 1,000,000.
  - Lessons 21–28, Multiplication: multiples of 10s, 100s and 1,000s with cedi notes
    (e.g. 3 × 20; 4 × 50; 80 × 500 = 40,000 by the book's working pattern); column
    method preparation and use.
  - Lessons 29–40, Division: division through multiplication tables (e.g. 6,000 ÷ 2 =
    3,000; 4,200 ÷ 6 = 700); division with remainders; long-division groundwork.
  - Lesson 41 (single-lesson block before fractions), Integers: adding and subtracting
    simple integers on a number line (e.g. 2 − 3 = −1; −2 + 4 = 2; −2 − 2 = −4;
    3 − 7 = −4).
  - Lessons 42–53, Fractions: equivalent fractions of three numbers by listing the
    multiples of the biggest denominator and checking which multiples the other
    denominators divide (e.g. 1/3, 2/5, 1/6 → 10/30, 12/30, 5/30; 1/2, 2/3, 1/4 →
    6/12, 8/12, 3/12); comparing, adding and subtracting fractions with different
    denominators. The teacher's note says the curriculum term "lowest common
    denominator" is used but learners need not memorise it. (Prime factorising for
    denominators 4, 6 and 20 is the CURRICULUM's method, B5 PDF p. 90 — not this
    lesson's.)
  - Lessons 54–68, Decimal fractions: thousandths with a 10 × 10 square (each cell
    0.001; a row 0.01); adding and subtracting decimal fractions (e.g.
    0.025 + 0.013 = 0.038, Lesson 62; 0.025 − 0.013 = 0.012, Lesson 63).
  - Lessons 69–72, Percentage: converting a percentage to a common fraction and finding
    a given percentage of a number (e.g. 40% and 25% of a number, with diagrams).
  - Lessons 73–78, Patterns and Relationships: extending patterns (increase by 10/50/500,
    decrease by 20/1000; chart patterns including diagonals, Lesson 73; add 0.5,
    subtract 3, add 0.25, add 50, Lesson 76; multiply/divide patterns, Lesson 77;
    divide-by-2 chain 560, 280, 140, 70, 35, Lesson 78).
  - Lessons 79–85, Algebraic Expressions: simplifying expressions with an unknown
    (integer review on a number line first — NOTE: the book's Lesson 79 introduction
    sample misprints "−3 + 4 = −1"; the correct value is 1. Verified tasks on the
    same page: −5 + 3 = −2; −1 − 3 = −4; −1 + 8 = 7);
    rules for patterns in expressions (e.g. difference 6, test 6n).
  - Lessons 86–88, Variables and Equations: solving linear equations by adding or
    subtracting, by manipulatives and by guess-and-check (e.g. 3 + p = 5, p = 2;
    6 − p = 2, p = 4).
  - Lessons 89–91, 2D and 3D Shapes: characteristics of quadrilaterals (sides, angles,
    diagonals, congruence, bisecting).
  - Lessons 92–100, Measurement — Perimeter, Area and Capacity/Volume: estimating and
    finding perimeters of objects around the learner; 1 cm² and 1 m² sense of quantity;
    area of rectangles and combined rectangles; volume sense with a 1 m³ cube made
    from twelve 1 m ropes/sticks; volume of 3D shapes by formula (e.g. which is bigger?
    2 × 2 × 2 = 8, 3 × 1 × 3 = 9, 2 × 2 × 6 = 24, 3 × 3 × 3 = 27, Lesson 98).
  - Lessons 101–102, Measurement — Angle: types of angles (definitions written on the
    board; angles found around the learner — door, scissors; changes in angle
    demonstrated).
  - Lessons 103–105, Geometric Reasoning: position and direction of objects (e.g. from
    home (H): school (S) 3 steps east, post office (P) 2 steps south, bus stop (B)
    1 step south 2 steps west, kiosk (K) 2 steps north 3 steps east; from school (S):
    home (H) 3 steps west, church (C) 1 step north 2 steps west, post office (P)
    2 steps south 3 steps west, Lesson 103; reflected image, Lesson 104; review,
    Lesson 105).
  - Lessons 106–111, Data: first-hand versus second-hand data (league tables: played
    − win − draw = lost); interpreting and drawing bar graphs and double bar graphs
    (e.g. rainfall by month; graphs from newspapers/magazines).
  - Lessons 112–113, Chance (Probability): likelihood of a single outcome as certain
    (probability 1), possible, or impossible (probability 0) — die-throwing examples
    (obtaining 5 is possible; obtaining 7 is impossible; obtaining 1–6 is certain).
  - Lessons 114–119, Catch-up/revisit: common factors/HCF and LCM of three numbers
    (e.g. 12, 20, 30; teacher's note: learners will learn perfect numbers in B8, so
    this is only an introduction); operations and patterns revisit.
  - Lesson 120: final review lesson.
  - Annual Review Lessons 1–5 (PDF pp. 132–136): column method (e.g. 36 × 47 = 1,692;
    72 × 30 = 2,160); long division (e.g. 619 ÷ 3 = 206 remainder 1; 214 ÷ 6 = 35
    remainder 4); fraction addition (same and different denominators); fraction
    multiplication; addition/subtraction of decimal fractions. No teaching tips, no
    mental maths.
- B5 honest negatives: no ratio/proportion block (B6's topic); no prisms/nets or
  translation block (B6's geometry; reflection is introduced here, Lesson 104); no line graphs (line graphs arrive in
  B6 data); no experimental probability (B6's probability block — B5 probability is
  likelihood words only).

## 6. JICA-B6 — JICA Primary Mathematics Teacher Manual B6

- File: grade6_teacher-manual.pdf. No duplicate rows (grade-specific volume).
- Cover: "JICA B6 Primary Mathematics Teacher Manual". Same imprint, acknowledgements,
  © 2025 GES and placeholder "ISBN:XXXX" as B5; same April 2025 / pilot March 2023–
  July 2024 series note; same "About the Book" (PDF p. 137). 137 PDF pages — front
  matter (PDF pp. 1–11), 120 numbered lessons (PDF pp. 12–131), 5 Annual Review
  lessons (PDF pp. 132–136), About the Book (PDF p. 137). Same five-part lesson design
  and review rhythm as B4/B5.
- CONTENTS-PAGE WARNING: the contents page in this file (PDF p. 5) is a copy of the B5
  contents page, not a map of this volume. It lists Fractions at Lesson 42, Decimal
  fractions at 54, Percentage at 69, 2D and 3D Shapes at 89, Perimeter/Area/Capacity at
  92, Angle at 101, Geometric Reasoning at 103, Data at 107 and Probability at 112.
  The actual B6 lesson headers differ from the copied map at most points: division
  starts at Lesson 27 (not 29) and integers run Lessons 38–41 (not a single Lesson 41);
  fractions start at Lesson 42 — "Make the denominators the same" — so the copied
  "Fractions Lesson 42" happens to be right, while the "decimal fractions" and
  "percentage" blocks do not exist as such — Lessons 57–70 are Ratios and Proportion
  (the curriculum's B6.1.4); patterns start at Lesson 73 (which the copy also lists,
  correctly, as Patterns); geometry is prisms Lessons 88–92 and position/transformation
  Lessons 93–98 (not "2D and 3D Shapes 89 / Perimeter-Area-Capacity 92 / Angle 101 /
  Geometric Reasoning 103"); data starts at Lesson 99, not 107; probability starts at
  Lesson 109, not 112. The lesson map below follows the
  lesson headers, not the contents page. (See Record correction 3.)
- Teaching content, by lesson block:
  - Lessons 1–20, Counting, Representation, Cardinality and Ordinality: modelling
    numbers to 1,000,000 with multi-base diagrams (same opening as B5, e.g. 24,000;
    321,000, Lesson 1); number names, place value and ordering extending to billions
    (place-value table to 1,000,000,000 and the number name 1,234,560,000, Lessons 3–4;
    expansion up to 10 billion, Lesson 6); rounding and comparing large numbers.
  - Lessons 21–26, Number Operations — Multiplication: (3-digit) × (1-digit) by the
    column method (with the note not to draw the dotted place-value line in the last
    example); multiplication facts applied to larger numbers. (Lesson 27 is already
    division: "Solve division out of 9×9".)
  - Lessons 27–41, Number Operations — Division and Integers: division out of 9×9
    (Lesson 27); division with remainder
    (e.g. 14 chocolates, 3 per child, Lesson 28); money problems (e.g. 7 papayas at ¢8, paid
    ¢60 — change ¢4, Lesson 36 introduction); comparing integers (Lesson 38);
    adding/subtracting integers on the number line (Lesson 39); (positive number) ×
    (negative numbers) with the rule to be found by learners (Lesson 41).
  - Lessons 42–56, Fractions: making denominators the same (e.g. 1/3 = 4/12;
    3/4 = 15/20; 3/5 = 18/30, Lesson 42); adding mixed fractions with the same denominator by
    converting mixed fractions (Lesson 43, flagged as a review of B5 to prepare for
    later lessons); comparing, adding, subtracting, multiplying and dividing common
    fractions (Lessons 44–56, B6.1.3.1.2–1.3.1.3).
  - Lessons 57–70, Ratios and Proportion: meaning and representation of ratio with
    concrete mixing (banku: 4 cups cornmeal, 2 cups cassava, 6 cups water, in
    same-size cups, no real filling needed); equivalent ratios (e.g. men:women 5:7 with
    45 men → 63 women, Lesson 63; boys:girls 7:11 with 28 boys → 44 girls, 72
    altogether); ratio in simplest form and its
    relationship to fractions and multiplication.
  - Lessons 71–72, Fractions revisit: comparing common and decimal fractions by
    converting a common fraction to a decimal by long division (e.g. 1/8 = 0.125
    terminating against 2/3 = 0.66… repeating; also 1/8 > 0.123, 2/3 < 0.7,
    1/6 > 0.16, Lesson 71).
  - Lessons 73–87, Algebra: geometric-pattern rules (edges rule Add 2: No. 7 = 15 edges;
    circles rule Add 3: No. 8 = 24 circles, Lesson 73; matchstick tables: perimeters
    3, 6, 9, 12, 15 with enclosed 0, 3, 9, 18, 30, and perimeters 7, 12, 17, 22, 27
    with enclosed 1, 4, 7, 10, 13, Lesson 74); algebraic expressions with an
    unknown; equations by manipulatives and by guess-and-check (e.g. 3 + x = 5,
    x = 2; x − 6 = 2, x = 8; x − 5 = 8, x = 13; 3x = 270, x = 90); word problems with
    an unknown (e.g. a tree 10 cm tall on day 1, growing 3 cm a day — write the
    expression); in sequence across Lessons 73–87: pattern rules (Lessons 73–74),
    expressions (Lessons 76–79), equations (Lessons 81–87).
  - Lessons 88–92, Geometry — Prisms: identifying rectangular and triangular prisms
    among classroom objects; drawing nets of rectangular and triangular prisms;
    constructing prisms from their nets.
  - Lessons 93–98, Geometry — Position and Transformation: position and direction
    (home → factory/market in steps north/east); reflection of a triangle (each
    vertex reflected to the opposite side); reflection across the x-axis, y-axis and
    line k (Lesson 94); translation by a vector, e.g. vector (5, −2), points A, B, C
    to A′, B′ … (Lesson 96); translate shape K 5 right 3 down and reflect shape L in
    the x-axis, with the properties that reflection preserves size and shape and
    translation preserves size, direction and shape (Lesson 97); identifying reflection
    versus translation (Lesson 98); "transformation" taught as the term covering both
    reflection and translation.
  - Lessons 99–108, Data: discrete versus continuous data (definitions and examples);
    drawing and interpreting line graphs from tables (e.g. rainfall in Accra by
    month; rainfall in Ghana); collecting data by interview in groups of 4 (age,
    shoe size, favourite drink); summarising data with tallies and tables.
  - Lessons 109–114, Chance (Probability): experimental probability — tossing a coin
    10 times and counting heads/tails (Lesson 109; the book's sample counts are head 7,
    tail 3 → 7/10); spinning an 8-sector spinner 20 times in groups, taking turns,
    recording with tallies (Lesson 111); listing possible outcomes (coin, die with a given
    number of sides, spinner with a given number of sectors) and determining
    theoretical probability, compared with experimental probability (Lessons 112–114).
  - Lessons 116–119, Catch-up/revisit: common factors of three numbers (HCF/LCM of 12,
    20, 30, same introduction note as B5: perfect numbers come in B8); operations
    revisit (Lesson 116 common factors, B6.1.2.3.1; Lesson 117 box method and Lesson 118
    lattice method, B6.1.2.2.1; Lesson 119 multiplication strategies, B6.1.2.1.1).
  - Lesson 120: final review lesson.
  - Annual Review Lessons 1–5 (PDF pp. 132–136): column method introduction samples (e.g. 218 × 34 = 7,412;
    382 × 856 = 326,992); long-division introduction samples (e.g. 66 ÷ 21 = 3 remainder 3; 348 ÷ 23 = 15 remainder
    3); fraction addition/subtraction and multiplication; equations (Annual Review 5 tasks:
    e.g. 4 + x = 15; x − 9 = 7). No teaching tips, no mental maths.
- B6 honest negatives: no percentage block (percentages were B5's topic; B6 replaces
  them with ratios); no perimeter/area/volume block and no angle-types block (those
  were B5's geometry — B6 geometry is prisms, reflection and translation only); no
  pictograph/bar-graph introduction (assumed from B4/B5 — B6 data starts at discrete/
  continuous data and line graphs); the contents page must not be used as this
  volume's map (see warning above).

---

## RECORD-ONLY: CURR-B46 curriculum section (not taught lessons)

What the document is: the official standards-based mathematics curriculum for Ghanaian
primary schools, Basic 4–6, issued by NaCCA under the Ministry of Education (September
2019). It states what learners should attain, with content standards, indicators and
exemplars, subject-specific practices and core competencies for each grade. It contains
no pupil lessons, no exercises for learners, and no teacher lesson scripts. Its content
is recorded here for reference only and must not be presented as book teaching.

Front matter (PDF pp. 1–18; printed pp. i–xviii):
- Rationale and philosophy (PDF pp. 5–6): mathematics as integral to everyday life and
  national development; inquiry-based, learner-centred teaching with hands-on and
  minds-on approaches.
- General aims (PDF pp. 5–6, eight aims in total, including pursuing further studies in
  mathematics and developing abstract, logical and critical thinking).
- Core competencies (PDF pp. 6–7): Critical Thinking and Problem Solving (CP), Personal
  Development and Leadership (PL), Digital Literacy (DL), and the other competencies of
  the national framework as listed in the document (communication, collaboration,
  creativity and related skills are carried in the practices/competencies columns of
  every standard table).
- Learning domains (PDF p. 7): Knowledge, Understanding and Application; Process Skills;
  Attitudes and Values. Attitudes listed (PDF p. 10) include commitment, tolerance,
  patriotism, flexibility in ideas, respect for evidence, reflection, comportment,
  co-operation, responsibility, environmental awareness and respect for the rule of law.
- Assessment (PDF p. 12): assessment FOR learning (ongoing, feedback to refine teaching)
  and assessment OF learning (summative); criterion-referenced assessment against a
  representative sample of indicators. The time-allocation paragraph on the same page is
  worded for "the Lower Primary level" (ten 30-minute periods a week) although it stands
  in this Basic 4–6 document — wording as printed.
- Pedagogy (PDF pp. 13–15): learning-centred classroom; differentiation (by task, by
  support, by outcome) and scaffolding (breaking tasks into smaller parts with support
  toward independence); the 4Rs (Reading, wRiting, aRithmetic, cReativity) as the
  progression focus (named in the foreword, PDF p. 3, and in the learning-centred
  pedagogy, PDF p. 13); ICT tools named include calculators, radios, cameras, phones,
  television sets, computers and Microsoft Office packages (PDF p. 15).
- Organisation (PDF pp. 15–17): strands = broad areas; sub-strands = topics within a
  strand; content standard = predetermined level of attainment; indicator = the
  milestone/expectation for the year; exemplar = guidance and suggested activities.
  Annotation codes read as grade.strand.sub-strand.standard.indicator (e.g. B4.1.1.1.1,
  as used from PDF p. 20).

Strands and scope (PDF pp. 17–18; printed pp. xvii–xviii). Four strands run through
B4–B6. Scope-and-sequence ticks confirm every sub-strand below is present in all three
grades except where noted:

- Strand 1, Number: Whole Numbers — Counting and Representation; Whole Numbers —
  Operations; Fractions — Representation and Relationship. (B6 adds a fourth Number
  sub-strand, Ratios and Proportion, which has no B4/B5 counterpart in the scope table.)
- Strand 2, Algebra: Patterns and Relationships; Functions and Unknowns; Expressions;
  Equations and Inequalities. (Grade sections label these as Patterns and Relationships;
  Unknowns/Expressions/Equations in B4; Algebraic Expressions and Variables and
  Equations in B5/B6 — same strand, evolving labels.)
- Strand 3, Geometry and Measurement: Lines and Shapes; Measurements; Geometrical
  Reasoning. (Grade sections split Measurements into Perimeter/Area, Capacity/Volume,
  Angle and Time according to grade.)
- Strand 4, Data: Data (Collection, Organisation, Interpreting, Analysis); Chance
  (Probability). (The scope table ticks Chance only at B5/B6 in one presentation and at
  all three grades in another; the grade sections settle it: B4 has Data only, B5 and
  B6 have Data plus Chance. The JICA manuals match the grade sections, not the looser
  scope tick.)

Grade sections (content pages; printed p. = PDF p. − 18):
- BASIC 4 (PDF pp. 19–71; printed pp. 1–53): Number — counting/representation/cardinality
  to 100,000 with multi-base materials and graph sheets (e.g. modelling 32,300; cedi
  notes to ¢10,000); number operations including basic multiplication facts and
  multiplication/division; fractions — unit fractions on a number line (e.g. one-eighth),
  equivalent and improper fractions; Algebra — patterns in tables/charts (hundred chart,
  skip counting by 2s–9s), unknowns/expressions/equations; Geometry and Measurement —
  2D/3D shapes and symmetry, position/transformation, perimeter and area, time;
  Data — one-to-one and many-to-one correspondence in graphs (e.g. favourite fruits of
  a P4 class).
- BASIC 5 (PDF pp. 72–130; printed pp. 54–112): Number — counting/representation to
  1,000,000 (multi-base: cube = 1,000, rod = 10,000, flat = 100,000, block = 1,000,000;
  e.g. modelling 436,000); fractions — equivalent fractions via lowest common
  denominator (prime factorising; e.g. denominators 4, 6, 20), comparing/adding/
  subtracting fractions; Algebra — pattern rules and predictions (skip counting in
  multiples of 20, 50, 500); expressions; variables and equations; Geometry and
  Measurement — quadrilaterals (squares, rectangles, trapezoids, parallelograms:
  sides, angles, diagonals), measurement of perimeter, area, capacity/volume and
  angle, geometric reasoning; Data — first-hand versus second-hand data (e.g. a class
  measuring rainfall for 5 days), data handling, and Chance: likelihood of a single
  outcome as impossible, possible or certain (Ludo die: obtaining 1 is possible,
  obtaining 7 is impossible, obtaining 1–6 is certain).
- BASIC 6 (PDF pp. 131–179; printed pp. 113–161): Number — counting/representation/
  cardinality/ordinality to 1,000,000 (and, as headed on the opening B6 counting page,
  to 1,000,000,000 in the standard's wording); mental strategies and number properties
  (skip counting from a known fact, doubling/halving, 9s and 11s patterns) for
  multiplication facts to 144 and related division facts; fractions — comparing and
  ordering a mixture of common, percent and decimal fractions to thousandths
  (e.g. ordering 0.758, a common fraction and 73% by converting to one form); Ratios
  and Proportion (new in B6: ratio as the number of times one quantity can be obtained
  in another, in simplest form, related to fractions and multiplication); Algebra —
  pattern rules verified visually (matchstick perimeters); expressions; variables and
  equations; Geometry and Measurement — prisms (rectangular/triangular, uniform cross
  sections) and geometric reasoning; Data — line graphs (title, axes, intervals; e.g.
  temperature over minutes) and Chance: listing all possible outcomes of an experiment
  (coin, die, spinner) and determining theoretical probability, distinguished from
  experimental probability.
- Back matter (PDF pp. 180–182): Mathematics Subject Panel Members and Reviewers
  (e.g. Prof. Eric Magnus Wilmot, University of Cape Coast) and Supervisors (including
  Felicia Boakye-Yiadom, former Executive Secretary, and Dr. Prince H. Armah, Acting
  Executive Secretary, NaCCA). No appendix of lessons or exercises follows.
- Curriculum defects/quirks: the Table of Contents (PDF p. 4) carries a Word artefact
  on the Foreword line ("Error! Bookmark not defined"); the B4 geometry section repeats
  a "Position/Transformation" sub-strand heading (PDF p. 56 and again PDF p. 64) after
  the Measurement–Time section; the scope table's Chance tick is inconsistent between
  its two presentations (see above) — the grade sections govern. No content pages are
  missing: all 182 PDF pages carry text except the footer-only trailing page (PDF p. 182).

## Band-level gaps (what this band does NOT contain)

- No pupil textbook: no work in this band presents mathematics to the learner as
  exposition to read and learn from directly. The learner-facing material is the DL
  workbook's task sheets only.
- No DL workbook for Levels 2 or 3, and no workbook at all for DL Modules 4–5.
- No JICA manual for Basic 1 or Basic 2 (the series in the set starts at B3, outside
  this band; B4–B6 are the band's volumes).
- DL coverage is number-only; JICA coverage is full-strand but teacher-scripted, with
  no pupil book to pair it with. Fractions, algebra, geometry/measurement and data for
  B4–B6 therefore rest entirely on the JICA manuals in this band.
- The curriculum's B6 ratio/proportion and probability content is carried by JICA B6
  only; the DL material contains no ratio or probability work at any level.

## Record corrections found in this read

1. DL "Modules 1/2/3" is the wrong description of the three teacher-guide files. The
   files are three LEVEL volumes (ability Levels 1, 2, 3, matching the programme's
   three learning-ability groups). Level 1 contains lesson Modules 1–3, Level 2
   contains Modules 2–4, Level 3 contains Modules 3–5. Distinct lesson-plan content is
   therefore Modules 1–5 (80 lessons), not 3 × 48 = 144 lessons: Modules 2, 3 and 4
   each appear in two files with identical lesson text (apart from printed page
   numbers), and the Activity Book, Mental Maths page and Glossary are identical in
   all three files. The set-table's "Module 1/2/3" labels describe each file's FIRST
   module only, and the brief's "Modules 1/2/3 of one guide" should be replaced by
   this level-window description.
2. DL workbook "Module 1 ONLY" is wrong. The Level 1 workbook file contains Modules 1,
   2 and 3 (24 lessons, 8 per module), as its own Table of Content lists and as the
   module divider pages in the file confirm. What remains true: workbook Levels 2 and
   3 are not in the set, and there is no workbook for Modules 4–5.
3. JICA B6 contents page is a copy of the B5 contents page. Do not use it as B6's map:
   actual B6 starts are Division Lesson 27 (not 29), Integers Lessons 38–41 (not a
   single Lesson 41), Fractions Lesson 42 (the copied "Fractions 42" happens to be
   right), Ratios and Proportion Lessons
   57–70 (not "Decimal fractions 54 / Percentage 69"), Geometry as prisms Lessons
   88–92 and position/transformation Lessons 93–98 (not "2D and 3D Shapes 89 /
   Perimeter-Area-Capacity 92 / Angle 101 / Geometric Reasoning 103"), Data Lesson 99
   (not 107), Probability Lesson 109 (not 112). The B5 contents page, by contrast,
   matches B5's actual lesson headers except that its Data entry reads Lesson 107
   while data content already starts at Lesson 106.
4. Curriculum kind correction (already in the set-table, confirmed here): the
   "full-year" files recorded as "teacher" are curriculum/planning documents, not
   teacher guides. The same correction applies in this band to CURR-B46.
5. JICA B4 file version lacks the copyright page and contents page that B5/B6 carry
   (already in file-facts, confirmed here); B4's strand map must be derived from its
   lesson headers, as done above.
6. Minor held-copy slips, no content lost: DL acknowledgement running head says "Lower
   Primary" in an Upper Primary guide; DL introduction says "English Teachers guide"
   in a Mathematics guide; DL glossary is a reading glossary; DL Module 3 Week 6
   Lesson 2 carries an "Addition and Subtraction" section header above a multiplication
   lesson; DL Module 5 Week 3 Lesson 1 is headed "Addition sum up to 999" for a
   subtraction lesson; curriculum contents line for the Foreword reads "Error!
   Bookmark not defined"; curriculum B4 geometry repeats a "Position/Transformation"
   heading; curriculum time-allocation paragraph is worded for Lower Primary inside
   the Basic 4–6 document.
7. Held-copy defects, no content lost: one near-blank back-matter page in each DL guide
   (PDF p. 276 in Levels 1–2, PDF p. 275 in Level 3); one blank leaf in the workbook
   (PDF p. 5) and one solid red trailing workbook page with no content (PDF p. 65); one
   footer-only trailing page in the curriculum file (PDF p. 182). JICA volumes have no blank or missing lesson pages:
   all 120 numbered lessons plus 5 annual reviews are present in each of B4, B5, B6
   (B4 Lesson 15 is a review lesson whose header is split across the page layout in
   text extraction, but the lesson page itself is present and complete).
8. No ISBN correction is needed beyond what the set-table already records: every ISBN
   in this band is a placeholder (DL: XXX-XXXX-XXXX-X-X; JICA B5/B6: XXXX) or absent
   (curriculum; JICA B4). None may be cited as a real identifier.

## Reading notes (method)

- Text-layer works (curriculum, all three DL guides, all three JICA manuals) were read
  page by page from extracted text, with lesson/module structure verified against
  contents pages and lesson headers, and with sample lesson bodies read in full for
  every strand block.
- The image-only workbook was read as page pictures: every one of its 65 pages was
  rendered and inspected visually (in contact sheets and, for task detail, at full
  page size for the lesson-opening pages), with OCR used only as a cross-check. PDF p. 5
  was confirmed blank; PDF p. 65 is a solid red page with no text (OCR returns no text).
- Short quoted fragments above are headings, task openers and worked-example lines
  only; all other wording is summary in the reader's own words.

## CITATION CHECK (checker, 2026-11-05) — per-work anchors, passed / corrected / not-found

Method: every anchor below was opened at the exact page in the real PDF (text layer for
the curriculum, guides and JICA manuals; rendered page pictures for the image-only
workbook, rendered fresh from grade4_student-workbook.pdf — note: the work folder's
wbimg/ renders do NOT match this PDF's pagination and were not used). "Corrected" means
the claim was fixed in place above with a verified replacement; "not-found" means an
anchor had to be removed outright. No anchor had to be removed outright in this check:
every wrong claim was replaced with a verified one in place. Total anchors 158.

- CURR-B46 — 18 anchors: 15 passed, 3 corrected, 0 not-found.
  Anchors: cover/imprint; foreword and NaCCA block; TOC artefact; rationale; aims;
  competencies; attitudes (11 items); assessment FOR/OF and time allocation; pedagogy;
  organisation definitions and annotation code; grade spans B4/B5/B6; B4 examples;
  B5 examples; B6 examples; Chance scope (grade sections vs scope table); B4 Position
  repeat; back matter. Corrected: (a) 4Rs moved from rationale pp. 5–6 to foreword
  PDF p. 3 and pedagogy PDF p. 13; (b) ICT list page range widened to PDF pp. 13–15
  (Microsoft Office list is on PDF p. 15); (c) PDF p. 182 clarified as footer-only,
  not "the last content page".
- DL-TG-UPPER-L1 — 20 anchors: 18 passed, 2 corrected, 0 not-found.
  Anchors: level window Modules 1–3; contents starts; dividers; front matter
  (acknowledgement slip, foreword, introduction incl. held-copy sentence); lesson-plan
  structure and timings; Activity Book span and identity; Mental Maths page; Glossary;
  near-blank page; module weeks spot-checked (M1 W1/W2/W4, M2 W1/W4/W6/W7, M3 W1/W4/
  W6/W7/W8); activity examples (9,042; 457 + 349; 8457; 427; 815; 383 × 4; 119; 18 ÷ 7);
  honest negatives (no fractions/decimals/algebra/geometry/pictograph/percentage
  anywhere in the guide). Corrected (shared module-map sentences, applied here):
  (d) weekly shape qualified to Modules 1–3 with Modules 4–5 described separately;
  (e) lesson-pair claim softened to "most pairs" with the four split-pair exceptions.
- DL-TG-UPPER-L2 — 18 anchors: 18 passed, 0 corrected, 0 not-found.
  Anchors: level window Modules 2–4; contents starts; dividers; Activity Book text
  identical to Level 1 after stripping printed page numbers; Mental Maths identical;
  Glossary identical; near-blank page; Module 3 Week 6 Lesson 2 header slip; Module 4
  weeks spot-checked (W1–W8); Module 5 Week 3 Lesson 1 "Addition sum up to 999"
  header slip; honest negatives as Level 1.
- DL-TG-UPPER-L3 — 18 anchors: 18 passed, 0 corrected, 0 not-found.
  Anchors: level window Modules 3–5; contents starts; dividers; Activity Book
  identical except shifted printed page numbers (first difference "104" vs "103";
  glossary last number "267" vs "266"); Mental Maths identical (PDF p. 276 vs 277);
  near-blank page (PDF p. 275); Module 5 weeks spot-checked (W1–W8, incl. 40-minute
  Learning Activity); honest negatives as Level 1.
- DL-WB-UPPER-L1 — 21 anchors: 19 passed, 2 corrected, 0 not-found.
  Anchors: cover/title/copyright/writers/placeholder ISBN; 65 PDF pages; TOC Modules
  1–3; module spans and printed-number restarts (dividers PDF pp. 6/26/46, printed
  pp. 1/21/1); blank PDF p. 5; M1 L1 100-chart opening; M1 L3 79 vs 91; M1 L6 Kotokoraba
  35 + 9 and 51 + 7; M1 L7 ladder 2 × 3 = 6; M1 L8 write-a-problem for 12 ÷ 2; M2 L1 mat
  136, sequences 210/260/310 and 100–990 chart; M2 L5 mat 56 − 41 and chart 48 − 5 /
  61 − 8; M2 L8 repeated subtraction 18 ÷ 3, 21 ÷ 7 = 3, 24 ÷ 6 = 4; M3 L1 currency
  GH¢465 worked total; M3 L2 worked 129; M3 L3 wheel 1,301 and charts 2,006 / 4,122;
  M3 L6 Expand and Box 76 × 34 = 2,584 with tasks 34 × 21 / 60 × 35; M3 L7 lattice
  383 × 4 = 1,532 with tasks 120 × 4 / 455 × 6; M3 L8 Big 7 318 ÷ 3 = 106 with tasks
  120 ÷ 6 / 279 ÷ 9. Corrected: (i) PDF p. 65 is a solid red page with no content, not
  a "blank" page (three places fixed); (ii) Table of Content Module 2 page numbers
  (7, 10, 12, 14, 16, 20, 22, 24) do not match Module 2's printed pagination (22–40) —
  defect now noted. Book typos noted, draft values already right: M2 L8 chain
  "17 − 6 = 6" (should be 12 − 6 = 6); M3 L7 summary "384 x 4 = 1532" (lattice is 383).
- JICA-B4 — 19 anchors: 15 passed, 4 corrected, 0 not-found.
  Anchors: cover/imprint (no copyright/ISBN); structure (front matter PDF pp. 1–9,
  lessons PDF pp. 10–129, reviews PDF pp. 130–134); five-part lesson page; evaluation
  rule; timings; Scheme of Work (PDF p. 8, L5 27 Sept to L120 30 June, skip-review
  rule); observation sheet (PDF p. 9); block boundaries from all 120 lesson headers;
  modelling 32,100; rounding 14,500 → 15,000; box method 214 × 3 = 642; folding
  1/2–1/4–1/8; algebra 4 + P = 6 / Q + 15 = 21 / 15 − X = 8; perimeter 20 cm task;
  time durations 2:25–6:55 / 5:40–13:15; Annual Review 1; data titles. Corrected:
  (f) decimals examples replaced with L69 addition 1.2 + 2.3 = 3.5 / 4.7 + 2.8 = 7.5
  and L71 subtraction 2.5 − 1.3 = 1.2 / 4.7 − 2.8 = 1.9 (the draft's 0.3 + 0.3 /
  0.9 + 0.6 = 1.5 pair is a B5 L72 mental-maths item, not B4); (g) unit-fractions
  number-line phrase replaced with the verified L56 improper/mixed number line;
  (h) area example replaced with verified L99/L101/L102 tasks; negatives wording
  fixed: negative values ARE introduced in L27, only integer operations arrive in B5.
  Annual Review note now also mentions area/perimeter on Review 5.
- JICA-B5 — 22 anchors: 12 passed, 10 corrected, 0 not-found.
  Anchors: cover/imprint (© 2025 GES, placeholder ISBN, About the Book PDF p. 137);
  structure; contents page; block boundaries from all 120 lesson headers; counting
  L1 (24,000 / 321,000); multiples L21 (80 × 500); integers L41 tasks; thousandths
  L54 introduction; percentage L69; angles L101 introduction; volume referents L96;
  league table L106; double-bar rainfall L108; chance L112/L113; equations L86
  introduction; catch-up L114 introduction and perfect-numbers note; annual reviews.
  Corrected: (1) contents Data entry reads 107 while data content starts at L106;
  (2) integers examples replaced with printed tasks (2 − 3 = −1; −2 + 4 = 2;
  −2 − 2 = −4; 3 − 7 = −4); (3) fractions L42 method replaced: multiples-listing, not
  prime factorising (the 4/6/20 prime-factorising example is the CURRICULUM's, B5
  PDF p. 90); (4) decimals examples replaced with L62/L63 thousandths
  (0.025 + 0.013 = 0.038; 0.025 − 0.013 = 0.012) — the tenths pair was not found in
  L54–68; (5) patterns example replaced with verified L73/L76–78 patterns;
  (6) L79 integer-review example corrected and the book error flagged: the book prints
  "−3 + 4 = −1" (correct value 1), with verified tasks −5 + 3 = −2, −1 − 3 = −4,
  −1 + 8 = 7; (7) "and regular shapes" removed from quadrilaterals; (8) volume
  comparison replaced with verified L98 set (2 × 2 × 2 = 8, 3 × 1 × 3 = 9,
  2 × 2 × 6 = 24, 3 × 3 × 3 = 27); (9) geometric-reasoning examples replaced with
  verified B5 L103 steps (the draft's factory/airport examples are B6 L93's);
  (10) chance wording fixed to obtaining 5 (not 1) possible. NOT reclassified:
  L72 circle graph stays inside Percentage (contents window L69–72); L104 reflected
  image stays inside Geometric Reasoning (L103–105) — and B5's honest negatives now
  say reflection is introduced here (L104), with only prisms/nets and translation
  deferred to B6.
- JICA-B6 — 22 anchors: 8 passed, 14 corrected, 0 not-found.
  Anchors: cover/imprint/structure; contents page verbatim-copy fact (identical to
  B5's except the (B6) header); block boundaries from all 120 lesson headers;
  ratios block L57–70 (banku mixing, equivalent ratio, amounts, rate, number line,
  split); equations L81 introduction; position L93 introduction; reflection L94
  introduction; translation L96/L97 and identification L98; data L102/L106/L107–108;
  probability L109/L111/L112–114; catch-up L116–119 (12/20/30 introduction and
  perfect-numbers note, identical to B5 L114); annual review introduction samples.
  Corrected: (1) contents-warning rewritten — see below; (2) counting ceiling raised
  to billions (L3–L6); (3) multiplication range narrowed to L21–26 (L27 is division);
  (4) division/integers range corrected to L27–41 with comparing (L38) and
  adding/subtracting (L39) integers; (5) fractions range corrected to L42–56 with
  L42 "Make the denominators the same" (1/3 = 4/12; 3/4 = 15/20; 3/5 = 18/30);
  (6) ratio amount example replaced with L63 (5:7 = 45:n, n = 63; 7:11 with 28 boys →
  44 girls); (7) fractions-revisit example replaced with L71 (1/8 = 0.125 vs
  2/3 = 0.66…); (8) algebra pattern examples replaced with verified L73/L74 tables;
  (9) algebra sequence corrected to pattern rules → expressions → equations (not
  interleaved); (10) "cardboard" dropped from prism nets (unverified); (11) position/
  transformation wording separated by lesson (x-axis/y-axis/line k reflection L94;
  vector translation L96; translate K / reflect L in x-axis L97; identification L98);
  (12) probability wording separated (coin 10 times L109; spinner 20 times in groups
  L111; outcomes/theoretical L112–114); (13) catch-up codes corrected to B6.1.2.3.1 /
  B6.1.2.2.1 / B6.1.2.1.1 (the draft's B6.1.1.3 does not occur in L116–119);
  (14) Annual Review 5 examples replaced with AR5 tasks (4 + x = 15; x − 9 = 7) and
  AR1/AR2 examples marked as introduction samples (218 × 34 = 7,412;
  382 × 856 = 326,992; 66 ÷ 21 = 3 R 3; 348 ÷ 23 = 15 R 3 — all verified).
  BRIEF-VS-BOOK DISCREPANCY (flagged, resolved in favour of the book): the task
  brief asserted B6 fractions start at L43 with L42 "still integers work". The book
  says otherwise: L41 is "Multiply integers" (PDF p. 52) and L42 is "Make the
  denominators the same" (PDF p. 53, fractions content). The draft, Record correction 3
  and this block now all read Fractions L42–56; the brief's L43 claim should not be
  used. Two copied contents numbers happen to land inside the right block (Fractions
  42, Patterns 73) — the warning now says so instead of "differs at every point".

Truncation-marker grep after editing: zero occurrences of the marker in this draft.


## Band C — JHS (Basic 7–9 curriculum only)
## Work read (1 distinct work, 1 row)

- **Work ID:** CURR-JHS
- **Title as printed:** "MATHEMATICS COMMON CORE PROGRAMME (CCP) CURRICULUM FOR JHS1 (B7) - JHS3 (B9)"
- **Issuer:** National Council for Curriculum and Assessment (NaCCA), Ministry of Education, Republic of Ghana
- **Date as printed:** September 2020
- **ISBN as printed:** none — no ISBN appears anywhere in the document (checked by full-text search).
- **File read:** `pdfs/grade7_full-year.pdf` (repo path `grade-07/gov/ghana/mathematics/full-year.pdf`)
- **Pages:** 259 PDF pages, read in full, page by page, from the text layer (the file carries a full text layer; no page-picture reading was needed).
- **Size / hash:** 5,590,851 bytes; sha256 `220a7c1d435ecb4d81bd90bd081c44038aeab3a28a5e9f888128a4b450ef4bd2`
- **Language as printed:** English throughout.
- **Proved kind:** curriculum / planning document — NOT a textbook, NOT a teacher guide, NOT a workbook.
- **Record correction:** the set table records this row's kind as generic "teacher". That is wrong. The cover, foreword and contents all show a curriculum document that states what must be taught, not lessons that teach it. Kind verdict: CORRECTION — curriculum.

## What this document is — and what it is not

This is the official standards document for junior high school mathematics in Ghana's Common Core Programme (CCP). Each of its tables has three columns — a content standard, its indicators and exemplars, and the core competencies it serves. The "exemplars" are short worked suggestions addressed to the teacher (for example, how a class discussion or a grouping task might run). They are planning guidance, not pupil lessons: there are no taught chapters, no learner exercises to work through, and no pupil textbook content here.

**Therefore, in LiqLearns terms: this work contributes ZERO taught lessons.** Its content is filed here as a record only — a map of what Ghana's JHS curriculum requires at each level — so that later lesson-building from real textbooks can be checked against it. Nothing below is presented as book teaching, and no lesson, question set, or worked example has been lifted from it into course material.

## Scope facts (stated plainly)

- Grade 7 (Basic 7, JHS1) has ONLY this curriculum in the Ghana maths set. No JHS teacher guide, no JHS workbook, and no JHS pupil textbook is held for any JHS grade.
- The curriculum itself spans three levels — Basic 7, Basic 8 and Basic 9 (JHS1–JHS3) — but it is a single filed row, filed under Grade 7. Basic 8 and Basic 9 have no separately filed rows in this set; their sections are covered by this one document.
- The foreword places the CCP as the sequel to the kindergarten–primary standards-based curriculum (implementation from the 2019/2020 academic year) and as preparation for post-secondary education, work, or both, with pathways onward from Basic 10.

## Front matter (PDF pp. 1–30)

- **Cover (p. 1)** as titled above, September 2020, Ministry of Education, Republic of Ghana.
- **Enquiries page (p. 2):** NaCCA Director-General contact block, Cantonments, Accra.
- **Foreword (p. 3):** signed by the Minister of Education. It frames the CCP around character and values as well as progression, the "4Rs" (Reading, wRiting, aRithmetic and cReativity), core competencies, and personal/community projects and service as part of assessment. Note a slip in the foreword's own wording: it describes the CCP as for "Basic 7 to Basic 9 (JHS 1 – SHS 3)"; the second label should read JHS3, and every other part of the document confirms the span is B7–B9.
- **Acknowledgements (p. 4):** NaCCA developed the CCP curriculum together with the national assessment framework and teacher/learner resource packs, under the Ministry of Education, with Ghana Education Service, the inspectorate, the teaching council, the TVET commission, universities, colleges of education, teachers and learners; a national stakeholder engagement in Accra in February 2020 is named.
- **Contents (pp. 5–7):** lists the front matter, then the full B7, B8 and B9 tables by strand and sub-strand, then an appendix and a bibliography.
- **Introduction (pp. 8–10):** the CCP runs from Basic 7 through Basic 9; its centre is the common-core learner attributes across cognitive, psychomotor and affective domains, shaped by learning/teaching approaches (core competencies, 4Rs, pedagogies), learning context (engagement, projects, service) and learning areas (mathematics alongside science, computing, languages, career technology, social studies, physical and health education, creative arts and design, and religious and moral education).
- **Rationale (p. 11):** mathematics as integral to everyday life and national development, to be taught with hands-on and minds-on approaches.
- **Philosophy (p. 12):** inquiry-based, learner-centred teaching; learners as constructors of knowledge, teachers as facilitators.
- **Aims (p. 13):** one general aim (mathematically literate, good problem solvers, creative thinkers, confident participants in Ghanaian society as responsible local and global citizens) and eight subject aims, covering recognising mathematics in the world, appreciating its usefulness, power and beauty, enjoying it with patience and persistence, using its language, symbols and notation, reasoning inductively and deductively, applying it in school and real life, preparing for further study, and thinking abstractly, logically and critically.
- **Profile of expected learning behaviours (pp. 14–16):** six dimensions (knowing, understanding, analysis, synthesis, evaluation, creation) grouped for teaching, learning and assessment into three weighted profiles — Knowledge and Understanding 30%, Application of Knowledge 40%, Attitudes, Values and Process Skills 30%. [CHECKER CORRECTION: the draft had listed the dimensions as "knowing, understanding, applying, analysing, synthesising/evaluating, creating"; PDF p. 14 names the six as knowing, understanding, analysis, synthesis, evaluation and creation.]
- **Attitudes, values and process skills (p. 17):** respect, diversity, equity, commitment to excellence, teamwork/collaboration, truth and integrity, and related values.
- **Assessment in the CCP (pp. 18–21):** assessment for learning, assessment of learning, and assessment as learning; school-based assessment (SBA) covering all three; a criterion-referenced proficiency scale with five levels — Highly Proficient (80%+), Proficient (68–79%), Approaching Proficiency (54–67%), Developing (40–53%), Emerging (39% and below). One internal inconsistency: the SBA text speaks of a "four-year duration of CCP", although the programme documented here is the three-year B7–B9 span (see also the appendix note below).
- **Creative pedagogical approaches (pp. 22–25):** learning-centred pedagogy, inclusion, differentiation (by task, by support, by outcome), scaffolding, and ICT as a teaching and learning tool.
- **Core competencies (pp. 26–27):** the six competencies tagged on every standards table — Critical Thinking and Problem Solving (CP), Creativity and Innovation (CI), Communication and Collaboration (CC), Cultural Identity and Global Citizenship (CG), Personal Development and Leadership (PL) (all defined on p. 26), and Digital Literacy (DL) (defined on p. 27). [CHECKER CORRECTION: the draft had listed five and omitted CG, which is defined on PDF p. 26 and tagged in the tables, e.g. PDF p. 201.]
- **Instructional expectations (p. 28):** twelve teacher roles (numbered 1–12; a thirteenth item is a transition sentence, not a role), including guiding and facilitating learning, selecting and adapting content, collaborating across disciplines and grades, gathering evidence about understanding, managing learning environments, pressing learners to reason, present ideas and critique each other's reasoning, using appropriate technologies, insisting on precision, and looking for patterns in repeated reasoning. [CHECKER CORRECTION: the draft had said "nine teacher roles"; PDF p. 28 numbers twelve.]
- **Structure and organisation (pp. 29–30):** definitions of the four organising units — strands (broad areas), sub-strands (topics within a strand), content standards (the level of knowledge, skill and/or attitude a learner attains by a set stage), and indicators (the clear outcomes a learner must exhibit in a year, stated as the minimum expected standard), with exemplars as supporting guidance for teachers. A unique annotation labels class, strand, sub-strand, standard, indicator and exemplar (for example, a code reading B7, strand 1, sub-strand 1, standard 1, indicator 1).

## The standards structure (same shape at all three levels)

Four strands, twelve sub-strands, in the same order at B7, B8 and B9:

- **Strand 1: Number** — Sub-strand 1: Number and Numeration Systems; Sub-strand 2: Number Operations; Sub-strand 3: Fractions, Decimals and Percentages; Sub-strand 4: Number: Ratios and Proportion.
- **Strand 2: Algebra** — Sub-strand 1: Patterns and Relations; Sub-strand 2: Algebraic Expressions; Sub-strand 3: Variables and Equations.
- **Strand 3: Geometry and Measurement** — Sub-strand 1: Shape and Space (spelled "Shapes and Space" in the B8/B9 headings); Sub-strand 2: Measurement; Sub-strand 3: Position and Transformation.
- **Strand 4: Handling Data** — Sub-strand 1: Data; Sub-strand 2: Chance or Probability.

Counts below are distinct standard and indicator codes recovered from the document's tables. Standard counts were verified code by code against the section tables (see the Table 3 note below); indicator counts are a floor, because a few indicator codes run into their following text in the PDF's text layer and escape exact counting, but every standard's indicators were read in the tables.

### Basic 7 — PDF pp. 31–118 (section divider p. 31; tables pp. 32–118; printed pp. 2–88 for the tables) [CHECKER CORRECTION: the draft had said printed pp. 1–88 for the tables; the footers run PDF p. 32 = printed 2 through PDF p. 118 = printed 88, matching the PDF-minus-30 mapping used for B8/B9.]

21 content standards; at least 68 indicators.

| Sub-strand | PDF pp. | Standards | What the section covers (structural summary) |
|---|---|---|---|
| 1.1 Number and Numeration Systems | 32–36 | 2 | Place value for quantities beyond 1,000,000,000; comparing and ordering such whole numbers. |
| 1.2 Number Operations | 37–46 | 3 | Mental strategies and number properties; multiplying and dividing by powers of 10, including decimals and benchmark fractions; powers and repeated factors. |
| 1.3 Fractions, Decimals and Percentages | 47–53 | 3 | Benchmark fractions and their percentages/decimals; simplifying, comparing and ordering mixtures of fractions, decimals and percentages. |
| 1.4 Number: Ratios and Proportion | 54–56 | 1 | The concept of ratio and ratio language for relationships between two quantities. |
| 2.1 Patterns and Relations | 57–64 | 1 | Deriving the rule for a set of points of a relation, drawing its table of values and graphing it. |
| 2.2 Algebraic Expressions | 65–70 | 1 | Creating and simplifying simple algebraic expressions involving the four basic operations. |
| 2.3 Variables and Equations | 71–76 | 1 | Linear equations of the form x + a = b, translating word problems to equations and back. |
| 3.1 Shape and Space | 77–88 | 2 | Angles — right, acute, obtuse and reflex, including adjacent and vertically opposite angles. |
| 3.2 Measurement | 89–101 | 3 | Perimeter of plane shapes whose dimensions use two units; area relationships; bearings and vectors (including true and back bearings and column/magnitude–bearing conversion). |
| 3.3 Position and Transformation | 102–106 | 1 | Single transformations (reflection and translation) on 2-D shapes; reflectional symmetry. |
| 4.1 Data | 107–115 | 2 | Selecting, justifying and using methods to collect quantitative and qualitative data; determining features of data sets. |
| 4.2 Chance or Probability | 116–118 | 1 | Sample space for single-event experiments; likelihood language (impossible, possible, certain); probabilities as fractions, decimals, percentages and/or ratios. |

### Basic 8 — PDF pp. 119–193 (section divider p. 119, printed p. 89; tables pp. 120–193, printed pp. 90–163)

18 content standards; at least 58 indicators.

| Sub-strand | PDF pp. | Standards | What the section covers (structural summary) |
|---|---|---|---|
| 1.1 Number and Numeration Systems | 120–123 | 2 | Place value for quantities beyond 1,000,000,000, read and written; related number concepts. |
| 1.2 Number Operations | 124–131 | 3 | Mental strategies and number properties; multiplying and dividing by powers of 10, including decimals and benchmark fractions. |
| 1.3 Fractions, Decimals and Percentages | 132–134 | 1 | Operations on fractions applied to problems. |
| 1.4 Number: Ratios and Proportion | 135–141 | 1 | Ratio, rate and proportion, including ratio reasoning to convert measurement units. |
| 2.1 Patterns and Relations | 142–147 | 1 | Tables of values for linear relations, graphing, gradient, and equations of the form y = mx + c. |
| 2.2 Algebraic Expressions | 148–150 | 1 | The distributive property, removing brackets, and multiplication of binomial expressions. |
| 2.3 Variables and Equations | 151–152 | 1 | Linear inequalities in one variable, translating word problems to inequalities and back. |
| 3.1 Shapes and Space | 153–171 | 2 | Angle relationships, including alternate and corresponding angles. |
| 3.2 Measurement | 172–180 | 2 | Pythagoras' theorem, primary trigonometric ratios, the diameter–circumference relationship for circles, and addition/subtraction of vectors. [CHECKER CORRECTION: the draft had covered only the first standard (B8.3.2.1); the second standard, B8.3.2.2 (PDF pp. 179–180), is vector addition/subtraction.] |
| 3.3 Position and Transformation | 181–182 | 1 | Rotation as a single transformation on 2-D shapes. |
| 4.1 Data | 183–190 | 2 | Data types (numerical, categorical, ungrouped and grouped) and methods of collecting data. |
| 4.2 Chance or Probability | 191–193 | 1 | Sample space for experiments with two independent events (for example, drawing coloured bottle tops from a bag with replacement). |

### Basic 9 — PDF pp. 194–250 (section divider p. 194, printed p. 164; tables pp. 195–250, printed pp. 165–220)

19 content standards; at least 51 indicators.

| Sub-strand | PDF pp. | Standards | What the section covers (structural summary) |
|---|---|---|---|
| 1.1 Number and Numeration System | 195–197 | 2 | Place value applied to real-life problems; expressing integers to given significant and decimal places. |
| 1.2 Number Operations | 198–201 | 4 | Mental strategies with powers of 10, decimals and benchmark fractions; surds, including simple and compound surds and approximating roots of non-perfect squares. |
| 1.3 Fractions, Decimals and Percentages | 202–204 | 1 | Operations on fractions applied to problems. |
| 1.4 Number: Ratios and Proportion | 205–209 | 1 | Ratio, rate and proportion, including representing proportional relationships by equations. |
| 2.1 Patterns and Relations | 210–212 | 1 | Tables of values and graphs for two linear relations. |
| 2.2 Algebraic Expressions | 213–219 | 1 | Change of subject of a formula and substitution, used to solve problems. |
| 2.3 Variables and Equations | 220–225 | 1 | Single-variable linear inequalities with rational coefficients. |
| 3.1 Shapes and Space | 226–234 | 2 | Properties of angles at a point and on polygons (including the sum of angles in a polygon) and constructions of inscribed and circumscribed triangles and other shapes. |
| 3.2 Measurement | 235–238 | 2 | Nets and surface area of cuboids and triangular prisms, and bearings/vector problem solving (parallel and perpendicular vectors, triangle and parallelogram laws of addition). [CHECKER CORRECTION: the draft had described the second standard as "related volume/surface-area problem solving"; B9.3.2.2 (PDF p. 238) is "Solve problems involving bearings and addition/subtraction of vectors".] |
| 3.3 Position and Transformation | 239–240 | 1 | Enlargement in everyday situations. |
| 4.1 Data | 241–248 | 2 | Selecting, justifying and using methods of collecting quantitative and qualitative data. |
| 4.2 Chance or Probability | 249–250 | 1 | Sample space for experiments with two dependent events (for example, drawing coloured bottle tops from a bag without replacement). |

**Totals across the document: 58 content standards (B7 21 + B8 18 + B9 19) and at least 177 indicators.**

## Back matter (PDF pp. 251–259)

- **Appendix (pp. 251–255, printed pp. 221–225):** "Unpacking the Core Competences of the Standards-Base Curriculum" — sub-skill lists for the CCP core competencies, headed B7–B10. The B7–B10 label is a framework-wide label (the shared CCP competency framework runs beyond JHS); it does not extend this mathematics document's standards, which stop at B9. This is also the source of the document's only "B10" mentions.
- **Bibliography (pp. 256–257, printed pp. 226–227):** source books and syllabuses, including Ghana senior secondary mathematics books, Ghanaian curriculum writers, and the Alberta mathematics framework among others.
- **Subject panel members and reviewers (p. 258)** and **supervisors and coordinating team (p. 259, printed p. 229):** NaCCA staff and reviewers from universities, colleges of education and schools.

## Near-blank pages — checked, not defects

- **PDF p. 31** carries only the words "BASIC 7"; **PDF p. 119** only "BASIC 8" (printed p. 89); **PDF p. 194** only "BASIC 9" (printed p. 164). These are section dividers, visually confirmed, not missing content. The B7, B8 and B9 tables begin on the following page in each case.
- **PDF p. 27** is short (a single competency definition, Digital Literacy, closing a spread) and **PDF p. 10** is a short continuation paragraph; neither loses content.
- No other blank, missing or garbled pages were found in the 259 pages. One recurring text-layer quirk: a few standard codes print with an extra dot after the level letter (as "B.7.3.2.2" for B7.3.2.2); the codes and their indicators are intact and readable in context.

## Record corrections and observations for the parent

1. **Kind correction (the main one):** set-table row id 30 (grade7_full-year.pdf) is recorded as kind "teacher". Proved kind is **curriculum**. Same correction pattern as the B1–3 and B4–6 curricula in this set, but this row is a distinct work, not a duplicate of either.
2. **The document's own summary table disagrees with its own tables.** Table 3 (PDF p. 30, printed p. xxx) totals the content standards as B7 19, B8 18, B9 17. Counting the standards actually printed in the section tables gives **B7 21, B8 18, B9 19**. B8 matches Table 3 exactly. The B7 gap is in Number and Numeration Systems (Table 3 says 1, the tables print 2: comparing/ordering whole numbers beyond 1,000,000,000) and Measurement (Table 3 says 2, the tables print 3: bearings/vectors). The B9 gap is in Number Operations (Table 3 says 3, the tables print 4: surds) and Shapes and Space (Table 3 says 1, the tables print 2: inscribed/circumscribed constructions). Three of the four extra standards were verified as full standard headers with their own numbered indicators: B7.3.2.3 with indicators .1–.5 (PDF pp. 97–101), B9.1.2.4 with indicators .1–.3 (PDF pp. 200–201), and B9.3.1.2 with indicators .1–.2 (PDF pp. 229–234). The fourth, B7.1.1.2 (PDF p. 33, "Compare and order whole numbers more than 1,000,000,000 and represent the comparison using >, <, or ="), is a full standard header row with exemplars (E.g. 1–3) but carries no numbered indicator code anywhere in the document's text layer, so the draft's earlier wording claiming all four had "their own indicators" is corrected here. [CHECKER CORRECTION.] The table counts in this draft follow the section tables, not Table 3.
3. **Document-internal wording slips (not reading errors):** the foreword's "(JHS 1 – SHS 3)" for the B7–B9 span; the SBA text's "four-year duration of CCP"; the appendix's B7–B10 competency labels against a B7–B9 standards document. None of these changes the scope of what was read.
4. **No ISBN, no pupil textbook, no teacher guide, no workbook in this band.** The set's Band C gap note stands: Grade 7 has only this curriculum; nothing else JHS is held. Any future JHS pupil textbook or teacher guide would be a new acquisition, not a re-read of this work.

## Gaps found (within this band's assignment)

- None within the assigned work: the single CURR-JHS row was read in full (259 of 259 pages).
- Gaps in the wider set that this band does not fill: no JHS pupil textbook, teacher guide or workbook exists in the Ghana maths record for B7, B8 or B9, so no JHS taught lessons can be built from Ghana sources in this set until such a book is acquired. This curriculum record is the map against which any such future book would be checked.
- No lessons, questions or taught content were filed from this document, by design: it is record-only.

## Checker block (citation-check, 2026-11-04; checker did not write this draft)

Method: every anchor below was opened on its exact PDF page in `pdfs/grade7_full-year.pdf` (259 pages; 5,590,851 bytes; sha256 `220a7c1d435ecb4d81bd90bd081c44038aeab3a28a5e9f888128a4b450ef4bd2` — matches the draft's file facts) via the PDF text layer, and standard codes were extracted page by page. Counts verified code by code: B7 21 standards / 68 distinct indicator codes, B8 18 / 58, B9 19 / 51, total 58 standards and 177 indicators — matching the draft's "at least" figures exactly. All 36 sub-strand page spans in the draft match the first/last pages of their standard codes. Full-text search finds zero "ISBN" occurrences. Only near-blank pages in the whole file are the three dividers (PDF pp. 31, 119, 194).

Anchors checked: 20 — passed 13, corrected 7, not found 0.

Passed (13): cover title/date/issuer (p. 1); enquiries block (p. 2); foreword slip "(JHS 1 – SHS 3)" and Minister signature (p. 3); acknowledgements, Accra Feb 2020 engagement (p. 4); contents (pp. 5–7, incl. appendix 221, bibliography 226, panel 228, supervisors 229); introduction/rationale/philosophy (pp. 8–12); aims, 1 general + 8 subject (p. 13); attitudes/values list (p. 17); assessment, SBA, 5-level scale with benchmarks 80+/68–79/54–67/40–53/39-and-below, and the "four-year duration" slip (pp. 18–21); pedagogical approaches incl. differentiation by task/support/outcome, scaffolding, ICT (pp. 22–25); structure definitions and Table 3 totals B7 19 / B8 18 / B9 17 (pp. 29–30); the three near-blank dividers (pp. 31, 119, 194); back matter — appendix B7–B10 labels (pp. 251–255), bibliography (pp. 256–257), panel (p. 258), supervisors (p. 259, printed 229); and the four-strand / twelve-sub-strand order, identical at B7, B8 and B9 (section headings on PDF pp. 32, 120, 195, etc.), with the noted spelling variants (B7 "Shape and Space" vs B8/B9 "Shapes and Space"; B9 1.1 singular "System").

Corrected (7, all fixed in place above and marked [CHECKER CORRECTION]):
1. Profile dimensions (pp. 14–16): draft's list replaced with the document's own six — knowing, understanding, analysis, synthesis, evaluation, creation. The 30/40/30 weighting itself passed (p. 15).
2. Core competencies (pp. 26–27): added the omitted sixth competency, Cultural Identity and Global Citizenship (CG), defined on p. 26 and tagged in tables.
3. Instructional expectations (p. 28): "nine teacher roles" corrected to twelve numbered roles (item 13 is a transition sentence, not a role).
4. B7 printed pagination: tables are printed pp. 2–88, not 1–88 (footers: PDF p. 32 = printed 2, PDF p. 118 = printed 88); B8 (90–163) and B9 (165–220) ranges passed as written.
5. B7 2.1 summary: added graphing (the standard header on p. 57 includes graphing the relation).
6. B8 3.2 summary: added the second standard, vector addition/subtraction (B8.3.2.2, pp. 179–180), which the draft had omitted.
7. B9 3.2 summary + observation 2: the second standard is bearings/vector problem solving, not "volume/surface-area problem solving" (B9.3.2.2, p. 238); and the "all four extras have their own indicators" claim is qualified — B7.1.1.2 (p. 33) is a full header with exemplars but no numbered indicator code in the text layer, while B7.3.2.3 (.1–.5), B9.1.2.4 (.1–.3) and B9.3.1.2 (.1–.2) do carry numbered indicators. Standard totals B7 21 / B8 18 / B9 19 stand.

Not found (0): no draft claim failed to be located; no anchor was removed. One text-layer note, not a draft error: a few indicator codes merge into following text (e.g. B7.1.1.1.2, B9.1.2.3.1–.3 do not surface as distinct codes), which is why the draft's "at least" framing for indicator counts is kept.

Literal-marker sweep: occurrences of the bracketed truncation marker in this draft after checking: 0.
