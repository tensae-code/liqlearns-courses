# Iran — Mathematics, Grades 1–12 (OERP, Ministry of Education)

READ COMPLETE. Files in hand (reconciled against the record):
**22 files — Grades 1–12 — 3,020 PDF pages in total**
(Band A, Grades 1–6: 951; Band B, Grades 7–9: 447;
Band C, Grades 10–11: 1,016; Band D, Grade 12: 606;
274,331,030 bytes, ~262 MiB).
Distinct works: **22 distinct works** (22 student textbooks;
no teacher guides or workbooks exist in the Iran set).
Anchors: **417 (398 passed, 17 corrected, 2 not found)** —
Band A 108 (97 passed, 10 corrected, 1 not found),
Band B 67 (65 passed, 1 corrected, 1 not found),
Band C 146 (142 passed, 4 corrected, 0 not found),
Band D 96 (94 passed, 2 corrected, 0 not found).
The 17 corrected items are fixed in the sections below (each fix is the
checker's render-verified value). The 2 not-found items are NOT carried
as fact: Band A's not-found (a Grade 1 heavier/lighter comparison
activity cited at printed ~p. 152) was deleted as cited — printed 152
is a count-by-2s/3s/4s dot-joining page; the Grade 1 late sections were
then re-read by a repair reader, who found a genuine heavier-marking
activity at printed p. 168 (render-verified; the text layer garbles the
word, which is why the checker's text search missed it) — it is filed
at p. 168 in the Grade 1 section. Band B's not-found was a filing defect, not a book claim — the Band B
reader's Grade 7 filing was truncated on disk mid-Chapter 7, and the
missing chunk (rest of Ch. 7, Ch. 8, Ch. 9, Grade 7 §§5–8) was supplied
by a separate completion re-read of g07.pdf (printed pp. 83–end) and is
spliced into the Grade 7 section below.
**Record correction: the inventory's "16 in hand" UNDERCOUNTS by 6.**
The inventory rests on the staging books.json files, which exist only
for Grades 7–12; the six primary Mathematics books (Grades 1–6) are
recorded in textbooks.tsv with GitHub tree URLs, all six tree files
exist and are complete, and all six are read here. The inventory's 16
are all present and byte-verified — a confirmed subset, not a different
set (full reconciliation in the read's set-verification record).

## The set at a glance

- **One language: Persian throughout.** Every book is in Persian; no
  other-language edition is in hand. All books are OERP (Organization
  for Educational Research and Planning, Ministry of Education, Iran)
  pupil textbooks, printed by the Iran Textbook Printing and Publishing
  Company; the held printings are 1405 (school year 1405–1406) except
  Grade 5, whose held printing is 1404.
- **One student book per grade in Grades 1–9** — Mathematics (ریاضی) for
  Grades 1–6 primary and Grades 7–9 lower secondary, no branch split.
- **Grades 10–12 split by branch, and the branches are never merged in
  this filing.** Mathematical Sciences (ریاضی و فیزیک): G10 Mathematics
  (1) + Geometry (1); G11 Calculus/Hesaban (1) + Geometry (2) +
  Statistics and Probability; G12 Calculus (2) + Geometry (3) +
  Discrete Mathematics. Experimental Sciences (علوم تجربی): G11
  Mathematics (2), G12 Mathematics (3) — and G10 Mathematics (1), the
  one book shared with Mathematical Sciences exactly as its cover
  prints. Humanities (علوم انسانی): Mathematics and Statistics (1),
  (2), (3) for G10, G11, G12.
- **No teacher guides, no workbooks, no answer keys.** No Iran maths
  teacher guide or workbook is in the record at all, and none of the 22
  student books carries an answer key.
- **Calculus is split across two grades and never reaches integration.**
  Grade 11 Hesaban (1) ends at limits and continuity (the derivative is
  never mentioned); Grade 12 Hesaban (2) teaches the derivative and its
  applications but no integrals and no differential equations anywhere
  in the set.
- **Only 2 confirmed book errors in 3,020 pages** (both render-verified
  and recomputed by reader and checker independently): G11 Statistics
  and Probability printed p. 89 prints (32−28)/28 × 100 = 14% as an
  exact equality (true 14.2857…% ≈ 14.3%); G12 Mathematics and
  Statistics (3) printed p. 104 prints 40,000,000 × (1−0.01)¹⁸ =
  3,338,600 (true ≈ 33,380,550 — a dropped digit). Every other
  recomputed worked value in the set checked out; several extraction
  artefacts that looked like errors (reversed RTL inequalities, column
  interleavings) were dissolved by renders and are recorded as
  artefacts, never as errors.
- **Gaps (record facts):** no Grade 10–12 book for the Technical/
  Vocational branch is in the record; senior-branch negatives are filed
  per book (e.g. Humanities never meets trigonometry or calculus;
  Mathematical Sciences never meets a probability distribution beyond
  Grade 11's inferential introduction; vectors appear as lower-
  secondary introductions (Grades 7–8), as translation vectors inside
  Grade 11 Geometry (2)'s transformations chapter, and in full only in
  Grade 12 Geometry (3)'s ℝ³ chapter).

---

## Band A — Primary (Grades 1–6)

Band reader filing, 2026-11-06. Set record: `../set-verification.md` (22 files in hand; this band is the 6 primary books).

**How I read (method honesty):** full read of every book from the real Persian text layer
(`scratch/txt/g01.txt` … `g06.txt`, one form-feed per PDF page, 951 PDF pages in total),
page by page, building a per-page outline of headings, activity types and printed page
numbers for all six books. Page-specific claims that the RTL text layer makes ambiguous
(digits, equation layout, contents pages) were verified against the PDF itself:
contents pages and imprint pages were rendered with `pdftoppm` and looked at
(G2 visual contents, G4/G5/G6 contents, and the three error-candidate pages below).
An automated recompute scan extracted every `a+b=c / a−b=c / a×b=c` string in the six
text layers and recomputed it; every mismatch was traced and proved to be an extraction
interleaving of side-by-side exercise items, a blank-answer exercise, or a correct
printed value — see each book's error section. **Confirmed errors filed in this band: 0.**

**Band-wide facts**

- All six are pupil's textbooks (see kind proof per book). No teacher guide and no
  workbook for any Iran grade is in the set (set-verification.md).
- **Answer keys: none.** No book in this band carries answers anywhere — no answer
  section, no worked answers beyond the teaching examples on the page. Exercises are
  printed with blanks for the pupil to fill.
- Common lesson machinery (Grades 2–6): each chapter opens with a picture/intro page,
  then lessons built from **فعالیت (Activity)** → **کار در کلاس (Classwork)** →
  **تمرین (Exercise/homework)**, one **حل مسئله (Problem-solving)** unit per chapter
  teaching a named strategy, and a closing **مرور فصل (Chapter review)** with
  فرهنگ نوشتن (writing about maths), فرهنگ خواندن (reading) and a معما (puzzle) page.
- Numbers are printed in both Persian digits (۰۱۲۳…) and Western digits in different
  places; money is the rial (ریال), with the toman used informally in G3.
- **No missing or duplicated pages found in any of the six held copies.** Page counts
  match the set record exactly (184 / 152 / 152 / 160 / 151 / 152). A few pages are
  picture-only and yield no text layer (listed per book) — they are present in the PDF,
  not missing.

---

## Grade 1 — g01.pdf

### 1. Identity
- Persian title as printed (cover): **ریاضی ـ اول دبستان** — "Mathematics — First [grade of] Primary School".
- Grade: 1 (اول دبستان). Publisher: سازمان پژوهش و برنامه‌ریزی آموزشی — Organisation for
  Educational Research and Planning (OERP), Ministry of Education, Iran.
- Imprint (PDF p. 2): book code **105** (ریاضی ـ اول دبستان ـ ۱۰۵); printing as printed:
  **چاپ شانزدهم 1405** — 16th printing, year 1405. Printer: Offset Co. (شرکت افست), Tehran.
- ISBN as printed: **978-964-05-1983-7**.
- PDF pages: **184**. Printed pages: 1–175.
- **Offset: PDF page = printed page + 6** (established at PDF p. 8 = printed 2, and
  verified late at PDF p. 176 = printed 170, PDF p. 181 = printed 175).
- Authors (imprint): Khosro Davoudi, Arash Rastegar, Vahid Alamian (writing group).

### 2. Kind proof
Cover + title/imprint page name it the Grade-1 pupil's Mathematics book (ریاضی ـ اول
دبستان, code 105 in the national textbook series); every page is a pupil activity page
to be coloured, counted and written in — not a workbook (it *is* the textbook, written
in) and not a guide (the short notes at the foot of pages are tips *inside* the pupil
book, addressed to teacher/parent).

### 3. Contents
Grade 1 has **no printed contents list**. The preface (PDF p. 6) states the book has
**25 sections (بخش)**; each section opens with a full-page picture tablet (لوحه) and
then has six activity pages. Section tablets are at printed pp. 7N−6 for
section N — printed 1, 8, 15, 22, …, 169 — i.e. every 7 printed pages
(checker-verified on renders; the reader's first draft said every 6, which
is wrong); section 25's tablet is at printed 169 and the last content page
is printed 175.
The 25 sections are one continuous number course; their content is filed in §4 in
section groups, since the book itself gives the sections no titles.

### 4. Everything taught (printed page numbers; PDF = printed + 6)
Activity types recur on almost every page and are named in Persian on the page:
**بشمار و بگو (Count and say), بشمار و بنویس (Count and write), بشمار و رنگ کن
(Count and colour), الگویابی کن (Find the pattern), با ابزار کار کن (Work with tools —
ruler, template/stencil شابلون, scissors), کامل کن (Complete), مسئله حل کن (Solve the
problem), اندازه‌گیری کن (Measure)**. Every page also carries a one-line tip for the
teacher and one for parents at the foot. Introduction is always concrete first:
real objects, fingers, tally sticks (چوب خط), paper clips and blocks (چینه) before
any written numeral.

- **Sections 1–4 (printed 1–24): counting to 5 and number sense.** Count sets of
  like shapes and say/write how many (pp. 2–3); colour as many boxes as the count
  (p. 3); shape patterns continued by colouring (pp. 4–5); join groups with equal
  counts with a ruler (p. 6); show counts on fingers (p. 7); "magic tables"
  (جدول شگفت‌انگیز — Sudoku-like picture grids) first appear (printed 9); say the count
  quickly without counting one-by-one (p. 10); one-before / one-after a count (p. 14);
  add 2 to a set and say the new count (pp. 16–19); count sides/corners of shapes and
  matchstick shapes (pp. 18, 23); tally marks introduced for counting (p. 24).
- **Sections 5–6 (printed 25–36): joining and taking away, pre-symbolic.** Colour as
  many right-hand shapes as the left-hand count; close fingers to show what remains
  (pp. 25, 31); draw with a stencil/template and count corners and edges (p. 26);
  tally each animal (p. 27); "how many altogether / how many left" with tallies and
  fingers (pp. 30–36); symmetry first appears as completing a shape's other half
  (p. 30 area and repeatedly later).
- **Sections 7–8 (printed 37–48): writing numerals.** "Each shape shows which
  number?" — reading finger/picture representations and writing the digit (pp. 43–48);
  telling a story for a picture (p. 37); measuring length in paper clips (گیره) and
  writing the measure (p. 55 in section 8's run, printed 49–54: numeral writing
  continues, magic tables now with numerals).
- **Sections 9–10 (printed 55–66): totals with a written number; the numbers 6 and 7.**
  "Left and right groups together are how many? Show it with one number" (p. 61);
  take away and write what remains (p. 62); completing symmetric halves (p. 60);
  transferring fingers hand-to-hand to make 6 and 7 in different ways (pp. 65–70).
- **Sections 11–12 (printed 67–78): = , < , >.** Write each group's number; where
  counts are equal put the equals sign (p. 73, e.g. 4 = 4 pictured); colour the
  bigger group (p. 70); the less-than/greater-than signs introduced and used
  (pp. 79–82); number 9 representations (p. 81).
- **Section 13 (printed 85–91): addition as a written expression.**
  - Picture tablet 13 (printed 85) — full-page scene, no activities.
  - Write the number shown by each hand's fingers; close the left hand's fingers
    and open the same number on the right hand (transferring), then write the
    addition and its result — the + sign and the sum are introduced here
    (printed 86).
  - Draw tally marks (چوب خط) for each pictured group, then complete the
    addition expression (عبارت جمع); below, find two numbers whose sum is the
    number written at the head of a column (printed 87).
  - Colour blue squares to match the left-hand number and green squares to
    match the right-hand number, count the coloured squares and write the sum
    (printed sums include 4 + 2, 2 + 3, 3 + 4, 6 + 3, 5 + 5, 4 + 6, 7 + 3);
    the page's teaching note is the written symbol for 10, before tens/ones
    are named (printed 88).
  - Find the pattern (الگویابی کن): colour the right half of a shape like its
    left half (symmetry), and complete a magic table (جدول شگفت‌انگیز) (printed 89).
  - Find two numbers whose sum is the number at the head of each column
    (heads 7, 8, 9, 10), written out systematically; continue a shape pattern
    in the same order (printed 90).
  - Work with tools (با ابزار کار کن): join equal numbers with a ruler so the
    figure on the left is reproduced; the joined figure is symmetric (printed 91).

- **Section 14 (printed 92–98): subtraction as a written expression.**
  - Picture tablet 14 (printed 92).
  - Close as many left-hand fingers as the right hand shows; say what number
    the hand now shows and write the subtraction for the pictures — the −
    sign and writing a subtraction expression are introduced here (printed 93).
  - "How many were there? How many went? How many remain?" — write a
    subtraction expression for each pictured scene (printed 94).
  - Add by drawing a picture or colouring, following the example
    (4 + 3, 3 + 5, 5 + 2, 6 + 3, 7 + 2, 5 + 5); complete the magic tables
    below (printed 95).
  - Complete (کامل کن): subtract following the worked example 6 − 2 = 4, by
    crossing out (8 − 5, 5 − 3, 7 − 4, 9 − 6, 10 − 5); measure — say how many
    small shapes / blocks long each pictured object is, in "a little longer
    than … blocks" sentences (printed 96).
  - Add by colouring: use a different colour for each number and find the sum
    by colouring; includes adding three numbers (1 + 3 + 2, 2 + 2 + 2,
    0 + 2 + 4) and making 7 from three numbers (printed 97).
  - Work with tools: complete the right side of a shape with the stencil
    (شابلون) and colour it so the two halves match (symmetry) (printed 98).

- **Section 15 (printed 99–105): grouping; tens bundles; numbers past 10.**
  - Picture tablet 15 (printed 99).
  - Group the shapes by drawing lines, following the number beside each part
    — the side number gives the size of each group (groups of 4, 6, 3, 5, 7
    and 10), stating each result as "… groups of … and … ones"; grouping as
    preparation for place value (printed 100).
  - **Make tens bundles (دسته‌های ده‌تایی درست کن) in each part and write the
    suitable number in the blank** — "… tens bundles and … ones" (printed 101).
  - Fill the blanks with the suitable number, entering pictured bundles in a
    tens/ones table (جدول ده‌تایی / یکی); the number 10 is met again as one
    tens bundle and zero ones, and numbers are read out of the table
    (printed 102).
  - Complete (کامل کن): complete tens/ones tables, and complete magic tables
    (printed 103).
  - Find the pattern: complete the right-hand side of a shape and colour the
    middle shape like the example; measure — the height of a tree is how many
    "people" (آدم) units? (printed 104).
  - Work with tools: join equal numbers (7, 8, 9, 10) with a ruler in one
    colour; the page's notes also recall geometric shapes, their corners and
    sides, and the names rectangle, square and triangle (printed 105).

- **Section 16 (printed 106–112): tallies into tens; the tens/ones table; first clock page.**
  - Picture tablet 16 (printed 106).
  - Count the shapes in each group with tally marks, make tens bundles from
    the shapes, complete the tens/ones table and write the number belonging
    to each group (numbers in the teens) (printed 107).
  - Count each group with tally marks (tallies grouped in fives) and write
    its number; the number line (محور) starting at 0 is introduced, shown
    running 0–19 (printed 108).
  - Find the pattern: colour the right half of a shape like the left half
    (symmetry); complete a magic table (printed 109).
  - Use the fingers to find addition answers — hold one number "on the
    shoulder" (5, then 10) and show the rest on the fingers — say how many
    shapes two groups have together and write the addition; sums stay below
    15 (printed 110).
  - Work with tools: join the numbers 10–19 with a ruler to the matching
    picture; each teen number is practised as one tens bundle plus ones
    (printed 111).
  - **First clock page:** look at a real clock and write the numerals on the
    clock face below, and fill the blanks — observation of the clock's
    1–12 numerals only; telling the time is expressly not taught yet. The
    page also sets the clock face beside a 0–12 line and completes
    "shorter than" length sentences for a knife and a fork (printed 112).

- **Section 17 (printed 113–119): addition with tallies; comparing results; the number line.**
  - Picture tablet 17 (printed 113) — full-page picture only; no text
    (render-verified).
  - Find sums with tally marks and write the addition, completing the
    five-tally bundles and counting the two fives as 10 (printed 114).
  - Write the suitable addition for each picture and find the result; colour
    squares in different colours to match a written addition and write its
    result — three- and four-number additions appear (a printed worked
    example 3 + 4 + 7 = 14; also 1 + 2 + 4 + 5 and 5 + 2 + 5), built on
    5 + 5 making a ten (printed 115).
  - Complete (کامل کن): work out each side, compare the two results and
    choose the suitable < or > sign (a printed worked pair: 10 − 3 = 7
    against 2 + 4 + 5 = 11) (printed 116).
  - Work with tools: enlarge a small shape with the stencil; fill in the
    magic table below (printed 117).
  - Measure (اندازه‌گیری کن): complete "the length of the fork / spoon /
    watch is between … and …" sentences — a first approximation in length
    measurement; also number the four seasons 1–4 in order (ordinal
    numbers) (printed 118).
  - Add or subtract with the help of the number line 0–10, one line per item
    (worked example 3 + 5 = 8; then 8 − 3, 6 − 4, 3 + 2 + 4, 7 − 5)
    (printed 119).

- **Section 18 (printed 120–126): counting in twos, threes and fours; first headed problem-solving page.**
  - Picture tablet 18 (printed 120).
  - Write the number of each shape and fill the blanks; practise counting
    three by three in shapes, on the line and in a number pattern
    (3–6–9–…, marked +3); also "the height of the salt cellar / the glass
    is between … and …" (printed 121).
  - Write the suitable number in the blanks and continue the patterns —
    counting two by two (6–8–10–… and 5–7–9–…, marked +2), as preparation
    for odd/even without those names; design a pattern of one's own around
    a chosen 3-shape (printed 122).
  - **Find the sums with tally marks and write the addition expression** —
    an addition-expression-with-tallies page (worked example 2 + 12 = 14;
    all sums below 20) (printed 123).
  - Fill the blanks; continue the patterns — counting four by four
    (0–4–8–…, marked +4) — fill the missing numbers in a 1–19 run, and draw
    the shape that repeats in each pattern (printed 124).
  - Work with tools: continue the patterns on both sides of a carpet and
    draw identical shapes with the stencil on both sides; fill in the magic
    table below (printed 125).
  - Solve the problem (مسئله حل کن) — the first page with this heading in
    these sections: find the answer to each addition using two colours
    (drawing / model method): 6 + 7, 8 + 5, 7 + 9, 9 + 6, 9 + 8
    (printed 126).

- **Section 19 (printed 127–133): counting in tens; whole-tens arithmetic; problems drawn and shown on the line.**
  - Picture tablet 19 (printed 127).
  - Complete the tens/ones table and write beside it the number each
    pictured set shows; continue the pattern counting ten by ten
    (10–20–30–…, marked +10) — reading and writing the multiples of 10
    begins here (printed 128).
  - Write the answers to additions and subtractions of whole tens
    (40 + 30, 50 − 10, 20 + 40, 60 − 50, and the like), done by joining or
    removing tens bundles; in each row, number a pictured sequence of jobs
    in the order they must be done (first, second, third) (printed 129).
  - Solve the problem (مسئله حل کن): for each problem draw a simple picture,
    find the answer and show it on a 0–10 number line — four joining stories
    (4 ducks in the water and 2 more come; 7 fish and 2 more put in; 6 birds
    on a branch and 4 more settle; 5 pupils playing and 4 more join)
    (printed 130).
  - Add or subtract, then choose the suitable <, > or = sign between the
    two results (printed 131).
  - Work with tools: join the dots of the right half like the left half and
    of the lower half like the upper half, so the figure has 4 identical
    parts; fill in the magic table below (printed 132).
  - Solve the problem (مسئله حل کن): show each problem both with a picture
    and on the number line and find the answer — four taking-away / part
    stories (8 birds, 3 fly away; 9 balloons, 5 float off; 7 lit candles,
    4 blown out; 10 chicks of which 3 are black — how many are not black?)
    (printed 133).

- **Section 20 (printed 134–140): two-digit numbers past 20; counting by fives.**
  - Picture tablet 20 (printed 134).
  - Fill the blanks from tens/ones tables — teaching of numbers greater
    than 20 starts here: take the two-digit number out of the place-value
    table and continue +10 patterns (14–24–34–…–94; 17–27–37–…–97)
    (printed 135).
  - Count the shapes in each group, write its number, then enter it in the
    tens/ones table; continue a counting-on pattern (53–54–55–…) (printed 136).
  - Make tens bundles, complete the tens/ones table and write the number —
    numbers from 20 to 99 are built this way (printed 137).
  - Fill the blanks and complete a shape so its two halves match; counting
    by fives, forwards (15–20–25–…–90, marked +5) and backwards (marked −5)
    (printed 138).
  - Work with tools: join dots with a ruler to make a shape with 4 identical
    parts; number a pictured sequence of actions in the right order
    (printed 139).
  - Solve the problem (مسئله حل کن): find sums and differences mentally
    from pictured tens and fives groups, continue a by-fives pattern
    (5–10–15–20–25–…–50), and solve two problems by drawing a picture
    (two tens bundles of flying pigeons and 5 more join them; two tens
    bundles of pencils on the desk and the teacher puts 3 more tens bundles
    down) (printed 140).

- **Section 21 (printed 141–147): the 1–100 table; pencil lengths "between"; clock times and duration.**
  - Picture tablet 21 (printed 141).
  - Fill the blanks from tens/ones tables (pictured numbers include 23, 39,
    71, 40); continue number sequences (47–48–…–51; …–55–…) and write the
    numbers from 63 to 75; colour the numbers table following the given
    pattern — gradual familiarisation with the 1–100 number table
    (printed 142).
  - From the coloured squares or the tally marks, write the additions and
    find the results — practice in adding multiples of 10 and groups of 5,
    converting 5-groups into tens; write as digits the numbers given in
    words (the words for one to ten) (printed 143).
  - Solve the problem (مسئله حل کن): add or subtract with tally marks, and
    solve the problems by drawing tallies — three-addend joining stories
    (4 ducks in the water, 5 more come, then 3 more; 8 pupils in class,
    4 more arrive, then 5 more) (printed 144).
  - Work with tools / measure: **a pencil's length is between which two
    numbers?** — do this for three pictured pencils and fill the blanks;
    compare the pencils in words (pencil 3 is shorter than pencil …;
    pencil 1 is the same length as pencil …; the longest pencil; the
    shortest pencil) (printed 145).
  - Find the pattern: continue +2 and +5 number patterns (4–6–8–…;
    25–30–35–…); following the example, write the time each clock shows
    (whole-hour clock faces) (printed 146).
  - Measure (اندازه‌گیری کن): do as in the example and mark in each part
    which job takes longer; clock phrases of the type "… o'clock has
    passed" and "a little [time] remains to … o'clock" — a sense of
    duration; minutes are expressly not required (printed 147).

- **Section 22 (printed 148–154): skip-counting by sixes; two-step problems on the line.**
  - Picture tablet 22 (printed 148).
  - **Skip-count chart by sixes:** fill the blanks; colour the numbers table
    (1–50) counting six by six, then complete the number pattern with the
    table's help (0–6–12–…, marked +6) (printed 149).
  - Fill the blanks with the suitable number — mental subtraction in tens
    and fives groups from pictured bundles (printed 150).
  - Solve the problem (مسئله حل کن): continue a by-twos pattern
    (2–4–6–8–…–16); solve two-step problems with the 0–20 number line
    (a bus with 18 passengers, 2 get off at each of three stops; a class of
    12, 4 come in and 5 go out) (printed 151).
  - Work with tools (با ابزار کار کن): following the written instructions,
    join the dots on a circle with a ruler — start at 2 and count two by
    two back to 2; start at 3 and count three by three back to 3; start at
    4 and count four by four back to 4; also complete the blue numbers
    around the clock face by their pattern. **This — not any weighing
    activity — is what printed 152 contains** (render-verified) (printed 152).
  - **Skip-count chart by sevens:** fill the blanks; count seven by seven
    and continue the colouring on the numbers table (1–50), completing
    7–14–21–…–49 (marked +7); a month calendar below shows the weekdays
    stepping by 7 (printed 153).
  - Fill the blanks: count backwards by fives along a 0–16 line to find the
    numbers before a by-fives run (…–20–25–30, marked −5), and match the
    tens in words (ten, twenty, thirty, …, ninety) (printed 154).

- **Section 23 (printed 155–161): skip-counting by eights; numbers in words; comparing; the calculator.**
  - Picture tablet 23 (printed 155).
  - **Skip-count chart by eights:** fill the blanks; count eight by eight
    and continue the colouring on the numbers table (1–60), completing
    8–16–24–… (marked +8) (printed 156).
  - Fill the blanks and play the game by its instructions: put a counter on
    a number from 1 to 5 on a 1–40 track, then follow the steps in order
    (5 forward, 10 forward, 5 back, 10 forward, 5 back) — where is the
    counter at the end? Counting forwards and backwards by fives from
    varied starts (printed 157).
  - Fill the blanks from pictured tens/fives/ones groups (adding and
    subtracting multiples of 10 with a one-digit number); **write as digits
    the numbers given in words** — two-digit numbers in words (eleven,
    twelve, thirteen, fourteen, fifteen, sixteen, seventeen, eighteen,
    nineteen, thirty-one, forty-three, fifty-seven) (printed 158).
  - Work with tools: follow the instructions to draw a figure — start from
    the smallest number, join the numbers in order with a ruler, and return
    to 19; below, write the addition/subtraction answers, compare and
    choose the suitable sign (e.g. 20 + 30 against 60 − 10; 25 − 5 against
    15 + 10) (printed 159).
  - Work with tools: join equal numbers with a ruler; compare with the help
    of a picture and put the suitable <, = or > sign — the page's teaching
    note introduces the calculator, its keypad and display digits
    (printed 160).
  - Fill the blanks (number patterns; the page's notes allow a calculator
    for finding the next pattern number) and solve the problems by any
    method wanted (Hamid has 18 story books and his father gives him 9
    more; Maryam has 9 story books and 27 science books — how many books
    altogether?) (printed 161).

- **Section 24 (printed 162–168): multi-step problems; clock times "between"; stencil shapes named.**
  - Picture tablet 24 (printed 162).
  - Solve the problem (مسئله حل کن): fill the blanks on a 0–20 number line
    and solve by drawing a picture — the sub-problem (زیر مسئله) strategy:
    Ali has a 12-pack and is given a 6-pack of coloured pencils (1: how many
    pencils has he? 2: he takes the pencils shown in the picture from the
    two packs — how many has he taken? 3: how many remain?); Zahra's 18
    coloured pencils, 6 left at home and 6 given to a friend at school —
    how many remain? (printed 163).
  - Measure (اندازه‌گیری کن): do as in the example — read the pictured
    clocks (whole hours), and in the lower part state that the time is
    between one hour and the next (worked example: between 4 and 5
    o'clock); reading the time in minutes is expressly not taught
    (printed 164).
  - Work with tools: a carpet is divided into 4 parts — colour 5 squares of
    one part, then complete the other 3 parts exactly like it (symmetry
    about both axes); fill the blanks counting in tens in words
    (fifty–sixty–seventy–eighty–ninety; ninety-one, ninety-two, …)
    (printed 165).
  - Work with tools: each shape's name is written (square, triangle,
    circle, rectangle) — draw a shape like it with the stencil; then build
    a figure with the stencil, colour it, and say how many times each shape
    was used; pupils learn to write (spell) the shape names (printed 166).
  - Solve the problem (مسئله حل کن): solve like the example with tally
    marks or a drawing and write an addition or subtraction expression for
    the solution — from this page pupils write the expression for a
    problem (12 chocolates in the dish, the children ate 7; 18 coloured
    stars, 8 pasted in a notebook; 17 game cards in hand, 6 put on the
    table; 11 coloured beads and 4 more red ones bought; 12 spoons at home
    and a pack of 6 more bought) (printed 167).
  - Solve the problem (مسئله حل کن): solve with tally marks, beads or other
    things, then complete the sentences — two-step problems (6 white and
    8 pink flowers in the vase, 10 flowers withered — how many fresh
    flowers are in the vase?; 9 yellow and 7 red sheets of coloured paper,
    12 sheets given to friends — with how many sheets was the kite made?).
    A second headed task on the same page asks, **in each row, which is
    heavier — mark it with a ×**: the rows picture a school satchel against
    a balloon, and a pencil against a calculator (printed 168).
    *Repair note:* this is a render-verified activity of printed 168. It is
    **not** the old filing's item at printed ~152 — printed 152 is the
    count-by-2s/3s/4s dot-joining page (see §22 above) and carries no such
    activity. The text layer spells the word in this line in a garbled
    form (سنگنی), which is why a text-layer search for سنگین‌تر misses it.

- **Section 25 (printed 169–175): consolidation problems; counting sequences; sufficient information; the design task.**
  - Picture tablet 25 (printed 169).
  - Solve the problem (مسئله حل کن): fill the blanks with the help of the
    picture, then solve the problems using the picture — two-step
    subtractions (Mehri's 24 childhood photos: grandmother takes 8, then
    an aunt takes 8 more; Ali's 27 marbles: 7 given to Reza and 5 more to
    Mohammad) (printed 170).
  - Solve the problem (مسئله حل کن): solve the problems below by any method
    wanted, and mark with a × which job is done in the shorter time —
    a class of 33 pupils whose teacher gave every pupil a pencil at the
    start of the year and another pencil in Aban (how many pencils given
    in all?); 74 chocolates to be packed in bundles of ten (how many tens
    bundles, and how many remain?) (printed 171).
  - Write the counting sequences from memory, without pictures: from 20 to
    30 one by one; from 10 to 90 ten by ten; from 90 to 99 one by one;
    from 10 to 50 five by five; from 70 to 95 five by five (printed 172).
  - Solve the problem (مسئله حل کن): first fill the blanks with the help
    of the pictures, then solve using a picture — sub-problems again
    (29 pupils in the first-year class, 9 went out; the second-year class
    of 27: 9 went to play football and then 9 more to skip rope — how many
    remain in class?) (printed 173).
  - Solve the problem (مسئله حل کن): **"If the information in the problem
    is sufficient, solve it" (اگر اطلاعات مسئله کافی است آن را حل کن)** —
    pupils must spot extra or missing information: (1) a bus has 40 seats,
    24 passengers were on it and 4 got off at the station — the question
    asks how many seats the bus has; (2) a 2-shelf bookcase with 12 books
    on the first shelf and 13 on the second, 4 books moved from the first
    shelf to the second — how many books in the bookcase altogether?;
    (3) two taxis carrying 4 and 3 passengers, with an unspecified number
    getting off and on along the way — how many passengers got off at the
    end of the route? Below, draw the hands of the last clock following
    the pattern of the clocks shown (printed 174).
  - Work with tools / design (با ابزار کار کن / طراحی کن): design a
    beautiful carpet with the stencil, ruler and coloured pencils, using
    everything learned about pattern-finding and symmetry — the book's
    last content page (printed 175).

  *Repair note (citation check + repair re-read, 2026-11-06):* the old
  §13–25 bullets cited pages derived from a wrong 6-page section span;
  every item above is re-filed at its folio-verified page. One old item
  was NOT located as filed: a "heavier/lighter comparison" cited at
  printed ~152 — printed 152 is a count-by-2s/3s/4s dot-joining activity;
  a real heavier-marking activity exists at printed 168 (§24) and is
  filed there.

### 5. Honest negatives — Grade 1 does NOT teach
No multiplication or division in any form; no fractions (halves appear only as
"two equal halves" of a symmetric picture, never as a fraction concept or notation);
no written column addition/subtraction algorithm (all work is counting, tallies,
fingers, drawings and the number line); numbers stay within 100 and mostly within
20 for operations; no money; no formal units (length is paper clips, blocks and
people; time is whole hours and "which takes longer"); no negative numbers, no
algebra, no graphs/charts beyond the magic-table grids.

### 6. Errors
**Confirmed errors: 0.** No printed worked value in this book survived as a
candidate: the book prints almost no completed arithmetic (answers are left blank
for the pupil), and the few completed examples visible in the text layer
(e.g. the 4 = 4 equality picture task) are correct. Deliberate error-spotting
exercises: none identified in Grade 1.

### 7. Answer keys
None — see band header.

### 8. Slips/defects of the held copy
PDF p. 3 is blank in the text layer (image page), PDF p. 119 likewise (a section
tablet, picture only), and PDF pp. 182–184 are blank/back pages. No page is missing
or duplicated; the printed sequence 1–175 is complete and in order.

---

## Grade 2 — g02.pdf

### 1. Identity
- Persian title as printed (cover): **ریاضی ـ دوم دبستان** — "Mathematics — Second [grade of] Primary School".
- Grade: 2. Publisher: OERP (سازمان پژوهش و برنامه‌ریزی آموزشی), Ministry of Education.
- Imprint (PDF p. 2): book code **205**; printing as printed: **چاپ پانزدهم 1405** —
  15th printing, year 1405. Printer: Offset Co., Tehran.
- ISBN as printed: **978-964-05-2078-9**.
- PDF pages: **152**. Printed pages: 1–144, plus one unnumbered stencil appendix page
  (PDF p. 151) and the back page (PDF p. 152).
- **Offset: PDF page = printed page + 6** (PDF p. 8 = printed 2; verified late at
  PDF p. 149 = printed 143).
- Authors (imprint): Khosro Davoudi, Arash Rastegar, Vahid Alamian.

### 2. Kind proof
Cover + imprint name it the Grade-2 pupil's Mathematics book (ریاضی ـ دوم دبستان,
code 205); the preface (PDF p. 5) describes the pupil-facing structure (Activity,
Classwork, Exercise, puzzles for interested pupils) — a pupil's textbook, not a
workbook or guide.

### 3. Contents (8 chapters; chapter-start pages are printed pages, from the
visual contents, PDF p. 6 — thumbnails of each chapter's opener)
1. عدد و رقم — Number and Digit — p. 1
2. جمع و تفریق اعداد دو رقمی — Addition and Subtraction of Two-Digit Numbers — p. 19
3. اشکال هندسی — Geometric Shapes — p. 37
4. عددهای سه رقمی — Three-Digit Numbers — p. 55
5. اندازه‌گیری — Measurement — p. 73
6. جمع و تفریق اعداد سه رقمی — Addition and Subtraction of Three-Digit Numbers — p. 91
7. کسر و احتمال — Fractions and Probability — p. 109
8. آمار و نمودار — Statistics and Graphs — p. 127

Each chapter: four lessons + one problem-solving unit + chapter review (preface, PDF p. 5).

### 4. Everything taught, chapter by chapter (printed pages; PDF = printed + 6)
- **Ch. 1, Number and Digit (pp. 1–18).** Counting accurately (mark each object once;
  last number said is the count, p. 2); tally marks in pairs work and a 1–9 "amazing
  table" grid puzzle (p. 3); reading clock hours as review (p. 4); tens bundles and
  ones — build two-digit numbers from ten-bundles, count in tens to 90, read numbers
  in words (ده، بیست، سی… هشتاد) (p. 5); write 23 = 2 tens and 3 ones, 47 = 4 tens and
  7 ones; digit, ones digit (یکان) and tens digit (دهگان) named (p. 6); continue
  number sequences, numbers in words (p. 7). Problem solving: **drawing a picture**
  (رسم شکل) incl. number-line work to 16 (pp. 8–9). Addition/subtraction review with
  fingers, counters and colouring squares in two colours to make sums (pp. 10–12);
  counting in groups (شمارش چندتا چندتا) building towers of 4 blocks per floor
  (pp. 13–14); chapter review incl. approximate addition/subtraction language (pp. 16–18).
- **Ch. 2, Add/Subtract Two-Digit Numbers (pp. 19–36).** Add/subtract whole tens with
  bundles (p. 20) and by analogy 3 + 5 → 30 + 50 (p. 21); mixed drills with pictures
  and the number line (pp. 22–24); addition/subtraction tables using the number line
  (p. 25). Problem solving: **systematic listing / pattern-making** (الگوسازی) —
  e.g. all two-digit numbers with given ones/tens digits, counting colourings (pp. 26–27).
  Column (vertical) addition/subtraction of two-digit numbers with bundles:
  34 + 23 set out in columns, adding tens first (pp. 28–29); with regrouping —
  24 + 37 by exchanging ten ones for a ten-bundle (pp. 30–31); using the 1–99 number
  grid to add/subtract (p. 32); mixed column practice (p. 33); review: approximate
  answers for two-digit sums/differences (pp. 34–36).
- **Ch. 3, Geometric Shapes (pp. 37–54).** Review of circle, rectangle, square,
  triangle drawn with the stencil; compare square vs rectangle (sides/corners)
  (pp. 38–40); relations between shapes — cut the end-of-book square into 7 pieces
  (tangram-like) and build new shapes (pp. 41–43); draw a shape from a description
  ("4 sides and 4 corners; 4 equal sides") (p. 43). Problem solving: **finding a
  pattern** (الگویابی) — next figure in a sequence, number patterns 1, 5, 9, 13, 17…
  (pp. 44–45). Symmetry (تقارن): fold on the dotted line to get two identical halves;
  complete the other half from the symmetry line; shapes with two symmetry lines;
  divide squares into 2 and then 4 equal parts and build shapes from the pieces
  (pp. 46–51); review incl. writing clock times two ways (8:15, "quarter past")
  (pp. 52–54).
- **Ch. 4, Three-Digit Numbers (pp. 55–72).** Money first: hundred-bundles in banks;
  the rial as the country's unit, coins and banknotes (pp. 56–57); three-digit numbers
  on a 0–900 number line (p. 58); hundreds/tens/ones place-value table; writing
  numbers such as 508, 349, 420 in words (pp. 59–61). Problem solving: **eliminating
  unwanted cases** (حذف حالت‌های نامطلوب) — build all three-digit numbers from three
  digit cards, find smallest/largest (pp. 62–63). Rounding/approximation of
  three-digit numbers (p. 64); writing three-digit numbers by adding ones, tens,
  hundreds (103 to 114 one by one; patterns in tens and hundreds) (pp. 65–66);
  preparation for addition/subtraction: extend the 1–100 grid, add/subtract hundreds
  on the number line (pp. 67–68); word problems with scoring gains/losses (p. 69);
  review (pp. 70–72).
- **Ch. 5, Measurement (pp. 73–90).** Length with arbitrary units, comparing results
  (pp. 74–76); measuring more precisely by folding a paper strip into 2, then 4,
  then 16 equal parts (pp. 77–79). Problem solving: **guess and check** (حدس و
  آزمایش) (pp. 80–81). The centimetre: measure with a 20 cm ruler, length 13 cm
  read off; a length "between __ and __ centimetres" (pp. 82–84). The millimetre:
  10 mm = 1 cm, count millimetre marks from zero (pp. 85–87); review: measure sides
  of shapes, find a segment's midpoint, estimate before measuring (pp. 88–90).
- **Ch. 6, Add/Subtract Three-Digit Numbers (pp. 91–108).** Comparing numbers:
  compare by hundreds first (201 vs 99, 100 vs 91) (pp. 92–94); three-digit
  addition/subtraction by parts — add hundreds, tens, ones separately (214 + 342
  modelled with bundles) and the matching mental/approximate method (pp. 95–97).
  Problem solving: **breaking into sub-problems** (زیر مسئله) (pp. 98–99). Addition
  in the place-value table with regrouping (ones→tens, tens→hundreds exchanges drawn
  with bundles) (pp. 100–102); subtraction in the place-value table with borrowing
  (open a hundred-bundle into ten tens) (pp. 103–105); review (pp. 106–108).
- **Ch. 7, Fractions and Probability (pp. 109–126).** A part of a unit: tenths of a
  centimetre strip — "one part of 10 parts" language throughout, **no fraction
  notation yet** (pp. 110–112); meeting the fraction concept by folding a square
  sheet in half and into equal parts; "1 part of 2", "1 part of 4 equal parts"
  sentences completed for coloured shapes (pp. 113–115). Problem solving: **solving a
  simpler problem** (حل مسئله‌ی ساده‌تر) (pp. 116–117). Probability concept
  (مفهوم احتمال): draw a bead unseen from a bag of 5 red + 1 white — can we know the
  colour beforehand? repeat the experiment 15 times and record (pp. 118–120);
  probability and fraction together: spinner coloured in parts — what fraction of
  the spinner is blue, which colour is most likely (pp. 121–123); review (pp. 124–126).
- **Ch. 8, Statistics and Graphs (pp. 127–144).** Census/data collection (سرشماری):
  ask every classmate a question and tally it (pp. 128–130); bar chart (نمودار
  ستونی): draw beads from a bag and colour one square per draw to build the chart
  (p. 131); measure classmates' heights into a table (p. 132); weather tally into a
  chart (p. 133). Problem solving: **symbolic methods** (روش نمادین) — find the
  unknown in □ + 27 = 53 type statements (pp. 134–135). Pictograph (نمودار تصویری)
  with approximate counts — is 23 nearer 20 or 30? one picture = 10 trees (pp. 136–139);
  choosing a chart (انتخاب نمودار) for a day's activities (pp. 139–141); review
  (pp. 142–144).

### 5. Honest negatives — Grade 2 does NOT teach
No multiplication or division (group counting stops at repeated grouping); no
fraction notation a/b (fractions are only "k parts of n equal parts" in words, and
probability is qualitative — more/less likely, no numerical probability); no decimals;
no negative numbers; no algebra beyond a missing-addend box; no perimeter or area
formulas (area appears only as covering a surface with pieces, a puzzle); no mass or
capacity units; angle is not named (only corners of shapes); time is hours and
quarter-hours on a clock face, no elapsed-time calculation.

### 6. Errors
**Confirmed errors: 0.** The recompute scan's Grade-2 hits (e.g. apparent
"760 − 210 = 840" on PDF p. 102 and "430 + 200 = 520" on PDF p. 103) are extraction
interleavings of the part-by-part mental method page (printed p. 96) and of parallel
exercise columns (printed p. 97) — the printed pages present the working in columns
that the RTL text layer splices; no single printed line states a wrong result.
Deliberate error-spotting exercises: none identified in Grade 2. (The Ch. 8
"which colour is wrong/right" items are prediction experiments, not error-spotting.)

