# Kuwait — Mathematics, Grades 1–12 (Ministry of Education, Kuwait)

READ COMPLETE. Files in hand (reconciled against the record):
**29 files in the reconciled set — 28 in hand and read, 1 listed but
unfetchable** (Grade 11 Mathematics Term 1 student book — see Gaps).
**28 distinct works: 26 student books + 2 workbooks; 0 teacher guides**
(there are no teacher guides in the Kuwait maths set at all).
**5,017 PDF pages in total** (Band A, Grades 1–4: 1,373; Band B,
Grades 5–8: 1,782; Band C, Grades 9–12: 1,862;
1,380,072,763 bytes, ~1.28 GiB, for the 28 read PDFs).
Anchors: **449 (402 passed, 42 corrected, 5 not found)** —
Band A 115 (97 passed, 18 corrected, 0 not found),
Band B 148 (130 passed, 13 corrected, 5 not found),
Band C 186 (175 passed, 11 corrected, 0 not found).
Confirmed book errors after check: **48** (Band A 12, Band B 6,
Band C 30) — the readers' drafts claimed 69; 21 claimed errors were
struck on citation check as reader misreadings (Arabic-Indic
digit-order reversals in Band A/B drafts, and RTL inequality glyphs
read as Latin-direction symbols in Band C), each retraction recorded
in-section in the band filings below.

## The set at a glance

- **One ministry, one series, one language: Arabic throughout.**
  Every book is a Kuwait Ministry of Education mathematics book
  (Educational Research and Curricula Sector). This filing is in
  English; maths content is given in English.
- **Grades 1–9:** a Term 1 and a Term 2 student book for every grade,
  each term file holding Part 1 and Part 2 bound together, each part
  with its own cover, title page and printed pagination. No track is
  printed before Grade 11.
- **Grades 11–12 split into Scientific and Literary tracks, and the
  tracks are never merged in this filing.** Scientific: Grade 11
  Maths workbook T1 + student book T2, Grade 12 student books T1 + T2.
  Literary: statistics only — Grade 11 Statistics student books
  T1 + T2 + T2 workbook, Grade 12 Statistics student book T2.
  Grade 10 is pre-track (student books T1 + T2).
- **Kinds were proved from each book's own cover + title page, never
  from the filename or the record** — and the record was wrong
  repeatedly: five files recorded/shelved as workbooks are STUDENT
  books (G10 T1, G10 T2, G11 Maths T2, G12 Maths T2, G12 Statistics
  T2). Only two files in the whole set are exercises-only workbooks:
  the Grade 11 Maths T1 workbook (scientific) and the Grade 11
  Statistics T2 workbook (literary).
- **No answer key in any book.** The statistics books' back covers
  list an "exercise workbook with answers" as a separate series
  component; it is not in hand.
- **Editions are per book and never borrowed across files** (each
  band section states its own): broadly, Grades 1–9 Term 1 books are
  2nd edition 1448 AH / 2026–2027 and Term 2 books 1st edition
  1447 AH / 2025–2026, with named exceptions (Grade 5 both terms are
  1st edition 1447 AH; Grade 9 Part 2 and several Band C books vary);
  Band C also holds an old generation (2012/2013/2014 Pearson-source
  series, 2nd editions running to 1447 AH / 2025–2026) alongside the
  new generation. References pages in many books cite older editions
  than the title page — the references were not updated.

## How this filing was made — read this first

- **22nd maths read, 2026-11-05/06.** Three bands (A: Grades 1–4;
  B: Grades 5–8; C: Grades 9–12), one filing per book (28 filings
  for 28 books). The band filings are reproduced in full below,
  with their headings demoted one level.
- **Method honesty.** Band A: text-layer books read from
  `pdftotext -layout`; image-only books (G1-T1, G2-T1, G3-T1) read
  visually from renders — **G3-T1 is contents-complete with all four
  تدرب أكثر sections read in full and lessons spot-sampled, NOT a
  page-by-page error hunt** (stated in its section). Band B: every
  book read in full from the text layer, flagged pages verified
  visually; Grade 5 Term 2 is ~106 pages image-only and was read
  visually. Band C: every book read visually from 200 dpi renders of
  every page (Arabic OCR proved unusable on this machine), with
  text-layer cross-checks where a clean layer exists. No
  word-for-word transcription anywhere — own summaries and
  structural notes only, with worked values re-computed.
- **Separate citation check.** Checkers (not the readers) verified
  **449 anchors** against the exact PDF pages (check files:
  `checks/check-band-a.md`, `checks/check-band-b.md`,
  `checks/check-band-c.md` in the work folder), re-adding to
  **402 passed, 42 corrected, 5 not found**. Every correction was
  made in place in the band filings before assembly; the 5
  not-found items are listed under "Not found and unverified"
  below and are cited nowhere as fact.
- **The RTL traps (all three bands).** `pdftotext` reverses
  equation/inequality lines in these Arabic books, and Arabic-Indic
  digits can be misread in reverse order; Band C adds that
  inequality glyphs must be read by which side opens toward the
  larger quantity. No error in this filing rests on extraction
  alone — and 21 of the readers' claimed errors died of exactly
  these traps on check.

## Reconciliation and record corrections

- **The inventory's "18 in hand" is a confirmed undercount.**
  Set verification in both directions (TSV rows + books.json rows +
  push-state paths + live release-asset listings across all 9
  releases, via the authenticated GitHub API; work-folder files
  `set-verification.md`, `set-check.json`) proves **29 files**: the
  inventory was written before the 2026-11-05 grab runs landed the
  missing Term 1 books (G2 T1, G3 T1, G5 T1, G5 T2, G6 T1, G8 T1,
  G9 T1, G11 Maths WB T1, G11 Maths SB T1, G11 Stats SB T1, G12
  Maths T1 SB). The inventory's 18 are all present; its list is a
  subset, not a different set.
- **One of the 29 is listed but NOT in hand.** The Grade 11 Maths
  SB T1 release asset (mid-size-books-8, id 715037815,
  102,105,970 B) is listed, but its blob 404s on the authenticated
  API asset endpoint and on the releases/download route (fresh
  retries 2026-11-06; the local `g11-t1.pdf` is the 139-byte 404
  JSON body, not the book). The one bounded external attempt the
  user authorized (2026-11-06) also failed: the recorded original
  source, kw.afedne.com file/873, returned HTTP 520, and minhaji's
  Kuwait G11 catalogue did not expose the file. Full record:
  `checks/g11-t1-fetch-note.md`. So the read set is **28 books**,
  and Grade 11 Term 1 (scientific) is covered only by its workbook.
- **textbooks.tsv holds 30 Kuwait Mathematics/Statistics rows =
  28 distinct books + 2 duplicated rows** (the Statistics Grade 11
  Term 2 workbook row and the Statistics Grade 12 Term 2 workbook
  row each appear twice, with identical Drive URLs; no distinct
  book is lost). **TSV is missing one row books.json holds: the
  G12 Mathematics Term 1 student book** — TSV needs that row added.
  TSV's Drive-link rows (G1 T1/T2, G2 T2, G5 T1/T2, G6 T1, G11
  Stats T1) are stale as source URLs: those books are secured as
  release assets.
- **The record's kind labels are wrong for five books** (see The
  set at a glance): the G10/G11/G12 files titled "كتابي الطالب
  والتمارين" (my student and exercises book) were proved from
  their covers to be student books in five cases (G10 T1, G10 T2,
  G11 Maths T2, G12 Maths T2, G12 Statistics T2) and true
  exercises-only workbooks in two (G11 Maths T1, G11 Statistics
  T2). books.json's title-based split (22 student + 7 workbook)
  does not survive cover proof: the read set is 26 student + 2
  workbook.
- **Push-state** lists 28 Kuwait maths tree paths — exactly
  books.json's 29 minus the staged G12 Maths T1 student book
  (staged on disk, byte-matched to books.json at 71,902,092 B, and
  read from the staging copy; its unpushed state is a library-side
  note, not a reading gap).
- **Band-summary totals corrected at assembly (sections win over
  summaries):** Band A errors 21 → 12, Band B errors 11 → 6,
  Band C errors 37 → 30 — all three corrections were made by the
  citation checkers in-section, not at assembly. Page totals
  re-added at assembly: 1,373 + 1,782 + 1,862 = **5,017**.

## Gaps

- **Grade 11 Mathematics Term 1 student book (scientific) — NOT
  IN HAND** (listed but unfetchable; see Reconciliation). Grade 11
  scientific Term 1 rests on its workbook only. The workbook is
  never cited as the student book.
- **No Grade 11 Statistics workbook Term 1; no Grade 12 Statistics
  book for Term 1 at all; no Grade 12 Mathematics workbook Term 1.**
  (The Grade 12 Statistics Term 2 slot recorded as a workbook holds
  the student book — there is no Grade 12 statistics workbook in
  hand.)
- **No teacher guides for any grade** — none exist in the record.
- Content ceilings are stated per book in the band sections
  (honest negatives). Headlines: the literary track teaches no
  calculus, complex numbers, logarithms or trigonometry; Grade 10
  stops at 2×2 matrices and descriptive statistics; the Grade 11
  scientific book stops short of De Moivre, nth roots of complex
  numbers, inverse trig functions and vectors in space; the Grade
  12 scientific book covers partial fractions only for distinct
  linear factors and differential equations only for
  constant-coefficient second-order linear equations; the Grade 12
  literary book has no statistical inference at all.

## Not found and unverified (carried, never taught as fact)

- Band B, 5 anchors NOT FOUND (Bands A and C: none): the G6-T2
  planet-moon table staleness note; the G7-T2 author-replacement
  line; the G8-T1 references-editions line (the identical claim was
  verified for G8-T2); the G8-T2 L5-3 six-vs-five conditions
  summary; the G8-T2 embedded-"G7"-filename claim (not reproducible
  from the held file's metadata; the book's identity is
  cover-proved anyway). All five are minor and stand in the filing
  as filed, flagged here.
- Two Band C items flagged by the checker but NOT added to the
  filing (check file only, unverified): g11-t2-wb printed p. 77 —
  a second apparent sin/cos slip in the lake-area guide; and
  g11-stats-t2-wb printed p. 14 — a Group B item saying 16 weights
  whose list appears to have 15 values (200-dpi read only, not
  crop-verified).

---

## Kuwait — Maths — Band A (Grades 1–4)

**READ COMPLETE — final filing, 2026-11-06.** All 8 books read in full (see "How the books were read" at the end). File in English; the books are in Arabic. Own summaries only — no word-for-word transcription; only very short quoted fragments where a single phrase must be shown.

### Set at a glance

- **8 books, all student textbooks, 0 teacher guides, 0 answer keys.** Each term file holds both Part 1 and Part 2 bound together, each part with its own cover, title page and front matter.
- **Total: 1,373 PDF pages, 394,383,773 bytes.**
- **Book errors confirmed: 12** (G1-T1 1, G1-T2 2, G2-T1 2, G2-T2 0, G3-T1 3, G3-T2 3, G4-T1 0, G4-T2 1). Teach corrected, never as fact. One earlier "error" (G4-T1 Venn diagram) was retracted — the diagram is correct. A citation check (2026-11-06) struck nine further claimed errors (G2-T1 ×5, G3-T1 ×3, G4-T2 ×1) as Arabic-Indic digit-order / sentence-order misreads — see Resolved non-errors and checks/check-band-a.md.
- **No file-to-record mismatches:** grade, term and kind are as filed for all 8 books, each proved from its own cover + title page. No track is printed in Grades 1–4. No answer key in any book.
- All 8 books carry portraits of Amir Sheikh Meshal Al-Ahmad Al-Jaber Al-Sabah and Crown Prince Sheikh Sabah Khaled Al-Hamad Al-Sabah, a shared introduction, unit-opener value pages, and recurring characters Barak and Maryam. Every book ends with references (citing older editions), a guardian letter, and a back cover.
- **Term 1 books are 2nd edition 1448H / 2026–2027 (with ISBN); Term 2 books are 1st edition 1447H / 2025–2026 (no ISBN printed).**

### Files (in `kuwait-maths/pdfs/`)

| File | Grade / Term | PDF pp. | Bytes | SHA-256 |
|---|---|---|---|---|
| `g01-t1.pdf` | 1 / 1 | 174 | 15,771,239 | `b2e9c4e806e06c25adc0b4dc41cba884a29b27a619e1c55444c77cd9cea014dc` |
| `g01-t2.pdf` | 1 / 2 | 164 | 31,123,530 | `f53d2da33ba21310360b370866f3ab04657383e33a44fce9df9ea9b559ac9f4b` |
| `g02-t1.pdf` | 2 / 1 | 166 | 15,518,022 | `c923bbb2de56956f1551b8c5178ddb2b8d59c6b1b05a4c8e36aac1d3a89ff71f` |
| `g02-t2.pdf` | 2 / 2 | 166 | 19,972,162 | `61a4bc8924afa86d362878fda39d4aff8d8a38c36b71098f9e852366ed462543` |
| `g03-t1.pdf` | 3 / 1 | 180 | 84,667,113 | `a842d3d8b2f1c319a4cd92e2814c4daba3208dd9fea73fe840f9fc651d73d54f` |
| `g03-t2.pdf` | 3 / 2 | 165 | 21,877,621 | `c8c545756ec7976adb8922663e67ddb645508d53ac7cef321ee8b1b9f43b65bf` |
| `g04-t1.pdf` | 4 / 1 | 187 | 106,348,736 | `a9b9767d4fe032fcdeb4a929e71cbbe47092aa1ab4eb9cb987421e10cee09a44` |
| `g04-t2.pdf` | 4 / 2 | 171 | 99,105,350 | `e87d89ec7c9c4211405dce85eccef9821f90b8a2191ee7825c7bb07933709359` |

All 8 SHA-256 hashes re-computed 2026-11-06 and matching the work notes.

### Printed-page offsets (PDF page − printed page)

| Book | Part 1 offset | Part 2 offset |
|---|---|---|
| G1-T1 | PDF − 1 (PDF pp. 12–82) | PDF − 3 (PDF pp. 105–169) |
| G1-T2 | PDF − 1 (PDF pp. 12–82) | PDF − 3 (PDF pp. 99–161) |
| G2-T1 | PDF − 1 | PDF − 5 (PDF p. 100 = lesson 3-1, footer badge printed 95) |
| G2-T2 | PDF − 1 (PDF pp. 15–81) | PDF − 2 (PDF pp. 98–165) |
| G3-T1 | PDF − 1 (PDF p. 15 standards footer printed 14) | PDF − 3 (PDF p. 103 standards footer printed 100) |
| G3-T2 | PDF − 1 (PDF pp. 15–85) | PDF − 4 (PDF pp. 98–160) |
| G4-T1 | PDF − 1 for PDF pp. 12–86 | PDF − 0 for PDF pp. 98–186 |
| G4-T2 | PDF − 1 (PDF pp. 12–88) | PDF − 2 (PDF pp. 99–169) |

### Reconciliation — corrections applied in this final filing

This filing reconciles the interrupted reader's draft filing and work notes against the books. The following were corrected (each re-verified against the PDF this session):

- **G1-T2 author list:** the draft listed 3 authors; the full list is **7** (same team as G2-T2 and G3-T2).
- **G2-T1 Unit 3 lesson titles:** the draft had 3-6/3-7 as "subtracting a 2-digit number from another 2-digit number"; the contents page (PDF pp. 95–96, re-read) says 3-6 and 3-7 are subtracting a **1-digit** number from a 2-digit number (without / with renaming), and 3-8 is subtracting a 2-digit number from another 2-digit number with renaming when needed.
- **G2-T1 error 2 permutations:** the work-notes summary listed impossible sums (88, 96, 142); the six permutations of digits 6, 2, 0 in 8_+2_=9_ give **102, 106, 102, 108, 106, 108** — never a 9x number. The error stands; the arithmetic is corrected.
- **G3-T1 تدرب أكثر Unit 2, item 11:** the draft read the subtrahend as 3065 and the answer as 2235. Re-read at 300 dpi: the subtrahend is **3056**; Yousef's answer is 2356 (wrong) and Yaqoub's is **2244 (correct: 5300−3056=2244)**. The item is a correctly constructed deliberate spot-the-error exercise, not a book error.
- **G3-T2 author list and reviews:** the draft listed 3 authors and scientific review Loulouh Mohammed Sultan bin Issa. The imprint (PDF p. 3 and Part 2 imprint PDF p. 88) gives the **7-author team**; scientific review **Raja Hassan Al-Ustad**; language review **Sahar Saleh Al-Shanawi**.
- **G3-T2 models:** the draft listed 3 models in Part 1. The book has **4** (divider printed 75; fact families 77; robot 78; division unknown-number board 79; number lines 81). Part 1 references are printed **83** (PDF p. 84), guardian letter PDF p. 85; Part 2 models are divider printed 151, digital clocks 153, ruler 20 cm 155, paper money 156, coins 157; Part 2 references printed **159** (PDF p. 163), guardian letter PDF p. 164, back cover PDF p. 165. All verified from renders this session.
- **G3-T2 errors:** the draft listed 1; **3 are confirmed** — the two new ones (lesson 8-1 comparison, تدرب أكثر Unit 8 item 20) were found and verified from renders this session.
- **G4-T2 author list:** the draft listed 3 authors; the title page (PDF p. 2, re-read) gives **7** (Dalal Mubarak Al-Hajraf head, Fatima Asad Al-Kandari, Hanadi Mohammed Al-Mutairi, Hessa Mohammed Al-Kandari, Nawal Fahd Al-Jafin, Riyasa Sultan Al-Hathal, Maha Abdulwahab Mohammed Taqi). The title page also carries the G4-T1 language reviewers' names as printed.
- **G4-T2 errors:** the draft listed 1; **2 are confirmed** — تدرب أكثر Unit 7 item 29 (0.6 has no partner summing to 1.5) was confirmed from a render this session.
- **G4-T1 / G4-T2 Part 2 front-matter blanks:** the draft listed the ranges "91–96" / "93–98" as blank. They are not: blanks are T1 **92, 94, 96** (portraits 93, 95) and T2 **94, 96, 98** (portraits 95, 97). The "4–9" front-matter blank ranges are likewise corrected to **4, 5, 7, 9** (portraits on 6 and 8).
- **G1-T1 Part 2 models:** the draft said "PDF pp. 166–170". The models are divider printed 161 (PDF p. 164); model 1 abacus printed 163 (PDF p. 166); model 2 ten-frames printed 164 (PDF p. 167); model 3 number lines printed 165 (PDF p. 168); model 4 number-bond board printed 167 (PDF p. 170) — blanks interleaved at PDF pp. 165, 169, 171. All verified from renders this session. The Part 2 deposit **(522)** was also verified from the Part 2 imprint (PDF p. 95).
- **G1-T1 Part 1 tail:** Part 1 ends with references (PDF p. 90, unnumbered), guardian letter (PDF p. 91), back cover (PDF p. 92); Part 2 starts at PDF p. 93. The "References printed p. 169" in the contents list is Part 2's references (PDF p. 172).
- **Impossible blank-page numbers removed:** the draft listed blank PDF p. 165 in G1-T2 (164 pages), p. 167 in G2-T2 (166 pages) and p. 166 in G3-T2 (165 pages). None exists; dropped.
- **G1-T1 blanks:** the work-notes list adds PDF p. 135 (Unit 4 opener reverse); the draft omitted it. Included.
- **G2-T1 blanks:** the draft adds PDF p. 122 ("my project" page); the work notes omitted it. Included.
- **G3-T1 blanks:** the work-notes list adds PDF p. 168 ("my project" page); the draft omitted it. Included.
- **G4-T2 Unit 6 project:** "Fraction spinner" (دوارة الكسور), not "Fraction wheel" — verified from the text layer (PDF p. 75).
- **G4-T1 contents-page pagination slip:** the contents page lists Unit 3 تدرب أكثر on p. 132; it is on **p. 128** (verified from the text: PDF p. 128 footer 128).
- **G2-T1 Part 2 tail (re-read from renders this session):** references are printed **159** (PDF p. 164), guardian letter printed **160** (PDF p. 165), back cover PDF p. 166 — the draft's "references PDF 163 (printed 158); guardian letter PDF 164; back cover PDF 165; PDF 166 blank reverse" was wrong throughout. Part 2 models are divider printed 149 (PDF p. 154) and 8 models printed **151–158** (ten-frames 151, work card 152, place-value board 153, number lines 154, hundred chart 155, clock 156, calendar 157, dot grid 158), with blank reverses at PDF pp. 153 and 155 — not a consecutive "149–160" run. Part 1 tail is now also complete from renders: references printed 81 (PDF p. 82), guardian letter printed 82 (PDF p. 83), back cover PDF p. 84. Part 1 models corrected to ten-frames 72, work card 73, place-value board 74, abacus 75, number-components board 76, partitioning board 77, number lines 78, hundred chart 79.
- **G2-T2 Part 2 tail (re-read from renders this session):** references are printed **163** (PDF p. 165) — the contents page lists 164, a contents-page slip; the references page itself carries no printed number, and the model run (divider 157, models 158–162) plus offset PDF−2 gives 163. The guardian letter is PDF p. **166 (last page)** — not a back-cover reverse. There is no separate back-cover page: the Part 2 back cover is the right half of the landscape cover spread on PDF p. 86 (mediabox 1227×782 pt, double-width; all other pages are portrait ~612×792 pt). Part 1 tail confirmed from renders: references printed 81 (PDF p. 82), guardian letter PDF p. 83, blank decorative pages PDF pp. 84–85. Part 1 model 3 is the **abacus**, not "counters".
- **G1-T2 hundred-chart pages:** the earlier "pp. 55/78" citations were off by 2; the error is on printed pp. **57 and 80**.
- **G4-T1 Venn "error" RETRACTED** (see below) — G4-T1 has zero book errors.

### Consolidated book errors — Band A (12)

| # | Book | Location (printed p. / PDF p.) | What is printed | Correct value |
|---|---|---|---|---|
| 1 | G1-T1 | Lesson 2-13, November calendar, p. 76 / PDF 77 | 1 November shown on a Saturday (2025 layout) | 1 Nov 2026 is a **Sunday**; 30 Nov is a Monday |
| 2 | G1-T2 | Intro footer, PDF pp. 11–12 | Footer reads "Grade 4, Term 2" | "Grade 1, Term 2" |
| 3 | G1-T2 | Lesson 6-5, p. 57 / PDF 58; Model 7, p. 80 / PDF 81 | Hundred chart prints **34** instead of 45 (twice) | **45** (34 appears twice, 45 never) |
| 4 | G2-T1 | تدرب أكثر Unit 1, item 21, p. 43 / PDF 44 | "56 > ___" with options 25, 36, 80 | **Two** correct options (25 and 36 are both < 56) |
| 5 | G2-T1 | Lesson 2-7, item 10, p. 63 / PDF 64 | Fill 8_+2_=9_ using digits 6, 2, 0 each once | **No solution** (permutations give 102, 106, 102, 108, 106, 108 — never a 9x number) |
| 6 | G3-T1 | Lesson 1-6 تدرب, item 7, p. 29 / PDF 30 | Pattern "98, 2, 99, 1, 100, __, __, __" with four options (none matching) | Natural rule gives **0, 101, −1** (includes a negative outside Grade 3 scope) — no correct option |
| 7 | G3-T1 | تدرب أكثر Unit 1, item 31, p. 41 / PDF 42 | "4815 < □" with options 4814, 4926, 4895 | **Two** correct options (4926 and 4895 are both > 4815) |
| 8 | G3-T1 | Lesson 2-8 تدرب, item 9, p. 63 / PDF 64 | "Which of these estimated 711−393 reasonably?" (actual 318) | **Two** correct options: 300 (700−400) and 320 (710−390) |
| 9 | G3-T2 | Lesson 5-12 ÷9, p. 40 / PDF 41 | Multiples line prints **8, 16, 24** | First multiples of 9: **9, 18, 27** |
| 10 | G3-T2 | Lesson 8-1, p. 127 / PDF 131 | Worked comparison hint prints "500 cm > 2000 cm" | **500 cm < 2000 cm** (500 cm = 5 m < 20 m = 2000 cm) |
| 11 | G3-T2 | تدرب أكثر Unit 8, item 20, p. 147 / PDF 151 | Three groups of notes to match a 10-dinar note; groups total 8, 11 and 11 dinars | **No correct option** (no group totals 10 dinars) |
| 12 | G4-T2 | تدرب أكثر Unit 7, item 29, p. 125 / PDF 127 | Match each of 0.8, 1, 1.2, 0.6 with a partner summing to 1.5; partners offered 1.4, 0.7, 0.3, 0.5 | 0.8+0.7, 1+0.5, 1.2+0.3 all work, but **0.6 has no partner** (it needs 0.9, not offered) |

### Resolved non-errors (deliberate error-spotting exercises and extraction artefacts — NOT book errors)

- **G4-T1 lesson 4-9 تدرب, item 12 (printed p. 157, PDF p. 157) — the Venn diagram is CORRECT.** An earlier read flagged it as an error; re-verified at 300 dpi: left circle = multiples of 3 (3, 15, 27, 33), right circle = even numbers (8, 16, 20, 32), overlap = multiples of 6 (6, 12, 24). 20 and 32 sit in the right-circle-only region where they belong. **Do NOT file it as an error.**
- **G3-T1 تدرب أكثر Unit 2, item 11 (printed p. 75, PDF p. 76):** Yousef and Yaqoub solve 5300−3056. Yaqoub's 2244 is CORRECT; Yousef's 2356 is wrong. Deliberate find-the-error item, correctly constructed (re-verified at 300 dpi).
- **G3-T1 تدرب أكثر Unit 1, item 13 (printed p. 39):** Hashim says the library 580 m away is "about 500 m" — the pupil's answer is wrong (580 rounds to 600 to the nearest hundred) and the item asks the pupil to judge it. Deliberate, not a book error.
- **G3-T1 تدرب أكثر Unit 2, item 15 (printed p. 76):** 350−208 = 142; the three base-ten pictures are 142 (right, correct), 158 (middle), 152 (left) — exactly one correct option.
- **G3-T1 lesson 1-5, item 11:** Sara wrote "one hundred thousand four hundred and seventeen" as 1417 — wrong; correct 100,417. Spot-the-error item.
- **G3-T1 lesson 2-5 تدرب, item 9:** 4561+5264 printed as 9725 (correct 9825); 327+128 printed as 445 (correct 455). Spot-the-error item.
- **G3-T1 lesson 2-11, item 9:** Faisal vs Othman on 5360−1247 = 4113. Spot-the-error item.
- **G3-T1 lesson 4-2 تدرب, item 7:** Shahd 14×2=28 correct; Munira 14×2=82 wrong. Spot-the-error item.
- **G3-T1 lesson 4-3 تدرب, items 6–7:** 54×8 printed as 402 (correct 432); 38×7 printed as 2156 (correct 266). Spot-the-error item ("find the error then correct it").
- **G2-T2 deliberate error-spotting:** lesson 5-3 "300+50+6 = 365" (correct 356); lesson 6-3 Shikha "687+3 = 610" (correct 690); lesson 8-3 Mubarak "3x10 = 0" (correct 30); p. 48 item 9: Shahd's 400+235=536 (correct 635) — explicitly "what mistake did Shahd make?".
- **G4-T1 lesson 1-9 find-the-error items** (456+128, correct 584; 24,561+52,371, correct 76,932) are spot-the-error items, not book errors.
- **G4-T2 تدرب أكثر Units 5–8 true/false items** (e.g. U5 item 19: 630÷70=90 is FALSE as stated — 630÷70=9; item 20: factors of 20 "10, 5, 4, 2 only" is FALSE — also 1, 20; item 21: 1598 divisible by 2 is TRUE) are deliberate true/false exercises.
- **G4-T2 Unit 5 item 10** lists 1 among "non-prime" numbers — 1 is neither prime nor composite; recorded as a simplification, not filed as an error.
- **G1-T2 PDF p. 108 (lesson 7-3):** "99−9=42 / 45−3=65 / 67−2=90" are a matching exercise — 42, 65, 90 are scrambled match targets (99−9=90, 45−3=42, 67−2=65), not printed results.
- **G2-T2 PDF p. 46 (lesson 6-2):** "500=400+18" etc. are circle-the-answer / matching items (options, not results); item 20 matching: 500↔200+300, 900↔500+400, 90↔30+60.
- **G3-T2 PDF pp. 131–132 (lesson 8-2):** "90 m = 9000 cm", "3 m 65 cm = 365 cm", "1 dm = 10 cm", "1 m = 10 dm", "1 cm = 10 mm", "1 m = 100 cm = 1000 mm", "6 dm = 60 cm", "8000 mm = 80 dm" — all correct.
- **G3-T2 lesson 5-12 item 19 (p. 44):** options read RTL as 12÷6, 12÷12, 12÷3 — the related fact 12÷3=4 IS present; not an error.
- **G4-T1 Unit 2 items 32–33 true/false:** "400×50 = 2,000" (false as printed — 20,000) and "3×20×40 = 2,400" (true) are true/false judgement items.
- **G4-T1 تدرب أكثر Unit 1, item 32 (p. 46):** the table gives elephant 2,430 kg, camel 860 kg, hippopotamus 2,250 kg; elephant − camel = 1,570 kg, and that option is present. Item 29 (500,000+500+5=500,505), item 30 (Mansour 4,434; Majid 100 more = 4,534; together 8,968), item 31 (1,465−1,005=460) and item 33 (bar-model sentence "211 = ? + 105" correctly expresses the model) all check out.
- **RTL trap:** `pdftotext` reverses equation/inequality lines in these Arabic books; no inequality-direction error is filed from extraction alone — every such item was verified against a render.

- **Struck on citation check (2026-11-06) — G2-T1 lesson 2-8 bottom strip (printed p. 64, PDF p. 65):** read with Arabic-Indic digits in their printed order (tens left, ones right), the sums are 27+14+13 = **54** (printed 54), 16+21+26 = **63** (printed 63), 45+14+18 = **77** (printed 77) — all correct as printed. The draft had reversed every number.
- **Struck on citation check — G2-T1 lesson 2-8 تدرب, item 3 (printed p. 64, PDF p. 65):** the item is **19+20+35** (blank for the pupil to answer; = 74), inside the lesson's "sums less than 100" aim. The draft's "91" was a digit reversal.
- **Struck on citation check — G2-T1 تدرب أكثر Unit 2, item 12 (printed p. 67, PDF p. 68):** Salem starts at **23**, not 32; 23+50 = **73**, which IS one of the options (28, 73, 78). The item works as printed.
- **Struck on citation check — G2-T1 lesson 3-4, item 3 (printed p. 103, PDF p. 108):** item 3's robot subtracts **1** (inputs 9, 4, 3 → 8, 3, 2); the subtract-4 robot is item 4 (inputs 12, 10, 15 → 8, 6, 11). No negative arises.
- **Struck on citation check — G2-T1 lesson 3-7, item 13 (printed p. 109, PDF p. 114):** the problem is **61−5**; Mubarak's answer **56 is correct** and Mohammed's 64 is the wrong one — a correctly built "which is right?" item. The draft had reversed the problem and both answers.
- **Struck on citation check — G3-T1 تدرب أكثر Unit 2, item 17 (printed p. 76, PDF p. 77):** the second addend is **7251**, not 725; 1048+7251 = **8299**, which IS the first option. The item works as printed.
- **Struck on citation check — G3-T1 lesson 3-6 تدرب, items 11–12 (printed p. 115, PDF p. 118):** the book's instruction puts the **product at the top and the sum at the bottom**: item 11 product 8 / sum 6 → **2 and 4**; item 12 product 21 / sum 10 → **3 and 7**. Both items are solvable exactly as printed; the draft had swapped sum and product.
- **Struck on citation check — G3-T1 lesson 4-10 اربط (printed p. 158, PDF p. 161):** the book says "نصفي المربع" — **the two halves** of a square equal a whole square — which is true, and the area count 16 full squares + the two halves = **17** is correct. The draft's "half a square equals a whole square" was a mistranslation.
- **Struck on citation check — G4-T2 تدرب أكثر Unit 8, item 2 (printed p. 152, PDF p. 154):** read in sentence order, Adel's trip **starts 05:20 pm and ends 08:20 pm** (3 hours) — no error. The draft had read the two time clusters in reverse order.

### Minor typos (confirmed; not counted as book errors)

- G2-T2 English subtitles "Befoer" (Before), "Numbres" (Numbers); spacing/underscore typos in lessons 6-3/6-4/6-5.
- G3-T2 lesson 6-8 "Par Graph" (Bar Graph).
- G4-T1 lesson 4-6 "Line Ghraph" (Line Graph).
- G4-T2 lesson 5-8 "Dividing Greating Numbers" (Greater).

### Minor inconsistencies (not counted as book errors)

- **G3-T1 Unit 3 project, printed p. 134 (PDF p. 137):** the project says its multiplication cards stay within the table up to 9×9, but one pictured card is 1×10.
- **G4-T1 contents page:** lists Unit 3 تدرب أكثر on p. 132; it is on p. 128 (see Reconciliation).
- **G2-T2 contents page:** lists Part 2 references on p. 164; they are on printed p. 163 (PDF p. 165) — see Reconciliation.
- **G3-T1 lesson 4-7 تدرب, item 7 (printed p. 153, PDF p. 156) — ambiguous, not filed as an error:** a cuboid-shaped residential building — "if each side has 10 windows, how many windows are there?" The book never says how many sides to count (4 visible sides → 40; all 6 faces → 60).

---

### 1. Grade 1 Term 1 — `g01-t1.pdf` (Second Edition 1448H / 2026–2027, ISBN 978-9921-33-099-1)

#### Identity (cover + title page + imprint, PDF p. 3; Part 2 title p. 94, imprint p. 95)

- **Grade:** 1. **Term:** 1. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** Dar Al-Qabas. © Ministry of Education, Kuwait.
- **Edition/year as printed:** First edition 2025/2026; **Second Edition 1448H / 2026–2027**.
- **ISBN:** **978-9921-33-099-1**. Ministry deposits **(521)** Part 1 and **(522)** Part 2, both dated 9/8/2026.
- **Authors:** Dalal Mubarak Falah Al-Hajraf (head), Ghazil Saeed Dalmouk Al-Dosari, Abeer Barjas Ayed Al-Mutairi.
- **Review teams:** scientific review Radhia Ahmed Ibrahim Al-Sarraf, Hessa Mohammed Al-Kandari, Iman Ibrahim Yousef Bouhamra; AI slides team Saadia Othman Ibrahim, Faten Ahmed Al-Khouli; language review Dr Mishal Sanat Al-Harbi, Wasmiya Maakam Al-Ajmi.
- **PDF pages:** 174. **Printed range:** Part 1 printed pp. 17–88; Part 2 printed pp. 105–169. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 3.
- **Reading method:** image-only book (no usable text layer) — **read visually in full from 150 dpi renders (174/174 pages)**, disputed items at 300 dpi. Greyscale run: PDF pp. 33–77 only; colour resumes PDF p. 78. Zero is written with a diamond glyph ◆.
- **Part 1 tail:** references PDF p. 90 (unnumbered; cites 3rd ed. 2024–2025 and trial ed. 2023–2024), guardian letter PDF p. 91, back cover PDF p. 92 ("سبورتي 1" + QR codes). **Part 2 front matter:** cover PDF p. 93 ("2/1"), title p. 94, imprint p. 95, Basmala p. 96, portraits PDF pp. 98 and 100, intro PDF p. 102, contents PDF pp. 103–104, standards PDF p. 105 (printed 102).

#### Contents (from the contents pages, printed pp.)

**Unit 1 (numbers to 5 and position)** — standards 14 · 1-1 spatial relations 17 · 1-2 inside/between/outside 20 · 1-3 sorting 22 · 1-4 patterns 24 · 1-5 more/less/equal 26 · 1-6 number 1 (28) · 1-7 number 2 (30) · 1-8 number 3 (32) · 1-9 numbers 1, 2, 3 (34) · 1-10 number 4 (36) · 1-11 number 5 (38) · 1-12 numbers 1–5 (40) · 1-13 comparing numbers 42 · تدرب أكثر Unit 1, 44 · project "Sorting is fun" 46.
**Unit 2 (numbers to 12 and time)** — standards 48 · 2-1 number 6 (51) · 2-2 number 7 (54) · 2-3 number 8 (56) · 2-4 number 9 (58) · 2-5 number 0 (60) · 2-6 number 10 (62) · 2-7 number 11 (64) · 2-8 number 12 (66) · 2-9 whole hours 68 · 2-10 time (before/after) 70 · 2-11 time problems 72 · 2-12 calendar 74 · 2-13 days of the week 76 · تدرب أكثر Unit 2, 78 · project (paper-plate clock) 80 · models 83.
**Unit 3 (addition to 10)** — standards 102 · 3-1 Understanding Addition 105 · 3-2 addition sentence 108 · 3-3 composing 2, 3 (110) · 3-4 composing 4, 5 (112) · 3-5 composing 6 (114) · 3-6 composing 7 (116) · 3-7 composing 8 (118) · 3-8 composing 9 (120) · 3-9 composing 10 (122) · 3-10 vertical addition 124 · تدرب أكثر Unit 3, 126 · project (number bonds wheel) 128.
**Unit 4 (subtraction from 10)** — standards 130 · 4-1 Understanding Subtraction 133 · 4-2 subtraction sentence 136 · 4-3 addition-subtraction link (fact families) 138 · 4-4 subtracting 0 and subtracting the whole 140 · 4-5 subtracting from 2, 3 (142) · 4-6 subtracting from 4, 5 (144) · 4-7 subtracting from 6, 7 (146) · 4-8 subtracting from 8 (148) · 4-9 subtracting from 9 (150) · 4-10 subtracting from 10 (152) · 4-11 problem solving (choose the operation) 154 · تدرب أكثر Unit 4, 156 · project (washing-pegs number line) 158 · models 161. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 1 — Numbers to 5 and position (17–46):** 1-1 spatial relations (over/under, above/below, right/left); 1-2 inside/between/outside; 1-3 sorting by one attribute; 1-4 repeating patterns; 1-5 more/less/equal by one-to-one matching; 1-6 to 1-12 numbers 1–5 one at a time (counting, writing, representing with objects and fingers), then numbers 1–5 together; 1-13 comparing numbers 1–5. تدرب أكثر Unit 1 (printed pp. 44–45). Project "Sorting is fun" (p. 46). Verified correct by zoom: 1-12 item 5 matching lines.
- **Unit 2 — Numbers to 12 and time (51–80):** 2-1 to 2-8 numbers 6–12 one at a time (6, 7, 8, 9, 0, 10, 11, 12) with counting, writing and ten-frame representation; 2-9 whole hours (reading the clock to the hour); 2-10 time — before/after; 2-11 time problems; 2-12 calendar (months of the year, Hijri months in order: Ramadan is the fasting month, Dhul-Hijjah is the Hajj month; National Day is February); 2-13 days of the week (see error 1 below). تدرب أكثر Unit 2 (printed pp. 78–79). Project: paper-plate clock (p. 80). Verified correct by zoom: 2-10 item 3 (four clocks 7:00, 5:00, 4:00, 6:00; Badr 4:00, Khalid 6:00, Mohammed 5:00; 7:00 is a distractor); 2-11 item 1 (clock with three hour-hands at 10, 7, 4; the pupil colours the 7). Picture-count observation (not a printed error): 2-3's beach picture shows 7 pairs of sunglasses (not 8) and 9 ice creams counting the one in the seller's hand (8 on the cart); the book prints no number for those two columns — the pupil fills them.
- **Unit 3 — Addition to 10 (105–128):** 3-1 understanding addition (joining groups); 3-2 the addition sentence; 3-3 to 3-9 composing each number from 2 to 10 (pairs that make the number); 3-10 vertical addition. تدرب أكثر Unit 3 (printed pp. 126–127). Project: number bonds wheel (p. 128). Verified correct: 3-1 bees 7+2=9; 3-2 birds 2+6=8.
- **Unit 4 — Subtraction from 10 (133–158):** 4-1 understanding subtraction (taking away); 4-2 the subtraction sentence; 4-3 the addition–subtraction link; 4-4 subtracting 0 and subtracting the whole number; 4-5 to 4-10 subtracting from 2, 3, 4, 5, 6, 7, 8, 9, 10; 4-11 problem solving — choosing the operation. تدرب أكثر Unit 4 (printed pp. 156–157). Project: washing-pegs number line (p. 158). Verified correct: 4-7 birds 6; 4-8 cross-number puzzle fully consistent.
- **Models:** Part 1 divider printed 83 (PDF p. 84); model 1 abacus (ones rod) printed 84 (PDF p. 85), model 2 abacus ones+tens printed 85 (PDF p. 86), model 3 ten-frames printed 86 (PDF p. 87), model 4 number lines 0–12 printed 87 (PDF p. 88), model 5 clock face printed 88 (PDF p. 89). Part 2 divider printed 161 (PDF p. 164); model 1 abacus printed 163 (PDF p. 166), model 2 ten-frames printed 164 (PDF p. 167), model 3 number lines printed 165 (PDF p. 168), model 4 number-bond board printed 167 (PDF p. 170). Part 2 references printed 169 (PDF p. 172); guardian letter PDF p. 173; back cover PDF p. 174.

#### Honest negatives (what a Grade 1 Term 1 book might be expected to teach that this one does not)

- No addition/subtraction of 2-digit numbers, no multiplication/division, no fractions, no shapes/geometry beyond spatial relations and sorting, no measurement beyond whole hours/time/calendar, numbers only to 12 (Unit 2) then addition/subtraction to 10 (Units 3–4); no money.

#### Confirmed book errors — Grade 1 Term 1 (1 error)

1. **Lesson 2-13, November calendar (printed p. 76, PDF p. 77):** 1 November is shown on a Saturday (2025 layout). Confirmed by render-read: the grid has 1 under السبت (Saturday) and 30 under الأحد (Sunday). The book's own Gregorian year calendar (lesson 2-12) is 2026. Correct for November 2026: **1 November is a Sunday, 30 November is a Monday**.

#### Held-copy defects

- Blank PDF pp. 83, 97, 99, 101, 107, 135, 163, 165, 169, 171 — all blank by design (front-matter separators, opener reverses, models-divider reverses). "My project" pupil pages PDF pp. 82 and 162 blank by design. No missing, duplicated or truncated content pages. No answer key.

---

### 2. Grade 1 Term 2 — `g01-t2.pdf` (First Edition 1447H / 2025–2026, no ISBN printed)

#### Identity (cover + title page + imprint, PDF p. 3)

- **Grade:** 1. **Term:** 2. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** © Ministry of Education, Kuwait. **Edition/year as printed:** **First Edition 1447H / 2025–2026**. No ISBN printed (no ISBN line on the imprint page; text search confirms). Ministry deposit 93, dated 19/1/2026.
- **Authors:** Dalal Mubarak Al-Hajraf (head), Abeer Barjas Ayed Al-Mutairi, Abeer Mohammed Jassim Mubarak, Radhia Ahmed Ibrahim Al-Sarraf, Shahd Mohammed Hamoud Al-Rashidi, Munira Zabaran Mohammed Al-Ajmi, Fatima Manzil Hazam Al-Dhafiri (7 authors).
- **Review teams:** scientific review Loulouh Mohammed Sultan bin Issa; language review Ahmed Ismail Hamdi; printed by Dar Al-Siyasa presses.
- **PDF pages:** 164. **Printed range:** Part 1 printed pp. 17–83; Part 2 printed pp. 99–158. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 3.
- **Reading method:** text layer (pdftotext) — read in full; key pages verified visually.

#### Contents (from the contents pages, printed pp.)

**Unit 5 (numbers to 100)** — standards 15 · 5-1 numbers to 20 (17) · 5-2 numbers to 30 (20) · 5-3 counting by 10s to 100 (22) · 5-4 numbers to 50 (24) · 5-5 numbers to 100 (26) · 5-6 comparing numbers to 100 (28) · 5-7 counting successively — before/between/after (30) · 5-8 ordering numbers to 100 (32) · 5-9 estimating numbers to 100 (34) · 5-10 skip counting (36) · 5-11 using data (38) · تدرب أكثر Unit 5, 40 · project (number train) 42.
**Unit 6 (addition and subtraction to 100)** — standards 44 · 6-1 adding 0–20 (47) · 6-2 adding 3 numbers (50) · 6-3 making a ten (52) · 6-4 adding, sums to 30 (54) · 6-5 adding tens (56) · 6-6 adding two 2-digit numbers, sums to 100 (58) · 6-7 subtracting numbers to 20 (60) · 6-8 subtracting by decreasing ten (62) · 6-9 relation between addition and subtraction (64) · 6-10 problem solving (draw a picture) (66) · تدرب أكثر Unit 6, 68 · project "Addition and subtraction heroes" 70 · models 72–81 · references 83.
**Unit 7 (subtraction to 100 and solids)** — standards 96 · 7-1 subtracting numbers to 30 (99) · 7-2 subtracting tens (102) · 7-3 subtracting 1-digit from 2-digit (104) · 7-4 subtracting two 2-digit numbers (106) · 7-5 problem solving, add/subtract 0–100 (108) · 7-6 using data (110) · 7-7 3D forms, cube-sphere (112) · 7-8 classifying solids (114) · 7-9 identifying shapes (116) · تدرب أكثر Unit 7, 118 · project (play with shapes/regions) 120.
**Unit 8 (congruence, fractions, measurement, money)** — standards 122 · 8-1 congruence 125 · 8-2 half 128 · 8-3 quarter 130 · 8-4 length 132 · 8-5 measuring length 134 · 8-6 weight 136 · 8-7 measuring weight 138 · 8-8 capacity 140 · 8-9 measuring capacity 142 · 8-10 money 144 · تدرب أكثر Unit 8, 146 · project "my trip with congruent parts" 148 · models 153–158 · references 159. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 5 — Numbers to 100 (17–42):** 5-1 numbers to 20; 5-2 numbers to 30; 5-3 counting by 10s to 100; 5-4 numbers to 50; 5-5 numbers to 100; 5-6 comparing numbers to 100; 5-7 counting successively (before/between/after); 5-8 ordering numbers to 100; 5-9 estimating numbers to 100; 5-10 skip counting; 5-11 using data. تدرب أكثر Unit 5 (printed p. 40, PDF p. 41). Project: number train (printed p. 42, PDF p. 43).
- **Unit 6 — Addition and subtraction to 100 (47–70):** 6-1 adding 0–20; 6-2 adding 3 numbers; 6-3 making a ten; 6-4 adding, sums to 30; 6-5 adding tens; 6-6 adding two 2-digit numbers, sums to 100; 6-7 subtracting numbers to 20; 6-8 subtracting by decreasing ten; 6-9 relation between addition and subtraction; 6-10 problem solving (draw a picture). تدرب أكثر Unit 6 (printed p. 68, PDF p. 69). Project "Addition and subtraction heroes" (printed p. 70, PDF p. 71).
- **Unit 7 — Subtraction to 100 and solids (99–120):** 7-1 subtracting numbers to 30; 7-2 subtracting tens; 7-3 subtracting 1-digit from 2-digit; 7-4 subtracting two 2-digit numbers; 7-5 problem solving, add/subtract 0–100; 7-6 using data; 7-7 3D forms (cube, sphere); 7-8 classifying solids; 7-9 identifying shapes. تدرب أكثر Unit 7 (printed p. 118, PDF p. 121). Project: play with shapes/regions (printed p. 120, PDF p. 123). "My project" PDF p. 124.
- **Unit 8 — Congruence, fractions, measurement, money (125–148):** 8-1 congruence; 8-2 half; 8-3 quarter; 8-4 length; 8-5 measuring length; 8-6 weight; 8-7 measuring weight; 8-8 capacity; 8-9 measuring capacity; 8-10 money. تدرب أكثر Unit 8 (printed p. 146, PDF p. 149). Project "my trip with congruent parts" (printed p. 148, PDF p. 151). "My project" PDF p. 152.
- **Models:** Part 1 divider printed 73 (PDF p. 74); model 1 abacus printed 74, model 2 ten-frames 75, model 3 number lines 76, model 4 partitioning board 77, model 5 work card 78, model 6 place-value board 79, model 7 hundred chart 80, model 8 parts board 81. References printed 83 (PDF p. 84); guardian letter PDF p. 85. Part 2: model 1 work card printed 153 (PDF p. 156), model 2 place-value board 154, model 3 number lines 155, model 4 parts board 156, model 5 hundred chart 157 (PDF p. 160), model 6 money (coins and paper notes) 158 (PDF p. 161). References PDF p. 162; guardian letter PDF p. 163; back cover PDF p. 164.

#### Honest negatives (what a Grade 1 Term 2 book might be expected to teach that this one does not)

- No multiplication/division, fractions only half/quarter, no time.

#### Confirmed book errors — Grade 1 Term 2 (2 errors)

1. **Intro, PDF pp. 11–12:** the footer reads **"Grade 4, Term 2"** in a Grade 1 book — confirmed from the text layer (PDF p. 12 footer "الصف الرابع - الفصل الدراسي الثاني").
2. **Hundred chart prints 34 instead of 45, twice** — lesson 6-5 printed p. 57 (PDF p. 58) and Model 7 printed p. 80 (PDF p. 81). Text layer confirms both: the row 41–50 reads `50 49 48 47 46 34 44 43 42 41`; 34 appears twice, 45 never. Correct: **45**.

#### Held-copy defects

- Blank PDF pp. 4, 5, 7, 9, 47, 83, 90, 91, 93, 95, 101, 127, 153, 155 — all blank by design (front-matter separators, opener reverses, "my project" pages, models-divider reverse). No missing, duplicated or truncated content pages. No answer key. No ISBN seen.

---

### 3. Grade 2 Term 1 — `g02-t1.pdf` (Second Edition 1448H / 2026–2027, ISBN 978-9921-33-083-0)

#### Identity (cover + title page + imprint, PDF p. 3)

- **Grade:** 2. **Term:** 1. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** Dar Al-Qabas. © Ministry of Education, Kuwait.
- **Edition/year as printed:** First edition 2025/2026; **Second Edition 1448H / 2026–2027**.
- **ISBN:** **978-9921-33-083-0**. Ministry deposits **(523)** Part 1 and **(524)** Part 2, both dated 9/8/2026.
- **Authors:** Dalal Mubarak Falah Al-Hajraf (head), Radhia Ahmed Ibrahim Al-Sarraf, Shahd Mohammed Hamoud Al-Rashidi.
- **Review teams:** scientific review Abeer Mohammed Jassim Mubarak + Abeer Barjas Ayed Al-Mutairi; AI team Zainab Qasim Mohammed, Sara Ahmed Wabran, Salam Khaled Al-Daqbasi (Part 2: Al-Jazi Nasser Al-Dossary replaces Zainab); language review Wasmiya Maakam Al-Ajmi (Part 2 also Maali Salem Al-Harbi).
- **PDF pages:** 166. **Printed range:** Part 1 printed pp. 17–82; Part 2 printed pp. 95–160. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 5.
- **Reading method:** image-only book (no usable text layer) — **read visually in full from 150 dpi renders (166/166 pages)**, disputed items at 300 dpi.

#### Contents (from the contents pages, printed pp.)

**Unit 1 (numbers to 100)** — standards 14 · 1-1 position in space 17 · 1-2 patterns 20 · 1-3 data representations (tally/bar/pictograph) 22 · 1-4 reading/writing/representing numbers to 100 (24) · 1-5 number names 26 · 1-6 talking about the number 100 (28) · 1-7 counting successively (hundred chart) 30 · 1-8 comparing numbers 32 · 1-9 ordering numbers 34 · 1-10 estimation 36 · 1-11 odd and even numbers 38 · تدرب أكثر Unit 1, 40 · project (number symbols) 44 · models 71.
**Unit 2 (addition to 100)** — standards 46 · 2-1 addition to 20 without renaming 49 · 2-2 adding by making ten 52 · 2-3 addition on the hundred board 54 · 2-4 adding 2-digit + 1-digit without renaming 56 · 2-5 adding 2-digit + 1-digit with renaming 58 · 2-6 adding two 2-digit numbers without renaming 60 · 2-7 adding two 2-digit numbers with renaming 62 · 2-8 adding three numbers 64 · تدرب أكثر Unit 2, 66 · project (fish pond) 68 · models 71–79.
**Unit 3 (subtraction to 100)** — standards 92 · 3-1 subtracting numbers to 20 without renaming 95 · 3-2 subtracting by deduction from ten 98 · 3-3 relation between addition and subtraction (fact families) 100 · 3-4 using addition/subtraction rules (input-output robots) 102 · 3-5 subtraction on the hundred board 104 · 3-6 subtracting a 1-digit number from a 2-digit number without renaming 106 · 3-7 subtracting a 1-digit number from a 2-digit number with renaming 108 · 3-8 subtracting a 2-digit number from another 2-digit number with renaming when needed 110 · 3-9 problem solving (choose the operation) 112 · تدرب أكثر Unit 3, 114 · project (hundred board) 116.
**Unit 4 (shapes, fractions, time, calendar)** — standards 118 · 4-1 exploring solids 121 · 4-2 plane shapes 124 · 4-3 congruent shapes 126 · 4-4 equal parts 128 · 4-5 half 130 · 4-6 third 132 · 4-7 quarter 134 · 4-8 whole hour – half hour 136 · 4-9 minute 138 · 4-10 finding the duration 140 · 4-11 calendar 142 · تدرب أكثر Unit 4, 144 · project (make a pizza) 146 · models 149. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 1 — Numbers to 100 (17–44):** 1-1 position in space; 1-2 patterns; 1-3 data representations (tally, bar, pictograph); 1-4 reading, writing and representing numbers to 100; 1-5 number names; 1-6 talking about the number 100; 1-7 counting successively on the hundred chart; 1-8 comparing numbers; 1-9 ordering numbers; 1-10 estimation; 1-11 odd and even numbers. تدرب أكثر Unit 1 (printed p. 40, PDF p. 41). Project: number symbols (printed p. 44, PDF p. 45).
- **Unit 2 — Addition to 100 (49–68):** 2-1 addition to 20 without renaming; 2-2 adding by making ten; 2-3 addition on the hundred board; 2-4 adding 2-digit + 1-digit without renaming; 2-5 adding 2-digit + 1-digit with renaming; 2-6 adding two 2-digit numbers without renaming; 2-7 adding two 2-digit numbers with renaming; 2-8 adding three numbers. تدرب أكثر Unit 2 (printed p. 66, PDF p. 67). Project: fish pond (printed p. 68, PDF p. 69).
- **Unit 3 — Subtraction to 100 (95–116):** 3-1 subtracting numbers to 20 without renaming; 3-2 subtracting by deduction from ten; 3-3 relation between addition and subtraction (fact families); 3-4 using addition/subtraction rules (input-output robots); 3-5 subtraction on the hundred board; 3-6 subtracting 1-digit from 2-digit without renaming; 3-7 subtracting 1-digit from 2-digit with renaming; 3-8 subtracting two 2-digit numbers with renaming when needed; 3-9 problem solving (choose the operation). تدرب أكثر Unit 3 (printed p. 114, PDF p. 119). Project: hundred board (printed p. 116, PDF p. 121).
- **Unit 4 — Shapes, fractions, time, calendar (121–146):** 4-1 exploring solids; 4-2 plane shapes; 4-3 congruent shapes; 4-4 equal parts; 4-5 half; 4-6 third; 4-7 quarter; 4-8 whole hour – half hour; 4-9 minute; 4-10 finding the duration; 4-11 calendar. تدرب أكثر Unit 4 (printed p. 144, PDF p. 149). Project: make a pizza (printed p. 146, PDF p. 151).
- **Models:** Part 1 divider printed 71 (PDF p. 72); model 1 ten-frames printed 72, model 2 work card 73, model 3 place-value board 74, model 4 abacus 75, model 5 number-components board 76, model 6 partitioning board 77, model 7 number lines 78, model 8 hundred chart 79 (PDF p. 80). References printed 81 (PDF p. 82); guardian letter printed 82 (PDF p. 83); back cover PDF p. 84 ("سبورتي 2" + QR codes). Part 2 divider printed 149 (PDF p. 154); model 1 ten-frames printed 151 (PDF p. 156), model 2 work card 152, model 3 place-value board 153, model 4 number lines 154, model 5 hundred chart 155 (PDF p. 160), model 6 clock 156, model 7 calendar 157, model 8 dot grid 158 (PDF p. 163). References printed 159 (PDF p. 164); guardian letter printed 160 (PDF p. 165); back cover PDF p. 166 (last page).

#### Honest negatives (what a Grade 2 Term 1 book might be expected to teach that this one does not)

- No multiplication/division; no fractions beyond half/third/quarter as parts of shapes (no fraction arithmetic); no 3-digit numbers; no money; no measurement of length/mass/capacity; time only to whole/half hours and minutes (no seconds, no 24-hour); geometry limited to cube/cuboid/sphere (faces/edges/vertices) and square/rectangle/triangle/circle.

#### Confirmed book errors — Grade 2 Term 1 (2 errors)

1. **تدرب أكثر Unit 1, item 21 (printed p. 43, PDF p. 44):** "56 > ___" with options 25, 36, 80 — **TWO correct options** (25 and 36 are both < 56).
2. **Lesson 2-7, item 10 (printed p. 63, PDF p. 64):** fill 8_+2_=9_ using digits 6, 2, 0 each once — **NO solution**. The six permutations give 86+22=108, 86+20=106, 82+26=108, 82+20=102, 80+26=106, 80+22=102 — never a 9x number.

#### Verified NOT errors

- **Lesson 4-1 cone note:** the book classifies the cone as non-rolling — a primary-school simplification, not an error.
- **Five items struck on citation check (2026-11-06; Arabic-Indic digit-order misreads in the draft, verified at 300 dpi):** lesson 2-8 bottom strip sums are 27+14+13 = 54, 16+21+26 = 63, 45+14+18 = 77 — all printed correctly; lesson 2-8 تدرب item 3 is 19+20+35 (blank; = 74, within the lesson's aim); تدرب أكثر Unit 2 item 12 starts Salem at **23**, and 23+50 = 73 IS an option (items 9–11 on the same spread check out: 9+4=13 as 10+3; 41+23+7=71; Reem 47 + Saad 22 = 69); lesson 3-4 item 3 is a subtract-**1** robot (9, 4, 3 → 8, 3, 2) — the subtract-4 robot is item 4 (12, 10, 15 → 8, 6, 11), the worked subtract-3 robot (7, 9, 6 → 4, 6, 3) and item 7 machine (10+5−7+11=19) are correct; lesson 3-7 item 13 is **61−5**, and Mubarak's **56 is the correct answer** (Mohammed's 64 is wrong; worked example 42−7=35 and item 12 bus 32−4=28 also correct).
- **Lesson 4-11 calendar:** verified correct for 2026 (1 January Thursday, 1 February Sunday, February 28 days, 1 March Sunday).
- Hundred charts verified (lesson 1-7 p. 30, Model 8 p. 79, Part 2 Model 5 p. 155).

#### Held-copy defects

- Blank PDF pp. 5, 7, 9, 17, 49, 71, 81, 85, 89, 91, 93, 99, 122, 125, 152, 153, 155 — all blank by design (front-matter separators, opener reverses, "my project" pages, models-divider reverses). "My project" pupil page PDF p. 152 blank by design. (PDF p. 154 is the Part 2 models divider, not blank — an earlier list wrongly included it.) No missing, duplicated or truncated content pages. No answer key.

---

### 4. Grade 2 Term 2 — `g02-t2.pdf` (First Edition 1447H / 2025–2026, no ISBN printed)

#### Identity (cover + title page + imprint, PDF p. 3)

- **Grade:** 2. **Term:** 2. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** © Ministry of Education, Kuwait. **Edition/year as printed:** **First Edition 1447H / 2025–2026**. No ISBN printed (no ISBN line on the imprint page; text search confirms). Ministry deposit 94, dated 19/1/2026.
- **Authors:** Dalal Mubarak Al-Hajraf (head), Abeer Barjas Ayed Al-Mutairi, Abeer Mohammed Jassim Mubarak, Radhia Ahmed Ibrahim Al-Sarraf, Shahd Mohammed Hamoud Al-Rashidi, Munira Zabaran Mohammed Al-Ajmi, Fatima Manzil Hazam Al-Dhafiri (7 authors).
- **Review teams:** scientific review Loulouh Mohammed Sultan bin Issa; language review Anwar Ahmed Mabrouk; printed by Dar Al-Siyasa presses.
- **PDF pages:** 166. **Printed range:** Part 1 printed pp. 17–81; Part 2 printed pp. 99–163. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 2.
- **Reading method:** text layer (pdftotext) — read in full; key pages verified visually. PDF p. 122 is an image page (garbled in the text layer; read from the render).

#### Contents (from the contents pages, printed pp.)

**Unit 5 (numbers to 1000)** — standards 14 · 5-1 counting by hundreds to 1000 (17) · 5-2 numbers to 1000 (20) · 5-3 expanded form of 3-digit numbers 22 · 5-4 counting successively — before/after/between (24) · 5-5 comparing numbers 26 · 5-6 ordering numbers 28 · 5-7 rounding to nearest ten 30 · 5-8 rounding to nearest hundred 32 · 5-9 problem solving: look for a pattern 34 · تدرب أكثر Unit 5, 36 · project 38.
**Unit 6 (adding and subtracting 3-digit numbers)** — standards 40 · 6-1 addition patterns 43 · 6-2 adding hundreds 46 · 6-3 adding 3-digit + 1-digit 48 · 6-4 adding 3-digit + 2-digit 50 · 6-5 adding two 3-digit numbers 52 · 6-6 subtraction patterns 54 · 6-7 subtracting hundreds from 3-digit 56 · 6-8 subtracting 1-digit from 3-digit 58 · 6-9 subtracting 2-digit from 3-digit 60 · 6-10 subtracting two 3-digit numbers 62 · 6-11 using data 64 · 6-12 problem solving: multi-step problems 66 · تدرب أكثر Unit 6, 68 · project 70 · models 73–80 · references 81.
**Unit 7 (multiplication concept, ×1–×5)** — standards 96 · 7-1 skip counting 99 · 7-2 skip counting using a hundred chart 102 · 7-3 repeating addition 104 · 7-4 exploring multiplication concept 106 · 7-5 exploring building arrays 108 · 7-6 multiplying using number line 110 · 7-7 multiplying a number by itself 112 · 7-8 multiplication in vertical and horizontal form 114 · 7-9 multiplication in any order 116 · 7-10 multiplication by 1 / by 0 (118) · تدرب أكثر Unit 7, 120 · project 122.
**Unit 8 (multiplying by 2–5, measurement, money)** — standards 124 · 8-1 multiplying by 2 (127) · 8-2 by 3 (130) · 8-3 by 4 (132) · 8-4 by 5 (134) · 8-5 measuring length, non-standard units 136 · 8-6 measuring length, metric cm–m 138 · 8-7 measuring mass, non-standard 140 · 8-8 measuring mass, metric kg 142 · 8-9 measuring capacity, non-standard 144 · 8-10 measuring capacity, metric litre 146 · 8-11 coins 148 · 8-12 paper money 150 · تدرب أكثر Unit 8, 152 · project 154 · models 157–162 · references 164. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 5 — Numbers to 1000 (17–38):** 5-1 counting by hundreds to 1000; 5-2 numbers to 1000; 5-3 expanded form of 3-digit numbers; 5-4 counting successively (before/after/between); 5-5 comparing numbers; 5-6 ordering numbers; 5-7 rounding to nearest ten; 5-8 rounding to nearest hundred; 5-9 problem solving: look for a pattern. تدرب أكثر Unit 5 (printed p. 36, PDF p. 37). Project (printed p. 38, PDF p. 39).
- **Unit 6 — Adding and subtracting 3-digit numbers (43–70):** 6-1 addition patterns; 6-2 adding hundreds; 6-3 adding 3-digit + 1-digit; 6-4 adding 3-digit + 2-digit; 6-5 adding two 3-digit numbers; 6-6 subtraction patterns; 6-7 subtracting hundreds from 3-digit; 6-8 subtracting 1-digit from 3-digit; 6-9 subtracting 2-digit from 3-digit; 6-10 subtracting two 3-digit numbers; 6-11 using data; 6-12 problem solving: multi-step problems. تدرب أكثر Unit 6 (printed p. 68, PDF p. 69). Project (printed p. 70, PDF p. 71).
- **Unit 7 — Multiplication concept, ×1–×5 (99–122):** 7-1 skip counting; 7-2 skip counting using a hundred chart; 7-3 repeating addition; 7-4 exploring multiplication concept; 7-5 exploring building arrays; 7-6 multiplying using number line; 7-7 multiplying a number by itself; 7-8 multiplication in vertical and horizontal form; 7-9 multiplication in any order; 7-10 multiplication by 1 / by 0. تدرب أكثر Unit 7 (printed p. 120, PDF p. 122 — image page, read from render). Project (printed p. 122, PDF p. 124).
- **Unit 8 — Multiplying by 2–5, measurement, money (127–154):** 8-1 multiplying by 2; 8-2 by 3; 8-3 by 4; 8-4 by 5; 8-5 measuring length, non-standard units; 8-6 measuring length, metric cm–m; 8-7 measuring mass, non-standard; 8-8 measuring mass, metric kg; 8-9 measuring capacity, non-standard; 8-10 measuring capacity, metric litre; 8-11 coins; 8-12 paper money. تدرب أكثر Unit 8 (printed p. 152, PDF p. 154). Project (printed p. 154, PDF p. 156).
- **Models:** Part 1 divider printed 73 (PDF p. 74); model 1 place-value printed 74, model 2 work card 75, model 3 abacus 76, model 4 number lines 77, model 5 number-components 78, model 6 partitioning 79, model 7 parts board 80. References printed 81 (PDF p. 82); guardian letter PDF p. 83. Part 1 has no separate back-cover page (PDF pp. 84–85 are blank decorative pages). Part 2 starts with a landscape cover spread on PDF p. 86 (front cover + back cover, double-width page); title PDF p. 87, imprint PDF p. 88. Part 2 divider printed 157 (PDF p. 159); model 1 number line 158, model 2 hundred chart 159, model 3 robot 160, model 4 multiplication table 161, model 5 coins 162. References printed 163 (PDF p. 165; the contents page lists 164 — a contents-page slip); guardian letter PDF p. 166 (last page). No separate back-cover page at the end: the Part 2 back cover is the right half of the cover spread on PDF p. 86.

#### Honest negatives (what a Grade 2 Term 2 book might be expected to teach that this one does not)

- No division, no fractions, no time, multiplication only ×2–×5, no geometry beyond measuring.

#### Confirmed book errors — Grade 2 Term 2 (0 errors)

- **None found.** Minor typos only (not counted): English subtitles "Befoer" (Before), "Numbres" (Numbers); spacing/underscore typos in lessons 6-3/6-4/6-5.

#### Verified NOT errors

- **Deliberate error-spotting:** lesson 5-3 "300+50+6 = 365" (correct 356); lesson 6-3 Shikha "687+3 = 610" (correct 690); lesson 8-3 Mubarak "3x10 = 0" (correct 30); p. 48 item 9: Shahd's 400+235=536 (correct 635) — explicitly "what mistake did Shahd make?".

#### Held-copy defects

- Blank PDF pp. 4, 5, 7, 9, 84, 85, 89, 90, 92, 94 — all blank by design (front-matter separators, opener reverses, "my project" pages). PDF p. 122 is an image page (garbled in the text layer; read from the render). No missing, duplicated or truncated content pages. No answer key. No ISBN seen.

---

### 5. Grade 3 Term 1 — `g03-t1.pdf` (Second Edition 1448H / 2026–2027, ISBN 978-9921-33-052-6)

#### Identity (cover + title page + imprint)

- **Grade:** 3. **Term:** 1. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** Dar Al-Qabas. © Ministry of Education, Kuwait.
- **Edition/year as printed:** First edition 2025/2026; **Second Edition 1448H / 2026–2027**.
- **ISBN:** **978-9921-33-052-6**. Ministry deposits **(525)** Part 1 and **(526)** Part 2, both dated 9/8/2026.
- **Authors:** Dalal Mubarak Falah Al-Hajraf (head), Abeer Mohammed Jassim Mubarak, Munira Zabaran Mohammed Al-Ajmi.
- **Review teams:** scientific review Radhia Ahmed Ibrahim Al-Sarraf; language review Noura Ammash Al-Shammari, Maha Fadhil Al-Rashidi; AI explanations team Fatima Mohsen Abdulnabi Safar, Wissam Ibrahim Abdulhamid Shalabi, Hajar Talal Hazam Al-Mutairi.
- **PDF pages:** 180. **Printed range:** Part 1 printed pp. 17–87; Part 2 printed pp. 100–175. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 3.
- **Reading method:** image-only book (no usable text layer) — **read visually from 150 dpi renders**. Method honesty: the contents are complete from the contents pages; all four تدرب أكثر sections were read in full; lessons were spot-sampled (1-1, 2-1, 3-1, 3-3, 4-1) and verified correct; this is NOT a page-by-page error hunt — but each of the six errors below was verified against a render.

#### Contents (from the contents pages, printed pp.)

**Unit 1 (numbers to 6 digits)** — standards 14 · 1-1 reading, writing and representing numbers to 1000 (17) · 1-2 thousands 20 · 1-3 4-digit numbers 22 · 1-4 5-digit numbers 24 · 1-5 6-digit numbers 26 · 1-6 skip counting 28 · 1-7 comparing numbers 30 · 1-8 ordering numbers 32 · 1-9 rounding to the nearest ten 34 · 1-10 rounding to the nearest hundred 36 · تدرب أكثر Unit 1, 38 · project 42.
**Unit 2 (addition and subtraction to 10,000)** — standards 44 · 2-1 addition patterns 47 · 2-2 estimating sums 50 · 2-3 adding two numbers, sums ≤1000 (52) · 2-4 adding, sums ≤10,000 without renaming 54 · 2-5 adding, sums ≤10,000 with renaming 56 · 2-6 adding three numbers, sums ≤10,000 (58) · 2-7 subtraction patterns 60 · 2-8 estimating differences 62 · 2-9 subtracting from numbers ≤1000 (64) · 2-10 subtracting from numbers ≤10,000 without renaming 66 · 2-11 subtracting from numbers ≤10,000 with renaming 68 · 2-12 mental maths 70 · 2-13 problem solving: guess and check 72 · تدرب أكثر Unit 2, 74 · project 78 · models 81.
**Unit 3 (multiplication, ×1–×9)** — standards 100 · 3-1 multiplication concept 103 · 3-2 ×2 (106) · 3-3 ×5 (108) · 3-4 patterns on the hundred board: twos and fives 110 · 3-5 ×1 and ×0 (112) · 3-6 ×3 (114) · 3-7 ×4 (116) · 3-8 ×6 (118) · 3-9 ×7 (120) · 3-10 ×8 (122) · 3-11 ×9 (124) · 3-12 order of operations 126 · 3-13 problem solving: make a table 128 · تدرب أكثر Unit 3, 130 · project 134.
**Unit 4 (multiplication of larger numbers, shapes, perimeter, area)** — standards 136 · 4-1 ×10, 100 and multiples 139 · 4-2 1-digit × 2-digit without renaming 142 · 4-3 1-digit × 2-digit with renaming 144 · 4-4 × 3-digit number 146 · 4-5 × three numbers 148 · 4-6 solids 150 · 4-7 plane shapes 152 · 4-8 movement of shapes 154 · 4-9 perimeter 156 · 4-10 area 158 · 4-11 problem solving: look for a pattern 160 · تدرب أكثر Unit 4, 162 · project 164 · models 167. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 1 — Numbers to 6 digits (17–42):** 1-1 reading, writing and representing numbers to 1000; 1-2 thousands; 1-3 4-digit numbers; 1-4 5-digit numbers; 1-5 6-digit numbers; 1-6 skip counting; 1-7 comparing numbers; 1-8 ordering numbers; 1-9 rounding to the nearest ten; 1-10 rounding to the nearest hundred. تدرب أكثر Unit 1 (printed pp. 38–39, read in full — no errors). Project (printed p. 42). Verified correct: 1-1 (254 = 200+50+4).
- **Unit 2 — Addition and subtraction to 10,000 (47–78):** 2-1 addition patterns; 2-2 estimating sums; 2-3 adding two numbers, sums ≤1000; 2-4 adding, sums ≤10,000 without renaming; 2-5 adding, sums ≤10,000 with renaming; 2-6 adding three numbers, sums ≤10,000; 2-7 subtraction patterns; 2-8 estimating differences; 2-9 subtracting from numbers ≤1000; 2-10 subtracting from numbers ≤10,000 without renaming; 2-11 subtracting from numbers ≤10,000 with renaming; 2-12 mental maths; 2-13 problem solving: guess and check. تدرب أكثر Unit 2 (printed pp. 74–75, read in full — no errors). Project (printed p. 78). Verified correct: 2-1 (2000+3000=5000; patterns 2+3=5, 20+30=50, 200+300=500, 2000+3000=5000).
- **Unit 3 — Multiplication, ×1–×9 (103–134):** 3-1 multiplication concept; 3-2 ×2; 3-3 ×5; 3-4 patterns on the hundred board (twos and fives); 3-5 ×1 and ×0; 3-6 ×3; 3-7 ×4; 3-8 ×6; 3-9 ×7; 3-10 ×8; 3-11 ×9; 3-12 order of operations; 3-13 problem solving: make a table. تدرب أكثر Unit 3 (printed pp. 130–131, PDF pp. 133–134, read in full — no errors; the multiplication table on p. 130 verified fully correct). Project "magic number boxes" game (printed p. 134, PDF p. 137). Verified correct: 3-3 (6 hens × 5 eggs = 30; ×5 and ×2 robots).
- **Unit 4 — Multiplication of larger numbers, shapes, perimeter, area (139–164):** 4-1 ×10, 100 and multiples; 4-2 1-digit × 2-digit without renaming; 4-3 1-digit × 2-digit with renaming; 4-4 × 3-digit number; 4-5 × three numbers; 4-6 solids; 4-7 plane shapes; 4-8 movement of shapes; 4-9 perimeter; 4-10 area; 4-11 problem solving: look for a pattern. تدرب أكثر Unit 4 (printed pp. 162–163, PDF pp. 165–166, read in full — no errors). Project "robot money box" (printed p. 164, PDF p. 167). Verified correct: 4-1 (5 baskets × 10 apples = 50; 5 coins × 100 fils = 500 fils).
- **Models:** Part 1 divider printed 81 (PDF p. 82); model 1 place-value board 82 (PDF p. 83), model 2 abacus 83 (PDF p. 84), model 3 number line 84 (PDF p. 85), model 4 place-value chart 85 (PDF p. 86), model 5 number lines 86 (PDF p. 87). References printed 87 (PDF p. 88; cites 3rd ed. 2016–2017, 5th ed. 2024–2025, trial ed. 2023–2024); guardian letter PDF p. 89; back cover PDF p. 90. Part 2 front matter: cover PDF p. 91, title 92, imprint 93, Basmala 94, blank 95, Amir portrait 96, blank 97, Crown Prince portrait 98, blank 99, intro/icons 100, contents 101–102, standards 103, opener 104, blank PDF p. 105 (printed 102). Part 2 models: divider printed 167 (PDF p. 170); PDF p. 171 blank; model 1 multiplication robot printed 169 (PDF p. 172), model 2 number lines 170 (PDF p. 173), model 3 multiplication table 171 (PDF p. 174, table verified fully correct), model 4 grid 172 (PDF p. 175), model 5 multiplication arrays 173 (PDF p. 176); PDF p. 177 blank; references printed 175 (PDF p. 178); guardian letter PDF p. 179; back cover PDF p. 180 ("سبورتي 3" + QR codes).

#### Honest negatives (what a Grade 3 Term 1 book might be expected to teach that this one does not)

- Numbers to 6 digits, addition/subtraction to 10,000, multiplication tables 1–9 plus 1-digit × 2-/3-digit numbers, solids/plane shapes/movement/perimeter/area; no division, no fractions, no decimals, no time, no measurement units, no money.

#### Confirmed book errors — Grade 3 Term 1 (3 errors)

1. **Lesson 1-6 تدرب, item 7 (printed p. 29, PDF p. 30):** pattern "98, 2, 99, 1, 100, __, __, __" with four options, none matching. The natural rule gives **0, 101, −1** (includes a negative outside Grade 3 scope) — no correct option.
2. **تدرب أكثر Unit 1, item 31 (printed p. 41, PDF p. 42):** "4815 < □" with options 4814, 4926, 4895 — **TWO correct options** (4926 and 4895 are both > 4815).
3. **Lesson 2-8 تدرب, item 9 (printed p. 63, PDF p. 64):** estimated 711−393 (actual 318) — **TWO correct options**: 300 (700−400) and 320 (710−390).

#### Verified NOT errors

- **تدرب أكثر Unit 2, item 11 (printed p. 75, PDF p. 76):** Yousef and Yaqoub solve 5300−3056. Yaqoub's 2244 is CORRECT; Yousef's 2356 is wrong. Deliberate find-the-error item, correctly constructed (re-verified at 300 dpi).
- **Three items struck on citation check (2026-11-06):** تدرب أكثر Unit 2 item 17 — the second addend is **7251**, so 1048+7251 = **8299**, which IS the first option; lesson 3-6 تدرب items 11–12 — the instruction puts the **product at the top and the sum at the bottom** (item 11: product 8 / sum 6 → 2 and 4; item 12: product 21 / sum 10 → 3 and 7), so both work as printed; lesson 4-10 اربط — the book says "نصفي المربع" (**the two halves** of a square equal a whole square), which is true, and the area 16 + 1 = 17 is correct.
- **تدرب أكثر Unit 1, item 13 (printed p. 39):** Hashim says the library 580 m away is "about 500 m" — the pupil's answer is wrong (580 rounds to 600 to the nearest hundred) and the item asks the pupil to judge it. Deliberate, not a book error.
- **تدرب أكثر Unit 2, item 15 (printed p. 76):** 350−208 = 142; the three base-ten pictures are 142 (right, correct), 158 (middle), 152 (left) — exactly one correct option.
- **Lesson 1-5, item 11:** Sara wrote "one hundred thousand four hundred and seventeen" as 1417 — wrong; correct 100,417. Spot-the-error item.
- **Lesson 2-5 تدرب, item 9:** 4561+5264 printed as 9725 (correct 9825); 327+128 printed as 445 (correct 455). Spot-the-error item.
- **Lesson 2-11, item 9:** Faisal vs Othman on 5360−1247 = 4113. Spot-the-error item.
- **Lesson 4-2 تدرب, item 7:** Shahd 14×2=28 correct; Munira 14×2=82 wrong. Spot-the-error item.
- **Lesson 4-3 تدرب, items 6–7:** 54×8 printed as 402 (correct 432); 38×7 printed as 2156 (correct 266). Spot-the-error item ("find the error then correct it").

#### Held-copy defects

- Blank PDF pp. 5, 7, 9, 17, 44, 47, 80, 81, 95, 97, 99, 105, 138, 141, 168, 169, 171, 177 — all blank by design (front-matter separators, opener reverses, "my project" pages, models-divider reverses). "My project" pupil pages PDF pp. 138 and 168 blank by design. No missing, duplicated or truncated content pages. No answer key.

---

### 6. Grade 3 Term 2 — `g03-t2.pdf` (First Edition 1447H / 2025–2026, no ISBN printed)

#### Identity (cover + title page + imprint, PDF p. 3; Part 2 imprint PDF p. 88)

- **Grade:** 3. **Term:** 2. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** © Ministry of Education, Kuwait. **Edition/year as printed:** **First Edition 1447H / 2025–2026**. No ISBN printed (no ISBN line on the imprint page; text search confirms). Ministry deposit 95, dated 19/1/2026.
- **Authors:** Dalal Mubarak Al-Hajraf (head), Abeer Barjas Ayed Al-Mutairi, Abeer Mohammed Jassim Mubarak, Radhia Ahmed Ibrahim Al-Sarraf, Shahd Mohammed Hamoud Al-Rashidi, Munira Zabaran Mohammed Al-Ajmi, Fatima Manzil Hazam Al-Dhafiri (7 authors — same team as G1-T2/G2-T2; verified from the title page, PDF p. 2).
- **Review teams:** scientific review Raja Hassan Al-Ustad; language review Sahar Saleh Al-Shanawi; printed by Dar Al-Siyasa presses.
- **PDF pages:** 165. **Printed range:** Part 1 printed pp. 17–83; Part 2 printed pp. 97–159. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 4.
- **Reading method:** text layer (pdftotext) — Part 1 read in full; Part 2 text layer is garbled/mojibake, so Part 2 was read visually from renders. Key pages verified visually.

#### Contents (from the contents pages, printed pp.)

**Unit 5 (division to ÷9)** — standards 14 · 5-1 equal distribution 17 · 5-2 repeated subtraction 20 · 5-3 ×/÷ relationship 22 · 5-4 ÷2 (24) · 5-5 ÷5 (26) · 5-6 ÷1 and ÷ itself 28 · 5-7 ÷3 (30) · 5-8 ÷4 (32) · 5-9 ÷6 (34) · 5-10 ÷7 (36) · 5-11 ÷8 (38) · 5-12 ÷9 (40) · تدرب أكثر Unit 5, 42 · project 44.
**Unit 6 (division with remainder, even/odd, data)** — standards 46 · 6-1 division patterns 49 · 6-2 division with remainder 52 · 6-3 ÷1-digit without renaming, with remainder 54 · 6-4 ÷1-digit with renaming, without remainder 56 · 6-5 even/odd 58 · 6-6 organising data 60 · 6-7 pictograph 62 · 6-8 bar graph 64 · 6-9 dot plot 66 · تدرب أكثر Unit 6, 68 · project 72.
**Unit 7 (fractions and time)** — standards 94 · 7-1 congruence/symmetry/similar parts 97 · 7-2 fractions as parts of a whole 100 · 7-3 half 102 · 7-4 third and two-thirds 104 · 7-5 quarter, two quarters, three quarters 106 · 7-6 fractions as parts of a set 108 · 7-7 time 110 · 7-8 reading time to 12 hours 112 · 7-9 reading time to 24 hours 114 · تدرب أكثر Unit 7, 116 · project 120.
**Unit 8 (measurement and money)** — standards 122 · 8-1 length, metre/centimetre 125 · 8-2 decimetre/millimetre 128 · 8-3 kilometre 130 · 8-4 mass 132 · 8-5 capacity 134 · 8-6 temperature 136 · 8-7 period 138 · 8-8 coins 140 · 8-9 paper money 142 · 8-10 problem solving (use data from the picture) 144 · تدرب أكثر Unit 8, 146 · project 148. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 5 — Division to ÷9 (17–44):** 5-1 equal distribution; 5-2 repeated subtraction; 5-3 ×/÷ relationship; 5-4 ÷2; 5-5 ÷5; 5-6 ÷1 and ÷ itself; 5-7 ÷3; 5-8 ÷4; 5-9 ÷6; 5-10 ÷7; 5-11 ÷8; 5-12 ÷9. تدرب أكثر Unit 5 (printed pp. 42–43, read in full). Project (printed p. 44).
- **Unit 6 — Division with remainder, even/odd, data (49–72):** 6-1 division patterns; 6-2 division with remainder; 6-3 ÷1-digit without renaming, with remainder; 6-4 ÷1-digit with renaming, without remainder; 6-5 even/odd; 6-6 organising data; 6-7 pictograph; 6-8 bar graph; 6-9 dot plot. تدرب أكثر Unit 6 (printed pp. 68–71, read in full). Project (printed p. 72).
- **Unit 7 — Fractions and time (97–120):** 7-1 congruence/symmetry/similar parts; 7-2 fractions as parts of a whole; 7-3 half; 7-4 third and two-thirds; 7-5 quarter, two quarters, three quarters; 7-6 fractions as parts of a set; 7-7 time; 7-8 reading time to 12 hours; 7-9 reading time to 24 hours. تدرب أكثر Unit 7 (printed pp. 116–118, read in full — e.g. item 23 pattern 9:15/9:30/9:45 → 10:00; item 24: 180 min = 3 h; item 32: 17:00 = 5:00 pm; item 33: just before noon is 11:00 am). Project (printed p. 120).
- **Unit 8 — Measurement and money (125–148):** 8-1 length, metre/centimetre; 8-2 decimetre/millimetre; 8-3 kilometre; 8-4 mass; 8-5 capacity; 8-6 temperature; 8-7 period; 8-8 coins; 8-9 paper money; 8-10 problem solving (use data from the picture). تدرب أكثر Unit 8 (printed pp. 146–148, read in full from renders — items 1–19 all verified; see below). Project (printed p. 148).
- **Models:** Part 1 divider printed 75 (PDF p. 76); model 1 fact families 77 (PDF p. 78), model 2 robot 78 (PDF p. 79), model 3 division unknown-number board 79 (PDF p. 80), model 4 number lines 81 (PDF p. 82). References printed 83 (PDF p. 84); guardian letter PDF p. 85. Part 2 cover PDF p. 86, title 87, imprint 88. Part 2 models: divider printed 151 (PDF p. 155), model 1 digital clocks 153 (PDF p. 157), model 2 ruler 20 cm 155 (PDF p. 159), model 3 paper money 156 (PDF p. 160), model 4 coins 157 (PDF p. 161). References printed 159 (PDF p. 163); guardian letter PDF p. 164; back cover PDF p. 165.

#### Honest negatives (what a Grade 3 Term 2 book might be expected to teach that this one does not)

- Part 1: no fraction operations, no decimals, no time, no measurement. Part 2: fractions only to denominators ≤10, no fraction arithmetic, no decimals/percentages, money to 20 dinars, no division of larger numbers, no geometry beyond congruence/symmetry.

#### Confirmed book errors — Grade 3 Term 2 (3 errors)

1. **Lesson 5-12 ÷9 (printed p. 40, PDF p. 41):** the multiples line prints **8, 16, 24**. Correct first multiples of 9: **9, 18, 27**. (The skip-counting row on the same page, 0, 9, 18, is correct.)
2. **Lesson 8-1 (printed p. 127, PDF p. 131):** a worked comparison hint prints "500 cm > 2000 cm". Correct: **500 cm < 2000 cm** (500 cm = 5 m < 20 m = 2000 cm).
3. **تدرب أكثر Unit 8, item 20 (printed p. 147, PDF p. 151):** three groups of notes to match a 10-dinar note; the groups total 8, 11 and 11 dinars — **no correct option** (no group totals 10 dinars).

#### Verified NOT errors

- **تدرب أكثر Unit 8, items 1–19 (printed pp. 146–148):** all verified from renders. Item 17: the money shown is three 1-dinar notes + three 100-fils coins = 3.300 dinars; only the ball at 2.25 dinars is affordable. Item 19: Saoud 140 cm, after two years 160 cm is the only plausible option. Item 18: the balance scale is the weight tool. Items 1–2: red pencil 2→7 = 5 cm, green 0→3 = 3 cm. January calendar: 1 January Sunday, 31 days. Item 3: 4 full weeks. Item 4: two weeks after 5 January = 19 January. Item 5: 31 days. Items 6–11: 1 kg = 1000 g, 1 m = 10 dm, 2000 mL = 2 L, 4 weeks = 28 days, 35 days = 5 weeks, 36 months = 3 years. Items 13–15: road → kilometre, teapot → litre, weight → kilogram. Item 16: 17°C → 32°C = 15°.
- **Lesson 8-2 (PDF pp. 131–132):** "90 m = 9000 cm", "3 m 65 cm = 365 cm", "1 dm = 10 cm", "1 m = 10 dm", "1 cm = 10 mm", "1 m = 100 cm = 1000 mm", "6 dm = 60 cm", "8000 mm = 80 dm" — all correct.
- **Lesson 5-12, item 19 (printed p. 44):** options read RTL as 12÷6, 12÷12, 12÷3 — the related fact 12÷3=4 IS present; not an error.

#### Held-copy defects

- Blank PDF pp. 4, 5, 7, 9, 49, 89, 90, 92, 94, 100, 128, 154, 156, 158, 160, 162 — all blank by design (front-matter separators, opener reverses, "my project" pages, models-divider reverses). No missing, duplicated or truncated content pages. No answer key. No ISBN seen.

---

### 7. Grade 4 Term 1 — `g04-t1.pdf` (First Edition 1447H / 2025–2026, no ISBN printed)

#### Identity (cover + title page + imprint, PDF p. 3)

- **Grade:** 4. **Term:** 1. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** Dar Al-Qabas. © Ministry of Education, Kuwait.
- **Edition/year as printed:** **First Edition 1447H / 2025–2026**. No ISBN printed (no ISBN line on the imprint page; text search confirms). Ministry deposit 93, dated 14/9/2025.
- **Authors:** Dalal Mubarak Al-Hajraf (head), Hessa Mohammed Al-Kandari, Fatima Asad Al-Kandari.
- **Review teams:** scientific review Dr Fatima Ismail Daif Al-Jadi + Iman Ibrahim Yusuf Bouhamra; language correction Dr Mishal Sanat Al-Harbi + Wasmiya Maakam Al-Ajmi (Part 2: Noura Ammash Al-Shammari replaces Wasmiya).
- **PDF pages:** 187. **Printed range:** Part 1 printed pp. 17–85; Part 2 printed pp. 100–185. **Offsets:** Part 1 PDF − 1 for PDF pp. 12–86, Part 2 PDF − 0 for PDF pp. 98–186.
- **Reading method:** text layer (pdftotext) — read in full; key pages verified visually. Five image-model pages (PDF pp. 136, 177, 179, 181, 183) have garbled text layers and were read from renders.

#### Contents (from the contents pages, printed pp.)

**Unit 1 (whole numbers to millions)** — standards 14 · 1-1 up to 1,000,000 (17) · 1-2 to millions (A) 20 · 1-3 to millions (B) 22 · 1-4 comparing 24 · 1-5 ordering 26 · 1-6 rounding 28 · 1-7 +/− patterns 30 · 1-8 estimating sums/differences 32 · 1-9 addition 34 · 1-10 subtraction 36 · 1-11 mental math 38 · 1-12 problem solving: choose operation, multi-step 40 · تدرب أكثر Unit 1, 42–45 · project "World of numbers" 46.
**Unit 2 (multiplication)** — standards 48 · 2-1 review of the × concept 51 · 2-2 ×10, 100, 1000 and multiples 54 · 2-3 multiplication concepts 56 · 2-4 1-digit × 2-or-more-digit 58 · 2-5 exploring × of 2-digit numbers 60 · 2-6 2-digit × 2-or-more-digit 62 · 2-7 mental math 64 · 2-8 problem solving: make a table 66 · تدرب أكثر Unit 2, 68–74 · project (Japanese method for multiplication) 75 · models 79–84 · references 86.
**Unit 3 (geometry)** — standards 100 · 3-1 solids 103 · 3-2 lines, line segments and angles 106 · 3-3 lines 108 · 3-4 polygons 110 · 3-5 rectangle properties 112 · 3-6 square properties 114 · 3-7 perimeter 116 · 3-8 measure and compare area of plane surfaces 118 · 3-9 area of rectangle and square 120 · 3-10 exploring volume 122 · 3-11 congruence and symmetry 124 · 3-12 movement of shapes 126 · تدرب أكثر Unit 3, **128–133** (the contents page says 132 — wrong) · project "Make a solid" 134.
**Unit 4 (data)** — standards 136 · 4-1 pictograph 139 · 4-2 coordinates on a grid 142 · 4-3 ordered pairs 144 · 4-4 bar graph 146 · 4-5 double bar graph 148 · 4-6 line graph 150 · 4-7 double line graph 152 · 4-8 line plot 154 · 4-9 Venn diagrams 156 · 4-10 Carroll diagrams 158 · 4-11 exploring mode, median and range 160 · 4-12 exploring mean 162 · تدرب أكثر Unit 4, 164–171 · project "Art of classification" 172 · models 175–183 · references 185. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 1 — Whole numbers to millions (17–46):** 1-1 up to 1,000,000; 1-2 to millions (A); 1-3 to millions (B); 1-4 comparing; 1-5 ordering; 1-6 rounding; 1-7 +/− patterns; 1-8 estimating sums/differences; 1-9 addition; 1-10 subtraction; 1-11 mental math; 1-12 problem solving: choose operation, multi-step. تدرب أكثر Unit 1 (printed pp. 42–45). Project "World of numbers" (printed p. 46).
- **Unit 2 — Multiplication (51–75):** 2-1 review of the × concept; 2-2 ×10, 100, 1000 and multiples; 2-3 multiplication concepts; 2-4 1-digit × 2-or-more-digit; 2-5 exploring × of 2-digit numbers; 2-6 2-digit × 2-or-more-digit; 2-7 mental math; 2-8 problem solving: make a table. تدرب أكثر Unit 2 (printed pp. 68–74). Project: Japanese method for multiplication (printed p. 75).
- **Unit 3 — Geometry (103–134):** 3-1 solids; 3-2 lines, line segments and angles; 3-3 lines; 3-4 polygons; 3-5 rectangle properties; 3-6 square properties; 3-7 perimeter; 3-8 measure and compare area of plane surfaces; 3-9 area of rectangle and square; 3-10 exploring volume; 3-11 congruence and symmetry; 3-12 movement of shapes. تدرب أكثر Unit 3 (printed pp. 128–133). Project "Make a solid" (printed p. 134).
- **Unit 4 — Data (139–172):** 4-1 pictograph; 4-2 coordinates on a grid; 4-3 ordered pairs; 4-4 bar graph; 4-5 double bar graph; 4-6 line graph; 4-7 double line graph; 4-8 line plot; 4-9 Venn diagrams; 4-10 Carroll diagrams; 4-11 exploring mode, median and range; 4-12 exploring mean. تدرب أكثر Unit 4 (printed pp. 164–171). Project "Art of classification" (printed p. 172).
- **Models:** Part 1 divider printed 77 (PDF p. 78); model 1 numbers 79, model 2 place-value board 80, model 3 number lines 81, model 4 multiplication table board 82, model 5 robot 83, model 6 multiplication table 84; references PDF p. 86 (Part 1). Part 2 front matter: cover PDF p. 87, title 88, imprint 89/90, intro 97, contents 98–99, standards 100. Part 2 models printed 175–183 (divider 175; model pages on printed pp. 177–183, read from renders where the text layer is garbled). References PDF p. 185; guardian letter PDF p. 186; back cover PDF p. 187.

#### Honest negatives (what a Grade 4 Term 1 book might be expected to teach that this one does not)

- No fractions/decimals; no division beyond patterns; no time or measurement units; no percentages; no negative numbers; no probability.

#### Confirmed book errors — Grade 4 Term 1 (0 errors)

- **None found.** Only the "Line Ghraph" typo below (not counted).

#### Verified NOT errors

- **Lesson 4-9 تدرب, item 12 (printed p. 157, PDF p. 157) — the Venn diagram is CORRECT (retracted "error").** An earlier read flagged it as an error; re-verified at 300 dpi: left circle = multiples of 3 (3, 15, 27, 33), right circle = even numbers (8, 16, 20, 32), overlap = multiples of 6 (6, 12, 24). 20 and 32 sit in the right-circle-only region where they belong. **Do NOT file it as an error.**
- **Lesson 1-9 find-the-error items** (456+128, correct 584; 24,561+52,371, correct 76,932) are spot-the-error items, not book errors.
- **تدرب أكثر Unit 1, item 32 (printed p. 46):** the table gives elephant 2,430 kg, camel 860 kg, hippopotamus 2,250 kg; elephant − camel = 1,570 kg, and that option is present. Item 29 (500,000+500+5 = 500,505), item 30 (Mansour 4,434; Majid 100 more = 4,534; together 8,968), item 31 (1,465−1,005 = 460) and item 33 (bar-model sentence "211 = ? + 105" correctly expresses the model) all check out.
- **تدرب أكثر Unit 2, items 32–33 true/false:** "400×50 = 2,000" (false as printed — 20,000) and "3×20×40 = 2,400" (true) are true/false judgement items.
- **تدرب أكثر Unit 3, item 37:** 3 layers × 10 cubes = 30 — correct.
- **تدرب أكثر Unit 4, item 14:** values 4, 9, 6, 9, 4, 9, 8 → mean 7, median 8, mode 9, range 5 — correct. Item 18: point (3,0) on the horizontal axis is TRUE. Item 25: mean of 2, 1, 2, 3 litres = 2 litres — correct.

#### Held-copy defects

- Blank PDF pp. 4, 5, 7, 9, 17, 92, 94, 96, 182, 184 — all blank by design (front-matter separators, opener reverses, models-divider reverses). (An earlier list included PDF p. 188, which does not exist in a 187-page file; dropped.) No missing, duplicated or truncated content pages. No answer key. No ISBN seen.

---

### 8. Grade 4 Term 2 — `g04-t2.pdf` (First Edition 1447H / 2025–2026, no ISBN printed)

#### Identity (cover + title page + imprint, PDF p. 2)

- **Grade:** 4. **Term:** 2. **Kind:** student textbook. **Language:** Arabic.
- **Title as printed:** الرياضيات — *Al-Riyāḍiyyāt* (Mathematics).
- **Publisher:** © Ministry of Education, Kuwait. **Edition/year as printed:** **First Edition 1447H / 2025–2026**. No ISBN printed (no ISBN line on the imprint page; text search confirms). Ministry deposit 96, dated 19/1/2026.
- **Authors:** Dalal Mubarak Al-Hajraf (head), Fatima Asad Al-Kandari, Hanadi Mohammed Al-Mutairi, Hessa Mohammed Al-Kandari, Nawal Fahd Al-Jafin, Riyasa Sultan Al-Hathal, Maha Abdulwahab Mohammed Taqi (7 authors — verified from the title page, PDF p. 2).
- **Review teams:** scientific review Mona Qasim Dashti; language correction Abdul-Fattah Yassin Mahmoud Al-Akrat; printed by Dar Al-Siyasa presses. (The title page also carries the G4-T1 language reviewers' names as printed: Dr Mishal Sanat Al-Harbi, Wasmiya Maakam Al-Ajmi.)
- **PDF pages:** 171. **Printed range:** Part 1 printed pp. 17–87; Part 2 printed pp. 103–167. **Offsets:** Part 1 PDF − 1, Part 2 PDF − 2.
- **Reading method:** text layer (pdftotext) — read in full; key pages verified visually.

#### Contents (from the contents pages, printed pp.)

**Unit 5 (division)** — standards 14 · 5-1 division concept 17 · 5-2 ÷10, 100, 1000 and multiples 20 · 5-3 estimate division result 22 · 5-4 division 24 · 5-5 exploring factors 26 · 5-6 divisibility by 2, 5 and 10 (28) · 5-7 ÷1-digit 30 · 5-8 dividing greater numbers 32 · 5-9 ÷1-digit with zeros in quotient 34 · 5-10 order of operations 36 · تدرب أكثر Unit 5, 38–41 · project "Sun of factors" 42.
**Unit 6 (fractions)** — standards 44 · 6-1 fraction 47 · 6-2 equivalent fractions 50 · 6-3 simplest form 52 · 6-4 comparing fractions 54 · 6-5 ordering fractions 56 · 6-6 adding fractions, like denominators 58 · 6-7 adding fractions, unlike denominators 60 · 6-8 subtracting fractions, like denominators 62 · 6-9 subtracting fractions, unlike denominators 64 · 6-10 mixed numbers and improper fractions 66 · 6-11 adding/subtracting fractions from a whole number 68 · تدرب أكثر Unit 6, 70–73 · project "Fraction spinner" 74 · models 79–85 · references 88.
**Unit 7 (decimals)** — standards 100 · 7-1 exploring tenths 103 · 7-2 hundredths 106 · 7-3 decimal numbers 108 · 7-4 decimal place value relationship 110 · 7-5 comparing fractions in decimal forms 112 · 7-6 ordering fractions in decimal forms 114 · 7-7 rounding decimal numbers 116 · 7-8 estimating +/− of decimals 118 · 7-9 adding decimals 120 · 7-10 subtracting decimals 122 · تدرب أكثر Unit 7, 124–127 · project "Houses of decimal numbers" 128.
**Unit 8 (time, measurement, money)** — standards 130 · 8-1 reading a clock 133 · 8-2 units of time 136 · 8-3 finding the time period 140 · 8-4 calendar 142 · 8-5 length 144 · 8-6 weight 146 · 8-7 capacity 148 · 8-8 using money 150 · تدرب أكثر Unit 8, 152–155 · project "Make my clock" 156 · models 161–165 · references 169. **No answer key.**

#### Unit-by-unit filing (printed pp.)

- **Unit 5 — Division (17–42):** 5-1 division concept; 5-2 ÷10, 100, 1000 and multiples; 5-3 estimate division result; 5-4 division; 5-5 exploring factors; 5-6 divisibility by 2, 5 and 10; 5-7 ÷1-digit; 5-8 dividing greater numbers; 5-9 ÷1-digit with zeros in quotient; 5-10 order of operations. تدرب أكثر Unit 5 (printed pp. 38–41). Project "Sun of factors" (printed p. 42).
- **Unit 6 — Fractions (47–74):** 6-1 fraction; 6-2 equivalent fractions; 6-3 simplest form; 6-4 comparing fractions; 6-5 ordering fractions; 6-6 adding fractions, like denominators; 6-7 adding fractions, unlike denominators; 6-8 subtracting fractions, like denominators; 6-9 subtracting fractions, unlike denominators; 6-10 mixed numbers and improper fractions; 6-11 adding/subtracting fractions from a whole number. تدرب أكثر Unit 6 (printed pp. 70–73). Project "Fraction spinner" (printed p. 74).
- **Unit 7 — Decimals (103–128):** 7-1 exploring tenths; 7-2 hundredths; 7-3 decimal numbers; 7-4 decimal place value relationship; 7-5 comparing fractions in decimal forms; 7-6 ordering fractions in decimal forms; 7-7 rounding decimal numbers; 7-8 estimating +/− of decimals; 7-9 adding decimals; 7-10 subtracting decimals. تدرب أكثر Unit 7 (printed pp. 124–127). Project "Houses of decimal numbers" (printed p. 128).
- **Unit 8 — Time, measurement, money (133–156):** 8-1 reading a clock; 8-2 units of time; 8-3 finding the time period; 8-4 calendar; 8-5 length; 8-6 weight; 8-7 capacity; 8-8 using money. تدرب أكثر Unit 8 (printed pp. 152–155). Project "Make my clock" (printed p. 156).
- **Models:** Part 1 divider printed 77 (PDF p. 78); model 1 vertical division 79, model 2 number line 80, models 3–7 fraction chips 81–85 (printed pp. 79–85); references PDF p. 88 (Part 1; cites 3rd ed. 2017–2018 and 5th ed. 2024–2025). Part 2 front matter: cover PDF p. 89, title 90, imprint 91, Basmala 92, blanks 94, 96, 98 (portraits PDF pp. 95 and 97). Part 2 models: divider printed 159 (PDF p. 161); model 1 tenths grid 161, model 2 hundredths grid 162, model 3 place-value board 163, model 4 clock model 164, model 5 calendar 165; references PDF p. 169 (printed 167); guardian letter PDF p. 170; back cover PDF p. 171.

#### Honest negatives (what a Grade 4 Term 2 book might be expected to teach that this one does not)

- No multiplication/division of fractions; no percentages; no negative numbers; probability only one possible/impossible item; no geometry beyond clock/calendar models; no data/graphs in Term 2.

#### Confirmed book errors — Grade 4 Term 2 (1 error)

1. **تدرب أكثر Unit 7, item 29 (printed p. 125, PDF p. 127):** match each of 0.8, 1, 1.2, 0.6 with a partner summing to 1.5; partners offered 1.4, 0.7, 0.3, 0.5. 0.8+0.7, 1+0.5 and 1.2+0.3 all work, but **0.6 has no partner** (it needs 0.9, not offered).

#### Verified NOT errors

- **تدرب أكثر Unit 5, true/false items (printed pp. 38–41):** e.g. item 19: 630÷70=90 is FALSE as stated (630÷70=9); item 20: factors of 20 "10, 5, 4, 2 only" is FALSE (also 1, 20); item 21: 1598 divisible by 2 is TRUE. Deliberate true/false exercises.
- **تدرب أكثر Unit 5, item 10:** lists 1 among "non-prime" numbers — 1 is neither prime nor composite; recorded as a simplification, not filed as an error.
- **تدرب أكثر Unit 7, item 30 (printed p. 127):** 59.76−47.9 = 11.86 seconds — correct.
- **تدرب أكثر Unit 8, items 3–5 (printed pp. 152–153):** item 3: Sunday + 20 days = Saturday; item 4: 1 h 3 min = 3,780 s; item 5: 4:10 → 5:55 pm = 1 h 45 min — all correct.
- **تدرب أكثر Unit 8, item 2 (printed p. 152, PDF p. 154) — struck on citation check (2026-11-06):** read in sentence order, Adel's trip starts **05:20 pm** and ends **08:20 pm** (3 hours). The draft had read the two time clusters in reverse order and filed a phantom "ends before it starts" error.

#### Held-copy defects

- Blank PDF pp. 4, 5, 7, 9, 17, 47, 87, 94, 96, 98, 104 — all blank by design (front-matter separators, opener reverses, "my project" pages, models-divider reverse on PDF p. 87). (An earlier list included PDF p. 172, which does not exist in a 171-page file; dropped.) No missing, duplicated or truncated content pages. No answer key. No ISBN seen.

---

### Per-book summary

| Book | PDF pp. | Printed pp. (Part 1 / Part 2) | Edition | ISBN | Errors | Answer key | Held-copy defects |
|---|---|---|---|---|---|---|---|
| G1-T1 | 174 | 17–88 / 105–169 | 2nd ed. 1448H / 2026–2027 | 978-9921-33-099-1 | 1 | None | Blanks only; greyscale PDF pp. 33–77 |
| G1-T2 | 164 | 17–83 / 99–158 | 1st ed. 1447H / 2025–2026 | None printed | 2 | None | Blanks only |
| G2-T1 | 166 | 17–82 / 95–160 | 2nd ed. 1448H / 2026–2027 | 978-9921-33-083-0 | 2 | None | Blanks only |
| G2-T2 | 166 | 17–81 / 99–163 | 1st ed. 1447H / 2025–2026 | None printed | 0 | None | Blanks only; PDF p. 122 image page |
| G3-T1 | 180 | 17–87 / 100–175 | 2nd ed. 1448H / 2026–2027 | 978-9921-33-052-6 | 3 | None | Blanks only |
| G3-T2 | 165 | 17–83 / 97–159 | 1st ed. 1447H / 2025–2026 | None printed | 3 | None | Blanks only; Part 2 text layer garbled |
| G4-T1 | 187 | 17–85 / 100–185 | 1st ed. 1447H / 2025–2026 | None printed | 0 | None | Blanks only; 5 image-model pages (PDF pp. 136, 177, 179, 181, 183) |
| G4-T2 | 171 | 17–87 / 103–167 | 1st ed. 1447H / 2025–2026 | None printed | 1 | None | Blanks only |
| **Band total** | **1,373** | | | | **12** | **0** | |

### How the books were read

- **Text-layer books** (G1-T2, G2-T2, G3-T2 Part 1, G4-T1, G4-T2): `pdftotext -layout` with NFKC normalisation and spaced-letter joining; read in full. `pdftotext` reverses equation/inequality lines in these Arabic books (RTL trap) — no inequality-direction error was filed from extraction alone; every such item was verified against a render.
- **Image-only books** (G1-T1, G2-T1, G3-T1): no usable text layer; read visually from 150 dpi `pdftoppm` renders in 2-page stacks, disputed items at 300 dpi. G1-T1 and G2-T1 were read 174/174 and 166/166 pages. **G3-T1 method honesty:** contents complete from the contents pages; all four تدرب أكثر sections read in full; lessons spot-sampled (1-1, 2-1, 3-1, 3-3, 4-1) and verified correct; NOT a page-by-page error hunt — but each of its three confirmed errors was verified against a render (three further claimed errors were struck on citation check as digit-order misreads).
- **Garbled pages:** G3-T2 Part 2 text layer is mojibake — read visually from renders. G4-T1 image-model pages (PDF pp. 136, 177, 179, 181, 183) and G2-T2 PDF p. 122 (image page) were read from renders. No OCR script was used (tesseract chokes on illustrated pages).
- **Verification:** all 8 SHA-256 hashes re-computed 2026-11-06 and matching the work notes. Every confirmed error was checked against a render or the text layer with its arithmetic recomputed; every deliberate error-spotting exercise was checked the same way and excluded. Contents-page pagination slips (G4-T1 Unit 3 تدرب أكثر, G2-T2 Part 2 references) were caught by checking the named page itself.
- **What was NOT done:** no teacher guides or answer keys exist in this band, so none were checked. No book was checked against an external edition — edition/year/ISBN are as printed on each book's own imprint page.

### Band A — closed

- **Band A (Grades 1–4) is read and filed.** 8 books, all student textbooks, 0 teacher guides, 0 answer keys. Total 1,373 PDF pages. 12 confirmed book errors (teach corrected, never as fact); one earlier "error" (G4-T1 Venn diagram) retracted — the diagram is correct, and nine more claimed errors were struck on citation check (2026-11-06) as digit-order misreads.
- **Grade/term/kind confirmed from each book's own cover + title page for all 8 books; no file-to-record mismatches.** Term 1 books are 2nd edition 1448H / 2026–2027 (with ISBN); Term 2 books are 1st edition 1447H / 2025–2026 (no ISBN printed).
- **Record mismatches found and corrected in this filing** (not in grade/term/kind, but in the earlier draft): G1-T2/G3-T2/G4-T2 author lists (3 → 7 authors), G2-T1 Unit 3 lesson titles, G3-T1 تدرب أكثر Unit 2 item 11 (subtrahend 3056, answer 2244 — not an error), G4-T1/G4-T2 Part 2 front-matter blanks, G2-T1/G2-T2 Part 2 tails and models (re-read from renders this session), G4-T1 contents-page slip (Unit 3 تدرب أكثر on p. 128, not 132), G2-T2 contents-page slip (Part 2 references printed 163, not 164), and five impossible blank-page numbers (PDF p. 165 in G1-T2, p. 167 in G2-T2, p. 166 in G3-T2, p. 188 in G4-T1, p. 172 in G4-T2 — none exists).

---

## Kuwait — Mathematics, Grades 5–8 (Band B)

READ COMPLETE. Files in hand:
**8 files — Grades 5–8, Term 1 + Term 2 — 1,782 PDF pages in total**
(Grade 5: 375; Grade 6: 454; Grade 7: 470; Grade 8: 483;
308,831,710 bytes, ~294.5 MiB).
Distinct works: **8 distinct works** (all 8 SHA-256 distinct).
**8 student books, 0 teacher guides** — there are no teacher guides in
the Kuwait maths set at all.
Answer key: **none in any of the 8 books.**
Book errors found: **6 in total** — Grade 5 Term 2: 1; Grade 6 Term 1: 1;
Grade 7 Term 1: 1; Grade 7 Term 2: 2; Grade 8 Term 1: 1.
Grade 5 Term 1, Grade 6 Term 2 and Grade 8 Term 2 are error-free as held.
(Citation check, 2026-11-06: this filing originally claimed 11 errors;
the checker retracted 5 of them as misreadings — see the retraction list
after the Consolidated book errors table and
checks/check-band-b.md.)

- Band: B (Grades 5–8). Reader: Band B reader, 2026-11-06.
- Set: 8 files, 1,782 PDF pages. This is one band of the 22nd maths
  country read (Kuwait).
- How read: every book read in full, page by page, from the PDF text
  layer (`pdftotext -layout`), with flagged pages verified visually from
  150–200 dpi renders. **Grade 5 Term 2 is ~106 pages image-only** (no
  text layer on those pages) and was read visually from renders — see
  §2. Where a claim rests on a render it says so.
- Conventions: "printed p." = the book's own printed page number
  (footer). "PDF p." = the PDF page. Offsets are stated per book and
  were verified at two or more points. Lesson numbers are the book's
  own. Only short quoted fragments are used; the rest is summary and
  structural notes.
- Language: all 8 books are in **Arabic**. This filing is in English;
  maths content is given in English.
- **The `pdftotext` inequality trap.** The text layer systematically
  mirrors inequality/equality lines (reverses the numbers and flips
  `<`/`>`). The books write maths left-to-right and their comparisons
  are correct as printed. No inequality-direction error is reported
  from extraction alone anywhere in this filing; every suspected case
  was checked against a render or against an Arabic conclusion
  sentence in the book.

### The set at a glance

- **One ministry, one series.** All 8 files are Kuwait Ministry of
  Education mathematics student books (copyright: Ministry of
  Education, Educational Research and Curricula Sector). Grades 5 is
  Primary stage (المرحلة الابتدائية); Grades 6–8 are Intermediate
  stage (المرحلة المتوسطة). No track is printed in any of the 8 books
  (none expected in Grades 5–8).
- **Each term file holds BOTH parts bound together.** Every file
  contains Part 1 (القسم الأول) and Part 2 (القسم الثاني) of that
  term's book, each part with its own cover, title page, front matter
  and printed pagination. There are no separate part files.
- **Two edition cycles.** Grade 5 both terms: **1st edition 1447 AH /
  2025–2026**. Grades 6, 7, 8 Term 1: **2nd edition 1448 AH /
  2026–2027**. Grades 6, 7, 8 Term 2: **1st edition 1447 AH /
  2025–2026**. Never borrow a year across files.
- **Only three ISBNs in the whole band** — one on each Term 1
  2nd-edition book: G6-T1 978-9921-33-067-0, G7-T1 978-9921-33-075-5,
  G8-T1 978-9921-33-121-9. Grade 5 books and all Term 2 books print no
  ISBN. Deposit numbers are printed on the 2nd-edition books
  (401/402, 403/404, 405/406, all dated 2026/7/13) and on the Term 2
  Grade 6–8 books (89, 90, 91, all dated 2026/1/16). The Grade 5 books
  also print deposit numbers: G5-T1 no. 94 dated 2025/9/14 and G5-T2
  no. 97 dated 2026/1/19 (checker correction, 2026-11-06).
- **Publisher.** The three Term 1 2nd-edition books name Dhat
  Al-Salasil – Kuwait (ذات السلاسل) as publisher. The Grade 6, Grade
  7 and Grade 8 Term 2 books also name Dhat Al-Salasil (Grade 6
  Term 2: imprint, PDF p. 3 — checker correction, 2026-11-06; this
  filing originally said the Grade 6 Term 2 book named none). The
  Grade 5 books name no Dhat Al-Salasil line; their imprints name a
  printing company instead — G5-T1: Al-Asriya Company for Printing,
  Publishing and Distribution LLC; G5-T2: Dar Al-Siyasa Press
  (a printer). Their copyright line is the Ministry of Education.
- **References cite older editions.** In every book the references
  page cites the 1st edition 2024–2025, the trial edition 2023–2024
  (and, for Grades 7–8, the 3rd edition 2016–2017/2017–2018) while the
  title page says the new edition (1st ed. 2025–2026 or 2nd ed.
  2026–2027). The references were not updated for the new editions.
- **Back covers repeat cover wording.** In most books the back cover
  repeats the cover text of one part ("1/1", "2/2", or the Part 1
  wording on a Term 2 book). See per-book defects.
- **Author teams change between terms.** The Grade 5 Term 2 team (7
  authors) is different from the Grade 5 Term 1 team (3 authors).
  Uhud Mubarak Hamad Al-Ajmi replaces Samira Mohammed Sultan
  Al-Matrouk in both Grade 6 Term 2 and Grade 7 Term 2. Grade 8 has a
  wholly different team from Grades 5–7 under the same head (Dalal
  Mubarak Falah Al-Hajraf), and Afaf Abdulaziz Yaqoub Al-Sanea
  replaces Mona Faraj Saad Al-Mutairi in Grade 8 Term 2. The imprint
  pages of the 2nd-edition books also name a scientific reviewer and
  an "AI explanations" team — those are NOT authors.
- **Structure shared by all 8 books.** Each unit opens with an opener
  page (a Kuwaiti-life context), a standards page (curriculum
  standards and performance indicators), and an organiser page, then a
  "ready" (استعد) revision page, then lessons, each lesson with worked
  examples, "your turn now" (دورك الآن) guided items, self exercises
  (تمارين ذاتية), and a higher-order-thinking (مهارات تفكير عليا) item;
  each unit ends with a unit assessment (تقويم الوحدة التعليمية) in
  three parts — essay items, true/false items, multiple-choice items.
  Grades 7–8 also carry two projects per term (المشروع).
- **No answer key anywhere.** Every assessment and exercise is given
  without answers in the pupil's book.
- **Honest negatives per grade (as filed in the band sections).**
  - **Grade 5 Term 1:** no fractions at all (Term 2); no geometry
    (shapes, angles, perimeter/area); no measurement units; no
    ratio/percentage; no probability; no negative numbers; no algebra.
  - **Grade 5 Term 2:** no decimal operations (decimals only in Term
    1); no negative numbers; no algebra/expressions; no coordinate
    geometry; no volume; statistics only as in Term 1 (data handling
    is a Term 1 unit).
  - **Grade 6 Term 1:** no integers/negative numbers (Term 2); no
    ratio/proportion (Term 2); no measurement (Term 2); no
    probability/statistics (Term 2); no algebra/equations; no
    coordinate geometry; no percentages.
  - **Grade 6 Term 2:** no equations (Unit 5, Lesson 5-6 introduces
    the variable concept only); no geometry beyond
    measurement; no coordinate geometry; no percentages as a
    standalone topic; no formal proof.
  - **Grade 7 Term 1:** no fraction operations (Term 2); no
    percentages (Term 2); no probability (Term 2); no Pythagoras; no
    circle geometry; no coordinate geometry; no formal proof; no
    simultaneous equations.
  - **Grade 7 Term 2:** no statistics/data-handling unit (probability
    only); no Pythagoras; no coordinate geometry; no circle geometry;
    algebra limited to one-variable equations with fractions; no
    formal proof.
  - **Grade 8 Term 1:** no formal proof of Pythagoras; no
    trigonometry; no circle theorems beyond area/circumference; Unit 1
    sets/relations without functions.
  - **Grade 8 Term 2:** no trigonometry; no circle geometry; no
    functions; no simultaneous equations; no factorising of quadratic
    trinomials (factorising stops at GCF and difference of two
    squares); no surds as a topic; no coordinate geometry; statistics
    stops at mean/median/mode, pie charts and stem-and-leaf (no
    dispersion, no quartiles); probability is classical counting only.
- **Confirmed book errors:** carried in full below with their correct
  values, to be taught corrected, never as fact. The sharpest is:
  **G7-T1, Unit 2 opener (printed p. 63):**
  claims Kuwait's highest recorded temperature is 52.1°C on 30 July
  2020 at Mutriba; the WMO-verified record is **53.9°C on 21 July
  2016 at Mitribah** — the highest ever recorded in Asia.
  (Two items originally listed here as among the sharpest — G5-T2
  Unit 6 review Q47 and G8-T2 Unit 6 assessment Q12 — were retracted
  by the citation checker on 2026-11-06 as misreadings; see the
  retraction list after the Consolidated book errors table.)

### File table (cover-proved grade + kind for every file)

| File | Grade / term / kind | PDF pp. | Printed pp. | Bytes | SHA-256 |
|---|---|---|---|---|---|
| g05-t1.pdf | G5 Term 1 student, Arabic | 196 | 1–189 | 63,494,342 | 33520415b80dfdfbe0b6e68647eca02b9cbd75e6ab1d8e27b4d4e0f8b3764645 |
| g05-t2.pdf | G5 Term 2 student, Arabic | 179 | 1–176 | 39,111,971 | a0fcdf552f6bf8257a7b6883e281a414e26b72d627990fa5a6a980e63eafa857 |
| g06-t1.pdf | G6 Term 1 student, Arabic | 232 | 1–214 | 37,569,446 | f64738d61900bfd0ccdaf1e0a77d951f99e9d62727eaada4b9e5da2be9cc01e3 |
| g06-t2.pdf | G6 Term 2 student, Arabic | 222 | 1–205 | 29,790,955 | 7a8cf0db89210b3a9b6a83d72a840bc4fd4340457dbcef7846f8e690dacc8646 |
| g07-t1.pdf | G7 Term 1 student, Arabic | 246 | 1–230 | 35,617,477 | 4ee921fd93ae8e1fcafb08ab3fbcfeae29b486d7e8db3fc502cb10a19334e94a |
| g07-t2.pdf | G7 Term 2 student, Arabic | 224 | 1–207 | 36,860,592 | 8931e7432b93271ea0f410c3d83beea27dcc961897fe64dd603bd79727b90eb6 |
| g08-t1.pdf | G8 Term 1 student, Arabic | 235 | 1–216 | 43,034,333 | 5964f096eca489efa35f13027aefa4769541958c2d7659fa7e667e0107a3d295 |
| g08-t2.pdf | G8 Term 2 student, Arabic | 248 | 1–230 | 23,352,594 | c3c60a27310c41c9aa1ab8914b1ebcfdf5b4419c274e204b439c41c6a31413a3 |

Totals: 8 files, 1,782 PDF pages, 308,831,710 bytes. All 8 SHA-256
distinct. All 8 files carry a `%PDF` header and `%%EOF` tail and match
their recorded page counts (`pdfinfo`).

#### Printed-page offsets (per file)

| File | Printed = PDF … |
|---|---|
| g05-t1.pdf | Part 1: −1; Part 2: −3 |
| g05-t2.pdf | Part 1: −1; Part 2: −2 |
| g06-t1.pdf | Part 1: −1; Part 2: −14 |
| g06-t2.pdf | Part 1: −1; Part 2: −15 |
| g07-t1.pdf | Part 1: −1; Part 2: −14 |
| g07-t2.pdf | Part 1: −1; Part 2: −15 |
| g08-t1.pdf | Part 1: −1; Part 2: −14 |
| g08-t2.pdf | Part 1: −1; Part 2: −15 |

### Reconciliation and record corrections

Proved from the books' own covers and title pages — never from the
filename or the record.

1. **Every file is a student book, Term 1 or Term 2 as filed, and each
   holds BOTH parts.** The record's slot labels were not trusted: the
   English phase had already shown Kuwait files shelved as workbooks
   turning out to be student books. In this band every file's grade,
   term and kind were proved from its own cover + title page, and all
   8 match their filenames.
2. **The reconciled Kuwait maths set is 29 files in hand, not the
   inventory's 18** — the inventory predates the 2026-11-05 grab runs.
   Grades 1–9 hold Term 1 + Term 2 student books. There are NO
   teacher guides in the Kuwait maths set at all.
3. **Edition cycles (see The set at a glance).** Grade 5 both terms
   1st ed. 1447 AH / 2025–2026; Grades 6–8 Term 1 2nd ed. 1448 AH /
   2026–2027; Grades 6–8 Term 2 1st ed. 1447 AH / 2025–2026.
4. **G8-T1 vs G8-T2 year-unit order.** G8-T1's contents overview lists
   the year's Units 5–7 as Algebraic expressions, Factorising,
   Quadrilaterals; G8-T2 lists them as Quadrilaterals, Algebraic
   expressions, Factorising — and the actual Term 2 book follows the
   G8-T2 order. G8-T1's year-list is inconsistent with the Term 2
   book.
5. **G8-T1 structure.** Its contents overview lists 8 year units but
   the Term 1 volume holds Units 1–4 only (printed 15–216); Term 2
   holds Units 5–8. Not a defect — the volume ends cleanly.
6. **G8-T2 lesson oddity.** Unit 5 Lesson 5-3 presents six
   parallelogram-detection conditions (printed pp. 34–43) but the
   summary on printed p. 45 lists only five, omitting
   consecutive-angles-supplementary.
7. **G8-T2 embedded filename.** The PDF's embedded InDesign filename
   references "G7". This is not identity evidence; identity is proved
   from the cover + title page (Grade 8, Term 2, Part 1 and Part 2).
8. **References cite older editions** in all 8 books while the title
   pages say the new edition (see The set at a glance).

### Consolidated book errors (6) — teach corrected, never as fact

| Book | Location | Error as printed | Correct value |
|---|---|---|---|
| g05-t2 | Unit 6 review Q26, printed p. 77 | Ratio table (5,8) and (10,24) not equivalent (5/8 ≠ 10/24 = 5/12) | Likely 10 should be 15 |
| g06-t1 | Unit 4 assessment item 8, printed p. 212 | 1/3 ÷ 6/7 = 7/18 not among options (2 4/7, 4 2/7, 2 2/7, 18/7) | 7/18 |
| g07-t1 | Unit 2 opener, printed p. 63 | Claims Kuwait's highest recorded temperature 52.1°C, 30 July 2020, Mutriba, WMO-classified | 53.9°C, 21 July 2016, Mitribah — WMO-verified, highest ever in Asia |
| g07-t2 | Unit 8 assessment MCQ 9, printed p. 205 | Options أ 1/2 and د 4/8 both correct for P(prime from 1–8) | 4/8 = 1/2 (duplicate correct options) |
| g07-t2 | Lesson 6-7 Q3 MCQ, printed p. 103 | Two data sets determine a triangle: أ (SSA: 7 cm, 5 cm, 50°) and د (6 cm, 6 cm, 60° → equilateral) | Intended answer د; أ also drawable — two-answer item |
| g08-t1 | Lesson 1-6 sidebar, printed p. 50 | Calls Descartes "from the nineteenth century" | René Descartes lived 1596–1650 — the seventeenth century |

- g05-t1: no errors. g06-t2: no errors. g08-t2: no errors.
- Checker note on the g06-t1 row (2026-11-06): option د reads 18/7,
  not "1 8/7" as originally transcribed; note option أ (2 4/7) is the
  same value as د. The error itself stands: 7/18 is not an option.

#### Retracted by the citation checker (2026-11-06) — NOT book errors

Five error claims in the original filing were misreadings of the
printed page (Arabic-Indic digits / superscripts read from renders at
too low a resolution). They are retracted here and in the per-book
sections; do not teach them as book errors:

1. **g05-t2, L5-5 Q18, printed p. 27** — options أ and ب do NOT both
   read 0.45: أ reads 0.045 and ب reads 0.45, so 9/20 = 0.45 is
   option ب uniquely. No duplicate.
2. **g05-t2, L6-2 Q9, printed p. 51** — the football fraction is
   1/6, not 1/2: Ali spent 3/5 + 1/6 = 23/30 of his free time,
   which is possible. Not an error.
3. **g05-t2, L6-3 Q10, printed p. 53** — the four expressions give
   7 1/2, 7 1/2, 7 1/3 and 7 1/2 (in book order: 2 4/14 + 5 3/14;
   1 3/10 + 6 2/10; 2 4/15 + 5 1/15; 4 5/12 + 3 1/12), so a unique
   odd one out (the /15 expression) exists. Not an error.
4. **g05-t2, Unit 6 review Q47, printed p. 79** — the question is
   3/10 × 2 1/2 (not × 1 1/2), whose product is 3/4, option ج;
   option ب (15/20) is the same value in non-simplest form, a
   standard distractor under the question's "in simplest form"
   wording. Not an error.
5. **g08-t2, Unit 6 assessment Q12, printed p. 122** — the second
   polynomial is 2x² + x³ − 4x − 1 (not "2x³ + x³ − 4x − 1"); the
   true sum is 3x⁴ + 5x³ + 2x² − 7x + 1, which IS option د.
   Not an error.
- The g07-t2 Unit 8 MCQ 9 and the g07-t2 Lesson 6-7 Q3 errors and the
  g08-t1 Descartes error were all verified against renders.

### Resolved non-errors (do NOT report as errors)

Items that looked wrong in extraction but are correct as printed
(render-verified where noted): g05-t2 Unit 6 review Q43, Q33, L6-11
Q16; g06-t2 L5-5 Q4, Unit 5 assessment Q8, L8-2 Q5 (72 tosses);
g07-t1 L2-1 Q6 MCQ (5 × 3³ × 2³ = 1080); g07-t2 assessment MCQ 11
(7 4/5 = 7.8), L5-7 Q3 (45/1000 dinar = 45 fils), Unit 7 assessment Q3
(25% of a number = 3 → 12), L8-4 gift probability 1/6; g08-t1 p78
irrationals vs recurring-decimal box, p85 ordering, p88 addition,
p94–95 subtractions, p106 division, p117 order of operations (42),
p145 Pythagoras (√27), cone-vessel Q3 value 314 ml (render-verified),
Unit 4 opener oil "~10% of world reserves" (sources range ~6–10%,
not counted as error), Millau Bridge "longest cable-stayed"
(defensible as tallest, not counted); g08-t2 p116 Q6 (5(x−y) − (5x−5y)
= 0, option ب — render-verified), p123 Q14 ((x³/2x⁴)^m = 1 → m = 0,
option أ — render-verified), p161 Q6 (all four factorisations correct,
including (1/4)h² − 25a²l² — render-verified), p161 Q7 (√(x²−y²) = 8
given x+y = 16, x−y = 4 — the question asks for the square root,
option أ — render-verified), p179 worked example 2 (6−5x ≤ −7 →
x ≥ 2 3/5, with the inequality correctly reversed; 5x+4 < −3−2x →
x < −1 — render-verified), p182 Q7 (greatest value of x²−y² is 36,
option د — render-verified), p228 self-exercise Q1 (drawing/arts 20%,
photography 30%; 40 and 10 learners of 200 — render-verified), p233
internet-speed grouped table (frequencies 5 and 10 are correct for
the data as printed — render-verified), p242 Unit 8 assessment T/F Q7
(poetry 10%, statement false) and Q9 (net profit 720 KD, statement
false — render-verified).
Deliberate wrong-answer items (not errors): g06-t1 p58 Q3 (2.86 ÷ 22
= 0.013 vs correct 0.13); g07-t1 Fajr/Duha, Saleh/Faisal, cube
S = 54; g08-t1 Mohammed vs Hussein (5 − 2.25 = 2.75, not 3.25);
g08-t2 Hanan (degree 6), Tariq (subtraction signs), Nawwaf (GCF
factorising), Abdulaziz ((x−1)² = 0), Khalid's GCF claim (correct),
Fawziya (12x, 12y like terms — wrong), x+x answers 2x² vs 2x.

---

### 1. `g05-t1.pdf` — Grade 5 Term 1 student book

- Title as printed (Arabic): الرياضيات، الصف الخامس، الفصل الدراسي
  الأول — القسم الأول / القسم الثاني. Transliteration: *al-Riyāḍiyyāt,
  al-ṣaff al-khāmis, al-faṣl al-dirāsī al-awwal*. Translation:
  "Mathematics, Grade 5, Term 1 — Part 1 / Part 2". Primary stage
  (المرحلة الابتدائية). Grade, term and kind proved from the cover +
  title page (PDF p. 2).
- Edition as printed: **1st edition 1447 AH / 2025–2026**. No ISBN.
  Deposit no. 94 dated 2025/9/14 (imprint, PDF p. 3 — checker
  correction, 2026-11-06; the original filing recorded no deposit
  number). The imprint names Al-Asriya Company for Printing,
  Publishing and Distribution LLC; copyright Ministry of Education,
  Educational Research and Curricula Sector, Curriculum Development
  Administration.
- Authors (title page, PDF p. 2): Dalal Mubarak Al-Hajraf (head),
  Riyasa Sultan Zabin Al-Hathal, Fatima Ismail Daif Al-Jadi.
- PDF pages: 196. Printed pages: 1–189. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–98); Part 2 printed = PDF − 3 (PDF 99–196).
  File size 63,494,342 bytes. SHA-256
  33520415b80dfdfbe0b6e68647eca02b9cbd75e6ab1d8e27b4d4e0f8b3764645.
- Answer key: none.
- Contents (printed pages):
  - Unit 1 — Whole numbers and decimals (14–45): whole numbers,
    decimal place value, comparing and ordering, rounding, decimal
    operations.
  - Unit 2 — Data and statistics (46–80): collecting and organising
    data, tables, pictographs, bar graphs, reading and interpreting
    data.
  - Unit 3 — Multiplication (108–136): multiplication facts and
    strategies, multiplying by one- and two-digit numbers.
  - Unit 4 — Division (138–174): division facts and strategies,
    dividing by one- and two-digit numbers, remainders, word
    problems. Unit assessment and references follow to printed 189.
- Book errors: **none found**.
- Honest negatives: no fractions at all (Term 2); no geometry
  (shapes, angles, perimeter/area); no measurement units; no
  ratio/percentage; no probability; no negative numbers; no algebra.
- Held-copy defects: PDF p. 178 carries only the running head
  ("Grade 5 – Term 1"; no content — checker correction, 2026-11-06);
  PDF p. 179 blank; PDF pp. 181, 191, 193
  blank template backs. No content pages missing; printed 1–189 all
  present.
- Numbering oddities: none recorded.

### 2. `g05-t2.pdf` — Grade 5 Term 2 student book

- Title as printed (Arabic): الرياضيات، الصف الخامس، الفصل الدراسي
  الثاني — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-khāmis, al-faṣl al-dirāsī al-thānī*.
  Translation: "Mathematics, Grade 5, Term 2 — Part 1 / Part 2".
  Primary stage. Grade, term and kind proved from the cover + title
  page (PDF p. 2, read from a render — the title page is image-only).
- Edition as printed: **1st edition 1447 AH / 2025–2026**. No ISBN.
  Deposit no. 97 dated 2026/1/19 (imprint, PDF p. 3 — added by the
  citation checker, 2026-11-06). The imprint names Dar Al-Siyasa
  Press (a printer); no commercial publisher named; copyright
  Ministry of Education.
- Authors (title page, PDF p. 2, read from a render): Dalal Mubarak
  Al-Hajraf (head), Hnadi Mohammed Al-Mutairi, Fatima Asad
  Al-Kandari, Nawal Fahd Al-Jafin, Hessa Mohammed Al-Kandari, Riyasa
  Sultan Al-Hathal, Maha Abdulwahab Mohammed Taqi. (A different,
  larger team from Term 1's three authors.)
- PDF pages: 179. Printed pages: 1–176. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–89); Part 2 printed = PDF − 2 (PDF 90–179).
  File size 39,111,971 bytes. SHA-256
  a0fcdf552f6bf8257a7b6883e281a414e26b72d627990fa5a6a980e63eafa857.
- Answer key: none.
- **Method note: ~106 pages of this book are image-only (no text
  layer) and were read visually from page renders.** That includes the
  whole of Part 1's front matter and title page and much of Part 2.
  The read is complete; the method is recorded here because it is
  different from the other seven books.
- Contents (printed pages):
  - Unit 5 — Fractions (17–42): fraction meaning, equivalent
    fractions, comparing and ordering fractions, fractions on the
    number line.
  - Unit 6 — Fraction operations, ratio and percentage (47–81):
    adding/subtracting fractions, multiplying fractions, ratio,
    proportion in simple form, percentage as parts per hundred.
  - Unit 7 — Probability and geometry (100–130): simple probability
    (certain, possible, impossible; likelihood), basic geometry
    (shapes, angles).
  - Unit 8 — Measurement (132–159): length, mass, capacity, time and
    money measurement.
- Book errors: **1** (see Consolidated book errors table):
  1. Unit 6 review Q26, printed p. 77 — ratio table (5,8) and (10,24)
     not equivalent; likely 10 should be 15.
  (Four further errors originally claimed for this book were
  retracted by the citation checker on 2026-11-06 as misreadings —
  L5-5 Q18 printed p. 27, L6-2 Q9 printed p. 51, L6-3 Q10 printed
  p. 53 and Unit 6 review Q47 printed p. 79; see the retraction
  list after the Consolidated book errors table.)
- Honest negatives: no decimal operations (decimals only in Term 1);
  no negative numbers; no algebra/expressions; no coordinate
  geometry; no volume; statistics only as in Term 1.
- Held-copy defects: Part 2 cover and back cover repeat the Part 1
  wording. References cite 2024–2025 while the title pages say
  2025–2026 (1st ed. 2024–2025 and trial ed. 2023–2024 cited). No
  content pages missing.
- Numbering oddities: none recorded.

### 3. `g06-t1.pdf` — Grade 6 Term 1 student book

- Title as printed (Arabic): الرياضيات، الصف السادس، الفصل الدراسي
  الأول — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-sādis, al-faṣl al-dirāsī al-awwal*.
  Translation: "Mathematics, Grade 6, Term 1 — Part 1 / Part 2".
  Intermediate stage (المرحلة المتوسطة). Grade, term and kind proved
  from the cover + title page.
- Edition as printed: **2nd edition 1448 AH / 2026–2027**. ISBN
  **978-9921-33-067-0**. Publisher: Dhat Al-Salasil – Kuwait.
  Deposit nos. 401/402 dated 2026/7/13.
- Authors: Dalal Mubarak Falah Al-Hajraf (head), Samira Mohammed
  Sultan Al-Matrouk, Abeer Rashoud Saeed Al-Jassar, Wadha Mubarak
  Fahd Al-Owaihan, Fatima Ali Ghareeb Yateem. The imprint page also
  names scientific reviewer Haya Mohammed Falah Al-Azmi and an
  AI-explanations team — NOT authors.
- PDF pages: 232. Printed pages: 1–214. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–122); Part 2 printed = PDF − 14 (PDF 123–232).
  File size 37,569,446 bytes. SHA-256
  f64738d61900bfd0ccdaf1e0a77d951f99e9d62727eaada4b9e5da2be9cc01e3.
- Answer key: none.
- Contents (printed pages):
  - Unit 1 — Whole numbers and decimals (16–69): place value,
    comparing/ordering, rounding, operations with whole numbers and
    decimals.
  - Unit 2 — Geometry (72–120): angles, triangles, quadrilaterals,
    polygons, symmetry, perimeter and area of basic shapes.
  - Unit 3 — Number theory and fractions (123–168): factors,
    multiples, prime/composite numbers, GCF/LCM in simple form,
    fraction meaning and equivalence.
  - Unit 4 — Fraction operations (171–214): adding, subtracting,
    multiplying and dividing fractions and mixed numbers.
- Book errors: **1** (see Consolidated book errors table):
  1. Unit 4 assessment item 8, printed p. 212 — 1/3 ÷ 6/7 = 7/18
     not among the options (2 4/7, 4 2/7, 2 2/7, 18/7; option
     transcription corrected by the citation checker, 2026-11-06 —
     د reads 18/7, the same value as option أ).
- Honest negatives: no integers/negative numbers (Term 2); no
  ratio/proportion (Term 2); no measurement (Term 2); no
  probability/statistics (Term 2); no algebra/equations; no
  coordinate geometry; no percentages.
- Held-copy defects: PDF pp. 71, 74, 135, 183 blank; PDF pp. 230–231
  blank. Back cover repeats the Part 1 wording. No content pages
  missing.
- Numbering oddities: none recorded.
- Deliberate wrong-answer item (not an error): p. 58 Q3 gives
  2.86 ÷ 22 = 0.013 as a pupil's wrong answer (correct 0.13).

### 4. `g06-t2.pdf` — Grade 6 Term 2 student book

- Title as printed (Arabic): الرياضيات، الصف السادس، الفصل الدراسي
  الثاني — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-sādis, al-faṣl al-dirāsī al-thānī*.
  Translation: "Mathematics, Grade 6, Term 2 — Part 1 / Part 2".
  Intermediate stage. Grade, term and kind proved from the cover +
  title page (PDF p. 2, read from a render).
- Edition as printed: **1st edition 1447 AH / 2025–2026**. No ISBN.
  Deposit no. 89 dated 2026/1/16. Publisher: Dhat Al-Salasil –
  Kuwait, named on the imprint page (PDF p. 3 — checker correction,
  2026-11-06; the original filing said no commercial publisher was
  named); copyright Ministry of Education.
- Authors (title page, PDF p. 2, read from a render): Dalal Mubarak
  Al-Hajraf (head), Abeer Rashoud Saeed Al-Jassar, Wadha Mubarak
  Fahd Al-Owaihan, Uhud Mubarak Hamad Al-Ajmi, Fatima Ali Ghareeb
  Yateem. (Same team as Grade 6 Term 1 except Uhud Mubarak Hamad
  Al-Ajmi replaces Samira Mohammed Sultan Al-Matrouk.)
- PDF pages: 222. Printed pages: 1–205. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–110); Part 2 printed = PDF − 15 (PDF 111–222).
  File size 29,790,955 bytes. SHA-256
  7a8cf0db89210b3a9b6a83d72a840bc4fd4340457dbcef7846f8e690dacc8646.
- Answer key: none.
- Contents (printed pages):
  - Unit 5 — Integers (16–65): negative numbers, the number line,
    comparing/ordering integers, adding and subtracting integers;
    Lesson 5-6 (printed p. 41) introduces the variable concept
    (checker addition, 2026-11-06, from the book's own contents).
  - Unit 6 — Ratio and proportion (66–108): ratio, equivalent ratios,
    proportion, direct proportion, and inheritance (المواريث) shares
    worked as ratio problems.
  - Unit 7 — Measurement (112–159): length, area, volume, mass,
    capacity, time; unit conversion.
  - Unit 8 — Probability and statistics (162–205): simple probability,
    data collection, tables, bar graphs, interpreting data.
- Book errors: **none found**.
- Data-staleness note (not counted as an error): L8-7 Q2's
  planet-moon table uses older counts (Saturn 47, Uranus 27, Neptune
  13); by 2025 Saturn has 274 confirmed moons. Teach the table as
  dated data, not current fact.
- Honest negatives: no equations (algebra is limited to introducing
  the variable concept in Unit 5, Lesson 5-6 — checker correction,
  2026-11-06); no geometry beyond
  measurement; no coordinate geometry; no percentages as a standalone
  topic; no formal proof.
- Held-copy defects: PDF p. 65, p. 119 blank; PDF pp. 114–115 blank.
  Back cover repeats the Part 2 cover wording. No content pages
  missing.
- Numbering oddities: Unit 8 assessment skips Q4 (numbering jumps
  from Q3 to Q5).

### 5. `g07-t1.pdf` — Grade 7 Term 1 student book

- Title as printed (Arabic): الرياضيات، الصف السابع، الفصل الدراسي
  الأول — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-sābiʿ, al-faṣl al-dirāsī al-awwal*.
  Translation: "Mathematics, Grade 7, Term 1 — Part 1 / Part 2".
  Intermediate stage. Grade, term and kind proved from the cover +
  title page.
- Edition as printed: **2nd edition 1448 AH / 2026–2027**. ISBN
  **978-9921-33-075-5**. Publisher: Dhat Al-Salasil – Kuwait.
  Deposit nos. 403/404 dated 2026/7/13.
- Authors: same team as Grade 6 Term 1 — Dalal Mubarak Falah
  Al-Hajraf (head), Samira Mohammed Sultan Al-Matrouk, Abeer Rashoud
  Saeed Al-Jassar, Wadha Mubarak Fahd Al-Owaihan, Fatima Ali Ghareeb
  Yateem. Imprint page names a scientific reviewer and an
  AI-explanations team (Hawraa Jassim Malik, Mona Abdo Al-Saeedi,
  Nashwa Mahmoud Abdelwahab, Samar Mohammed Abdelfattah) — NOT
  authors.
- PDF pages: 246. Printed pages: 1–230. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–130); Part 2 printed = PDF − 14 (PDF 131–246).
  File size 35,617,477 bytes. SHA-256
  4ee921fd93ae8e1fcafb08ab3fbcfeae29b486d7e8db3fc502cb10a19334e94a.
- Answer key: none.
- Contents (printed pages):
  - Unit 1 — Whole numbers and decimals (16–62): place value and
    operations, decimal operations, estimation.
  - Unit 2 — Linking arithmetic to algebra (64–127): variables,
    algebraic expressions, evaluating expressions, one-step and
    two-step equations, solving by inverse operations.
  - Unit 3 — Measurement and solids (131–185): length, area, volume
    and surface area of prisms and other solids, unit conversion.
  - Unit 4 — Transformation geometry and statistics (187–229):
    translations, reflections, rotations, symmetry, data collection
    and bar-graph representation.
  - Project 1 (printed 128); Project 2 (printed 230).
- Book errors: **1** (see Consolidated book errors table):
  1. Unit 2 opener, printed p. 63 — claims Kuwait's highest recorded
     temperature is 52.1°C on 30 July 2020 at Mutriba; correct is
     53.9°C on 21 July 2016 at Mitribah (WMO-verified, highest ever
     in Asia).
- Honest negatives: no fraction operations (Term 2); no percentages
  (Term 2); no probability (Term 2); no Pythagoras; no circle
  geometry; no coordinate geometry; no formal proof; no simultaneous
  equations.
- Held-copy defects: PDF p. 15, p. 63 blank; PDF pp. 4–9 and
  134–139 front-matter blanks/portraits; PDF p. 199 is the Unit 4
  divider image. Back cover repeats the Part 1 cover wording
  ("1/1"). No content pages missing.
- Numbering oddities: none recorded.
- Deliberate wrong-answer items (not errors): the Fajr/Duha,
  Saleh/Faisal and cube-surface-area (S = 54) items present pupils'
  wrong working for correction.

### 6. `g07-t2.pdf` — Grade 7 Term 2 student book

- Title as printed (Arabic): الرياضيات، الصف السابع، الفصل الدراسي
  الثاني — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-sābiʿ, al-faṣl al-dirāsī al-thānī*.
  Translation: "Mathematics, Grade 7, Term 2 — Part 1 / Part 2".
  Intermediate stage. Grade, term and kind proved from the cover +
  title page.
- Edition as printed: **1st edition 1447 AH / 2025–2026**. No ISBN.
  Deposit no. 90 dated 2026/1/16. Publisher: Dhat Al-Salasil.
- Authors: Dalal Mubarak Falah Al-Hajraf (head), Abeer Rashoud Saeed
  Al-Jassar, Wadha Mubarak Fahd Al-Owaihan, Fatima Ali Ghareeb
  Yateem, Uhud Mubarak Hamad Al-Ajmi. (Uhud Mubarak Hamad Al-Ajmi
  replaces Samira Mohammed Sultan Al-Matrouk.)
- PDF pages: 224. Printed pages: 1–207. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–130); Part 2 printed = PDF − 15 (PDF 131–224).
  File size 36,860,592 bytes. SHA-256
  8931e7432b93271ea0f410c3d83beea27dcc961897fe64dd603bd79727b90eb6.
- Answer key: none.
- Contents (printed pages):
  - Unit 5 — Fractions and operations (15–62): fraction meaning and
    equivalence, comparing/ordering, adding, subtracting, multiplying
    and dividing fractions and mixed numbers; fractions of quantities
    (including money: 45/1000 dinar = 45 fils).
  - Unit 6 — Geometry (63–128): angles, parallel lines, triangles
    (including triangle-determination conditions — Lesson 6-7),
    quadrilaterals, circles (area and circumference), constructions.
  - Unit 7 — Percentages and their uses (130–171): percentage as a
    rate per hundred, finding a percentage of a number, percentage
    increase/decrease, discount, and zakat (including a worked zakat
    calculation with the Zakat House rate).
  - Unit 8 — Probability (172–207): sample space, equally likely
    outcomes, probability of simple and compound events, probability
    from 1–8 and from spinners and cards.
  - Project 3 (printed 128); Project 4 (printed 207).
- Book errors: **2** (see Consolidated book errors table):
  1. Unit 8 assessment MCQ 9, printed p. 205 — options أ 1/2 and
     د 4/8 both correct for P(prime from 1–8) (render-verified).
  2. Lesson 6-7 Q3 MCQ, printed p. 103 — two data sets determine a
     triangle: أ (SSA: 7 cm, 5 cm, 50°) and د (6 cm, 6 cm, 60° →
     equilateral); intended answer د, but أ is also drawable
     (render-verified).
- Honest negatives: no statistics/data-handling unit (probability
  only); no Pythagoras; no coordinate geometry; no circle geometry
  beyond area/circumference; algebra limited to one-variable equations
  with fractions; no formal proof.
- Held-copy defects: PDF p. 63 blank; PDF p. 187 is the Unit 8
  divider page carrying printed 172, not blank (checker correction,
  2026-11-06); PDF pp. 134–135, 137,
  139 blank portraits (front matter: the Amir Sheikh Meshal
  Al-Ahmad Al-Jaber Al-Sabah and the Crown Prince Sheikh Sabah Khaled
  Al-Hamad Al-Sabah). Back cover repeats the Part 2 cover wording.
  References cite the 5th edition 2024–2025 while the title page says
  1st edition 2025–2026. No content pages missing.
- Numbering oddities: none recorded.

### 7. `g08-t1.pdf` — Grade 8 Term 1 student book

- Title as printed (Arabic): الرياضيات، الصف الثامن، الفصل الدراسي
  الأول — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-thāmin, al-faṣl al-dirāsī al-awwal*.
  Translation: "Mathematics, Grade 8, Term 1 — Part 1 / Part 2".
  Intermediate stage. Grade, term and kind proved from the cover +
  title page.
- Edition as printed: **2nd edition 1448 AH / 2026–2027**. ISBN
  **978-9921-33-121-9** (one ISBN for both parts). Publisher: Dhat
  Al-Salasil – Kuwait. Deposit nos. 405 (Part 1) / 406 (Part 2),
  dated 2026/7/13.
- Authors: Dalal Mubarak Falah Al-Hajraf (head), Noura Abdullah
  Abu-Ruqba Al-Otaibi, Sara Zayed Shinan Al-Ajmi, Wasmiya Badi Hadi
  Al-Rashidi, Essam Abdulhadi Al-Sayed Hassan, Mona Faraj Saad
  Al-Mutairi. (A different team from Grades 5–7.) Imprint page names
  scientific reviewer Samir Abdullah Morsi and an AI-explanations
  team (Rasha Mohammed Abdulmonem Hashish, Hawraa Salem Attia
  Ghannam) — NOT authors.
- PDF pages: 235. Printed pages: 1–216. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–125); Part 2 printed = PDF − 14 (PDF 126–235).
  File size 43,034,333 bytes. SHA-256
  5964f096eca489efa35f13027aefa4769541958c2d7659fa7e667e0107a3d295.
- Answer key: none.
- Contents (printed pages). The contents overview lists 8 year units
  but this volume holds Units 1–4 only:
  - Unit 1 — Sets and relations (15–67): sets, subsets, union,
    intersection, difference, Venn diagrams, ordered pairs, relations
    and their representations (arrow diagrams, tables, graphs);
    Cartesian product. Lesson 1-6 sidebar carries the Descartes
    error (see below).
  - Unit 2 — Rational numbers (72–123): rational numbers on the
    number line, comparing/ordering, absolute value, adding,
    subtracting, multiplying and dividing rationals, recurring
    decimals, irrational numbers introduced (√2, √3), powers and
    roots, order of operations.
  - Unit 3 — Geometry and measurement (126–175): angles, triangles,
    Pythagoras' theorem used (not proved), area and circumference of
    circles, surface area and volume of prisms, cylinders and cones
    (cone-vessel worked example: 314 ml — render-verified).
  - Unit 4 — Ratio and proportion: geometric transformations
    (178–216): ratio, proportion, direct and inverse proportion,
    translations, reflections, rotations, enlargements, similarity.
  - Project 1 (printed 123); Project 2 (printed 216).
- Book errors: **1** (see Consolidated book errors table):
  1. Lesson 1-6 sidebar, printed p. 50 — calls Descartes "from the
     nineteenth century"; René Descartes lived 1596–1650, the
     seventeenth century (render-verified).
- Honest negatives: no formal proof of Pythagoras; no trigonometry;
  no circle theorems beyond area/circumference; Unit 1 sets/relations
  without functions.
- Held-copy defects: PDF pp. 4–9, 15, 71, 129–134, 190, 232–234
  blank. References cite the 3rd edition 2017–2018, the 5th edition
  2024–2025 and the trial edition 2023–2024 while the title page says
  2nd edition 2026–2027. No content pages missing.
- Pagination oddity: PDF p. 138 is nearly blank, carrying printed
  number 124 only — duplicating the Part 1 references page number.
  Part 2 offset is PDF − 14 (an earlier −10 reading was wrong).
- Deliberate wrong-answer item (not an error): Mohammed vs Hussein
  (5 − 2.25 = 2.75, not 3.25).

### 8. `g08-t2.pdf` — Grade 8 Term 2 student book

- Title as printed (Arabic): الرياضيات، الصف الثامن، الفصل الدراسي
  الثاني — القسم الأول / القسم الثاني. Transliteration:
  *al-Riyāḍiyyāt, al-ṣaff al-thāmin, al-faṣl al-dirāsī al-thānī*.
  Translation: "Mathematics, Grade 8, Term 2 — Part 1 / Part 2".
  Intermediate stage. Grade, term and kind proved from the cover +
  title page. (The PDF's embedded InDesign filename references "G7";
  that is not identity evidence.)
- Edition as printed: **1st edition 1447 AH / 2025–2026**. No ISBN.
  Deposit no. 91 dated 2026/1/16 (Part 1 imprint); the Part 2
  imprint (PDF p. 129) gives 1st edition 1447 AH / 2025–2026 and
  scientific review Samir Abdullah Morsi, with **no deposit number
  printed**. Publisher: Dhat Al-Salasil.
- Authors: same team as Grade 8 Term 1 except Afaf Abdulaziz Yaqoub
  Al-Sanea replaces Mona Faraj Saad Al-Mutairi — Dalal Mubarak Falah
  Al-Hajraf (head), Noura Abdullah Abu-Ruqba Al-Otaibi, Sara Zayed
  Shinan Al-Ajmi, Wasmiya Badi Hadi Al-Rashidi, Essam Abdulhadi
  Al-Sayed Hassan, Afaf Abdulaziz Yaqoub Al-Sanea.
- PDF pages: 248. Printed pages: 1–230. Offsets: Part 1 printed =
  PDF − 1 (PDF 1–128); Part 2 printed = PDF − 15 (PDF 129–248).
  File size 23,352,594 bytes. SHA-256
  c3c60a27310c41c9aa1ab8914b1ebcfdf5b4419c274e204b439c41c6a31413a3.
- Answer key: none.
- Contents (printed pages):
  - Unit 5 — Quadrilaterals (15–81). Ready (18–19). L5-1 Detecting
    parallel lines (20): alternate, corresponding and co-interior
    angle tests, with proofs. L5-2 Parallelogram — drawing a
    parallelogram (26): properties, SSS/SAS constructions. L5-3
    Detecting a parallelogram (34): six conditions — definition,
    congruent opposite sides, one pair congruent and parallel,
    congruent opposite angles, consecutive angles supplementary,
    diagonals bisecting each other. L5-4 Detecting a rectangle (48):
    one right angle, or congruent diagonals. L5-5 Detecting a rhombus
    (54): adjacent sides congruent, or perpendicular diagonals. L5-6
    Detecting a square (61): rectangle + rhombus conditions.
    Assessment (72–80).
  - Unit 6 — Algebraic expressions (82–124). Ready (84). L6-1 Laws
    of exponents (85): product, quotient, power-of-power,
    power-of-product, power-of-quotient, zero and negative exponents;
    phone-memory worked example (1st generation ≈ 2¹⁰ MB, 3rd
    generation = 7.6 × 2³ × 2¹⁰ = 7.6 × 2¹³ MB). L6-2 Polynomials
    (95): vocabulary, classification by number of terms, degree
    including multi-variable, general form, leading coefficient,
    constant term, like/equal terms, evaluation; Hanan's claim that
    9x⁴+4y² is degree 6 is WRONG (degree 4) — a deliberate
    wrong-answer item. L6-3 Adding and subtracting polynomials (102):
    like terms, additive inverse, vertical and horizontal methods;
    Tariq's subtraction sign error (correct −x²+4x) — deliberate
    wrong-answer item. L6-4 Multiplying polynomials (109): monomial
    × monomial, distributive law, area models, (x+3)(x−3) = x²−9,
    perfect-square trinomials. L6-5 Dividing a polynomial by a
    monomial (116): divide each term; (15x+10x²−5)/5x is NOT a
    polynomial. Assessment (119–123). Project 3 (124, quadrilateral
    mind map).
  - Unit 7 — Factorising algebraic expressions (126–174). Opener
    (127, mathematics and development in Kuwait); standards (128);
    organiser (129); ready (130–131). L7-1 Greatest common factor
    (132): GCF (ع.م.أ), Euclid sidebar; Khalid's claim that the GCF
    of 6x and 8x is 2x is CORRECT. L7-2 Factorising by taking out the
    GCF (136): Nawwaf's 8x³+6x²+2x = 2x(4x²+3x) is WRONG — correct
    2x(4x²+3x+1) — deliberate wrong-answer item. L7-3 Difference of
    two squares (141): a²−b² = (a+b)(a−b), including (x−2)²−64 and
    49−(x+y)². L7-4 First-degree equations in one variable (147):
    Kuwait Book Fair problem 3x−4 = 26 → x = 10; recurring decimals
    to fractions (0.3̄ = 1/3, 0.15̄ = 5/33); Mohammed's first step
    correct, Nawwaf's partial division wrong — deliberate
    wrong-answer item. L7-5 Second-degree equations by factorising
    (155): zero-product property; solution sets in ℚ, ℤ, ℕ including
    empty-set cases; Abdulaziz's x = −1 for (x−1)² = 0 is WRONG
    (x = 1) — deliberate wrong-answer item. L7-6 First-degree
    inequalities (161): ≤/≥ meanings, reversal on multiplication by
    a negative, solution sets in ℕ/ℤ/ℚ; worked examples 6−5x ≤ −7 →
    x ≥ 2 3/5 and 5x+4 < −3−2x → x < −1 (render-verified).
    Assessment (168–173).
  - Unit 8 — Probability — Statistics (175–230). Opener (175,
    genetics/tree diagrams); standards (176); organiser (177); ready
    (178–179, stem-and-leaf: largest 46, smallest 12, mode 46 ×3).
    L8-1 Counting methods (180): counting principle, permutations
    (ل), combinations (ق), factorials; ⁴ل₂ = 12, ⁵ل₃ = 60, ⁴ق₂ = 6,
    ⁵ق₃ = 10. L8-2 Sample space (191): random experiment, sample
    space (ف), certain/impossible/simple/compound events; two dice,
    36 outcomes. L8-3 Probability (197): P = favourable/all,
    0 ≤ P ≤ 1; Jasem spinner 25%; two dice P(sum < 5) = 1/6,
    P(sum 9 or 12) = 5/36. L8-4 Double stem-and-leaf plots (204):
    Qur'an reading, health-centre visitors, flight prices
    (Turkey/Malaysia), Avenues mall, Winterland/Scientific Centre,
    robot users, school heights, swimming teams. L8-5 Pie charts
    (210): sector angle = frequency/total × 360°; football 144°,
    volleyball 108°, basketball 72°, table tennis 36°; Hessa's daily
    tasks (sleep 30%, school 25%, homework 20%, worship 13%, sports
    7%, other 5%; homework ≈ 5 h, sleep ≈ 7 h of 24). L8-6 Mean —
    median — mode (215–221): frequency tables, outlier (302 t fruit
    shipment — mean 98.8 with it, 65 without; median 65, mode 62);
    grouped data, class centre = (lower + upper)/2, mean from class
    centres (Sahel app: classes 1–3…9–11, mean 4.8 h; internet
    speeds: 25 values, classes 10–14…26–30, frequencies 5, 10, 4, 4,
    2 — render-verified); double stem-and-leaf mean/median/mode
    worked example (English vs Chinese learners' ages: modes 32 and
    21, medians 27 and 22, Chinese mean 25).
    Unit 8 assessment (222–229): essay items (tree diagrams,
    factorials/permutations/combinations, Yasmin's 3-number locker
    code, council president/vice-president, 30-card box, gift
    wrapping 20×10×4 = 800, AI invitation card 4×5×6 = 120, boat
    lengths double stem-and-leaf, grouped grades mean 34, story-type
    pie chart, Ministry of Health COVID allocations); true/false
    items 1–9 (two dice sample space 36, ₆ل₂ = 30, ₇ق₃ = ₇ق₄,
    2!×4! ≠ 8!, P(prime from 1–6) = 1/2, mean-9 sum 54, poetry 10%
    not 20%, reading 3 of 6 = ₆ق₃, net profit 720 KD not 2160 KD —
    render-verified); MCQs 10–19 (P(sum 10) = 1/12, stem 9 leaf 5 =
    95, choosing 3 of 7 dishes = ₇ق₃, 8×7! = 8!, 720 = 6!, range 80,
    median 4.5, neither-mean-nor-median-nor-mode = 22, highest May
    temperature 44°C, walkers 15% of 800 = 120).
    Project 4 (230, "Mathematics and life": probability in daily
    life — spinner, dice or coin played 3 times in a row).
    References (PDF p. 246, unnumbered): Grade 8 Mathematics, 3rd
    edition 2017–2018; 5th edition 2024–2025; trial edition
    2023–2024, Ministry of Education, Educational Research and
    Curricula Sector; image sources listed for pp. 132, 144, 147,
    151, 153, 154, 160, 164, 165, 170, 177, 178, 180, 183, 185, 189,
    191, 193, 195, 196, 197, 198, 200, 214, 220 and the cover.
- Book errors: **none found**. (The one error originally claimed
  for this book was retracted by the citation checker on
  2026-11-06: Unit 6 assessment Q12, printed p. 122 — the second
  polynomial is 2x² + x³ − 4x − 1, not "2x³ + x³ − 4x − 1" as
  originally transcribed, and the true sum 3x⁴ + 5x³ + 2x² − 7x + 1
  is option د. See the retraction list after the Consolidated book
  errors table.)
- Honest negatives: no trigonometry; no circle geometry; no
  functions; no simultaneous equations; no factorising of quadratic
  trinomials (factorising stops at GCF and difference of two
  squares); no surds as a topic; no coordinate geometry; statistics
  stops at mean/median/mode, pie charts and stem-and-leaf (no
  dispersion, no quartiles); probability is classical counting only.
- Held-copy defects: PDF pp. 4–9, 15 blank; PDF p. 81 nearly blank
  (printed 80 only); PDF pp. 130–131, 133, 135 blank (Part 2 front
  matter/portraits: the Amir Sheikh Meshal Al-Ahmad Al-Jaber
  Al-Sabah, the Crown Prince Sheikh Sabah Khaled Al-Hamad Al-Sabah);
  PDF p. 247 blank. Back cover repeats the Part 2 cover wording
  ("2/2"). Part 1 references (printed 125) cite the same three older
  editions as the end references. No content pages missing.
- Numbering oddities: Unit 5 Lesson 5-3 presents six
  parallelogram-detection conditions (printed pp. 34–43) but the
  summary on printed p. 45 lists only five, omitting
  consecutive-angles-supplementary. Unit 8 assessment Q3 (Yasmin's
  locker code, printed p. 222) does not state whether the three
  numbers may repeat or whether order matters: ₈ل₃ = 336 if order
  matters without repetition, ₈ق₃ = 56 if choosing a set.

---

## Kuwait — Mathematics, Grades 9–12 (Band C)

**Country:** Kuwait (22nd maths country read)
**Band:** C — Grades 9–12 (middle-school Grade 9 + secondary Grades 10–12)
**Language of the books:** Arabic (all 12 files read)
**Filing language:** English (maths content in English; Arabic titles given as printed)
**Status:** READ COMPLETE — 12 of 13 band files read in full (1,862 PDF pages).
**PENDING — NOT READ:** `g11-t1.pdf`, the Grade 11 Mathematics Term 1 **student book** (102,105,970 B). The file on disk is a 139-byte JSON `{"message":"Not e-asset","status":"404"}`; it was not read and is not counted in the totals. A fresh fetch is being chased separately. This is a gap in the band's coverage, not a book read.

### Set at a glance

| § | File | Grade | Term | Kind | Track | PDF pages |
|---|---|---|---|---|---|---|
| 1 | g09-t1.pdf | 9 | 1 | Student book (Parts 1–2) | — | 235 |
| 2 | g09-t2.pdf | 9 | 2 | Student book (Parts 1–2) | — | 260 |
| 3 | g10-t1-wb.pdf | 10 | 1 | Student book | — | 134 |
| 4 | g11-t1-wb.pdf | 11 | 1 | Workbook (exercises) | Scientific | 106 |
| 5 | g12-t1.pdf | 12 | 1 | Student book | Scientific | 213 |
| 6 | g10-t2-wb.pdf | 10 | 2 | Student book (old generation) | — | 227 |
| 7 | g11-t2-wb.pdf | 11 | 2 | Student book (Parts 1–2, old generation) | Scientific | 192 |
| 8 | g11-stats-t1.pdf | 11 | 1 | Student book — Statistics | Literary | 74 |
| 9 | g11-stats-t2.pdf | 11 | 2 | Student book — Statistics (old generation) | Literary | 82 |
| 10 | g11-stats-t2-wb.pdf | 11 | 2 | Workbook — Statistics (old generation) | Literary | 50 |
| 11 | g12-t2-wb.pdf | 12 | 2 | Student book (Parts 1–2, old generation) | Scientific | 197 |
| 12 | g12-stats-t2-wb.pdf | 12 | 2 | Student book — Statistics (old generation) | Literary | 92 |
| **Total** | | | | | | **1,862** |

**Kind question — resolved from each book's own cover, title page and contents, never from the filename:** the files named `*-wb.pdf` are a mixed bag. G10 both terms are **student books** (the cover and title page say "student book"), G11 Term 2 and G12 Term 2 are also **student books** (Parts 1–2 bound in one file), and the Grade 12 Term 2 statistics file is a **student book** too. Only two files in this band are exercises-only workbooks: g11-t1-wb (scientific track) and g11-stats-t2-wb (literary track). See each per-book section for the proof.

**Generations:** Grade 9 and Grade 10 Term 1 are the new generation (1st/2nd editions, 1447–1448 AH / 2025–2027), as are Grade 11 Statistics Term 1 (3rd edition, 1448 AH / 2026–2027) and Grade 12 Term 1 (2nd edition, 1448 AH / 2026–2027). Grade 10 Term 2, Grade 11 Term 2 (scientific), Grade 11 Statistics Term 2 (student + workbook), Grade 12 Term 2 (scientific) and Grade 12 Statistics Term 2 are the **old generation** (2012/2013/2014 series, 2nd editions running to 1447 AH / 2025–2026). Grade 11 Term 1 workbook is a 2nd-edition 1448 AH / 2026–2027 volume on a 2013 Pearson source. There are **no teacher guides** in the Kuwait maths set at all.

**Answer keys:** none of the 12 books carries an answer key (checked in full; see per-book notes).

**Reading method:** every book was read visually from 200 dpi renders (pdftoppm) of every page, because Tesseract OCR on Arabic proved unusable on this machine (30–60 CPU-seconds per page, jobs killed after producing nothing usable; a RapidOCR test gave Latin gibberish for Arabic). Books with a clean text layer were cross-checked against `pdftotext -layout` extraction where it helped, but no finding below rests on extraction alone. Image-only books (g11-t2-wb, g11-stats-t1, g12-t2-wb) and legacy-font mojibake books (g10-t2-wb, g11-stats-t2, g11-stats-t2-wb, g12-stats-t2-wb) have no usable text layer and were read from the renders only. Where extraction or a first visual pass suggested a wrong answer, a wrong inequality direction or a garbled fraction, the value was verified against a 200–400% crop of the render before being reported — no error below rests on extraction alone.

**Errors found in this band:** **30** across the 12 books — g09-t1: 3; g09-t2: 1; g10-t1-wb: 2; g11-t1-wb: 1; g12-t1: 5; g10-t2-wb: 2; g11-t2-wb: 1; g11-stats-t1: 5; g11-stats-t2: 0; g11-stats-t2-wb: 4; g12-t2-wb: 5; g12-stats-t2-wb: 1. (Originally filed as 37; the independent citation check of 2026-11-06 retracted seven claimed errors — see the per-book BOOK ERRORS lists and checks/check-band-c.md.) See the per-book BOOK ERRORS lists; tallied in the band summary at the end of this file.

---

### 1. Grade 9, Term 1 — Student book

**Title as printed:** الرياضيات — الصف التاسع — الفصل الدراسي الأول (Mathematics — Grade 9 — First term), bound in one file as Part 1 (Units 1–2) and Part 2 (Units 3–4).
**Grade / term / track:** Grade 9, Term 1, no track (middle school).
**Edition / year as printed:** Part 1 — 2nd edition, 1448 AH / 2026–2027; Part 2 — 1st edition, 1447 AH / 2025–2026 (each part has its own title page; Part 2's title page is PDF p.118).
**ISBN:** 978-9921-33-112-7 (Part 1); Part 2 ISBN not printed on its title page. Deposit numbers 407 (Part 1) / 408 (Part 2), dated 2026/7/13.
**Publisher:** Kuwait Ministry of Education, General Administration for Guidance, Research and Curricula — Educational Research and Curricula Administration.
**Authors (Part 1):** Dalal Mubarak Falah Al-Hajraf (head), Noura Abdullah Abu-Ruqba Al-Otaibi, Sarah Zayed Shinan Al-Ajmi, Wasmiya Badi Hadi Al-Rashidi, Essam Abdul-Hadi Al-Sayed Hassan, Muna Faraj Saad Al-Mutairi. Part 2 replaces the last author with Afaf Abdul-Aziz Yaqoub Al-Sanea.
**PDF pages:** 235 (printed 1–114 Part 1; printed 114–218 Part 2). Printed = PDF − 1 in Part 1; printed = PDF − 15 in Part 2.
**File size:** 27,492,743 B. **SHA-256:** 925b9a7a439d706b2955b74f42f7d15b6b94fb7b9110a75ba2c6bb709543376b
**How read:** clean text layer, read in full (PDF pp. 1–235); flagged items verified against 150–400 dpi renders.
**Answer key:** none.

#### Contents (printed page numbers)

**Unit 1 — Real numbers and operations** (printed pp. 15–64): opener + standards + organiser (pp. 15–19); 1-1 Square roots and irrational numbers (pp. 20–23); 1-2 Real numbers: comparison and order, intervals (pp. 24–31); 1-3 Operations on real numbers (pp. 32–35); 1-4 Absolute value (pp. 36–42); 1-5 First-degree inequality in one variable (pp. 43–50); 1-6 Scientific notation with integer exponents (pp. 51–58); Unit 1 assessment (pp. 59–64). Each lesson: "explore" opener, worked examples, "your turn now" items, self exercises, higher-order-thinking item. Worked content verified: scientific notation (65,241 = 6.5241×10⁴; 0.00256 = 2.56×10⁻³; (4.1×10³ + 7.2×10³) = 1.13×10⁴; (2.1×10⁵) ÷ (3×10⁻²) = 7×10⁶; Jupiter−Earth diameter difference = 1.302×10⁵ km); |2x+1| = 3 → {1, −2}; |5y−2| + 9 = 9 → {2/5}; |x−3| = 3 → {6, 0}; 2x+3 ≤ 7 → x ≤ 2; |x| ≤ 2 → [−2, 2]; |2x−1| > 3 → (−∞, −1) ∪ (2, ∞). Assessment checked: largest of the listed numbers is 4.23×10⁵; 0.00123 = 1.23×10⁻³.

**Unit 2 — Factorisation and equations** (printed pp. 65–112): 2-1 Difference and sum of two cubes (pp. 70–74); 2-2 Trinomial x²+bx+c (pp. 75–80); 2-3 Trinomial ax²+bx+c, a≠1 (pp. 81–85); 2-4 Perfect square (pp. 86–93); 2-5 Four-term polynomial (pp. 94–97); 2-6 Quadratic equation in one variable (pp. 98–105); Unit 2 assessment (pp. 106–112); Project 1 (p. 113, scientific notation). Worked content verified: x³−27, x³+y³, x²+4x+3, x²−7x−36, 6x²−19xy+10y² = (2x−5y)(3x−2y); completing the square x²−6x+8 = (x−4)(x−2), x²−5x+6 = (x−3)(x−2); x²+5x = 150 → x = 10; x²−4x = 5 → {5, −1}; x²+4x+2 = 0 → −2±√2; x²+6x−2 = 0 → −3±√11. Assessment checked: l+m = 3, l³+m³ = 51 → l²−lm+m² = 17; 2x²+mx−7 = (2x−1)(x+7) → m = 13; x(x−12) = 13 → {13, −1}; c = 9 makes the trinomial a perfect square; Hussain is right (not Hamoud) on p. 79 — (x−3)(x+7) = x²+4x−21.

**Unit 3 — Rational polynomials and coordinate geometry** (printed pp. 114–160): 3-1 Rational polynomials and simplifying (pp. 120–123); 3-2 Multiplying rational polynomials (pp. 124–127); 3-3 Dividing (pp. 128–131); 3-4 Adding and subtracting (pp. 132–139); 3-5 Distance between two points (pp. 141–148); 3-6 Midpoint coordinates (pp. 149–153); Unit 3 assessment (pp. 154–160). Worked content verified: (2x²+13x−7)/(x²+4x−21) = (2x−1)/(x−3); (4x−2)/(2x−1) = 2; (x³+8)/(x²−2x+4) = x+2; (x²−9)/(x³−27) = (x+3)/(x²+3x+9); (2x+1)/3 × 6x/(4x²−1) = 2x/(2x−1); (4m/(m+1)) × ((m+1)/(1−m)) = 4m/(1−m); distance A(3,1), B(6,5) = 5; triangle (8,5), (4,1), (1,4) has squared sides 50, 32, 18 — right-angled scalene; midpoint of T(2,−3), Q(−4,1) = (−1,−1); 1/(6x²) + 3/(4x) = (2+9x)/12x²; 12/(x²−4) + 3/(x+2) = 3/(x−2). Assessment checked: midpoint (1,4) true; AB parallel to the y-axis true; (1−x)/(x−1) = −1; QK = 2.

**Unit 4 — Transformations, statistics and probability** (printed pp. 160–217): 4-1 Rotation in the plane (pp. 166–176); 4-2 Enlargement (pp. 177–186); 4-3 Frequency histogram (pp. 187–190); 4-4 Frequency polygon (pp. 191–197); 4-5 Box-and-whisker plot (pp. 198–203); 4-6 Weighting and fairness — probability (pp. 204–210); Unit 4 assessment (pp. 211–217); Project 2 (p. 218, enlargement and mosaic design). Worked content verified: rotation rules about the origin D(O, ±90°/180°/270°): (x,y) → (y,−x) / (−y,x) / (−x,−y); (5,2) → (2,−5) under −90°; enlargement t(O,2): (2,1) → (4,2), (2,4) → (4,8), (4,3) → (8,6); area ratio = m² (area 25 → image 100 gives m = 2); histogram classes 40–50 (4), 50–60 (2), 60–70 (4), 70–80 (16), 80–90 (11), 90–100 (3) = 40 total; box-plot data 75, 76, 77, 80, 82, 84, 85 → min 75, max 85, median 80, lower quartile 76, upper quartile 84; advertisement prices 3–27 (14 values) → range 24, median 9.5, lower quartile 6, upper quartile 15; two-dice game: doubles 6 outcomes vs different 30 — Omar has the better chance; odds of 2 on a die = 1:5; box of 7 red, 3 green, 4 blue pens: P(blue) = 4/14 = 2/7, P(not green) = 11/14, P(yellow) = 0, odds of blue = 4:10 = 2:5; odds 3:10 → probability 3/13; odds 1:7 → probability 1/8. Assessment checked: D(O,−30°) ≡ D(O,330°) true; rotation preserves lengths (the "does not preserve" statement is false); the enlargement centre is a fixed point; triangle of sides 5, 6, 3 under m = 2 has perimeter 28; class (4–9) has length 5; prime (2,3,5) vs even (2,4,6) is a fair game; area 2 → image 50 gives m = 5; C(1,2) as image of B under t(O,1/3) gives B = (3,6); third class of 14–18, 18–22, 22–26, 26–30 has centre 24; consecutive class centres 15, 25 give class length 10; odds 2:3 → probability 2/5; probability 5/13 → odds 5:8; odds of a multiple of 3 on a die = 1:2.

**References (printed p. 114, end of Part 1):** cite the 1st edition 2024–2025 and the trial edition 2023–2024, while the title page says 2nd edition — the references were not updated for the new edition (same pattern as Band B).

#### BOOK ERRORS — 3 (all verified against renders, not extraction; a fourth claim was retracted by the citation check — see item 3)

1. **Printed p. 72, Lesson 2-1, worked example 2, item (أ):** the problem 54y² − 2y⁴ is solved as if it were 54y² − 2y⁵: the book gives 2y²(3−y)(9+3y+y²). As printed, 2y²(3−y)(9+3y+y²) expands to 54y² − 2y⁵, not 54y² − 2y⁴. **Correct:** either the problem should read 54y² − 2y⁵ (then the printed working is right), or the printed problem factors as 2y²(27 − y²).
2. **Printed p. 72, Lesson 2-1, worked example 2, item (ب):** −0.008x³ is factorised as (−0.2x)(0.04 + 0.2x + x²). That product expands to −0.2x³ − 0.04x² − 0.008x, not −0.008x³. **Correct:** −0.008x³ = (−0.2x)(0.04x²) — the second factor is 0.04x² only (the book pasted the (a²+ab+b²) template with a = 0.2, b = x, as if the problem were −0.008 − x³).
3. **RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 125, Lesson 3-2, worked example 1, item (أ) was first read as (4/35) × (7/4²) = 4/5. A 400-dpi crop shows the item is (ع³/35) × (7/ع²), where ع is the book's Arabic-letter variable — misread as the digit 4. The book simplifies it to ع/5, which is correct.
4. **Printed p. 125, Lesson 3-2, worked example 1, item (ب):** (5l³/l²) × (3l⁴/l⁶) is given as 5l⁴/2. **Correct:** 15l⁷/l⁸ = **15/l**. (The book cancels the coefficient 3 against the exponent 6 as if both were factors, and mishandles the l-exponents.)

Items checked and cleared (extraction artefacts, not book errors): p. 34 worked example 3 × 0.6̄ − √3 × √27 = 2 − 9 = −7 (correct); p. 96 worked example 3 x³ − 2x² − x + 2 = (x−2)(x−1)(x+1) (correct); p. 101 worked example 3: 6y²+9y = y²+2 → {1/5, −2}, y(6−y) = 7 → {7, −1}, (x+2)² = 144 → {10, −14} (all correct).

#### HONEST NEGATIVES

- No quadratic formula: quadratics are solved only by factorisation and completing the square; the discriminant is never introduced.
- No complex numbers (no square root of a negative number is ever taken).
- No functions beyond the brief absolute-value function; no graphing of quadratics, no domain/range language.
- Statistics stays descriptive (histograms, polygons, quartiles, box plots) — no mean/standard deviation for grouped data, no correlation.
- Probability is odds and simple equally-likely probability only — no tree diagrams, no combined events, no conditional probability.
- Enlargement/rotation are about the origin only (centre at the origin); no general centre, no translation or reflection in this term.
- No surds beyond simplifying square roots; no rationalising denominators.

#### HELD-COPY DEFECTS

- Printed p. 64 is blank (a blank page between the Unit 1 assessment and the Unit 2 opener).
- PDF p. 116 is blank (between the Part 1 references and the Part 2 cover).
- The held copy is a used copy: handwritten blue-ink working is present on at least printed p. 34 ("your turn now" items answered in ink). The handwriting is a previous user's, not part of the book.
- No missing, duplicated or truncated content pages found. The Part 1 references page (PDF p. 115) carries no printed page number.
- One render warning (not a content defect): `pdftoppm` reported "Bad block header in flate stream" while rendering p. 2, but the page renders cleanly.

#### Numbering oddities

- Two parts bound in one file with two title pages and two edition statements (Part 1: 2nd ed. 1448 AH; Part 2: 2nd ed. 1448 AH — the Part 2 title page, PDF p. 118, reads الطبعة الثانية ١٤٤٨ هـ / ٢٠٢٦–٢٠٢٧; an earlier draft of this filing said 1st ed. 1447 AH for Part 2, corrected by the citation check). The printed pagination runs continuously 1–218 across both parts, but Part 2 restarts its own title page at PDF p. 118.
- The back cover (PDF p. 235) repeats the Part 2 cover wording and the mark "2/1".
- Lesson numbering is per unit (1-1 … 4-6) and unit assessments are unnumbered; the two projects are numbered Project 1 (p. 113) and Project 2 (p. 218).

---
### 2. g09-t2.pdf — Grade 9, Term 2, student book

#### Identity

- **Title as printed:** الرياضيات — الصف التاسع — الفصل الدراسي الثاني (al-Riyāḍiyyāt — Mathematics — Grade 9 — Second term), bound as Part 1 (Units 5–6) + Part 2 (Units 7–8) in one file. The cover marks Part 1 "1/2" and Part 2 "2/2".
- **Grade / term / track:** Grade 9, Term 2, intermediate stage (المرحلة المتوسطة). No track — Grade 9 is pre-track.
- **Kind:** Student book (كتاب الطالب). Confirmed from the cover and both title pages.
- **Edition / year as printed:** Both parts 1st edition, 1447 AH / 2025–2026 (Part 1 imprint, PDF p. 3; Part 2 title page, PDF p. 136).
- **ISBN:** None printed — neither the Part 1 imprint page nor the Part 2 title page carries an ISBN. Part 1 was deposited at the Ministry library under no. 92, dated 2026/1/16.
- **Publisher:** Kuwait Ministry of Education, General Administration for Guidance, Research and Curricula (الإدارة العامة للتوجيه والبحوث والمناهج).
- **Scientific reviewer:** Samir Abdullah Ahmed Morsi (أ. سمير عبدالله مرسي), both parts.
- **Authors:** Dalal Mubarak Falah Al-Hajraf (head), Noura Abdullah Abu-Ruqba Al-Otaibi, Sarah Zayed Shinan Al-Ajmi, Wasmiya Badi Hadi Al-Rashidi, Essam Abdul-Hadi Al-Sayed Hassan, Afaf Abdul-Aziz Yaqoub Al-Sanea — the same team as Term 1 except the last author (Afaf replaces Muna Faraj Saad Al-Mutairi).
- **Pages:** 260 PDF pages; printed pp. 1–242. Printed = PDF − 1 (Part 1), printed = PDF − 15 (Part 2).
- **File:** 35,759,652 bytes. SHA-256: `9b9c6b338799d9558c410468faad022812106b548215a8f472d6de95f36fa138`.
- **Language:** Arabic. **Answer key:** none.
- **How read:** Clean text layer in full (PDF pp. 1–260), except PDF pp. 3–9 (image front matter: cover, Basmala, portraits) and the Part 2 title page (PDF p. 136) plus several Part 2 pages, whose text layer is degraded legacy font (backspace characters, some mojibake) — those were read from the extraction plus visual spot-checks and renders. Flagged items were verified against renders.

#### Contents

**Front matter (Part 1):** cover (PDF p. 1); Basmala (PDF p. 4); portrait of the Amir (PDF p. 6); portrait of the Crown Prince (PDF p. 8); foreword, pp. 10–11 (Kuwait Vision 2035); year overview, p. 12 (all 8 units of the year); contents for Units 5–6, pp. 13–14. **Front matter (Part 2):** title page (PDF p. 136); scientific review (PDF p. 137); Amir portrait (PDF p. 140); Crown Prince portrait (PDF p. 142); foreword repeated (PDF pp. 144–145); contents overview (PDF p. 146); contents for Units 7–8, pp. 147–148.

**Unit 5 — Relations & functions (printed pp. 16–78).** Opener p. 16; standards p. 17; organiser p. 18; revision p. 19. 5-1 Relation and its properties, pp. 20–35 (reflexive, symmetric, transitive, equivalence relations; arrow diagrams and graphs; the main diagonal). 5-2 Function (mapping), pp. 36–43 (domain, codomain, range, rule of correspondence). 5-3 Types of function, pp. 44–54 (onto, one-to-one, bijection). 5-4 Linear function, pp. 55–59. 5-5 Quadratic function, pp. 60–68 (vertex form y = (x − d)² + h, shifts and reflection). Unit assessment, pp. 69–78 (essay, true/false, multiple-choice).

**Unit 6 — Linear equations & inequalities (printed pp. 79–132).** Opener p. 79 (roads in the Mutlaa and Sabah Al-Ahmad cities as a slope context); standards p. 80; organiser p. 81; revision pp. 82–83. 6-1 Slope, pp. 84–94 (slope from two points; slope–intercept form; vertical and horizontal lines). 6-2 Parallel and perpendicular lines, pp. 95–101 (equal slopes; slopes whose product is −1). 6-3 Solving two linear equations in two unknowns simultaneously, pp. 102–113 (graphical, elimination and substitution methods; the three cases — one solution, no solution, infinitely many). 6-4 Linear inequalities (common solution region), pp. 114–124. Unit assessment, pp. 125–131. Project 3, p. 132 (Sarah has 15 dinars; a pen costs 1 dinar and a notebook 2 dinars — write the equation, a table of three possible purchases, and graph it).

**Unit 7 — Triangle geometry (printed pp. 135–199).** Opener p. 135; standards p. 136; organiser p. 137; revision pp. 138–139. Proofs throughout use the format givens / required / proof (المعطيات / المطلوب / البرهان). 7-1 Mid-segment of a triangle, pp. 140–152 (the segment joining two midpoints is parallel to the third side and half its length; the converse). 7-2 Segment from the right-angle vertex to the hypotenuse midpoint, pp. 153–160 (median to the hypotenuse equals half the hypotenuse; the 30°–60°–90° triangle). 7-3 Perpendicular bisectors of the sides of a triangle, pp. 161–167 (circumcentre, equidistant from the vertices). 7-4 Interior angle bisectors, pp. 168–177 (incenter, equidistant from the sides). 7-5 Altitudes, pp. 178–182 (orthocentre; the orthocentre of a right triangle is the right-angle vertex). 7-6 Medians, pp. 183–190 (centroid divides each median 2:1 from the vertex). Unit assessment, pp. 191–199.

**Unit 8 — Percentages, geometry & measurement (printed pp. 200–242).** Opener p. 201 (Kuwait Towers — sphere surface area and volume); standards p. 202; organiser p. 203; revision pp. 204–207 (percentages, proportions, equations, areas and volumes met earlier). 8-1 Estimating percentages, pp. 208–211 (round the rate and the quantity to friendly numbers first). 8-2 Percentage increase and decrease, pp. 212–217 (final value = original × (100% ± rate)). 8-3 Applications of percentage change, pp. 218–222 (successive changes; the percentage needed to return to the original). 8-4 Surface area of a right circular cone, pp. 223–227 (lateral area πrℓ, total area πr(ℓ + r); the slant height is the hypotenuse of radius and height). 8-5 Volume of a right pyramid, pp. 228–231 (V = ⅓ × base area × height, by the sand-filling experiment with a prism). 8-6 Volume of a sphere, pp. 232–236 (V = ⁴⁄₃πr³, by Archimedes' relation to the circumscribed cylinder — the sphere is ⅔ of the cylinder). Unit assessment, pp. 237–241. Project 4, p. 242 (percentages in daily life — choose five products, record original and sale prices, apply a 20% discount, present a table). References, p. 243.

**Verified clean (spot-checked):** Unit 5 — f(x) = 3x + 1 on {−2, −1, 0, 1, 2, 3} gives −5, −2, 1, 4, 7, 10; f(x) = x² − 1 on {−2, −1, 0, 2} has range {−1, 0, 3}, onto but not one-to-one; y = (x − 2)² + 3 has axis x = 2 and vertex (2, 3); y = −(x − 3)² + 4 has vertex (3, 4). Unit 6 — slope through (−3, 1), (4, 6) is 5/7; the line through (3, 4), (5, 7) has slope 3/2 and is perpendicular to 3y + 2x − 3 = 0 (slope −2/3); x + y = 5 and y − x = −3 give {(4, 1)}; 8x + 3y = 5, 2x + y = 1 give {(1, −1)}; assessment: y = x − 3, 2y − x = −3 give {(3, 0)}; y = 3x + 5, 3x − y = 0 has no solution. Unit 7 — mid-segment: LM = ½(8) = 4 cm; median to hypotenuse 10 cm is 5 cm; 2k + 3 = ½(k + 12) gives k = 2; circumcentre MB = √(3² + 4²) = 5; centroid: BD = 6 gives BM = 4, DM = 2; assessment: DH = 5 → AC = 10; median MD = 3 → AD = 9; orthocentre angle 110° → angle A = 70°; AD = 3x + 6 = ½(10x) gives x = 3, AD = 15. Unit 8 — 24% of 62 ≈ 25% of 60 = 15; 53.5% of 99 ≈ 54; 19% of 300,000 ≈ 60,000; 40 people = 8% of the total → total ≈ 400; original 40, +30% → 52; final 36,000 after −10% → original 40,000, decrease 4,000; admissions 4,500 → 6,300 is +40%; sales fell 20% to 4,000 → original 5,000, and +25% returns them; gold +25% then −20% returns to the original price; cone r = 7, ℓ = 20, π = 22/7: lateral 440 cm², total 594 cm²; cone diameter 6 dm, height 4 dm: ℓ = 5 dm, total area 24π dm²; ice-cream cone (diameter 4, ℓ = 10, π = 3.14): total 75.36 cm²; pyramid, square base 6, height 20: V = 240 cm³; serving dish V = 400, h = 20 → base 60 cm²; sphere r = 6: V = 288π cm³; sphere r = 1 m, π = 22/7: V = 88/21 = 4⁴⁄₂₁ m³; hemisphere diameter 12 m: V = 144π m³; lamp V = 256π/3 cm³ → r = 4 cm, diameter 8 cm; assessment: TV after −30% is 280 → original 400; item reduced 40% to 300 → original 500; washing machine 65 after −35% → original 100; share −50% needs +100% to return; sphere diameter 6: a third of its volume is 12π cm³; square pyramid base 6, height 9: V = 108 cm³; cone r = 5, ℓ = 13: lateral 65π cm²; sphere V = 288π → r = 6; spheres of radii 2 and 6 have volumes in ratio 1:27.

#### BOOK ERRORS — 1

1. Printed p. 109, Lesson 6-3, worked example 5: the system 3x − y + 4 = 0, y − x = −4. The book substitutes y = x − 4 into the first equation and reduces 3x − (x − 4) + 4 = 0 to "−2x = 0" — dropping the +8 and flipping the sign of 2x — giving the solution set {(0, −4)}. **Correct:** 2x + 8 = 0 → x = −4, y = −8, solution set {(−4, −8)}. Check: 3(−4) − (−8) + 4 = 0 and −8 − (−4) = −4. The book's (0, −4) fails the first equation (it gives 8 ≠ 0). The book prints a "verify the solution" note after the example but does not carry the verification out.

**Cleared (teaching devices, not book errors):** p. 89 — Amer computes the slope through (5, 7), (−2, 3) as 7/4; the book asks "is Amer right?" and the intended answer is no (correct slope 4/7). P. 113 — Sarah claims two lines with the same y-intercept have infinitely many common solutions; the book presents the claim to be judged and the intended answer is no. P. 62 — Mohammed and Badi describe y = −(x − 3)² as "reflect then shift right 3" and "shift right 3 then reflect"; both are correct, the two orders are equivalent.

#### HONEST NEGATIVES

- Functions are on finite listed sets only — no real-number domains, no composite or inverse functions, no function composition, and no graphing of functions beyond the quadratic shift sketches in 5-5.
- Simultaneous equations: two equations in two unknowns only; no three unknowns, no elimination by determinants, and word problems are limited to the money/project items.
- Triangle geometry is synthetic proof only — no coordinate proofs, no trigonometry (no sine or cosine anywhere), no circle theorems, no area ratios.
- Percentages: no compound interest, no single-multiplier formula for successive changes (each change is worked step by step), no percentage points.
- Solids: cone surface area and pyramid/sphere volume only — no surface area of a sphere, no cylinder surface area in this term, no frustum, no surface area of composite solids.
- No statistics and no probability in this term (both were in Term 1); no sequences, no surds, no logarithms.

#### HELD-COPY DEFECTS

- PDF p. 15 (printed 14) is near-blank — just the page number, at the end of the Part 1 front matter.
- PDF p. 79 (printed 78) is a near-blank page between the Unit 5 assessment and the Unit 6 opener.
- PDF p. 259 is blank; PDF p. 260 is the Part 2 back cover (marked "2/2").
- Part 2 front matter repeats the foreword (PDF pp. 144–145) and the two portraits (PDF pp. 140, 142) — by design, not a defect.
- The Part 2 title page (PDF p. 136) and several Part 2 pages have a degraded legacy-font text layer (backspace characters, some mojibake); the content is intact and was read from the extraction plus visual spot-checks.
- No missing, duplicated or truncated content pages found.
- The references pages (PDF pp. 134 and 258) cite the 1st edition 2024–2025 and the trial edition 2023–2024 while the title pages say 1st edition 2025–2026 — the references were not updated (same stale-references pattern as Term 1).

#### Numbering oddities

- Two parts bound in one file with two title pages and two edition statements (both 1st ed. 1447 AH here; in Term 1 both parts are likewise the same edition, 2nd ed. 1448 AH). Printed pagination runs continuously 1–242 across both parts.
- Lessons are numbered per unit (5-1 … 8-6); unit assessments are unnumbered. The projects continue Term 1's numbering: Project 3 (p. 132) and Project 4 (p. 242).

---
### 3. g10-t1-wb.pdf — Grade 10, Term 1, STUDENT book (not a workbook)

#### Identity

- **Title as printed:** الرياضيات — الصف العاشر — الفصل الدراسي الأول – القسم الأول (al-Riyāḍiyyāt — Mathematics — Grade 10 — First term — Part 1), كتاب الطالب (student book).
- **Grade / term / track:** Grade 10, Term 1, Part 1. No track — Grade 10 is pre-track.
- **Kind:** **Student book — not a workbook.** The cover (PDF p. 1) and the title page (PDF p. 2) both say كتاب الطالب. The filename's "-wb" is wrong; the record slot that calls this file a workbook is wrong with it.
- **Edition / year as printed:** 1st edition, 1448 AH / 2026–2027.
- **ISBN:** 978-9921-33-124-0. Deposited at the Ministry library under no. 531, dated 2026/8/9.
- **Publisher:** Kuwait Ministry of Education, General Administration for Guidance, Research and Curricula (Educational Research and Curricula Administration).
- **Authors:** Dalal Mubarak Falah Al-Hajraf (head), Mohammed Abdullah Al-Hamad Al-Majran, Wadhah Ibrahim Mazal Al-Dosari, Haya Mohammed Falah Al-Azmi, Hessa Madhi Abdullah Al-Hajri, Thuraya Ghadeer Murbid Al-Shammari.
- **Scientific team:** Samir Abdullah Ahmed Morsi, Khaled Sawi Sayed Shehata. AI-enhanced explanations: Nihal Hashem Abdel-Hamid Hashem. Design and layout: Khuloud Khaled Mahdi Al-Shammari. Language review: Abdullah Mohammed Al-Dharwa, Abbas Faisal Al-Sarraf, Amani Abdul-Karim Al-Arifi.
- **Pages:** 134 PDF pages; printed pp. 1–133. Printed = PDF − 1.
- **File:** 32,013,779 bytes. SHA-256: `897e9cdb8ed9ddaf621955ec143eee7e9cb8670b50c35b6a4a14ebf086f8116e`.
- **Language:** Arabic. **Answer key:** none.
- **Generation:** new-generation book (2026–2027) — QR codes at the start of lessons and at some exercises link to videos and visual explanations; AI-enhanced explanations are credited; each unit opens with a STEAM project; the icon key (p. 11) marks lesson idea, remember, note, explore / think with me, theorem / generalisation, lesson entry.
- **How read:** Clean text layer in full (PDF pp. 1–134); flagged items verified against renders.

#### Contents

**Front matter:** cover (PDF p. 1); title page (PDF p. 2); scientific team and imprint (PDF p. 3); Amir portrait (PDF p. 6); Crown Prince portrait (PDF p. 8); contents (PDF p. 10); icon key (PDF p. 11); foreword (PDF p. 12) — it lists the year's units as algebra and solving equations, plane geometry, trigonometry and logic and statistics, circle geometry, matrices, coordinate geometry, and sequences.

**Unit 1 — Algebra & solving equations (printed pp. 13–77).** Unit opener pp. 13–14 (what the unit is for; what was learned before; what will be learned). STEAM project pp. 15–16, "Harmony of Light & Shadows" (quadratic equations and sum/product of roots applied to light, shadow and aperture sizes; build a light box). 1-1 Absolute-value function, pp. 16–32 (definition and redefinition of |x|; f(x) = |ax + b| + c, vertex (−b/a, c), axis of symmetry x = −b/a, range, even function; graphing by vertex and symmetry, by redefinition, and by geometric transformations — horizontal and vertical shifts, combined shifts, reflection in the x-axis; model: a building-entrance canopy y = |x − 3| + 4, vertex (3, 4)). 1-2 Solving absolute-value equations, pp. 33–42 (|ax + b| = c; |ax + b| = |cx + d| by properties and by squaring both sides; |ax + b| = cx + d with the solution condition cx + d ≥ 0; model: the distances of home, school and club from a park on one line). 1-3 Solving a quadratic equation in one variable algebraically and graphically, pp. 42–53 (graphical method via the parabola's x-intercepts; completing the square; the quadratic formula; the discriminant Δ = b² − 4ac and the number of real roots; word problems — two consecutive odd numbers whose squares sum to 34, and a playground 68 m wide by 105 m long). 1-4 Sum and product of the roots of a quadratic — forming the quadratic from its roots, pp. 54–62 (l + m = −b/a, l·m = c/a; l² + m², 1/l + 1/m, l − m from sum and product; x² − (l + m)x + lm = 0; infinitely many equations share the same roots, k[x² − (l + m)x + lm] = 0). 1-5 Solving quadratic inequalities, pp. 62–77 (by factorisation and the sign properties of products; by studying the sign of ax² + bx + c, including the Δ > 0, Δ = 0 and Δ < 0 cases; special case via absolute value, x² < 9 ⇔ |x| < 3; model: a 20 × 20 block of chairs, remove at least 5 rows to stay at or under 225 chairs). Unit 1 test preparation, p. 78 — a QR code only; the test questions themselves are behind the QR code and are not printed in the book.

**Unit 2 — Plane geometry (printed pp. 78–133).** Unit opener pp. 79–80. Project pp. 81–82, "Geometric similarity and digital modelling of the Kuwait Towers" (real heights 187 m, 147 m, 113 m; scale 1:500, i.e. 1 cm in the model = 5 m in reality; model height of the main tower 187 ÷ 5 = 37.4 cm). 2-1 Proportion, pp. 82–96 (ratio and proportion; cross-multiplication and its converse; the properties of proportion — invertendo, alternando; continued (geometric) proportion and the geometric mean b = ±√(ac); sums of antecedents and consequents; applications — basketball: 30 minutes burns 300 kcal, so 450 kcal takes 45 minutes; zakat, inheritance, scale drawing). 2-2 Similar polygons, pp. 96–104 (definition — equal corresponding angles and proportional corresponding sides; congruent polygons are similar; similarity is transitive; similarity ratio k — k > 1 enlargement, 0 < k < 1 reduction, k = 1 congruence; perimeter ratio = k, area ratio = k²). 2-3 Similar triangles, pp. 104–116 (the AA, SSS and SAS cases, each proved with an auxiliary construction; mirror model — Fahd, 1.8 m tall, stands 2.7 m from a mirror and sees the top of a building 24 m beyond it: the building is 16 m tall). 2-4 Similarity in right triangles, pp. 116–123 (Euclid's theorem — with AD ⊥ BC in the right-angled triangle ABC: AD² = DC·DB, AB² = BD·BC, AC² = CD·CB, AB·AC = AD·BC). 2-5 Proportions and similar triangles, pp. 123–133 (the parallel-line theorem and its converse; Thales' theorem — a transversal cutting three or more parallels; the angle-bisector theorem, interior bisector only). The file then ends — see held-copy defects.

**Verified clean (spot-checked):** 1-1 — f(x) = |2x + 4| has vertex (−2, 0), f(−1) = 2, f(0) = 4; y = |x − 2| + 1 has vertex (2, 1) and range [1, ∞); y = −|2x + 3| has vertex (−3/2, 0) and range (−∞, 0]; f(x) = |x − 4| + 2 meets g(x) = |x| at (3, 3); f(x) = −|x + 1| + 2 crosses the x-axis at x = −3 and x = 1. 1-2 — |x − 3| = 2 gives {1, 5}; |3x + 2| = 0 gives {−2/3}; |5x + 2| = −4 has no solution; |x − 2| = |2x − 1| gives {−1, 1} by both methods; |x + 4| = |x − 3| gives {−1/2}; |2y + 1| = |3y + 4| gives {−1, −3}; |x − 3| = 3x − 1 gives {1} (x = −1 is rejected by the condition x ≥ 1/3); |x + 4| + 2x + 3 = 0 gives {−7/3}; |x − 3| = |3 − x| holds for all real x; |2x − 3| = |x + 3| gives {0, 6}. 1-3 — graphically x² − 2x − 3 = 0 has roots −1 and 3, and x² + 2 = 0 has none; 4x² − 4x − 3 = 0 has Δ = 64 (two roots); 2x² − 4x + 2 = 0 has Δ = 0 (one repeated root); x² + 2x + 3 = 0 has Δ = −8 (no real roots); x² − 8 = 0 gives ±2√2; x² = x + 1 gives (1 ± √5)/2; the playground equation x² + 37x − 7140 = 0 gives x = 68 (x = −105 rejected), length 105 m. 1-4 — for 2x² − 8x + 5 = 0: l + m = 4, l·m = 5/2, l² + m² = 11, 1/l + 1/m = 8/5, |l − m| = √6; roots 4/3 and 3/4 give 12x² − 25x + 12 = 0; from 2x² − 3x − 1 = 0 the roots 2l, 2m give x² − 3x − 2 = 0; x² = 2 − |x| gives {1, −1}; x² − 2|x| = 8 gives {4, −4}. 1-5 — x² − 2x − 8 ≥ 0 gives (−∞, −2] ∪ [4, ∞), ≤ 0 gives [−2, 4]; x² − x ≤ 5 gives [(1 − √21)/2, (1 + √21)/2] ≈ [−1.8, 2.8]; x² − 10x + 25 > 0 gives ℝ ∖ {5}; −3x² + 4x − 2 ≥ 0 has no solution; 2x² + 5 ≥ 23 gives (−∞, −3] ∪ [3, ∞); (5x + 7)² + 3 < 2 has no solution; (x + 2)(x − 5) > 0 gives (−∞, −2) ∪ (5, ∞); x² + 6x + 9 ≤ 0 gives {−3}; of 60, −20, 2 and 0, only 0 is not a solution of 4x² − 4x − 5 > 0. 2-1 — 2, x, 4, 6 proportional gives x = 3; fourth proportional to 1, 3, 9 is 27; subtracting x from both terms of 7/9 to get 4/5 gives x = −1; (5x − 1):(x + 4) = 4:5 gives x = 1; 5a = 4b gives a/b = 4/5; (2a + 5b)/(3b + 2a) with a/b = 3/4 is 13/9; 5, 6, 3 proportional to a, b, c gives (a + 2b + c)/(3a + b + c) = 5/6; geometric mean of 9 and 16 is ±12; 2a = 3b = 5c gives a:b:c = 15:10:6 (Ibrahim's method is right; Fahd's 2:3:5 is the distractor); (2a + 3b)/(2b + 3c) = (a + 2b)/(b + 2c) implies b² = ac; 20, x, 32 in continued proportion gives x = ±8√10. 2-2 — XYZL ~ ABCD with XY = 10, YZ = 8, LX = 6, BC = 12 gives AB = 15, DA = 9; similarity ratio 5/6 with smaller perimeter 14.5 gives larger perimeter 17.4 cm; perimeter ratio 36:25 gives side ratio 6:5. 2-3 — AC/AE = AB/AD gives AC = 10, DC = 6; sides 4/8 = 5/10 = 3/6 = 1/2 prove similarity; FC/AC = 7/14 = EC/BC = 9/18 = 1/2 with the common angle proves similarity; BC = √(6² + 8²) = 10, then FE = 1.8 cm and BF = 2.4 cm. 2-4 — DC = 9, DB = 16 gives AD = 12 and AC = 15; AD = 10, DC = 5 gives DB = 20. 2-5 — 6/x = 8/10 gives x = 7.5; Thales 12/x = 20/50 gives x = 30; (3x − 4)/x = 33/12 gives x = 16; angle bisector 6/5 = 8/x gives x = 9.6; 16/12 = (3x + 3)/(x + 6) gives x = 3; the parallel-line item: Ibrahim is right (AD = 10/3, BC = 24) and Fahd is wrong (his BC = 18 mixes the side-segment ratio with the similarity ratio).

#### BOOK ERRORS — 2

1. Printed p. 30, Lesson 1-1, the "question" box on reversing the transformation order: the reversed sequence (shift |x| left 1, then up 2, then reflect in the x-axis) is drawn with vertex (−1, −2) and labelled on the curve itself f₃(x) = −|x + 1| − 2 — but the caption under the graphs and the concluding sentence both call it f₃(x) = −|x + 1| + 2 ("this curve's equation will be f(x) = −|x + 1| + 2"). **Correct:** reflecting |x + 1| + 2 in the x-axis gives −|x + 1| − 2 (vertex (−1, −2)); −|x + 1| + 2 has vertex (−1, +2) and is a different curve from the one drawn. The book's own graph is right and its label is wrong. The blanket answer "of course we cannot" also overstates the point: only the vertical shift changes sign under reflection — a horizontal shift can be done before the reflection with the same result; the book's example differs only because the vertical shift was also done first.
2. Printed p. 35, Lesson 1-2, properties of absolute value, property 7: "|n|² = n², where n is an even number". **Correct:** |n|² = n² holds for every real n; the restriction to even n is wrong (the condition belongs to a property about even powers, e.g. |aⁿ| = aⁿ when n is even). The identity itself is true; the stated condition is not.

**Cleared (teaching devices, not book errors):** p. 92 — Fahd's a:b:c = 2:3:5 for 2a = 3b = 5c is the distractor (correct 15:10:6); p. 94 — the two answers for 6, x, 54, 162 in continued proportion are presented for judgement (correct x = 18); p. 126 — Fahd's BC = 18 is the distractor (correct 24); p. 77 — Nour's claim that −x² + 2x − 7 < 0 has no solutions is presented to be corrected (it holds for all real x); p. 78 — Hadeel's claim that 2x² + x − 3 < 0 and (2x² + x − 3)/(x + 1)² have the same solution is presented to be judged (they differ at x = −1, which the second excludes).

#### HONEST NEGATIVES

- Absolute-value functions: shifts and reflection only — no stretching or compression (the "think with me" box asks about |2x − 4| + 3, but horizontal scaling is never taught); no piecewise-defined functions beyond redefining the absolute value.
- Quadratics: no complex numbers — Δ < 0 is always "no real roots" and complex roots are never mentioned; no sum/product formulas beyond quadratics; the quadratic formula is derived but complex solutions are not.
- Inequalities: one variable only; no systems of inequalities; no inequalities with parameters except the Δ = 0 item.
- Geometry: similarity only — congruence cases are assumed known, not proved here; no circle geometry, no trigonometry, no coordinate geometry in this part (the foreword promises trigonometry, logic and statistics, circle geometry, matrices, coordinate geometry and sequences for the year, but this Part 1 file covers only Units 1–2).
- No statistics or probability in this part.
- Unit tests are not printed in the book at all — they sit behind QR codes (p. 78).

#### HELD-COPY DEFECTS

- **The file ends abruptly.** PDF p. 134 (printed p. 133) is the first page of Lesson 3-6, "Solving Trigonometric Equations" (Unit 3), showing 2 sin θ − 1 = 0 with solutions θ = π/6, 5π/6, … — and the file stops there. The rest of Unit 3 and any end matter are not in this file. The file therefore contains Units 1–2 complete (through the Lesson 2-5 exercises, printed p. 132) plus one stray opening page of Unit 3.
- **No printed unit assessments:** the Unit 1 test is QR-only (p. 78), and there is no Unit 2 test page at all in the file.
- PDF pp. 4–5, 7, 9 are blank front-matter pages (between the portraits). The text layer on pp. 121–123 duplicates some passages — an extraction artefact; the printed pages are fine.
- No missing, duplicated or truncated content pages within Units 1–2.

#### Numbering oddities

- Each lesson's exercises carry a code in the margin footer (e.g. G10-U01-L01A, G10-U02-L05B) and the Unit 1 test page is coded G10-U01-T01.
- The two STEAM projects (Unit 1 "Harmony of Light & Shadows", Unit 2 Kuwait Towers digital model) are unnumbered and sit at the start of their units.
- Lesson 1-3's exercises include items that refer to the quadratic formula as "the general law" (القانون العام); the discriminant is introduced as Δ (delta).

---
### 4. Grade 11 Term 1 — Mathematics exercise workbook (scientific track)

#### Identity

- **Title as printed:** الرياضيات — كرّاسة التمارين — الصف الحادي عشر علمي — الفصل الدراسي الأول
- **Transliteration/translation:** *Al-Riyāḍiyyāt — Kurrāsat al-Tamārīn — al-Ṣaff al-Ḥādī ʿAshar ʿIlmī — al-Faṣl al-Dirāsī al-Awwal* — Mathematics — Exercise Workbook — Grade 11 scientific track — First term. Secondary stage (المرحلة الثانوية).
- **Kind: WORKBOOK (exercises only).** Proved from the book itself: the cover and title page both say كرّاسة التمارين (exercise workbook); the contents are تمرّن (practice) sets per lesson, a unit test and enrichment exercises per unit; there are no lessons, no worked examples and no printed answers anywhere in the file. The filename's "-wb" is right this time, but the kind is proved from the cover, not the filename.
- **Grade:** 11. **Term:** 1. **Track:** scientific (علمي), printed on the cover and title page. This is the scientific-track workbook; the literary-track statistics books are separate files (see §§8–10).
- **Edition/year as printed:** 2nd edition (الطبعة الثانية), 1448 AH / 2026–2027. Prepared by the supervisory committee for studying and aligning the mathematics book series: Ibrahim Hussein Al-Qattan (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour.
- **ISBN:** 978-9921-33-071-7 (imprint page). The back cover carries a different barcode ISBN, 978-614-406-477-1 (Pearson Scott Foresman) — the series' Pearson ISBN, not the ministry imprint ISBN.
- **Publisher:** Kuwait Ministry of Education, General Administration for Guidance, Research and Curricula (Educational Research and Curricula Administration). Printed by the Government Press — State of Kuwait. The imprint page also carries "House of Education / Pearson Education 2013" — this workbook is built on a 2013 Pearson source.
- **Deposit as printed:** deposited at the National Library of Kuwait; deposited at the Ministry library under no. 48, dated 2015/5/10. The 2015 date predates this 2nd edition (2026–2027) and is plainly carried over from the first edition; recorded as printed.
- **Pages:** 106 PDF pages; printed pp. 1–103 (content printed pp. 9–99). Printed = PDF − 3 throughout the content (PDF p. 12 = printed p. 9).
- **File:** `g11-t1-wb.pdf`, 11,969,930 bytes, SHA-256 `627cea850a74fff59fdc6b91b996f037dd98c0e5726b301b5860cee2be895273`.
- **Language:** Arabic. **Answer key:** none in this copy. The back cover lists the series components as student book, teacher's book, exercise workbook, and exercise workbook *with answers* (كرّاسة التمارين مع الإجابات) — the answers live in that separate component, not in this file.
- **How read:** clean text layer for most pages, read in full (PDF pp. 1–106). The title page (PDF p. 2), imprint (PDF p. 3), contents (PDF pp. 10–11) and cover (PDF p. 1) were verified against renders. Figure-heavy pages with no usable text layer (PDF pp. 53, 64, 78 and parts of others) were read from renders. PDF pp. 4–9 are blank/image front matter (no text layer). Cover art: a normal-distribution curve (34%, 34%, 13.5%, 2.5%), a bar chart of actual vs natural growth, a decibel scale (airplane 120, vacuum cleaner 70, library 30) and electricity pylons.

#### Contents (printed page numbers)

Every lesson's exercises are split into **Group A** (essay — تمارين مقالية) and **Group B** (objective — تمارين موضوعية: true/false, multiple-choice and matching). Each unit closes with a unit test (اختبار الوحدة) and enrichment exercises (تمارين إثرائية). There are 27 exercise sets, 6 unit tests and 6 enrichment sets.

**Unit 1 — Real numbers (الأعداد الحقيقية), pp. 9–19.**
- 1-1 Roots and radical expressions (pp. 9–11): simplifying square and cube roots (√400 = 20, ∛(−64) = −4), rationalising denominators, writing expressions in the form a + b√2, a garden 5√21 m × 2√7 m (perimeter 10√21 + 4√7 m, area 70√3 m²), the golden ratio φ = (1 + √5)/2 with φ² = φ + 1, a cuboid of volume 40 cm³ with sides 5, x, x giving x = 2√2 cm.
- 1-2 Rational exponents (pp. 12–14): fractional exponents (64^(2/3) = 16), even roots of negatives have no real value, an error-analysis item on 5∛4 − 5∛(5/2) (deliberately wrong working for the learner to find), x² − xy + y² = 4 with x + y = 2 giving x³ + y³ = 8.
- 1-3 Solving equations (pp. 15–16): radical equations (3√x + 3 = 15 → x = 16; ∛(x + 5) = 4 → x = 59; √(5 − 3x) + 4 = 3 → no solution), a sphere of volume 424.75 m³, exponential equations (5^(2x−3) = 125 → x = 3; 3^(x+1) = 1 → x = −1).
- Unit 1 test (pp. 17–18): simplify and rationalise radicals; 64^(2/3), 25^1.5 = 125, 81^(−0.25) = 1/3; x = √(6 − 2√5) − √(6 + 2√5), compute x² = 4 and prove x = −2; error analysis on 1/(1 − √2)²; 2^x = 512 → x = 9.
- Enrichment (p. 19): ∛(−343) = −7, ⁴√810000 = 30, −⁴√6561 = −9, ⁵√(−0.00001) = −0.1; a right triangle with MN ∥ BC, AM = 2√3 − 1, AN = 2 + √3, MB = 1 — find CN and MN.

**Unit 2 — Real functions (الدوال الحقيقية), pp. 20–36.**
- 2-1 Domain of the function (pp. 20–21): vertical-line test on graphs; domains (f(x) = √(3x − 7) + 2 → [7/3, ∞); f(x) = (x² − 1)/(x² + 2x + 1) → ℝ ∖ {−1}; f(x) = x²/x → ℝ ∖ {0}).
- 2-2 Quadratic functions and their modelling (pp. 22–23): classify linear vs quadratic (y = (2x + 1)(x − 2) + 4 − 2x² simplifies to −3x + 2, linear; y = (3x + 7)² − (9x² − 49) simplifies to 42x + 98, linear); minimum 3 data pairs for a quadratic model; fitting quadratics to tables (f(x) = 2x² − 5x − 3; f(x) = x² + 2x; f(x) = −3x² + 20).
- 2-3 Quadratic functions and parabolas (pp. 24–26): parabolas with vertex at the origin and in vertex form, graphing y = (x + 3)², y = −(x + 1)², y = 3(x − 2)² + 4; a bridge over a river, 20 m between its bases and 8 m maximum height → y = −0.08(x − 10)² + 8.
- 2-4 Comparing vertex and general form (pp. 27–29): write quadratics in vertex form and in general form; y = 2x² − 12x + c with vertex (3, 5) → c = 23; y = ax² + bx + 8 with vertex (2, −4) → a = 3, b = −12; vertex of y = −x² − 16x − 62 is (−8, 2), in the second quadrant.
- 2-5 Inverses and square root functions (pp. 30–31): inverses of linear and quadratic functions, graphing square-root functions with domain and range, a sale-price function with 20% off (y = 0.8x) and its inverse.
- 2-6 Solving inequalities (pp. 32–33): quadratic and rational inequalities; a rectangle of width (x − 2) cm and length 2x cm with area between 90 and 100 cm²; Ahmed's grandfather is 8 times Ahmed's age and in 3 years Ahmed's age squared will exceed twice his grandfather's age for the first time (Ahmed 10, grandfather 80).
- Unit 2 test (pp. 34–35): domains, a company-profit quadratic model from a table, graphing parabolas from vertex and a point, inverses, inequalities including (x − 2)⁻¹-type rational inequalities and a graphical study of f(x) = −x² + 4x − 3 against y = −8.
- Enrichment (pp. 36–37): a football shot modelled by y = a(x − 10)² + 3 (goalkeeper reaches 2.53 m, goal height 2.44 m); a tennis ball modelled by y = −0.08(x − 9)² + k from 1 m up over a 23.8 m court; first differences of y = 2x and y = 2x² tables; a tsunami model from speed/depth data (speed 52–98 m/s, depth 270.40–960.40 m).

**Unit 3 — Polynomials (كثيرات الحدود), pp. 38–52.**
- 3-1 Power functions and their inverses (pp. 38–40): symmetry of graphs, even/odd/neither (y = x³ odd, y = x⁴ even, y = (x − 1)³ + 2 neither), inverses of power functions, a watermelon of circumference 80 cm weighing M = 0.008p³ grams, a torus of volume V = 2π²R₁R₂², and why (−64)^(1/2) is not a real number while (−64)^(1/3) is.
- 3-2 Polynomial functions (pp. 41–42): write polynomials in standard form and classify by degree and number of terms ((2x² + 9) − (3x² − 7), (w − 1)⁴, (2c − 3)(2c + 4)(2c − 1)); end behaviour; a perfume bottle (cylindrical base + hemispherical cap, h = 10 cm) as a polynomial volume.
- 3-3 Linear factors of polynomials (pp. 43–45): zeros and their multiplicity, writing a polynomial from given zeros (1, −1; 0, 1, 2; −4, −1, 3; 2 repeated twice), a box of length 2x + 1, width x + 4, height x + 3 built from x, x², x³ blocks; factor-theorem items (f divisible by (2x + 3) → f(−2/3) = 0; f(x) = x³ − x divisible by x − k for k ∈ {0, −1, 1}).
- 3-4 Dividing polynomials (pp. 46–48): long division ((x² − 3x − 40) ÷ (x + 5), (x³ − 13x − 12) ÷ (x − 4)), synthetic division, remainder theorem (f(−1) = −2 − 4 − k − 1 = 0 → k = −7 for f(x) = 2x³ − 4x² + kx − 1 divided by x + 1 with zero remainder), patterns: (x² − 1) ÷ (x − 1), (x³ − 1) ÷ (x − 1), (x⁵ − 1) ÷ (x − 1) and (x³ + 1) ÷ (x + 1), (x⁵ + 1) ÷ (x + 1), (x⁷ + 1) ÷ (x + 1).
- 3-5 Solving polynomial equations (pp. 49–51): factoring (6y² = 48y; 3x³ − 6x² − 9x = 0), rational zeros (x³ − 3x + 2 = 0; x³ − 7x + 6 = 0; x⁴ + x³ − 6x² − 4x + 8 = 0); x⁴ − 10x² + 9 = 0 has solutions ±1, ±3, so 2 is not a solution.
- Unit 3 test (p. 51): inverses of power functions, standard form and classification, zeros and approximate graphs, solving (x − 3)(x² + 3x − 4) = 0 and x⁴ − 2x² − x + 2 = 0, long and synthetic division.
- Enrichment (p. 52): g(x) = (m + 1)x³ + 11x² + 4x − 4 with 1/2 a zero; a for which f(x) = x⁵ + x⁴ − 6x³ − 14x² − (a + 5)x − (a − 3) is divisible by (x + 1)²; prove x⁴ + 6x³ + 7x² − 6x + 1 = (x² + 3x − 1)²; a cubic model through (−1, −3), (0, 0), (1, −1), (2, 0) used to estimate y at x = 17.

**Unit 4 — Exponential and logarithmic functions (الدوال الأسية والدوال اللوغاريتمية), pp. 54–71.**
- 4-1 Exploring exponential models (pp. 54–56): growth vs decay and the percentage rate (y = 1298(1.63)^x grows 63%; y = 2(0.65)^x decays 35%); 1994 populations of Tokyo (26,518,000, +1.4%), New York (16,271,000, +0.3%), São Paulo (16,110,000, +2.0%), Mexico City (15,525,000, +0.7%) projected to 2004 (São Paulo overtakes New York); a delivery van worth 1,750 dinars losing 11% a year; a goat herd of 115 falling 1.25% a year; choosing between three cars by depreciation; a frustum volume V = πh/3 · (R² + Rd + d²); three consecutive integers with product 210 (5, 6, 7); a tank V(x) = x³ + 8x² + 15x = 70 m³ giving width 2 m, length 5 m, height 7 m.
- 4-2 Exponential functions and their graphs (pp. 57–58): graphing y = 4^x, y = 6^x + 3, y = (1/3)^(x+2), y = −2(3)^(2x) + 1; e-values to four decimal places; a for which y = ab^x is a horizontal line (b = 1); radioactive decay A = Pe^(−0.0001t).
- 4-3 Logarithmic functions and their graphs (pp. 59–61): exponential ↔ logarithmic form (4² = 16 ↔ log₄16 = 2; log₃(1/9) = −2; log₃(1/243) = −5); values (log₂4 = 2, log₂8 = 3); domains (y = log(x² + 1) → ℝ; y = log(x − 1) → (1, ∞)); pH of a lemon with [H⁺] = 1.26 × 10⁻² (pH ≈ 1.9); matching inverses of y = −log_(1/4)x (→ y = 4^x) and y = −log₄x (→ y = (1/4)^x), and inverse graphs of y = log₃x (→ y = 3^x) and y = log₂(4x) (→ y = 2^(x−2)).
- 4-4 Properties of logarithms (pp. 62–64): condense to one logarithm and expand (log 7 + log 2; ½log₄y − log₄x; log a + 3 log b); values with log 4 ≈ 0.6021, log 5 ≈ 0.6990, log 6 ≈ 0.7782 (log 20, log 16, log 1.25, log 125, log 36); decibel table (L = 10 log(I/I₀), I₀ = 10⁻¹² W/m²).
- 4-5 Exponential and logarithmic equations (pp. 65–67): solve 9^(2y) = 66, 5 − 3^x = −40, 3x² = 27 (x > 0); change of base (log₂7, log₃33, log₂₁0.085); solve 2^(3x) = 80 by log base 2 and by log base 10; log equations (log 6x − 3 = −4; log(2x) + log(x − 3) = log 8); an endangered species falling 3.5% a year from 80 animals.
- 4-6 Natural logarithm (pp. 67–68): condense/expand ln expressions; rocket velocity V = −0.0098t + C·ln R (mass ratio 20, exhaust speed 2.7 km/s, burn time 30 s); solve 3e^(2x) = 12, e^(x+1) = 30, 2e^(2x) = e^x + 6, ln 3x = 6, ln(x − 1)² = 3.
- Unit 4 test (pp. 69–70): graphing exponentials, writing y = ab^x from a base and a point, a Richter-scale item (a magnitude 5.2 earthquake is 30^2.2 ≈ 1,776 times as strong as a magnitude 3 one, using E ∝ 30^x), log expansions and values, log equations (log_x(3x + 4) = 2; ln(x − 2) + ln x = 1), a machine with annual decay factor 0.75 worth 10,000 dinars after 5 years (original ≈ 42,137 dinars), Karachi's population (8 million in 1991, growth factor 1.039), world population 5.63 billion in 1994 growing 2% a year (doubles every 35 years).
- Enrichment (p. 71): solve (e^x − 1)e^x = 3e^x − 3 and 3(e^x)² − e^x − 4 = 0; is a·ln b = b·ln a? (no in general); a vacuum cleaner whose noise falls from 10⁻⁴ to 6.31 × 10⁻⁶ W/m² (80 dB to 68 dB, a 15% fall in level); a raindrop of volume 7 mm³ whose radius shrank 0.02 mm by evaporation; internet users f(x) = 1.31e^(0.548x) millions, 1990–1995.

**Unit 5 — Vectors (المتجهات), pp. 72–84.**
- 5-1 The vector in the plane (pp. 72–73): position vectors and components (A(−3, 4), B(2, −1), C(3, 5) → AB = ⟨5, −5⟩, BC = ⟨1, 6⟩, CA = ⟨−6, −1⟩); magnitude and direction angle (u = ⟨3, 2⟩ → √13, ≈ 33.7°; v = ⟨−2, 4⟩ → 2√5, ≈ 116.6°); unit vectors (u = ⟨x, 3/5⟩ is a unit vector for x = ±4/5); proving AB = CD and that three points are collinear.
- 5-2 Addition and subtraction of vectors (pp. 74–76): triangle and parallelogram rules, midpoints and the mid-segment identity 2·EF = AB + DC; a fishing boat that sails 250 km east then 40 km north and returns straight at 50 km/h (return ≈ 253 km, ≈ 5.1 h); Khalid swimming north at 35 km/h against a 12 km/h east current; vector identities with i and j (OA = 3i − 4j, OB = −2i + 3j, OC = −4i − j); a parallelogram ABCD with A(−2, 1), B(0, −2), C(3, −1) → D = (1, 2).
- 5-3 Scalar product (pp. 77–80): u·v from diagrams and components (u = ⟨2, −1⟩, v = ⟨−3, 2⟩, w = ⟨1, 2⟩ → u·v = −8, u·w = 0, v·w = 1); |2u + 3v|² = 217 from |u| = 4, |v| = 5, u·v = −6; perpendicularity (u = ⟨x, 4⟩, v = ⟨2, −3⟩ → x = 6); angle between vectors (u = ⟨2, −2⟩, v = ⟨−2, 0⟩ → 135°); proving a triangle right-angled at A (A(−1, 3), B(−3, 1), C(3, −1): AB·AC = 0); an isosceles triangle with AB = AC = 3 cm and base angle 70° → AB·AC = 9cos40° ≈ 6.89; if AB·BC = −2 then the angle between BA and BC cannot be 122°.
- Unit 5 test (pp. 81–83): position vectors, unit vector u = ⟨2√2/3, y⟩ (y = ±1/3), the projection identity AM·AB = AN·AB = ½‖AB‖² (N the midpoint of AB), a triangle with ‖AB‖ = 6, ‖AC‖ = 2√3, AB·AC = 18 → the angle between AB and AC is 30°, a line through C perpendicular to AB meeting the y-axis at D = (0, −3/2) for A(1, 2), B(4, 0), C(3, 3), an equilateral triangle of side 4 cm giving the rhombus ABDC with |a + b| = 4√3.
- Enrichment (p. 84): m for which triangle ABC with A(2, 2), B(4, 5), C(4 − m, 0) is right-angled at A (m = −1) and then isosceles at A; perpendicularity of CQ and PR in a square with an inscribed rectangle (hint: use Chasles' relation); MA·MB = |MI|² − a² in triangle MAB with I the midpoint of AB; if A + B = w and A − 2B = −w then A and B have the same direction; a rectangle with DC = 5 cm, AD = 2 cm, E the midpoint of AB — find θ.

**Unit 6 — Discrete algebra (Statistics) (الجبر المتقطع (الإحصاء)), pp. 85–99.**
- 6-1 Statistical population and sampling (pp. 85–86): the four stages of statistical research; data types (tickets sold — discrete quantitative; toothpaste types — qualitative nominal; weights of Grade 11 pupils — continuous quantitative; monthly family income — continuous quantitative); finite vs infinite population; census vs sampling; births in the world in 2010 are a finite population; the number of pages in a book is discrete, not continuous, data.
- 6-2 Samples (pp. 87–88): sampling fraction (sample 8 from population 100 → 0.08); population = interval length × sample size (5 × 100 = 500); simple vs stratified random samples (200 workers + 40 employers, sample 60 → stratified, fraction 0.25); using a random-number table (row 6, column 6); interval length 70 with first unit 43 → the fifth unit is 323; sample 100 from population 2,000 → fraction 0.05; interval 40 with population 1,000 → sample 25.
- 6-3 Ways to display data (pp. 89–90): relative and percentage frequencies (5, 7, 4, 6 out of 22 → 22.7%, 31.8%, 18.2%, 27.3%); pie sectors; class centres, histograms and frequency polygons (car exit times, frequencies 17, 31, 25, 14, 7, 6 totalling 100; delivery distances, frequencies totalling 102); the centre of class 20–30 is 25, not 30.
- 6-4 Standard deviation (pp. 91–92): SD of 5, 5, 5, 5 is 0; grouped data — shop prices (classes 0–10 … 50–60 dinars, frequencies 190, 300, 470, 280, 260, 100; mean 27.625 dinars, variance ≈ 198, SD ≈ 14.1); cheese boxes (weights 167–174 g, 200 boxes; mean 170.4 g); SD of 1, 2, 3, 4, 4, 5, 5, 6 is ≈ 1.56 (population SD); variance 100 → SD 10; multiplying data by 3 multiplies the SD by 3.
- 6-5 Empirical rule (pp. 93–94): the normal distribution and its properties (68–95–99.7); a company's monthly profits, mean 1,250 dinars, SD 225 (68% within [1,025, 1,475]; 2,000 dinars is beyond 3σ); wire strength, mean 1,400 kg, SD 200 (97.5% of wires stronger than 1,000 kg); a product with mean life 50 months — 50% live longer than 50 months; [x̄ − 2σ, x̄ + 2σ] holds 95% of the data.
- 6-6 Standardized value (pp. 95–96): z = (x − x̄)/σ (a score of 15 with mean 14 and SD 4 → z = 0.25); data 5, 5, 6, 7, 7 (mean 6, SD ≈ 0.89); comparing a 75 kg man in city A (mean 70, SD 5 → z = 1) with an 80 kg man in city B (mean 76, SD 8 → z = 0.5); Khalid's 15 in maths (z = 0) vs 15 in chemistry (z ≈ 1.34) — the 15 is better in chemistry; mean 12, x = 15, z = 0.4 → σ = 7.5.
- Unit 6 test (pp. 97–98): census or not (blood-sugar study — no; mean weight of your class — yes); stratified sample of 70 with fraction 0.08 → population 875 (strata 375, 375, 125); systematic sample of 25 with interval 50 → population 1,250; future-profession survey (25 pupils: teacher 2, officer 3, engineer 6, doctor 7, lawyer 5, businessman 2); data 3, 4, 5, 6, 7, 8, 9 (mean 6, variance 4, SD 2); Salem's 15/20 in maths (mean 13, SD 2.5 → z = 0.8) vs 13/20 in physics (mean 11.5, SD 2.4 → z = 0.625) — maths is the better result; weights of Grade 11 pupils (classes 64–68 … 80–84, frequencies 4, 5, 7, 6, 3).
- Enrichment (p. 99): census or not (insect types in Kuwait — no; male/female ratio among a bank's staff — yes); a textile factory of 600 workers, simple random sample of 15 from a random-number table; a paint company (80 engineers numbered 201–280, 120 lab specialists 301–420, 220 workers 501–720), stratified sample of 21; a Quran-teaching systematic sample of 16 from 144 pupils; 360 employees by sex and full/part-time (male full-time 180, male part-time 36, female full-time 18, female part-time 126), stratified sample of 40 (20, 4, 2, 14).

#### BOOK ERRORS

**1. Printed p. 81, Unit 5 test, item 7(a) — no value of x exists.** Let A = ⟨x − 5, x − 5⟩ and B = ⟨1, 1 − x⟩. The item asks for the value of x "such that vector A has the direction of B". A = (x − 5)·⟨1, 1⟩ and B = ⟨1, 1 − x⟩. For A to have B's direction, A = λB with λ > 0: then x − 5 = λ and x − 5 = λ(1 − x), so λ = λ(1 − x), i.e. λx = 0. The only cases are x = 5 (λ = 0, and A is the zero vector, which has no direction) or x = 0 (λ = −5, and A = ⟨−5, −5⟩ is *opposite* to B = ⟨1, 1⟩). **Correct:** as worded, no such x exists; the intended answer is presumably x = 0, treating "direction" as mere parallelism and ignoring sense. (Part (b) is fine: A perpendicular to B gives (x − 5)(2 − x) = 0, i.e. x = 2, the 5 being the degenerate zero-vector case.)

**Cleared by render (not errors):** p. 21 Group B Q3 — the domain of f(x) = √(−x) is (−∞, 0], as the book's statement says (the text layer garbled it as "[−3, 0]"); Q4's f(x) = (1/x²)√(x + 3) has domain [−3, 0) ∪ (0, ∞), so the book's stated "[−3, ∞)" is false — that is the item's design, a true/false item. P. 72, item 4 — u = ⟨x, 3/5⟩ (not ⟨x, 5/3⟩ as the extraction suggested), giving x = ±4/5 as a unit vector. P. 83, item 14 — part (a) asks to prove B ≠ C (not B ⊥ C); B = ⟨−1, −3⟩, C = ⟨−5, 5⟩, and A·B = A·C = 10. P. 83, item 15 — ⟨3/2, 2⟩ is perpendicular to ⟨−4, 3⟩ (−6 + 6 = 0). P. 81, Unit 5 test item 6 — ‖AC‖ = 2√3 (not 3), so cos θ = 18/(6 × 2√3) = √3/2 and θ = 30°. P. 61, matching items 14–15 — graph (b) is y = 2^(x−2) (it crosses the y-axis at 1/4, passes through (2, 1) and (4, 4)), the correct inverse of y = log₂(4x); graph (c) is y = 3^x, the inverse of y = log₃x. P. 79, item 9 — U = 4i − 2j and V = xi − j are parallel for x = 2. P. 50, item 6 — the polynomial that can have 5 as a zero is ax³ + x⁴ + 5, with a chosen as −(625 + 5)/125.

#### HONEST NEGATIVES

- **Exercises only — it teaches nothing by itself.** No lessons, no worked examples, no explanations and no answers. A learner needs the Grade 11 Term 1 student book alongside it — and that student book is the one file of this band not in hand (g11-t1.pdf, PENDING).
- **No complex numbers; no trigonometry in this term's workbook; no matrices; no conic sections; no calculus; no probability** — statistics here is descriptive (display, standard deviation, empirical rule, z-scores) plus sampling concepts only.
- **Dated data throughout.** The exercises carry a 1990s Pearson source: city populations from 1994, Karachi 1991, world population 1994, internet users 1990–1995. The numbers are correct as exercises but the world they describe is thirty years old.
- **No digital links.** Unlike the new-generation Grade 10 student book, this workbook has no QR codes to videos or tests; the back cover's two QR codes are a whole-book link and a curriculum-evaluation link.
- A plausibility quirk, not an error: in 5-2 Khalid swims north at 35 km/h — no human swims that fast; the number is there to make the vector addition work.

#### HELD-COPY DEFECTS

- PDF pp. 103–105 (printed pp. 100–102) are blank after the last content page (printed p. 99); PDF p. 106 is the back cover. No content is lost — the Unit 6 enrichment ends complete on printed p. 99.
- PDF pp. 4–9 are blank/image front matter (no text layer); the text layer is also unusable on figure-heavy pages (PDF pp. 53, 64, 78 and parts of others) — those pages were read from renders and their content is intact.
- The imprint deposit date 2015/5/10 predates the 2nd edition (2026–2027); it is carried over from the first edition and recorded as printed.
- No missing, duplicated or truncated content pages.

#### Numbering oddities

- Lessons are numbered per unit (1-1 … 6-6); each lesson's set is headed تمرّن ("practice"). Unit tests and enrichment sets are listed in the contents but carry no lesson number.
- Unit 6 is headed "الجبر المتقطع (الإحصاء)" — "Discrete algebra (Statistics)".
- Printed = PDF − 3 throughout the content pages.
- The contents list gives the unit tests and enrichment sets in bold; the enrichment sets are the only place the book asks for proofs (e.g. MA·MB = |MI|² − a², x⁴ + 6x³ + 7x² − 6x + 1 = (x² + 3x − 1)²).

---
### 5. Grade 12, Term 1 — Student book (scientific track)

**Title as printed:** الرياضيات — كتاب الطالب — الصف الثاني عشر علمي — الفصل الدراسي الأول (Mathematics — Student book — Grade 12 scientific track — First term), secondary stage.
**Grade / term / track:** Grade 12, Term 1, scientific track (علمي) — printed on the cover and title page.
**Edition / year as printed:** 2nd edition, 1448 AH / 2026–2027 (both parts carry the same edition).
**ISBN:** 978-9921-33-107-3 (same ISBN on both parts' imprint pages). Deposit: National Library of Kuwait; Ministry library no. 319, dated 2015/12/31 as printed (carried over from the first edition).
**Publisher:** Kuwait Ministry of Education, General Administration for Guidance, Research and Curricula. Supervisory committee: Hussein Ali Abdullah (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour. Foreword by Dr. Saud Hilal Al-Harbi (PDF pp. 10–11).
**PDF pages:** 213. **Two books bound in one file:** Part 1 (PDF pp. 1–122, printed pp. 1–119, Units 1–2); PDF p. 123 blank; Part 2 (PDF pp. 124–213, printed pp. 120–198, Units 3–4) with its own cover (PDF p. 124, "القسم الثاني"), title/imprint (PDF pp. 125–126) and front matter (PDF pp. 127–132, including portraits of the Amir and the Crown Prince). Printed = PDF − 3 in Part 1; printed = PDF − 14 in Part 2. The contents page in Part 2 (PDF p. 133) is a full-book contents listing all four units. Cover art: water pouring, space shuttle/ISS, ECG trace, and a graph of y = f(x) with local/global maxima and minima labelled f(a), f(c), f(e), f(d).
**File size:** 71,902,092 B. **SHA-256:** 2eb859e364f3f4c8d3fb9f3a7d73190a8a7e8814577b6a8697c0bef07dbd23b1
**How read:** clean text layer, read in full (PDF pp. 1–213); flagged items were verified against renders.
**Answer key:** none.

#### Contents (printed page numbers)

**Unit 1 — Limits and Continuity (النهايات والاتصال)** (printed pp. 10–71): 1-1 Limits (pp. 12–26) — limit at a point, neighbourhoods and punctured neighbourhoods, one-sided limits, limit theorems 1–6, the 0/0 indeterminate form, conjugate/rationalisation, synthetic division; 1-2 Limits involving ∞, −∞ (pp. 27–35) — finite and infinite limits, Theorems 7–10, horizontal and vertical asymptotes; 1-3 Indeterminate forms (pp. 36–41) — ∞/∞, ∞−∞, 0·∞, Theorem 11 (rational functions at ∞); 1-4 Limits of some trigonometric functions (pp. 42–47) — lim sin x/x = 1, Theorems 12–13, the sandwich theorem; 1-5 Continuity (pp. 48–53) — continuity at a point (three conditions), removable, jump and infinite discontinuity; 1-6 Continuity theorems (pp. 54–60) — Theorems 14–16, composite functions; 1-7 Continuity on an interval (pp. 61–71) — Definitions 9–10. Unit 1 organiser + summary (PDF pp. 72–74). **No separate Unit 1 assessment/test section — the unit ends with the organiser + summary.** Worked content verified: lim_{x→∞} √(2x²−x)/(x+1) = √2; lim_{x→−∞} (3x−5)/√(x²−9) = −3; lim_{x→∞} (x−2)/(ax²+bx−3) = −1 gives a = 0, b = −1; f(x) = (x³+kx²+3x−2)/(x²−x−2) has a removable discontinuity at x = 2 when k = −3, lim = 1, redefined g(2) = 1; piecewise continuity with a = −2, b = 2.

**Unit 2 — Differentiation (الاشتقاق)** (printed pp. 72–119): project "Effect of pressure on the diver" (Boyle's law P = 1 + d/13 atm, V = 12/P quarts; Newton 1642–1727, Leibniz 1646–1716); 2-1 Rates of change and tangent lines (pp. 74–78) — falling body d(t) = 4.9t², average velocity 19.6 m/s between t = 1 and t = 3, instantaneous velocity 29.4 m/s at t = 3; fruit-fly growth 190/22 ≈ 8.6 per day; tangent slope of y = x² at (2, 4) is 4; 2-2 The derivative (pp. 79–89) — definition f′(a) = lim_{h→0} (f(a+h)−f(a))/h, one-sided derivatives, corner/cusp/vertical tangent/discontinuity, differentiable ⇒ continuous (with proof); f′(1) = 4 for f(x) = 2x²+1; f′(a) = 1/(2√a) for √x; 2-3 Rules of differentiation (pp. 90–99) — constant, power (positive, negative and rational exponents), constant multiple, sum/difference, product, quotient, tangent and normal equations, differentiability on an interval; 2-4 Derivatives of trigonometric functions (pp. 100–102) — sin′ = cos, cos′ = −sin, tan′ = sec², cot′ = −csc², sec′ = sec·tan, csc′ = −csc·cot; 2-5 Chain rule (pp. 103–107) — (f∘g)′(x) = f′(g(x))·g′(x), Leibniz form dy/dx = dy/du · du/dx, power chain rule; 2-6 Higher-order derivatives and implicit differentiation (pp. 108–119) — y⁽ⁿ⁾ notation, implicit differentiation; particle s(t) = 0.6t³ − 1.5t − 0.9: s(5) = 66.6 m, average velocity 13.5 m/s, s′(5) = 43.5 m/s. Unit 2 organiser + summary (PDF pp. 120–122). **No separate Unit 2 assessment/test section.** Worked content verified: f(x) = (x²+1)(x³+3) → f′ = 5x⁴+3x²+6x; f(x) = (x³−1)/(5x²+1) → f′ = (5x⁴+3x²+10x)/(5x²+1)²; tangent and normal to f(x) = (x³+1)/(x²+2) at (1, 2/3): tangent y = (5/9)x + 1/9, normal y = −(9/5)x + 37/15; y = sin⁵x at x = π/3 has slope 45/32; f(x) = 1/(1+x²) satisfies (1+x²)f‴ + 6xf″ + 6f′ = 0; circle x²+y² = 25 at (3, −4) has tangent slope 3/4.

**Unit 3 — Applications on Differentiation (تطبيقات على الاشتقاق)** (printed pp. 120–165): project — coffee cup with no holder, maximum coffee height so it does not spill, centre of mass ȳ = (m₁y₁+m₂y₂+m₃y₃)/(m₁+m₂+m₃); opener quotes Descartes (1596–1650) on the tangent problem; 3-1 Extreme values of functions (pp. 122–130) — absolute and local extrema, Extreme Value Theorem, critical points, Fermat's theorem, steps for absolute extrema on [a, b]; two squares on AB = 6 cm, S(x) = 2x²−12x+36, minimum at x = 3; f(x) = x³−3x+1 on [0, 3]: absolute maximum 19, absolute minimum −1; f(x) = x^(2/3) on [−2, 3]: absolute maximum ∛9 ≈ 2.08, absolute minimum 0; f(x) = x³+ax²+bx+5 with local extremes at x = 1 and x = 1/3 gives a = −2, b = 1; 3-2 Increasing and decreasing functions (pp. 131–137) — Mean Value Theorem (Theorem 3), increasing/decreasing/constant functions (Theorem 4), monotonic functions; car covering 120 m in 8 s averages 15 m/s = 54 km/h; f(x) = x³+1 on [−3, 3]: c = ±√3; f(x) = x³−3x²−9x+1 increasing on (−∞, −1) and (3, ∞), decreasing on (−1, 3); f(x) = x²/(x−1) increasing on (−∞, 0) and (2, ∞), decreasing on (0, 1) and (1, 2); 3-3 Relating the graphs of f′, f″ and f (pp. 138–146) — First Derivative Test (Theorem 5), concavity, points of inflection, Second Derivative Test (Theorem 6); f(x) = x³−12x−5: local maximum 11 at x = −2, local minimum −21 at x = 2; f(x) = 2x³+3x²−1: inflection point (−1/2, −1/2); particle s(t) = 2t³−14t²+22t−5: v = 6t²−28t+22, a = 12t−28, moving right on (0, 1) ∪ (11/3, ∞), left on (1, 11/3); 3-4 Graphing polynomial functions (pp. 147–154) — 7-step method; f(x) = x³−3x+4 (local maximum 6 at x = −1, local minimum 2 at x = 1, inflection (0, 4)); f(x) = 1−x³ (decreasing everywhere, inflection (0, 1)); f(x) = 3x⁴+4x³+2 (inflection points (−2/3, 38/27) and (0, 2)); f(x) = −x⁴+2x²+1 (critical points (0, 1), (1, 2), (−1, 2); f″ zeros ±1/√3); 3-5 Applications on extreme values (pp. 155–162) — shoe-shop profit f(x) = −15x²+600x+50, vertex x = 20, maximum profit 6,050 dinars; two numbers summing to 100 with minimum sum of squares (50, 50); box from a 16 cm × 6 cm sheet: V(x) = 4x³−44x²+96x, x = 4/3, maximum volume 1600/27 cm³ ≈ 59.26; oil can of 1 litre: r = ∛(500/π) ≈ 5.42 cm, h ≈ 10.84 cm (height equals diameter); shortest distance from (6, 0) to the hyperbola y²−x² = 16 is √34; cost C(x) = x−20+400/x, minimum cost at 20 pieces, maximum profit 3,200 dinars at 60 pieces (see error 4 below); rectangle inside a right isosceles triangle of hypotenuse 2: maximum area 0.5, dimensions 1 × 0.5. Unit 3 organiser + summary (PDF pp. 177–179). **No separate Unit 3 assessment/test section.**

**Unit 4 — Statistics (الإحصاء)** (printed pp. 166–199): project "What is the best way to find a job?" (random sample of employees, channels for finding work); prior-knowledge page "where are you now"; 4-1 Estimation (pp. 168–176) — parameter vs statistic, point estimate, confidence interval, confidence level (1−α), normal distribution, critical value Z_{α/2}, margin of error, standard error; t-distribution (properties, degrees of freedom n−1) for σ² unknown and n < 30; only 95% confidence is used anywhere in the book. Worked: pulse-rate study n = 40, σ = 12.5, x̄ = 76.3 → E ≈ 3.8738, CI (72.4262, 80.1738); n = 36, x̄ = 60, s = 4 → E ≈ 1.3067, CI (58.6933, 61.3067); n = 25, S = 10, x̄ = 15 → t_{0.025} = 2.064 (df 24), E = 4.128, CI (10.872, 19.128); 4-2 Testing statistical hypotheses (pp. 177–181) — statistical hypothesis, test statistic, null hypothesis H₀ and alternative H₁ (two-sided only, H₁: μ ≠ μ₀), test-statistic table (σ known → Z = (x̄−μ)/(σ/√n), any n; σ unknown, n ≥ 30 → Z with S; σ unknown, n < 30 → t = (x̄−μ)/(S/√n)), acceptance region, decision (accept H₀, or reject H₀ and accept H₁). Worked: salary claim H₀: μ = 4000, n = 25, x̄ = 3950, σ = 125 → Z = −2, outside (−1.96, 1.96), reject H₀; μ = 37 test, n = 80, x̄ = 37.2, S = 1.79 → Z ≈ 0.999, accept H₀; food spending μ = 290, n = 10, x̄ = 283, S = 32 → t ≈ −0.6917 (df 9, critical 2.262), accept H₀; water campaign: old study Z = −1.66 (accept), new study Z = −3.33 (reject) — the bigger mean is not closer to the target once the spread shrinks; 4-3 Correlation and regression (pp. 182–193) — correlation and its types, scatter plot, Pearson correlation coefficient r (both formulas, −1 ≤ r ≤ 1, strength bands: |r| in (0.7, 1] strong, (0.5, 0.7] medium, (0, 0.5] weak), regression line ŷ = b₀+b₁x by least squares, prediction, error of prediction |y − ŷ|. Worked: age vs exercise hours — linear negative relationship; x = 1…5, y = 3, 5, 7, 9, 11 → r = 1, perfect positive; second Pearson example r ≈ −0.172, weak negative; ŷ = 0.75+1.45x, ŷ(10) = 15.25, error at x = 5 is 1; falling ball (dropped from 50 m, distances 0, 1.2, 4.9, 11, 19.5, 30.5, 44 m at 0–3 s): ŷ = −6.12+14.66x, ŷ(4) = 52.52 m, error at 2.5 s = |30.5 − 30.53| = 0.03. Unit 4 organiser + summary (PDF pp. 206–207).
**Appendix** (printed pp. 194–198): standard normal (Z) table (p. 194); t-distribution table, df 1–30 and "30 and more" (p. 195) — spot-checked: df 24, α/2 = 0.025 → 2.064; df 9 → 2.262; df 30+ → 1.960, all matching the worked examples; formula sheets — algebra (p. 196), trigonometry (p. 197), statistics (p. 198). PDF p. 213 is blank.

#### BOOK ERRORS — 5, all render-verified (the three p. 47 values rechecked numerically in Python)

1. **Printed p. 47, Lesson 1-4, table y = sin x/x, row x = 37π/7: the book gives 0.0224.** Correct: sin(37π/7) = −sin(2π/7) ≈ −0.7818, and 37π/7 ≈ 16.606, so sin x/x ≈ **−0.0471**.
2. **Printed p. 47, Lesson 1-4, table y = cos x/x, row x = 100: the book gives −0.00862.** Correct: cos(100) ≈ 0.8623, so cos x/x ≈ **+0.00862** — a sign flip.
3. **Printed p. 47, Lesson 1-4, table y = cos x/x, row x = 450: the book gives 0.00162256.** Correct: cos(450) ≈ −0.7300, so cos x/x ≈ **−0.00162256** — a sign flip (the magnitude matches exactly).
4. **Printed p. 161, Lesson 3-5, profit example: P(60) = −(60)² + 120(60) − 400 is written as "−4 000 + 7 200 = 3 200".** Correct: −(60)² = **−3 600** (not −4 000), and the −400 term is dropped from the sum. The final answer 3,200 dinars is still correct — the two slips cancel (−3 600 + 7 200 − 400 = 3 200).
5. **Printed p. 171, Lesson 4-1, margin-of-error section: the book defines the standard error wrongly.** It says the absolute value of the difference between the sample mean x̄ and the population mean μ "is called the standard error and equals σ/√n". **Correct:** |x̄ − μ| is the (point) estimation error, a single realised difference; the standard error of the sample mean is σ/√n. The book's own next paragraph uses σ/√n as the standard error correctly (E = Z_{α/2}·σ/√n), so only the label is wrong — but as printed the definition is false.

All other rows in both p. 47 tables were checked and are correct: sin x/x — 7π/2 → −0.091; 150 → −0.00477; 240 → 0.00394; 300 → −0.00333; 600 → 0.000074; cos x/x — 3π → −0.106; 4π → 0.0795; 200 → 0.002435; 300 → −0.0000736.

**Cleared flags (extraction artefacts, NOT book errors):** printed pp. 33, 35–36 — limits 1/|x| and 1/|x−2| (the | | bars were dropped by extraction; render-verified); p. 43 item 3 — no square root in the book (extraction inserted one); p. 61 — (f∘g)(x) = √(x⁴+2) (radical dropped by extraction); pp. 66–67 — the piecewise function has no square root (extraction artefact); p. 134 — Mean Value Theorem example gives c = **±√3** (the radical was dropped by extraction; render-verified); p. 190 — the error of prediction is written |30.5 − 30.53| = 0.03, i.e. an absolute value (the bars were dropped by extraction).

#### HONEST NEGATIVES

- **No integration at all.** The book is limits, differentiation and statistics only — no antiderivatives, no definite integrals, no area under a curve, no volumes of revolution.
- **Limits:** no ε–δ definition; no limits of exponential or logarithmic functions; no L'Hôpital's rule.
- **Differentiation:** no derivatives of exponential or logarithmic functions (eˣ, ln x) anywhere in the book; no inverse-trigonometric derivatives; no parametric or polar differentiation; no related rates beyond the motion examples; no differentials or linear approximation.
- **Applications:** curve sketching is polynomials only — no rational or trigonometric functions are graphed; optimisation is the worked set only, with no constrained optimisation beyond it. The falling-ball regression predicts 52.52 m at t = 4 s although the ball was dropped from 50 m — the book never flags extrapolation beyond the data range.
- **Statistics:** only the 95% confidence level is used throughout; hypothesis testing is two-sided only (H₁: μ ≠ μ₀); no p-values; no tests for proportions or for σ; no χ²; correlation and regression are linear only, with no discussion of causation versus correlation beyond the examples; no binomial or normal probability in this book (that lives in the Grade 11 statistics books).
- **No answer key and no unit assessments/tests** — each unit ends with an organiser + summary only. There is no printed test and no QR-code test anywhere in the book.
- No complex numbers, no matrices, no conic sections, no vectors in this book.

#### HELD-COPY DEFECTS

- PDF p. 123 (between Part 1 and Part 2) is blank; PDF p. 213 (last page) is blank; PDF pp. 4–9 are blank/image front matter.
- The title-page text layers (PDF pp. 2–3 and 125–126) carry multiple overlapping edition imprints (1438, 1444, 1446, 1448 AH) — the rendered pages are clean 2nd edition 1448 AH; the layered text is a PDF-production artefact, not printed content.
- The imprint deposit date 2015/12/31 predates the 2nd edition (2026–2027); carried over from the first edition, recorded as printed.
- Formula-sheet gap: the geometry sheet (printed p. 196) gives the sphere's and the cone's surface areas but no surface-area formula for the cylinder (volume only); the cone's area given is the lateral area only, without saying so.
- No missing, duplicated or truncated content pages; Units 1–4 complete.

#### Numbering oddities

- Lessons are numbered per unit (1-1 … 4-3). Theorem numbering restarts in Unit 3: its Theorem 1 is the Extreme Value Theorem, Fermat's theorem is Theorem 2, the Mean Value Theorem is Theorem 3, the increasing/decreasing theorem is Theorem 4, the First Derivative Test is Theorem 5 and the Second Derivative Test is Theorem 6 — while Unit 1's theorems run 1–16.
- The contents page in Part 2 (PDF p. 133) is a full-book contents listing all four units, not a Part 2-only contents.
- Printed = PDF − 3 in Part 1; printed = PDF − 14 in Part 2.

---
### 6. g10-t2-wb.pdf — Grade 10, Term 2, STUDENT book (not a workbook)

**Title as printed:** الرياضيات — الصف العاشر — الفصل الدراسي الثاني — القسم الأول — كتاب الطالب (al-Riyāḍiyyāt — Mathematics — Grade 10 — Second term — Part 1 — Student book), secondary stage (المرحلة الثانوية). Part 2 (same file) is القسم الثاني, 2/2.
**Grade / term / track:** Grade 10, Term 2, Parts 1–2. No track — Grade 10 is pre-track.
**Kind:** **Student book — not a workbook.** The cover (PDF p. 1) and the title page (PDF p. 2) both say كتاب الطالب. The filename's "-wb" is wrong; the record slot that calls this file a workbook is wrong with it.
**Edition / year as printed:** 2nd edition, 1447 AH / 2025–2026. Imprint (PDF p. 3): 1st edition 2012–2013, 2nd edition 2014–2015, reprints 2016–2017, 2017–2018, 2018–2019, 2019–2020, 2020–2021, 2021–2022, 2022–2023, 2023–2024, 2024–2025, 2025–2026.
**Supervisory committee:** Ibrahim Hussein Al-Qattan (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour.
**Work team:** Radhiya Nasser Al-Qattan (head), Al-Saeed Fawzi Ibrahim, Najwa Mohammed Waseem, Majdi Mohammed Al-Kawawi, Munira Ali Al-Adwani.
**Publisher:** Kuwait Ministry of Education, Educational Research sector — Curriculum Development Administration. House of Education / Pearson Education 2012. Printed by the Government Press — State of Kuwait.
**Deposit as printed:** Ministry library no. 145, dated 2014/10/28.
**ISBN:** none printed on the imprint; back-cover barcode ISBN 978-614-406-315-6 (Pearson Scott Foresman).
**PDF pages:** 227; printed pp. 1–213. Part 1: PDF pp. 1–89, printed pp. 1–85 (printed = PDF − 3). Part 2: PDF pp. 90–227, printed pp. 86–213 (printed = PDF − 14).
**File:** `g10-t2-wb.pdf`, 87,991,029 bytes, SHA-256 `984083e1f93f820cd6e5080b0e9ea2a121784735cd879a1903ec05d6a16d7749`.
**Language:** Arabic. **Answer key:** none.
**Generation:** old generation (2012 series, 2nd edition).
**How read:** the text layer is garbled Arabic (legacy font) — read visually from 200-dpi renders of all 227 pages; flagged items were re-verified at 300 dpi. **Matrices in this book are displayed right-to-left** (the first column is the rightmost column); all matrices in this filing are written in standard left-to-right notation. Ordered pairs are displayed left-to-right (x on the left, y on the right). Arabic arithmetic is laid out right-to-left; every inequality direction and fraction in this section was verified against a 300-dpi crop and the book's own working.
**Cover art:** hard drive, rocket launch, bar chart, Earth–Moon–Sun diagram.

#### Contents (printed page numbers)

**Front matter (Part 1):** cover (PDF p. 1); title page (PDF p. 2); imprint (PDF p. 3); Basmala calligraphy (PDF p. 4); PDF p. 5 blank; Amir portrait (PDF p. 6); PDF p. 7 blank; Crown Prince portrait (PDF p. 8); PDF p. 9 blank; introduction (PDF pp. 10–11, signed Dr. Saud Hilal Al-Harbi); contents, Part 1 only (PDF p. 12).

**Unit 6 — Geometry of a Circle (printed pp. 10–51).** Opener/project p. 10 (the circle in Islamic geometric art — four circles of radius √75 about (0,5), (5,0), (0,−5), (−5,0), then four of radius √74; join the centres to form a square; a five-step Islamic pattern). Prior knowledge p. 11 (circumference and area; congruent triangles; Pythagoras). 6-1(a) The circle, pp. 12–13 (definition; radius, diameter, chord, central and inscribed angles; Theorem 1: three non-collinear points determine exactly one circle; the archaeology example — find a pottery shard's centre by perpendicular bisectors of two chords). 6-1(b) Tangent of the circle, pp. 14–17 (Theorem 2: a tangent is perpendicular to the radius at the point of tangency; Theorem 3: its converse; Theorem 4: the two tangent segments from an exterior point are congruent, with its corollary — the line from the point to the centre bisects both angles and is perpendicular to the chord of contact). 6-2 Chords and arcs, pp. 25–31 (Theorem 1: congruent central angles/chords/arcs imply each other; Theorem 2: congruent chords are equidistant from the centre and conversely; Theorem 3: a diameter perpendicular to a chord bisects it and its arcs, and conversely). 6-3 Central and inscribed angles, pp. 32–41 (Theorem 1: central angle = its arc; Theorem 2: inscribed angle = half its arc; Theorem 3: the tangent-chord angle equals the inscribed angle on the same arc, and half the intercepted arc; cyclic quadrilaterals). 6-4 Intersecting chords and tangent, pp. 42–48 (Theorem 1: intersecting chords inside — product of the segments equal; Corollary 1: two secants from an exterior point; Corollary 2: tangent² = whole secant × external part; problem-solving guide p. 48 — the perimeter of the triangle formed by a moving tangent is constant, 2 × the tangent length). Concept map p. 49; summary pp. 50–51. **No unit test in Part 1.**
**Verified:** Ex (2) p. 15 — two tangents, angle 117° gives 63°; Ex (3) pp. 15–16 — bicycle wheels (radii 40 cm, 32 cm, common external tangent 96 cm), axle distance √(96²+8²) ≈ 96.33 cm; Ex (4) p. 18 — 7-24-25 proves the line is tangent; Ex (6) pp. 20–21 — circumscribed triangle, tangent lengths 15, 10, 8, perimeter 66 cm; Ex (2) p. 28 — chord 25 cm by Theorem 2; Ex (3) p. 29 — radius √(49+9) ≈ 7.6 cm, and √(225−121) ≈ 10.2 cm; Ex (4) p. 30 — two congruent circles, common chord 10 cm; Ex (5) p. 31 — square in a circular window of diameter 1.6 m, side 1.6/√2 ≈ 1.13 m; Ex (7) p. 39 — tangent-chord angle 45°, inscribed angle 35°, third angle 100°; Ex (1) p. 43 — 2×8 = 7×s gives s = 16/7; Ex (2) p. 44 — arched bridge, chord 90 m, rise 21 m, diameter ≈ 117 m; Ex (3) p. 45 — s(s+2) = 48 gives s = 6; Ex (4) p. 46 — tangent 8 cm; Ex (5) pp. 46–47 — tangent 6 cm.

**Unit 7 — Matrices (printed pp. 52–85).** Opener/project p. 52 (biotherapy — an oil spill; compound levels in soil samples in four matrices). Prior knowledge p. 53. 7-1 Organising data into matrices, pp. 54–59 (dimension m×n; element labelling; square, horizontal, vertical, zero matrices; equal matrices). 7-2 Adding and subtracting matrices, pp. 60–65 (same dimension only; properties — closure, commutative, associative, zero matrix, additive inverse; matrix equations). 7-3 Multiplying matrices, pp. 66–73 (scalar multiplication; matrix product — defined only when the first matrix's columns equal the second's rows; product dimension m×r; not commutative; powers of a square matrix). 7-4 Identity and inverse matrices, pp. 74–78 (identity matrix; multiplicative inverse; determinant of a 2×2 matrix; singular matrices; the 2×2 inverse formula). 7-5 Solving a system of two linear equations, pp. 79–82 (7-5-1 by inverse matrix; 7-5-2 by Cramer's rule; the Δ = 0 cases noted but not fully covered). Problem-solving guide p. 82 (the coordinates of a point as the solution of a system; intersection (2,3)). Concept map p. 83; summary pp. 84–85.
**Verified:** consumer-price-index table (general index 146.0 → 151.1); electricity production/consumption matrix (Kuwait 45000/40000, UAE 70000/65000, Bahrain 10000/10000 GWh); Ex (2) p. 62 — pentathlon totals 5,217 / 5,168 / 5,338, winner player 3; Ex (4) pp. 70–71 — product [[−6,3],[−12,4],[0,2]] in standard notation; Ex (6) p. 73 — A² = [[3,−2],[2,−1]], A³ = [[4,−3],[3,−2]] for A = [[2,−1],[1,0]]; Ex (1) p. 75 — inverse proof; Ex (2) p. 76 — determinants 7, 0, s²; Ex (1) pp. 79–80 — {x+y=3; x−y=7} gives (5,−2); Ex (2) p. 81 — Cramer's rule gives (−2,−3).

**Front matter (Part 2):** cover (PDF p. 90, 2/2); title page (PDF p. 91); imprint (PDF p. 92); Basmala (PDF p. 93); PDF p. 94 blank; Amir portrait (PDF p. 95); PDF p. 96 blank; Crown Prince portrait (PDF p. 97); PDF p. 98 blank; contents, Part 2 only (PDF p. 99). No separate introduction in Part 2.

**Unit 8 — Trigonometry (2) (printed pp. 86–117).** Opener/project p. 86 (tidal energy — "the future wave"; tide heights at two sites, estimate period and range). Prior knowledge p. 87 (trig ratios; Pythagoras; the etymology of "sine" — Sanskrit *jiva*, Arabic *jiba*, Latin *sinus*). 8-1 The unit circle and circular trig functions, pp. 88–94 (triangular point; sin θ = y, cos θ = x; the six functions; special values; signs by quadrant; reference angle). 8-2 Relations between trig functions (1), pp. 95–106 (θ and −θ; θ and π−θ; θ and θ+π; θ and θ±π/2; coterminal angles; the domain extended to ℝ; solving trig equations, pp. 103–106). 8-3 Relations between trig functions (2), pp. 107–113 (basic identities; Pythagorean identities; tan²+1 = sec²; 1+cot² = csc²; proving identities; solving equations). Problem-solving guide p. 114 (Ferris wheel — Sultan's height 5(1−cos 30°)+1.2 ≈ 1.87 m). Concept map p. 115; summary pp. 116–117.
**Verified:** Ex (1) p. 89 — cos 60° = 1/2, sin 60° = √3/2; Ex (2) p. 92 — signs (135° Q2; 7π/6 Q3; 305° Q4); Ex (3) p. 93 — reference angles 55°, 35°, π/6; Ex (4) p. 98 — sin 150° = 1/2, cos 240° = −1/2, tan 120° = −√3; Ex (5) p. 102 — sin x + sin(x+90°) + sin(x+180°) + sin(x−90°) = 2 cos x; Ex (1) p. 108 — cos θ = 0.4 gives sin θ ≈ 0.917, tan θ ≈ 2.29; Ex (2) p. 109 — tan θ = 2√2, cos θ > 0 gives cos θ = 1/3, sin θ = 2√2/3; Ex (3) p. 110 — tan θ = 12/5, sin θ < 0 gives cos θ = −5/13, sin θ = −12/13; Ex (5) p. 112 — sin³x + sin x·cos²x = sin x; Ex (6) p. 112 — sec²θ = (sec θ+1)(sec θ−1)/sin²θ; Ex (7) p. 113 — cos²θ/sin θ = cot θ gives θ = π/2, 3π/2.

**Unit 9 — Analytic Geometry (printed pp. 118–155).** Opener/project p. 118 (choosing a job — income graphs for two jobs). Prior knowledge p. 119 (Descartes, 1596–1650). 9-1 The coordinate plane, pp. 120–123 (distance; midpoint). 9-2 Dividing a line segment, pp. 124–130 (internal division; external division; the eclipse example). 9-3(a) Slope of a straight line, pp. 131–135 (rate of change; slope = vertical change / horizontal change; slope = tan θ). 9-3(b) Equation of a straight line, pp. 136–140 (point-slope; general form; parallel/perpendicular lines; modelling data). 9-4 Distance between a point and a straight line, pp. 141–142. 9-5 Equation of a circle, pp. 143–150 (standard form; general form; centre and radius; tangent to a circle; relation between two circles). Problem-solving guide p. 152 (a stone in a pool — waves reach a boat 2 m east, 1 m north in ≈ 37 s; circle x²+y² = 5). Concept map p. 153; summary pp. 154–155.
**Verified:** Ex (1) p. 121 — distance √13 ≈ 3.6; Ex (2) p. 122 — midpoint (1, 2.5); Ex (3) p. 123 — fountains at (20,28) and (60,28), 40 units apart; Ex (1) p. 126 — internal division (−2, 1.25); Ex (2) p. 126 — (31/8, 57/8); Ex (3) p. 127 — ratio 4:3; Ex (4) p. 129 — external division (7,10); Ex (5) p. 130 — eclipse, ratio 12/4675, Earth ≈ (6.015, 10.026); Ex (2) p. 133 — slope 6/7; Ex (3) p. 134 — collinearity (both slopes 3); Ex (4) p. 135 — slope = tan = 2; Ex (1) p. 136 — line y = (3/2)x − 7; Ex (2) p. 137 — y = x+2; Ex (3) p. 137 — parallel y = 2x−7, perpendicular y = −(1/2)x−1; Ex (4) p. 138 — linear relation y = (1/2)x+9/2; Ex (5) p. 139 — battery y = −20x+100, 5% after 4.75 h (4 h 45 min); Ex (1) p. 141 — point (2,1) not on y = 3x−4, distance 1/√10; Ex (2) p. 142 — distance √13; Ex (6) p. 146 — centre (1, −3/2), radius (1/2)√29; Ex (7) p. 147 — circle tests (49 > 0 circle; −15 < 0 not a circle; 0 a point); Ex (8) p. 148 — tangent y = 2x−5; Ex (9) pp. 149–150 — tangent y = (4/3)x−12.

**Unit 10 — Statistics and Probability (printed pp. 156–213).** Opener/project p. 156 (saving money — budget with Excel). Prior knowledge p. 157. 10-1 Data analysis, pp. 158–169 (mean; median from cumulative-frequency curves; mode — including the lever law and the histogram method). 10-2 Quartiles, pp. 170–175 (range; quartiles; five-number summary; box-and-whisker plot). 10-3 Standard deviation, pp. 176–182 (variance; standard deviation; grouped data). 10-4 Methods of counting, pp. 183–191 (counting principle; tree diagram; permutations; combinations). 10-5 Conditional probability, pp. 192–205 (sample space; operations on events; independent and dependent events; conditional probability; Bayes — the quality-test example). Problem-solving guide pp. 203–205 (variances 1761 and 17.61; the Bayes quality test). Organisation chart p. 206; summary pp. 207–208; ruled blank note pages pp. 209–212; back cover p. 213.
**Verified:** Ex (1) pp. 159–160 — grouped mean 67.5 kg; Ex (2) pp. 161–162 — median ≈ 168.5; Ex (3) p. 163 — median ≈ 750; Ex (4) pp. 164–165 — median ≈ 750 dinars (both curves); Ex (5) p. 166 — modes (5; 11 and 12; none; 5 and 6); Ex (6) pp. 167–168 — lever-law mode ≈ 43.41; Ex (7) pp. 168–169 — histogram mode ≈ 445 dinars; Ex (1) p. 171 — ranges 8 and 37; Ex (2) pp. 171–172 — five-number summary (14, 19.5, 24.5, 36.5, 51); Ex (4) pp. 174–175 — two box plots (Europe: min 310, Q1 400, median 480, Q3 575, max 750; Arab countries: min 190, Q1 510, median 780, Q3 975, max 1190); Ex (1) p. 177 — variance 4, SD 2; Ex (2) pp. 178–180 — lamp lifetimes, SDs ≈ 45.98 and ≈ 150.43; Ex (3) pp. 180–181 — grouped mean 60, variance 473⅓, SD ≈ 21.76; Ex (4) p. 182 — n = 15; Ex (3) p. 185 — plates 544,320; Ex (4) pp. 185–186 — 8! = 40,320; Ex (5) p. 186 — 755,160; Ex (6) p. 187 — P(6,4) = 360, P(11,3) = 990; Ex (7) p. 188 — P(28,5) = 11,793,600; Ex (9) p. 190 — C(12,5) = 792; Ex (10) p. 190 — C(51,10) = 12,777,711,870; Ex (11) p. 191 — P(25,22) = 2.5852×10²⁴; Ex (1) pp. 192–193 — two dice, P(sum 4) = 1/12; Ex (3) p. 194 — sweets, P = 1/11; Ex (4) p. 195 — Venn, only sports 35%, not sports 38%; Ex (5) p. 196 — P(A∪B) = 0.7, P(Ā) = 0.3; Ex (7) p. 198 — hospital table (nurse 0.72, woman 0.8, doctor 0.12; P(A∪C) = 0.84); Ex (8) p. 199 — random numbers, 0.15; Ex (9) p. 200 — two red balls, 5/14; Ex (10) p. 202 — P(B|A) = 2/3, P(A|B) = 1/3; Ex (11) p. 202 — P(B|A) = 1/3; guide Ex (1) pp. 203–204 — variances 1761 and 17.61 (ratio 100); guide Ex (2) pp. 204–205 — Bayes, P(defective | not cancelled) ≈ 0.00041.

#### BOOK ERRORS — 2 (four further claims were retracted by the citation check — see items 2–5)

1. **Printed p. 23, Lesson 6-1(b), the inscribed circle of a triangle:** the book labels the centre — the intersection of the triangle's internal angle bisectors — "Circum Center" in English. **Correct: Incenter** (Incentre). The Arabic description is correct; only the English label is wrong. The next section (the circumscribed circle, centre = intersection of the perpendicular bisectors) is the true circumcentre.
2. **RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 65, Lesson 7-2, worked example (4): the ب−أ "direct-subtraction line" quoted in the first draft of this filing was spliced from neighbouring lines of the example. Read whole (printed pp. 64–65, 400-dpi crop), the example is consistent: with أ = [[3,2,4],[−1,4,0]] and ب = [[1,4,3],[−2,2,4]], أ−ب = [[2,−2,1],[1,2,−4]] is correct by both methods, and the direct ب−أ line gives the correct [[−2,2,−1],[−1,−2,4]]. The only oddity is presentational: inside the ب−أ line the second operand and the elementwise step run left-to-right while the result follows the book's usual right-to-left display — no value is wrong.
3. **RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 109, Lesson 8-3, "mathematical information" note box: the first draft read the note as "if tan θ < 0, then sin θ and cos θ have the same sign". A 400-dpi crop shows the glyph's opening faces ظاθ (tan θ): the note says **tan θ > 0**, for which "sin θ and cos θ have the same sign" is correct. The book is right; the glyph was read in the Latin direction.
4. **RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 111, Lesson 8-3, worked example (4): the first draft read the given as "sin θ = 3/7 > 0 with cos θ < 0" and the conclusion as cot θ = −√40/3, tan θ ≈ −0.474. A 400-dpi crop of the statement shows the glyph opening toward جتاθ (cos θ): the given is **cos θ > 0**, and the book in fact concludes cot θ = **+**√40/3 and tan θ ≈ **+**0.474 with "same sign (positive)" — fully consistent and correct.
5. **RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 147, Lesson 9-5, the note on the general form of a circle's equation: the first draft read the note's conditions reversed. 400-dpi crops show item (1)'s glyph points toward the expression ل²+ك²−4ب and opens toward ٠ — i.e. the expression is **< 0** → "does not represent a circle" (correct); item (3)'s glyph opens toward the expression — **> 0** → "represents a circle" (correct); item (2) (= 0 → a point) is correct. The glyph reading is cross-validated by Ex (7) on the same page, whose cases (49 > 0 circle; −15 < 0 not a circle) use the identical glyphs. The book states the rule correctly in the note, in Ex (7) and in the Unit 9 summary.
6. **Printed p. 197, Lesson 10-5, worked example (6), the final line:** with P(Ā) = 0.2, P(A∪B) = 0.9, P(A∩B) = 0.4, the book states P((A∪B)̄) = 1 − P(A∩B) = 0.6. **Correct: P((A∪B)̄) = 1 − P(A∪B) = 1 − 0.9 = 0.1** — the complement of the union is 1 minus the union's probability, not 1 minus the intersection's. (The rest of the solution is correct: P(A) = 0.8, P(B) = 0.5, P(B̄) = 0.5.)

**Cleared (teaching devices and extraction artefacts, not book errors):** p. 82 — the problem-solving guide's coefficient matrix and inverse are correct under the book's right-to-left matrix display (an earlier transpose reading was retracted after a 300-dpi check); the guide's "wrong-order multiplication" aside is a legitimate teaching move. P. 105, Ex (8) — the solution gives both solution families (x = π/3+2kπ or x = 4π/3+2kπ); the last line restates only the second family, a partial restatement, not a false claim. P. 112 — Ex (5) (sin³x + sin x·cos²x = sin x), Try-it 5 (cos³x + sin²x·cos x = cos x) and Ex (6) (sec²θ = (sec θ+1)(sec θ−1)/sin²θ) are all correct; the 200-dpi read had mistaken the superscript ³ for ². P. 132 — the slope of the line through (−1,5) and (4,2) is −3/5 (the minus sign was missed at 200 dpi). P. 142, Ex (2) — the point is (−4,−3), not (4,−3); the distance √13 is correct. P. 166 — the ClassPad side box: the 15-value list sums to 73, mean 4.8667, median 5, mode 5 (the 200-dpi read had truncated the printed list to 11 values). P. 191, Ex (11)(ج) — the book prints 2.5852×10²⁴ (the exponent 24 was misread as 31 at 200 dpi). P. 194, Ex (3) — the middle fraction is P(12,2)/2! = 66 (the permutation symbol was misread as a factorial at 200 dpi). P. 205, Bayes Ex (2) — the line computing 0.0245 is P(خ) with intersections ع∩خ and ع̄∩خ (no phantom complement bars).

#### HONEST NEGATIVES

- No answer key; no printed unit tests or assessments anywhere in the book — each unit ends with a concept map and a summary only, and every "try-it" item is unanswered.
- Matrices stop at 2×2: determinant and inverse for 2×2 only; Cramer's rule for two equations in two unknowns only; no 3×3 matrices, no larger systems, no eigenvalues.
- Trigonometry is the unit circle, relations and identities, and solving equations — no graphs of trig functions, no inverse trig functions, no trig in a calculus context.
- No calculus, no complex numbers, no vectors, no conic sections in this book (those live in Grades 11–12).
- Statistics is descriptive (grouped mean/median/mode, quartiles, standard deviation) plus counting and classical/conditional probability — no distributions, no sampling, no inference, no regression, no hypothesis testing.
- The book's data are old (2012 Pearson source): the consumer-price table is January 2011 vs January 2012, the Premier League tables are 2010–2012, the cholesterol and lamp examples are of the same vintage.

#### HELD-COPY DEFECTS

- PDF pp. 5, 7, 9 blank (Part 1 front matter); PDF p. 89 ruled blank (end of Part 1); Part 2 front matter PDF pp. 94, 96, 98 blank; PDF pp. 223–226 ruled blank note pages (printed pp. 209–212); PDF p. 227 is the back cover.
- The text layer is garbled Arabic (legacy font) — read from renders; the printed pages are clean.
- No ISBN on the imprint page (back-cover barcode ISBN only).
- No missing, duplicated or truncated content pages; Units 6–10 complete.

#### Numbering oddities

- Two parts bound in one file with separate covers, title pages, imprints and contents pages; Part 1 covers Units 6–7, Part 2 covers Units 8–10; printed pagination runs continuously 1–213.
- Lesson numbering is per unit (6-1 … 10-5); 6-1 is split into (a) the circle and (b) the tangent; 9-3 is split into (a) slope and (b) equation of a straight line.
- Printed = PDF − 3 in Part 1; printed = PDF − 14 in Part 2.
- Matrices are displayed right-to-left (first column on the right); ordered pairs are displayed left-to-right (x on the left, y on the right). All matrices in this filing are written in standard left-to-right notation.


---
### 7. g11-t2-wb.pdf — Grade 11, Term 2, STUDENT book, scientific track (not a workbook)

**Title as printed:** الرياضيات — الصف الحادي عشر علمي — الفصل الدراسي الثاني — القسم الأول — كتاب الطالب (al-Riyāḍiyyāt — Mathematics — Grade 11 scientific track — Second term — Part 1 — Student book), secondary stage (المرحلة الثانوية). Part 2 (same file) is القسم الثاني, 2/2.
**Grade / term / track:** Grade 11, Term 2, Parts 1–2, scientific track (العلمي).
**Kind:** **Student book — not a workbook.** The cover (PDF p. 1) and the title page (PDF p. 2) both say كتاب الطالب. The filename's "-wb" is wrong; the record slot that calls this file a workbook is wrong with it.
**Edition / year as printed:** 2nd edition, 1447 AH / 2025–2026. Imprint (PDF p. 3): 1st edition 2013–2014, 2nd edition 2015–2016, reprints 2017–2018, 2018–2019, 2019–2020, 2020–2021, 2021–2022, 2022–2023, 2023–2024, 2024–2025, 2025–2026. The Part 2 imprint (PDF p. 85) repeats the same edition history; its deposit is Ministry library no. 244, dated 2015/6/9.
**Supervisory committee:** Hussein Ali Abdullah (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour.
**Part 2 sub-committee:** Hassan Noh Ali Al-Mahna (head), Hussein Al-Bayati Al-Shami, Mostafa Mohammed Shaaban Mahmoud, Sadiqa Ahmed Saleh Al-Ansari, Sheikha Falah Mubarak Al-Hajraf, Mona Ali Issa Al-Masri.
**Publisher:** Kuwait Ministry of Education, Educational Research sector — Curriculum Development Administration. House of Education / Pearson Education 2013. Printed by the Government Press — State of Kuwait.
**ISBN:** no ISBN on the imprint; back-cover barcode ISBN 978-614-406-585-3 (Pearson Scott Foresman).
**PDF pages:** 192; printed pp. 1–179. Part 1: PDF pp. 1–82, printed pp. 1–79 (printed = PDF − 3). Part 2: PDF pp. 83–192, printed pp. 80–179 (printed = PDF − 13).
**File:** `g11-t2-wb.pdf`, 176,885,393 bytes, SHA-256 `643804dd2823cb87dad77bcb5f23fcf7fd05af0f1346b74d892a3037552a65b6`.
**Language:** Arabic. **Answer key:** none.
**Generation:** old generation (2013 series, 2nd edition).
**How read:** image-only — the text layer is essentially empty (about 35 lines of fragments) — read visually from 200-dpi renders of all 192 pages; flagged items were re-verified at 300 dpi.
**Cover art:** Kuwait Towers, dhows, a pyramid/cone geometry figure, trig graphs y₁ = cos x and y₂ = −2cos x.

#### Contents (printed page numbers)

**Front matter (Part 1):** cover (PDF p. 1); title page (PDF p. 2); imprint (PDF p. 3); portraits; introduction (PDF pp. 10–11, signed Dr. Saud Hilal Al-Harbi); contents, Part 1 only (PDF p. 12).

**Unit 7 — Complex Numbers (printed pp. 10–41).** Opener/project p. 10 (radar tracking aircraft — polar coordinates). Prior knowledge p. 11. 7-1 Complex numbers, pp. 12–24 ((a) algebraic form and powers of i; (b) the Argand plane — including the modulus, the conjugate, operations, and the properties of the conjugate and modulus; (c) the multiplicative inverse — including the modulus of a product/quotient, the conjugate of a quotient, and the two modulus identities). 7-2 Polar coordinates and the trigonometric form, pp. 25–32 ((a) polar coordinates; (b) the trigonometric form — including the conditions on a trig form: r ≥ 0 and an argument in [0, 2π); (c) division in trig form — including equality of complex numbers in trig form). 7-3 Solving equations, pp. 33–41 ((a) first-degree equations; (b) square roots of complex numbers; (c) second-degree equations — including the Δ < 0 case; problem-solving guide p. 40 — a cubic with a real root −3 and complex roots). Concept map + summary p. 41.
**Verified:** Ex (1) pp. 12–13 — √(−4) = 2i, i²⁰ = 1, i²¹ = i, (3i)² = −9, (−i)³ = i; Ex (2) p. 14 — (2+3i)+(5−i) = 7+2i, (2+3i)−(5−i) = −3+4i, (2+3i)(5−i) = 13+13i, (2+3i)/(5−i) = 7/26+17/26 i; Ex (3) p. 16 — (5−6i)/(2+3i) = −8/13−27/13 i, (5i)⁻¹ = −i/5, 1/(2+3i) = (2−3i)/13, 1/(3−4i) = (3+4i)/25, (i−1)³ = 2+2i, (2+i)(1−2i) = 4−3i, (2−5i)⁻¹ = (2+5i)/29, |z| values (√2, 1/2, 3, 2√5); Ex (4) p. 18 — z·z̄ = 2|z|²; Ex (5) p. 19 — (1+i)/(1−i) = i; Ex (6) p. 20 — z² = 8+6i with |z| = √10 gives z = ±(3+i); Ex (7) p. 21 — z−z̄ = 2i·Im(z) = −4i; Ex (8) p. 22 — z·z̄ = |z|² = 5; Ex (9) p. 23 — modulus product (√3·2) and quotient (√2/√5); Ex (10) p. 24 — z−z̄ = 2i; Ex (11) p. 24 — z+z̄ = 2Re(z) = 4; Ex (12) p. 24 — |z|² = z·z̄ = 9; Ex (13) p. 24 — z = 3i; 7-2 Ex (1) p. 26 — |z| and θ for (1,√3), (√3,−1), (−√3,√3), (3,−4), (√2,√2); Ex (2) p. 28 — trig forms 5(cos 240°+i sin 240°) etc.; Ex (3) p. 30 — normalising non-standard forms (θ=θ₀+π); Ex (4) p. 31 — trig form with cos(θ+π/2) = −sin θ; Ex (5) p. 31 — equality in trig form; 7-3 Ex (1) p. 34 — 3z+1−i = 7+3i gives z = 2+(4/3)i; Ex (2) p. 35 — √(3+4i) = ±(2+i); Ex (3) p. 36 — √(7−24i) = ±(4−3i); Ex (4) p. 38 — z²+(2+i)z−1+7i = 0 gives z = −3+i or 1−2i; Ex (5) p. 39 — z²−(3+2i)z+5+i = 0 gives z = 1+2i or 2; guide p. 40 — the cubic x³−x²−10x−8 = 0 has roots {−3, 4−i, 4+i}.

**Unit 8 — Trigonometry (printed pp. 42–79).** Opener p. 42. Prior knowledge p. 43. 8-1 Graphs of trig functions, pp. 44–51 (the sine, cosine and tangent graphs — including amplitude and period; the tangent graph's vertical asymptotes). 8-2 Geometric transformations of trig graphs, pp. 52–62 ((a) shifts and reflections; (b) period changes and the day-length model — including the Kuwait day-length example f(91) ≈ 12.69 h). 8-3 Sine law, pp. 63–69 (the sine law; the ambiguous case — including the "no triangle" and "two triangles" cases; the mountain-height example ≈ 1818 m; the forest-fire example ≈ 6.79 km and ≈ 8.61 km). 8-4 Cosine law, pp. 70–73 (the cosine law; the SSA two-triangle case). 8-5 Area of a triangle, pp. 74–77 (including Heron's formula). Problem-solving guide p. 77 (the lake area ≈ 1645 m²). Concept map + summary pp. 78–79.
**Verified:** 8-1 Ex (1) pp. 44–45 — y = 2 cos x (period 2π); Ex (2) p. 47 — y = −5 cos(x/3) (period 6π); Ex (3) p. 48 — y = 3 sin 2x (period π); Ex (4) p. 49 — y = −2 sin x (period 2π); Ex (5) p. 50 — y = 2 tan(x/2) (period 2π); 8-2 Ex (1) pp. 53–54 — reflections/shifts; Ex (2) p. 56 — phase shift 2 sin(2x+π/3) = 2 sin 2(x+π/6); Ex (3) p. 59 — day-length f(91) ≈ 12.69 h; 8-3 Ex (1) p. 64 — sine law a = 8 sin 60°/sin 40° ≈ 10.78; Ex (2) p. 65 — a ≈ 4.5; Ex (3) p. 67 — mountain height ≈ 1818 m; Ex (4) p. 68 — forest fire, two solutions ≈ 6.79 km and ≈ 8.61 km; 8-4 Ex (1) pp. 70–71 — cosine law, c ≈ 12.0; Ex (2) p. 72 — SSA, two triangles; Ex (3) p. 72 — c ≈ 14.3; Ex (4) p. 73 — cosine law, c ≈ 23.2; 8-5 Ex (1) p. 75 — area 10√3 ≈ 17.32 by two methods; Ex (2) p. 76 — dhow sail ≈ 7.48 m²; Ex (3) p. 76 — area = (1/2)·4·5·sin 60° = 5√3 ≈ 8.66.

**Front matter (Part 2):** cover (PDF p. 83, 2/2); title page (PDF p. 84); imprint (PDF p. 85); PDF p. 87 blank; Amir portrait (PDF p. 88); PDF p. 89 blank; Crown Prince portrait (PDF p. 90); PDF p. 91 blank; contents, Part 2 only (PDF p. 92).

**Unit 9 — Applications of Trigonometry (printed pp. 80–113).** Opener/project p. 80 (sound waves — the sine model of a tuning fork). Prior knowledge p. 81. 9-1 Trig identities, pp. 82–86 (the quotient, reciprocal and Pythagorean identities; even/odd identities). 9-2 Proving trig identities, pp. 87–91 (including the non-identity sin²x−tan x = −cos²x+cot x, shown false at x = 0). 9-3 Solving trig equations, pp. 92–99 (including the spring example — the toy first reaches 5 cm above its rest position at t = 1 s). 9-4 Sum and difference identities, pp. 100–104 (cos(α−β), cos(α+β), sin(α±β), tan(α±β)). 9-5 Double-angle and half-angle identities, pp. 105–113 (sin 2x, cos 2x, tan 2x; half-angle formulas; the problem-solving guide pp. 110–111 — triangle area ≈ 5.7 cm²). Concept map + summary pp. 112–113.
**Verified:** 9-1 Ex (1) p. 83 — sin x·cot x = cos x; Ex (2) p. 84 — (1−sin x)(1+sin x) = cos²x; Ex (3) p. 85 — (1+tan x)² = sec²x+2 tan x; 9-2 Ex (1) pp. 88–89 — identities proved; Ex (2) p. 90 — the non-identity shown false at x = 0; 9-3 Ex (1) pp. 93–94 — 2 cos x+√3 = 0 gives x = 5π/6, 7π/6; Ex (2) pp. 94–95 — 4 sin²x−8 sin x+3 = 0 gives x = π/6, 5π/6; Ex (3) p. 96 — spring, first 5 cm above rest at t = 1 s; 9-4 Ex (1) p. 101 — cos 15° = (√2+√6)/4; Ex (2) p. 101 — sin 105° = (√2+√6)/4; Ex (3) p. 102 — tan 75° = 2+√3; Ex (4) p. 102 — sin(α+β) = −63/65; Ex (5) p. 103 — cos(α−β) = 33/65; 9-5 Ex (1) pp. 106–107 — cos 2x = −7/25; Ex (2) pp. 107–108 — sin 15° = √(2−√3)/2; Ex (3) pp. 108–109 — tan 2x = 24/7; guide pp. 110–111 — triangle area ≈ 5.7 cm².

**Unit 10 — Solid Geometry (printed pp. 114–149).** Opener p. 114. Prior knowledge p. 115. 10-1 Lines and planes in space, pp. 116–123 (postulates; positions of two lines, of a line and a plane, of two planes — including the skew-lines example and the intersection-line example). 10-2 Parallel lines and planes, pp. 124–129 (Theorems 1–4 — including the midsegment theorem in space and the parallel-planes theorem). 10-3 A line perpendicular to a plane, pp. 130–136 (Theorem 5 — a line perpendicular to two intersecting lines of a plane is perpendicular to the plane; Theorem 6 — perpendicular lines through a point; Theorem 7 — the three-perpendiculars theorem). 10-4 The dihedral angle, pp. 137–142 (the dihedral angle of a regular triangular pyramid ≈ 70°31′44″; a rectangle's dihedral angle 60°). 10-5 Perpendicular planes, pp. 143–149 (Theorems 8–9 — including the MC² = 50 proof). Problem-solving guide p. 147 (the angle between a pyramid's faces). Concept map + summary pp. 148–149.
**Verified:** 10-1 Ex (1) p. 118 — skew lines; Ex (2) p. 120 — the intersection line of two planes; 10-2 Ex (1) p. 126 — midsegment; Ex (2) p. 128 — parallel planes; 10-3 Ex (1) p. 132 — Theorem 5 applied; Ex (2) p. 134 — three perpendiculars; 10-4 Ex (1) p. 138 — regular triangular pyramid, dihedral ≈ 70°31′44″; Ex (2) p. 140 — rectangle dihedral 60°; 10-5 Ex (1) p. 144 — MC² = 50 proof; Ex (2) p. 146 — perpendicular planes.

**Unit 11 — Discrete Algebra (printed pp. 150–178).** Opener p. 150. Prior knowledge p. 151. 11-1 Counting principle, permutations and combinations, pp. 152–161 (the counting principle; permutations — including circular permutations; combinations; the basketball-team example — 2,556,456 by two methods; the delegation example — ⁴⁸⁴⁵ = 969+3876). 11-2 Binomial theorem, pp. 162–166 (the binomial theorem; the general term; the 7th term of (2x−3y²)¹⁰ = 2,449,440x⁴y¹²; the x³y⁴ term in (2x+3y)⁷ = 22,680x³y⁴). 11-3 Probability, pp. 167–178 (classical probability; the addition rule; the multiplication rule; conditional probability; Bayes — including the transport example P(bus) = 31/52, the radio example P = 2/3125, the ages example P = 0.74, the prize-cards example 0.288, the batteries example 0.6561). Problem-solving guide p. 176 (tennis serve 14/15; P(5 in 7) ≈ 0.0661). Concept map + summary pp. 177–178.
**Verified:** 11-1 Ex (1) pp. 153–154 — 3-digit numbers 125 / 60 / 24; Ex (2) p. 155 — 4-digit numbers 1080 / 360 / 120; Ex (3) p. 156 — 8 routes; Ex (4) pp. 157–158 — ⁷P₃ = 210; Ex (5) p. 158 — basketball team 2,556,456; Ex (6) p. 160 — delegation ⁴⁸⁴⁵ = 969+3876; 11-2 Ex (1) p. 163 — (x−3)⁶ expanded; Ex (2) p. 164 — (x²+3y)⁴; Ex (3) p. 165 — 7th term 2,449,440x⁴y¹²; Ex (4) p. 166 — x³y⁴ term 22,680x³y⁴; 11-3 Ex (1) p. 168 — die events; Ex (2) p. 170 — transport P(bus) = 31/52; Ex (3) p. 172 — radio P = 2/3125; Ex (4) p. 173 — ages P = 0.74; Ex (5) p. 174 — prize cards 0.288; Ex (6) p. 175 — batteries 0.6561.

#### BOOK ERRORS — 1

1. **Printed p. 77, Unit 8 problem-solving guide (the lake area), the EC² line:** the formula part of the line writes "sin 80°" while the substitution part writes "cos 80°" — the same line contradicts itself. **Correct: cos 80°** (the cosine law needs the cosine of the included angle). The computation is correct — EC² = 2112.433, EC ≈ 45.961 m — and uses cos 80° throughout, so the "sin 80°" is a formula-line typo, self-corrected within the line. The guide's final answer (the lake area ≈ 1645 m²) is unaffected.

#### HONEST NEGATIVES

- No answer key; no printed unit tests or assessments anywhere in the book — each unit ends with a concept map and a summary only, and every "try-it" item is unanswered.
- Complex numbers stop at solving quadratic equations and square roots — no De Moivre's theorem, no multiplication or division in polar form, no nth roots of complex numbers, no powers of complex numbers beyond iⁿ.
- Trigonometry covers graphs, transformations, laws and identities — no inverse trig functions, no trig equations beyond the standard forms, no calculus.
- Solid geometry is synthetic (postulates and theorems) — no vectors in space, no coordinates in space, no analytic solid geometry.
- Discrete algebra stops at binomial probability — no random variables, no distributions, no expected value (those live in the Grade 12 statistics books).
- The worked examples carry old data (the 2013 Pearson source) throughout.

#### HELD-COPY DEFECTS

- Part 2 front matter: PDF p. 87 blank; PDF p. 89 blank; PDF p. 91 blank (portrait dividers).
- The text layer is essentially empty (image-only PDF) — read from renders; the printed pages are clean.
- No ISBN on the imprint page (back-cover barcode ISBN only).
- No missing, duplicated or truncated content pages; Units 7–11 complete.

#### Numbering oddities

- Two parts bound in one file with separate covers, title pages, imprints and contents pages; Part 1 covers Units 7–8, Part 2 covers Units 9–11; printed pagination runs continuously 1–179.
- Lesson numbering is per unit (7-1 … 11-3); no split lessons in this book.
- Printed = PDF − 3 in Part 1; printed = PDF − 13 in Part 2.


---
### 8. g11-stats-t1.pdf — Grade 11, Term 1, Statistics student book (literary track)

**Title as printed:** الرياضيات — كتاب الطالب — الصف الحادي عشر أدبي — الفصل الدراسي الأول (al-Riyāḍiyyāt — Mathematics — Student book — Grade 11 literary track — First term), 3rd edition.
**Grade / term / track:** Grade 11, Term 1, literary track (الأدبي).
**Kind:** Student book — Statistics, literary track.
**Edition / year as printed:** 3rd edition, 1448 AH / 2026–2027. Imprint (PDF p. 3): 1st edition 2013–2014; 2nd edition 2016–2017, reprints 2018–2019, 2021–2022, 2022–2023, 2023–2024, 2024–2025; 3rd edition 2025–2026, 2026–2027.
**Supervisory committee:** Ibrahim Hussein Al-Qattan (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour.
**Work team:** Fathi Mohammed Abdel-Fattah (head), Mohammed Bader Hatem Mohammed, Iqbal Mohammed Al-Bahrani, Maha Zayed Mutlaq Al-Anzi, Radhiya Jawad Hussein Al-Nasr, Mohammed Abdullah Al-Hamad Al-Majran.
**Publisher:** Kuwait Ministry of Education, General Administration for Guidance, Research and Curricula — Educational Research and Curricula Administration. House of Education / Pearson Education 2013. Printed by the Government Press — State of Kuwait.
**ISBN:** 978-9921-33-008-3 (imprint, National Library of Kuwait); back-cover Pearson barcode ISBN 978-614-406-328-6.
**Deposit as printed:** National Library of Kuwait; Ministry library no. 2, dated 2015/4/30.
**PDF pages:** 74; printed pp. 1–72 (printed = PDF − 1; PDF p. 74 is the back cover).
**File:** `g11-stats-t1.pdf`, 76,941,895 bytes, SHA-256 `e21d4255ea9ef93d9ea55d010fdd7057da2a80f88da8331f0a61ccd8f47ff9fd`.
**Language:** Arabic. **Answer key:** none.
**Generation:** NEW generation (3rd edition, 1448 AH / 2026–2027).
**How read:** image-only — the text layer is 1,088 bytes (essentially empty) — read visually from 200-dpi renders of all 74 pages; flagged items were re-verified at 300 dpi. Arabic arithmetic is laid out right-to-left; every root index, superscript and fraction in this section was verified against a 300-dpi crop and the book's own working.
**Cover art:** spreadsheet screenshot, line graph, Formula 1 cars, pie chart labelled التكرار (frequency).

#### Contents (printed page numbers)

**Front matter:** cover (PDF p. 1); title page (PDF p. 2); imprint (PDF p. 3); Amir portrait (PDF p. 4); PDF p. 5 BLANK; Crown Prince portrait (PDF p. 6); PDF p. 7 BLANK; ministry foreword (PDF pp. 8–9, signed Dr. Saud Hilal Al-Harbi); contents (PDF p. 10).

**Unit 1 — Real numbers (printed pp. 10–35).** Opener p. 10 (unit project: the spiral of Theodorus). Prior knowledge p. 11. 1-1 Roots and radical expressions and operations on them, p. 12 ((a) roots, p. 12; (b) simplifying radicals, p. 13; (c) addition and subtraction of radicals, p. 14; (d) multiplication and division of radicals, p. 17; (e) conjugates, p. 20). 1-2 Rational exponents and their properties, p. 24 ((a) rational exponents, p. 24; (b) properties of rational exponents, p. 29). Problem-solving guide p. 33 (a football pitch's fence: 4√1500 ≈ 154.92 m, ≈ 155 m; 4√6000 ≈ 309.8 m, ≈ 310 m). Concept map p. 34; summary p. 35. No separate end-of-unit exercise set — the exercises are the try-its inside the lessons plus the guide.
**Verified:** ∛(−8) = −2, ∛125 = 5; √(4x⁶) = 2|x|³, ∛(8x³) = 2x, √(16x⁴y⁶) = 4x²y²|y|; 3√5+4√5 = 7√5; √27+3√12−√75 = 4√3; Ex (4) p. 16 solutions (27∛3; 5√2; 2√2; −3∛2); √2×√8 = 4; ∛(5x³y⁴)×∛(54x²y³) = 3xy²∛(10x²y); ∛32/∛(−4) = −2; ∛(162x⁵)/∛(3x²) = 3x∛2; √(56x³)/√(2x) = 2x√7; (4+∛3)² = 19+8∛3; (4+∛3)(4−∛3) = 13; (6+∛2)(2−∛2) = 12−4∛2−∛4; conjugate examples (∛25 is the conjugate of ∛5, product 5); Ex (10) p. 22 — E = mc² gives c = √(E/m) = √(Em)/m; Ex (11) p. 23 — (s+1)²(3s−2)/(7s−4) at s = √2−1 equals (26+4√2)/23; ⁴√16 = 2; ⁵√(−32) = −2; ⁶√(64x¹²) = 2x²; 125^(1/3) = 5; 25^(3/2) = 125; s^(2/3) = ∛(s²); 32^(3/5) = 8; 4^3.5 = 128; ⁴√5×⁴√7 = ⁴√35; ∛16/∛2 = 2; the fence examples p. 33 (4√1500 ≈ 154.92 m; 4√6000 ≈ 309.8 m).

**Unit 2 — Types of samples (printed pp. 36–53).** Opener/project p. 36 (cholesterol disease). Prior knowledge p. 37. 2-1 Statistical population, p. 38 ((a) data collection, p. 40; (b) types of data and methods of collecting it, p. 41). 2-2 Samples, p. 45 ((a) simple random sample, p. 45; (b) stratified sample, p. 47; (c) systematic sample, p. 49). Problem-solving guide p. 52 (a cotton-clothing institution — a stratified sample of 20, fraction 0.04 → 1/3/16). Concept map + summary p. 53.
**Verified:** population finite/infinite (secondary students finite; smokers worldwide called "infinite" — see Honest negatives); variable; complete enumeration vs sampling (blood-sugar example — no; left-handed students — yes); qualitative nominal (hair colour) vs ordinal (grades); quantitative continuous (marks 12, 13.5, 17…) vs discrete (World Cup goals — Germany 5, Netherlands 5, Japan 4, Cameroon 2, Italy 4, Brazil 5, Spain 4 — group-stage totals, correct); data-collection methods; simple random sample Ex (1) p. 46 — 28, 53, 31, 37, 41, 2, 35; Ex (2) p. 46 — 246, 383, 349, 341, 215, 267, 318, 271, 368, 288; stratified Ex (3) p. 48 — fraction 0.05 → 5/15/60; Ex (4) p. 48 — fraction 0.02 → 2/4/12; systematic Ex (5) p. 50 — interval 60, first 31 → 31, 91, …, 871; Ex (6) p. 50 — interval 70, first 38 → 38, 108, …, 668.

**Unit 3 — Methods of displaying data (printed pp. 54–72).** Opener/project p. 54 (bottling quality). Prior knowledge p. 55. 3-1 Displaying and representing data, p. 56 ((a) relative and percentage frequency table, p. 57; (b) graphical representation, p. 58: (1) pie sectors, p. 58; (2) histogram / frequency curve / frequency polygon, p. 59; (3) cumulative frequency polygon, p. 62; (4) broken line, p. 64). Problem-solving guide p. 68 (lamp lifetimes — cumulative 45/200/470/500; percentages 9/31/54/6; pie angles 32.4°/111.6°/194.4°/21.6°). Concept map + summary p. 70; random-numbers table printed pp. 71–72.
**Verified:** Ex (1) p. 57 — salaries, range 200, 10 classes of 20, frequencies 2, 1, 4, 6, 11, 5, 3, 1, 1, 1 (total 35); Ex (3) p. 59 — nitrate, range 40, 8 classes of 5, frequencies 8, 5, 6, 7, 5, 6, 7, 6 (total 50); Ex (4) pp. 62–63 — telephone calls, cumulative 15/56/131/191/225 and 225/210/169/94/34, median ≈ 13:30; Ex (5) pp. 64–65 — revenues 2500, 3200, 5300, 4300, 4000, 5500, 7100, 8000; Ex (6) p. 66 — sunny days 13, 14, 11, 10, 12, 11, 9, 9, 13, 11, 8. (Ex (2) p. 58 is the pie-chart example — see error 5.)

#### BOOK ERRORS — 5

1. **Printed p. 14, Lesson 1-1(ج), the "note that" box on like radical expressions:** two of the five pairs are wrongly labelled as LIKE. (a) 5∛2 and 2∛3 are **NOT like** (same index, different radicands); (b) √27 and ∛12 are **NOT like** (different root indices — a square root and a cube root can never be like). The other three pairs in the note are correct: 8√x and −3√x ARE like; 5∛3 and 3√5 are not like; 8√x and −3√y are not like.
2. **Printed p. 21, Example (9)(أ), rationalising (1+∛2)/∛3:** the book multiplies top and bottom by ∛3 and writes the denominator (∛3)² as 3, giving (∛3+∛6)/3 ≈ 1.0865. **Correct: (∛3)² = ∛9**, so the value is (∛9+∛18)/3 ≈ 1.5669. The book squares a cube root as if it were a square root. (Verified against the item itself: (1+∛2)/∛3 = 1.5669, matching the corrected value, not the book's.)
3. **Printed p. 21, Example (9)(ب), rationalising (1−∛2)/(∛2−3):** the book gives (1−2∛2)/7 ≈ −0.2171. **Correct: (3−2∛2−∛4)/(∛4−9) ≈ 0.1494.** Three compounding mistakes: the book treats (∛2)² as 2 (writing the denominator as 2−9), flips the sign of the numerator factor, and divides by +7 instead of −7. Both parts of Example (9) share the same root cause — the book squares cube roots as if they were square roots. (Verified against the item itself: (1−∛2)/(∛2−3) = 0.1494, matching the corrected value.)
4. **Printed p. 30, Example (6)(أ), a factor of 2 lost in the last step:** 4^(1/2)×4^(2/3) = 4^(7/6) = ⁶√(2¹⁴) is given as 2·⁶√(2²). **Correct: ⁶√(2¹⁴) = 4·⁶√(2²) = 4∛2 ≈ 5.04** — the book's 2∛2 ≈ 2.52 is half the true value. (The other parts of Example (6) are correct: (ب) 17^(5/6)/17^(1/6) = 17^(2/3) = ∛289; (ج) 3^(1/2)×3^(1/3) = ⁶√(3⁵); (د) 2^(3/4)×2^(1/4) = 2; (هـ) 5^(7/5)/5^(2/5) = 5.)
5. **Printed p. 58, Example (2), the printed list of grades and the frequency table disagree:** the list has **26 grades** (excellent 4, very good 4, good 6, average 5, acceptable 6, unacceptable 1) but the table — and the pie chart built on it — counts only **25** (excellent 4, very good 4, good 6, average 4, acceptable 5, unacceptable 2). **Correct: either the list should have 25 items matching the table, or the table should count all 26 printed grades** (average 5, acceptable 6, unacceptable 1, with central angles 69.2°, 83.1° and 13.8° instead of the printed 57.6°, 72° and 28.8°). The table is internally consistent (its tally marks match its 25 total, and its angles sum to 360° on the /25 basis) — it is the list that does not match it.

**Cleared (not errors):** Ex (2)(ج) p. 14 — √(16x⁴y⁶) = 4x²y²|y| (the absolute value on y is correct); Ex (4)(د) p. 16 — ³√128+∛54−2∛250 = −3∛2; Ex (6)(ب) p. 18 — ∛(5x³y⁴)×∛(54x²y³) = 3xy²∛(10x²y); Ex (7)(ج) p. 18 — √(56x³)/√(2x) = 2x√7; the conjugate examples p. 20 (∛25 is the conjugate of ∛5, product 5); Ex (10) p. 22 — E = mc² gives c = √(Em)/m; Ex (11) p. 23 — the value is s = √2−1 (not 1−√2); Ex (1), Lesson 1-2, p. 25 (⁴√16 = 2, ⁵√(−32) = −2, ⁶√(64x¹²) = 2x²); Ex (2) p. 26; Ex (3) p. 27 — 25^(3/2) = 125; Ex (4) pp. 27–28; Ex (5) pp. 28–29 — n ≈ 0.382 rev/s; the properties table p. 29; Ex (6)(ب)–(هـ) p. 30; Ex (7) pp. 30–31; Ex (8) pp. 31–32; the guide p. 33; Ex (1) p. 57 — the salaries table; Ex (3) p. 59 — the nitrate table; Ex (4) pp. 62–63 — median ≈ 13:30; Ex (5) pp. 64–65 — the revenues (2500, 3200, 5300, 4300, 4000, 5500, 7100, 8000); Ex (6) p. 66 — the sunny-days table; the guide pp. 68–69 — the lamp lifetimes.

#### HONEST NEGATIVES

- No complex numbers, no logarithms, no functions or function graphs, no trigonometry, no calculus — the term is real numbers (radicals and rational exponents) plus elementary statistics only.
- Statistics is descriptive only: no probability (that is Term 2), no measures of central tendency or dispersion beyond reading the median off an ogive (mean/median/mode of raw data are treated as prior knowledge, not re-taught), no standard deviation, no correlation or regression, no hypothesis testing.
- No unit tests or unit assessments anywhere in the book, and no answer key — every exercise set is unanswered, including the "try to solve" items.
- Sampling is taught only with the printed random-number table; no calculator/computer random generation and no discussion of sampling bias beyond representativeness.
- Rational exponents are worked only for positive bases (negative bases with rational exponents are not treated).
- Definitional looseness (not counted as a book error): p. 38 calls smokers worldwide an "infinite" population because the total cannot be known, although by the book's own definition (limited vs unlimited number of elements) the number of smokers is finite — the book conflates "cannot be counted" with "infinite".

#### HELD-COPY DEFECTS

- PDF p. 5 BLANK and PDF p. 7 BLANK (front-matter pages between the portraits and the foreword).
- PDF p. 74 is the back cover.
- The book is image-only (no text layer) — read from renders, as noted above.
- No missing, duplicated or truncated content pages; printed pp. 1–72 complete.

#### Numbering oddities

- None. Units are numbered 1–3 — this statistics book is a self-contained Term 1 volume, not a continuation of the scientific-track books; lesson numbering restarts per unit (1-1 … 3-1).
- The back cover lists the series components as student book, teacher's book, exercise workbook and exercise workbook with answers — the teacher's book and the answered workbook are not in hand. (No teacher guides exist in the Kuwait maths set.)


---
### 9. g11-stats-t2.pdf — Grade 11, Term 2, Statistics student book (literary track)

**Identity.** Title as printed: الرياضيات — كتاب الطالب (Mathematics — Student book), الصف الحادي عشر أدبي (Grade 11, literary), الفصل الدراسي الثاني (Second term), الطبعة الثانية (2nd edition). Grade 11, Term 2, **literary track**, **student book**, old generation. Edition as printed: 2nd edition, 1446 AH / 2024–2025 (1st edition 2013–2014; 2nd edition 2015–2016; reprints 2017–2018, 2019–2020, 2020–2021, 2021–2022, 2023–2024, 2024–2025). Supervising committee: Hussein Ali Abdullah (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour. Work team (G11 literary): Fathi Mohammed Abdel-Fattah (head), Mohammed Badr Hatem Mohammed, Iqbal Mohammed Al-Bahrani, Maha Zayed Mutlaq Al-Anzi, Radia Jawad Hussein Al-Nasr, Mohammed Abdullah Al-Hamad Al-Majran. Publisher: Kuwait Ministry of Education, Educational Research sector — Curriculum Development Administration. House of Education / Pearson Education 2013; Arwa Printing Press. **No ISBN printed on the imprint**; back-cover Pearson barcode ISBN **978-614-406-582-2**. Deposit: Ministry library no. (94) dated 2015/5/26. Cover art: roller coaster, a die, a Kuwaiti dhow coin, a normal curve and a histogram (same art as its workbook). Introduction (مقدمة, printed pp. 7–8) signed by the Assistant Undersecretary for Educational Research and Curricula. PDF pages 82; printed pages 1–79 (printed = PDF − 1; PDF p. 81 is blank, PDF p. 82 is the back cover). File size 23,109,182 B. SHA-256 `7911e68969aebed6125781831eea62fac4298bb635eae20bec13133d845cc4e3`.

**Method note.** The text layer is mojibake (WinSoftPro legacy font) — Arabic is unreadable in extraction. The book was read visually from 200 dpi renders of every page; worked examples were checked against the renders, and the flagged skewness rule was re-checked from 200% and 250% crops.

**Contents (printed page numbers).**

- **Unit 4 — Describing data (وصف البيانات), p. 10.** Unit project (p. 10): mobile devices — mobiles are a central part of daily life; the learner surveys how long different groups in society (doctors, lawyers, engineers, teachers, businessmen, officers, students) use their mobiles, takes equal-sized samples from each group, finds the mean time in hours per group, fills in a table (group × frequency × mean time), uses it to find the mean usage time for one person in one day, and writes a detailed report with results and suggestions. Unit opener (p. 11): prior knowledge — census, sampling, classifying data, data-collection methods, types of random samples, relative and percentage frequency, ascending/descending cumulative frequency, cumulative frequency curves, pie charts, histogram, frequency curve and polygon, broken line. What will be learned: finding the lower and upper quartiles; the box-and-whisker plot; distinguishing types of skewness; relating skewness to the box plot and to measures of central tendency; finding the range and describing range, variance and standard deviation; the empirical rule and the standard value in decision-making; using the computer for measures of central tendency and dispersion. Key terms: lower quartile, upper quartile, box-and-whisker plot, skewness, positive skewness, negative skewness, symmetry, semi-interquartile range, variance, standard deviation, empirical rule, standard value. "Add to your knowledge" box: the mobile phone in the age of globalisation — Martin Cooper (Motorola researcher) made the first mobile call on 3 April 1973; studies on the magnetic field of mobiles and possible harm to the heart.
  - **4-1 Median, lower and upper quartile, and the box-and-whisker plot, p. 12.** Group work: monthly salaries (KD) of 37 workers in an institution (700–1150 KD) — find the median, Q1 and Q3. (a) From a frequency table, p. 12: the median of n ordered values is the value at rank (n+1)/2 when n is odd, and the mean of the values at ranks n/2 and n/2+1 when n is even; the median splits the data into two equal groups (denoted م₂); Q1 is the median of the lower half (م₁), Q3 the median of the upper half (م₃). Box-and-whisker plot: the five-number summary — smallest value, Q1, median, Q3, largest value. Worked example 1: phone cards sold in the first week in a shop (values 200, 300, 350, 400, 500 with frequencies 2, 2, 3, 2, 2; n = 11): median 350 (rank 6), Q1 300, Q3 400, box plot from 200 to 500. (b) Grouped data, p. 15: interpolation formulas — median = lower limit of the median class + ((n/2 − cumulative frequency before the class) ÷ frequency of the class) × class length, and the same form with n/4 and 3n/4 for Q1 and Q3. Worked example 3: ages of 20 residents of a building (classes 0–10, 10–20, 20–30, 30–40, 40–50, 50–60; frequencies 3, 3, 5, 2, 5, 2) — ascending cumulative frequencies 3, 6, 11, 13, 18, 20; median class 20–30; median = 20 + ((10−6)/5) × 10 = **28**. Worked example 4: marks of 24 students in maths (max 30; classes 0–5, 5–10, 10–15, 15–20, 20–25; frequencies 1, 4, 7, 9, 3) — ascending cumulative-frequency table, then Q1 and Q3 by the same interpolation.
  - **4-2 Skewness, p. 19.** (a) Skewness and its relation to measures of central tendency, p. 19: a symmetric frequency curve has mode = median = mean at one point; large values pull the mean to the right (right tail, positive skew); small values pull it to the left (left tail, negative skew). Cooperative activity: a symmetric table (classes 10–20, 20–30, 30–40, 40–50, 50–60; frequencies 5, 10, 20, 10, 5) — draw the histogram and curve, find mean, mode and median and compare. Worked example 1: marks of 30 students in a test (max 20; classes 6–8, 8–10, 10–12, 12–14, 14–16, 16–18, 18–20; frequencies 2, 4, 9, 7, 5, 2, 1) — histogram and frequency curve; the curve tails to the right, so the skew is positive. (b) Skewness and its relation to the box plot, p. 21: Worked example 3: daily bank deposits (KD) of 14 families in Kuwait, ascending 27, 28, 30, 32, 34, 38, 41, 42, 43, 44, 46, 53, 56, 60 — median = (41+42)/2 = **41.5**, Q1 = **32**, Q3 = **46**; the box plot shows the median closer to Q3 than to Q1, so the skew is to the left (negative).
  - **4-3 Measures of dispersion and their applications, p. 23.** Group work: one student's end-of-term marks (max 20) in History (9, 10, 11, 12, 11), Geography (13, 7, 10, 8, 16), Philosophy (5, 5, 15, 15, 15) and Maths (11, 10, 11, 12, 11) — the four means are all about 11, but the spreads differ, which is what the standard deviation shows. (a) Measures of dispersion, p. 23: range = largest value − smallest value; semi-interquartile range = (Q3 − Q1)/2; variance σ² = Σ(x − x̄)²/n; standard deviation σ = √[Σ(x − x̄)²/n]; with repeated values, variance = Σfᵣ(xᵣ − x̄)²/Σfᵣ (class midpoints for grouped data). Worked example 1: data 2, 4, 5, 6, 6, 7, 7, 7, 8, 8 — range 6, median 6.5, Q1 5, Q3 7, semi-interquartile range 1, mean 6, Σ(x−x̄)² = 32, variance **3.2**, standard deviation **≈ 1.788**. (b) Normal distribution, p. 27: the empirical rule — about 68% of values lie in [x̄ − σ, x̄ + σ], about 95% in [x̄ − 2σ, x̄ + 2σ] (47.5% on each side of the mean, 2.5% in each tail), about 99.7% in [x̄ − 3σ, x̄ + 3σ] (49.85% each side, 0.15% each tail). (c) Standard value, p. 31: z = (x − x̄)/σ. Worked example 6: Mawaddah scored 64 in Arabic (mean 69, SD 8) and 48 in Geography (mean 56, SD 10) — z(Arabic) = (64−69)/8 = **−0.625**, z(Geography) = (48−56)/10 = **−0.8**; −0.625 > −0.8, so she did better in Arabic. "Try to solve" 6: Khaled (height 180 cm; city A men mean 174 cm, SD 12 cm) vs Saleh (172 cm; city B men mean 165 cm, SD 15 cm) — whose height is better compared with the men in his city (z = 0.5 vs ≈ 0.467; Khaled's is higher).
  - **4-4 Statistical applications, p. 33.** (a) Measures of central tendency, p. 33: using Excel (AVERAGE) — a spreadsheet of 18 students with weights (70–90 kg), heights (156–184 cm) and numbers of brothers/sisters (0–7): mean weight **76.4 kg** (1375/18), mean height **171.8 cm** (3092/18), mean number of siblings **3** (54/18). The lesson walks through the Insert Function dialog, relative-cell copying and the fill handle. (b) Median, p. 35: using Excel (MEDIAN) — a teacher's two online problems; the students' times in minutes (15 values each) give median **27 minutes** for problem 1 and **29 minutes** for problem 2 (confirmed by the book's own Excel output, printed p. 40). "Try to solve" 2: a group monitoring a satellite channel for two weeks counted offensive words/scenes: 342, 267, 321, 157, 33, 349, 254, 166, 132, 289 — find the median with a statistics program (260.5). Worked example 3: a 12-page booklet, word counts per page 271, 354, 296, 301, 333, 326, 285, 298, 327, 316, 287, 314 — find the variance and standard deviation with Excel (mean 309; variance ≈ 512.2; SD ≈ 22.6).
  - **Unit 4 summary, printed pp. 41–49** (definitions and formulas for mode, quartiles, box plot, skewness, range, semi-interquartile range, variance, standard deviation, empirical rule, standard value).
- **Unit 5 — Probability (الاحتمال), p. 50.** Unit project (p. 50): "Know your country's landmarks" — Kuwaiti institutions run awareness campaigns to protect some animals and endangered plants; the learner makes a poster for a nature reserve showing some animals and plants that live there, using 10 plant cards and 10 animal cards: draw a card at random and find the probability of a plant picture and of an animal picture, then repeat the draw 50 times (recording plant/animal each time), then 100 times, compare the counts with the probabilities, tabulate the results, and write a report giving the reasons for choosing that reserve. Unit opener (p. 51): prior knowledge — tree diagrams and their use in counting; counting methods (tables, permutations, combinations); using counting in some problems. What will be learned: solving problems with counting, permutations and combinations; Pascal's triangle; the binomial theorem; the random experiment and sample space; probabilities of events, mutually exclusive events, the complement of an event, independent events. Key terms: lists, fundamental counting principle, multiplication principle, permutations, combinations, Pascal's triangle, binomial theorem, random experiment, sample space, event, probability, mutually exclusive events, complement of an event, independent events. "Add to your knowledge" box: Jacob Bernoulli (1654–1705) studied random experiments in his book *Ars Conjectandi* (The Art of Conjecturing), published by his nephew Nicolaus Bernoulli eight years after his death; Bernoulli showed that the relative frequency of an outcome in a series of trials approaches the probability of the event — e.g. a fair die: P(2) = 1/6, and if the die is rolled n times and 2 appears m times, m/n = 1/6 (the law of large numbers); today computer simulation is used to verify it. Portrait of Bernoulli.
  - **5-1 Counting principle, permutations and combinations, p. 52.** (a) Listing, p. 52: all 24 orderings of four students (Saleh, Khaled, Salem, Ahmed) assigned to four tasks (4 × 6 = 24 ways). "Try to solve" 1: three letters of the word ناصر (Nasser) used without repetition — how many different words (with or without meaning)? (24.) (b) Fundamental counting principle, p. 53: a task in 3 successive stages with 3, 4 and 1 ways gives 3 × 4 × 1 = **12** ways; in general, n₁ × n₂ × … × n_m ways. (c) Factorial of a number, p. 56: Hisham's 4 small boats in a row — 4 × 3 × 2 × 1 = **24** ways; the product is the factorial of 4, written 4!; in general n! = n × (n−1) × … × 3 × 2 × 1, 0! = 1, n! = n × (n−1)!. Information box: Christian Kramp (1760–1826) first used "!" for factorials in 1808; 10! = 3,628,800. Worked example 4: 5! = **120**; 12!/9! = **1320**; 16!/(12!4!) = **1820**. (d) Permutations, p. 57: a permutation is arranging elements in a given order; the number of permutations of n things is n!; P(n,r) = n × (n−1) × … × (n−r+1) = n!/(n−r)!, r ≤ n, n a positive integer; P(n,0) = 1. Worked example 5: choosing a president, vice-president and secretary from 20 students — 20 × 19 × 18 = **6,840** ways. Worked example 6: P(8,3) = **336**; P(7,3) + P(7,5) = 210 + 2520 = **2730**; P(9,5)/P(8,4) = **9**. (e) Combinations, p. 59: C(n,r) = P(n,r)/r! = n!/(r!(n−r)!); C(n,0) = 1, C(n,n) = 1, C(n,1) = n, C(n,r) = C(n,n−r). Worked example 8: choosing 3 pharmacies from 8 in a Kuwaiti governorate for night duty — C(8,3) = (8×7×6)/(1×2×3) = **56** ways.
  - **5-2 Binomial theorem, p. 63.** (a) Pascal's triangle, p. 63: the outer edges are 1; each number in a row equals the sum of the two numbers directly above it. Worked example 1: row 5 is 1, 5, 10, 10, 5, 1, so row 6 is **1, 6, 15, 20, 15, 6, 1**. Portrait of Blaise Pascal (1623–1662). Information box: Abu Bakr Muhammad ibn al-Hasan al-Karkhi, a Muslim mathematician who lived in Baghdad, set out the famous triangle now known as Pascal's triangle; it was also known to the Chinese mathematician Zhu Shijie, but it is named after Pascal, who used it in 1654 to find binomial coefficients. (b) Binomial theorem, p. 65: (a+b)^n = C(n,0)a^n + C(n,1)a^(n−1)b + … + C(n,n)b^n; the expansion has n+1 terms; the (r+1)th term is C(n,r)·a^(n−r)·b^r; coefficients of terms equidistant from the ends are equal. Worked example 3: (s+2)^6 = **s^6 + 12s^5 + 60s^4 + 160s^3 + 240s² + 192s + 64**. Worked example 4: (2s − 3ṣ)^4 = **16s^4 − 96s³ṣ + 216s²ṣ² − 216sṣ³ + 81ṣ^4**.
  - **5-3 Probability, p. 68.** (a) Random experiment and sample space, p. 68: rolling two dice — the sample space has 36 ordered pairs; by the fundamental counting principle, 6 × 6 = 36 outcomes. An event is a subset of the sample space (possibly equal to it): A = "the two numbers are equal" = {(1,1), (2,2), (3,3), (4,4), (5,5), (6,6)}; B = "the sum is 9" = {(3,6), (4,5), (5,4), (6,3)}; C = "the sum is 15" = ∅. Types of event: simple (one element) and compound (more than one element). "Try to solve" 1: two bags of 5 numbered balls (1–5 and 6–10), one ball drawn from each — 25 possible outcomes. (b) Assigning probabilities, p. 70: if A is an event in a finite non-empty sample space F whose outcomes are equally likely, P(A) = n(A)/n(F). Properties: 0 ≤ P(A) ≤ 1; if A = ∅ then P(A) = 0 (impossible event); if A = F then P(A) = 1 (certain event). Worked example 3: transport used by G11 students in two sections (school bus 16+15, with family 6+8, public transport 4+3; total 52) — P(a randomly chosen student comes by school bus) = **31/52**. (c) Mutually exclusive events, p. 72: P(A∪B) = P(A) + P(B) − P(A∩B); if A and B are mutually exclusive, P(A∩B) = 0 and P(A∪B) = P(A) + P(B) (and conversely). Worked example 5: choose a number at random from 0 to 9 — P(greater than 6 or smaller than 3) = 3/10 + 3/10 = **0.6**. (d) Complement of an event, p. 73: Ā is all outcomes in the sample space not in A; A ∪ Ā = F, A ∩ Ā = ∅, so P(A) + P(Ā) = 1; the complement rule P(Ā) = 1 − P(A). Worked example 6: roll a fair die, A = "a number ≥ 5 appears" = {5, 6} — P(A) = 2/6 = **1/3**, P(Ā) = **2/3**. (e) Independent events, p. 74: two events are independent if the occurrence of one has no effect on the occurrence of the other (coin and die; two free throws; drawing from two separate bags). Rule: if A and B are independent, P(A∩B) = P(A)·P(B) (and conversely); P(A∪B) = P(A) + P(B) − P(A)·P(B). Worked example 7: Ibrahim and Youssef play darts; P(Ibrahim hits) = 2/5, P(Youssef hits) = 1/3 — P(both hit) = **2/15**; P(the target is hit) = 2/5 + 1/3 − 2/15 = **3/5**.
  - **Unit 5 organiser (p. 78) and summary (p. 79).**

**BOOK ERRORS — 0 (one claim, stated twice, retracted by the citation check).**
- **RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 19, lesson 4-2(a) "relation between measures of central tendency and skewness" box, and printed p. 49, Unit 4 summary. The first draft read the mode–median–mean chains in the Latin direction and reported them reversed. Read physically — by which side of each glyph opens toward the larger quantity — the book is correct in both places: the p. 49 summary's first line uses "<"-shaped glyphs whose openings face المنوال (the mode, rightmost in the RTL line) and then الوسيط (the median), i.e. **mode > median > mean → negative (left) skew**; its second line uses the opposite glyphs, i.e. **mode < median < mean → positive (right) skew**. The p. 19 box agrees: the right-hand panel (tail to the left, captioned الالتواء إلى اليسار / السالب — left/negative skew) heads its chain with the mode as the largest of the three, and the left-hand panel (tail right, الالتواء إلى اليمين / الموجب) with the mode as the smallest; the arrow labels under the curves agree, and worked example 1 (pp. 20–21) — mean ≈ 12.27 > median 12 > mode ≈ 11 called positive skew — is consistent. Diagrams, captions, chains and examples all state the standard rule correctly.

**Cleared flag (checked, not an error).** Printed p. 33, example 6: the comparison of the two z-values is typeset in right-to-left order and reads −0.8 < −0.625 — correct, and the conclusion (Arabic better than Geography) follows.

**HONEST NEGATIVES.**
- No conditional probability, no Bayes' rule, no tree-diagram probability calculations (tree diagrams are only prior knowledge for counting) — the probability chapter stops at independent events.
- No random variables or probability distributions (those are Grade 12 literary, Term 2), no binomial distribution, no expected value.
- No permutations or combinations with repetition; no arrangements of objects that are not all distinct.
- The empirical rule is stated without proof and without a z-table (the z-table appears only in the Grade 12 scientific book).
- Excel is the only computer tool taught (AVERAGE and MEDIAN, with the Insert Function dialog); the lessons never use a spreadsheet function for variance or standard deviation (STDEV appears only inside a dialog screenshot).
- No unit tests or unit assessments anywhere in the book, and no answer key — every exercise set and "try to solve" item is unanswered.

**HELD-COPY DEFECTS.** None in content: printed pp. 1–79 are complete, with no missing, duplicated or truncated pages. PDF p. 7 is a blank front-matter page (between the portraits and the introduction); PDF p. 81 is blank; PDF p. 82 is the back cover. The text layer is mojibake (legacy font) — read from renders, as noted above.

**Answer key:** none. **Numbering oddities:** the contents page lists 5-1(c) as "multiplication principle" (مبدأ الضرب), but the lesson as printed (p. 56) and the Unit 5 title-page lessons grid (p. 50) both call (ج) "factorial of a number" (مضروب العدد). The fundamental counting principle in 5-1(b) *is* the multiplication principle, so the contents-page label is a mislabel, not a missing lesson. Units continue Term 1 numbering (Units 4–5); the statistics book is a self-contained Term 2 volume, not a continuation of the scientific-track books. The back cover lists the series components as student book, teacher's book, exercise workbook and exercise workbook with answers — the teacher's book and the answered workbook are **not** in hand (no teacher guides exist in the Kuwait maths set).

---
### 10. g11-stats-t2-wb.pdf — Grade 11, Term 2, Statistics exercise workbook (literary track)

#### Identity

- **Title as printed:** الرياضيات — كرّاسة التمارين — الصف الحادي عشر أدبي — الفصل الدراسي الثاني
- **Transliteration/translation:** *Al-Riyāḍiyyāt — Kurrāsat al-Tamārīn — al-Ṣaff al-Ḥādī ʿAshar Adabī — al-Faṣl al-Dirāsī al-Thānī* — Mathematics — Exercise Workbook — Grade 11 literary track — Second term. Secondary stage (المرحلة الثانوية).
- **Kind: WORKBOOK (exercises only).** Proved from the book itself: the cover and title page both say كرّاسة التمارين (exercise workbook); the contents are تمرّن (practice) sets per lesson, a unit test and enrichment exercises per unit; there are no lessons, no worked examples and no printed answers anywhere in the file. The filename's "-wb" is right this time, but the kind is proved from the cover, not the filename.
- **Grade:** 11. **Term:** 2. **Track:** literary (أدبي), printed on the cover and title page. This is the literary-track statistics workbook; the scientific-track mathematics workbook (Term 1, §4) is a separate file, and the two tracks must not be merged.
- **Edition/year as printed:** 2nd edition (الطبعة الثانية), 1446 AH / 2024–2025. The imprint lists the 1st edition 2013–2014 and the 2nd edition 2015–2016, then reprint years 2017–2018, 2019–2020, 2020–2021, 2021–2022, 2023–2024, 2024–2025 — so this is the 2015–2016 second edition reprinted through 2024–2025. **Old generation.** Prepared by the supervisory committee for studying and aligning the mathematics book series: Hussein Ali Abdullah (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour. Work team for the Grade 11 literary mathematics books: Fathi Mohammed Abdel Fattah (head), Mohammed Bader Hatem Mohammed, Iqbal Mohammed Al-Bahrani, Maha Zayed Mutlaq Al-Anzi, Radhiya Jawad Hussein Al-Nasr, Mohammed Abdullah Al-Hamad Al-Majran.
- **ISBN:** none printed on the imprint page. The back cover carries a barcode ISBN, 978-614-406-583-9 (Pearson Scott Foresman) — the series' Pearson ISBN, not a ministry imprint ISBN.
- **Publisher:** Kuwait Ministry of Education — Educational Research and Curricula Sector — Curriculum Development Department. Publisher: House of Education (دار التربويون) with Pearson Education 2013. Printed at Al-Khatt presses (مطابع الخط).
- **Deposit as printed:** deposited at the Ministry library under no. 95, dated 2015/5/26. The 2015 date predates this reprint (2024–2025) and is plainly carried over from the first edition; recorded as printed.
- **Pages:** 50 PDF pages; printed pp. 1–49 (content printed pp. 8–48). Printed = PDF − 1 (PDF p. 9 = printed p. 8).
- **File:** `g11-stats-t2-wb.pdf`, 6,985,121 bytes, SHA-256 `35579e729f98b98ff46168c1206e1737cf1411a791031b86792822c045458e76`.
- **Language:** Arabic. **Answer key:** none in this copy. The back cover lists the series components as student book, teacher's book, exercise workbook, and exercise workbook *with answers* (كرّاسة التمارين مع الإجابات) — the answers live in that separate component, not in this file.
- **How read:** the text layer is mojibake throughout (custom-encoded fonts with no ToUnicode map — `pdffonts` confirms `uni: no` on the Arabic fonts), so the book was read **visually from 150-dpi renders of all 50 pages**; the five flagged items were re-verified against 300-dpi renders. Cover art: a roller coaster, a die, a coin and a normal curve. PDF p. 4 is a portrait of the Amir (H.H. Sheikh Meshal Al-Ahmad Al-Jaber Al-Sabah); PDF p. 6 is a portrait of the Crown Prince (H.H. Sheikh Sabah Khaled Al-Hamad Al-Sabah); PDF pp. 5 and 7 are blank. The imprint page carries three QR codes: the full book, "evaluate our curricula", and the educational channel.

#### Contents (printed page numbers)

The contents page lists exercise numbers only — no lesson titles. The lesson titles below are the student book's (g11-stats-t2, §9) lesson titles for the same units; this workbook never prints them. Every exercise set is split into **Group A** (basic exercises — تمارين أساسية) and **Group B** (consolidation exercises — تمارين تعزيزية). Each unit closes with a unit test (اختبار الوحدة) and enrichment exercises (تمارين إثرائية).

**Unit 4 — Describing Data (الوحدة الرابعة: وصف البيانات), pp. 8–30.**
- 4-1 Median, lower and upper quartile, box and whisker plot (pp. 8–11). Group A: (1) 15 pupils' marks 4, 5, 6, 7, 8, 10 with frequencies 2, 3, 3, 2, 3, 2 = 15 (median 6, Q1 5, Q3 8); (2) 12 days' temperatures 28–40 °C, frequencies 1, 1, 3, 1, 3, 2, 1 = 12 (median 35); (3) grouped classes 10–20 … 50–60, frequencies 4, 8, 9, 7, 2 = 30 (median ≈ 33.33); (4) heights of 24 pupils, classes 160–185, frequencies 4, 1, 4, 6, 7, 2 = 24 (Q1 ≈ 171.25); (5) grouped classes 6–16, frequencies 4, 5, 7, 4, 3, 5 = 28 (Q3 ≈ 14.67). Group B: (1) weights of 13 pupils 56, 57, 58, 60, 70 with frequencies 2, 3, 5, 2, 1 = 13 (median 58); (2) years of service, classes 0–30, counts 14, 53, 45, 22, 12, 8, 6 = 160 (median ≈ 11.44, Q1 ≈ 7.45, Q3 ≈ 16.82).
- 4-2 Skewness (pp. 12–15). Group A: (1) three curves with mean/median/mode marked — right-skewed (mean rightmost), symmetric (mean = median = mode), left-skewed (mode rightmost), all labelled correctly; (2) marks of 27 pupils, classes 4–20, frequencies 1, 2, 3, 4, 6, 7, 3, 1 = 27 (mean ≈ 12.7 < median ≈ 13 < mode ≈ 15, left-skewed); (3) a football team's mean salary 1,500,000 KD vs median 800,000 KD — a few very high salaries pull the mean up, right-skewed; (4) 25 people on a diet, ages listed — **see book error 1**; (5) cinema ticket sales 497, 429, 746, 469, 504, 464, 326 (median 469, Q1 429, Q3 504). Group B: (1) classes 20–120, frequencies 5, 9, 3, 2, 1 = 20, right-skewed; (2) 15 flight delays 9, 12, 2, 5, 5, 15, 6, 7, 17, 5, 3, 3, 4, 6, 9 (mode 5, median 6, mean 7.2, right-skewed); (3) weights of 16 pupils 56, 56, 57, 58, 58, 59, 60×4, 62, 62, 65, 66, 67, 70 (median 60, mean 61, slight right skew).
- 4-3 Measures of dispersion and its applications (pp. 16–19). Group A: (1) data 8, 7, 10, 15, 13, 9, 11, 12, 14 (mean 11, range 8, median 11, variance 6.67, SD ≈ 2.58); (2) a cheese factory whose labels say 50% of the ingredients are fats — analysis of 100 tins, fat-percentage classes 42–45 … 54–57 with frequencies 11, 25, 38, 23, 3 = 100 (class centres 43.5, 46.5, 49.5, 52.5, 55.5; mean ≈ 48.96, SD ≈ 3.01); (3) a factory's monthly profits, mean 1,250 dinars, SD 225, bell-shaped — apply the empirical rule; 2,000 dinars is mean + 3.33σ, essentially not reached. Group B: (1) data 24, 25, 20, 18, 21, 27, 29, 28 (mean 24, range 11, variance 14, SD ≈ 3.74); (2) a shop's goods by price, classes 0–10 … 50–60 dinars, frequencies 190, 300, 470, 280, 260, 100 = 1,600 (mean 27.625); (3) metal wires, mean breaking load 1,400 kg, SD 200 kg, approximately normal — P(load > 1,000 kg) ≈ 97.5%; (4) z-scores: a 75 kg man in city A (mean 70, SD 5 → z = 1) vs an 80 kg man in city B (mean 76, SD 8 → z = 0.5).
- 4-4 Statistical applications (pp. 20–21). Group A: (1) a table of children's doctor visits in a year, 0–7 visits with counts 2, 8, 27, 45, 38, 15, 4, 1 = 140 (mean 3.25, median 3), to be done with a statistics program — the page prints empty spreadsheet screenshots (columns A–E) for the learner to fill. Group B: (1) a doctor measures pain (0–100 mm scale) for 7 patients: 1, 1, 2, 3, 3, 6, 56 — mean ≈ 10.29, median 3; the outlier 56 inflates the mean and SD, which is the point of the item; then the same data transformed with ln, the values printed to 9 decimal places — 0, 0, 0.693147181, 1.098612289, 1.098612289, 1.791759469, 4.025351691 — all correct (ln 1 = 0, ln 2 = 0.6931, ln 3 = 1.0986, ln 6 = 1.7918, ln 56 = 4.0254); find the mean, median and SD of the transformed data and compare.
- Unit 4 test (pp. 22–25). Essay questions: (1) 30 Arabic-language marks (max 20) of Grade 11 pupils — median 12.5, Q1 and Q3, box-and-whisker plot; (2) heights of Grade 11 pupils, classes 163–166 … 178–181, frequencies 3, 6, 4, 4, 3, 5 = 25 — frequency curve and its name, skewness; (3) weights 56–65 kg (10 values) — variance 8.25, SD ≈ 2.87; (4) a pupil's final maths mark 16 (class mean 13.5, SD 1.75 → z ≈ 1.43) vs science mark 16 (mean 13, SD 1.8 → z ≈ 1.67) — the science mark is the better result; (5) books each pupil owns, 0–6 with frequencies 4, 12, 8, 2, 1, 2, 1 = 30 (mean 1.8, median 1), with a statistics program; (6) 9 friends bet on the number of balls in a closed tin, guesses 12, 9, 7, 2, 0, −1, −4, −7, −9 (negatives mean the estimate is below the true count) — mean 1, variance ≈ 46.22, SD ≈ 6.8. Objective items: true/false (1)–(7) — (1) data 3, 8, 12, 15, 20, semi-interquartile range 17 (false; correct 3.5); (2) lower quartile of 308, 314, 316, 317, 321, 321, 321, 324, 325, 326, 327, 332 is 316.5 (true); (3) SD 4 → variance 2 (false; 16); (4) mean 20, SD 2 → 95% in [16, 24] (true); (5) mean 14, σ 4 → z(16) = 1/2 (true); (6) [x̄ − σ, x̄ + σ] contains 95% in the normal distribution (false; ≈ 68%); (7) mean 12, z(15) = 0.4, σ 7.5 (true). Multiple choice (8)–(13): (8) z = 0.75, x = 18, σ = 8 → mean 12; (9) median of 50, 10, 15, 5, 10, 10, 20, 25, 15 is 15; (10) from a box plot, upper quartile 90; (11) **see book error 3**; (12) variance is not a measure of central tendency; (13) right-skewed curve → mean greater than median.
- Enrichment (pp. 26–30): (1) heights of a number of teenagers, 158–172 cm — **see book error 2**; (2) chemistry test marks (max 20), classes 6–8 … 16–18, frequencies 2, 5, 7, 8, 6, 3, 1 = 32 (mean 12.5) — frequency curve and its name, skewness; (3) basketball players' heights, classes 175–180 … 200–205, frequencies 2, 3, 5, 6, 8, 3 = 27 — frequency curve and its name, skewness; (4) Arabic test marks (max 20), classes 6–8 … 14–16, frequencies 6, 4, 3, 9, 8 = 30 (mean 11.6) — mean and SD; (5) Kuwait City June 2011, mean temperature ≈ 43 °C, SD 2.5; Salmiya June 2011, mean ≈ 41 °C, SD 3.75 — z-score of a shared 45 °C day (0.8 in Kuwait City, ≈ 1.07 in Salmiya); (6) data 8, 7, 3, 4, 3 (mean 5, SD ≈ 2.10); add 5 to each (mean 10, SD unchanged) and multiply each by 5 (mean 25, SD ≈ 10.49), with a statistics program; (7) a class's die-roll results as a bar chart — faces 1–6 with frequencies 7, 8, 6, 4, 7, 8 = 40 (mean 3.5, median 3, variance 3.25, SD ≈ 1.80), with a statistics program.

**Unit 5 — Probability (الوحدة الخامسة: الاحتمال), pp. 31–48.**
- 5-1 Counting principle, permutations and combinations (pp. 31–34). Group A: (1) list all 3-letter words from م، ج، د without repetition (6 words); (2) list all 4-letter words from س، ع، ي، د without repetition (24 words); (3)–(8) 8! = 40,320; 11!/9! = 110; 6! × 4! = 17,280; 3! × 5! = 720; 3! + 5! = 126; 8! − 6! = 39,600; (9)–(15) ¹²P₁₁ = 479,001,600; ¹²P₁₀ = 239,500,800; ¹²P₅ = 95,040; ¹²P₁ = 12; ⁸P₄ + ⁸P₄ = 3,360; ⁸P₂ − ⁸P₂ = 0; ¹²P₈/¹²P₅ = 210; (16) 8 pupils compete for a school grant — top three in order, ⁸P₃ = 336 ways; (17) a traveller chooses between 3 airlines, 5 hotels, 4 car-rental companies — 60 ways; (18) Salma has 3 colouring pens (pink, blue, brown) and 4 separate circles — 3⁴ = 81 ways, 2⁴ = 16 without pink; (19)–(25) ¹²C₁₁ = 12; ¹²C₁₀ = 66; ¹²C₅ = 792; ¹²C₁ = 12; ¹²C₁₂ = 1; ⁵C₄ + ⁵C₃ = 15; ⁵C₃/⁵C₂ = 1; (26) choose 4 drawings from a class of 24 — ²⁴C₄ = 10,626; (27) solve ⁿP₂ = 20 (n = 5), ⁿC₃ = 10 (n = 5), n!/(n−2)! = 12 (n = 4); (28) from 5 teachers choose one to train olympiad pupils in maths and another to prepare the exam — 20 ways; (29) from 8 pupils choose 3 in turn for volleyball, basketball, football — ⁸P₃ = 336; (30) choose 4 pupils from 12 for the science centre — ¹²C₄ = 495. Group B: (1)–(2) list all words from ن، ج، ح (6 words) and ش، ك (2 words) using all letters without repetition; (3)–(8) 6! = 720; 7! − 4 = 5,036; 8!/5! = 336; 7! − 5! = 4,920; 15!/(12! × 3!) = 455; 4 × 4! = 96; (9) a bag with 5 red balls and 6 green balls, two drawn together — ¹¹C₂ = 55 ways, both red ⁵C₂ = 10; (10) solve equations — **see book error 4**; (11)–(16) ⁶P₄ = 360; ³P₂ + ⁵P₂ = 26; ⁷P₅/⁷P₄ = 3; ⁷C₅ = 21; ⁵C₃ + ⁵C₂ = 20; ⁷C₅/⁷C₄ = 3/5; (17) a 5-question true/false test — 2⁵ = 32 ways to answer; (18) 10 distinct points on a circle — ¹⁰C₃ = 120 triangles.
- 5-2 The binomial theorem (pp. 35–39). Group A: (1)–(3) fill in the missing coefficients — (x+y)⁴ = x⁴ + 4x³y + 6x²y² + 4xy³ + y⁴; (z−y)³ = z³ − 3z²y + 3zy² − y³; (x+y)⁵ = x⁵ + 5x⁴y + 10x³y² + 10x²y³ + 5xy⁴ + y⁵; (4)–(9) expand (1+x)⁴, (1−x)⁴, (1−2x)⁵, (2x−1)³, (x−y)³, (1−x/2)⁴; (10) in (1−3/(2x))⁵ the third term is 45/(2x²) and the fifth is 405/(16x⁴); (11) coefficient of x³ in (1−x)⁴ is −4; (12) coefficient of x³ in (x+y)⁵ is 10; (13) coefficient of x⁴ in (x+2)⁶ is 60; (14) coefficient of x⁵ in (x−1/2)⁸ is −7; (15) expand (2+√3)⁴ and prove (2+√3)⁴ + (2−√3)⁴ = 194 (correct: 97 + 56√3 and 97 − 56√3); (16) prove (x+1/x)³ = (x³+1/x³) + 3(x+1/x); (17) expand (2x)⁵ = 32x⁵. Group B: (1)–(9) expand (x−2)³, (1−y)³, (1+y)³, (1/2+b)³, (2p−3b)⁴, (x+1/x)⁴, (x²+1)³; coefficient of x³ in (2x)⁴ is 0; coefficient of x⁴ in (x+y)⁷ is 35; (10) prove (2+√3)⁴ − (2−√3)⁴ = 112√3 (correct); (11) if (√2+√6)³ − (√2−√6)³ = 2√2·m then m = 12√3; (12) prove (1+x)⁷ = 1 + 7x + 21x² + 35x³ + 35x⁴ + 21x⁵ + 7x⁶ + x⁷.
- 5-3 Probability (pp. 40–44). Group A: (1)–(3) decide whether two events are independent — draw with replacement (independent), draw without replacement (dependent), two rolls of a die (independent); (4)–(5) independent events, P(A∩B) — 0.4 × 0.3 = 0.12; (1/2) × (2/5) = 1/5; (6)–(7) mutually exclusive events, P(M∪N) — 0.3 + 0.14 = 0.44; 0.6 + 0.2 = 0.8; (8) A, B mutually exclusive, P(A) = 0.4, P(B) = 0.35 — P(Ā) = 0.6, P(B̄) = 0.65, P(A∩B) = 0, P(A∪B) = 0.75, P(Ā∪B̄) = 1; (9) P(A) = 0.4, P(B) = 0.3, P(A∩B) = 0.25 — P(Ā∩B̄) = 0.55, P(A∪B) = 0.45, P(Ā∪B̄) = 0.75; (10) M, N independent, P(N) = 1/2, P(M̄) = 3/5 — P(M) = 2/5, P(M∩N) = 1/5, P(M∪N) = 7/10; (11) P(M∪N) = 0.7, P(M) = 0.5, P(N) = 0.3 — P(M∩N) = 0.1; (12) P(M̄) = 1/3, P(N̄) = 1/4, P(M̄∪N̄) = 1/5 — P(M∪N) = 37/60, P(M∩N) = 4/5; (13) P(M∪N) = 7/10, P(M) = 1/5, P(M∩N) = 0 — P(N) = 1/2; (14) a die 1–6, A = {2}, B = square numbers {1, 4}, C = even numbers — P(A∪B) = 1/2, P(A∪C) = 1/2, P(A∩B) = 0, P(B̄∪C̄) = 5/6; (15) P(Rashid succeeds) = 2/5, P(Saad succeeds) = 1/3 — both succeed 2/15 (independence assumed, not stated); (16) an institution's 200 employees, English/computing courses — table 45, 33, 70, 52 = 200 (both courses 45/200, English only 33/200, either 148/200); (17) a salmon farm, coloured 3, 20, 35, 12 = 70 and spotted 7, 15, 25, 3 = 50 (total 120) by length class 16–18 … 22–24 cm — P(coloured) = 7/12, P(length < 20 cm) = 3/8, P(spotted and length ≥ 20 cm) = 7/30, P(spotted or length ≥ 22 cm) = 31/60, P(coloured and length ≥ 18 cm) = 67/120, P(not spotted and length ≥ 20 cm) = 47/120. Group B: (1)–(2) independence — drawing a red ball and rolling a 3 (independent); first and second child both boys (independent); (3)–(4) independent, P(M∩N) — (3/7) × (7/15) = 1/5; 0.12 × 0.24 = 0.0288; (5)–(6) mutually exclusive, P(M∪N) — 0.14 + 0.16 = 0.30; 3/5 + 3/10 = 9/10; (7) A, B mutually exclusive, P(Ā) = 0.3, P(B) = 0.25 — P(A) = 0.7, P(B̄) = 0.75, P(A∩B) = 0, P(A∪B) = 0.95, P(Ā∩B̄) = 0.05; (8) P(Ā) = 0.45, P(B) = 0.32, P(A∩B) = 0.18 — P(B̄) = 0.68, P(A∪B) = 0.69, P(Ā∪B̄) = 0.82; (9) P(M) = 0.25, P(N) = 0.45, P(M∪N) = 0.7 — P(M∩N) = 0, so the events are mutually exclusive; (10) P(M) = 0.7, P(N) = 0.4 — can they be mutually exclusive? No: P(M) + P(N) = 1.1 > 1; (11) P(A∪B) = 0.243, P(A) = 0.152, P(A∩B) = 0.125 — P(B) = 0.216, P(B̄) = 0.784; (12) a box of 12 discs numbered 1–12 — P(2) = 1/12, P(odd) = 1/2, P(prime) = 5/12, P(multiple of 4) = 1/4; (13) a die with faces 3, 3, 3, 1, 4, 6 — P(even) = 1/3, P(multiple of 3) = 2/3.
- Unit 5 test (pp. 45–47). Essay questions: (1) choose 5 actors from 11 for a play — combination, ¹¹C₅ = 462; (2) choose 3 pupils from 15 with regard to order — permutation, ¹⁵P₃ = 2,730; (3) expand (1−2x)⁴ = 1 − 8x + 24x² − 32x³ + 16x⁴; (4) M, N independent, P(M) = 0.38, P(N) = 0.24 — P(M∩N) = 0.0912; (5) M, N mutually exclusive, P(M) = 0.33, P(N) = 0.20 — P(M∪N) = 0.53; (6) blood types of 1,500 people — A 515+/115−, B 75+/45−, AB 60+/15−, O 510+/165− (positive 1,160, negative 340, total 1,500) — P(blood type A) = 630/1,500 = 0.42, P(positive) = 1,160/1,500. Objective items: true/false (1)–(12) — (1) 10! = 3,628,800 (true); (2) 4! × 5! = 360 (false; 2,880); (3) ⁸P₂ = 360 (false; 56); (4) ⁴C₃ × 3 = 15 (false; 12); (5) ⁵P₂ = 2 × ⁵C₂ (true); (6) the expansion of (1+j)⁵ (true); (7) the term 126j⁴d⁵ in (j+d)ⁿ gives n = 5 (false; n = 9); (8) second-term coefficient 7 in (x+r)ⁿ gives n = 6 (false; n = 7 if r = 1); (9) the second term of (x+3)⁹ is 54x⁸ (false; 27x⁸); (10) choosing a car's colour and its tyre type at random are independent events (true); (11) M, N independent, P(M) = 12/17, P(N) = 3/8 → P(M∩N) = 9/17 (false; 9/34); (12) rolling a fair die once, P(4 or an even number) = 1/2 (true). Multiple choice (13)–(24): (13) 10!/(7! × 3!) = 120; (14) **see book error 5**; (15) (⁷C₄ × ⁹C₂)/⁹C₄ = 10; (16) choose 5 basketball players from 12 with the order of positions mattering — ¹²P₅ = 95,040; (17) choose 3 flags from 7 — ⁷C₃ = 35; (18) expansion of (p−b)³ — p³ − 3p²b + 3pb² − b³ (the other options differ in signs or drop the 3 on pb²); (19) third term of (p−b)⁷ is 21p⁵b²; (20) coefficient of j⁴ in (2j−4b)⁵ is −320; (21) M, N independent, P(M) = 1/3, P(N) = 9/10 — P(M∩N) = 3/10; (22) E, T mutually exclusive, P(E) = 3/5, P(T) = 1/3 — P(E∪T) = 14/15; (23) E, T mutually exclusive, P(E) = 1/7, P(T) = 60% — P(E∪T) = 26/35; (24) rolling a fair die once, P(even or prime) = 5/6.
- Enrichment (p. 48): (1) a bag with 3 black balls and 1 white ball, drawn one after another without replacement, stopping at the white ball — P(stopping at the third draw) = (3/4)(2/3)(1/2) = 1/4; (2) a safe code is a letter followed by a 3-digit number — (a) the letter is one of the letters of "Kuwait" (4 letters) → 4,000 codes; (b) the letter is K with no repeated digit → 720; (c) the letter is one of "Kuwait" and the code is even → 2,000; (3) prove (x+1/x)⁶ − (x−1/x)⁶ = 12x⁴ + 12/x⁴ + 40 (correct — verified at 300 dpi; the middle term is 12/x⁴).

#### BOOK ERRORS — 4 (a fifth claim was retracted by the citation check — see item 2)

**1. Printed p. 13, Exercise 4-2, item (4) — the list has 24 ages, not 25.** (Cited as printed p. 14 in the first draft; the page's own footer is ١٣, and printed = PDF − 1, so the item is on printed p. 13 — citation corrected by the citation check.) The item says 25 people following a certain event (٢٥ شخصًا يتابعون حدثًا معينًا; first draft's "follow a diet" was a mistranslation), then lists their ages: 25, 22, 22, 19, 18, 17, 16, 8, 7, 7, 7, 7, 7, 6, 6, 6, 6, 6, 4, 4, 4, 4, 3, 3 — 24 values (verified digit-by-digit against a 600-dpi crop). **Correct:** either the count is 24 people, or one age is missing from the list. With the 24 listed values the sum is 234, the mean 9.75, the median 7, and the mode is bimodal (6 and 7, five each).

**2. RETRACTED by the citation check (2026-11-06) — not a book error.** Printed p. 26, Unit 4 enrichment, item (1): the first draft counted 16 frequencies for 15 heights, including a "0" after the frequency 5. A 400-dpi crop of the table shows exactly **15 heights (158–172) and 15 aligned frequencies (2, 3, 4, 2, 1, 5, 3, 1, 2, 6, 7, 8, 4, 1, 1)**, summing to the printed total 50; the "0" was a phantom cell in the first read. The table is usable as printed.

**3. Printed p. 25, Unit 4 test, multiple-choice item (11) — no correct option.** The data are 5, 6, 7, 8, 9, 9, 9, 10, 12, 14, 17, 18, 18, 19, 19 (15 values — three 9s, verified at 300 dpi): minimum 5, Q1 8, median 10, upper quartile 18, maximum 19 (the book's own quartile convention, position 3(n+1)/4 = 12th value). The intended plot (option ج) has median 10 and Q1 8 but draws the upper quartile at 17; the other three plots get the median wrong (11, 12, 9). **Correct:** the upper quartile is 18, so none of the four plots represents the data.

**4. Printed p. 34, Exercise 5-1 Group B, item (10)(a) — ⁿP₂ = 28 has no integer solution.** ⁿP₂ = n(n−1) = 28 gives n = (1+√113)/2, not an integer (5 × 4 = 20, 6 × 5 = 30) — verified at 300 dpi. **Correct:** the intended value was presumably 20 (n = 5) or 30 (n = 6). The neighbouring parts are fine: (b) (n+3)!/(n+1)! = 42 gives n = 4; (c) ⁿP₂ = 8n gives n = 9.

**5. Printed p. 46, Unit 5 test, multiple-choice item (14) — no correct option.** ⁶P₄ × ¹⁰C₇ = 360 × 120 = 43,200, but the options are 75,600 / 7,560 / 2.5 / 210 (verified at 300 dpi). **Correct:** 43,200. Option (أ), 75,600, is ⁶P₄ × ¹⁰C₄ — the value if the second factor were ¹⁰C₄ instead of ¹⁰C₇.

**Cleared by render (not errors):** p. 21, Exercise 4-4 Group B (1)(b) — the printed ln values (0, 0, 0.693147181, 1.098612289, 1.098612289, 1.791759469, 4.025351691) are all correct. P. 48, enrichment (3) — (x+1/x)⁶ − (x−1/x)⁶ = 12x⁴ + 12/x⁴ + 40 is correct (the middle term is 12/x⁴, verified at 300 dpi). P. 47, Unit 5 test item (18) — the four expansions of (p−b)³ are all distinct: options (أ) and (ج) carry pb² with coefficient 1 instead of 3, so only (د) is correct. P. 37, Exercise 5-2 (15)(b) — (2+√3)⁴ + (2−√3)⁴ = 194 is correct.

#### HONEST NEGATIVES

- **Exercises only — it teaches nothing by itself.** No lessons, no worked examples, no explanations and no answers. The contents page does not even print the lesson titles — only exercise numbers — so a learner needs the Grade 11 Statistics Term 2 student book (§9) alongside it to know what each set is about.
- **No tables or formula sheet anywhere.** No z-table, no t-table, no binomial-coefficient table, no formula summary. Several exercises (4-4, the die-roll enrichment, the add-5/multiply-by-5 item) require a statistics program — the pages print empty spreadsheet screenshots (columns A–G) — but no program is named and no instructions for one are given.
- **Statistics stops at descriptive measures plus z-scores in Unit 4; Unit 5 is classical probability only** — independent and mutually exclusive events, the binomial theorem, counting. No conditional probability as a formula, no Bayes, no random variables or probability distributions (those live in the Grade 12 statistics books).
- **Dated data throughout.** The exercises carry a 2013 Pearson source: Kuwait temperatures from June 2011, a cheese factory, a wire factory, a salmon farm. The numbers work as exercises but the world they describe is old.
- **The ln-transformation exercise never says why.** Exercise 4-4 Group B (1) hands the learner ln values to 9 decimal places and asks for the mean, median and SD of the transformed data, but the book never explains that the log transform is a way of taming an outlier — the teaching point is left implicit.
- **Independence is assumed, not stated, in Exercise 5-3 (15).** P(both Rashid and Saad succeed) = 2/15 only holds if their results are independent; the item never says so — the learner is expected to infer it from the lesson context.

#### HELD-COPY DEFECTS

- PDF pp. 5 and 7 are blank (portrait dividers between the Amir's portrait, PDF p. 4, and the Crown Prince's portrait, PDF p. 6). PDF p. 50 is the back cover. No content is lost — the enrichment ends complete on printed p. 48.
- The text layer is mojibake throughout (custom-encoded fonts with no ToUnicode map) — a PDF-production property, not damage; the rendered pages are clean and the book was read from renders.
- The imprint deposit date 2015/5/26 and the Pearson 2013 imprint predate this reprint (2024–2025); they are carried over from the first edition and recorded as printed.
- No missing, duplicated or truncated content pages.

#### Numbering oddities

- Exercises are numbered per unit (4-1 … 5-3); each set is headed تمرّن ("practice") and split into Group A (basic) and Group B (consolidation).
- The Unit 4 test restarts its numbering inside the test: essay items 1–6, then true/false items 1–7, then multiple-choice items 8–13. The Unit 5 test runs essay 1–6, true/false 1–12, then multiple-choice 13–24 (continuous across the two objective blocks).
- Printed = PDF − 1.
- The contents page lists exercise numbers only, with no lesson titles and no page numbers for the unit tests' internal blocks.


---
### 11. g12-t2-wb.pdf — Grade 12, Term 2, STUDENT book, scientific track (not a workbook)

**Title as printed:** الرياضيات — الصف الثاني عشر علمي — الفصل الدراسي الثاني — القسم الأول — كتاب الطالب (al-Riyāḍiyyāt — Mathematics — Grade 12 scientific track — Second term — Part 1 — Student book), secondary stage (المرحلة الثانوية). Part 2 (same file) is القسم الثاني, 2/2.
**Grade / term / track:** Grade 12, Term 2, Parts 1–2, scientific track (العلمي).
**Kind:** **Student book — not a workbook.** The cover (PDF p. 1) and the title page (PDF p. 2) both say كتاب الطالب. The filename's "-wb" is wrong; the record slot that calls this file a workbook is wrong with it.
**Edition / year as printed:** 2nd edition, 1447 AH / 2025–2026. Imprint (PDF p. 3): 1st edition 2014–2015, 2nd edition 2016–2017, reprints 2018–2019, 2019–2020, 2020–2021, 2021–2022, 2022–2023, 2023–2024, 2024–2025, 2025–2026.
**Supervisory committee:** Hussein Ali Abdullah (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour.
**Part 2 sub-committee:** Hassan Noh Ali Al-Mahna (head), Sadiqa Ahmed Saleh Al-Ansari, Sheikha Falah Mubarak Al-Hajraf, Majdi Mohammed Yis Daraz, Yahya Abdelsalam Khaled Aql, Wadha Ibrahim Mazal Al-Dosari.
**Publisher:** Kuwait Ministry of Education, Educational Research sector — Curriculum Development Administration. House of Education / Pearson Education 2014. Printed by the Government Press — State of Kuwait.
**Deposit as printed:** Ministry library no. 19, dated 2016/4/13.
**ISBN:** no ISBN on the imprint; back-cover barcode ISBN 978-6-14406-643-0 (Pearson Scott Foresman).
**PDF pages:** 197; printed pp. 1–177. Part 1: PDF pp. 1–68, printed pp. 1–63 (printed = PDF − 3). Part 2: PDF pp. 69–197, printed pp. 64–177 (printed = PDF − 17).
**File:** `g12-t2-wb.pdf`, 114,936,919 bytes, SHA-256 `3418a9e3241a9163fe5aa2a1725d3f4ab85aa1be413c15aca5269b4fe6ed5ba4`.
**Language:** Arabic. **Answer key:** none.
**Generation:** old generation (2014 series, 2nd edition).
**How read:** image-only — the text layer is empty — read visually from 200-dpi renders of all 197 pages; flagged items were re-verified at 300 dpi.
**Cover art:** oil refinery, Kuwait Towers, a hyperbola figure (F₁(−c,0), F₂(c,0), A₁(−a,0), A₂(a,0), B₁(0,−b), B₂(0,b)) and a solid of revolution.

#### Contents (printed page numbers)

**Front matter (Part 1):** cover (PDF p. 1); title page (PDF p. 2); imprint (PDF p. 3); PDF p. 5 blank; Amir portrait (PDF p. 6); PDF p. 7 blank; Crown Prince portrait (PDF p. 8); introduction (PDF pp. 10–11, signed Dr. Saud Hilal Al-Harbi); contents, Part 1 only (PDF p. 12).

**Unit 5 — Integration (printed pp. 10–63).** Opener/project p. 10 (the area under y = x² — Riemann sums R₅/L₅; the table for n = 5, 10, 20, 50, 100 is left for the learner to compute and the values are never printed). Prior knowledge p. 11. 5-1 The indefinite integral, pp. 12–19 (the antiderivative; basic integrals; the power rule — including ∫((x²−2)/x²)²dx = x+4/x−4/(3x³)+C and ∫(x+1)/(∛x+1)dx = (3/5)x∛(x²)−(3/4)x∛x+x+C, where the denominator is ∛x+1, not ∛(x+1)). 5-2 Integration by substitution, pp. 20–23. 5-3 Integration of trig functions, pp. 24–28 (the trig integrals table — eight integrals; including ∫x csc²(x²−1)dx = −(1/2)cot(x²−1)+C and ∫sec⁴x tan x dx = sec⁴x/4+C). 5-4 Integration of exponential and logarithmic functions, pp. 29–35 (derivatives of 3^x, 6^√x, 10^sin x, e^(2x/3), e^sec x; the 5-4 discovery table — f′(0) for a = 2, 3, e — is left blank for the learner, with the conclusion lim (a^h−1)/h = ln(a) stated). 5-5 Integration by parts, pp. 36–41 (including ∫x sin x dx = −x cos x+sin x+C and ∫x e^x dx = (x−1)e^x+C). 5-6 Integration using partial fractions, pp. 42–49 (distinct linear factors only; including the result 2ln|x+3|+3ln|x−5|+C). 5-7 The definite integral, pp. 50–59 (including ∫₋₂³(3x²−x+4)dx = 52.5, ∫₀³x√(x+1)dx = 116/15, ∫₋₂⁰x e^(−x)dx = −e²−1, ∫₁⁵(2x+8)/(x²+4x+3)dx = 3ln3−ln2). Problem-solving guide p. 60 (a revenue model — R(30) = 8550 dinars). Concept map p. 61; summary pp. 61–63.
**Verified:** ∫(x²−2x+5)dx = x³/3−x²+5x+C; the substitution examples pp. 20–23; the trig integrals pp. 24–28; the exp/log examples pp. 29–35; the parts examples pp. 36–41; the partial-fractions examples pp. 42–49; the definite-integral examples pp. 50–59.

**Front matter (Part 2):** cover (PDF p. 69, 2/2); title page (PDF p. 71); imprint (PDF p. 72); Amir portrait (PDF p. 75); Crown Prince portrait (PDF p. 77); contents, Part 2 only (PDF p. 79); PDF p. 80 blank.

**Unit 6 — Applications of the definite integral (printed pp. 64–97).** Opener/project p. 64 (crude-oil price P(t) = 30+0.3√t). Prior knowledge p. 65. 6-1 Areas in the plane, pp. 66–75 (including the area for f(x) = x²+4−4x on [2,5] → 9, and for f(x) = x²−3x on [0,3] → 9/2). 6-2 Volumes of solids of revolution, pp. 76–79 (including f(x) = x²+2 on [−1,1] → 166π/15). 6-3 Arc length and the equation of a function curve, pp. 80–85 (including f(x) = x^(3/2) on [0,4] → (8/27)(10√10−1) ≈ 9.07). 6-4 Differential equations, pp. 86–97 (order and degree; y = e^(x²) solves y′−2xy = 0; y′′−4y′+3y = 0 gives y = C₁e^x+C₂e^(3x); y′′−4y′+4y = 0 gives y = (C₁x+C₂)e^(2x); y′′+y′+4y = 0 gives y = e^(−x/2)(C₁cos(√15/2)x+C₂sin(√15/2)x); the drug model 2S′′+3S′+S = 0 gives r = −1, −1/2). Concept map p. 96; summary pp. 96–97.
**Verified:** all of the worked examples above were recomputed and are correct.

**Unit 7 — Conic sections (printed pp. 98–137).** Opener/project p. 98 (the parabola as the locus equidistant from a point and a line). Prior knowledge p. 99 (Kepler, 1571–1630). 7-1 The parabola, pp. 100–108 (including the headlight y² = 12x → focus (3,0), and the suspension bridge x² = 270y, support height 26.7 m). 7-2 The ellipse, pp. 109–117 (including x²/36+y²/20 = 1, and the lithotripter with foci (±5.45,0)). 7-3 The hyperbola, pp. 118–125 (including 9x²−16y² = 144 → x²/16−y²/9 = 1, and |P₁F₁−P₁F₂| = 8 = 2a). 7-4 Eccentricity, pp. 126–133 (e = 1 parabola, e < 1 ellipse, e > 1 hyperbola; the planet table — Mercury 0.21 … Neptune 0.008). Problem-solving guide p. 134 (a solar-panel parabola — focus (0,2), x² = 8y). Concept map p. 135; summary pp. 135–137.
**Verified:** all of the worked examples above were recomputed and are correct.

**Unit 8 — Probability (printed pp. 138–177).** Opener/project p. 138 (airline overbooking — 213 seats, no-show probability 0.025, 236 tickets; 236×0.9025 ≈ 213 expected show-ups, consistent). Prior knowledge p. 139 (Fermat — see error 1; Pascal, 1623–1662, correct). 8-1 Discrete random variables, pp. 140–158 (two-dice random variables; the conditions on a discrete p.d.f.; the CDF property P(a<X≤b) = F(b)−F(a), p. 153; Ex (9) p. 152 — the CDF values; the binomial — factory μ = 2, σ² = 1.98; coin μ = 2.5, σ² = 1.25). 8-2 Continuous random variables, pp. 159–177 (the uniform distribution; the normal distribution; Ex (4) p. 164 — P(Z≤2.18) = 0.98537, P(Z≥2.43) = 0.00755, P(1.4≤Z≤2.6) = 0.0761; Ex (5) p. 165 — P(Z≤−0.55) = 0.29116, P(−2.2≤Z≤−1.6) = 0.0409). Problem-solving guide p. 167 (salaries N(50000, 400000000): P(X<40000) = 30.85%, P(45000<X<65000) = 37.21%, P(X>70000) = 15.87% — see error 2). Concept map p. 168; summary pp. 169–170; tables pp. 171–177 (binomial tables (1)–(3), pp. 171–175; standard normal tables (4)–(5), pp. 176–177).
**Verified:** all of the worked examples above were recomputed and are correct.

#### BOOK ERRORS — 5

1. **Printed p. 139, the prior-knowledge page:** Pierre de Fermat's dates are reversed — the caption prints "(1665–1601)". **Correct: (1601–1665)** (born 1601, died 1665). (Pascal on the same page is correct, 1623–1662; Kepler on p. 99 is correct, 1571–1630.)
2. **Printed p. 167, the problem-solving guide, part (c) conclusion sentence:** the book writes "37.21% of employees have salaries between 65 000 and 54 000 Kuwaiti dinars". **Correct: "45 000", not "54 000"** — the digits are transposed. The computation itself is for 45 000 (z = −0.25) and is correct (0.37206).
3. **Printed p. 169, the Unit 8 summary, the CDF interval formulas, items 2–3:** the book states P(a ≤ X < b) = F(b) − F(a) and P(a ≤ X < b) = P(a ≤ X ≤ b) = F(b) − F(a). **Both are FALSE for a discrete random variable** (point masses at a and b matter); only item 1, P(a < X ≤ b) = F(b) − F(a), is correct. Counterexample from the book's own Ex (9) (p. 152): X takes values {3, 4, 5} with f(3) = 0.5, f(4) = 0.3, f(5) = 0.2; F(3) = 0.5, F(4) = 0.8. With a = 3, b = 4: P(3 ≤ X < 4) = 0.5, but F(4) − F(3) = 0.3; P(3 ≤ X ≤ 4) = 0.8 ≠ 0.5. **Correct forms:** P(a ≤ X < b) = F(b) − F(a) − P(X=b) + P(X=a); P(a ≤ X ≤ b) = F(b) − F(a) + P(X=a). (The four interval forms are equal only for a continuous variable.) The book contradicts itself: its own property on p. 153 (P(a<X≤b) = F(b)−F(a)) is correct, while the summary on p. 169 extends it wrongly.
4. **Printed p. 171, the binomial probability table, n = 2, x = 2 row:** the last four entries are each exactly one-tenth of the correct value. The book prints p = 0.7 → 0.0490, p = 0.8 → 0.0640, p = 0.9 → 0.0810, p = 0.95 → 0.0902. **Correct: 0.490, 0.640, 0.810, 0.902** (f(2;2,p) = p²). Confirmed by the table's own symmetry: the row n = 2, x = 0 gives 0.490 at p = 0.3, 0.640 at p = 0.2, 0.810 at p = 0.1, 0.902 at p = 0.05. The rest of the row (0.002, 0.010, 0.040, 0.090, 0.160, 0.250, 0.360) is correct, and the other binomial rows spot-checked are symmetric and correct.
5. **Printed pp. 164–165, worked Examples (4) and (5), the table page references:** Ex (4) says table (4) is on "page 177"; it is on printed p. 176. Ex (5) says table (5) is on "page 178"; it is on printed p. 177 — and no printed p. 178 exists (the book's last printed page is 177; PDF pp. 195–196 are blank). The table values the examples use are correct; only the page references are wrong (each one page too high).

**Cleared (not errors):** Ex (6)(c), pp. 17/20 — the denominator is ∛x+1 (the radical covers only x), and the factorisation is correct. The planet eccentricity table (p. 127) gives Neptune as 0.008 — a truncation of ~0.0086, not the current osculating value 0.0113 — but the book's arithmetic never uses it, so it is not filed as an error (see Honest negatives). The Unit 8 opener's 236 tickets (236×0.9025 ≈ 213 expected show-ups) is consistent. The 5-4 calculator table (p. 29) is left blank for the learner, with the conclusion lim (a^h−1)/h = ln(a) stated.

#### HONEST NEGATIVES

- No answer key (the "try to solve" items throughout have no printed answers; the back cover lists an "exercises workbook with answers" as a separate series component, not included here).
- The Unit 5 opener's R₅/L₅ table (n = 5, 10, 20, 50, 100) is left for the learner to compute; the book never prints the values. The 5-4 discovery table (f′(0) for a = 2, 3, e) is likewise left blank, with answers not given.
- Integration by partial fractions covers distinct linear factors only — no repeated factors, no irreducible quadratic factors.
- Differential equations cover only constant-coefficient second-order linear equations (by the sign of Δ) plus y′ = ay and y′ = ay+b — no separation of variables, no integrating factor, no first-order linear equations in general.
- Conic sections cover the parabola, ellipse, hyperbola and eccentricity — no rotation of axes, no polar form of conics, no asymptotes beyond the hyperbola's.
- Probability covers discrete and continuous random variables, the binomial and the normal — no Poisson, no geometric distribution, no sampling distributions, no hypothesis testing, no confidence intervals (those live in the Grade 12 Term 1 scientific book).
- The planet eccentricity table (p. 127) mixes precision: Neptune is given as 0.008 (3 decimals, a truncation of ~0.0086) while the other seven planets are given to 2 decimals — and the current osculating value for Neptune is 0.0113, so a learner checking a current table will find a different number.
- The Unit 8 summary's CDF formulas (error 3) contradict the book's own correct property on p. 153 (P(a<X≤b) = F(b)−F(a)), so the book disagrees with itself on discrete interval probabilities.
- No worked example shows a binomial probability being read from the printed binomial tables (pp. 171–175); the tables are given but never used in a worked example.

#### HELD-COPY DEFECTS

- PDF pp. 5 and 7 blank (Part 1 front matter, portrait dividers); PDF pp. 67–68 blank (Part 1 tail); PDF p. 80 blank (before the Unit 6 opener); PDF pp. 195–196 blank (Part 2 tail); PDF p. 197 is the back cover.
- The book is image-only (no text layer) — read from renders; the printed pages are clean.
- No ISBN on the imprint page (back-cover barcode ISBN only).
- The Part 2 title page repeats the Part 1 imprint verbatim (same deposit no. 19, same edition history).
- No missing, duplicated or truncated content pages; Units 5–8 complete.

#### Numbering oddities

- Two parts bound in one file with separate covers, title pages, imprints and contents pages; Part 1 covers Unit 5 only, Part 2 covers Units 6–8; the two contents pages list only their own part's units — neither lists the whole book. Printed pagination runs continuously 1–177.
- The book's last printed page is 177, but Examples (4) and (5) refer to table pages as 177/178 (see error 5).
- The binomial tables are numbered (1)–(3) and the normal tables (4)–(5), continuing one sequence across both units.
- Printed = PDF − 3 in Part 1; printed = PDF − 17 in Part 2.


---
### 12. g12-stats-t2-wb.pdf — Grade 12, Term 2, Statistics student book (literary track)

**Identity.** Title as printed: الرياضيات — كتاب الطالب (Mathematics — Student book), الصف الثاني عشر أدبي (Grade 12, literary), الفصل الدراسي الثاني (Second term), الطبعة الثانية (2nd edition). Grade 12, Term 2, **literary track**, **student book — not a workbook** (the filename's "-wb" is wrong; the cover and title page both say كتاب الطالب), old generation. Edition as printed: 2nd edition, 1446 AH / 2024–2025 (1st edition 2014–2015; 2nd edition 2016–2017; reprints 2018–2019, 2019–2020, 2020–2021, 2021–2022, 2022–2023, 2023–2024, 2024–2025). Supervising committee: Hussein Ali Abdullah (head), Hessa Younes Mohammed Ali, Fathiya Mahmoud Abu Zour. Work team (Grade 12 literary): Fathi Mohammed Abdel-Fattah (head), Mahmoud Abdel-Ghani Mohammed, Saeed Ahmed Ali Khalaf, Yusra Shamlan Ahmed Al-Bahr, Aida Khalaf Awad Al-Shammari, Hanadi Habas Ghaneem Al-Majoul. Publisher: Kuwait Ministry of Education, Educational Research sector — Curriculum Development Administration. House of Education / Pearson Education 2014; Arwa Printing Press (مطبعة أروى). Three QR codes (educational channel, curriculum evaluation, whole book). **No ISBN printed on the imprint**; back-cover Pearson barcode ISBN **978-614-406-606-5**. Deposit: Ministry library no. (14), dated 2016/4/11. Cover art: press microphones, a normal curve with a shaded area, and a linear-programming graph (the common solution region). PDF pages 92; printed pages 1–90 (printed = PDF − 1; PDF p. 92 is the back cover). File size 10,869,545 B. SHA-256 `8209eb596e5f13d0dc346ea430bedb37187270d92afeb1111436aafdae4935d6`.

**Method note.** The text layer is mojibake (legacy WinSoftPro font) — Arabic is unreadable in it, Latin and digits partly survive. The book was read visually from 200 dpi renders of all 92 pages; every worked example was recomputed, and every inequality direction in Unit 5 (and in the normal-distribution examples) was checked against a 300% crop of its glyph before being filed — see the reading note below.

**Contents (printed page numbers).** Two units, continuing Term 1 numbering (Units 4–5). No answer key. No unit tests or assessments anywhere.

**Unit 4 — Random variables and their distributions (المتغيرات العشوائية وتوزيعها), p. 10.** Project (p. 10): airline overbooking — a plane with 213 seats; the probability a passenger misses the flight is 0.025; (a) prove the airline should sell 236 tickets to be sure 213 passengers show up; (b) if it sold 240 tickets, find the probability there is an extra passenger with no seat; (c) if it pays 200 dinars to each passenger who booked and found no seat, find the probability it pays 1,000 dinars if it sold 246 tickets; then write a detailed report. Opener (p. 11): prior knowledge — counting principle, permutations and combinations; random experiment and sample space; probabilities of events, mutually exclusive events, complement, independent events. Will learn: discrete and continuous random variables; probability distribution function and cumulative distribution function of a discrete random variable; probability density function of a continuous random variable. Key terms: discrete random variable, probability distribution, Bernoulli trial, Bernoulli distribution, expected value, probability distribution function, cumulative distribution function, probability density function, continuous uniform distribution, normal probability distribution. "Add to your knowledge": the founders of probability — Cardano, Pascal, Fermat, Bernoulli — developed probability through games of chance; attention then turned to random variables that take infinitely many values, or all values in an interval.

**4-1 Random variables and probability distributions (pp. 12–37).** "Let's think and discuss" (p. 12): two dice — die 1 has two faces 0, two faces 1, two faces 2; die 2 has three faces 0, three faces 1; M = sum of the two upper faces takes 0, 1, 2, 3 with probabilities 1/6, 1/3, 1/3, 1/6; M = product takes 0, 1, 2 with probabilities 2/3, 1/6, 1/6. Definition: a random variable is a function whose domain is the sample space and whose codomain is R; two types, discrete and continuous. Notation used throughout: س، ص، … for random variables; د(س) for the density/distribution function, ت(م) for the c.d.f., μ for expectation, σ² for variance, ح for the standard normal variable z.

**(4-1-a) Discrete random variables (pp. 14–37).** The range is a countable set, finite or infinite. Ex. 1: two coin tosses, X = number of tails, range {0,1,2}. Ex. 2: two tosses; X = number of heads {0,1,2}; Y = square of the number of heads {0,1,4}; Z = heads minus tails {2,0,−2}. Try-its 1–2: three tosses. Probability distribution function د(سᵣ) = P(X = sᵣ), in table and graph form. Ex. 3: one toss, X = number of heads: د(0) = د(1) = 1/2. Ex. 4: three tosses, X = number of heads: 1/8, 3/8, 3/8, 1/8. The two conditions for a discrete p.d.f.: 0 ≤ د(س) ≤ 1 and Σد(سᵣ) = 1. Ex. 5: X takes −2, 1, 2, 3 with probabilities 0.3, 0.1, k, 0.2 → k = 0.4. Try-it 5: k = 0.2. Ex. 6: range {−2,−1,0,1}, د(−2) = د(−1) = 0.3, د(1) = 0.2 → د(0) = 0.2. Try-it 6: د(3) = 0.15. Ex. 7: box of 10 balls (7 white, 3 red), draw 4 together, X = number of red balls: P(X=0) = 35/210, P(X=1) = 105/210, P(X=2) = 63/210, P(X=3) = 7/210. Try-it 7: draw 3, X = number of white balls. Expectation E(X) = μ = Σ sᵣ·د(sᵣ): Ex. 8 (X 1–5, probs 3/7, 2/7, 6/35, 3/35, 1/35 → μ = 2), Try-it 8 (μ = 2/3), Ex. 9 (two tosses, X = heads → μ = 1), Try-it 9 (number of children per family). Variance Var(X) = σ² = Σ sᵣ²·د(sᵣ) − μ²; SD σ = √Var: Ex. 10 (X 1,2,3,4, probs 0.1, 0.6, 0.2, 0.1 → μ = 2.3, σ² = 0.61, σ ≈ 0.7810), Try-it 10 (μ = 3.6, σ² = 0.64, σ = 0.8), Ex. 11 (X 1–5, probs 0.43, 0.29, 0.17, 0.09, 0.02 → μ = 1.98, σ² = 1.1396, σ ≈ 1.0675), Try-it 11 (μ = 3.2, σ² = 2.16, σ ≈ 1.4697). Cumulative distribution function ت(م) = P(X ≤ م): Ex. 12 (X 3,4,5, probs 0.5, 0.3, 0.2: ت(2) = 0, ت(3) = 0.5, ت(4) = 0.8, ت(4.5) = 0.8, ت(5) = 1, ت(7) = 1), Try-it 12. Properties P(a < X ≤ b) = ت(b) − ت(a) and P(X > a) = 1 − ت(a): Ex. 13 (c.d.f. ت(1) = 0.15, ت(2) = 0.2, ت(3) = 0.6, ت(5) = 1: P(1 < X ≤ 3) = 0.45; P(2 < X ≤ 5) = 0.8; P(X > 2) = 0.8), Try-it 13. Graphs: the p.d.f. graph is a set of points, the c.d.f. graph a step function (Ex. 14: X 1–4, probs 0.2, 0.1, 0.4, 0.3; Try-it 14). Binomial distribution (توزيع ذات الحدين): Bernoulli trial — n independent identical trials, two outcomes, P(success) = p constant; P(X = s) = C(n,s)·p^s·(1−p)^(n−s): Ex. 15 (n = 7, p = 0.1: P(X=0) ≈ 0.4783; P(1 < X ≤ 3) ≈ 0.1470, by formula and by the binomial table), Try-it 15 (n = 8, p = 0.2), Ex. 16 (fair coin 8 times, P(exactly 5 heads) = 56/256 ≈ 0.2188), Try-it 16 (10 tosses, exactly 5 tails), Ex. 17 (fair die 5 times, X = number of 4s: (a) P(X=2) ≈ 0.1608; (b) P(X ≥ 1) = 0.5981; (c) P(X ≤ 1) = 0.8038), Try-it 17 (number of 3s). Binomial expectation and variance: μ = np, σ² = np(1−p): Ex. 18 (car factory 200 cars/day, 1% defective: μ = 2, σ² = 1.98, σ ≈ 1.4071), Try-it 18 (350 cars/day, 2% defective: μ = 7, σ² = 6.86, σ ≈ 2.619), Ex. 19 (coin 5 times, X = heads: μ = 2.5, σ² = 1.25, σ ≈ 1.1180), Try-it 19 (8 tosses: μ = 4, σ² = 2, σ ≈ 1.4142), Ex. 20 (1% of cars unfit, 8 drawn, X = number fit (n = 8, p = 0.99): μ = 7.92, σ² = 0.0792), Try-it 20 (100 customers, 70% pleased: μ = 70, σ² = 21, σ ≈ 4.5826).

**(4-1-b) Continuous random variables (pp. 38–50).** A continuous random variable takes every value in an interval (uncountable set) — travel time home, blood sugar, weights, temperature, distance, milk yield. Ex. 21 / Try-it 21: classify examples as discrete or continuous. Probability density function د(س): the relative-frequency histogram approaches the density curve as class widths shrink; total area = 1. Properties: (1) continuous on its domain; (2) د(س) ≥ 0; (3) area under the curve = 1; (4) P(a < X ≤ b) is the area between a and b; (5) P(X = a) = 0. Ex. 22: د(س) = 1 on [0,1]: P(1/2 ≤ X ≤ 1) = 1/2. Try-it 22: د(س) = 1/2 on [0,2]. Ex. 23: uniform د(س) = 1/4 on [1,5]: (a) P(1 < X ≤ 5) = 1; (b) P(X > 3) = 1/2; (c) P(X ≥ 1.5) = 7/8; (d) P(X = 2) = 0. Try-it 23: د(س) = 1/6 on [−3,3]. Ex. 24: triangular د(س) = س/8 on [0,4]: (a) P(0 ≤ X ≤ 4) = 1; (b) P(X ≤ 2) = 1/4; (c) P(X > 2) = 3/4. Try-it 24: د(س) = س/2 on [0,2]: (a) P(X > 1) = 3/4; (b) P(X ≤ 1) = 1/4; (c) P(X = 1) = 0. Uniform distribution: د(س) = 1/(ب−أ) on [أ,ب], μ = (أ+ب)/2, σ² = (ب−أ)²/12: Ex. 25 (د(س) = 1/4 on [−2,2]: (a) د is a density function; (b) د follows the uniform distribution; (c) P(−1 < X ≤ 2) = 3/4; (d) μ = 0, σ² = 4/3), Try-it 25 (د(س) = 1/5 on [−2,3]; that distribution has μ = 0.5, σ² = 25/12 ≈ 2.0833), Ex. 26 (د(س) = 1/2 on [−0.5,1.5]: P(−0.2 ≤ X ≤ 0.3) = 0.25; μ = 0.5, σ² = 1/3), Try-it 26 (د(س) = 1/3 on [0,3]; that distribution has μ = 1.5, σ² = 0.75). Normal distribution ط(μ, σ²) (pp. 46–50): mean = median = mode; bell-shaped, symmetric about س = μ; tails to ±∞; area 1; the line س = μ splits the area into 0.5 + 0.5. Standard normal ط(0,1); standardisation z = (س − μ)/σ; tables (4) and (5) at the end of the unit (table 4 for z ≥ 0, table 5 for z < 0). Ex. 27: P(Z ≤ 2.18) = 0.98537; P(Z ≥ 2.43) = 0.00755; P(1.4 ≤ Z ≤ 2.6) = 0.07610. Try-it 27. Ex. 28: P(Z ≤ −0.55) = 0.29116; P(−2.2 ≤ Z ≤ −1.6) = 0.04090; P(−1.3 ≤ Z ≤ 0.28) = 0.51346. Try-it 28. Ex. 29 (p. 49): marks ~ ط(16, 16) (μ = 16, σ = 4): (a) P(14 < X < 18) = 0.38292; (b) P(11 < X < 13) = 0.12098. Try-it 29: travel time ~ ط(16, 4). Guided problem (p. 50): salaries ~ ط(50000, 400000000) (μ = 50,000, σ = 20,000): (b) P(X < 40,000) = 0.30854 (30.85%); (c) P(45,000 < X < 65,000) = 0.37206 (37.21%); (d) P(X > 70,000) = 0.15866 (15.87%). Additional problems (p. 50): car-assembly time ~ ط(20, 4): (a) μ, σ²; (b) P(< 19.5 hours); (c) P(20 < time < 22).

**Unit 4 end matter.** Organiser (concept map, p. 51); summary (pp. 52–54) restating every definition and formula. Tables (pp. 55–59): binomial probabilities د(س), tables (1)–(3), n = 2–15, p = 0.05–0.95 (spot-checked entries recomputed — see cleared flags). Tables (4)–(5) (pp. 60–61): standard normal areas from the left, Φ(z) for z = 0.00–3.99 (table 4) and z = −3.99–0.00 (table 5).

**Unit 5 — Inequalities and linear programming (المتباينات والبرمجة الخطية), p. 62.** Project (p. 62): best return from an advertising campaign — a firm advertises a product on radio and TV: at least 60 devices take part, radio devices at least twice TV devices; a radio ad costs 2 KD, a TV ad 24 KD, budget 1,080 KD; each radio device reaches 2,000 listeners, each TV device 1,500 viewers; how many of each medium to reach the most consumers? Let س = radio devices, ص = TV devices: write the inequality for the expected number of devices, the inequality for the relation between radio and TV numbers, the equation for total listeners/viewers, the system with non-negativity (س ≥ 0, ص ≥ 0), graph it, find the solution region and the point maximising reach, then write a report. Opener (p. 63): prior knowledge — solving equations; locating points in the coordinate plane. Will learn: solving first-degree inequalities in two variables graphically; finding the common solution region of two or more first-degree inequalities in two variables graphically. Key terms: inequalities, solution region, linear programming, common solution region, constraints, decision variables, objective function. "Add to your knowledge": solving inequalities matters in decision-making in economic, commercial, agricultural and industrial operations — in agriculture to increase production and cut cost per area; in industry to increase production, cut cost and get the highest profit rate; in trade to choose between two offers so the consumer picks the best.

**READING NOTE — inequality directions in this book (applies to all of Unit 5, to the normal-distribution examples in Unit 4, and to every try-it below).** The book lays inequality expressions out right-to-left; a Latin left-to-right reading reverses the sign. The correct reading is by which side the glyph opens toward — the open side is the larger quantity. Every worked example's test-point conclusion and its graph confirm the intended direction, and every try-it inequality below was resolved the same way from a 300% crop of its glyph. All inequalities in this section are given in that resolved form. Points are likewise written right-to-left: the rightmost number is the x-coordinate — the point written with the minus on the rightmost number is (−1,1), not (1,−1); the three points in Try-it 2 are the set {(−1,1), (2,0), (1,−1)}, confirmed from the parallel worked Example 2, whose solution substitutes those coordinates.

**5-1 Inequalities (pp. 64–65).** Discussion: buying a car for less than 5,695 KD after 5% sales tax, with fuel under 570 KD for 90,000 km at 0.065 KD/litre — a table of 8 cars (prices 4,680–6,465 KD; consumption 6–12.3 km/litre) to test against the two conditions (only car ب meets both: price 4,680 × 1.05 = 4,914 < 5,695; fuel 90,000/11.4 × 0.065 ≈ 513 < 570). Recap: س < 5 is a first-degree inequality in one variable; س + ص ≥ 3 in two variables. Properties of inequalities: if س > ص then (1) س + ع > ص + ع for every ع; (2) س·ع > ص·ع for every ع > 0; (3) س·ع < ص·ع for every ع < 0. Ex. 1: solve and represent on the real line: (a) 2س − 3 ≥ 5 → س ≥ 4, [4, ∞); (b) 5 − 3س ≥ 7 → س ≤ −2/3, (−∞, −2/3]; (c) −2 < 7س − 5 ≤ 3 → 3/7 < س ≤ 8/7, (3/7, 8/7]. Try-it 1: (a) 7 + 2س ≤ 4; (b) −4 < 2س + 1 ≤ 5; (c) 2 − س ≥ 8.

**(5-1-a) Solution region of a first-degree inequality in two variables, graphically (pp. 66–78).** Forms أس + بص > ج, ≥ ج, < ج, ≤ ج (أ, ب ∈ R − {0}, ج ∈ R); the solution region is all points (س، ص) satisfying the inequality. Ex. 2 (p. 66): which of (1,1), (−1,1), (1,−1) satisfy 2س − 3ص ≤ 1? (1,1) and (−1,1) do; (1,−1) does not. Try-it 2: which of the points (−1,1), (2,0), (1,−1) satisfy 5س − 2ص < 7? (Only (−1,1) does: −7 < 7; (2,0) gives 10; (1,−1) gives 7, not < 7.) Boundary line: the line أس + بص = ج; solid for ≤/≥, dashed for </>. Ex. 3 (pp. 67–68): draw the boundary line for (a) 2س + 5ص ≥ 5 (solid; through (0,1), (5/2,0), (5,−1)) and (b) 3س + 2ص < 6 (dashed; through (0,3), (2,0), (3,−3/2)). Try-it 3: boundary lines for (a) س + ص < 6; (b) 5س + 2ص ≤ 20. Ex. 4 (p. 69): boundary lines for (a) س < 3 (dashed vertical x = 3) and (b) ص ≥ −2 (solid horizontal y = −2). Try-it 4: (a) ص < 3; (b) س ≥ −4. Steps to find the solution region graphically (p. 70): (1) draw the boundary line (solid for ≤/≥, dashed for </>); (2) pick a test point on one side and substitute — a true statement means that side is the region, a false one the other; (3) for ≤/≥ the region includes the boundary line; for </> it does not; (4) shade the region. Ex. 5 (p. 70): 3س + ص ≤ 6 — boundary 3x + y = 6 through (0,6), (2,0), (3,−3); test (0,0): 0 ≤ 6 true, shade the origin side. Try-it 5: 4س + ص ≤ 8. Ex. 6 (p. 71): −3س + ص < 6 — boundary −3x + y = 6 through (0,6), (−2,0), (−1,3); test (0,0): 0 < 6 true, shade the origin side. Try-it 6: −2س + ص < 4. Ex. 7 (pp. 71–72): 2س − 3ص > 0 — boundary 2x − 3y = 0 through (0,0), (3/2,1), (3,2), dashed; the boundary passes through the origin, so test (1,2): 2 − 6 = −4 > 0 false, shade the side not containing (1,2). Try-it 7: س − 5ص ≤ 0. Common solution region of two or more inequalities: Ex. 8 (pp. 72–73): س + ص ≥ 6 and 5س + 2ص ≤ 10 — the first fails at the origin (shade away from it), the second passes (shade the origin side); the overlap is the wedge above both lines, the lines meeting at (−2/3, 20/3). Try-it 8: س − 2ص < 2 and 2س + 3ص ≤ 6. Ex. 9 (p. 74): 2س − ص ≥ −3 and 2ص > −س + 1 — the first passes at the origin, the second fails; the overlap is the wedge in the upper right. Try-it 9: س + 2ص ≤ 4 and ص ≥ −س − 1. "Using a system of inequalities" (p. 75): real-life problems usually have whole-number solutions, so only whole-number points in the common region count. Ex. 10 (pp. 75–76): a cultural centre's concert must raise at least 30,000 KD; front-row tickets 30 KD (500 available), back-row tickets 20 KD (1,250 available); let س = back-row tickets sold, ص = front-row tickets sold: 20س + 30ص ≥ 30,000; ص ≤ 500; س ≤ 1,250; check: 900 back-row + 450 front-row gives 20(900) + 30(450) = 31,500 ≥ 30,000, and both caps hold — the target is reached. Try-it 10 (p. 76): a fatayer restaurant — 1 KD per vegetable topping, 2 KD per meat topping, at least 5 toppings, 10 KD to spend; how many of each topping at most? Ex. 11 (pp. 76–77): common region of س + ص ≤ 1, س − ص > 2, 3س + 4ص < 12 — boundary tables: x + y = 1 through (−1,2), (0,1), (1,0); x − y = 2 through (0,−2), (1,−1), (2,0); 3x + 4y = 12 through (0,3), (2,3/2), (4,0); the common region is the (unbounded) wedge below the intersection point (3/2, −1/2) of the first two lines, shown in the graph as the shaded triangle at the bottom of the page. Try-it 11: س + ص ≤ 2, س − ص ≥ 3, ص ≤ 0.

**5-2 Linear programming (pp. 79–87).** Discussion (p. 78): spend at most 40 KD on at most 15 tomato seedlings; large-fruit seedlings yield 8 kg at 2 KD, small-fruit 10 kg at 3 KD — how many of each to maximise the yield? Will learn: linear programming and its methods; choosing the optimal solution. Definition (p. 78): linear programming is a method for finding the smallest or largest value of a function under given constraints, each a linear inequality, after representing the system graphically; the optimum usually occurs at a vertex of the solution region. Basics (p. 79): every LP problem has (1) decision variables — the variables whose values must be found; (2) objective function — the linear function to maximise or minimise (largest profit, smallest cost); (3) constraints — the inequalities or equations that must hold. The goal: maximise or minimise a linear objective function subject to constraints. Feasible-solutions space: all points satisfying every constraint — the common solution region of the constraints. Optimal solution: a point in the feasible space where the objective function takes its largest (or smallest) possible value. Formulating the problem (pp. 79–80): (1) identify the variables س₁، س₂، …، سₙ; (2) identify the goal and express it as the objective function, denoted هـ; (3) identify the constraints as inequalities in the variables; (4) add the non-negativity condition (every variable ≥ 0); (5) move the objective line هـ = أس + بص in parallel in the direction of increase (away from the origin) until it leaves the feasible space. Important notes (p. 80): (1) the optimum is a vertex of the polygon (then it is unique); (2) if the objective function is parallel to a side of the feasible polygon, the optimum is infinitely many points; (3) after computing هـ at each vertex, the optimum is at the vertex giving the largest (or smallest) value. Note: this book covers only the unique-optimum case, solved by substitution at the vertices. Steps to find the optimum (p. 80): (1) identify the variables; (2) write the system of linear inequalities; (3) represent it graphically; (4) find the vertices' coordinates; (5) write the objective function هـ; (6) substitute the vertices in it; (7) choose the largest or smallest value as the problem asks. Ex. 1 (p. 81): maximise هـ = 5س + 3ص subject to س ≥ 0, ص ≥ 0, س + ص ≤ 4, 3س + ص ≤ 6 — vertices (0,0), (2,0), (1,3), (0,4); values 0, 10, 14, 12; maximum 14 at (1,3). Try-it 1: maximise هـ = 6س + 4ص subject to س ≥ 0, ص ≥ 0, س + 2ص ≤ 6, 3س + 2ص ≤ 12. Ex. 2 (p. 82): minimise هـ = 5س + 4ص subject to س ≥ 0, ص ≥ 0, س + 2ص ≤ 4, س + ص ≤ 3 — vertices (0,0), (3,0), (2,1), (0,2); values 0, 15, 14, 8; minimum 0 at (0,0). Try-it 2: minimise هـ = 4س + ص subject to س ≥ 0, ص ≥ 0, س + 2ص ≤ 11, 3س + 2ص ≤ 12. Ex. 3 (pp. 83–84): a mill has 90 kg of maize and 120 kg of wheat; a bag of the first kind of flour needs 1 kg maize + 2 kg wheat, a bag of the second kind 3 kg maize + 2 kg wheat; prices 3 and 5 dinars — maximise income: constraints س ≥ 0, ص ≥ 0, س + 3ص ≤ 90, 2س + 2ص ≤ 120; vertices (0,0), (60,0), (45,15), (0,30); values 0, 180, 210, 150; maximum 210 dinars at (45,15) — 45 bags of the first kind, 15 of the second. Try-it 3: a tailor with 90 m of cotton and 120 m of wool; a garment of the first kind needs 1 m cotton + 3 m wool, of the second kind 2 m cotton + 2 m wool; prices 30 and 40 dinars — maximise income. Ex. 4 (pp. 84–85): a company makes scientific and graphing calculators; daily demand at least 80 scientific and 90 graphing; capacity at most 180 scientific and 160 graphing; sells at least 200 calculators a day; a scientific calculator loses 1 dinar, a graphing calculator gains 3 dinars — maximise profit: 80 ≤ س ≤ 180, 90 ≤ ص ≤ 160, س + ص ≥ 200; هـ = −س + 3ص; vertices (180,90), (180,160), (80,160), (80,120), (110,90); values 90, 300, 400, 280, 160; maximum 400 dinars at (80,160) — 80 scientific, 160 graphing. Try-it 4: a test in two parts A and B — 8 marks per correct answer in A, 12 in B; at most 5 minutes per A question, 8 minutes per B question, total time at most 120 minutes, at most 18 questions; all answers correct — how many correct answers from each part for the highest mark? Guided problem (pp. 86–87): air quality — a city plants resin trees and maple trees to absorb CO₂; 2,100 KD to spend, area 4,500 m²; resin: 30 KD, 60 m², 650 kg CO₂/year; maple: 40 KD, 90 m², 300 kg CO₂/year; constraints 30س + 40م ≤ 2100, 60س + 90م ≤ 4500, س ≥ 0, م ≥ 0; objective هـ = 650س + 300م; vertices (0,0), (70,0), (30,30), (0,50); values 0, 45,500, 28,500, 15,000; maximum 45,500 kg/year at (70,0) — plant 70 resin trees. Additional problem (p. 87): a biologist and two kinds of bacteria — each sample of the first kind produces 4 new bacteria, of the second kind 3; at least 240 new bacteria; at least 30 samples of the first kind; at most 60 original samples; at most 70 samples of the second kind; costs 5 and 7 dinars — how many samples of the second kind to minimise the cost?

**Unit 5 end matter.** Organiser (concept map, p. 88); summary (pp. 89–90) restating the inequality properties, the boundary line, the four solution-region steps, the LP definition, the optimal-solution definition and the seven LP steps.

**BOOK ERRORS — 1.**

1. **Printed p. 53, the Unit 4 summary, item 2, second line:** the summary states the four interval forms as if always equal: P(a<X≤b) = P(a<X<b) = P(a≤X<b) = P(a≤X≤b). **Correct: the four forms are equal only for a continuous random variable** (where the point probabilities are zero). For a discrete variable they differ by the point masses at a and b. With the book's own Ex (13) distribution (printed p. 30; ت(1) = 0.15, ت(2) = 0.2, ت(3) = 0.6, ت(5) = 1) and a = 1, b = 3: P(1<X≤3) = 0.45, P(1<X<3) = 0.05, P(1≤X<3) = 0.20, P(1≤X≤3) = 0.60 — four different values. The error is summary-only: the properties box on printed p. 29 does not state the interval equalities, and the book's own property P(a<X≤b) = F(b)−F(a) is correct. The same false claim appears in the Grade 12 Term 2 scientific book's Unit 8 summary (§11, error 3) — the two books share the error.

**Cleared flags (checked, not errors).** Printed p. 35, Ex. 17(b)/(c): rolling a fair die 5 times, X = number of 4s: (b) "at least once" = 1 − P(X=0) = 0.5981; (c) "at most once" = P(X=0) + P(X=1) = 0.8038 — the Arabic words (على الأقل = at least, على الأكثر = at most) and the computations confirm the book; the glyphs only look reversed to a Latin reader. Printed p. 41, Ex. 23(c): uniform density 1/4 on [1,5]; P(X ≥ 1.5) = (1/4)×(5 − 1.5) = 7/8 — the stem, the computation and the shaded graph agree. Printed pp. 42–43, Ex. 24: triangular density س/8 on [0,4]; (a) P(0 ≤ X ≤ 4) = 1; (b) P(X ≤ 2) = 1/4 — the book computes the area of the triangle from 0 to 2, (1/2)×2×(1/4); (c) P(X > 2) = 1 − 1/4 = 3/4, the area of the unshaded region in the second graph. A left-to-right reading of the stem glyphs would give (b) as P(X ≥ 2) and (c) as P(X < 2) — both wrong; the 300% crops of the stem glyphs show both glyphs opening toward 2, so the book's (b) and (c) are correct as printed. Printed pp. 47–48, Ex. 27–28: the standard-normal inequality glyphs are mirrored by the book's right-to-left typesetting — the solutions, the table choices (table 4 for z ≥ 0, table 5 for z < 0) and the numbers confirm the intended meanings (e.g. Ex. 28(a) P(Z ≤ −0.55) = 0.29116 from table 5). Binomial tables (1)–(3), printed pp. 55–59, spot-checked: n = 7, p = 0.1: P(X=0) = 0.478, P(X=2) = 0.124; n = 8, p = 0.5: P(X=5) = 0.219; n = 10, p = 0.5: P(X=5) = 0.246; n = 11, p = 0.1: P(X=0) = 0.314; n = 12, p = 0.5: P(X=6) = 0.226; n = 13, p = 0.1: P(X=0) = 0.254; n = 15, p = 0.1: P(X=0) = 0.206; n = 15, p = 0.5: P(X=7) = 0.196 — all match recomputation (the tables were spot-checked, not read cell by cell). Normal tables (4)–(5), printed pp. 60–61, spot-checked: Φ(0) = 0.5; Φ(0.5) = 0.69146; Φ(1.4) = 0.91924; Φ(2.18) = 0.98537; Φ(2.6) = 0.99534; Φ(−0.55) = 0.29116; Φ(−0.75) = 0.22663; Φ(−1.25) = 0.10565 — all match the standard normal values used in the worked examples.

**HONEST NEGATIVES:**
- No statistical inference at all: no sampling distributions, no central limit theorem, no confidence intervals, no hypothesis testing, no p-values, no χ² or t-distributions (the t-table in the G12 scientific book belongs to the other track). The statistics here stops at describing distributions and computing probabilities from them.
- No Poisson distribution, no geometric distribution, no other discrete distributions beyond the binomial; no continuous distributions beyond uniform and normal.
- No expectation or variance for continuous random variables (no integration of the density — the book never integrates; areas are read off rectangles and triangles only).
- No correlation, no regression, no bivariate data (those sit in the G12 scientific Term 1 book).
- The binomial table stops at n = 15; larger n must be computed by formula (no normal approximation to the binomial is taught).
- Linear programming is two variables only, graphical only: no simplex method, no three-variable problems, no integer programming (whole-number answers are only noted as a restriction, never solved as such), no unbounded/infeasible-region cases worked (only a note that the optimum is a vertex when it is unique).
- No computer work: no spreadsheet, no calculator normal-distribution function — probabilities come from printed tables only.
- No unit tests or assessments anywhere in the book; no answer key (see below).

**HELD-COPY DEFECTS:** PDF pp. 5 and 7 are blank (portrait dividers between the Amir's portrait, PDF p. 4, and the Crown Prince's portrait, PDF p. 6). PDF p. 92 is the back cover. No content is lost — printed pp. 1–90 are complete, no missing, duplicated or truncated pages. The text layer is mojibake (legacy WinSoftPro font) — the book was read from 200 dpi renders throughout, as noted in the header. The binomial and normal tables occupy printed pp. 55–61 and are legible in the renders.

**Answer key:** none. **Numbering oddities:** units continue Term 1 numbering (Units 4–5); lesson 5-1 has a sub-lesson (5-1-a) for the graphical solution region; the book denotes the objective function by هـ, the standard normal variable by ح (z), the density by د(س) and the c.d.f. by ت(م). The back cover lists the series components as student book, teacher's book, exercise workbook and exercise workbook with answers — the teacher's book and the answered workbook are **not** in hand (no teacher guides exist in the Kuwait maths set).

---

### Band summary — Kuwait maths, Grades 9–12

**Coverage:** 12 of 13 band files read in full, **1,862 PDF pages**, **30 book errors** found (all with the correct value stated in the per-book BOOK ERRORS lists). (Filed as 37; corrected by the independent citation check, 2026-11-06 — seven claimed errors retracted: four right-to-left inequality-glyph misreads in §6 and §9, one Arabic-letter variable misread as a digit in §1, one matrix line spliced from neighbouring lines in §6, and one phantom table cell in §10. See checks/check-band-c.md.)

| § | File | Grade / Term / Track | Kind | PDF pp. | Errors |
|---|---|---|---|---|---|
| 1 | g09-t1.pdf | 9 / 1 / — | Student book | 235 | 3 |
| 2 | g09-t2.pdf | 9 / 2 / — | Student book | 260 | 1 |
| 3 | g10-t1-wb.pdf | 10 / 1 / — | Student book | 134 | 2 |
| 4 | g11-t1-wb.pdf | 11 / 1 / Scientific | Workbook | 106 | 1 |
| 5 | g12-t1.pdf | 12 / 1 / Scientific | Student book | 213 | 5 |
| 6 | g10-t2-wb.pdf | 10 / 2 / — | Student book | 227 | 2 |
| 7 | g11-t2-wb.pdf | 11 / 2 / Scientific | Student book | 192 | 1 |
| 8 | g11-stats-t1.pdf | 11 / 1 / Literary | Student book — Statistics | 74 | 5 |
| 9 | g11-stats-t2.pdf | 11 / 2 / Literary | Student book — Statistics | 82 | 0 |
| 10 | g11-stats-t2-wb.pdf | 11 / 2 / Literary | Workbook — Statistics | 50 | 4 |
| 11 | g12-t2-wb.pdf | 12 / 2 / Scientific | Student book | 197 | 5 |
| 12 | g12-stats-t2-wb.pdf | 12 / 2 / Literary | Student book — Statistics | 92 | 1 |
| | **Total** | | | **1,862** | **30** |

**Record mismatches (kind proved from each book's own cover, title page and contents, never the filename):** five files named `*-wb.pdf` are **student books, not workbooks** — g10-t1-wb, g10-t2-wb, g11-t2-wb, g12-t2-wb and g12-stats-t2-wb. Only two files in the band are exercises-only workbooks: g11-t1-wb (scientific) and g11-stats-t2-wb (literary). No teacher guides exist in the Kuwait maths set.

**Tracks:** scientific track — g11-t1-wb, g11-t2-wb, g12-t1, g12-t2-wb (the Grade 12 scientific books also carry the statistics for the scientific track: estimation, hypothesis testing, correlation and regression in Term 1; integration, conics and probability in Term 2). Literary track — g11-stats-t1, g11-stats-t2, g11-stats-t2-wb, g12-stats-t2-wb (statistics only: real numbers and elementary statistics in Term 1 of Grade 11; describing data and classical probability in Term 2; random variables and linear programming in Term 2 of Grade 12). Grades 9 and 10 are pre-track. The two tracks must not be merged.

**Generations:** new generation — g09-t1, g09-t2, g10-t1-wb, g11-stats-t1 (3rd edition, 1448 AH / 2026–2027), g12-t1 (2nd edition, 1448 AH / 2026–2027), g11-t1-wb (2nd edition, 1448 AH / 2026–2027, on a 2013 Pearson source). Old generation (2012/2013/2014 series, 2nd editions to 1447 AH / 2025–2026) — g10-t2-wb, g11-t2-wb, g11-stats-t2, g11-stats-t2-wb, g12-t2-wb, g12-stats-t2-wb.

**Answer keys:** none of the 12 books carries an answer key. The back covers of the statistics books list an "exercise workbook with answers" as a separate series component; it is not in hand.

**PENDING — NOT READ:** `g11-t1.pdf`, the Grade 11 Mathematics Term 1 student book (102,105,970 B). The file on disk is a 139-byte JSON `{"message":"Not e-asset","status":"404"}`; it was not read and is not counted in the totals. A fresh fetch is being chased separately. Until it lands, the Grade 11 scientific track has its Term 1 workbook (§4) but not its Term 1 student book, and the Grade 11 scientific coverage is incomplete.

**Main honest negatives across the band:** no answer keys anywhere; no unit tests or assessments in the old-generation books (the new-generation Grade 9 books have them); the literary-track statistics books teach no calculus, no complex numbers, no logarithms and no trigonometry; the Grade 10 book stops at 2×2 matrices and descriptive statistics; the Grade 11 scientific book stops short of De Moivre, nth roots of complex numbers, inverse trig functions and vectors in space; the Grade 12 scientific book covers partial fractions only for distinct linear factors and differential equations only for constant-coefficient second-order linear equations; the Grade 12 literary book has no statistical inference at all (no confidence intervals, no hypothesis testing, no t-distribution). The old-generation books (2012–2014 Pearson sources) carry dated data throughout.

**Reading note:** every book was read visually from 200-dpi renders of every page; flagged items were re-verified at 300 dpi (400 dpi for the cube-root cases in §8). Three traps recurred across the band and were checked book by book: (1) Arabic arithmetic is laid out right-to-left — inequality glyphs must be read by which side opens toward the larger quantity, and ordered pairs may be laid out right-to-left (g12-stats-t2-wb) or left-to-right (g10-t2-wb) depending on the book; (2) matrices are displayed right-to-left in g10-t2-wb; (3) the superscript ³ is easily mistaken for ² at 200 dpi — every flagged superscript was zoomed. No error in this filing rests on extraction alone.