### 7. Answer keys
None — see band header.

### 8. Slips/defects of the held copy
None found. Printed sequence 1–144 complete; PDF p. 151 is the unnumbered stencil
appendix (shapes to cut out, referred to from Ch. 3), PDF p. 152 the publisher's
back page.

---

## Grade 3 — g03.pdf

### 1. Identity
- Persian title as printed (cover): **ریاضی ـ سوم دبستان** — "Mathematics — Third [grade of] Primary School".
- Grade: 3. Publisher: OERP (سازمان پژوهش و برنامه‌ریزی آموزشی), Ministry of Education.
- Imprint (PDF p. 2): book code **305**; printing as printed: **چاپ چهاردهم 1405** —
  14th printing, year 1405. Printer: Offset Co., Tehran.
- ISBN as printed: **978-964-05-2334-6** (text layer prints it in reversed group
  order; the digits are as listed here and match the set record's pattern).
- PDF pages: **152**. Printed pages: 1–151; PDF p. 152 is the publisher's back page.
- **Offset: PDF page = printed page + 0** — this book counts its front matter in the
  printed pagination (established at the contents page, PDF p. 4, whose first lesson
  page is 8, and verified late: PDF p. 151 = printed 151).

### 2. Kind proof
Cover + imprint name it the Grade-3 pupil's Mathematics book (ریاضی ـ سوم دبستان,
code 305); the preface (PDF p. 5) describes the pupil lesson structure (Activity,
Classwork, Exercise, chapter review with puzzles) — a pupil's textbook.

### 3. Contents (from the printed فهرست, PDF p. 4; printed pages)
- **Ch. 1 الگوها — Patterns:** Problem solving: pattern-finding 8; Counting in groups 10;
  Input–output machines 13; Time in the afternoon 16; Symmetric patterns 19; Review 22.
- **Ch. 2 عددهای چهار رقمی — Four-Digit Numbers:** Problem solving: systematic listing 26;
  Introducing the thousand 28; Place value 31; Value of money 34; Approximating numbers 37; Review 40.
- **Ch. 3 عددهای کسری — Fraction Numbers:** Problem solving: drawing a picture 44;
  Fraction 46; Using fractions in measurement 49; Equality of fractions 52;
  Comparing fractions 55; Review 58.
- **Ch. 4 ضرب و تقسیم — Multiplication and Division:** Problem solving: symbolic methods 62;
  Multiplication 64; Multiplying one-digit numbers 67; Properties of multiplication 70;
  Division 73; Review 76.
- **Ch. 5 محیط و مساحت — Perimeter and Area:** Problem solving: sub-problems 80;
  Line, ray and segment 82; Perimeter 85; Size of a surface 88; Unit of area 91; Review 94.
- **Ch. 6 جمع و تفریق — Addition and Subtraction:** Problem solving: solving a simpler
  problem 98; Comparing numbers 100; Addition and subtraction 103; Addition in the
  place-value table 106; Subtraction in the place-value table 109; Review 112.
- **Ch. 7 آمار و احتمال — Statistics and Probability:** Problem solving: guess and check 116;
  Data tables 118; Probability 121; Pie chart 124; Choosing a chart 127; Review 130.
- **Ch. 8 ضرب عددها — Multiplying Numbers:** Problem solving: eliminating unwanted
  cases 134; Multiplying by 10 136; One-digit × multi-digit 139; Calculating a
  product 142; Division with remainder 145; Review 148.

### 4. Everything taught, chapter by chapter (printed pages = PDF pages)
Lesson rhythm throughout: فعالیت (Activity) → کار در کلاس (Classwork) → تمرین
(Exercise); chapter review adds فرهنگ نوشتن and a معما و سرگرمی (puzzle) page.
- **Ch. 1, Patterns (pp. 1–24).** Chapter opener: the moon's repeating phases (p. 7 in
  PDF terms = printed 7, chapter tablet). Pattern-finding strategy: continue number
  patterns and state the rule (jumps of +2, +3, +4…; 0, 1, 4, 9… squares appear as a
  picture pattern) (pp. 8–9); a shopkeeper's profit table (+50 each time) used to
  predict (p. 9). Counting in groups: count squares 3-by-3 and 4-by-4, write as
  repeated addition 3+3+3+3 = 12 (pp. 10–12) — the seed of multiplication. Input–output
  machines (ماشین‌های ورودی ـ خروجی): a machine adds/subtracts a fixed number; find the
  rule and missing outputs (pp. 13–15). Time in the afternoon: 24-hour reading —
  "afternoon" times, times like 19:25 written and read two ways (pp. 16–18). Symmetric
  patterns: complete the half picture across a symmetry line; count small triangles
  using symmetry (pp. 19–21). Review incl. writing times both ways (pp. 22–24).
- **Ch. 2, Four-Digit Numbers (pp. 25–42).** Systematic listing strategy: all
  three-digit numbers with a given hundreds digit, in order, so none is missed
  (pp. 26–27). The thousand introduced with hundred-bundles: 1000 as 10 hundreds;
  four-digit numbers in the place-value table (pp. 28–30); place value and expanded
  writing (pp. 31–33). Value of money: what 5000 rials / 1000 tomans can buy; a
  (fictional) exchange — 1 dollar of "Shekarestan" = 1200 tomans, find 3 dollars
  (pp. 34–36). Approximating numbers: round by place; expanded form 678 = 600 + 70 + 8
  (pp. 37–39). Review incl. unit choice (a maths book's mass 127 g; 325 cm = 3 m 25 cm)
  (pp. 40–42).
- **Ch. 3, Fraction Numbers (pp. 43–60).** Drawing-a-picture strategy (pp. 44–45).
  The fraction: equal parts of a shape/quantity, written with numerator and
  denominator for the first time in the band; write a fraction for each pictured
  shape; estimate what fraction of a glass is filled (pp. 46–48). Fractions in
  measurement: fractions of a metre strip and of an hour (minute hand from 2 to 2:30
  is what fraction of a turn); place fractions on the number line past 1 (pp. 49–51).
  Equal fractions: same amount shown with different partitions (pp. 52–54).
  Comparing fractions with pictures, < > = (pp. 55–57). Review incl. right angles
  recognised in shapes (pp. 58–60).
- **Ch. 4, Multiplication and Division (pp. 61–78).** Symbolic-methods strategy
  (pp. 62–63). Multiplication: arrays of squares counted by grouping, written as a
  multiplication sentence (pp. 64–66); "twice as many" language; multiplying one-digit
  numbers — build and complete the multiplication table (جدول ضرب) with strategies,
  not rote first (pp. 67–69). Properties of multiplication: count an array two ways
  (commutativity seen from grouping); table facts used in equalities (pp. 70–72).
  Division: grouping a set into equal groups; for one picture write one multiplication
  and two divisions (inverse relation) (pp. 73–75). Review: find 12 ÷ 3 by
  multiplication (pp. 76–78).
- **Ch. 5, Perimeter and Area (pp. 79–96).** Sub-problem strategy (pp. 80–81). Line,
  ray and segment (خط، نیم‌خط و پاره‌خط): name, draw, measure segments with a ruler
  (pp. 82–84). Perimeter: measure sides and add; perimeter of regular shapes by
  multiplication (pp. 85–87). Size of a surface: compare areas by counting unit
  squares on grids (pp. 88–90). Unit of area: the 1 cm square; area in square
  centimetres; area of a rectangle by counting rows (a 6 cm by 3 cm example is
  measured, formula still counting-based) (pp. 91–93). Review (pp. 94–96).
- **Ch. 6, Addition and Subtraction (pp. 97–114).** Simpler-problem strategy
  (pp. 98–99). Comparing four-digit numbers (pp. 100–102). Addition and subtraction
  methods: number-line jumps in hundreds to 1300, money totals (pp. 103–105).
  Addition in the place-value table (column addition with regrouping, e.g. orchard
  problem 1143 + 185… in exercises) (pp. 106–108). Subtraction in the place-value
  table with borrowing, told through money stories (pp. 109–111). Review incl.
  multi-step reading problems (a 1160-page book read over three weeks) (pp. 112–114).
- **Ch. 7, Statistics and Probability (pp. 115–132).** Guess-and-check strategy
  (pp. 116–117). Data tables: read and complete tables (temperatures across a week,
  pupils' favourite sports) (pp. 118–120). Probability: roll a die 20 times and tally;
  language certain / impossible / maybe (به طور حتم اتفاق می‌افتد…) chosen for events
  (pp. 121–123). Pie chart (نمودار دایره‌ای): colour a circle by the parts of a day;
  spinner results into a pie chart (pp. 124–126). Choosing a chart for given data
  (pp. 127–129). Review (pp. 130–132).
- **Ch. 8, Multiplying Numbers (pp. 133–151).** Eliminating-unwanted-cases strategy
  (pp. 134–135). Multiplying by 10: 14 × 10, 42 × 10 patterns (pp. 136–138).
  One-digit × multi-digit: 4 × 23 by drawing/partitioning (pp. 139–141). Calculating
  a product: written multi-digit × one-digit in columns (23, 41… set out vertically)
  (pp. 142–144). Division with remainder: quotient and remainder from grouping
  pictures; 37 passengers into 4-seat taxis — how many taxis (round-up reading)
  (pp. 145–147). Review incl. 23 × 7 = 161 used to explain a related product; a car
  at 80 km/h for 3 hours (pp. 148–151).

### 5. Honest negatives — Grade 3 does NOT teach
No fraction arithmetic (no adding/subtracting fractions — equality and comparison
only, by picture); no decimals (money uses whole rials/tomans); no two-digit ×
two-digit multiplication and no long division (division is grouping, with remainder
only in Ch. 8); no divisibility rules; no negative numbers; no formal area formula
for the rectangle (areas are counted in unit squares); no angles measured in degrees
(right angle only, recognised); no mean; probability is words (certain/maybe/
impossible), never a number or fraction; no algebra beyond pattern rules stated in words.

### 6. Errors
**Confirmed errors: 0.** Scan candidates in this book were all column interleavings
(e.g. the multiplication-table completion page, printed p. 69, and the division-with-
remainder page, printed p. 146, where quotient/remainder columns splice in the text
layer). The one fully printed worked equality the scan isolated, 23 × 7 = 161
(printed p. 148, chapter review), recomputes correctly (23 × 7 = 161).
Deliberate error-spotting exercises: none identified in Grade 3.

### 7. Answer keys
None — see band header.

### 8. Slips/defects of the held copy
None found; printed sequence 1–151 complete, no duplicated pages.

---

## Grade 4 — g04.pdf

### 1. Identity
- Persian title as printed (cover): **ریاضی ـ چهارم دبستان** — "Mathematics — Fourth [grade of] Primary School".
- Grade: 4. Publisher: OERP (سازمان پژوهش و برنامه‌ریزی آموزشی), Ministry of Education.
- Imprint (PDF p. 2): book code **405**; printing as printed: **چاپ سیزدهم 1405** —
  13th printing, year 1405. Printer: Offset Co., Tehran.
- ISBN as printed: **978-964-05-2372-8**.
- PDF pages: **160**. Printed pages: 1–154.
- **Offset: PDF page = printed page + 6** (PDF p. 8 = printed 2; verified late at
  PDF p. 160 = printed 154).
- Authors (imprint): Khosro Davoudi, Arash Rastegar, Ebrahim Reyhani, Shafigheh
  Saffari-Azar, Vahid Alamian (writing group).

### 2. Kind proof
Cover + imprint name it the Grade-4 pupil's Mathematics book (ریاضی ـ چهارم دبستان,
code 405); lessons are pupil Activity/Classwork/Exercise pages — a pupil's textbook.

### 3. Contents (from the printed فهرست, PDF p. 6; printed pages)
- **Ch. 1 اعداد و الگوها — Numbers and Patterns:** Problem solving 2; Number writing 4;
  Patterns 8; Input–output machine 12; Introducing the million 16; Review 20.
- **Ch. 2 کسر — Fractions:** Problem solving 24; Knowing fractions 26; Addition and
  subtraction (of fractions) 30; Equality of fractions 34; Multiplying a number by a
  fraction 38; Review 42.
- **Ch. 3 ضرب و تقسیم — Multiplication and Division:** Problem solving 46; Multiplying
  two two-digit numbers 48; Calculating the product 52; Approximate calculations 56;
  Division and divisibility 60; Dividing by one-digit numbers 64; Dividing by
  two-digit numbers 68; Review 72.
- **Ch. 4 اندازه‌گیری — Measurement:** Problem solving 76; Angle 78; Measuring an
  angle 82; Measuring time 86; Measuring length 90; Review 94.
- **Ch. 5 عدد مخلوط و عدد اعشاری — Mixed Numbers and Decimal Numbers:** Problem
  solving 98; Mixed number 100; Decimal number 104; Decimal addition and subtraction
  108; Place value of decimals 112; Review 116.
- **Ch. 6 شکل‌های هندسی — Geometric Shapes:** Problem solving 120; Perpendicular —
  parallel 122; Quadrilaterals 126; Area of parallelogram and triangle 130;
  Perimeter and area 134; Review 138.
- **Ch. 7 آمار و احتمال — Statistics and Probability:** Problem solving 142; Broken-line
  graph 144; Probability 148; Review 152.

### 4. Everything taught, chapter by chapter (printed pages; PDF = printed + 6)
- **Ch. 1, Numbers and Patterns (pp. 1–22).** Problem solving by pattern-finding and
  drawing: triangular circle patterns 1, 3, 6, 10… — find the 7th figure two ways
  (draw on, or convert to a number pattern) (pp. 2–3). Number writing: count by
  thousands; ten-thousand cube models; numbers to 7 digits in the place-value table
  (ones… hundred-thousands), read 8,341,925 aloud in review (pp. 4–7). Patterns:
  number and figure patterns, state the rule (pp. 8–11). Input–output machines now
  carry real rules (perimeter of a triangle/square as a machine; doubling money
  tables) (pp. 12–15). Introducing the million: abacus pictures, compare numbers
  with < > up to millions (pp. 16–19). Review + puzzle (pp. 20–22).
- **Ch. 2, Fractions (pp. 23–44).** Review-openers from Grade 3 (pp. 24–25). Knowing
  fractions: fold a strip, colour a stated fraction of a shape; **mixed numbers
  pictured and read from shapes** already here (pp. 26–29). Add/subtract fractions
  with like denominators using coloured hexagon pieces and shape records (pp. 30–33).
  Equal fractions: build equal fractions from pictures; fill the missing numerator/
  denominator so fractions are equal (denominator 9 equal to 1, etc.) (pp. 34–37).
  Multiply a whole number by a fraction: repeated addition on the number line,
  then a multiplication sentence for each picture (pp. 38–41). Review incl. fractions
  of an hour in minutes (pp. 42–44).
- **Ch. 3, Multiplication and Division (pp. 45–74).** Problem solving: systematic
  listing, eliminating cases (pp. 46–47). Two-digit × two-digit: tens/ones blocks —
  16 a month for a year type stories; several pupil methods compared, then the
  shortened written form (pp. 48–51). Calculating the product: bigger multiplications
  explained by splitting (231 = 200 + 30 + 1); multiplying by 100 (15 × 100,
  350 × 100…) (pp. 52–55). Approximate calculations: 47 is between 40 and 50 but
  nearer 50; estimate sums and products; round to nearest hundred (375, 791, 807)
  (pp. 56–59). Division and divisibility: 22 sweets packed equally — when is there
  no remainder; write the division relations (dividend = divisor × quotient +
  remainder) and check by remainder (pp. 60–63). Long division by a one-digit number
  (48 shared equally; 88 ÷ 4 set out; 737 flowers among 3 schools; 848 ÷ 4, 948 ÷ 3,
  504 ÷ 4) (pp. 64–67). Division by a two-digit number: grouping model first
  (675 chairs in rows of 21), then written (742 ÷ 31, 312 ÷ 43, 802 ÷ 53; 451 ÷ 32,
  570 ÷ 28, 645 ÷ 27, 977 ÷ 65) (pp. 68–71). Review (pp. 72–74).
- **Ch. 4, Measurement (pp. 75–96).** Problem solving: listing, sub-problems
  (pp. 76–77). Angle: show and name angles in shapes; the right angle as the corner
  of a set square (گونیا) drawn on circles; acute < right < obtuse identified by
  comparison with a transparent half-circle (pp. 78–81). Measuring an angle: degrees
  with a protractor (نقاله); the two set squares' angles (45°, 90°, 30°, 60°) stated;
  measure triangle angles with the protractor (pp. 82–85). Measuring time: elapsed
  time (arrive 11:10, leave 12:20 — how long); the second as a unit; choose hour/
  minute/second appropriately (pp. 86–89). Measuring length: metres/centimetres/
  millimetres conversions in pictured tasks (join a 110 cm ribbon to a 90 cm one;
  1 m strip partitioned) (pp. 90–93). Review incl. sum of a rectangle's angles found
  with a transparent circle (pp. 94–96).
- **Ch. 5, Mixed Numbers and Decimals (pp. 97–118).** Problem solving: simpler
  problem, drawing (pp. 98–99). Mixed numbers: a 1-metre strip in equal parts;
  measure a pin with a ruler and write a mixed number; each shape shown as a mixed
  number against its unit (pp. 100–103). Decimal numbers: a bee's length as a mixed
  number then decimal; liquid amounts written as fraction and decimal; 1 litre in
  10 equal parts — tenths (pp. 104–107). Decimal addition/subtraction: pour two
  vessels into one; sums/differences on the number line and in columns (carpet
  4.1 m pieces) (pp. 108–111). Decimal place value: tenths and ones table, 0.1 cm
  readings; add decimals on the number line (1.2 + 2.3) (pp. 112–115). Review
  (pp. 116–118). **Decimals reach tenths (and hundredths only as 0.1 cm readings);
  decimal notation uses a slash-like separator (e.g. 4/1 for 4.1) as printed.**
- **Ch. 6, Geometric Shapes (pp. 119–140).** Problem solving: guess-and-check,
  symbolic methods (pp. 120–121). Perpendicular and parallel: mark right angles;
  draw a perpendicular from a point to a line with set square(s); test whether two
  lines are parallel with a set square and say why (pp. 122–125). Quadrilaterals:
  build from four segments; draw a trapezium and a parallelogram on squared paper;
  properties table (equal sides/angles, parallel sides) completed with ✓ (pp. 126–129).
  Area of parallelogram and triangle: draw the altitude from a vertex; derive the
  parallelogram's area from the rectangle, triangle as half (pp. 130–133).
  Perimeter and area: the 1 cm square = 1 cm² recalled; a square metre divided into
  10 × 10 cm squares counted; compare two pupils' carpet-area answers — **see the
  deliberate-activity note in §6** (pp. 134–137). Review (pp. 138–140).
- **Ch. 7, Statistics and Probability (pp. 141–154).** Problem solving: simpler
  problem, guess-and-check (pp. 142–143). Broken-line graph (نمودار خط شکسته): read
  and draw from tables — oil prices over ten weeks, a city's temperature every two
  hours, a patient's pulse each hour (pp. 144–147). Probability: the phrase
  "it is probable that…" quantified for the first time with fractions of a spinner —
  8-part spinner coloured so a stated colour has a stated chance; a coin comes heads
  or tails; apple colours in a fridge table used for likelihood (pp. 148–151).
  Review incl. a die thrown — express each event's probability (pp. 152–154).

### 5. Honest negatives — Grade 4 does NOT teach
No fraction × fraction and no fraction division (only whole number × fraction);
no simplifying of fractions as a named skill (equal fractions are built from
pictures); decimals stop at tenths in operations (no decimal multiplication or
division, no thousandths); no negative numbers; no ratio, proportion or percent;
no divisibility rules as rules (divisibility is only "remainder zero" checked case
by case); no circle geometry (no circumference/area, circle used only as a drawing
tool); no volume or capacity measure; no coordinates; probability is still mostly
verbal, with spinner fractions only at the end of Ch. 7; no algebra — machines and
patterns carry rules in words.

### 6. Errors
**Confirmed errors: 0.** One candidate was render-verified and is **not an error**:
printed p. 134 (PDF p. 140), Ch. 6 opening activity — two pupils answer the same
carpet-area question: Mehdi works in metres, 4 m × 3 m = 12 (m²); Hadi works in
centimetres, 400 cm × 300 cm = 120,000 (cm²). Both printed results recompute
correctly (4 × 3 = 12; 400 × 300 = 120,000), and the page's own question is "why
are the two answers different?" — a deliberate unit-difference teaching activity,
filed here as a **deliberate discrepancy activity, not an error**. Other scan hits
in this book (e.g. products on the approximate-calculation page, printed p. 58) are
exercise statements interleaved by the text layer, with no printed result.

### 7. Answer keys
None — see band header.

### 8. Slips/defects of the held copy
None found; printed sequence 1–154 complete, no duplicated pages.

---

## Grade 5 — g05.pdf

### 1. Identity
- Persian title as printed (cover): **ریاضی ـ پنجم دبستان** — "Mathematics — Fifth [grade of] Primary School".
- Grade: 5. Publisher: OERP (سازمان پژوهش و برنامه‌ریزی آموزشی), Ministry of Education.
- Imprint (PDF p. 2): book code **505**; printing as printed: **چاپ یازدهم 1404** —
  11th printing, year 1404. (This is the one band book whose imprint year is 1404,
  not 1405 — the book's own imprint governs, exactly as the set record warned.)
  Printer: Offset Co., Tehran.
- ISBN as printed: **978-964-05-2433-6** (text layer prints the groups reversed).
- PDF pages: **151**. Printed pages: 1–141.
- **Offset: PDF page = printed page + 10** (front matter is longer here — contents
  spread over PDF pp. 4–6 and the teacher's notes over PDF pp. 7–9; established at
  PDF p. 12 = printed 2, verified late at PDF p. 151 = printed 141).
- Authors (imprint): Mohammad-Hashem Rostami, Ebrahim Reyhani, Shadi Safinia,
  Mojtaba Ghorbani-Arani, Khosro Davoudi, Zohreh Pendi, Zahra Rahimi (writing group).

### 2. Kind proof
Cover + imprint name it the Grade-5 pupil's Mathematics book (ریاضی ـ پنجم دبستان,
code 505); the teacher's-note pages (PDF pp. 7–9) describe the pupil Activity /
Classwork / Exercise structure — a pupil's textbook.

### 3. Contents (from the printed فهرست, PDF pp. 4–6; printed pages)
- **Ch. 1 عددنویسی و الگوها — Number Writing and Patterns:** Review of number writing
  and numerical calculations 2; Introducing the billion 6; Addition and subtraction
  of compound (mixed-unit) numbers 10; Patterns 14; Review 18.
- **Ch. 2 کسر — Fractions:** Fractions greater than one 22; Adding and subtracting
  mixed numbers 27; Multiplying fractions 32; Dividing fractions 36; Multiplying
  mixed numbers 40; Review 44.
- **Ch. 3 نسبت، تناسب و درصد — Ratio, Proportion and Percent:** Ratio 48; Equal
  ratios 52; Proportion 56; Percent 60; Review 64.
- **Ch. 4 تقارن و چندضلعی‌ها — Symmetry and Polygons:** Axial symmetry 68; Central
  symmetry 73; Angle and bisector 75; Polygons and the sum of their angles 79;
  Review 84.
- **Ch. 5 عددهای اعشاری — Decimal Numbers:** Decimal numbers 88; Adding decimals 93;
  Subtracting decimals 96; Multiplying decimals 98; Review 102.
- **Ch. 6 اندازه‌گیری — Measurement:** Area of rhombus and trapezium 106; Circumference
  of a circle 110; Volume 113; Capacity 118; Review 122.
- **Ch. 7 آمار و احتمال — Statistics and Probability:** Collecting and displaying
  data 126; Average (mean) 130; Probability 134; Review 138.

### 4. Everything taught, chapter by chapter (printed pages; PDF = printed + 10)
- **Ch. 1, Number Writing and Patterns (pp. 1–20).** Review: place value to millions,
  what multiplying by 10 does to each digit's value; written addition/subtraction of
  large numbers (302,040 and 900,000 appear as exercise numbers) (pp. 2–5). The
  billion introduced (1,000; 1,000,000; 1,000,000,000 in one place-value table);
  two pupils' ways of computing "12 hundred-thousands" compared (pp. 6–9).
  **Compound numbers (عددهای مرکب):** add/subtract times and masses written in two
  units — a clock reading 1:55:30, adding 8 h 20 min + 2 h 50 min with the 60-minute
  carry shown; a 5 kg 500 g watermelon against a 4 kg 700 g one; metro arrival-time
  tables (pp. 10–13). Patterns: perimeters of growing square figures and number
  patterns, rule stated (pp. 14–17). Review + puzzle (nature symmetry photos) (pp. 18–20).
- **Ch. 2, Fractions (pp. 21–46).** Fractions greater than one: place mixed numbers
  2 1/…, 1 2/…, 2 2/… on the number line; convert mixed number ↔ improper fraction
  with and without pictures (pp. 22–26). Add/subtract mixed numbers: number line
  first (a pupil walks 1 3/… km Thursday, … Friday), then a worked column method in a
  table; fish masses in mixed kilograms (pp. 27–31). Multiplying fractions: "of"
  language with area/picture models — half of a half of apples; a field halved, then
  a fraction of that half planted (pp. 32–35). Dividing fractions: share 5 cakes
  equally among 3 people; each division answer written as a fraction (15 ÷ 8, 2 ÷ 7
  as exercises) (pp. 36–39). Multiplying mixed numbers: a rectangular garden with
  mixed-number sides, area by splitting (pp. 40–43). Review: three equal fractions —
  write three more and explain; **simplify fractions** (12/48 type) as a named task
  (pp. 42–46).
- **Ch. 3, Ratio, Proportion and Percent (pp. 47–66).** Ratio: part-to-part and
  part-to-whole from pictures (fruit), length-to-width of a rectangle; a futsal
  team's win/draw/loss table read as ratios (pp. 48–51). Equal ratios: half a glass
  vs half a jug of syrup — show 4/6 = 8/12; prove 12:20 = 18:30 (pp. 52–55).
  Proportion: complete proportion tables from patterns; an angle problem — two
  angles in ratio 3:5 differing by 10°, find them; speed comparisons (320 m in
  8 min vs 180 m in 6 min) (pp. 56–59). Percent: percent as "out of 100" from news
  language; 3% fat in milk worked (3 g per 100 g); find the whole given 40% of it is
  240 and 70% of another is 280 (pp. 60–63). Review incl. simplifying ratios
  (18, 20, 45…) (pp. 64–66).
- **Ch. 4, Symmetry and Polygons (pp. 67–86).** Axial symmetry: reflect shapes and
  points across a line on squared paper (pp. 68–72). Central symmetry: the Ferris
  wheel turning about its centre; find the image of a shape under a half-turn
  (pp. 73–74). Angle and bisector: draw bisectors; a bisector line in a figure used
  to find unknown angles (pp. 75–78). Polygons and angle sums: find the angle sum of
  a quadrilateral by measuring/splitting; properties of parallelogram diagonals
  (draw, measure the parts); fold a square and a rhombus on a diagonal to explain
  symmetry; trapezium with one 100° angle in review (pp. 79–83). Review (pp. 84–86).
- **Ch. 5, Decimal Numbers (pp. 87–104).** Decimals rebuilt properly: unit strip in
  tenths, then hundredths/thousandths — colour 2.6 litres, show 1.84 on squares;
  expanded form 8.133 = 8 + … + 0.003; compare with 1 (1.84 > 1) (pp. 88–92).
  Adding decimals: place-value table alignment (4.3 m + 2.5 m curtain wood); estimate
  first by deleting the decimal parts (pp. 93–95). Subtracting decimals: 2.8 km
  home-to-school distances; table method (pp. 96–97). Multiplying decimals: a frog
  jumps 0.7 m, 5 jumps; convert factors to fractions to get the product; × 0.9 —
  is the result more or less than the number (pp. 98–101). Review: why 0.6 = 0.60 =
  0.600; place 4.256 approximately on differently-scaled number lines (pp. 102–104).
  Decimal separator printed as "/" (e.g. 2/6 = 2.6) throughout, as in Grade 4.
- **Ch. 6, Measurement (pp. 105–124).** Area of rhombus and trapezium: derive a
  general rule by cutting/rearranging card (rhombus from its diagonals; trapezium
  doubled into a parallelogram) (pp. 106–109). Circumference of a circle: measure
  round objects, diameter relation, then compute circumferences incl. semicircle
  composites (pp. 110–112). Volume: guess then count unit cubes; cuboid volume by
  layers (a 20 × 11 × 5 cm tissue box in exercises) (pp. 113–117). Capacity: litre
  and millilitre in pictured pouring tasks; choose a sensible unit for a material
  (pp. 118–121). Review: why the rhombus area uses half the product of the diagonals
  (pp. 122–124).
- **Ch. 7, Statistics and Probability (pp. 125–141).** Collecting and displaying
  data: survey classmates' free hours; the Tehran book fair data; methods of
  collection named (observing, asking, …); read a line/bar display of daily maximum
  temperatures (pp. 126–129). **Mean (میانگین) introduced:** level two unequal ring
  towers to the same height; mean = sum ÷ count, stated in words; a hen-keeper's
  daily egg table; Ali walks 460 cm in 10 steps — mean step length (pp. 130–133).
  Probability: the language of chance graded; spinner experiments; record die
  results across a game and compare with expectation (pp. 134–137). Review incl.
  mean of 3.5, 2.7, 1.1, 0.7 (pp. 138–141).

### 5. Honest negatives — Grade 5 does NOT teach
No negative numbers (integers wait for Grade 6); no percent applications beyond
finding a percent of a quantity and the whole from a percent (no discount/profit/
interest — those are Grade 6); no decimal division; no fraction–decimal conversion
as a system (decimals are built from tenths strips, fractions separately); no
π beyond one working value — circle exercises instruct "take π = 3"
(printed p. 112) and a reading page gives Archimedes' bounds 3 1/7 and
3 10/71 (printed p. 111), but π is never developed as a number and 3.14
is never used; no coordinate grid; no algebraic notation
(proportion is tables and equal ratios); no standard deviation/spread — mean only;
probability still not expressed as a single fraction/percent chance in this book.

### 6. Errors
**Confirmed errors: 0.** One page was render-verified: printed p. 45 (PDF p. 55),
Ch. 2 review — its two printed worked examples recompute correctly:
7 1/8 + 1 1/4 = 8 3/8 (1/8 + 2/8 = 3/8) and 8 3/8 − 7 1/8 = 1 1/4, both as printed
on the page (checked on the render, since the RTL text layer reverses fraction
order). The scan's other Grade-5 hits are unsolved exercises (products/quotients
left blank) spliced by the text layer. Deliberate error-spotting exercises: none
identified in Grade 5.

### 7. Answer keys
None — see band header.

### 8. Slips/defects of the held copy
PDF p. 10 is blank in the text layer (image/back page of the front matter). No
missing or duplicated pages; printed sequence 1–141 complete.

---

## Grade 6 — g06.pdf

### 1. Identity
- Persian title as printed (cover): **ریاضی ـ ششم دبستان** — "Mathematics — Sixth [grade of] Primary School".
- Grade: 6. Publisher: OERP (سازمان پژوهش و برنامه‌ریزی آموزشی), Ministry of Education.
- Imprint (PDF p. 2): book code **605**; printing as printed: **چاپ یازدهم 1405** —
  11th printing, year 1405. Printer: Offset Co., Tehran.
- ISBN as printed: **978-964-05-2491-6** (text layer prints the groups reversed).
- PDF pages: **152**. Printed pages: 1–144, plus one unnumbered closing page
  (PDF p. 152 region is the last printed page's verso matter; the final printed
  page is 144, the puzzle page of Ch. 7).
- **Offset: PDF page = printed page + 8** (PDF p. 10 = printed 2; verified late at
  PDF p. 152 = printed 144).
- Authors (imprint): Mohammad-Hassan Bijanzadeh, Zohreh Pendi, Khosro Davoudi,
  Mehdi Izadi, Ebrahim Reyhani, Shadi Safinia, Mojtaba Ghorbani-Arani.

### 2. Kind proof
Cover + imprint name it the Grade-6 pupil's Mathematics book (ریاضی ـ ششم دبستان,
code 605); the teacher's note (PDF p. 6) defines the pupil structure (Activity,
Classwork, Exercise) — a pupil's textbook, the last of the primary series.

### 3. Contents (from the printed فهرست, PDF pp. 4–5; printed pages)
- **Ch. 1 عدد و الگوهای عددی — Numbers and Number Patterns:** Number patterns 2;
  Review of number writing 7; Divisibility 11; Introducing integers 16; Review 20.
- **Ch. 2 کسر — Fractions:** Adding and subtracting fractions 24; Multiplying
  fractions 28; Dividing fractions 32; Calculations with fractions 36; Review 40.
- **Ch. 3 اعداد اعشاری — Decimal Numbers:** Review 44; Review of multiplication and
  division 48; Dividing a decimal by a whole number 52; Dividing a number by a
  decimal 56; Review 60.
- **Ch. 4 تقارن و مختصات — Symmetry and Coordinates:** Centre of symmetry and central
  symmetry 64; Rotation 70; Coordinate axes 74; Symmetry and coordinates 80; Review 83.
- **Ch. 5 اندازه‌گیری — Measurement:** Length and area 88; Volume and mass 94; Area
  of a circle 98; Lines and angles 102; Review 106.
- **Ch. 6 تناسب و درصد — Proportion and Percent** (chapter tablet headed
  کسر، نسبت و تناسب — Fraction, Ratio and Proportion): Fraction, ratio and
  proportion 110; Percent 115; Uses of percent in financial calculations 121; Uses
  of percent in statistics and probability 126; Review 128.
- **Ch. 7 تقریب — Approximation:** Approximation 132; Approximate measurement and
  calculations 137; Review 142.

### 4. Everything taught, chapter by chapter (printed pages; PDF = printed + 8)
- **Ch. 1, Numbers and Number Patterns (pp. 1–22).** Number patterns: bicycles and
  wheels table (2 per bicycle); even numbers pictured as patterns; a matchstick
  pattern generalised in words (× figure number = number of sticks); colour the
  even cells of the 1–100 grid (pp. 2–6). Review of number writing: billions in
  place-value language; World-Cup crowd figures read and written; place numbers
  approximately on a number line; build target numbers from digit cards 1, 0, 3, 7,
  2, 4, 0 (pp. 7–10). **Divisibility (بخش‌پذیری):** divide hundred-bundles by 5 and
  by 2 with pictures; circle the numbers divisible by 2, then by 5, then by 3
  (127, 46, 358, 93, 5532, 74, 7000… listed); a bindery packs 282 books (pp. 11–15).
  **Introducing integers (اعداد صحیح) — the band's first negative numbers:** agree
  positive/negative directions, then read temperatures and heights/depths with +
  and − signs; noon as origin for hours before/after (pp. 16–19). Review: how to get
  a number's multiples; write three numbers under 50 divisible by none of 2, 3, 5
  (pp. 20–22).
- **Ch. 2, Fractions (pp. 23–42).** Add/subtract fractions: unlike denominators —
  find equal fractions with a common denominator first (Nahid's 3/… + 5/… litres of
  milk worked both days) (pp. 24–27). Multiplying fractions: **reciprocals
  (معکوس) defined** — two numbers whose product is 1; complete multiplication
  tables of fractions (pp. 28–31). Dividing fractions: for each picture write a
  multiplication and a division; work last year's method, then divide by
  multiplying by the reciprocal (pp. 32–35). Calculations with fractions: mixed
  multi-step problems (Raheleh spends half her money on a book, then 3/… of the
  remainder on a notebook); order fractions small-to-large and discuss methods
  (pp. 36–39). Review: how to find a fraction's reciprocal (pp. 40–42).
- **Ch. 3, Decimal Numbers (pp. 43–62).** Review: an Olympic discus throw of
  68.19 m; simplify fractions into decimal equalities (30/… type); place decimals
  on the number line (pp. 44–47). Review of × and ÷: compute (2.4 + 1.7) × 100,
  (7.5 − 2.3) × …; divisions with the remainder stated (3.6 ÷ 5 type) (pp. 48–51).
  Dividing a decimal by a whole number: long division built step by step —
  6.28 ÷ 3 talked through ("6 ones; how many ones to each part?"), then 75.3 ÷ 4,
  45.27 ÷ 16, 128 ÷ 7 (pp. 52–55). Dividing by a decimal: scale the number line;
  use an equivalent division to get quotient and remainder of a second division
  without dividing; continue equal fractions of 2/3 by ×3 (pp. 56–59). Review
  (pp. 60–62).
- **Ch. 4, Symmetry and Coordinates (pp. 63–85).** Centre of symmetry and central
  symmetry: tracing paper tests; a shape coincides with itself after a half-turn
  (180°) about a point; three pupils' methods compared; draw the image of a shape
  in a given centre; colour a shape so point "M" is its centre of symmetry
  (pp. 64–69). Rotation (دوران): rotate shapes about a point, incl. 90° with tracing
  paper; which shapes have no rotational symmetry (pp. 70–73). **Coordinate axes
  (محورهای مختصات) — the band's first coordinates:** maps in daily life; a zoo map
  with 10 m squares; give an object's location exactly; write the coordinates of a
  shape's vertices in bracket pairs (pp. 74–79). Symmetry and coordinates: read
  coordinates of a shape and of its reflection across the red line; draw a
  quadrilateral from four coordinate pairs and find its area by counting (pp. 80–82).
  Review (pp. 83–85).
- **Ch. 5, Measurement (pp. 87–108).** Length and area: choose what is being
  measured (length/area/mass) in pictured cases; area of a handprint on squared
  paper; area in mixed numbers against a unit; unit relations (1 km = 1000 m…)
  and big real areas (the Imam Reza shrine complex) estimated (pp. 88–93). Volume
  and mass: a pyramid and its net; build a cylinder from a rectangle; what length/
  width/height can a 1 m³ box have; fill unit/example blanks (pp. 94–97). **Area of
  a circle:** recall circumference; estimate the circle's area against its square
  (≈ how many times), cut-and-rearrange argument, then compute (pp. 98–101). Lines
  and angles: shortest path (perpendicular) to a point; build stated angles with
  set-square corners; angles formed when two lines cross (vertical angles in
  pictured work); pins on a circle (pp. 102–105). Review: convert units across
  length/area/volume/capacity (pp. 106–108).
- **Ch. 6, Proportion and Percent (pp. 109–130).** Fraction, ratio and proportion:
  a multiple-choice test's results as fractions/ratios; scale tables (×1.5, ×4,
  ÷2); three boys' money in ratio 2 : … : … problems; compare syrup sweetness by
  ratio, with a graph offered as another comparison (pp. 110–114). Percent: write
  each fraction as decimal, fraction and percent (coloured cells of a grid);
  production up 1.5 times expressed in percent (pp. 115–120). **Percent in financial
  calculations:** a bookshop keeper's daughter works the till — an item sold at
  20% profit on cost has selling price 24,000 tomans, find the cost; 15% discount
  before Nowruz; CDs bought at 89% of price (pp. 121–125). **Percent in statistics
  and probability:** siblings survey data as percents; in many coin tosses expect
  heads about 50% of the time (pp. 126–127). Review: find examples of 50% around you
  (pp. 128–130).
- **Ch. 7, Approximation (pp. 131–144).** Approximation: a water bill read rounded;
  **two methods named — truncating (قطع کردن: replace right-hand digits with zeros)
  and rounding (گرد کردن)**; Ahmad tells the class "we used to round another way"
  and the methods are compared (pp. 132–136). Approximate measurement and
  calculations: how far can a measuring tool be trusted; read a 2000-rial coin's
  diameter on a ruler to the millimetre; a carpenter multiplies approximate side
  lengths for an area (pp. 137–141). Review incl. a worked discussion item: Ahmad
  computes 34.2 × 11.2 by truncating to whole numbers and gets a stated value —
  pupils judge the size of his error (printed p. 141). **This is a deliberate
  approximation exercise, not an error** (see §6).

### 5. Honest negatives — Grade 6 does NOT teach (and band-level negatives)
No operations with negative numbers (integers are only signed readings of
temperature/height/time — no integer addition or subtraction); no algebra — no
letters for unknowns, no equations (proportion and patterns stay numerical/verbal);
no percent-of-a-percent or compound change; no π value stated in the text layer
(circle area is estimated then computed with the diameter/radius relation as
taught in class activity); no area of a triangle/parallelogram re-derivation
(Grade 5 results are used); no probability as a computed fraction — percent
expectation for a coin is the closest; no mean re-teaching (Grade 5's mean is not
revisited); no graphs beyond the displays of earlier grades (no new chart type);
no square roots, powers or exponents anywhere in the band.

### 6. Errors
**Confirmed errors: 0.** Two items were examined closely and are **deliberate
exercises, not errors**, filed here so they are not later mistaken for errors:
(a) printed p. 59 (PDF p. 67): "Which of the divisions has been done correctly?
Which answers are wrong, and why?" — a deliberate error-spotting exercise in which
pupils judge given decimal divisions (one shows 0.04 in the working); the book
prints the suspect workings *as the exercise material*, not as results.
(b) printed p. 141 (PDF p. 149), last page of the "Approximate measurement
and calculations" lesson: Ahmad's truncated
multiplication 34.2 × 11.2 is printed precisely so pupils can discuss how far the
truncated answer (34 × 11 = 374) sits from the exact product (383.04, my
recomputation) — a deliberate approximation-discussion item. All other scan hits
in this book are unsolved exercises spliced by the RTL text layer.

### 7. Answer keys
None — see band header.

### 8. Slips/defects of the held copy
PDF p. 8 is blank in the text layer (image page in the front matter). No missing
or duplicated pages; printed sequence 1–144 complete.

---

## Band A totals

| Book | File | PDF pages | Printed pages | Chapters | Confirmed errors |
|---|---|---|---|---|---|
| Grade 1 | g01.pdf | 184 | 1–175 (25 untitled sections) | 25 sections | 0 |
| Grade 2 | g02.pdf | 152 | 1–144 | 8 | 0 |
| Grade 3 | g03.pdf | 152 | 1–151 | 8 | 0 |
| Grade 4 | g04.pdf | 160 | 1–154 | 7 | 0 |
| Grade 5 | g05.pdf | 151 | 1–141 | 7 | 0 |
| Grade 6 | g06.pdf | 152 | 1–144 | 7 | 0 |
| **Band A total** | **6 files** | **951** | **909 printed pages** | **37 chapters + G1's 25 sections** | **0** |

Band negatives in one line: the primary course runs counting → place value to
billions → the four operations (long division by two-digit divisors in G4) →
fractions with all four operations (G5–G6) → decimals with all four operations
(G5–G6) → ratio/proportion/percent incl. simple financial percent (G5–G6) →
geometry through symmetry, coordinates and circle area → statistics through mean
and pie/broken-line charts; it contains **no negative-number arithmetic, no
algebra or equations, no powers/roots, and no numerical probability**, and no
book in the band carries an answer key.

---

## Band B — Lower secondary (Grades 7–9)

Band reader filing for the LiqLearns courses read of the Iran mathematics set.
Set context: `../set-verification.md` (22 files in hand; this band = the 3 lower-secondary
Mathematics pupil books, no branch split, no teacher guides or workbooks in the set).

**Method honesty:** Each book was read in full, page by page, from the extracted text layer
(`../scratch/txt/g07.txt`, `g08.txt`, `g09.txt`, split per PDF page). Persian text extracts
in RTL order and Persian/Arabic-Indic digits are garbled in places; every identity datum
below was cross-checked on the imprint page, and the covers were checked on page renders.
Any number filed as a *confirmed book error* was recomputed by the reader AND verified
against a `pdftoppm` page render; suspicions visible only in the text layer are marked
"unverified" and kept out of the error count. All summaries are the reader's own English;
no textbook passage is transcribed (formulas and short technical terms only).

**Answer keys (whole band):** None of the three books carries an answer key, worked-solution
section or پاسخنامه — confirmed by full read and by text search (0 hits in all three files).
Exercises are open for the teacher/class to resolve.

---

## Book 1 — Grade 7 Mathematics (g07.pdf)

### 1. Identity block

- Persian title as printed (imprint): ریاضی ـ پایهٔ هفتم دورهٔ اول متوسطه
  ("Mathematics — Grade 7, First Period of Secondary School").
  Cover (render-checked, PDF p. 1): ریاضی / پایهٔ هفتم / دورهٔ اول متوسطه.
- Grade: 7 (first year of lower secondary).
- Publisher / پدیدآورنده: سازمان پژوهش و برنامه‌ریزی آموزشی (OERP — Organization for
  Educational Research and Planning), Ministry of Education; printed by شرکت چاپ و نشر
  کتاب‌های درسی ایران (Iran Textbook Printing and Publishing Company).
- Printing as printed on imprint (PDF p. 2): چاپ چهاردهم ۱۴۰۵ — **14th printing, 1405**
  (school year 1405–1406). The imprint also notes the book was comprehensively revised in
  school year 1392–93 by the mathematics group of the Textbook Authoring Office.
- ISBN as printed: **978-964-05-2242-4** (شابک 978-964-05-2242-4).
- Book code as printed: **705** (in the book-name line: … ـ ۷۰۵).
- PDF pages: **135**. Printed pages 1–124 plus front matter.
- Offset: **printed page = PDF page − 10** (printed p. 1, the Chapter 1 opener, is PDF p. 11;
  the last content page, printed 124, is PDF p. 134; PDF p. 135 is blank, and PDF p. 10 is a
  blank coloured divider page — render-checked, not a defect).

### 2. Kind proof

Cover + title/imprint name the book simply «ریاضی ـ پایهٔ هفتم» with pupil-facing apparatus
throughout (فعالیت activity, کار در کلاس classwork, تمرین exercises addressed to the student,
plus a سخنی با دانش‌آموز "a word to the student" preface, printed pp. before ch. 1): a pupil's
textbook, not a teacher guide or workbook.

### 3. Contents (printed pages)

| Ch. | Title (English) | Printed pp. |
|---|---|---|
| 1 | Problem-solving strategies | 1 |
| 2 | Integers | 13 |
| 3 | Algebra and equation | 27 |
| 4 | Geometry and reasoning | 41 |
| 5 | Divisors and prime numbers | 55 |
| 6 | Surface and volume | 69 |
| 7 | Powers and roots | 83 |
| 8 | Vectors and coordinates | 97 |
| 9 | Statistics and probability | 111 |

Each chapter ends with a مرور فصل (chapter review: key terms + main methods), printed at
ch. 1 pp. 10–12 (review of strategies), ch. 2 p. 26, ch. 3 p. 40, ch. 4 p. 54, ch. 5 p. 68,
ch. 6 p. 82, ch. 7 p. 96, ch. 8 p. 110, ch. 9 p. 124.

### 4. Everything taught, chapter by chapter

**Ch. 1 — Problem-solving strategies (pp. 1–12).** A four-step problem-solving frame is set
out first (pp. 1–2 of the chapter sequence, in the pre-chapter address and PDF pp. 18–19
equivalent sequence): (1) understand the problem, (2) choose a suitable strategy,
(3) solve, (4) look back — the fourth step appears in the strategy-review pages. Eight named
strategies are then taught one per spread, each with worked problems and a practice set:
drawing a figure (رسم شکل, p. 2), systematic listing / pattern-making (الگوسازی, p. 3),
eliminating unwanted cases (حذف حالت‌های نامطلوب, p. 4), pattern-spotting (الگویابی, p. 5),
guess and check (حدس و آزمایش, p. 6), sub-problems (زیرمسئله, p. 7), solving a simpler
problem (حل مسئلهٔ ساده‌تر, p. 8), symbolic methods / modelling (روش‌های نمادین, p. 9 —
turning a word problem into an equation such as 4x + 20000 = 200000, solved here only by
guessing). Pp. 10–12: mixed review set using all strategies (fractions-of-a-whole money and
tiling problems, a chessboard-grid movement problem, "in how many ways can a product of two
naturals be 36"). No new mathematics content; this chapter is method only. *Stated vs proved:*
nothing to prove; strategies are demonstrated, never justified formally.

**Ch. 2 — Integers (pp. 13–26).**
- *Introducing signed numbers* (معرفی عددهای علامت‌دار, p. 14): signed numbers for
  temperature, height/depth relative to sea level; signed angle measures on a circle with a
  chosen positive direction; opposite (قرینه) of a number and the − sign; +15 = 15 style
  identities; integers on the number line, ordering; movements on the line written as sums.
- *Addition and subtraction of integers (1)* (pp. 17–19): subtraction rewritten as addition
  of the opposite; black/white counter model (+1 / −1 discs) for sums; sign rules built from
  cases — sum of opposite signs takes the sign of the larger absolute value; applied problems
  (lift/elevator floors, weather).
- *Addition and subtraction of integers (2)* (pp. 20–22): column (tens/units) method for
  two-digit signed addition/subtraction; estimating the sign and approximate position of a
  result on the line first; calculator use, including the sign-change key; multi-term chains.
- *Multiplication and division of integers* (pp. 23–25): multiplication as repeated movement
  on the line; sign rules discovered from number patterns (4×(−3), 3×(−3), …); division as
  the inverse of multiplication, with the sign table for ÷; deciding the sign of a compound
  expression without computing. Exercises include true/false completion items on sign rules.
- Review p. 26 lists: signed number, integer, opposite, expanded form of an integer.
*Stated vs proved:* all rules are induced from patterns/activities; no formal proof is given
or claimed.

**Ch. 3 — Algebra and equation (pp. 27–40).**
- *Number patterns* (الگوهای عددی, p. 28): tables for perimeters/areas growing with a side a;
  matchstick and circle patterns; writing the n-th term (e.g. 2n + 1 circles); flow-diagram
  machines (+7, ×4) as proto-functions; circle circumference/area written with a variable,
  P in terms of r and S = 3.14 r².
- *Algebraic expressions* (عبارت‌های جبری, p. 31): a letter stands for a quantity; perimeter
  a + a + a + a = 4a; like terms can be combined, unlike terms (a with b) cannot; simplifying
  by collecting like terms, e.g. (3n + 1) + (2n + 1) = 5n + 2; multiplying a number through
  brackets, 3(2x + 5y) = 6x + 15y, and −(3x − 5y) = −3x + 5y — both worked in the text
  (recomputed by the reader: correct).
- *Numerical value of an algebraic expression* (p. 34): substituting values, with order of
  operations policed by a two-pupil worked example — 3(t + 27 ÷ s) at t = 6, s = 3 gives 45
  (brackets first), and 33 is shown as the wrong route (recomputed: the book is right).
- *Equation* (معادله, p. 37): an algebraic equality true for some values of the unknown;
  solution by trial substitution (6n + 7 = 37 → n = 5); the balance principles — adding the
  same number to both sides, multiplying both sides by the same number — discovered from
  4 = 4 and 8 = 8 activities and then used to solve, e.g. 2x − 1 = 7 → 2x = 8 → x = 4;
  modelling word problems as equations (municipal gardener planting pansies per m²).
*Stated vs proved:* the equality-preservation principles are asserted from numerical
experiments, not proved.

**Ch. 4 — Geometry and reasoning (pp. 41–54).**
- *Relations between segments* (روابط بین پاره‌خط‌ها, p. 42): naming points (capital Latin
  letters), lines, rays, segments; length notation; segment addition/subtraction on a line;
  triangle-inequality-type relations in figures (AB + AD > BD appears in classwork);
  equal segments marked with ticks; midpoint (وسط) and halving arguments — e.g. in an
  isosceles triangle with M, N midpoints of the equal sides, AN = AM is *derived* by a short
  ⇒ chain (AB = AC ⇒ ½AB = ½AC), the book's first explicit deductive steps.
- *Relations between angles* (p. 45): angle naming (xÔy and variants); adding/subtracting
  adjacent angles; equal angles marked; triangle angle sum 180° is *stated as known*
  ("we know that in every triangle the angles sum to 180°") and used to classify triangles
  by angles (acute / right / obtuse) and by sides, incl. why a triangle cannot have two
  right angles; vertical angles (زاویه‌های متقابل به رأس) equality is reached through
  "why can you conclude xÔy = tÔz?" reasoning exercises (named in the chapter review).
- *Geometric transformations* (تبدیل‌های هندسی, p. 48): translation, reflection in a line of
  symmetry, rotation (180°, 90° clockwise) — all done physically with tracing paper
  (کاغذ پوستی); centre of rotation.
- *Congruent figures* (شکل‌های مساوی / هم‌نهشت, p. 51): two figures are congruent if one can
  be made to coincide with the other by one or more transformations; corresponding parts
  (اجزای متناظر); tiling the plane by repeated transformations. Congruence is superposition
  only — no congruence criteria (SSS/SAS/…) and no proof.

**Ch. 5 — Divisors and prime numbers (pp. 55–68).**
- *Prime number* (عدد اول, p. 56): divisors (شمارنده) of a number listed in order; 1 is a
  divisor of every number; a number is its own largest divisor; numbers > 1 with exactly two
  divisors are prime (definition built from divisor tables for 9, 15, 4, 14, 5, 13; 29 prime
  used in true/false exercises). Divisibility language ("divisible by 15" checks on
  345, 924, 555, 360).
- *Prime divisor* (شمارندهٔ اول, p. 59): factor trees splitting a number down to prime
  factors (30, 45, 80, 210, 20, 200); writing a number as a product of prime factors
  (100 = 2×2×5×5, 36, 8); generating *all* divisors of a number from its prime factorisation
  (worked for 12 = 2×2×3 and 100); using prime factors to see why a fraction does/doesn't
  simplify.
- *Greatest common divisor* (بزرگ‌ترین شمارندهٔ مشترک, ب.م.م, p. 62): by listing divisors and
  by prime factorisation (worked sets: 12 & 14, 30 & 20, 36 & 48, 30 & 42; 28 = 2×2×7,
  36 = 2×2×3×3 …); applications — common tent sizes for classes of 30 and 36, square tiles
  filling a 16 × 12 frame, largest equal cubes filling a 12 × 36 × 28 box.
- *Least common multiple* (کوچک‌ترین مضرب مشترک, ک.م.م, p. 65): multiples of an integer
  (including negative multiples) vs natural multiples; LCM defined as the first common
  multiple, notation [a, b] (e.g. [6, 4] = 12 printed with the bracket order as extracted);
  finding [12, 18] by listing and from prime factorisations 18 = 2×3×3, 12 = 2×2×3;
  applications — buses every 20 and 30 minutes, runners lapping in 35 s and 21 s.
*Stated vs proved:* definitions are built from examples; no theorem is stated or proved
(e.g. no a·b = gcd·lcm relation).

**Ch. 6 — Surface and volume (pp. 69–82).**
- *Geometric volumes* (حجم‌های هندسی, p. 70): geometric vs non-geometric solids; the three
  families — prismatic (منشوری), spherical (کروی), pyramidal (هرمی) — and combinations;
  prisms: two parallel bases, lateral faces, edges (یال), vertices (رأس); counting faces/
  edges/vertices of triangular and quadrilateral prisms; views from above/front/side and
  cross-sections (مقطع) in exercises.
- *Volume of prisms* (محاسبهٔ حجم‌های منشوری, p. 73): cuboid V = a·b·c recalled, generalised
  to **V = S·h** (base area × height), worked for prisms and cylinders with given base areas.
- *Lateral and total surface area* (مساحت جانبی و کل, p. 76): lateral area as the sum of the
  lateral faces; unrolling/rolling a cylinder to get lateral area S = 2πrh in algebraic form
  (cylinder rolled on a page; circumference × height); total area adds the two bases; nets
  (گسترده) drawn and built.
- *Volume and surface* (حجم و سطح, p. 79): rolling one 60 × 40 rectangle two ways gives two
  cylinders of different volume (π taken as 3); solids of revolution introduced informally
  (rotating a rectangle about a side makes a cylinder — "in later years more will be said");
  percentage-of-soap-used and packing problems.

**Ch. 7 — Powers and roots (pp. 83–96).**
- *Definition of a power* (تعریف توان, p. 84): repeated multiplication from paper-folding
  (2, 2×2, …); a^n notation, base and exponent; squares (مجذور) and cubes (مکعب); a¹ = a,
  1^n = 1, 0^n = 0 (n ≠ 0); writing numbers in prime-power form (36 = 2²×3²).
- *Computing power expressions* (محاسبهٔ عبارت توان‌دار, p. 87): order of operations is
  restated with powers inserted — (1) brackets (پرانتز), (2) powers (توان), (3)
  multiplication and division, (4) addition and subtraction — and applied in fully
  stepped workings; classwork mixes powers with fractions and with each other
  (e.g. sums, differences, products and quotients of small powers, and spotting that
  (3 + 2)² ≠ 2² + 3² and (4 × 3)² ≠ 3² × 4² style claims need checking). Powers of
  negative bases (p. 88): (−2)² … (−2)⁶ are expanded and compared, and the sign pattern
  is read off — an even exponent gives a positive result, an odd exponent a negative
  one; −2³ (no brackets, the power binds to 2 only) is contrasted with (−2)³, and
  likewise −2⁴ with (−2)⁴. The descending pattern 2⁶, 2⁵, …, 2¹ is continued to 2⁰,
  motivating a⁰ = 1 for a ≠ 0; zero-exponent classwork includes (−9)⁰, (2/7)⁰ and
  mixed sums such as 4 + 2⁰. Exercises (p. 89): true/false items on zero powers
  (including fractional bases), writing 2472 and 5019 in expanded and then in power
  form (powers of 10: 2×10³ + 4×10² + 7×10¹ + 2×10⁰; recomputed by the reader:
  correct), comparing 4ⁿ with n⁴ for n = 1…5 and at n = 10, calculator power-key use,
  and evaluating algebraic power expressions at signed values. *Stated vs proved:*
  the sign pattern and a⁰ = 1 are induced from computed patterns; nothing is proved.
- *Simplifying power expressions* (ساده کردن عبارت‌های توان‌دار, p. 90): the product
  rule for equal bases is discovered from an area problem — a rectangle 2⁴ by 2³ has
  area 2×2×2×2 × 2×2×2 = 2⁷ — and generalised to aᵇ · aᶜ = aᵇ⁺ᶜ, practised on
  numbers, negative bases, fractions/decimals and letters (x²·x³, a³·a⁴), then run
  backwards to split one power into a product (2⁷ = 2⁵×2² and similar). Powers of
  powers appear only as a computation trick, e.g. 3⁴ = 3²×3² = 9², and 2¹² is found
  from the given 2¹⁰ = 1024. The product rule for equal exponents (p. 91) is
  discovered the same way — 2³×5³ expands to 10×10×10 — and generalised to
  aᶜ · bᶜ = (a·b)ᶜ, with (ab)³ = a³b³ and 6⁵ = (2×3)⁵ = 2⁵×3⁵ run in both directions;
  mixed classwork forces the pupil to choose which of the two rules applies.
  Exercises (p. 92): restating both rules with letters, prime-power forms of 121,
  256, 441 and 10000, ordering a mixed list of powers, true/false items (4³×4⁴ = 4⁷
  true; 4³×4⁴ = 4¹², 3²×2³ = 6⁵, 4³ + 2³ = 6³ false — deliberate items for pupils to
  judge), reading (2/3)² out of fraction pictures, a 4ⁿ digit-count pattern table
  (4⁶ = 4096, 4⁷ = 16384, 4⁸ = 65536; 4096 × 65536 written as a single power), and a
  differences-of-squares pattern (3² − 1², 6² − 3², …). No quotient rule
  (aᵐ ÷ aⁿ) and no power-of-a-power rule (aᵐ)ⁿ is stated anywhere in the chapter.
  *Stated vs proved:* both product rules are asserted from expanded examples,
  never proved.
- *Square root and root* (جذر و ریشه, p. 93): the inverse question — a square
  playground of area 144 m² has what side? — leads to: in 3² = 9, 9 is the square
  (مجذور) of 3 and 3 is a second root (ریشهٔ دوم) of 9; −3 is also a second root of
  9, while the square root (جذر) √9 is by definition the *positive* root only, 3.
  Side/area tables (including decimal and fractional sides) and the pattern
  1², 2², 3², … (does 15 occur? — the equation x² = 15 is attacked by guess-and-check
  with a calculator) prepare non-perfect squares. Notation (p. 94): the two roots of
  9 are written √9 and −√9; exact roots of perfect squares and of unit fractions are
  completed (√16, −√81, √(1/100), √(9/25), √49, √(1/81) …), and true/false items
  police the confusions √25 = 5 vs √25 = −5, √25 = 5², √25 = 25 and the like.
  Approximate roots (جذر تقریبی, pp. 94–95): a non-perfect square is first bracketed
  between consecutive perfect squares on a diagram of squares of area 4, 8 and 9
  (√5 lies between 2 and 3; √30 between 5 and 6), then refined to one decimal by
  squaring tenths — the worked table for √28 squares 5, 5.1, 5.2, 5.3, 5.4 to get
  25, 26.01, 27.04, 28.09, 29.16, so √28 ≈ 5.3 (recomputed by the reader and
  render-verified on PDF p. 105: correct). Exercises: why negative numbers have no
  (real) square root — √−25 is presented as meaningless and the pupil must explain
  why; placing √9, −√9, √(9/4), √4, −√4, √(1/4), −√1, √1 on a number line;
  completing the facts that 7 and −7 are the two roots of 49, that the square of 0 is
  0, that the square of a non-zero number is always positive, and that every positive
  number has two second roots, each the opposite (قرینه) of the other; estimating
  √40, √30, √500, √1000. Chapter review p. 96 lists: power, base, square, cube,
  root, square root, approximate square root — and the chapter's methods, including
  both multiplication rules and finding exact and approximate roots. *Stated vs
  proved:* √ defined as the positive root by convention; the "no root for
  negatives" point is argued from "a square is never negative", not proved formally;
  no root arithmetic (no √(ab), no simplifying surds) is taught.

**Ch. 8 — Vectors and coordinates (pp. 97–110).** *(Verified from the contents,
printed p. 97 opener and the pages themselves: the earlier summary was right.)*
Chapter opener (p. 97): position and navigation of aircraft and ships by coordinates
motivate the chapter.
- *Directed segment* (پاره‌خط جهت‌دار, p. 98): families of parallel lines are sorted
  into the same direction (راستا, the line/direction a segment lies along); on one
  راستا two segments are either in the same sense or in opposite senses. A force
  drawn at 1 cm scale shows the three attributes — magnitude (اندازه), direction-line
  (راستا) and sense (جهت). Definition: a directed segment is called a vector
  (بردار); notation OA⃗ for the vector from initial point (ابتدا) O to terminal point
  (انتها) A. Classwork draws vectors for a weight force, a rope-pull force,
  tug-of-war forces and an aircraft's direction of motion; a two-pullers activity
  (p. 99) compares two forces' راستا, sense and size, and names two vectors on the
  same راستا with equal size but opposite sense as opposites (قرینه) of each other —
  the word is introduced here, a lesson before its heading. Exercises (p. 100):
  forces on a many-roped box from above, a compass walk (3 east, 2 north, 4 west,
  4 south from A to B), home-to-school displacements, and reading initial point,
  terminal point and magnitude of vectors drawn on an integer axis.
- *Equal and opposite vectors* (بردارهای مساوی و قرینه, p. 101): pushing vs pulling
  the same object with equal forces shows equal size is not enough — two vectors
  are equal (مساوی) exactly when they have the same راستا, the same magnitude and
  the same sense; pupils draw several vectors equal to a given AB⃗, mark vectors of
  given size/sense on an axis, and pick the equal vectors out of a lettered figure.
  Opposites (pp. 102–103): the return journey B → A is compared with A → B (same
  راستا and magnitude, opposite sense — the two are قرینه, and the total
  displacement of going and returning is zero); force diagrams decide which way a
  body moves when some forces cancel as opposites; opposite vectors are named in a
  regular hexagon and a parallelogram. Exercises: the support force cancelling a
  weight (why the body stays at rest), compass walks and their return vectors, and
  the opposites of the compass directions (north ↔ south, east ↔ west, north-east ↔
  south-west).
- *Coordinates* (مختصات, p. 104): the primary-school coordinate axes are recalled —
  a point is written as a column [x; y], longitude (طول) over latitude (عرض), on the
  axis of longitudes (محور طول‌ها, x) and axis of latitudes (محور عرض‌ها, y) — then
  both axes are extended in the negative directions using the integer axis, and
  points with negative, fractional and decimal coordinates are read off and plotted
  (e.g. A = [−2; 3], E = [3; −3], G = [2.5; 3.5]). The axes divide the plane into
  4 regions (ناحیه). Classwork reads the coordinates of buildings (stadium, mosque,
  library, park) off a town map. A vector also gets coordinates (p. 105): moving
  from A to B as "first horizontal, then vertical" — 4 units in the positive x
  sense then 2 in the positive y sense — is written AB⃗ = [4; 2]; classwork uses a
  longitude/latitude world map (approximate coordinates of Cairo, Algiers,
  Dar es Salaam; the Khartoum → Luanda and Rabat → Lagos flights as vectors).
  Exercises (p. 106): approximate point coordinates on a ±10 grid, drawing a vector
  with given coordinates from a given initial point and finding its terminal point,
  reading point- and vector-coordinates from one figure, the reflection (قرینه) of
  a vector in the x-axis, in the y-axis and in the origin, chained vectors
  (from A = [−1; −4] by AB⃗ = [2; 2] then BC⃗ = [−1; 4] — what single vector goes
  from A to C?), and placing large-coordinate points ([47; −81], [−250; −180], …)
  in their regions.
- *Translation vector* (بردار انتقال, p. 107): a figure is translated by moving
  every point by a vector parallel, equal and in the same sense; translating
  triangle ABC by a vector a⃗ gives A′B′C′ and the vertex coordinates before/after
  are tabulated; the corresponding addition (جمع متناظر) is made explicit —
  initial point + vector = terminal point, component by component — so any one of
  the three can be found from the other two, and two vectors are equal exactly
  when their first components are equal and their second components are equal.
  Classwork (p. 108) translates shapes by given vectors, recovers the translation
  vector from a red endpoint dot, and solves component equations for unknowns
  (e.g. [−2; 1] + [x; y] = [3; −4]); a two-step activity translates by a⃗ then by b⃗
  and asks for the single vector doing both. Exercises (p. 109): a path
  A → B → C → D → E as translation vectors, picking out equal vectors among
  lettered arrows, opposites in coordinates — if d⃗ is given, d⃗′ is its opposite,
  and d⃗ + d⃗′ = [0; 0] (the zero vector, بردار صفر, appears here in coordinates and
  is named in the chapter review) — a marked-corner coordinate in a growing tiling
  pattern written algebraically for tile n, a board-game walk from [−2; 3] (3 right,
  4 down, then 2 left), and the general rule: A = [a; b] translated by [x; y] lands
  at B = [a + x; b + y]. Chapter review p. 110 lists: vector, direction-line,
  directed segment, translation vector, opposite vector and zero vector, coordinates
  of a point, the 4 regions, equal vectors, finding a vector's coordinates, the
  corresponding addition. *Stated vs proved:* everything is definitional and
  pictorial; vector "addition" exists only as the corresponding addition of a
  point and a vector and as chaining two translations in exercises — no general
  vector-addition rule, no scalar multiples, no components beyond two dimensions.

**Ch. 9 — Statistics and probability (pp. 111–124).** *(Verified from the contents,
printed p. 111 opener and the pages themselves: the earlier summary was right.)*
Chapter opener (p. 111): statistics and probability as tools for decisions and
prediction (a weather forecaster as the example).
- *Collecting and displaying data* (جمع‌آوری و نمایش داده‌ها, p. 112): a PE teacher
  needs the class's preferred kit colour. Two collections of the same class are
  compared — Javad asks everyone freely (7 colours appear: green, blue, yellow,
  purple, red, brown, …) while Mohammad offers only 3 colours to choose from — and
  pupils discuss the strengths/weaknesses of each method and why the two tallies
  differ. Definition: statistics (آمار) is the science of collecting, organising and
  examining information; the collected information is statistical data (داده‌های
  آماری). Raw lists are organised into a data table with tally marks (چوب‌خط) and
  counts. Chart choice (p. 113): different charts suit different data; the bar chart
  (نمودار میله‌ای) is for comparing counts and finding the largest/smallest — and
  the same table drawn by Javad and Mohammad at different scales is compared
  (which scale shows the data more precisely? which is easier to compare?). Software
  is mentioned as the drawing tool; choosing the right chart is the skill.
  Exercises (p. 114): find a published chart in another textbook or a newspaper and
  explain it; a full year of Rasht monthly rainfall (71, 62, 50, 55, 65, 141, 189,
  180, 171, 150, 121, 128 mm — recomputed total 1383 mm, mean 115.25 mm) is tabled
  and drawn as a column chart with a chosen scale, then interrogated (wettest/driest
  month, wettest season, months over 140 mm, the monthly mean (میانگین) — the mean
  is used here as a known primary-school tool, not re-taught); and designing a
  survey of "the most important Grade 7 maths topics".
- *Charts and interpreting results* (نمودارها و تفسیر نتیجه‌ها, p. 115): monthly mean
  temperatures for Yazd (21, 25, 30, 31, 34, 27, 24, 15, 10, 8, 10, 12 °C —
  recomputed sum 247, mean ≈ 20.6 °C) are plotted as points and joined into a
  broken-line chart (نمودار خط شکسته), whose job is to show *change* (hottest/coldest
  month, largest month-to-month change, the 12-month mean); financial series (gold,
  oil, shares) are named as its home ground. Approximate values: for large-scale
  planning, data are rounded (provincial populations rounded to less than
  1,000,000) and drawn as a pictograph (نمودار تصویری, p. 116) — one symbol stands
  for 2,000,000 people. Pie chart (نمودار دایره‌ای, p. 116): when a whole splits
  into parts, each part's share is computed as a percentage and shown on a circle,
  usually via approximate fractions with denominator 10 — worked on a school
  library's loans (religious 390, story 210, science 810, study-help 400, other
  190; total 2000 — recomputed: study-help is exactly 20%, "other" 9.5% ≈ 10%,
  matching the book's printed approximate percentages). Exercises (p. 117): a
  tally table of shoe sizes in a building (sizes 36–43) and a "smaller than 40"
  count; converting a bar chart of pupil numbers into a pictograph at 1 symbol =
  10 pupils; reading temperatures off a broken-line chart and describing the
  changes; and four different charts of the same charity-collection data — which
  chart best shows which class gave the largest share, and why.
- *Probability, or measuring chance* (احتمال یا اندازه‌گیری شانس, p. 118): events
  are sorted into certain (حتمی), impossible (غیرممکن) and possible-but-not-certain
  (ممکن است اما حتمی نیست) — after Farvardin comes Khordad (impossible), a die
  shows more than 7 (impossible), a die shows less than 7 (certain), a die shows an
  even number (possible); drawing a marble without looking is named random
  (تصادفی) choice. Equally likely outcomes (حالت‌های هم‌شانس) are listed for a
  coin, a die, a 3-marble bag and a spinner. Probability defined (p. 119): for a
  fair coin P(heads) = 1/2 because 1 of the 2 equally likely outcomes is wanted;
  in general, probability of an event = (number of desired outcomes) ÷ (number of
  possible outcomes), computed for a die (even, divisible by 3) and for spinner
  colours; and why a probability is always 0, 1 or a number between 0 and 1, and
  what probability 0 and probability 1 mean. Exercises (p. 120): give examples of
  probability 0, 1/2 and 1 events; place event probabilities on a 0–1 segment;
  spinner-red probability; one black marble hidden among 10, 100 or 1000 white
  ones — from which bag is black most likely, and why; comparing probabilities
  with <, = , >; and two shooting targets — which gives the better chance of
  hitting red, argued from area share.
- *Probability and experiment* (احتمال و تجربه, p. 121): prediction vs outcome —
  Mohsen's coin comes up heads three times running; does that change the next
  throw? Pupils toss a coin 10 times, tally heads/tails, write the relative
  frequency (تعداد رو آمدن ÷ تعداد کل آزمایش‌ها, as a fraction), and compare
  across the class — the fractions differ. A bag experiment (1 red, 2 blue
  marbles, draw–record–replace, 10 trials) and 30 die throws (does each face come
  up exactly 5 times? — no) do the same work. Pooling (p. 122): the whole class's
  coin results are combined (e.g. 30 pupils → 300 trials) and the pooled fractions
  computed; the book's gloss on P = 1/2 is that in *many* trials we *expect about*
  half to be heads — not exactly half in 20 throws (≈ 500 in 1000 throws; 400 tails
  in 500 throws is possible but not expected). Exercises (p. 123): a recorded
  20-throw die table — each face's experimental fraction, and the fractions sum
  to 1; expected counts in 1000 die throws (a given face ≈ 1000/6, an even face
  ≈ 500); colouring a spinner so that P(white) = 0; an unequal-sector numbered
  spinner (sectors weighted 1, 4, 3, 4, 6, 4, 5, 1, 2, 7 out of a full turn —
  recomputed total 37 parts in the extraction's reading; probabilities are taken
  as sector share, e.g. P(3) by its share) with expected counts in 1000 spins.
  Chapter review p. 124 lists: statistics, data collection, sampling (نمونه‌گیری —
  named in the review; no sampling method is taught in the lessons), equally
  likely events, probability — and the methods: organising data in a table,
  column/bar, broken-line and pictograph charts, choosing the right chart,
  classifying events as certain/possible/impossible, computing a probability, and
  comparing a probability with experimental results. Combined exercise: 10 die
  throws — compare the experimental fraction for "even" with the theoretical
  probability; are they always equal? can they be equal? do they approach each
  other as trials grow? *Stated vs proved:* the probability formula is stated as a
  definition for equally likely outcomes and used, not derived; the
  frequency-approaches-probability claim is supported only by the class's pooled
  experiments and is phrased throughout as expectation ("انتظار داریم"), never as
  a theorem.

### 5. Honest negatives (Grade 7)

- No formal proof anywhere in the book: every rule (integer signs, power rules,
  √ as the positive root, the probability formula) is induced from patterns,
  activities or stated as a definition; the short ⇒ chains of Ch. 4 are the only
  deductive steps, and congruence stays superposition-only — no congruence
  criteria (SSS/SAS/ASA) and no similarity.
- Powers: no negative exponents, no zero-exponent derivation beyond the descending
  pattern to 2⁰, no quotient rule for powers, no power-of-a-power rule, no
  fractional exponents, no scientific notation (verified by full read of Ch. 7 and
  text search: توان منفی and نماد علمی occur 0 times in the whole book).
- Roots: square roots only — no cube roots (ریشهٔ سوم, 0 occurrences), no root
  arithmetic, no simplifying surds, no rationalising; roots of negative numbers
  are declared meaningless rather than developed.
- Algebra: equations are solved only by trial substitution and the two balance
  principles; no inequalities, no systems of equations, no functions named as
  such (تابع, 0 occurrences), no graphs of relations.
- Vectors/coordinates: no general vector addition or subtraction as an operation
  on two vectors (only the point + vector "corresponding addition" and chaining
  translations), no scalar multiplication, no magnitude formula (no Pythagoras
  this year), no slope (شیب, 0 occurrences).
- Statistics: the mean (میانگین) is used but not defined or taught as a method;
  no median (میانه, 0 occurrences), no mode, no range or any other spread
  measure, no sampling design or bias discussion (نمونه‌گیری is named only in the
  Ch. 9 review list), no misleading-graph critique beyond comparing two bar-chart
  scales. Probability: equally likely outcomes only — no probability rules for
  combined events (no addition/multiplication rules), no permutations or
  counting principles, no expected value.

### 6. Confirmed book errors (Grade 7)

**0 confirmed errors.** Everything recomputed in the completed span checked out,
including — render-verified on PDF p. 105 (printed p. 95) — the √28 estimation
table (5² = 25, 5.1² = 26.01, 5.2² = 27.04, 5.3² = 28.09, 5.4² = 29.16; √28 ≈ 5.3).
Also recomputed and correct: the expanded/power forms 2472 = 2×10³ + 4×10² +
7×10¹ + 2×10⁰ and 5019 (p. 89); (−2)ⁿ sign pattern and 2¹⁰ = 1024 → 2¹² = 4096
(pp. 88, 90); the 4ⁿ table values 4⁶ = 4096, 4⁷ = 16384, 4⁸ = 65536 (p. 92); the
Ch. 9 Yazd temperature set (sum 247, mean ≈ 20.6 °C, p. 115), the Rasht rainfall
set (total 1383 mm, mean 115.25 mm, p. 114) and the library-loan pie-chart shares
(total 2000; study-help exactly 20%, p. 116). The false equalities printed in
Ch. 7 (e.g. 4³×4⁴ = 4¹², 3²×2³ = 6⁵ on p. 92; √25 = −5 on p. 94) are deliberate
true/false exercise items for pupils to judge, not book errors; remaining oddities
in this span are text-layer RTL/digit artefacts only.

### 7. Answer keys (Grade 7)

None — no answer key, solutions section or پاسخنامه anywhere in the book
(0 hits on text search across the whole book; confirmed by the full read of the
completed span and consistent with the whole-band note in band-b.md).

### 8. Held-copy defects (Grade 7)

None found in the completed span. PDF pp. 93–134 all carry their printed content
in order (printed pp. 83–124, continuous, matching the contents table). The two
non-content pages are design, not defects: PDF p. 10 is a blank coloured divider
(render-checked, already noted in band-b.md), and PDF p. 135 (render-checked by
this reader) is the publisher's back-matter feedback page inviting correction
suggestions (سامانهٔ نظرسنجی / nazar.roshd.ir) — not a missing content page.
---

## Book 2 — Grade 8 Mathematics (g08.pdf)

### 1. Identity block

- Persian title as printed (imprint): ریاضی ـ پایهٔ هشتم دورهٔ اول متوسطه
  ("Mathematics — Grade 8, First Period of Secondary School").
  Cover (render-checked, PDF p. 1): ریاضی / پایهٔ هشتم / دورهٔ اول متوسطه.
- Grade: 8.
- Publisher / پدیدآورنده: سازمان پژوهش و برنامه‌ریزی آموزشی (OERP), Ministry of Education;
  printed by شرکت چاپ و نشر کتاب‌های درسی ایران.
- Printing as printed on imprint (PDF p. 2): چاپ سیزدهم ۱۴۰۵ — **13th printing, 1405**
  (school year 1405–1406).
- ISBN as printed: **978-964-05-2379-7**.
- Book code as printed: **805**.
- PDF pages: **160**. Printed pages 1–152 plus front matter (address to the teacher,
  PDF pp. 7–8, precedes printed p. 1).
- Offset: **printed page = PDF page − 8** (Chapter 1 opener, printed p. 1, is PDF p. 9;
  the last printed page, 152 — a glossary of Academy-approved equivalents for foreign
  terms — is PDF p. 160).

### 2. Kind proof

Cover + imprint name the pupil book «ریاضی ـ پایهٔ هشتم»; the body is pupil-facing
activity/classwork/exercise apparatus throughout (a سخنی با معلم "word to the teacher"
preface is front matter only, not a teacher guide): a pupil's textbook.

### 3. Contents (printed pages; this book numbers its lessons درس)

| Ch. | Title | Lessons (printed pp.) |
|---|---|---|
| 1 | Integers and rational numbers (p. 1) | Review of integers 2 · Introducing rational numbers 6 · Addition/subtraction of rationals 10 · Multiplication/division of rationals 14 · Review 18 |
| 2 | Prime numbers (p. 19) | Review of prime numbers 20 · Determining prime numbers 24 · Review 28 |
| 3 | Polygons (p. 29) | Polygons and symmetry 30 · Parallelism and perpendicularity 34 · Quadrilaterals 38 · Interior angles 42 · Exterior angles 46 · Review 50 |
| 4 | Algebra and equation (p. 51) | Simplifying algebraic expressions 52 · Finding the value of an expression 56 · Factorising algebraic expressions 60 · Equation 64 · Review 68 |
| 5 | Vectors and coordinates (p. 69) | Adding vectors 70 · Multiplying a number by a vector 74 · Unit coordinate vectors 78 · Review 82 |
| 6 | The triangle (p. 83) | Pythagoras' relation 84 · Congruent figures 88 · Congruent triangles 92 · Congruence of right triangles 96 · Review 100 |
| 7 | Powers and roots (p. 101) | Powers 102 · Dividing powers 106 · Approximate square root 110 · Showing radical numbers on the number line 114 · Properties of multiplication/division of radicals 115 · Review 118 |
| 8 | Statistics and probability (p. 119) | Grouping data 120 · Mean of data 124 · Probability or measuring chance 128 · Examining the possible cases 132 · Review 136 |
| 9 | The circle (p. 137) | Line and circle 138 · Central angles 142 · Inscribed angles 146 · Review 150 |

### 4. Everything taught, chapter by chapter

**Ch. 1 — Integers and rational numbers (pp. 1–18).**
- *Review of integers* (p. 2): G7 integer arithmetic consolidated; several pupils' different
  correct routes to −43 + 37 − 29 = −35 compared (recomputed: all four printed routes give
  −35, correct); Gauss pairing story for 1 + 2 + … + 100 (pairs of 101; answer 5050 implied
  by the activity, not printed); classifying numbers as natural/integer in tables.
- *Introducing rational numbers* (p. 6): points between integers on the line; equal fractions
  (−1/2 = −2/4 = −3/6 shown on the line); simplifying fractions (108/126, −66/42, −90/6 in
  classwork); a rational number defined as any number writable as a fraction a/b with a an
  integer and b a non-zero integer (definition sentence completes on p. 9); a ÷ b written as
  the fraction a/b, incl. −2/3 = −2 ÷ 3 = −(2 ÷ 3); every integer is rational.
- *Addition and subtraction of rationals* (p. 10): built on line movements, then reduced to
  integer arithmetic over a common denominator; mixed numbers split into integer + fraction
  parts; estimating by rounding to the nearest integer first (worked: −17.9 − (−8.001) +
  12.87 ≈ −18 + 8 + 13 = 3).
- *Multiplication and division of rationals* (p. 14): sign table carried over from integers;
  reciprocal (معکوس) of a rational, x × (1/x) = 1 observed; division converted to
  multiplication by the reciprocal; 1 ÷ a = reciprocal of a; fractions converted to decimals
  with a calculator (terminating/recurring distinction is exercised, not theorised).

**Ch. 2 — Prime numbers (pp. 19–28).**
- *Review of primes* (p. 20): prime vs composite (مرکب) — a natural number writable as a
  product of two naturals > 1 is composite (24 = 6 × 4); **1 is neither prime nor composite**
  (asked and answered through activities); naturals split into three classes; gcd drill set
  incl. coprime pairs (نسبت به هم اول appears as a chapter term: (15, 4) = 1, (3, 5) = 1,
  (24, 25) = 1, (7, 8) = 1 among the worked pairs); primes between 40 and 60; "sum of two
  primes is 99 — find them" (forces 2 + 97).
- *Determining primes* (p. 24): the **sieve of Eratosthenes** (روش غربال) for 1–50 and 1–100,
  with the stopping rule stated: keep crossing out multiples of primes only while the
  prime's square is still among the listed numbers (√n rule in words); primality testing by
  trial division applied to 47, 107, 251; claim-checking ("to test numbers < 100 it suffices
  to divide by 2, 3, 5, 7 — true? why?"). No proof of the sieve rule; it is justified by the
  activity pattern.

**Ch. 3 — Polygons (pp. 29–50).**
- *Polygons and symmetry* (p. 30): polygon defined as a closed broken line whose sides meet
  only at vertices; regular polygon (all sides and all angles equal); convex (محدب) vs
  concave (مقعر) — review terms; axes of symmetry of regular polygons (pupils find 3 for
  the triangle, 4 for the square, and are asked to generalise to the regular nonagon/decagon);
  **centre of symmetry** defined: a point about which a 180° rotation maps the figure onto
  itself; equilateral triangle has none, even-sided regular polygons do (explored).
- *Parallelism and perpendicularity* (p. 34): a transversal (خط مورب) cutting two lines with
  equal angles ⇒ the lines are parallel; conversely a transversal to two parallels makes
  equal angles (both directions *stated* from the figure work, not proved); notation a ∥ b
  and l₁ ⊥ l₂; fill-in theorems: two lines perpendicular to the same line are parallel; two
  lines parallel to the same line are parallel; a line perpendicular to one of two parallels
  is perpendicular to the other; supplementary (مکمل) angle chasing with reasons.
- *Quadrilaterals* (p. 38): parallelogram defined (both pairs of opposite sides parallel);
  its centre of symmetry is the diagonal intersection — rotating the tracing 180° about it
  is used to read off opposite sides/angles equal and diagonals bisecting each other
  (properties experienced, stated through the rotation, not proved in Euclidean style);
  rhombus, rectangle, square, trapezium (ذوزنقه) defined and classified in a
  property table (equal sides / right angles / parallelogram family); the midpoint
  quadrilateral of a square discussed by two pupils' folding arguments.
- *Interior angles* (p. 42): triangulation table (3, 4, 5, 6 sides → 1, 2, 3, 4 triangles)
  giving the interior-angle sum **(n − 2) × 180°**; quadrilateral sum 360°; angle of a regular
  heptagon/dodecagon/icosagon computed; which regular polygons tile alone.
- *Exterior angles* (p. 46): exterior angle at a vertex of a convex polygon defined; the two
  exterior angles at one vertex of a triangle are equal (vertical angles); **triangle
  exterior angle = sum of the two non-adjacent interior angles** — discovered in a worked
  example (Â₁ = 180° − (30° + 80°) = 70°, exterior 110°; recomputed: correct); table proof
  that the exterior-angle sum of any (convex) polygon is **360°** (interior + exterior =
  n × 180°, subtract (n − 2) × 180°).

**Ch. 4 — Algebra and equation (pp. 51–68).**
- *Simplifying expressions* (p. 52): G7 power rules restated symbolically (a⁰ = 1, a ≠ 0);
  multiplying out: 5(a + b) = 5a + 5b from area; product of two brackets via the area model,
  (a + b)(c + d) = ac + ad + bc + bd; products like (x + y)(x − y), (x − 1)(x + 1),
  (3x − 2)(2x − 3) computed; like terms now include xy-terms (3xy, 7yx, 2yx identified as
  like); n-th terms for square and cube number patterns (n², n³).
- *Value of an expression* (p. 56): number machines and chained machines; input–output
  tables for y = 3x + 1, y = 5x, y = x − 7, y = 2x − 3 (a function table in all but name);
  even numbers written 2n, and algebraic "why" questions: is 4c even? is 2ab even? why?
- *Factorising expressions* (تجزیه, p. 60): factorising = reversing distribution; common-
  factor extraction only: ab + ac = a(b + c), 4x²y + 6xy², 8x²y³ − 4xy², 42xy³ − 35x²y²;
  simplifying algebraic fractions by factorising numerator and denominator
  ((a² − a)/(ab − b) type, with exclusion conditions a ≠ 1, b ≠ 0 printed); (a + b)² expanded
  step by step to **a² + 2ab + b²** (p. 62), (x − y)² likewise; pupils compare (a + b)² with
  a² + b² in a table and conclude they differ; (x − 1)(x² + x + 1) expansion asked;
  parity reasoning as exercises: why is the sum of two odd numbers even? (p. 63).
  Difference of squares and perfect-square *identities are computed but never named or
  stated as identities*; factorising is common-factor only — no trinomial factorising.
- *Equation* (p. 64): one problem (sum of five consecutive naturals = 65) solved by five
  strategies; formal solving: transposition (5x + 10 = 65 → 5x = 55 → x = 11), equations with
  x on both sides (2x − 3 = x + 5 → x = 8), brackets (2(x − 1) = 3(x + 4)); **fractional
  equations** cleared by multiplying through by the LCM — printed p. 66 (render-verified):
  (1/2)x − 1/3 = 5/6 solved two ways, both correctly giving **x = 7/3** (one route via
  (1/2)x = 7/6; the other via ×6 → 3x − 2 = 5 → 3x = 7); pupils must spot the deliberate
  sign error in one of two printed attempts at 6 × (−(x + 3)/2) (−3x − 9 correct, −3x + 9
  the planted mistake — a find-the-error exercise, not a book error).

**Ch. 5 — Vectors and coordinates (pp. 69–82).**
- *Adding vectors* (p. 70): resultant (برآیند) by the head-to-tail rule; coordinate sums;
  decomposing (تجزیه) a vector into two components — infinitely many answers, noted as a
  discussion point; the parallelogram-style resultant of two vectors from one point is in
  the review list.
- *Multiplying a number by a vector* (p. 74): k[x; y] = [kx; ky] stated in symbols; opposite
  vector as (−1)a; linear combinations a ± 2b, c = 3a + 3b, c = 4a − 2b, d = −a + 5b drawn and
  computed; decomposing the weight vector on an inclined plane (exercise).
- *Unit coordinate vectors* (p. 78): unit vectors i and j; [2; 3] = 2i + 3j and back;
  combinations in i–j form (a = 3i − 2j, b = 2i + j → x = 5a + 3b, y = −3a + 4b computed);
  solving a vector equation 2x − j = 2a − b for x (exercise, p. 81). No magnitude formula,
  no dot product.

**Ch. 6 — The triangle (pp. 83–100).**
- *Pythagoras' relation* (p. 84): discovered from squares on the sides of grid triangles
  (9, 16, 25 table) and paper-cutting dissections; **stated** as: in a right triangle the
  square on the hypotenuse equals the sum of the squares on the other two sides — presented
  as the famous relation, *verified on examples, not proved*; worked: 13² = x² + 5² →
  x² = 144 → x = 12 (recomputed: correct); checking candidate triples (1, 1, √2; 5, 12, 13;
  7.2, …) and the converse direction — deciding a triangle is right-angled from its three
  sides (review method); constructing segments of length √2, √3, √5, √6 geometrically vs
  arithmetically (three pupils' methods compared); cone height from a 10 cm-radius sector
  with 12 cm base diameter.
- *Congruent figures* (p. 88): congruence via superposition by transformations, as G7;
  corresponding sides/angles read off from ∆ABC ≅ ∆A′B′C′.
- *Congruent triangles* (p. 92): necessity explored by construction — three angles alone do
  NOT fix a triangle (pupils build a non-congruent triangle with the same three angles);
  equal sides alone fail for quadrilaterals but force triangles; the **three congruence
  cases are stated** (p. 95): SSS (ض ض ض), SAS (ض ز ض — two sides and the included angle),
  ASA (ز ض ز — two angles and the included side); first deductive proofs: the bisector of
  the apex angle of an isosceles triangle, and "if two angles of a triangle are equal the
  triangle is isosceles" proved via ABD ≅ ACD with a hint to first justify D̂₁ = D̂₂.
- *Congruence of right triangles* (p. 96): two further cases built the same way —
  hypotenuse + one leg, hypotenuse + one acute angle (in each case pupils first compute the
  third side/other angle, reducing to an earlier case); **perpendicular-bisector theorem**
  (p. 98): every point on the perpendicular bisector of a segment is equidistant from its
  endpoints — met as a quoted sentence from a geometry book and investigated ("why is this
  sentence true?"), the intended route being congruent triangles.

**Ch. 7 — Powers and roots (pp. 101–118).**
- *Powers* (p. 102): G7 product rules restated for natural exponents; **power of a power**
  (a^m)^n = a^(mn) built from (2³)⁴ = 2¹² and stated generally; true/false traps incl.
  (3²)⁴ = 3² × 3⁴ (false), (−4⁶) = 4⁶ (false), a² · a⁰ = 1 (false); 2⁷ + 2⁷ and 3⁵ + 3⁵ + 3⁵
  written as single powers.
- *Dividing powers* (p. 106): same-base quotient a^m ÷ a^n = a^(m−n) from 10⁷ ÷ 10² (sun's
  core vs boiling water); equal-exponent quotient a^m ÷ b^m = (a ÷ b)^m from 8⁵ ÷ 2⁵ = 4⁵;
  both rules stated symbolically (b ≠ 0).
- *Approximate square root* (p. 110): bracketing and refining with calculator tables —
  √34 ≈ 5.8 from 5.7² = 32.49, 5.8² = 33.64, 5.9² = 34.81 (recomputed: all correct),
  √34 ≈ 5.83095 quoted to five decimals; bisection on the line for √200 (14.5² = 210.25,
  14.1² = 198.81, 14.2² = 201.64; recomputed: correct); nearest-integer estimates.
- *Radicals on the number line* (p. 114): √2 located exactly by the compass arc from the
  hypotenuse of the unit right-isosceles triangle; negative radicals −√3, −√8, −√17 placed
  approximately.
- *Properties of multiplication and division of radicals* (pp. 115–117): from tables,
  **√(ab) = √a · √b** and **√(a/b) = √a / √b** for positive a, b, stated as rules; the false
  companion √(a + b) = √a + √b is put to pupils to test and reject. Simplifying a radical
  beyond extracting obvious perfect-square factors is not developed (no √12 = 2√3 routine).

**Ch. 8 — Statistics and probability (pp. 119–136).**
- *Grouping data* (p. 120): raw data set of 40 men's heights (n = 40 printed; the reader
  counted exactly 40 values); **range** (دامنه تغییرات) defined as max − min; grouping into
  classes, frequency tables and bar charts of grouped data; lamp-lifetime exercise (30
  lamps into 5 classes).
- *Mean of data* (p. 124): mean recalled and defined, x̄ = (sum of data) / (number of data);
  **class mark** (مرکز دسته) = midpoint of the class limits; approximate mean from grouped
  data as Σ(mark × frequency) / Σfrequency over classes 130 ≤ x < 145, …, 190 ≤ x ≤ 205;
  an outlier discussion: a class of 30 with mean 17.25 where one pupil scored 3.5 — predict
  and then verify the effect of removing that score (the book prints no answer).
- *Probability* (p. 128): event (پیشامد); probability = favourable cases / all equally
  likely cases, formalised from the 10-card (numbers 11–20) activity; spinner problems where
  the probabilities of complementary events are found to sum to 1; expected counts ("we
  expect the pointer to stop on blue about 100 times in 300 spins" marked true, "exactly
  100" / "certainly equal counts" marked false).
- *Examining the possible cases* (p. 132): sample-space enumeration by **tree diagram**
  (نمودار درختی) and two-way tables: two coins (is the two-girls-and-boy scoring game fair?
  — the mixed outcome has probability 1/2), two spinners, three coins (8 outcomes;
  P(3 heads) and P(exactly two heads) asked), spinner + die tables, one-digit and two-digit
  lock-code probabilities (1/10 → 1/100). Multiplication of probabilities is *used through
  counting only* — no product rule is stated.

**Ch. 9 — The circle (pp. 137–152).**
- *Line and circle* (p. 138): circle as the locus of points at a fixed distance from O;
  three positions of a line and a circle (0, 1, 2 common points); tangent (مماس) defined by
  the single common point; **the radius to the point of contact is perpendicular to the
  tangent** — stated (p. 139) and used with Pythagoras (tangent problems with 47°, 63°, 23°
  angle chasing; a point 13 cm from the centre of a radius-5 circle, tangents drawn from
  it); the perpendicular from the centre to a chord bisects the chord (activity built on
  two compared texts, p. 140); finding a broken plate's diameter by recovering the centre.
- *Central angles* (p. 142): arc notation; the measure of an arc equals its central angle;
  equal arcs ⇔ equal chords, justified by congruent triangles (∆AOB ≅ ∆COD activity,
  p. 144); dividing a circle into 8 equal arcs to construct a regular octagon and arguing
  its regularity; arc-as-fraction-of-the-circle tables (radius 1 cm).
- *Inscribed angles* (p. 146): inscribed angle (زاویه محاطی) defined (vertex on the circle,
  sides cutting it); across the position cases pupils complete the statement: **an inscribed
  angle equals half (the measure of its intercepted arc / the corresponding central
  angle)**; corollaries in use: angles on the same arc, the angle in a semicircle context
  (diameter AB problems, pp. 143/148 — a rhombus inscribed with all vertices on the circle
  "why is it a square?"); opposite angles of a cyclic quadrilateral sum to 180° — set as a
  "why" exercise (p. 149), not stated as a theorem first.
*Stated vs proved in Ch. 9:* the tangent–radius perpendicularity is stated without proof;
arc/chord equality and the inscribed-angle relation are built from congruent-triangle and
case activities rather than a single formal proof.

### 5. Honest negatives (Grade 8)

- No negative exponents and no zero-exponent *derivation* (a⁰ = 1 is restated as a rule);
  no scientific notation (10¹³ appears in a chapter opener's prose only).
- No square-root *simplification* routine (no √12 = 2√3), no rationalising denominators,
  no cube roots; radical arithmetic stops at √(ab) and √(a/b) for perfect-square-friendly
  numbers.
- Factorising stops at common factors; no difference-of-squares or trinomial factorisation
  even though (a + b)² and (a + b)(a − b) are expanded.
- No simultaneous equations, no inequalities, no functions named as such (input–output
  machines and y = … tables are the closest approach), no graphs of linear relations,
  no slope.
- No volume/surface-area chapter this year (the G7 prism work is only reused inside
  algebra exercises); no spheres/cones formulas (a cone appears once, solved by Pythagoras).
- Statistics: no median, mode, quartiles or any spread measure beyond the range; no
  sampling methods or bias discussion. Probability: no product/sum rules stated as rules.
- Geometry: no formal axiom system; Pythagoras and the tangent–radius fact are stated/
  verified, not proved; no circle area/circumference derivation (primary-school formulas
  are assumed), no chord-length or arc-length formulas (arc *degree measure* only).

### 6. Confirmed book errors (Grade 8)

**0 confirmed errors.** All worked material the reader recomputed checked out, including —
render-verified on PDF p. 74 (printed p. 66) — the two printed solutions of
(1/2)x − 1/3 = 5/6, both correctly ending at x = 7/3. (The wrong working printed beside
them, 6 × (−(x + 3)/2) = −3x + 9, is a deliberate find-the-error exercise for pupils, and
the text layer's garbled "x = 6"-looking fragments on that page are extraction artefacts,
not print.) The Gauss sum, the √34 and √200 approximation tables, the 40-value height data
set (count and extremes), the exterior-angle worked example, and the 5-12-13 Pythagoras
working were likewise recomputed and are correct. One extraction-only oddity, **not** a book
error and excluded from the count: the G8 text layer contains repeated stray fragments of
the form "x = 5a + 3b" throughout the Chapter 5 pages (PDF pp. 79–90) — a text-layer
artefact of this PDF copy; the rendered pages show the correct varied vector work.

### 7. Answer keys (Grade 8)

None — no answer key, solutions section or پاسخنامه anywhere in the book.

### 8. Held-copy defects (Grade 8)

None found. All 160 PDF pages carry content; the sparsest text page (PDF p. 9, the
Chapter 1 opener) is an illustrated opener, not a missing page.


---

## Book 3 — Grade 9 Mathematics (g09.pdf)

### 1. Identity block

- Persian title as printed (imprint): ریاضی ـ پایهٔ نهم دورهٔ اول متوسطه
  ("Mathematics — Grade 9, First Period of Secondary School").
  Cover (render-checked, PDF p. 1): ریاضی / پایهٔ نهم / دورهٔ اول متوسطه.
- Grade: 9.
- Publisher / پدیدآورنده: سازمان پژوهش و برنامه‌ریزی آموزشی (OERP), Ministry of Education;
  printed by شرکت چاپ و نشر کتاب‌های درسی ایران.
- Printing as printed on imprint (PDF p. 2): چاپ دوازدهم ۱۴۰۵ — **12th printing, 1405**
  (school year 1405–1406).
- ISBN as printed: **978-964-05-2435-0**.
- Book code as printed: **905**.
- PDF pages: **152**. Printed pages 1–144 plus front matter (address to the teacher,
  PDF pp. 7–8).
- Offset: **printed page = PDF page − 8** (printed p. 1, the Chapter 1 opener, is PDF p. 9;
  Lesson 1 begins on printed p. 2 = PDF p. 10; the last printed page, 144, an OERP feedback
  notice, is PDF p. 152).

### 2. Kind proof

Cover + imprint name the pupil book «ریاضی ـ پایهٔ نهم»; pupil-facing
activity/classwork/exercise apparatus throughout: a pupil's textbook (the سخنی با معلم
preface is front matter only).

### 3. Contents (printed pages)

| Ch. | Title | Lessons (printed pp.) |
|---|---|---|
| 1 | Sets (p. 1) | Introducing sets 2 · Equal sets and representing sets 6 · Union, intersection and difference of sets 11 · Sets and probability 15 |
| 2 | Real numbers (p. 18) | Rational numbers 19 · Real numbers 23 · Absolute value and approximate computation 28 |
| 3 | Reasoning and proof in geometry (p. 32) | Reasoning 33 · Introduction to proof in geometry 37 · Congruence of triangles 44 · Problem solving in geometry 49 · Similar figures 53 |
| 4 | Powers and roots (p. 59) | Integer powers 60 · Scientific notation 65 · Root-taking 68 · Adding and subtracting radicals 73 |
| 5 | Algebraic expressions (p. 78) | Algebraic expressions and the concept of identity 79 · More identities, factorising and applications 86 · Inequalities and in-equations 90 |
| 6 | Line and linear equations (p. 95) | Equation of a line 96 · Slope of a line and y-intercept 102 · Systems of linear equations 108 |
| 7 | Rational expressions (p. 113) | Introducing and simplifying rational expressions 114 · Computations with rational expressions 119 · Division of polynomials 126 |
| 8 | Volume and area (p. 130) | Volume and surface area of a sphere 131 · Volume of pyramid and cone 135 · Surface and volume 140 |

This book has no end-of-chapter مرور فصل review sections (unlike G7/G8); each lesson ends
with classwork and exercises.

### 4. Everything taught, chapter by chapter

**Ch. 1 — Sets (pp. 1–17).**
- *Introducing sets* (p. 2): a set must be specified by a well-defined rule ("four Iranian
  poets" and "four tasty fruits" fail the test; "two primes less than 12" passes); members
  (عضو) must be distinct — {1, 2, 1, 4, 5} must be rewritten without the repeat; membership
  symbol ∈ / ∉; naming sets with capital letters; the **empty set** ∅ = {}, with the explicit
  warning that {∅} and {0} each have one member and are not the empty set; counting members.
- *Equal sets and representing sets* (p. 6): equal sets (same members); **subset** ⊆ with
  worked justifications (e.g. {a, b, d} ⊄ {a, b, c, e} because d is missing on the right;
  {−1, 0, 1, 3} ⊆ {4, 3, 0, 1, −1, 2} member by member); Venn diagrams; roster form;
  **set-builder form**: N = {1, 2, 3, …}, E = {2k | k ∈ N}, {x | x ∈ Z, −5 ≤ x < 5},
  B = {3k + 2 | k ∈ Z}; Q defined in set-builder form as {a/b | a, b ∈ Z, b ≠ 0}, with
  Z ⊂ Q argued from a = a/1; Q cannot be listed because there is no "first rational above"
  a given one (density foreshadowed).
- *Union, intersection, difference* (p. 11): ∩ and ∪ from a two-team Venn situation; worked
  example A = {1, 2, 3, 4, 5, 8}, B = {3, 4, 5, 6, 7}: A ∩ B = {3, 4, 5} and
  A ∪ B = {1, 2, 3, 4, 5, 6, 7, 8} (recomputed: correct); difference defined
  A − B = {x | x ∈ A, x ∉ B} with worked A − B = {a, b, e}, B − A = {f, s, t}; exercises test
  identities such as (A − B) ∪ (A ∩ B) = A and special cases A ∩ A, A ∪ ∅, A ∩ ∅.
  **No complement set and no universal set are introduced.**
- *Sets and probability* (p. 15): sample space as a set S, event as a set A, and the formula
  restated as **P(A) = n(A) / n(S)**; spinner and die events described set-theoretically;
  the three-children family sample space written as ordered triples, P(exactly two girls)
  asked (= 3/8 by the pupils' own counting).

**Ch. 2 — Real numbers (pp. 18–31).**
- *Rational numbers* (p. 19): comparing fractions by several pupils' methods (common
  denominator 360, decimals, the line); **between any two rationals there are arbitrarily
  many rationals** (density, argued from the averaging/common-denominator methods);
  decimal expansions computed (5/11, 7/9, 5/6, 7/22, 3/20, 5/16) and the criterion *stated*:
  a fraction in lowest terms has a terminating decimal iff its denominator has no prime
  factor other than 2 and 5.
- *Real numbers* (p. 23): √2's decimal never settles (calculator displays compared);
  irrationals (عددهای گنگ) Q′; π is irrational — printed to 30 decimal places
  (π ≈ 3.141592653589793238462643383279; reader-checked against π: correct); **√n is
  irrational whenever n is not a perfect square** — stated, not proved; Venn picture
  N ⊂ Z ⊂ Q, R = Q ∪ Q′, with Q ∩ Q′ = ∅ and R ∩ … matching exercises (Q′ ∩ R = Q′ etc.);
  bracketing roots between integers (4 < 7 < 9 ⇒ 2 < √7 < 3); sets of reals drawn as
  intervals on the line with filled/hollow endpoints, e.g. A = {x ∈ R | 2 ≤ x < 3};
  W (whole numbers, حسابی, including 0) used in the classification table on p. 27.
- *Absolute value and approximate computation* (p. 28): |a| defined as the distance of a's
  point from the origin; |1 − √2| = √2 − 1 worked with the reason √2 ≈ 1.4, so 1 − √2 < 0;
  evaluating |a + b + c| for mixed radical values; comparing |a + b| with |a| + |b| and
  |a| − |b| in classwork (the triangle inequality is *explored numerically, never stated*);
  removing absolute bars under sign hypotheses; √(x²) type items begin here and are finished
  in Ch. 4 ((√(−2595)²) style computations).

**Ch. 3 — Reasoning and proof in geometry (pp. 32–58).**
- *Reasoning* (p. 33): optical-illusion opener (the senses deceive); inductive reasoning
  from instances is shown to be unreliable (a football fan's "my team always loses when I
  attend"; the claim that the altitudes of every triangle meet inside — pupils must produce
  the obtuse-triangle counterexample; perpendicular bisectors likewise); everyday fallacies
  matched to their logical shapes (affirming the consequent etc., in story form; the terms
  "induction/deduction" are carried by the activities rather than a formal logic vocabulary).
- *Introduction to proof* (p. 37): a proof works from the **hypotheses (فرض)** and previously
  established facts to the **claim (حکم)**; rectangle diagonals are equal, set up as
  فرض/حکم; a *flawed* printed proof (congruence of ∆ABC and ∆ADC from a bisector, smuggling
  in Ĉ₁ = Ĉ₂ without justification) is given for pupils to diagnose, then a correct SAS
  proof; when a proved property generalises (all members of the set share the features
  used); the **perpendicular-bisector theorem is now proved** (point P on the bisector,
  ∆AHP ≅ ∆BHP by SAS); the **triangle angle-sum theorem is proved** by drawing the parallel
  through A and using alternate angles; **vertical angles are proved equal** in full
  (Ô₁ + Ô₂ = 180°, Ô₃ + Ô₂ = 180° ⇒ Ô₁ = Ô₃; render-level text, recomputed: correct);
  the exterior-angle theorem's printed "proof" is itself put on trial in an exercise;
  definition-checking arguments about convex polygons (one pupil's single pair of points
  does not establish convexity — counterexample thinking).
- *Congruence of triangles* (p. 44): the G8 cases rewritten in symbolic فرض ⇒ حکم form
  (SAS displayed in full); applications: the Quran-stand (رحل) symmetry argument;
  in a rhombus, ∆ADM ≅ ∆ABN completed from the rhombus properties; a classroom debate —
  a pupil claims opposite sides of a parallelogram are equal "by definition" (they are
  not: the G8 definition is parallel sides only) and another "by measuring" (not a proof) —
  after which opposite sides/angles of a parallelogram are *derived* from congruent
  triangles; exercises: **prove the diagonals of a parallelogram bisect each other** and
  **the diagonals of a rectangle are equal**.
- *Problem solving in geometry* (p. 49): a four-step method (understand and draw; tabulate
  فرض/حکم; find a route — typically congruent triangles; write the proof) carried through a
  fully worked surveying problem (two villages A, B either side of a road; M the midpoint
  of AB; AH and BH′ perpendicular to the road line d; prove AH = BH′); further proof
  exercises (arc-chasing AC = BD from AB = CD on a line; MN = PQ for midpoints of a
  parallelogram's sides; any point on the bisector of an isosceles triangle's apex angle is
  equidistant from the base endpoints, MB = MC).
- *Similar figures* (p. 53): similarity defined — corresponding angles equal and all
  corresponding sides changed by one ratio; **ratio of similarity** (نسبت تشابه) named;
  every two squares are similar, arbitrary rectangles/rhombi are not (counterexample
  questions); congruent figures are similar with ratio 1; similarity checked on coordinate
  triangles by computing side lengths (with Pythagoras); no AA/SAS/SSS similarity *criteria*
  are stated or proved — similarity is verified from the definition.

**Ch. 4 — Powers and roots (pp. 59–77).**
- *Integer powers* (p. 60): negative exponents motivated by continuing the halving table;
  **a^(−n) = 1/a^n = (1/a)^n** (a ≠ 0) stated generally; all exponent laws extended to
  integer exponents and stated in one display (p. 63): a^m · a^n = a^(m+n),
  a^m ÷ a^n = a^(m−n), (a^m)^n = a^(mn), (ab)^m = a^m b^m, (a/b)^m = a^m / b^m, a⁰ = 1,
  a^(−m) = 1/a^m; comparisons (16² vs 8⁴ vs 2¹¹; sign traps (−5)^(−2) vs −5^(−2) vs 1/(−5)
  style items); hydrogen atom mass ≈ 10^(−24) g used for a ratio computation.
- *Scientific notation* (p. 65): **a × 10^n with 1 ≤ a < 10** defined for positive decimals;
  worked: 124000 = 1.24 × 10⁵, 1700000000 = 1.7 × 10⁹, 1393 = 1.393 × 10³,
  9204000 = 9.204 × 10⁶, 125.39 = 1.2539 × 10², 0.000007 = 7 × 10^(−6),
  0.0016 = 1.6 × 10^(−3) (reader recomputed: all correct); a true/false set in which
  1.02 × 10^(−5) = 0.00000102 and 7.004 × 10^(−2) = 0.7004 are the planted false items.
- *Root-taking* (p. 68): square roots ±√9 = ±3 notation consolidated; **cube root** defined
  (∛8 = 2, ∛(−8) = −2 since (−2)³ = −8) — negative numbers have cube roots though not square
  roots; ∛(ab) = ∛a · ∛b and ∛(a/b) = ∛a / ∛b guessed from tables and used
  (∛128 = ∛64 · ∛2 = 4∛2); √(x²) = x only under conditions (exercise: for which x is
  (−√x)² = x true?); simplifying surds begins: √90 = √(2 · 3² · 5) = 3√10 worked in full.
- *Adding and subtracting radicals* (p. 73): like radicals collected after simplification —
  worked in full: √72 − √32 + √18 = 6√2 − 4√2 + 3√2 = **5√2** (recomputed: correct), and a
  cube-root analogue ⁵√…/∛81 combination; a square of diagonal 2√6 has side 2√3 and area 12
  via Pythagoras (2x² = 24); products like (√2 + √3)(3√2 − 3); **rationalising the
  denominator** (گویا کردن مخرج): 20/√2-type computation re-done as
  (20 × √2)/(√2 × √2) to avoid dividing by a radical, then drilled (6/√3, 3x/√… etc.).

**Ch. 5 — Algebraic expressions (pp. 78–94).**
- *Expressions and the concept of identity* (p. 79): monomials (تک‌جمله‌ای) and their degree
  (in one variable, and total degree — 3ax²y⁴ table: degrees 2 in x, 4 in y, total 6);
  like/unlike monomials; polynomials (چندجمله‌ای); an **identity (اتحاد)** is an equality
  true for all values — (x + 3)² = x² + 6x + 9 first *guessed* from a value table, then
  verified by expansion; **square-of-a-binomial identity stated for all reals**:
  (a + b)² = a² + 2ab + b², (a − b)² = a² − 2ab + b² (worked (5x + 2)² = 25x² + 20x + 4;
  recomputed: correct); factorising by the greatest common factor, named ب.م.م of the terms
  (8x² + 12x = 4x(2x + 3) worked), and recognising a² + 2ab + b² as (a + b)².
- *More identities, factorising and applications* (p. 86): (a + b + c)² by two routes;
  **difference of squares (اتحاد مزدوج)**: (a + b)(a − b) = a² − b², justified geometrically
  for a > b > 0 and used both ways (A² − B² = (A + B)(A − B); (10 − x)(x + 10) = 100 − x²);
  mental arithmetic: 98 × 102 = 100² − 2², 497 × 503, 1001² = (1000 + 1)²;
  the **common-term identity**: (x + 2)(x + 5) = x² + 7x + 10 generalised, then used to
  factorise x² + 10x − 24 — four pupils' attempts are judged (only (x + 12)(x − 2) is
  correct; reader verified: (x + 12)(x − 2) = x² + 10x − 24 ✓, (x + 6)(x − 4) = x² + 2x − 24 ✗
  as the book intends); (x − 1)(x + 1)(x² + 1) chained products.
- *Inequalities and in-equations* (p. 90): inequality signs from a balance picture; properties
  **stated and render-verified (printed p. 92)**: adding the same number to both sides
  preserves the inequality; multiplying by a positive c preserves it (a > b, c > 0 ⇒
  ac > bc); multiplying by a negative c reverses it (c < 0 ⇒ ac < bc); a first-degree
  one-unknown in-equation (نامعادله) defined; solution set (مجموعه جواب) in set-builder form
  and on the line — worked: 2x + 1 > 7 ⇔ x > 3, D = {x ∈ R | x > 3}; fractional in-equation
  cleared by ×6 (render-verified, printed p. 93): x/3 − 1/2 < (x − 1)/6 → 2x − 3 < x − 1 →
  x < 2, D = {x ∈ R | x < 2} (recomputed: correct); sign-analysis true/false items
  (ab < 0 ⇒ opposite signs, etc.); a survival-calorie word problem (85 kg and 65 kg, food
  of 4500 kcal, daily need three times body weight — set up as an in-equation);
  exercise 5 asks to *show* a² > b² given a > b > 0 using the difference-of-squares identity.

**Ch. 6 — Line and linear equations (pp. 95–112).**
- *Equation of a line* (p. 96): relations (رابطه) between quantities (cyclist d = 2t, candle,
  n → 2n pattern); y = 4x (perimeter) graphed from a table vs y = x² (area), whose points
  form a curve, not a line; a line's equation read off its graph; a two-variable linear
  equation has infinitely many solutions (five solutions each for y = 2x − 1 and
  3x − 4y = 12); drawing lines from tables (y = −x + 3, y = (1/2)x + 2…); y = ax always
  passes through the origin; intercepts of y = 5x + 1 found algebraically.
- *Slope and y-intercept* (p. 102): the family y = (1/2)x, y = x, y = 3x, y = −x, y = −2x
  compared — the coefficient of x controls the angle with the positive x-axis, negative
  slope making an obtuse angle; slope (شیب) and y-intercept (عرض از مبدأ) named for
  y = ax + b; **slope as rise over run computed from a right triangle on the line**
  (worked: slope of d₁ = EB/EA = 2/1 = 2); the two-point slope formula
  (y₂ − y₁)/(x₂ − x₁) set as a "show that" exercise (p. 107); vertical lines x = 2;
  the general form ax + by = c rearranged to slope–intercept form (worked:
  2y − 4x = 8 → y = 2x + 4, slope 2, intercept 4; recomputed: correct); parallel lines
  (equal slopes) used to write equations through given points; sign-of-a/b quadrant sketching.
- *Systems of linear equations* (p. 108): break-even context (two internet tariffs,
  y = 3000 + 2000x vs y = 3000x, in thousands of tomans); solution by graphing
  ({x − y = 1, x + y = 3} and {2x − y = 3, x + 2y = 3}); multiplying an equation by a number
  gives the same line (2x − 3y = 4 vs 4x − 6y = 8) — coincident lines and infinitely many
  solutions recognised; **elimination** built from "equals added to equals" (balance
  pictures) and applied; **substitution (روش جایگزینی)** named and worked
  ({2x − 3y = 5, y = (1/3)x − (2/3)}-form system); rectangle length/perimeter modelling.
  The no-solution (parallel distinct lines) case is not separately theorised.

**Ch. 7 — Rational expressions (pp. 113–129).**
- *Introducing and simplifying* (p. 114): a rational expression is a ratio of two
  polynomials; opening problem solved in full: width x, length x + 4, x/(x + 4) = 2/3 →
  3x = 2x + 8 → x = 8, length 12 (recomputed: correct); recognising non-examples (absolute
  values, √x in numerator…); **undefined values**: denominator zero excluded —
  (x − 1)(x + 2) in a denominator excludes x = 1 and x = −2, worked; simplifying by
  factorising and cancelling: (y² − 9)/(3y + 9) = (y − 3)/3, (b − 5)/(5 − b) = −1,
  (m² − 16)/(4 − m), (a² − 5a − 14)/(a² + a − 2) in exercises; a wrong cancellation
  (a + ax)/a = a + x is presented against the correct = 1 + x for pupils to judge;
  expressions equal to 1 or −1 identified.
- *Computations* (p. 119): multiplication/division by the fraction rules
  (a/b)·(c/d) = ac/bd, (a/b) ÷ (c/d) = ad/bc, with factorise-and-cancel throughout
  ((a² − a − 6)/(a + 3) × … type); addition/subtraction over common denominators
  (a/b + c/d = (ad + bc)/bd stated for rationals and carried over), incl. x/(x − y) +
  y/(y − x) sign handling; **compound (complex) rational expressions** simplified both ways
  (simplify numerator and denominator separately, or multiply through by a common
  denominator — worked with a/(a + 1) forms, conditions a ≠ 0, a ≠ −1 printed);
  applied perimeter/area problems that end in rational equations (one worked through to
  7x = 35, x = 5); a true/false correction set on rational identities (a/b − … = (a − b)/… traps).
- *Division of polynomials* (p. 126): monomial ÷ monomial and polynomial ÷ monomial
  ((a + b + c)/d = a/d + b/d + c/d); the division relation dividend = divisor × quotient +
  remainder with remainder degree < divisor degree; **long division worked in full**:
  (2x² − 7x − 15) ÷ (x − 5) = 2x + 3, remainder 0, and (10x⁴ − 3x² + 2x − 19) ÷ (2x² − 3)
  begun with quotient 5x² + 6 … (reader verified: (2x² − 3)(5x² + 6) = 10x⁴ − 3x² − 18, so
  the remainder is 2x − 1, consistent with the book's layout); missing-degree terms handled
  by ordering in descending powers.

**Ch. 8 — Volume and area (pp. 130–144).**
- *Volume and surface area of the sphere* (p. 131): sphere inscribed in a cylinder
  (height = diameter); the water-filling experiment — a hemisphere placed in its cylinder
  and the second hemisphere's water filling the rest — leads to **V = (4/3)πR³**, printed as
  the formula "دستور" (the sphere is 2/3 of the circumscribing cylinder of height 2R in the
  equivalent reading); surface: covering a hemisphere with two great-circle paper discs and
  discussing the approximation honestly, then the book states "it is proved that the
  surface of a hemisphere is twice the area of its base circle", giving **S = 4πR²**;
  Earth exercise (diameter ≈ 12,800 km: scientific notation, surface area, Iran's
  1,648,000 km² as a fraction/percentage of it); capsule (cylinder + two hemispheres)
  volumes.
- *Volume of pyramid and cone* (p. 135): pyramid anatomy (base, apex, lateral faces,
  regular pyramids); comparing pyramids by base area and height; **a prism is dissected
  into three pyramids of equal volume** (guided activity), hence **V_pyramid = (1/3)Sh**;
  slant height of a regular square pyramid by Pythagoras (base 12 cm, lateral edge 10 cm —
  OM computed in right triangle OBM); cone **V = (1/3)πR²h** stated as following the pyramid
  rule; worked cone from a sector of radius 10 cm with base diameter 12 cm (the G8 problem
  returning); rectangular-base pyramid 6 × 5 × 10 (V = 100 cm³ by the formula).
- *Surface and volume* (p. 140): nets and total surface areas of cuboids and pyramids;
  cone lateral surface via the sector arc = base circumference relation; **solids of
  revolution** (rectangle → cylinder, right triangle → cone, quarter circle of radius 5 →
  hemisphere-type solid); views from above/front/left; cross-sections (a sphere cut by a
  plane is a circle, largest through the centre; a cube cut to give a rectangle section
  with sides found by Pythagoras); a closing comparison table — cube, sphere, and two
  cylinders of edge/radius a — computing V, S and the ratio V/S for each.
*Stated vs proved in Ch. 8:* the pyramid's 1/3 is genuinely derived by dissection; the
cone's 1/3 is asserted by analogy; the sphere's volume rests on the water experiment and
its surface on a stated "it is proved" — neither is proved in the book.

### 5. Honest negatives (Grade 9)

- No statistics or probability *chapter* this year (probability appears only as the
  sets-based P(A) = n(A)/n(S) restatement in Ch. 1); no new data handling at all.
- Sets: no complement/universal set, no subset counting (2^n), no Cartesian product,
  no set-identity proofs beyond Venn-level checks.
- No quadratic equations or factorising-to-solve (the x² identities are never turned into
  equations to solve), no quadratic functions or parabolas (y = x² is graphed once, as a
  non-line), no completing the square.
- Systems: only 2 × 2 linear; elimination and substitution only — no determinants, no
  three-variable systems; the parallel/no-solution case is not named.
- Functions are still not named as a concept (رابطه "relation" only); no domain/range
  language, no function notation f(x).
- Roots: no n-th roots beyond cube roots, no fractional exponents, no radical *equations*
  (no solving √x = a), no conjugate-pair rationalising (only single-radical denominators).
- Geometry: similarity criteria (AA etc.) are not stated; no Thales/basic-proportionality
  theorem, no trigonometric ratios, no circle chapter this year (G8's circle results are
  assumed), no constructions unit.
- No vectors this year; no sequences/series beyond pattern n-th terms from earlier years.

### 6. Confirmed book errors (Grade 9)

**0 confirmed errors.** The two places where the text layer made the print look wrong were
both render-verified as correct in print (PDF pp. 100–101, printed pp. 92–93): the
inequality multiplication properties (positive multiplier preserves, negative reverses) and
the worked in-equation x/3 − 1/2 < (x − 1)/6 with solution set D = {x ∈ R | x < 2}. Also
recomputed and correct: π to 30 decimal places (p. 24); all seven scientific-notation worked
examples (p. 66); √72 − √32 + √18 = 5√2 (p. 74); (2x² − 7x − 15) ÷ (x − 5) = 2x + 3 (p. 128);
the Ch. 7 opening ratio problem (x = 8, length 12); 2y − 4x = 8 → y = 2x + 4 (p. 106);
the set example A ∪ B / A ∩ B (p. 12); the vertical-angles proof (p. 42). Deliberate
planted mistakes (the flawed congruence proof in Ch. 3, the false scientific-notation
items, three of the four factorisations of x² + 10x − 24) are exercises for pupils to
catch and are not counted as errors.

### 7. Answer keys (Grade 9)

None — no answer key, solutions section or پاسخنامه anywhere in the book.

### 8. Held-copy defects (Grade 9)

None found. All 152 PDF pages carry content. The chapter-opener pages (printed pp. 1, 18,
32, 59, 78, 95, 113, 130) extract as rows of dots — they are printed dotted design openers
in this edition, not missing pages (spot-checked against the surrounding pagination, which
is continuous).

---

## Band B totals

| | Files | PDF pages | Printed pages | Confirmed book errors |
|---|---|---|---|---|
| Grade 7 (g07.pdf, code 705) | 1 | 135 | 124 | 0 |
| Grade 8 (g08.pdf, code 805) | 1 | 160 | 152 | 0 |
| Grade 9 (g09.pdf, code 905) | 1 | 152 | 144 | 0 |
| **Band B total** | **3** | **447** | **420** | **0** |

Band-level notes for the coordinator:

- All three books are OERP pupil books for school year 1405–1406 printings (G7 14th
  printing 1405, G8 13th printing 1405, G9 12th printing 1405); ISBNs 978-964-05-2242-4 /
  978-964-05-2379-7 / 978-964-05-2435-0; codes 705 / 805 / 905. No branch split, no teacher
  guide or workbook in the band, no answer key in any book.
- The band's arc: G7 builds number (integers), first algebra, congruence-by-superposition,
  gcd/lcm, prism volume, powers/roots, vectors-and-coordinates, descriptive statistics with
  theoretical probability. G8 adds rationals, the sieve, polygon angle theory, full vector
  algebra with i/j, Pythagoras, congruence *criteria*, radical rules, grouped-data mean and
  sample-space counting, and the circle. G9 caps it with sets, real numbers and absolute
  value, a genuine proof strand (angle sum, vertical angles, perpendicular bisector,
  parallelogram properties), integer exponents and scientific notation, cube roots and
  radical arithmetic, the named identities and inequalities, lines and 2 × 2 systems,
  rational expressions with polynomial long division, and sphere/pyramid/cone volumes.
- Proof posture across the band: results are overwhelmingly *stated or discovered through
  activities*; the only fully written proofs are in G9 Ch. 3 (plus the G9 pyramid-volume
  dissection). Pythagoras (G8), the tangent–radius perpendicularity (G8), irrationality of
  √n (G9), the terminating-decimal criterion (G9) and the sphere formulas (G9) are all
  asserted without proof — the filings above mark each one.

---

## Band C — Upper secondary, Grades 10–11 (all branches)

Band reader filing for the LiqLearns courses read of the Iran mathematics set.
Set context: `../set-verification.md` (22 files in hand; this band = the 8 files
for Grades 10–11). All books are Persian (Farsi) pupil textbooks of the
Organization for Educational Research and Planning (OERP, سازمان پژوهش و
برنامه‌ریزی آموزشی), Ministry of Education, printed by the Iran Textbook
Publishing Company (شرکت چاپ و نشر کتاب‌های درسی ایران). The branches are
filed SEPARATELY throughout: Mathematical Sciences (ریاضی و فیزیک),
Experimental Sciences (علوم تجربی), Humanities (ادبیات و علوم انسانی ـ علوم و
معارف اسلامی). No teacher guide or workbook for any of these books is in the set.

## Method honesty (header)

- Every book was read from its full text extract
  (`../scratch/txt/<basename>.txt`, one chunk per PDF page) cover to last page,
  chapter by chapter; contents lists below are the books' own printed
  contents pages, cross-checked against the chapter/lesson openings in the body.
- Identity (title, branch, code, printing, ISBN) was taken from the cover and
  the imprint page (PDF p. 2) of each book. ISBNs print in the imprint in RTL
  order; each ISBN below was decoded, then validated by its ISBN-13 check
  digit (all 8 valid), and the imprint pages were additionally render-checked
  (pdftoppm) for g10-maths, g10-maths-stats and g11-calculus, and the cover of
  g10-maths. All 8 ISBNs ARE present in the text layer — the warning that
  senior imprints might hide the ISBN did not bite for this band.
- Printed page numbers are the books' own folios. The printed↔PDF offset was
  established per book from at least two anchors (chapter opening + last
  numbered page) and is stated in each identity block; all page references
  below are PRINTED pages unless marked "PDF".
- Error hunting: checkable numeric claims were recomputed (standard
  deviations, a price-index worked example, an inflation percentage, Heron /
  combination / logarithm material). A claim is filed as a CONFIRMED error
  only where the recomputation disagrees AND the printed page was verified on
  a pdftoppm render. Extraction-only suspicions are listed separately as
  "unverified" and are NOT counted. Persian decimal notation uses a slash
  (e.g. 8/97 = 8.97); RTL digit strings in the text layer reverse — every
  number quoted below was read with that trap in mind.
- Answer keys: none of the 8 books contains an answer key / solutions section;
  each book ends with exercises (تمرین) without printed answers, then a
  sources list (منابع) and publisher credits. Stated once here, repeated per book.
- Held-copy defects: all 8 PDFs are complete and legible (page counts match
  the set record; no missing, duplicated or corrupt pages found). None.

Band totals: **8 files, 1,016 PDF pages, 1 confirmed error** (see §9).

---

## 1. g10-maths.pdf — Mathematics (1), Grade 10 — SHARED: Mathematical Sciences + Experimental Sciences

### Identity
- Persian title as printed: ریاضی (۱) — رشته‌های ریاضی و فیزیک ـ علوم تجربی —
  پایۀ دهم — دورۀ دوم متوسطه
- English: *Mathematics (1) — branches of Mathematics & Physics and
  Experimental Sciences — Grade 10 — second cycle of secondary school*
- Grade / branch: Grade 10; ONE book shared by Mathematical Sciences and
  Experimental Sciences (cover and imprint both name both branches).
- Publisher: OERP (authoring body: Office for Compiling General and
  Theoretical Secondary Textbooks); publisher/printer as printed: Iran
  Textbook Publishing Company, Tehran.
- Year / printing as printed: چاپ یازدهم ۱۴۰۵ — 11th printing, 1405
  (school year 1405–1406).
- ISBN as printed: 978-964-05-2512-8 (check digit valid; imprint render-verified).
- Book code: 110211.
- PDF pages: 176. Printed pages: 1–170. Offset: PDF page = printed page + 6.

### Kind proof
Cover (PDF p. 1) prints the pupil-book title, both branches, "Grade 10,
second secondary cycle"; imprint (PDF p. 2) names it نام کتاب (book title) in
the OERP textbook series with book code 110211 — a student textbook, not a
guide or workbook.

### Contents (printed pages)
- Ch. 1 Sets, Patterns and Sequences (p. 1): L1 Finite and infinite sets (2);
  L2 Complement of a set (8); L3 Pattern and sequence (14); L4 Arithmetic and
  geometric sequences (21).
- Ch. 2 Trigonometry (28): L1 Trigonometric ratios (29); L2 The trigonometric
  (unit) circle (36); L3 Relations between the trigonometric ratios (42).
- Ch. 3 Rational Powers and Algebraic Expressions (47): L1 Root and power (48);
  L2 The n-th root (54); L3 Rational powers (59); L4 Algebraic expressions (62).
- Ch. 4 Equations and Inequalities (69): L1 The quadratic equation and its
  methods of solution (70); L2 Parabola (78); L3 Sign determination (83).
- Ch. 5 Function (94): L1 The concept of function and its representations (95);
  L2 Domain and range of functions (101); L3 Types of function (109).
- Ch. 6 Counting, Without Counting (118): L1 Counting (119); L2 Permutation
  (127); L3 Combination (133).
- Ch. 7 Statistics and Probability (141): L1 Probability, or measuring chance
  (142); L2 Introduction to statistics, population and sample (152); L3
  Variable and its types (159).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 1–27).** Number sets N ⊂ W ⊂ Z ⊂ Q ⊂ R and irrationals as
  R−Q (p. 2); intervals on the real line; finite vs infinite sets, set
  membership and Venn representation; complement relative to a universal set,
  set operations (pp. 8–13). Patterns: recognising and continuing a pattern,
  the general (n-th) term of a sequence (pp. 14–20). Arithmetic sequences
  (common difference, n-th term) and geometric sequences (common ratio, n-th
  term) defined and worked (pp. 21–27). Definitions are stated in boxed text;
  results are developed through activities rather than formally proved.
- **Ch. 2 (pp. 28–46).** sin, cos, tan (and cot) defined for acute angles in a
  right triangle (p. 29); ratios for the standard angles; the unit circle with
  signed angles (counter-clockwise positive), ratios read off the circle for
  angles in all quadrants (p. 36); the fundamental identity sin²θ + cos²θ = 1
  and tan = sin/cos relations, used to find one ratio from another (pp. 42–46).
  Identities are stated and verified on examples, not proved in general.
- **Ch. 3 (pp. 47–68).** Square and cube roots, simplification of radicals
  (p. 48); n-th root defined, existence/uniqueness conventions for even/odd n
  (p. 54); rational exponents a^(m/n) defined via roots and their laws (p. 59);
  algebraic expressions: identities (difference of squares, square of a
  binomial/trinomial, sum/difference of cubes), factorisation, algebraic
  fractions (pp. 62–68). Worked-example types: simplify a radical, factorise a
  polynomial, simplify a compound fraction.
- **Ch. 4 (pp. 69–93).** Quadratic equations solved by factorising, completing
  the square, and the discriminant/formula method; nature of roots from the
  discriminant (pp. 70–77). The parabola y = ax² + bx + c: vertex, axis,
  intercepts, sketching (pp. 78–82). Sign determination: sign charts for linear
  and quadratic expressions, solving quadratic and rational inequalities
  (pp. 83–93).
- **Ch. 5 (pp. 94–117).** Function defined as a rule/machine and as a set of
  ordered pairs; representations (table, graph, formula, words) (p. 95);
  domain and range found from formula and graph, including square-root and
  rational functions (pp. 101–108); types: constant, identity, linear,
  quadratic, absolute-value and piecewise functions, with graphs (pp. 109–117).
- **Ch. 6 (pp. 118–140).** Addition and multiplication principles of counting
  (p. 119); permutations P(n,r) = n!/(n−r)! (p. 127); combinations
  C(n,r) = n!/(r!(n−r)!) defined as r-subsets, with worked examples of the
  type "choose 4 of 6 books" vs "arrange 4 of 6 books" (pp. 133–140; the
  combination formula and example on printed p. 134 were recomputed/checked —
  correct).
- **Ch. 7 (pp. 141–170).** Classical probability P = favourable/total for
  equally likely outcomes, probability of complement and union events
  (pp. 142–151); statistics introduced: population (جامعه) and sample (نمونه),
  sampling ideas (pp. 152–158); variables classified quantitative/qualitative,
  discrete/continuous, nominal/ordinal (pp. 159–170). No measures of centre or
  spread are computed in this book — that is the Humanities book's Ch. 3–4
  territory (see §3); this is a genuine branch difference, not an omission.

### Errors
- Confirmed: **0**. Spot recomputations passed (combination formula/example,
  p. 134; counting exercises are unsolved تمرین, no printed answers to check).
- Unverified suspicions: none filed.

### Answer key / defects
- Answer key: none (exercises unsolved; book ends at printed p. 170 with
  exercises, no solutions section).
- Held-copy defects: none.

### Honest negatives (this book)
No geometry beyond the parabola and coordinate sketching; no limit,
derivative or integral; no logarithm/exponential function (only rational
powers); probability stops at the classical equally-likely model — no
conditional probability, no Bayes; statistics is vocabulary-only (no mean,
median, variance or charts beyond an introductory look).

---

## 2. g10-geometry.pdf — Geometry (1), Grade 10 — Mathematical Sciences ONLY

### Identity
- Persian title as printed: هندسه (۱) — رشتۀ ریاضی و فیزیک — پایۀ دهم — دورۀ
  دوم متوسطه
- English: *Geometry (1) — Mathematics & Physics branch — Grade 10*
- Grade / branch: Grade 10, Mathematical Sciences only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ یازدهم ۱۴۰۵ — 11th printing, 1405.
- ISBN as printed: 978-964-05-2501-2 (check digit valid).
- Book code: 110213.
- PDF pages: 96. Printed pages: 1–96 (the PDF paginates from the cover, so
  PDF page = printed page, offset 0 — verified at printed pp. 9 and 96).

### Kind proof
Cover (PDF p. 1) prints هندسه (۱), the Mathematics & Physics branch, Grade 10;
imprint (PDF p. 2) lists it as the OERP pupil textbook, code 110213.

### Contents (printed pages)
- Ch. 1 Geometric Constructions and Reasoning (9): L1 Geometric constructions
  (10); L2 Reasoning (17).
- Ch. 2 Thales' Theorem, Similarity and Their Applications (29): L1 Ratio and
  proportion in geometry (30); L2 Thales' theorem (34); L3 Similarity of
  triangles (38); L4 Applications of Thales' theorem and similarity (45).
- Ch. 3 Polygons (53): L1 Polygons and their properties (54); L2 Area and its
  applications (65).
- Ch. 4 Spatial Visualisation (77): L1 Line, point and plane (78); L2 Visual
  thinking (87).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 9–28).** Ruler-and-compass constructions: perpendicular
  bisector, angle bisector, perpendiculars and parallels, copying segments and
  angles, with justification of why each construction works (pp. 10–16).
  Reasoning: inductive vs deductive reasoning (استقرا و استنتاج), counter-
  examples, the role of definitions and postulates, direct proof and proof by
  contradiction introduced in elementary form (pp. 17–28). This is the most
  proof-dense chapter of the G10 pair: 26 occurrences of "proof" (اثبات) in
  the book sit mostly here and in Ch. 2.
- **Ch. 2 (pp. 29–52).** Ratio and proportion of segments (p. 30); Thales'
  theorem stated and PROVED via equal-area triangles (the proof is developed
  in the activity on p. 34 and the theorem boxed there), plus its converse;
  triangle similarity criteria AA, SAS, SSS stated as theorems and proved/
  justified (pp. 38–44); applications: measuring inaccessible heights and
  distances, mid-segment theorem, dividing a segment in a given ratio
  (pp. 45–52).
- **Ch. 3 (pp. 53–76).** Polygons: convex/non-convex, diagonals count,
  interior/exterior angle sums, regular polygons; quadrilaterals and their
  properties — parallelogram, rectangle, rhombus, square, trapezium —
  with characterisations proved from earlier results (pp. 54–64). Area:
  area postulates, areas of triangle/parallelogram/trapezium, area ratios of
  similar figures, applications (pp. 65–76).
- **Ch. 4 (pp. 77–96).** Point, line and plane in space: relative positions of
  lines and planes, parallel and skew lines, plane determined by points
  (pp. 78–86). Visual thinking: nets, cross-sections of prisms and pyramids
  by a plane, solids of revolution (rotating a segment/rectangle/triangle/
  semicircle about an axis → cylinder, cone, sphere) worked through as
  exercises to the last page (pp. 87–96).

### Errors
- Confirmed: **0**.
- Unverified suspicions: none filed.

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (this book)
No circle theorems (those are G11 Geometry Ch. 1); no coordinate/analytic
geometry; no trigonometry of the sine/cosine rules (G11 Geometry Ch. 3);
no vectors; no volume formulas beyond visualisation of sections and solids
of revolution (volumes are not computed); constructions stay at the classical
ruler-and-compass set. Experimental Sciences and Humanities pupils get NONE
of this book — their G10 geometry exposure is limited to the constructions/
Thales material reused inside G11 Mathematics (2) for Experimental Sciences
(see §6), and none at all in Humanities.

---

## 3. g10-maths-stats.pdf — Mathematics and Statistics (1), Grade 10 — Humanities ONLY

### Identity
- Persian title as printed: ریاضی و آمار (۱) — رشته‌های ادبیات و علوم انسانی ـ
  علوم و معارف اسلامی — پایۀ دهم — دورۀ دوم متوسطه
- English: *Mathematics and Statistics (1) — Literature & Humanities and
  Islamic Sciences branches — Grade 10*
- Grade / branch: Grade 10, Humanities only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ یازدهم ۱۴۰۵ — 11th printing, 1405.
- ISBN as printed: 978-964-05-2503-6 (check digit valid; imprint render-verified).
- Book code: 110212.
- PDF pages: 120. Printed pages: 1–118 + back matter. Offset: PDF page =
  printed page (0) — verified at the chapter-1 opener (printed 9 = PDF 9) and
  the sources list (printed 118 = PDF 118).

### Kind proof
Cover (PDF p. 1) prints ریاضی و آمار (۱) with the Humanities branches and
Grade 10; imprint (PDF p. 2) lists it as the OERP pupil textbook, code 110212.

### Contents (printed pages)
- Part "Mathematics" — Ch. 1 The Quadratic Equation (9): L1 Equation and
  descriptive problems (10); L2 Solving the degree-2 equation and applications
  (19); L3 Equations containing rational expressions (33).
- Ch. 2 Function (39): L1 The concept of function (40); L2 The algebraic rule
  (formula) of a function (50); L3 Graph of a linear function (56); L4 Graph
  of a degree-2 function (63).
- Part "Statistics" — Ch. 3 Working with Statistical Data (71): L1 Collecting
  data (72); L2 Measures of central tendency (85); L3 Measures of dispersion (89).
- Ch. 4 Displaying Data (99): L1 Single-variable charts (100); L2
  Multi-variable charts (110). Sources (118).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 9–38).** Translating word problems into (mainly quadratic)
  equations (p. 10); solving quadratics by factorising and by the general
  formula, with applications (pp. 19–32); equations with rational expressions:
  clearing denominators, checking for extraneous roots (pp. 33–38). No
  completing-the-square development and no sign-chart/inequality work of the
  science book's Ch. 4 — a real branch difference.
- **Ch. 2 (pp. 39–70).** Function concept via ordered pairs, tables and
  real-life rules (p. 40); finding and using a function's formula (ضابطه)
  (p. 50); the linear function's graph, slope read from two points (p. 56);
  the quadratic function's graph as a parabola, vertex by symmetry (p. 63).
  Domain/range formalism and function types of the science book are NOT here.
- **Ch. 3 (pp. 71–98).** Data collection: population, sample, data types
  (pp. 72–84). Central tendency: mean, median, mode defined and computed
  (p. 85). Dispersion (pp. 89–98): range; variance and STANDARD DEVIATION
  defined by the population formula σ = √(Σ(xᵢ−x̄)²/n) and computed in full —
  the three-class worked comparison (each class n = 10, all means 67) prints
  σ = 8.97, σ = 17.75 and σ = 21.23; all three were recomputed from the
  printed data sets and are CORRECT (sums of squared deviations 804, 3152,
  4508). The normal ("bell") curve is introduced descriptively with the
  ±1σ/±2σ/±3σ percentage idea (pp. 91–93); quartiles and the interquartile
  range IQR = Q3 − Q1 are defined (p. 94).
- **Ch. 4 (pp. 99–117).** Single-variable displays: bar, pie (with percentage
  reading), line, pictogram-style and histogram-type charts (p. 100);
  multi-variable displays: grouped/stacked bars and multi-line graphs,
  reading comparisons off them (p. 110).

### Errors
- Confirmed: **0** (the three printed standard deviations above were the main
  checkable claims and all recompute exactly).
- Unverified suspicions: none filed. (A reading box on p. 92 says "at least
  96 of 100" packets fall within ±2σ; the normal-model figure is ≈95.45% —
  loose popular wording in a reading passage, NOT filed as an error.)

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (this book / Humanities track)
No sets/sequences, no trigonometry, no counting/permutation/combination, no
probability taught at all in G10 Humanities (the word احتمال occurs only
colloquially — "به احتمال زیاد", p. 88 — and in a bibliography title,
p. 118); no powers/roots beyond what quadratics
need; no inequalities chapter; no geometry. Conversely — and this must not be
merged away — Humanities G10 is the ONLY G10 track that computes mean/median/
mode, variance, standard deviation, quartiles and IQR; the science G10 book
(§1) teaches none of those.

---

## 4. g11-calculus.pdf — Calculus (1) / Hesaban (1), Grade 11 — Mathematical Sciences ONLY

### Identity
- Persian title as printed: حسابان (۱) — رشتۀ ریاضی و فیزیک — پایۀ یازدهم —
  دورۀ دوم متوسطه
- English: *Calculus (1) (Hesaban 1) — Mathematics & Physics branch — Grade 11*
- Grade / branch: Grade 11, Mathematical Sciences only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ دهم ۱۴۰۵ — 10th printing, 1405.
- ISBN as printed: 978-964-05-2787-0 (check digit valid; imprint render-verified).
- Book code: 111214.
- PDF pages: 160. Printed pages: 1–152 + sources/credits. Offset: PDF page =
  printed page + 6 (verified: ch. 1 opener printed 1 = PDF 7; sources printed
  152 = PDF 158).

### Kind proof
Cover (PDF p. 1) prints حسابان (۱), Mathematics & Physics branch, Grade 11;
imprint (PDF p. 2) lists it as the OERP pupil textbook, code 111214 (also the
coordinator's spot-proof in the set-verification file).

### Contents (printed pages)
- Ch. 1 Algebra and Equation (1): L1 Sum of the terms of arithmetic and
  geometric sequences (2); L2 Quadratic equations (7); L3 Rational and
  irrational (radical) equations (17); L4 Absolute value and its properties
  (23); L5 Introduction to analytic geometry (29).
- Ch. 2 Function (37): L1 Knowing functions better (38); L2 Types of functions
  (44); L3 Inverse of a function (54); L4 Operations on functions (63).
- Ch. 3 Exponential and Logarithmic Functions (71): L1 The exponential
  function (72); L2 The logarithmic function and logarithm (80); L3 Properties
  of logarithms and solving logarithmic equations (86).
- Ch. 4 Trigonometry (91): L1 Radian (92); L2 Trigonometric ratios of some
  angles (98); L3 Trigonometric functions (105); L4 Trigonometric relations
  for sum and difference of angles (110).
- Ch. 5 Limit and Continuity (113): L1 The concept of limit and limit
  processes (114); L2 One-sided limits (left and right limits) (123); L3
  Limit theorems (130); L4 Computing limits of rational functions (the 0/0
  case) (141); L5 Continuity (145). Sources (152).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 1–36).** Sums: Sₙ of an arithmetic sequence and of a geometric
  sequence derived (the 1+2+…+n pairing argument opens the book, p. 2) and
  applied, including finite geometric sums. Quadratics revisited at higher
  level: sum and product of roots, forming an equation from its roots,
  discriminant cases (pp. 7–16). Rational equations and radical (گنگ)
  equations with extraneous-root checking (pp. 17–22). Absolute value:
  definition, properties, equations and simple inequalities with |x|
  (pp. 23–28). Analytic geometry: coordinates, distance between two points,
  midpoint, slope, equation of a line (pp. 29–36).
- **Ch. 2 (pp. 37–70).** Function review deepened: domain/range from graphs,
  equality of functions (p. 38); types: polynomial, rational, radical, floor/
  greatest-integer and piecewise functions, monotonicity read from graphs
  (pp. 44–53); one-to-one functions and inverse functions, graph of f⁻¹ as
  reflection in y = x, inverse of simple formulas (pp. 54–62); operations:
  sum/product/quotient and COMPOSITION of functions (pp. 63–70).
- **Ch. 3 (pp. 71–90).** Exponential function aˣ built from a doubling-bacteria
  activity (m(t) = 2ᵗ, pp. 72–79): graph, growth/decay, one-to-oneness.
  Logarithm defined as the inverse operation (the "when is the mass 512 g?"
  question, p. 80ff.), logarithmic function and its graph. Properties of
  logarithms — log(ab) = log a + log b is PROVED in a worked example from the
  definition (printed p. 86); quotient, power and change-of-base properties
  stated and used; logarithmic equations solved (pp. 86–90).
- **Ch. 4 (pp. 91–112).** The radian defined (arc length = radius, pp. 92–97);
  ratios for angles beyond the acute range using the unit circle, reduction
  to reference angles (pp. 98–104); sin x and cos x as functions: graphs,
  period, amplitude (pp. 105–109); sum and difference formulas
  sin(A±B), cos(A±B) stated (with the double-angle consequences) and applied
  (pp. 110–112).
- **Ch. 5 (pp. 113–151) — the "calculus" of this book is LIMITS ONLY.** Limit
  introduced intuitively: inscribed polygons approaching the circle's area
  (p. 114), numerical tables and graphs; notation lim(x→a) f(x). One-sided
  limits (p. 123). Limit theorems (sum, product, quotient, powers, roots)
  STATED as theorems and used for direct computation (p. 130). Rational
  functions at a 0/0 point handled by factorising/cancelling and by
  conjugate multiplication (p. 141). Continuity defined at a point
  (limit = value, checked on graphs and formulas), continuity on an interval
  (p. 145). Limits of coverage, stated plainly: **no ε–δ definition anywhere**
  (the word does not occur); **no derivative** — the word مشتق (derivative)
  does not occur in the book at all; **no integral** — انتگرال occurs only
  inside bibliography titles of reference books in the sources list. Both
  belong to Hesaban (2), Grade 12, outside this band.

### Errors
- Confirmed: **0**. The logarithm product-property proof (p. 86) and the
  bacteria doubling table (2⁹ = 512, pp. 72–80) recompute/check correctly.
- Unverified suspicions: none filed.

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (Mathematical Sciences, G11 calculus track)
No derivative, no integral, no differential equations, no infinite-series
convergence theory (geometric sums are finite; infinite limits appear only
inside limit processes), no L'Hôpital-type results, no vectors, no conic
sections beyond the line in analytic geometry. Experimental Sciences pupils
never see this book: their G11 limits chapter (§6) is shorter and stays at
the same intuitive level.

---

## 5. g11-geometry.pdf — Geometry (2), Grade 11 — Mathematical Sciences ONLY

### Identity
- Persian title as printed: هندسه (۲) — رشتۀ ریاضی و فیزیک — پایۀ یازدهم —
  دورۀ دوم متوسطه
- English: *Geometry (2) — Mathematics & Physics branch — Grade 11*
- Grade / branch: Grade 11, Mathematical Sciences only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ دهم ۱۴۰۵ — 10th printing, 1405.
- ISBN as printed: 978-964-05-2783-2 (check digit valid).
- Book code: 111213.
- PDF pages: 80. Printed pages: 1–77 + credits. Offset: PDF page = printed
  page (0) — verified at printed pp. 9, 16, 18, 74–77.

### Kind proof
Cover (PDF p. 1) prints هندسه (۲), Mathematics & Physics branch, Grade 11;
imprint (PDF p. 2) lists it as the OERP pupil textbook, code 111213.

### Contents (printed pages)
- Ch. 1 Circle (9): L1 Basic concepts and angles in a circle (10); L2 Length
  relations in a circle (18); L3 Inscribed and circumscribed polygons (24).
- Ch. 2 Geometric Transformations and Applications (31): L1 Geometric
  transformations (32); L2 Applications of transformations (50).
- Ch. 3 Length Relations in a Triangle (59): L1 The sine rule (60); L2 The
  cosine rule (64); L3 The internal angle-bisector theorem and computing
  bisector lengths (68); L4 Heron's theorem (computing heights and the area
  of a triangle) (71).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 9–30).** Circle vocabulary (centre, radius, chord, diameter,
  arc); central, inscribed and tangent–chord (ظلی) angles — the inscribed-angle
  theorem and the tangent–chord angle theorem are developed by guided proof
  in the activities (the tangent–chord theorem is completed as a fill-in
  "قضیه" on p. 15–16 and used thereafter); intersecting chords, secants and
  tangents: the power-of-a-point length relations stated as theorems
  (p. 18ff.); cyclic (inscribed) quadrilaterals — opposite angles
  supplementary — and circumscribed polygons, tangent lengths from a point
  (pp. 24–30).
- **Ch. 2 (pp. 31–58).** Transformations defined as maps of the plane:
  translation, reflection, rotation — and homothety (تجانس) — with their
  invariants (distance, angle, parallelism) stated and checked in activities
  (p. 32ff.); composition of transformations; applications: symmetry in
  patterns/tiling and calligraphy, shortest-path and design problems
  (pp. 50–58).
- **Ch. 3 (pp. 59–77).** After recalling the right-triangle metric relations
  (p. 60): the SINE RULE a/sin A = b/sin B = c/sin C stated and proved via the
  altitude/area argument; the COSINE RULE stated and proved (pp. 64–67);
  the internal bisector theorem (bisector divides the opposite side in the
  ratio of the adjacent sides) and the bisector-length formula (pp. 68–70);
  HERON's formula: the proof is carried out in the book (printed p. 75
  derives S = √(p(p−a)(p−b)(p−c)) with p the semi-perimeter). The
  8-15-17 triangle on p. 74 (exercise 10(c)) is a triangle-type exercise
  — acute, right or obtuse, via exercise 9's cosine-rule criterion — not
  a Heron worked example; its area by Heron (60) is a recomputation,
  not printed.

### Errors
- Confirmed: **0**.
- Unverified suspicions: none filed.

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (this book)
No analytic/coordinate geometry of the circle, no conic sections, no
vector algebra and no vectors chapter (translation in Ch. 2 IS defined
and worked with vectors — translation vector on pp. 33, 38–39 and the
zero vector on pp. 56–57), no 3-D geometry beyond what G10 covered, no trigonometric equations.
Only Mathematical Sciences pupils take this book; the sine/cosine rules reach
Experimental Sciences only in the lighter trigonometry chapter of §6, and
Humanities not at all.

---

## 6. g11-maths.pdf — Mathematics (2), Grade 11 — Experimental Sciences ONLY

### Identity
- Persian title as printed: ریاضی (۲) — رشتۀ علوم تجربی — پایۀ یازدهم — دورۀ
  دوم متوسطه
- English: *Mathematics (2) — Experimental Sciences branch — Grade 11*
- Grade / branch: Grade 11, Experimental Sciences only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ دهم ۱۴۰۵ — 10th printing, 1405.
- ISBN as printed: 978-964-05-2780-1 (check digit valid).
- Book code: 111211.
- PDF pages: 176. Printed pages: 1–168 + credits. Offset: PDF page = printed
  page + 8 (verified: printed 166 = PDF 174, printed 168 = PDF 176).

### Kind proof
Cover (PDF p. 1) prints ریاضی (۲), Experimental Sciences branch, Grade 11;
imprint (PDF p. 2) lists it as the OERP pupil textbook, code 111211.

### Contents (printed pages)
- Ch. 1 Analytic Geometry and Algebra (1): L1 Analytic geometry (2); L2 The
  quadratic equation and the degree-2 function (11); L3 Rational equations
  and radical equations (19).
- Ch. 2 Geometry (25): L1 Geometric constructions (26); L2 Reasoning and
  Thales' theorem (31); L3 Similarity of triangles (42).
- Ch. 3 Function (47): L1 Becoming familiar with some types of function (48);
  L2 Inverse of a function and one-to-one functions (57); L3 Algebraic
  operations on functions (65).
- Ch. 4 Trigonometry (71): L1 Units of angle measurement (72); L2 Further
  relations between the trigonometric ratios (77); L3 Trigonometric
  functions (88).
- Ch. 5 Exponential and Logarithmic Functions (95): L1 The exponential
  function and its properties (96); L2 The logarithmic function and its
  properties (105); L3 Graphs and applications of exponential and
  logarithmic functions (115).
- Ch. 6 Limit and Continuity (119): L1 Limit processes (120); L2 Computing
  limits of functions (128); L3 Continuity (137).
- Ch. 7 Statistics and Probability (143): L1 Conditional probability and
  independent events (144); L2 Descriptive statistics (153).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 1–24).** Coordinates, distance, midpoint, slope and line
  equations (p. 2); quadratic equations and the quadratic function/parabola
  reviewed and extended (p. 11); rational and radical equations with domain
  checking (p. 19). Comparable to Hesaban Ch. 1 minus the sequence sums and
  the absolute-value lesson — those are NOT in this book.
- **Ch. 2 (pp. 25–46).** A compressed import of the Mathematical Sciences G10
  Geometry book: basic constructions (p. 26); reasoning and Thales' theorem
  (p. 31); triangle similarity (p. 42). No polygons/area chapter and no
  spatial visualisation — Experimental Sciences gets roughly half of §2.
- **Ch. 3 (pp. 47–70).** Function types (rational, radical, floor and
  piecewise; absolute value appears only as notation inside one
  function-equality exercise on p. 56, not as a taught type), one-to-one functions and inverses (p. 57), algebraic operations
  on functions including composition (p. 65).
- **Ch. 4 (pp. 71–94).** Degrees and RADIANS as angle units with conversion
  (p. 72); ratio relations for related angles (supplementary, complementary,
  negative angles) on the unit circle (pp. 77–87); sin/cos as periodic
  functions with graphs (p. 88). The sum/difference formulas of Hesaban
  Ch. 4 L4 are NOT here.
- **Ch. 5 (pp. 95–118).** Exponential function introduced through a
  knockout-cup halving activity (p. 96): graph, properties, growth/decay
  applications; logarithm and the logarithmic function with properties
  (p. 105); graphs and real applications (population, decay) (p. 115).
- **Ch. 6 (pp. 119–142) — limits, intuitive level.** Limit processes with
  tables/areas (p. 120); computing limits by substitution, theorems stated
  without proof, 0/0 handled by factorising (p. 128); continuity at a point
  (p. 137). **No derivative and no integral** — the word for derivative does
  not occur in this book either; differentiation is a Grade 12 topic for
  this branch (Mathematics (3)).
- **Ch. 7 (pp. 143–168).** Conditional probability defined (P(A|B) via reduced
  sample space), the multiplication rule, independent vs dependent events
  (p. 144); descriptive statistics: centre (mean, median, mode) and spread
  (range, variance, standard deviation) summarised and computed, with
  charts (p. 153). Bayes' theorem and total probability are NOT in this book
  — they live in the Mathematical Sciences statistics book (§8).

### Errors
- Confirmed: **0**.
- Unverified suspicions: none filed.

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (Experimental Sciences G11)
No sequence sums, no absolute-value chapter, no sum/difference trig formulas,
no circle theorems, no transformations, no sine/cosine rules, no Bayes, no
logic/set-algebra chapter, no derivative/integral. It is a deliberately
lighter single-volume route; it must not be filed as equivalent to the
Mathematical Sciences pair (§4 + §5 + §8).

---

## 7. g11-maths-stats.pdf — Mathematics and Statistics (2), Grade 11 — Humanities ONLY

### Identity
- Persian title as printed: ریاضی و آمار (۲) — رشته‌های ادبیات و علوم انسانی ـ
  علوم و معارف اسلامی — پایۀ یازدهم — دورۀ دوم متوسطه
- English: *Mathematics and Statistics (2) — Literature & Humanities and
  Islamic Sciences branches — Grade 11*
- Grade / branch: Grade 11, Humanities only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ دهم ۱۴۰۵ — 10th printing, 1405.
- ISBN as printed: 978-964-05-2767-2 (check digit valid).
- Book code: 111212.
- PDF pages: 80. Printed pages: 1–72 + credits. Offset: PDF page = printed
  page + 8 (verified: printed 71 = PDF 79, printed 72 = PDF 80).

### Kind proof
Cover (PDF p. 1) prints ریاضی و آمار (۲) with the Humanities branches and
Grade 11; imprint (PDF p. 2) lists it as the OERP pupil textbook, code 111212.

### Contents (printed pages)
- Ch. 1 Becoming Familiar with Logic and Mathematical Reasoning (1): L1
  Propositions and compound propositions (2) — conjunction (4), disjunction
  (5), conditional (6), biconditional (8); L2 Mathematical reasoning (12).
- Ch. 2 Function (21): L1 Constant, piecewise and identity functions (22) —
  types (25), constant (26), piecewise (27), identity (30); L2 Step functions
  and the absolute-value function (34) — step function (34), sign function
  (35), greatest-integer (floor) function (37), absolute value (40); L3
  Operations on functions (45).
- Ch. 3 Statistics (55): L1 Statistical indices (56) — the poverty line (57),
  inflation (60); L2 Time series (63) — time series (64), interpolation (66),
  extrapolation (68). Sources (71).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 1–20).** Propositions and truth values; negation; the four
  compound forms (and/or/if-then/if-and-only-if) with TRUTH TABLES built and
  used (pp. 2–11); quantifier language in elementary form. Mathematical
  reasoning (p. 12): translating verbal statements into symbols, direct
  argument, counter-example, and an introduction to proving/disproving simple
  statements. The preface states the deliberate boundary: proving equivalences
  WITHOUT truth tables is out of scope and must not be examined. This formal
  logic chapter exists in NO other G11 book in this band except the deeper
  Mathematical Sciences version in §8 — the science-track Mathematics (2)/
  Hesaban books contain no logic chapter at all.
- **Ch. 2 (pp. 21–54).** Function concept recalled, then the named family:
  constant, identity, piecewise (چندضابطه‌ای) functions (pp. 22–33); step
  functions in applications (tariffs, postage), the SIGN function and the
  GREATEST-INTEGER (floor, جزء صحیح) function with graphs (pp. 34–44);
  absolute-value function and its graph (p. 40); algebraic operations on
  functions (sum, difference, product, quotient; domain care) (pp. 45–54).
  No inverse functions, no composition, no exponential/logarithm — clear
  branch limits versus §§4/6.
- **Ch. 3 (pp. 55–72).** Statistical indices for social data: the POVERTY LINE
  defined as half the mean or half the median income, computed both ways on a
  household data set, and the international line quoted as about US$1.25/day
  (pp. 56–59); the consumer price index built as a Laspeyres-style basket
  ratio — the worked bread-and-meat example (base prices 1000 and 50000
  rials, current 1500 and 70000, quantities 200 and 80 kg) computes
  (1500·200 + 70000·80)/(1000·200 + 50000·80) × 100 = 5,900,000/4,200,000 ×
  100 ≈ 140.5; recomputed — CORRECT (p. 59); inflation defined as the change
  of the index (p. 60). Time series (marked "for study"): reading a series
  plotted over equal time intervals, comparing mean and standard deviation of
  two cities' six-month rainfall (the table on printed p. 63 is a fill-in
  activity — city A 15, 20, 30, 35, 30, 30 mm; city B 230, 170, 150, 130,
  110, 110 mm — render-verified, no printed totals to fault); interpolation
  and extrapolation explained and used cautiously (pp. 63–70).

### Errors
- Confirmed: **0** (price-index example recomputed exactly; the rainfall
  table is an unsolved activity, render-checked).
- Unverified suspicions: none filed.

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (Humanities G11)
No trigonometry, no geometry, no probability, no sequences, no
exponential/logarithmic functions, no limits; algebra stops at operations on
the elementary named functions. What Humanities has that the science tracks
do not: formal propositional logic with truth tables at this level of
explicitness in a maths book, and socio-economic statistics (poverty line,
price index, inflation, time series) — never merge these into the science
tracks' statistics.

---

## 8. g11-stats-prob.pdf — Statistics and Probability, Grade 11 — Mathematical Sciences ONLY

### Identity
- Persian title as printed: آمار و احتمال — رشتۀ ریاضی و فیزیک — پایۀ یازدهم —
  دورۀ دوم متوسطه
- English: *Statistics and Probability — Mathematics & Physics branch —
  Grade 11*
- Grade / branch: Grade 11, Mathematical Sciences only.
- Publisher: OERP; publisher/printer: Iran Textbook Publishing Company.
- Year / printing as printed: چاپ دهم ۱۴۰۵ — 10th printing, 1405.
- ISBN as printed: 978-964-05-2773-3 (check digit valid).
- Book code: 111215.
- PDF pages: 128. Printed pages: 1–122 + credits. Offset: PDF page = printed
  page + 6 (verified: ch. 1 opener printed 1 = PDF 7; printed 121 = PDF 127).

### Kind proof
Cover (PDF p. 1) prints آمار و احتمال, Mathematics & Physics branch, Grade 11;
imprint (PDF p. 2) lists it as the OERP pupil textbook, code 111215.

### Contents (printed pages)
- Ch. 1 Becoming Familiar with the Foundations of Mathematics (1): L1
  Becoming familiar with mathematical logic (2) — proposition, truth value
  and negation (2), open sentence/propositional function (3), domain of the
  variable (4), compound propositions: conjunction (4), disjunction (5),
  conditional (7), biconditional (10), quantifiers (11), negating quantified
  propositions (13); L2 Set algebra (16) — number of subsets (16), subset in
  symbols (17), the arbitrary-member method (18), equal sets (19), set laws
  and operations (21), De Morgan's laws (27), Cartesian product (30).
- Ch. 2 Probability (35): L1 Foundations of probability (36) — sample space
  (39), axioms/principles of probability (40); L2 Non-equally-likely
  probability (44); L3 Conditional probability (48) — reduced sample space
  (49), multiplication rule (52), law of total probability (55), Bayes' law
  (57); L4 Independent and dependent events (63) — sampling with/without
  replacement (65).
- Ch. 3 Descriptive Statistics (69): L1 Describing and displaying data (70);
  L2 Measures of central tendency (80) — mean (80), median (82), mode (83);
  L3 Measures of dispersion (87) — standard deviation and variance (87),
  coefficient of variation (90), box plot (91).
- Ch. 4 Inferential Statistics (97): L1 Data collection (98); L2 Estimation
  (112) — interval estimation (115). Sources (122).

### What is taught, chapter by chapter
- **Ch. 1 (pp. 1–34).** The fullest logic treatment in the band: propositions,
  truth tables for all connectives, quantifiers ∀/∃ and their negations
  (pp. 2–15); set algebra proved by the arbitrary-member method: subset and
  equality in symbols, union/intersection/complement laws, DE MORGAN's laws
  stated and proved (p. 27), number of subsets 2ⁿ, Cartesian product (pp.
  16–34). Several results are genuinely PROVED here (39 occurrences of
  "proof" in this book), unlike the activity-led style of the other volumes.
- **Ch. 2 (pp. 35–68).** Probability rebuilt on set theory: sample space,
  events as subsets, the probability axioms (p. 40); probability when outcomes
  are NOT equally likely (p. 44); conditional probability defined both by
  reduced sample space and by formula, the multiplication rule, the LAW OF
  TOTAL PROBABILITY and BAYES' theorem stated and worked (pp. 48–62);
  independent vs dependent events, sampling with and without replacement
  (pp. 63–68).
- **Ch. 3 (pp. 69–96).** Data display (tables, bar/line/pie, histogram-type
  displays, stem-style summaries) (p. 70); mean (including grouped/weighted
  use), median, mode (pp. 80–86); dispersion: variance and standard deviation
  by the deviation table method — the Tehran-province red-meat price data
  (13 values: 42, 20, 25, 26, 27, 40, 20, 16, 20, 21, 22, 23, 26 thousand
  tomans) are set as a fill-in table (printed p. 89, render-verified) — the
  coefficient of variation for comparing spread across scales (p. 90), and
  the BOX PLOT (p. 91). A reading box defines the inflation rate
  (P₁−P₀)/P₀ × 100 (pp. 89–90) — see the error filed below.
- **Ch. 4 (pp. 97–121).** Inferential statistics, the only such chapter in the
  band: data collection methods, census vs sampling, sources of bias
  (pp. 98–111); estimation: point estimation of a population mean/proportion
  from a sample, and INTERVAL ESTIMATION introduced with the sample-mean
  distribution picture (pp. 112–121). No named confidence-level machinery
  (no z-values table); the treatment is conceptual with worked numerical
  examples.

### Errors
- **Confirmed: 1 (minor).** Printed p. 89 (PDF p. 95), reading box "Inflation
  rate": the worked example computes the inflation rate for red-meat prices
  rising from 28 to 32 thousand tomans as (32 − 28)/28 × 100 = **14%**,
  printed with an equals sign, and the following page repeats that prices
  "rose 14 percent". Recomputed: 4/28 × 100 = 14.2857…%. The book prints a
  rounded value as an exact equality (correct statement: ≈ 14.3%). Verified
  on the pdftoppm render of PDF p. 95 (filed copy:
  `../scratch/bandc/renders/g11sp-p95-095.png`). Severity: minor — a rounding
  presented as exact in an otherwise correct formula.
- Unverified suspicions: none filed (every other suspicion raised by the RTL
  text layer dissolved on render or recomputation — e.g. the G11 Humanities
  rainfall table in §7 and this book's own meat-price table are fill-in
  activities with no printed results).

### Answer key / defects
- Answer key: none. Held-copy defects: none.

### Honest negatives (this book)
No regression/correlation, no named probability distributions (no binomial
or normal distribution as a distribution — the normal curve is not developed
here), no hypothesis testing (the term occurs once, printed p. 79, as a
historical mention of Fisher in a reading passage — never taught), no confidence-level/z machinery in estimation.
This depth of probability (Bayes, total probability, non-equally-likely
models) and of logic/set algebra belongs ONLY to Mathematical Sciences;
Experimental Sciences (§6 Ch. 7) stops at conditional probability and
independence, and Humanities has no probability book at all.

---

## 9. Band C totals and cross-branch summary

| File | Book | Grade | Branch | PDF pp. | Printed pp. | Confirmed errors |
|---|---|---|---|---|---|---|
| g10-maths.pdf | Mathematics (1) | 10 | Mathematical Sci. + Experimental Sci. (shared) | 176 | 170 | 0 |
| g10-geometry.pdf | Geometry (1) | 10 | Mathematical Sciences | 96 | 96 | 0 |
| g10-maths-stats.pdf | Mathematics and Statistics (1) | 10 | Humanities | 120 | 118 | 0 |
| g11-calculus.pdf | Calculus (1) | 11 | Mathematical Sciences | 160 | 152 | 0 |
| g11-geometry.pdf | Geometry (2) | 11 | Mathematical Sciences | 80 | 77 | 0 |
| g11-maths.pdf | Mathematics (2) | 11 | Experimental Sciences | 176 | 168 | 0 |
| g11-maths-stats.pdf | Mathematics and Statistics (2) | 11 | Humanities | 80 | 72 | 0 |
| g11-stats-prob.pdf | Statistics and Probability | 11 | Mathematical Sciences | 128 | 122 | 1 (minor) |
| **Band total** | **8 books** | **10–11** | **3 branches, kept separate** | **1,016** | **975** | **1** |

Branch shape of the band (do not merge):
- **Mathematical Sciences** carries 5 books across the two grades: the shared
  Mathematics (1), Geometry (1), Calculus (1), Geometry (2), Statistics and
  Probability. It alone gets: formal proof (Thales, Heron, De Morgan, log
  properties), circle theorems, transformations, sine/cosine rules, Bayes and
  total probability, inferential statistics, and the fullest logic/set algebra.
- **Experimental Sciences** carries the shared Mathematics (1) plus the single
  Mathematics (2): a compressed geometry import, intuitive limits, conditional
  probability without Bayes, descriptive statistics only. No derivative or
  integral appears in Grade 11 for ANY branch — in this band "calculus" means
  limits and continuity only.
- **Humanities** carries Mathematics and Statistics (1) and (2) only: a
  smaller algebra (quadratics, functions incl. floor/sign/step, operations),
  propositional logic with truth tables and reasoning, and statistics aimed at
  social data — centre/spread with computed standard deviation and IQR in
  G10; poverty line, price index, inflation and time series in G11. No
  trigonometry, geometry, sequences, probability, exponentials or limits.

---

## Band D — Grade 12 (all branches)

Band reader filing, 2026-11-06. Set context: `../set-verification.md` (22 files in hand for Iran maths; Band D is the five Grade 12 books).

## Method honesty (read this first)

- Every book below was read in full, page by page, from the publisher's text layer (`scratch/txt/<file>.txt`, split by PDF page), with the printed contents page as the map and chapter-by-chapter page outlines checked against the text.
- Identity (title, branch, code, ISBN, printing) was taken from the imprint page (PDF p. 2) in the text layer **and** confirmed on a page render (`pdftoppm`) — the Calculus imprint and the Mathematics and Statistics cover were inspected as images; ISBN digit order was read off the render, because the RTL text layer prints ISBN groups reversed.
- Printed page numbers below are the book's own printed pages. Each book's printed↔PDF offset is stated in its identity block; PDF page = printed page + offset.
- Errors: a item is filed as a **confirmed error** only if it was recomputed independently **and** the printed statement was verified on a page render. Anything seen only in the text layer is marked *unverified* and excluded from error counts. This matters: at least one alarming text-layer reading in this band (a reversed inequality in Discrete Mathematics, printed p. 51) proved on render to be an RTL extraction flip — the printed book is correct — and it is **not** filed as an error.
- All summaries are my own English paraphrase. No passages are transcribed; only short technical terms and formulas are quoted.
- **Branches are kept separate throughout.** Grade 12 in Iran is three different books/programmes: Mathematical Sciences (ریاضی و فیزیک, "Mathematics and Physics"), Experimental Sciences (علوم تجربی), and Humanities (ادبیات و علوم انسانی, with Islamic Sciences علوم و معارف اسلامی on the same cover). Content is never merged across branches; where two branches share a topic, each branch's treatment is filed under its own book.
- Publisher for all five: سازمان پژوهش و برنامه‌ریزی آموزشی (OERP — Organization for Educational Research and Planning), Ministry of Education; printed/distributed by شرکت چاپ و نشر کتاب‌های درسی ایران (Iran Textbook Printing and Publishing Company). All five imprints read: چاپ نهم ۱۴۰۵ — **ninth printing, year 1405** (school year 1405–1406). All five are pupil books; there are no teacher guides or workbooks in this band.

Band totals (all five books): **5 files, 606 PDF pages, 1 confirmed error** (details per book below).

---

## D1. Calculus (2) — حسابان (۲) — Mathematical Sciences branch

**File:** `pdfs/g12-calculus.pdf`

### 1. Identity

- Persian title as printed: حسابان (۲) — *Hesaban (2)*
- English translation: **Calculus (2)**
- Grade: 12 (پایۀ دوازدهم), second cycle of secondary school (دورۀ دوم متوسطه)
- **Branch: Mathematical Sciences — رشتۀ ریاضی و فیزیک (Mathematics and Physics)**
- Publisher: OERP (سازمان پژوهش و برنامه‌ریزی آموزشی), Ministry of Education
- Year / printing as printed: چاپ نهم ۱۴۰۵ — ninth printing, 1405
- ISBN as printed: **978-964-05-3112-9** (شابک ۹-۳۱۱۲-۰۵-۹۶۴-۹۷۸; digit order confirmed on the imprint render)
- Book code: **112214**
- PDF pages: **152**
- Printed ↔ PDF offset: **PDF = printed + 6** (printed p. 1 = PDF p. 7, the Chapter 1 opener; printed p. 144 = PDF p. 150; references, printed p. 145 = PDF p. 151; validator credits PDF p. 152)

### 2. Kind proof

Cover (PDF p. 1) prints «حسابان (۲) ـ رشتۀ ریاضی و فیزیک ـ پایۀ دوازدهم ـ دورۀ دوم متوسطه» and the imprint (PDF p. 2) names the book «حسابان (۲) ـ پایۀ دوازدهم دورۀ دوم متوسطه ـ ۱۱۲۲۱۴» — a Grade 12 pupil textbook for the Mathematics and Physics branch; activities / in-class work / exercises structure throughout, no answer section.

### 3. Contents (printed pages)

- Ch. 1 Function — p. 1
  - L1 Transformations of graphs of functions — p. 2
  - L2 Cubic functions, monotone functions, divisibility and division — p. 13
- Ch. 2 Trigonometry — p. 23
  - L1 Periodicity and tangent — p. 24
  - L2 Trigonometric equations — p. 35
- Ch. 3 Infinite limits — limits at infinity — p. 45
  - L1 Infinite limits — p. 46
  - L2 Limits at infinity — p. 59
- Ch. 4 The derivative — p. 71
  - L1 Introduction to the concept of the derivative — p. 72
  - L2 Differentiability and continuity — p. 84
  - L3 Average rate of change and instantaneous rate of change — p. 102
- Ch. 5 Applications of the derivative — p. 111
  - L1 Extrema of a function and increasing/decreasing functions — p. 112
  - L2 Direction of concavity of a graph and its inflection point — p. 127
  - L3 Sketching the graph of a function — p. 137
- References — p. 145

### 4. What is taught, chapter by chapter

**Ch. 1 — Function (pp. 1–22).** Graph transformations in full: vertical/horizontal shifts (pp. 2–5, worked on sin, cos, 2^x, log₂x graphs); vertical stretch/compression and reflection y = k·f(x), including negative k (pp. 6–8); horizontal scaling y = f(kx) with the reciprocal-width rule and its effect on domain and range (pp. 9–10); combined transformations as exercises (pp. 11–12). Polynomial functions defined; the cubic f(x) = x³ graphed from a table and used as the parent graph for shifted cubics (pp. 13–14). Increasing / decreasing / strictly increasing / strictly decreasing functions defined formally on a set (pp. 15–18), with piecewise examples. Polynomial divisibility: the division algorithm carried out in activities, the remainder/factor ideas used to show e.g. x⁴−16 divisible by x+2 (p. 19), and the identities x²−a², x³−a³, x⁴−a⁴ factorised via division by (x−a) (p. 20). Exercises pp. 21–22 (including invertibility of a shifted cubic).

**Ch. 2 — Trigonometry (pp. 23–44).** Periodicity of sin and cos recalled; period, maximum and minimum of y = a·sin bx + c and y = a·cos bx + c read from graphs and formulas, including recovering a formula from a given graph (pp. 24–29). The tangent function: variation of tan across the four quadrants (pp. 30–31), definition on its domain x ≠ kπ + π/2, and its graph (pp. 32–34). Trigonometric equations (pp. 35–44): general solution families for sin x = a (x = 2kπ + α or 2kπ + π − α), cos x = a (x = 2kπ ± α) and tan x = a (x = kπ + α), each developed graphically on the unit circle / graph intersection; equations reducible to quadratics or using identities (e.g. 2cos²x − 2cosx = 0 type, pp. 40–41); applied problems (blood-vessel resistance model in the chapter opener; a camera viewing-angle formula tan β = 2.5x / (x² + 1.5) type, p. 43). No double-angle formula section in this book — cos 2x identities appear only inside equation solving (p. 41).

**Ch. 3 — Infinite limits; limits at infinity (pp. 45–70).** Infinite one-sided limits defined informally-but-precisely ("values can be made larger than any given positive number") after numerical tables (pp. 46–49); eight numbered theorems on infinite limits stated (Theorems 1–5 on sums/products/quotients with infinite limits, pp. 51–55) and used computationally; vertical asymptotes defined and found for rational functions (pp. 56–58). Limits at infinity: definition, Theorem 6 (lim a/xⁿ = 0), infinite limits at infinity, Theorems 7–8 on end behaviour of polynomials (leading-term rule, pp. 62–66); horizontal asymptotes defined (p. 67) and identified from graphs and formulas. Proofs: the limit theorems are **stated and used, not proved** in this chapter; justification is graphical/numerical.

**Ch. 4 — The derivative (pp. 71–110).** Tangent line to a curve built as the limit of secant slopes, numerically first (secant slopes converging, pp. 73–77), then the derivative at a point defined by both limit forms, f′(a) = lim [f(a+h) − f(a)]/h = lim [f(x) − f(a)]/(x−a) (pp. 77–80); tangent-line equations as worked examples (f(x) = −x² + 10x, f′(2) = 6, f′(3) computed in full). Differentiability and continuity (pp. 84–101): one-sided derivatives, corner/cusp and vertical-tangent cases, the floor and absolute-value functions as non-differentiable examples; **theorem "differentiable at a ⇒ continuous at a" stated and proved** (p. 86). The derivative function (pp. 90–92). Rules, with proof status noted honestly by the book itself:
  - Power rule for n ∈ ℕ **proved** by the aⁿ − bⁿ factorisation (p. 93); extended to integer n (stated); derivative of 1/x as a corollary.
  - Derivatives of √x and ∛x (and √(ax+b)) **proved** by rationalisation (pp. 93–94); a footnote (p. 93) explicitly limits the radical scope of the book to these cases.
  - Sum, scalar-multiple, product and quotient rules **stated without proof** — the book says so in words ("in this book we do not prove them", p. 94).
  - Derivatives of sin x and cos x **proved** from the definition using the Grade 11 limits lim (sin h)/h = 1, lim (cos h − 1)/h = 0 (p. 95); derivative of tan x derived from the quotient rule: (tan x)′ = 1/cos²x = 1 + tan²x (p. 96).
  - **Chain rule stated** (no proof) with worked examples, e.g. h(x) = (x² + 3x + 1)⁷, y = sin²x (p. 96); differentiability on intervals (p. 97); second derivative defined and computed (p. 98).
  - Average vs instantaneous rate of change (pp. 102–110): average/instantaneous velocity, growth rate, fertility-rate graph reading, marginal-style sales applications — all as interpretation of the derivative, with worked numerical examples.

**Ch. 5 — Applications of the derivative (pp. 111–144).** Relative and absolute extrema defined (pp. 112–115); Fermat-type observation developed in activities — at an interior extremum where the derivative exists it is zero (p. 116); critical points; absolute extrema on a closed interval found by the endpoints-and-critical-points method (worked: |x² − 1| on [−2, 2], p. 118; open-box volume on [0, 4] with V′(x) = 12x² − 92x + 120 = 4(3x − 5)(x − 6), giving the cut x = 5/3 in, p. 119 — recomputed and correct). Sign of f′ and monotonicity (pp. 120–121); **first derivative test stated** (p. 123) with sign-table worked examples. Concavity and the second derivative (pp. 127–136): concavity defined via tangent position / sign of f″, inflection points defined, with the warning worked through that f″(c) = 0 is not sufficient (f(x) = x⁴ at 0, p. 132); worked concavity/inflection examples including cube-root-type functions (pp. 133–134). Full curve sketching (pp. 137–144): behaviour tables combining f, f′, f″, asymptotes and intercepts; worked sketches of cubics and of homographic (linear-fractional) functions f(x) = (ax + b)/(cx + d), whose asymptotes and concavity on each branch are analysed (pp. 141–143); final exercise set p. 144. A second worked optimisation: largest cylinder inscribed in a sphere of radius R, giving h = 2R/√3, r² = 2R²/3 (p. 119 — recomputed and correct).

**Depth ceilings (Calculus (2)).** No integral of any kind — the word "integral" occurs only inside bibliography titles on the references page (p. 145): entries 1 (Stewart's *Calculus*), 7 and 8, all book titles; no integration is taught anywhere. No differential equations. No L'Hôpital's rule, no Taylor series, no sequences/series. No derivatives of exponential or logarithmic functions (log/exp graphs are used in Ch. 1 only as pictures to transform). Limit theorems are stated, not proved (no ε–δ anywhere). This is a differential-calculus-only final year.

### 5. Honest negatives — Calculus (2)

- No integration, no area/volume-by-integration, no differential equations, no antiderivatives.
- No exponential/logarithmic differentiation; no inverse-trig functions or their derivatives.
- No formal ε–δ limits; limit theorems unproved (the book is transparent about which derivative rules it does not prove, p. 94).
- No optimisation chapter as such — optimisation appears only inside worked examples (box, cylinder) in Ch. 5 L1; there is no separate "optimisation" lesson (contrast the Experimental book, D4, which has one).
- No double-angle formula lesson (contrast D4).
- No answer key (see §7).

### 6. Confirmed book errors — Calculus (2)

**None filed.** Worked computations spot-recomputed across all five chapters (secant/derivative computations pp. 78–80; power-rule proof p. 93; tan derivative p. 96; box and inscribed-cylinder optimisations p. 119; first-derivative-test table p. 124) all check out. *Unverified (excluded from counts):* none carried — apparent text-layer garbles on pp. 119 and 124 resolve to correct mathematics once fractions/exponents are read in place.

### 7. Answer keys — Calculus (2)

**None.** The book ends with references (p. 145) and the validator-teachers credit page (PDF p. 152). Exercises, in-class work and activities carry no printed answers.

### 8. Held-copy defects — Calculus (2)

None. File complete: 152 PDF pages, matching the record; printed p. 70 (PDF p. 76) is a blank verso before Ch. 4 — normal print layout, not a defect.

---

## D2. Discrete Mathematics — ریاضیات گسسته — Mathematical Sciences branch

**File:** `pdfs/g12-discrete.pdf`

### 1. Identity

- Persian title as printed: ریاضیات گسسته
- English translation: **Discrete Mathematics**
- Grade: 12 (پایۀ دوازدهم), second cycle of secondary school
- **Branch: Mathematical Sciences — رشتۀ ریاضی و فیزیک (Mathematics and Physics)**
- Publisher: OERP, Ministry of Education
- Year / printing as printed: چاپ نهم ۱۴۰۵ — ninth printing, 1405
- ISBN as printed: **978-964-05-3111-2**
- Book code: **112215**
- PDF pages: **94**
- Printed ↔ PDF offset: **PDF = printed + 8** (printed p. 1 = PDF p. 9, Ch. 1 opener; printed p. 2 = PDF p. 10, confirmed by the footer "Chapter One: Introduction to Number Theory — 2"; references printed p. 85 = PDF p. 93; credits PDF p. 94)

### 2. Kind proof

Cover (PDF p. 1) prints «ریاضیات گسسته ـ رشتۀ ریاضی و فیزیک ـ پایۀ دوازدهم ـ دورۀ دوم متوسطه» and the imprint (PDF p. 2) names the book «ریاضیات گسسته ـ پایۀ دوازدهم دورۀ دوم متوسطه ـ ۱۱۲۲۱۵» — a Grade 12 pupil textbook for the Mathematics and Physics branch.

### 3. Contents (printed pages)

- Ch. 1 Introduction to number theory — p. 1
  - L1 Mathematical reasoning — p. 2
  - L2 Divisibility in the integers — p. 9
  - L3 Congruence in the integers and applications — p. 18
- Ch. 2 Graphs and modelling — p. 31
  - L1 Introduction to graphs — p. 32
  - L2 Modelling with graphs — p. 43
- Ch. 3 Combinatorics (counting) — p. 55
  - L1 Topics in combinatorics — p. 56
  - L2 Methods for counting — p. 73
- References — p. 85

### 4. What is taught, chapter by chapter

**Ch. 1 L1 — Mathematical reasoning (pp. 2–8).** Proof and disproof as working methods: disproof by counterexample, built on the two test statements "the sum of two primes…" style claims and the Fermat number F₅ = 2³² + 1 = 4,294,967,297 = 641 × 6,700,417 shown composite (p. 2 — recomputed: 641 × 6,700,417 = 4,294,967,297, correct); proof by considering all cases (parity case-split proving n² − 5n + 7 is odd, p. 4); direct proof; proof by contradiction (برهان خلف, used repeatedly in the chapter); two-way (if-and-only-if) statements worked both directions (pp. 7–8). A footnote (p. 3) warns that exam problems must stay at the book's level. **Notably absent: mathematical induction is never taught** (the word does not occur in the book).

**Ch. 1 L2 — Divisibility in the integers (pp. 9–17).** The divisibility relation a | b defined; its basic properties stated **and proved** one by one (transitivity, linear combinations, a | b ⇒ aⁿ | bⁿ, etc., pp. 10–12). gcd and lcm introduced from the divisibility relation (p. 13), with elementary facts proved (e.g. p prime, p ∤ a ⇒ gcd(p, a) = 1, p. 14). The **division theorem** (quotient and remainder) used to partition ℤ into residue classes (pp. 15–16) and to prove remainder facts. No Euclidean algorithm and no Bézout identity — gcd work stays at the level of definitions and small arguments.

**Ch. 1 L3 — Congruence in the integers and applications (pp. 18–30).** Congruence a ≡ b (mod m) defined via equal remainders / m | a − b; the arithmetic properties of congruences listed, with the cancellation law's failure flagged by counterexample request and the corrected cancellation rule (divide through by gcd(c, m)) **stated without proof** ("we accept this property without proof", p. 22). Divisibility tests derived from congruences, including the digit-sum rule mod 9 worked in full (p. 23). Calendar / day-of-the-week computation by congruences (p. 24). Linear congruences and their general solutions (p. 25); **Diophantine ("Siyāle") equations** ax + by = c solved by conversion to a congruence, with the general integer solution and non-negative-solution extraction worked in applied problems (money/weights problems, pp. 26–29); exercise set p. 30 (including solving congruences such as 423x ≡ 79 (mod 11) types — in the book's notation, modulus as superscript).

**Ch. 2 L1 — Introduction to graphs (pp. 32–42).** Königsberg bridges as the entry point, with Euler's 18th-century argument retold and Sheikh Baha'i's three-houses/three-wells problem (the K₃,₃ configuration, unnamed as such) as history (pp. 32–33). Graph, vertex, edge, loop, multiple edges; order and size; degree of a vertex, odd/even vertices, Δ(G) and δ(G) (pp. 34–37); complement graph Ḡ and degree in the complement; complete graphs K_p (edge count in exercises, e.g. K_p with 36 edges ⇒ p = 9); r-regular graphs; paths and cycles (the cycle C₇ is used by name); connected vs disconnected graphs (pp. 38–39). **Handshaking lemma (sum of degrees = 2|E|) proved, with its corollary "the number of odd vertices is even" proved from it** (p. 40). Exercises pp. 41–42.

**Ch. 2 L2 — Modelling with graphs (pp. 43–54).** One concept, developed deeply: **dominating sets**. Dominating set, minimal and minimum dominating sets, the domination number γ(G), motivated by placing ATMs / radio stations / guards so every vertex is covered or adjacent to a covered vertex (pp. 43–48). The lower bound **γ(G) ≥ ⌈n / (Δ + 1)⌉ stated and justified** (printed p. 49, verified on render: the bound is printed as a lower bound, with ⌈n/(Δ+1)⌉ ≤ |D| for every dominating set D); worked determinations of γ for pictured graphs by bound-plus-construction arguments (γ = 2 for the Fig. 10 graph, p. 49; γ = 4 for the 14-vertex Fig. 13 graph via the bound ⌈14/6⌉ = 3 improved by case analysis to 4, and for Fig. 14, p. 51 — all verified on renders, logic correct). Exercises pp. 52–54 (including γ(G) = 1 characterisation questions and domination numbers of P and C graphs).

**Ch. 3 L1 — Topics in combinatorics (pp. 56–72).** Review-and-complete of the addition/multiplication principles, permutations and combinations from earlier years; permutations with adjacent-block conditions; **permutations with repetition** (multiset permutations) with the division argument (pp. 58–60); distributing identical objects / non-negative integer solutions of x₁ + x₂ + x₃ = 7 counted by stars-and-bars reasoning through the flower-selection model (pp. 60–61); then a long block on **Latin squares** (pp. 62–71): definition, construction, permuting symbols, **orthogonal Latin squares**, checking orthogonality, an application to work scheduling, a construction of two orthogonal 5×5 Latin squares, and a reading note on Euler's 1782 conjecture for orders n = 4k + 2. This Latin-square block (≈10 pages) is the book's most distinctive content.

**Ch. 3 L2 — Methods for counting (pp. 73–84).** **Inclusion–exclusion** for two and three sets, with divisibility-counting applications (numbers divisible by 3 or 4 counted via lcm, pp. 73–76); counting functions A → B (n^m), injective functions, and **surjective (onto) functions by inclusion–exclusion** — worked: onto maps from a 4-set to a 3-set = 3⁴ − 3·2⁴ + 3·1⁴ = 81 − 48 + 3 = 36 (p. 78, recomputed correct). **Pigeonhole principle and its generalised form** (kn + 1 objects in n boxes ⇒ some box has ≥ k + 1) with applications: same-birth-month guarantees (p. 82), and closing pigeonhole proofs in the exercises (13 points in a 6×8 rectangle ⇒ two at distance < √8; lattice-point midpoint arguments, pp. 83–84 and PDF p. 92 continuation).

**Depth ceilings (Discrete).** Number theory stops at congruences and linear Diophantine equations: no primitive roots, no Fermat/Euler theorems, no CRT named, no Euclidean algorithm/Bézout. Graph theory is two topics only — basic vocabulary plus domination: **no trees, no Eulerian trails as a topic (Euler appears only as history), no Hamiltonian cycles, no bipartite graphs, no planar graphs, no graph colouring**. Combinatorics has no recurrence relations, no Fibonacci, no generating functions, no binomial-theorem chapter (binomial coefficients are used as combination notation only). No probability in this book (one passing mention).

### 5. Honest negatives — Discrete Mathematics

- No mathematical induction anywhere — proof teaching is counterexample / cases / direct / contradiction only.
- No trees, spanning trees, Eulerian/Hamiltonian theory, colouring, planarity, bipartite graphs, graph algorithms, adjacency matrices.
- No Euclidean algorithm, no Bézout identity, no Chinese remainder theorem, no Fermat's little theorem.
- No recurrence relations or generating functions; no probability chapter.
- No answer key (see §7).

### 6. Confirmed book errors — Discrete Mathematics

**None filed.** Recomputed/verified correct: F₅ factorisation (p. 2); handshaking corollary proof (p. 40); onto-function count 36 (p. 78); domination bound and both worked domination numbers (pp. 49, 51 — **render-verified**, see method note: the text layer reverses the p. 51 inequality, the printed page reads γ(G) ≥ 3 from the bound, then γ(G) = 4; this extraction artifact is explicitly **not** an error and is excluded).

### 7. Answer keys — Discrete Mathematics

**None.** The book ends with references (p. 85) and the validator-teachers credit page (PDF p. 94).

### 8. Held-copy defects — Discrete Mathematics

None. File complete: 94 PDF pages, matching the record.

---

## D3. Geometry (3) — هندسه (۳) — Mathematical Sciences branch

**File:** `pdfs/g12-geometry.pdf`

### 1. Identity

- Persian title as printed: هندسه (۳)
- English translation: **Geometry (3)**
- Grade: 12 (پایۀ دوازدهم), second cycle of secondary school
- **Branch: Mathematical Sciences — رشتۀ ریاضی و فیزیک (Mathematics and Physics)**
- Publisher: OERP, Ministry of Education
- Year / printing as printed: چاپ نهم ۱۴۰۵ — ninth printing, 1405
- ISBN as printed: **978-964-05-3113-6**
- Book code: **112213**
- PDF pages: **88**
- Printed ↔ PDF offset: **zero — printed page = PDF page throughout.** This book's printed pagination counts the front matter: contents is printed p. 5, Ch. 1 opens on printed p. 9 (= PDF p. 9, footer "9" confirmed), Ch. 1 L1 on p. 10, references on p. 87 (= PDF p. 87), credits PDF p. 88.

### 2. Kind proof

Cover (PDF p. 1) prints «هندسه (۳) ـ رشتۀ ریاضی و فیزیک ـ پایۀ دوازدهم ـ دورۀ دوم متوسطه» and the imprint (PDF p. 2) names the book «هندسه (۳) ـ پایۀ دوازدهم دورۀ دوم متوسطه ـ ۱۱۲۲۱۳» — a Grade 12 pupil textbook for the Mathematics and Physics branch. Despite the title, roughly two-thirds of the book is analytic geometry / linear algebra / vectors, not synthetic geometry.

### 3. Contents (printed pages)

- Ch. 1 Matrices and applications — p. 9
  - L1 Matrices and operations on matrices — p. 10
  - L2 Inverse of a matrix and determinant — p. 22
- Ch. 2 Introduction to conic sections — p. 33
  - L1 Introduction to conic sections and locus — p. 34
  - L2 The circle — p. 40
  - L3 Ellipse and parabola — p. 47
- Ch. 3 Vectors — p. 61
  - L1 Introduction to the space ℝ³ — p. 62
  - L2 Dot product and cross product of vectors — p. 77
- References — p. 87

### 4. What is taught, chapter by chapter

**Ch. 1 L1 — Matrices and operations (pp. 10–21).** Matrix as a data table (league-table opening), entries and double-index notation a_ij, order m×n (pp. 10–11); special matrices: square, row, column, diagonal, scalar, identity, zero (pp. 12–13); equality of matrices; addition, subtraction, scalar multiplication with their algebraic properties **listed and partly verified in activities, with one property assigned to prove in general** (pp. 14–17); row-by-column multiplication, matrix multiplication, non-commutativity and failure of the zero-product property explored in class work (pp. 17–19); properties of multiplication (distributivity etc.) stated (p. 20); exercises including powers of a 3×3 matrix and finding parameters making AB diagonal (p. 21).

**Ch. 1 L2 — Inverse and determinant (pp. 22–31).** Inverse via the identity matrix, motivated by reciprocals; the 2×2 inverse formula A⁻¹ = (1/(ad − bc)) · [[d, −b], [−c, a]] given and used (p. 23); 2×2 linear systems written as AX = B and solved by the inverse, with the geometric trichotomy (unique / no / infinitely many solutions ↔ intersecting / parallel / coincident lines) treated in full (pp. 24–26). Determinant defined for square matrices (p. 27); 2×2 determinant ad − bc computed in examples (e.g. |[[−2, 3], [4, 5]]| = −10 − 12 = −22, p. 28 — recomputed correct; a trigonometric determinant reducing to sin²α + cos²α); **Sarrus's rule for 3×3 determinants** (p. 29), with first-row expansion also referenced in exercises (p. 30); exercises relating |A⁻¹| and |A| and computing (2A⁻¹ − 3B⁻¹)-type expressions (p. 31). Depth ceiling: inverses and determinants are 2×2 in the lesson body (3×3 only for the determinant via Sarrus); no general n×n theory, no Cramer's rule named, no row operations / Gaussian elimination, no eigenvalues.

**Ch. 2 L1 — Conic sections and locus (pp. 34–39).** The double cone cut by a plane: circle / point / line degenerate cases and the three curves named; **the hyperbola is named and then explicitly excluded** — the book says in words that it will not define the hyperbola precisely or study its properties (p. 35). Locus (مکان هندسی) as a concept: perpendicular bisector and angle bisector recalled **with proofs from Geometry (1)**, circle as a locus proved both directions (pp. 36–38); a catalogue of standard loci (points equidistant from two intersecting lines, centres of circles tangent to a line at a fixed point, etc.) in class work (pp. 38–39).

**Ch. 2 L2 — The circle (pp. 40–46).** Standard equation (x − h)² + (y − k)² = r² from the locus definition; the expanded form x² + y² + ax + by + c = 0 with the exact trichotomy **a² + b² > 4c ⇔ real circle; = 4c ⇔ a single point; < 4c ⇔ no points** (p. 42 — condition recomputed: centre (−a/2, −b/2), r² = (a² + b²)/4 − c, correct); circles tangent to a line (radius = distance from centre, worked p. 43); internally tangent circles worked (p. 44); relative position of a line and a circle by substitution (p. 45); exercises p. 46.

**Ch. 2 L3 — Ellipse and parabola (pp. 47–60).** Ellipse by the string construction: foci F, F′, major axis 2a, minor axis 2b, centre, and the relation **b² + c² = a² proved from the construction** (pp. 47–48); drawing an approximate ellipse for given a and c, and **eccentricity defined as the ratio c/a**, with its limiting behaviour (c/a → 1 flattens to a segment, c/a = 0 gives a circle) (p. 49); the reflection property of the ellipse motivated via the tangent-line minimisation (p. 50). **Ceiling: the ellipse is treated geometrically — no Cartesian standard equation x²/a² + y²/b² = 1 is stated or derived anywhere in the lesson (pp. 47–54 checked).** Parabola (pp. 50–56): defined as a locus (equidistant from focus F and directrix d), traced with the set-square-and-string construction; the equation **derived** for focus (a, 0), directrix x = −a, giving y² = 4ax, and the four orientations tabulated (focus, directrix, axis, opening) (pp. 52–53); translated parabolas with vertex (h, k) (p. 54); worked: y = x² + 3x + 5 → (x + 3/2)² = y − 11/4, vertex (−3/2, 11/4), a = 1/4, focus (−3/2, 3), directrix y = 5/2 (p. 55 — recomputed correct); y² − 2y + 8x + 9 = 0 → (y − 1)² = −8(x + 1), vertex (−1, 1), focus (−3, 1), directrix x = 1, latus-rectum endpoints (−3, 5), (−3, −3) (pp. 55–56 — recomputed correct); the reflection property of the parabola and its applications (headlights) (p. 56). Exercises pp. 57–59 mix ellipse geometry proofs, parabola vertex/focus work and locus constructions.

**Ch. 3 L1 — The space ℝ³ (pp. 62–76).** Points as ordered triples; plotting points; the coordinate planes and simple surfaces/regions described by equations and inequalities in ℝ² and ℝ³ (x = 3, z = −3, regions between planes) (pp. 62–68); distance from the origin and the **distance formula between two points in ℝ³ derived by two applications of Pythagoras** (p. 66). Vectors in ℝ² recalled (directed segments, components, addition, scalar multiplication), then vectors in ℝ³ with the same componentwise operations and their algebraic properties listed (pp. 69–75); resultant-force modelling (aircraft crab landing in crosswind) as the motivating application (pp. 71–72). Ceiling: no equation of a line or plane in space is developed (planes appear only as coordinate planes / x = const. type surfaces), no midpoint/section formula section.

**Ch. 3 L2 — Dot and cross products (pp. 77–86).** Dot product motivated by finding the angle between two vectors via the cosine rule; a·b = a₁b₁ + a₂b₂ (+ a₃b₃ in ℝ³) defined, with a·b = |a||b|cos θ then established (p. 78); worked: angle between a = (2, −1, 2) and b = (1, −1, 0): a·b = 3, |a| = 3, |b| = √2, cos θ = 1/√2, θ = π/4 (p. 78 — recomputed correct). Properties of the dot product listed, commutativity **proved** (p. 79); orthogonal projection of one vector on another, formula a′ = ((a·b)/|b|²) b (p. 80). Cross product defined by the determinant-style formula (p. 81); **|a × b| = |a||b| sin θ proved algebraically** through |a × b|² = |a|²|b|² − (a·b)², and identified with the area of the parallelogram (p. 81); i × j = k, j × i = −k computed from the definition (p. 81); properties listed, orthogonality of a × b to both factors **proved**, anti-commutativity, a × a = 0, distributivity, parallel ⇔ a × b = 0 **proved** (p. 82). Scalar triple product as volume: **volume of the parallelepiped = |a · (b × c)|**, also as a 3×3 determinant (p. 83); worked: a = (1, 1, 0), b = (0, 1, 1), c = (1, 0, 1) ⇒ b × c = (1, 1, −1), V = |1 + 1 + 0| = 2 (p. 83 — recomputed correct); coplanarity ⇔ volume zero (p. 84). Closing reading section (pp. 85–86): vector proofs of classical geometry results, including a full proof that **the three altitudes of a triangle are concurrent** (p. 86).

### 5. Honest negatives — Geometry (3)

- The hyperbola is explicitly **not** taught (named p. 35, study declined in the book's own words).
- The ellipse has **no Cartesian equation** in this book — geometry only; no tangent-to-ellipse/parabola equations.
- No n×n matrix theory, no Gaussian elimination / row operations, no Cramer's rule by name, no eigenvalues/eigenvectors, no linear transformations.
- No lines/planes in 3D as equations, no angle between planes, no distance point-to-plane.
- No synthetic Euclidean geometry chapters (no congruence/similarity/circle theorems) — the "Geometry" title carries matrices, conics and vectors.
- No answer key (see §7).

### 6. Confirmed book errors — Geometry (3)

**None filed.** Recomputed/verified correct: 2×2 determinant −22 (p. 28); circle-existence condition a² + b² ≷ 4c (p. 42); both parabola standard-form conversions and foci/directrices (pp. 55–56); dot-product angle π/4 (p. 78); triple-product volume 2 (p. 83).

### 7. Answer keys — Geometry (3)

**None.** The book ends with references (p. 87) and the validator-teachers credit page (PDF p. 88).

### 8. Held-copy defects — Geometry (3)

None. File complete: 88 PDF pages, matching the record. Printed pp. 8, 32 and 60 are blank versos before chapters — normal print layout, not defects.

---

## D4. Mathematics (3) — ریاضی (۳) — Experimental Sciences branch

**File:** `pdfs/g12-maths.pdf`

### 1. Identity

- Persian title as printed: ریاضی (۳)
- English translation: **Mathematics (3)**
- Grade: 12 (پایۀ دوازدهم), second cycle of secondary school
- **Branch: Experimental Sciences — رشتۀ علوم تجربی**
- Publisher: OERP, Ministry of Education
- Year / printing as printed: چاپ نهم ۱۴۰۵ — ninth printing, 1405
- ISBN as printed: **978-964-05-3117-4**
- Book code: **112211**
- PDF pages: **160**
- Printed ↔ PDF offset: **PDF = printed + 8** (printed p. 1 = PDF p. 9, Ch. 1 opener; printed p. 144 = PDF p. 152; references begin printed p. 149 = PDF p. 157 and run to printed p. 150+; credits PDF p. 160)

### 2. Kind proof

Cover (PDF p. 1) prints «ریاضی (۳) ـ رشتۀ علوم تجربی ـ پایۀ دوازدهم ـ دورۀ دوم متوسطه» and the imprint (PDF p. 2) names the book «ریاضی (۳) ـ پایۀ دوازدهم دورۀ دوم متوسطه ـ ۱۱۲۲۱۱» — a Grade 12 pupil textbook for the Experimental Sciences branch. This is a **different book** from D1/D3: same author team and much shared wording with Calculus (2), but a reduced, re-ordered programme (see the branch notes in §5).

### 3. Contents (printed pages)

- Ch. 1 Function — p. 1
  - L1 Polynomial functions — increasing and decreasing functions — p. 2
  - L2 Composition of functions — p. 11
  - L3 Inverse function — p. 24
- Ch. 2 Trigonometry — p. 31
  - L1 Periodicity and tangent — p. 32
  - L2 Trigonometric equations — p. 42
- Ch. 3 Infinite limit and limit at infinity — p. 49
  - L1 Infinite limit — p. 50
  - L2 Limit at infinity — p. 58
- Ch. 4 Derivative — p. 65
  - L1 Introduction to the concept of the derivative — p. 66
  - L2 Differentiability and continuity — p. 77
  - L3 Rate of change — p. 93
- Ch. 5 Application of the derivative — p. 101
  - L1 Extrema of a function — p. 102
  - L2 Optimisation — p. 113
- Ch. 6 Geometry — p. 121
  - L1 Visual thinking and introduction to conic sections — p. 122
  - L2 The circle — p. 134
- Ch. 7 Probability — p. 143
  - (single lesson) The law of total probability — p. 144

### 4. What is taught, chapter by chapter

**Ch. 1 — Function (pp. 1–30).** Polynomial functions (linear, quadratic recalled; the cubic f(x) = x³ examined as the new case, pp. 2–5); increasing / decreasing / strictly monotone functions defined on an interval (pp. 6–10). **Composition of functions** (pp. 11–23): fog defined with the range/domain compatibility condition, computed from formulas, tables, graphs and ordered pairs; the lesson also carries the graph-transformation review (y = k·f(x), y = f(kx) with the 1/k width rule) as a "recall" block (pp. 15–21). **Inverse functions** (pp. 24–30): one-to-one functions, inverse by swapping pairs / reflecting in y = x, verifying f∘f⁻¹ = identity (worked: f(x) = 3x − 4, g(x) = (x + 4)/3, p. 26 — correct), finding f⁻¹ formulas, and restricting the domain of a non-injective function (h(x) = x² − 2x + 2) to make it invertible (p. 28). Neither composition nor inverse functions appear in the Mathematical Sciences Calculus (2) (D1) — they are this branch's Ch. 1 instead of D1's divisibility material (polynomial division survives only as a limit-computation tool, p. 51).

**Ch. 2 — Trigonometry (pp. 31–48).** Periodicity and tangent: essentially the D1 treatment (period/max/min of a·sin bx + c and a·cos bx + c, tangent's variation and graph, pp. 32–41). Trigonometric equations (pp. 42–48): **this branch adds the double-angle formulas as an explicit first block** — sin 2α = 2 sin α cos α; cos 2α = cos²α − sin²α = 2cos²α − 1 = 1 − 2sin²α (p. 43), with exact values (cos 15°, sin 15°) derived; then general solutions of sin x = a and cos x = a as in D1; worked: 2 sin 3x − √2 = 0 type giving x = 2kπ/3 + π/12 families (p. 47); worked: cos x (2 cos x − 9) = 5 → 2cos²x − 9cosx − 5 = 0 → cos x = −1/2 (root cos x = 5 rejected) → x = 2kπ ± 2π/3 (p. 48 — recomputed correct).

**Ch. 3 — Limits (pp. 49–64).** A compressed version of D1 Ch. 3: infinite limits defined (p. 55) after a limits review that uses polynomial division to remove 0/0 forms (pp. 50–53); one-sided neighbourhoods defined (p. 54); limits at infinity with the single stated theorem lim 1/xⁿ = 0 (p. 60), infinite limits at infinity, and end-behaviour of polynomials by the leading term (p. 63). **Ceiling vs D1:** no numbered theorem suite for infinite-limit algebra, and vertical/horizontal asymptotes are **not** developed as named concepts in this branch's limit chapter.

**Ch. 4 — Derivative (pp. 65–100).** Same arc as D1 Ch. 4, compressed: tangent line as limit of secants, derivative at a point in both limit forms, f(x) = −x² + 10x worked identically (f′(2) = 6) (pp. 66–76). Differentiability and continuity (pp. 77–92): one-sided derivatives, the theorem differentiable ⇒ continuous, the derivative function, and the rule list items 1–7 (pp. 85–88) — constant rule; power rule for n ∈ ℕ **proved** by the aⁿ − bⁿ factorisation (p. 85) and extended to integer n; derivatives of √x, √(ax + b) and ∛x **proved** by rationalisation, with the same footnote limiting radical scope to these (p. 86); sum/scalar/product/quotient rules **stated without proof** (p. 87); **chain rule stated** with the same (x² + 3x + 1)⁷ worked example and a quotient-inside-power example (p. 88); differentiability on intervals; second derivative (p. 90). **Branch ceiling: no derivatives of sin/cos/tan are given in this book** — the trigonometric-derivative block of D1 (its p. 95–96) is absent. Rate of change (pp. 93–100): average/instantaneous velocity, growth rate, fertility rate — same applications as D1.

**Ch. 5 — Application of the derivative (pp. 101–120).** Monotonicity test (sign of f′) stated (p. 104); relative extrema defined, critical points, first-derivative-test reasoning, absolute extrema defined and found on closed intervals (pp. 105–112). **Optimisation as its own lesson** (pp. 113–120) — a lesson D1 does not have: among rectangles of fixed perimeter the square maximises area (worked in full, pp. 114–115); the open-box problem from a 30 cm square sheet (p. 115); a cost-minimisation with C(x) = 200x² + 1800/x-type structure solved via its critical point (p. 116); a boat-to-shore least-time (refraction-type) problem (p. 117); the 1-litre cylindrical can of minimum material as class work (p. 118); fencing a 10,000 m² field with differently priced sides in the exercises (p. 120). **Ceiling vs D1:** no concavity, no second-derivative test, no inflection points, no systematic curve sketching — D1's whole L2–L3 of Ch. 5 is absent here.

**Ch. 6 — Geometry (pp. 121–142).** Visual thinking: solids of revolution and their volumes in activities, cross-sections of solids (section of a sphere is a circle; largest section through the centre) (pp. 122–125); conic sections from rotating a generator line around an axis and cutting the cone (pp. 126–127); the **ellipse treated geometrically exactly as in D3**: string construction, foci, major/minor axes, the a–b–c relation, and **eccentricity** (خروج از مرکز) (pp. 128–131) — again with no Cartesian ellipse equation; the **parabola appears only as the graph of a quadratic y = ax² + bx + c**, with the focus introduced in a reading box (p. 133) — no focus–directrix derivation, no y² = 4ax. The circle lesson (pp. 134–142): standard and expanded equations, relative positions of line and circle, and of **two circles** (distance of centres vs radii — the two-circle table is in this book, pp. 140–141), with worked two-circle position determinations.

**Ch. 7 — Probability (pp. 143–148).** A single short lesson: a 10-point recall list of earlier probability (random experiment, sample space S, events, P(A) = n(A)/n(S), complement, union/intersection rules, conditional probability P(A|B) = P(A ∩ B)/P(B), independence ⟺ P(A ∩ B) = P(A)P(B)) (p. 144); **partition of S and the law of total probability P(B) = Σ P(Aᵢ)·P(B|Aᵢ) stated and derived for the partitioned case** (pp. 145–146; a footnote says the partition concept itself is not examinable); worked examples with tree diagrams: a disease-prevalence computation (P(disease) = ½·0.08 + ½·0.03 type, p. 146); four-box marble problem (p. 147); a contest problem giving P(B) = ½·(90/100) + (1/6)·(60/100) + (1/3)·(85/100) = 5/6 (p. 147 — recomputed: 0.45 + 0.10 + 0.2833… = 0.8333… = 5/6, correct); a transfer-between-boxes problem (p. 148). **Bayes's theorem is not named and no inverse-probability computation is set**, although the total-probability machinery is fully present.

### 5. Honest negatives — Mathematics (3), Experimental branch

- No integrals, no differential equations (as in every book in this band).
- No trigonometric derivatives, no concavity / inflection / curve-sketching, no asymptote theory in the limit chapter — all present in the Mathematical Sciences book (D1) and all absent here. The branches must not be conflated.
- No ellipse equation, no parabola focus–directrix theory (reading box only), no hyperbola.
- Probability is one 6-page lesson (total probability only): no distributions, no expected value, no variance, no binomial/normal models.
- No answer key (see §7).

### 6. Confirmed book errors — Mathematics (3)

**None filed.** Recomputed/verified correct: inverse-pair verification (p. 26); trig-equation quadratic (p. 48); power-rule proof (p. 85); total-probability contest computation = 5/6 (p. 147).

### 7. Answer keys — Mathematics (3)

**None.** The book ends with references (pp. 149–151 — Persian list pp. 149–150, English list ending on printed p. 151; PDF pp. 157–159) and the validator-teachers credit page (PDF p. 160).

### 8. Held-copy defects — Mathematics (3)

None. File complete: 160 PDF pages, matching the record.

---

## D5. Mathematics and Statistics (3) — ریاضی و آمار (۳) — Humanities branch

**File:** `pdfs/g12-maths-stats.pdf`

### 1. Identity

- Persian title as printed: ریاضی و آمار (۳)
- English translation: **Mathematics and Statistics (3)**
- Grade: 12 (پایۀ دوازدهم), second cycle of secondary school
- **Branch: Humanities — رشته‌های ادبیات و علوم انسانی ـ علوم و معارف اسلامی** (Literature and Humanities **and** Islamic Sciences — both branch names print on the cover; one book serves both)
- Publisher: OERP, Ministry of Education
- Year / printing as printed: چاپ نهم ۱۴۰۵ — ninth printing, 1405
- ISBN as printed: **978-964-05-3097-9**
- Book code: **112212**
- PDF pages: **112**
- Printed ↔ PDF offset: **PDF = printed + 6** (printed p. 1 = PDF p. 7, Ch. 1 opener; printed p. 104 = PDF p. 110; references printed p. 105 = PDF p. 111; credits PDF p. 112)

### 2. Kind proof

Cover (PDF p. 1, inspected as a render) prints «ریاضی و آمار (۳) ـ رشته‌های ادبیات و علوم انسانی ـ علوم و معارف اسلامی ـ پایۀ دوازدهم ـ دورۀ دوم متوسطه» and the imprint (PDF p. 2) names the book «ریاضی و آمار (۳) ـ پایۀ دوازدهم دورۀ دوم متوسطه ـ ۱۱۲۲۱۲» — a Grade 12 pupil textbook for the Humanities branches. Structurally unrelated to D1–D4: no functions-and-calculus programme at all (see §5).

### 3. Contents (printed pages)

- Ch. 1 Statistics and probability — p. 1
  - L1 Counting — p. 2
  - L2 Probability — p. 12
  - L3 The statistics cycle in problem solving — p. 28
- Ch. 2 Linear patterns — p. 45
  - L1 Modelling and sequences — p. 46
  - L2 Arithmetic sequences — p. 61
- Ch. 3 Non-linear patterns — p. 73
  - L1 Geometric sequences — p. 74
  - L2 nth root and rational powers — p. 86
  - L3 The exponential function — p. 95
- References — p. 105

### 4. What is taught, chapter by chapter

**Ch. 1 L1 — Counting (pp. 2–11).** Addition and multiplication principles through everyday choice problems; factorial notation; permutations of n distinct objects **with the count n! proved by the multiplication principle** (p. 6); permutations P(n, r) = n!/(n − r)! **derived** (p. 8); combinations introduced by listing (the 3-subsets of {1, 2, 4, 6} are listed and counted as 4 = C(4, 3), p. 9) and C(n, r) used; forming a 6-person volleyball team from 9 as the standard combination example (p. 10); letter-arrangement problems on the word «ولایت» (p. 11). Ceiling: no permutations with repetition, no circular permutations, no binomial theorem.

**Ch. 1 L2 — Probability (pp. 12–27).** Deterministic vs random experiments; sample space; events as sets, with union/intersection and mutually exclusive (ناسازگار) events handled set-theoretically (pp. 12–19); the classical definition P(A) = n(A)/n(S) for equiprobable outcomes, counts obtained by the counting principles of L1 (worked: coin-and-die space of 12, P(die even) = 6/12 = 1/2, p. 20); the birthday-style computation P(all 5 taxi passengers born in Farvardin) = 1/12⁵ (pp. 20–21); two-dice sum distribution tabulated/bar-charted (p. 21); **complement rule P(A′) = 1 − P(A) stated and proved from the definition** (p. 22); "at least" problems by complement and by cases (red-shirt counting, p. 24). Ceiling: **classical finite probability only — no conditional probability (the term never occurs), no independence, no total probability** (contrast D4 Ch. 7, a different branch).

**Ch. 1 L3 — The statistics cycle in problem solving (pp. 28–44).** The full statistical-investigation cycle as the organising frame: state the problem precisely → plan and collect data → analyse → report/interpret, with the scope-of-conclusion discipline stated in words (results hold for the population actually studied, p. 30); population vs sample and why sample size matters (pp. 32–33); analysis step centred on centre and spread: **mean, median, interquartile range, box plots, variance and standard deviation** (the SD discussion is conceptual — which data points inflate the SD, pp. 34–36); misleading-statistics literacy worked hard: relative vs absolute change (a school whose passes "rose 200%" from a small base, p. 37), inappropriate generalisation and measurement errors classified by which cycle step they corrupt (pp. 38–39); data exercises throughout (transport survey sampling 9 of a class of 28, p. 40; library-membership trends, p. 43; accident-count vs speed table, p. 44).

**Ch. 2 L1 — Modelling and sequences (pp. 46–60).** Mathematical modelling recalled from Grade 11 (electricity bill, traffic light); functions as models with attention to the *real* domain of the model (pp. 46–49); sequences defined as functions on ℕ; nth-term formulas (a_n = 3n − 2, b_n = n² − 1 …), graphs of sequences as scattered points, two-piece sequences, and **recursive definitions** (a_{n+1} in terms of a_n) tabulated side by side (pp. 52–59); the Tehran Stock Exchange index as a reading passage (p. 51).

**Ch. 2 L2 — Arithmetic sequences (pp. 61–72).** Common difference d; nth term a_n = a₁ + (n − 1)d built up from the train-and-stations table (pp. 61–64); the terms of an arithmetic sequence lie on a line (activity, p. 66); linear decay of a drug level (250 mg aspirin) as a model (p. 68); **sum of the first n terms** motivated by the qanat-wells problem (depths 30, 29.5, 29, …, 1.5 — 58 wells) and the formula used in exercises (pp. 69–72).

**Ch. 3 L1 — Geometric sequences (pp. 74–85).** Common ratio r; nth term a_n = a₁·r^{n−1}; growth/decay classification by r; half-life contexts throughout (antibiotic with 8-hour half-life, caffeine) (pp. 74–79); **sum of the first n terms derived**: the antibiotic-accumulation computation builds S₆ term by term and generalises to S_n = a₁(1 − rⁿ)/(1 − r) (pp. 80–81; table values recomputed — e.g. for 1/2, 1/6, 1/18, 1/54, …, S₅ = 121/162, correct); Zeno's paradox presented in a reading passage as resolved by this sum formula (p. 82) — the infinite-series limit itself is discussed only in that reading, not as a theorem.

**Ch. 3 L2 — nth root and rational powers (pp. 86–94).** Integer power laws recalled in a table; nth roots: existence cases tabulated by parity of n and sign of a (even root of a negative: does not exist; ± roots for even n of a positive; unique real root for odd n) (p. 88); approximations (the 8th roots of 25 ≈ ±1.495, p. 89 — recomputed: 25^(1/8) ≈ 1.4953, correct); rational exponents defined through the "what must 2^(1/2) mean" argument (2 = 2^(2b) ⇒ b = 1/2, p. 91); fluency exercises converting between radical and power forms and simplifying (pp. 92–94).

**Ch. 3 L3 — The exponential function (pp. 95–104).** f(x) = aˣ built from a game-scoring pattern (3ⁿ points; the stage at which the score is 6561 found from the pattern); graphs of 2ˣ, 3ˣ and (1/2)ˣ from tables, calculator values to 3 decimals; growth vs decay by base; the general growth/decay models **y = c(1 + r)ᵗ and y = c(1 − r)ᵗ** applied to investment (14% annual growth table, p. 103) and population decay — the worked example that contains this band's one confirmed error (p. 104, §6). Ceiling: **no logarithms anywhere in the book** — exponential equations are solved only by pattern/table, never inverted; no e, no continuous compounding, no derivative or limit language (the words do not occur).

### 5. Honest negatives — Mathematics and Statistics (3), Humanities branch

- No calculus of any kind: no limits, no derivatives, no integrals (the words do not occur).
- No trigonometry, no geometry beyond what earlier years supplied, no vectors/matrices.
- Probability stops at the classical definition: no conditional probability, no independence, no total probability, no random variables, no expected value, no distributions (no binomial/normal), no statistical inference (no estimation, confidence intervals or hypothesis tests — the terms do not occur).
- Exponentials are never inverted: no logarithms.
- No answer key (see §7).

### 6. Confirmed book errors — Mathematics and Statistics (3)

**1 confirmed error.**

- **Printed p. 104 (PDF p. 110), Ch. 3 L3, worked example (population decay).** The example states: a country's population in the year 2000 is about forty million; it is decreasing at a rate of one percent; what is the population in 2018? The printed solution substitutes into the general exponential-decay equation and prints, in Persian digits on the page (render-verified): **y = 40,000,000 × (1 − 0.01)¹⁸ = 3,338,600**. Recomputation: 0.99¹⁸ ≈ 0.83451, so y ≈ 40,000,000 × 0.83451 ≈ **33,380,550** — about thirty-three million, not 3,338,600. The printed answer is too small by a factor of about 10 (a dropped digit in the product). The model, the substitution and the exponent (2018 − 2000 = 18) are all correct; only the final evaluated number is wrong.

No other confirmed errors: the counting/probability computations (pp. 9, 20–21), the geometric-sum table value S₅ = 121/162 (p. 81) and the 8th-root approximation (p. 89) were recomputed and are correct.

### 7. Answer keys — Mathematics and Statistics (3)

**None.** The book ends with references (p. 105) and the validator-teachers credit page (PDF p. 112). (Worked examples and activities carry solutions as part of the teaching text, as in all five books; there is no exercise answer key.)

### 8. Held-copy defects — Mathematics and Statistics (3)

None. File complete: 112 PDF pages, matching the record.

---

## Band D summary

| Book | Branch | File | PDF pages | Printed pages | Chapters | Confirmed errors |
|---|---|---|---|---|---|---|
| Calculus (2) — حسابان (۲), code 112214, ISBN 978-964-05-3112-9 | Mathematical Sciences | g12-calculus.pdf | 152 | 1–145 (+ credits) | 5 | 0 |
| Discrete Mathematics — ریاضیات گسسته, code 112215, ISBN 978-964-05-3111-2 | Mathematical Sciences | g12-discrete.pdf | 94 | 1–85 (+ credits) | 3 | 0 |
| Geometry (3) — هندسه (۳), code 112213, ISBN 978-964-05-3113-6 | Mathematical Sciences | g12-geometry.pdf | 88 | 1–87 (+ credits) | 3 | 0 |
| Mathematics (3) — ریاضی (۳), code 112211, ISBN 978-964-05-3117-4 | Experimental Sciences | g12-maths.pdf | 160 | 1–151 (+ credits) | 7 | 0 |
| Mathematics and Statistics (3) — ریاضی و آمار (۳), code 112212, ISBN 978-964-05-3097-9 | Humanities (incl. Islamic Sciences) | g12-maths-stats.pdf | 112 | 1–105 (+ credits) | 3 | 1 |
| **Band D total** | **3 branches, kept separate** | **5 files** | **606** | — | **21** | **1** |

Branch shape, in one line each (do not merge): Mathematical Sciences G12 = differential calculus with full applications (concavity, sketching, trig derivatives) + a genuine discrete book (number theory, domination-focused graph theory, combinatorics with a long Latin-squares block) + an analytic book (matrices/determinants, geometric conics, ℝ³ vectors with dot/cross/triple products). Experimental Sciences G12 = the same calculus core cut down (no trig derivatives, no concavity/sketching, no asymptote theory) but with composition/inverse functions, double-angle formulas, a dedicated optimisation lesson, a gentler conics chapter and a single total-probability lesson. Humanities G12 = no calculus at all: counting, classical probability, the statistics cycle with centre/spread literacy, arithmetic and geometric sequences, rational powers and exponential growth/decay models without logarithms. No book in Band D contains an answer key, an integral, or a differential equation.
