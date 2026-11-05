# Vietnam — Mathematics (Kết nối tri thức với cuộc sống, NXBGD)

READ COMPLETE. Files in hand (reconciled against the record):
**28 files / 28 distinct works — 27 student books + 1 workbook**,
all in Vietnamese, Grades 1–12, **3,344 PDF pages** in total.
Anchors: **504 (504 passed, 0 corrected in check, 0 not found)** —
18 per distinct work. No distinct work is owed: the record's
"30" overcounts by two phantom rows that duplicate held books
(see record corrections 1–2 below).

## The set at a glance

- Grades 1–5: two student volumes each (10 books), primary
  structure: Chủ đề (themes) with Bài lessons, Luyện tập chung
  practice sets, Ôn tập revisions, term glossaries.
- Grade 6: two student volumes + the set's only workbook
  (Bài tập Toán 6, Tập Hai only). Secondary structure begins:
  Chương (chapters) with Bài lessons, Luyện tập chung,
  Bài tập cuối chương, closing Hoạt động thực hành trải nghiệm,
  and term tables in every book.
- Grades 7–9: two student volumes each (6 books), chapters I–X
  per grade in continuous Bài numbering.
- Grades 10–12: two student volumes + one Chuyên đề học tập
  (study-topics) volume each (9 books). No track split: one
  student book per volume plus one enrichment volume per grade.
- Language: Vietnamese throughout. Publisher throughout: Nhà
  xuất bản Giáo dục Việt Nam (NXBGD), under the Ministry of
  Education and Training (Bộ Giáo dục và Đào tạo) header.
  Series throughout: "Kết nối tri thức với cuộc sống"
  (Connecting Knowledge to Life).
- Held-copy defects: the Grade 6 workbook is a third-party
  Blogtailieu.com scan, watermarked on every page (content
  otherwise complete). Government student books carry a faint
  "KẾT NỐI TRI THỨC VỚI CUỘC SỐNG" watermark across covers.
  No missing-page defect was found in any book's
  contents-vs-body checks.

## Reconciliation and record corrections

Proved from the secured library (GitHub releases + tree) in
both directions — record → files, and files → record — and
from the books themselves. Full evidence:
liqlearns-courses-work/vietnam-maths/set-verification.md.

1. **The record's "30 in hand (30 student)" is wrong; the true
   count is 28 files / 28 distinct works.** The TSV holds 33
   rows for Vietnam Mathematics but only 30 unique URLs: Grade 4
   volumes 1–2 and the Grade 6 workbook volume 2 are each listed
   twice. Of those 30 unique URLs, 2 do not resolve to any file.
2. **Two phantom rows: Grade 1 approved-private mathematics
   volumes 1–2 do not exist.** Their tree URLs return HTTP 404;
   the directory grade-01/approved-private/vietnam/mathematics
   does not exist; its parent holds only APPROVED_LIST.md,
   CURRICULUM.md and an EMPTY books.json (0 books). This is the
   same phantom pattern as the English phase (Grade 1
   approved-private English full-year also 404). No distinct
   work is lost: the phantom rows duplicate the Grade 1
   government release copies of exactly the same two volumes,
   which ARE in hand byte-exact. There is no second holding to
   hash-compare — the dual-holding question dissolves.
3. **The queue row's "30 student" is wrong twice over:** it
   counts the 2 phantom files, and it folds the 1 workbook into
   the student count. True split: 27 student books + 1 workbook.
4. **Grade 10 grab correction:** the TSV Grade 10 URLs point at
   release tag `mid-size-books`, not `mid-size-books-2` as first
   assumed; the first grab returned ASSET-NOT-FOUND for all
   three Grade 10 files and the re-grab from `mid-size-books`
   landed all three byte-exact.
5. **Sourcing split (no title missing, none misfiled, no extra
   maths file in tree or releases):** 24 government release
   assets + 4 tree files = 28. Grade 4 mathematics exists ONLY
   as approved-private tree copies (no government release copies
   for Grade 4 maths). Grade 2 is split: volume 1 tree-only,
   volume 2 government-only. Release tags hold no other
   `vietnam-mathematics` asset; tree maths folders hold no file
   outside the TSV list.
6. **No teacher guides in the set; no workbooks except Grade 6
   volume 2.** Volume 1 of that workbook is not in the record
   at all and not in the tree. No separate Grade 10–12 track
   books exist in this series — Grades 10–12 are single books
   plus a study-topics volume each, verified from their
   contents (see the Grade 10–12 structure note in Band D).

## Languages, publisher, editions

- Author teams change across the series (general editor Hà Huy
  Khoái throughout). Primary (Grades 1–5): Hà Huy Khoái with Lê
  Anh Vinh (editor) and the primary team (Nguyễn Áng, Vũ Văn
  Dương, Nguyễn Minh Hải, Bùi Bá Mạnh; Hoàng Quế Hương joins
  from Grade 2). Grade 6–7: Nguyễn Huy Đoan (editor) with the
  secondary team. Grade 8–9: Cung Thế Anh and Nguyễn Huy Đoan
  (co-editors). Grades 10–12: Cung Thế Anh, Trần Văn Tấn,
  Đặng Hùng Thắng (co-editors) with a new team; study books
  carry smaller teams under the same general editor.
- Reprint lines as printed on title pages (where verified):
  Grade 1 both volumes 6th reprint; Grade 2 volume 1 1st
  reprint, volume 2 5th reprint; Grade 3 both volumes 4th
  reprint; Grade 6 student volumes 5th reprint; Grade 7 both
  volumes 4th reprint; Grade 8 both volumes 3rd reprint;
  Grade 9 both volumes 2nd reprint; Grade 10 both student
  volumes and study book 4th reprint; Grade 11 both student
  volumes and study book 3rd reprint; Grade 12 both student
  volumes and study book 2nd reprint. Grade 4/5 reprint lines
  were not captured; their appraisal decisions were: Grade 4,
  Decision 1908/QĐ-BGDĐT, 11 July 2022; Grade 5, Decision
  1963/QĐ-BGDĐT, 5 July 2023; Grade 11, Decision 2026/QĐ-BGDĐT,
  21 July 2022; Grade 12, Decision 1882/QĐ-BGDĐT, 29 June 2023
  (all MoET National Textbook Appraisal Council).
- ISBNs were NOT captured: imprint pages (ISBN, book code,
  registration) were not part of this read's evidence beyond
  title-page team/reprint lines and appraisal decisions. No
  ISBN is stated anywhere below; this is the read's one
  bibliographic gap and does not affect any lesson filing.

## Page rules

- Printed = PDF − 1 for all Grade 1–10 student books and the
  Grade 6 workbook (cover = PDF 1). Verified repeatedly, e.g.
  G1 v1 Bài 1 printed p. 8 = PDF 9 (folio visible); G3 v1
  Bài 37 printed p. 99 = PDF 100 (folio visible); G6 workbook
  Bài 23 printed p. 4 = PDF 5 (opener-verified).
- Printed = PDF − 2 for the Grade 10 study book and all Grade
  11 and Grade 12 books (extra front-matter page: the appraisal-
  council page and/or how-to-use page). Verified per book from
  contents folios against PDF pages, e.g. G11 v1 Bài 1 printed
  p. 5 = PDF 7; G12 v2 Bài 11 printed p. 4 = PDF 6.
- Vietnamese terms kept where they carry meaning: Bài = lesson;
  Chủ đề = theme (primary); Chương = chapter (secondary);
  Chuyên đề = study topic; Tập Một/Hai = Volume 1/2;
  Luyện tập chung = general practice; Ôn tập = revision;
  Bài tập cuối chương/chuyên đề = end-of-chapter/topic
  exercises; Hoạt động thực hành trải nghiệm = hands-on
  experience activities; Bảng tra cứu thuật ngữ / Bảng giải
  thích thuật ngữ = term lookup / term explanation tables.

## Method note

Student books are image-only PDFs (a text layer, where present,
carries only watermarks); they were read from rendered pages,
never from extracted text. Contents (Mục lục) transcribed in
full per book; lesson titles below are the reader's plain-
English renderings of the contents titles, not transcriptions
of lesson text. Chapter/theme openers were OCR-checked and
last pages checked; ambiguous contents rows were verified
visually on the lesson opener. Secondary contents pages are
two-column: where OCR interleaved the columns (Grade 6
contents, and several primary contents lines), the visually
read contents page settles the numbers — every such case is
flagged in place. No word-for-word transcription: own summaries
and structural notes, only very short quoted fragments.

## Proven gaps (whole set)

- No teacher guides in hand for any grade (the set is student
  books + one workbook only).
- No Grade 6 workbook volume 1 (not in the record or the tree).
- No Grade 1 approved-private copies distinct from the
  government copies (the tree rows are phantoms; see
  correction 2).
- Content ceilings, proven grade by grade below: no negative
  numbers before Grade 6; no equations as a topic before
  Grade 8; no functions before Grade 8 (first-degree) and no
  trigonometry beyond acute-angle ratios before Grade 10
  (general-triangle rules); no logarithms/exponentials before
  Grade 11 volume 2; no derivatives before Grade 11 volume 2
  (second order only); no integrals before Grade 12 volume 2;
  no conditional probability/Bayes before Grade 12 volume 2;
  no complex numbers, matrices, differential equations, or
  continuous distributions anywhere in Grades 1–12; random
  variables and distributions appear ONLY in the Grade 12
  study book (discrete + binomial).

# Band A — Grades 1–4 (8 files, 1,026 PDF pages)

## GRADE 1 — Toán 1, Tập Một + Tập Hai (Kết nối tri thức, NXBGD)

Authors (title page, both vols): Hà Huy Khoái (general editor),
Lê Anh Vinh (editor), Nguyễn Áng, Vũ Văn Dương, Nguyễn Minh Hải,
Bùi Bá Mạnh. "Tái bản lần thứ sáu" (6th reprint) on both title
pages. MoET header + NXBGD imprint on covers. Characters: robot
Rô-bốt with Mi, Nam, Mai, Việt. Lesson shape throughout: Khám phá
(discover) → Hoạt động (activity) → Luyện tập (practice), with
games ("Trò chơi") closing many lessons. Contents pp. 4–5 (v1),
pp. 4–5 (v2, second contents page headed by theme 5).

### G1 v1 — 118 PDF pp., printed pp. 1–116 + covers (Bài 1–20)

- Theme 1 — CÁC SỐ ĐẾN 10 (Numbers to 10), p. 6: Tiết học đầu
  tiên (First lesson: meeting Rô-bốt and friends), p. 6; Bài 1
  Các số 0, 1, 2, 3, 4, 5 (counting fish in bowls, cubes, writing
  the digits; 0 as empty bowl), p. 8; Bài 2 Các số 6, 7, 8, 9, 10,
  p. 14; Bài 3 Nhiều hơn, ít hơn, bằng nhau (more/fewer/equal),
  p. 20; Bài 4 So sánh số (comparing numbers), p. 24; Bài 5
  Mấy và mấy (how many and how many — combining groups), p. 32;
  Bài 6 Luyện tập chung, p. 38.
- Theme 2 — LÀM QUEN VỚI MỘT SỐ HÌNH PHẲNG (Getting to know some
  plane shapes), p. 46: Bài 7 Hình vuông, hình tròn, hình tam giác,
  hình chữ nhật (square, circle, triangle, rectangle), p. 46;
  Bài 8 Thực hành lắp ghép, xếp hình (hands-on assembling and
  arranging shapes), p. 50; Bài 9 Luyện tập chung, p. 54.
- Theme 3 — PHÉP CỘNG, PHÉP TRỪ TRONG PHẠM VI 10 (Addition and
  subtraction within 10), p. 56: Bài 10 Phép cộng trong phạm vi 10,
  p. 56; Bài 11 Phép trừ trong phạm vi 10, p. 68; Bài 12 Bảng cộng,
  bảng trừ trong phạm vi 10 (addition/subtraction tables), p. 80;
  Bài 13 Luyện tập chung, p. 86.
- Theme 4 — LÀM QUEN VỚI MỘT SỐ HÌNH KHỐI (Getting to know some
  solid shapes), p. 92: Bài 14 Khối lập phương, khối hộp chữ nhật
  (cube, rectangular box), p. 92; Bài 15 Vị trí, định hướng trong
  không gian (position and orientation in space: above/below,
  left/right, in front/behind), p. 96; Bài 16 Luyện tập chung,
  p. 100.
- ÔN TẬP HỌC KÌ 1 (Term 1 revision), p. 102: Bài 17 Ôn tập các số
  trong phạm vi 10, p. 102; Bài 18 Ôn tập phép cộng, phép trừ
  trong phạm vi 10, p. 106; Bài 19 Ôn tập hình học, p. 110;
  Bài 20 Ôn tập chung, p. 112. Glossary "Một số thuật ngữ dùng
  trong sách", p. 114.

G1 v1 honest negatives: no numbers above 10; no two-digit
numbers, no place value beyond counting to 10; no measurement
(length/mass/time/money), no data handling; addition/subtraction
are within 10 only, with tables (Bài 12) but no column method;
shapes are recognition and assembly only (no sides/vertices
counted as properties in the contents titles).

### G1 v2 — 110 PDF pp. (Bài 21–41)

- Theme 1 — CÁC SỐ ĐẾN 100 (Numbers to 100), p. 6: Bài 21 Số có
  hai chữ số (two-digit numbers: tens and ones with tomatoes —
  10 tomatoes = 1 ten; reading/writing 11–20), p. 6; Bài 22 So
  sánh số có hai chữ số (comparing two-digit numbers), p. 16;
  Bài 23 Bảng các số từ 1 đến 100 (the 1–100 number table),
  p. 22; Bài 24 Luyện tập chung, p. 24.
- Theme 2 — ĐỘ DÀI VÀ ĐO ĐỘ DÀI (Length and measuring length),
  p. 28: Bài 25 Dài hơn, ngắn hơn (longer, shorter), p. 28;
  Bài 26 Đơn vị đo độ dài (units of length — the non-standard
  then standard introduction; see anchor), p. 32; Bài 27 Thực
  hành ước lượng và đo độ dài (practising estimating and
  measuring length), p. 36; Bài 28 Luyện tập chung, p. 40.
- Theme 3 — PHÉP CỘNG, PHÉP TRỪ (không nhớ) TRONG PHẠM VI 100
  (Addition/subtraction WITHOUT regrouping within 100), p. 44:
  Bài 29 Phép cộng số có hai chữ số với số có một chữ số, p. 44;
  Bài 30 Phép cộng số có hai chữ số với số có hai chữ số, p. 48;
  Bài 31 Phép trừ số có hai chữ số cho số có một chữ số, p. 52;
  Bài 32 Phép trừ số có hai chữ số cho số có hai chữ số, p. 58;
  Bài 33 Luyện tập chung, p. 64.
- Theme 4 — THỜI GIAN, GIỜ VÀ LỊCH (Time, hours and calendar),
  p. 72: Bài 34 Xem giờ đúng trên đồng hồ (telling the time
  exactly on the clock), p. 72; Bài 35 Các ngày trong tuần
  (days of the week), p. 76; Bài 36 Thực hành xem lịch và giờ
  (practising reading the calendar and clock), p. 80; Bài 37
  Luyện tập chung, p. 84.
- ÔN TẬP CUỐI NĂM (End-of-year revision), p. 88: Bài 38 Ôn tập
  các số và phép tính trong phạm vi 10, p. 88; Bài 39 Ôn tập các
  số và phép tính trong phạm vi 100, p. 94; Bài 40 Ôn tập hình
  học và đo lường, p. 100; Bài 41 Ôn tập chung, p. 104.
  Glossary p. 106.

G1 v2 honest negatives: addition/subtraction within 100 are
WITHOUT regrouping only ("không nhớ" in the theme title) — no
carrying/borrowing in Grade 1; no multiplication or division;
no fractions, decimals, mass, capacity or money; time is clock
reading and days/calendar only (no minutes-to-the-hour work in
the titles; Bài 34 is "exact hours" — verify in anchor).

### GRADE 1 summary

41 lessons (Bài 1–41) across the year, numbered continuously
across volumes. Arc: 0–10 → plane shapes → +/− within 10 →
solids/position → revision; then two-digit numbers to 100 →
length → +/− within 100 without regrouping → time/calendar →
final revision. Counting, comparing and the number table are the
spine; every theme ends in Luyện tập chung and each term in
Ôn tập.

## GRADE 2 — Toán 2, Tập Một + Tập Hai

Authors (v1 title page): Hà Huy Khoái (general editor), Lê Anh
Vinh (editor), Nguyễn Áng, Vũ Văn Dương, Nguyễn Minh Hải,
Hoàng Quế Hương, Bùi Bá Mạnh. (v2 title page confirmed: same team; 5th reprint.)

### G2 v1 — 142 PDF pp. (Bài 1–36)

- Theme 1 — ÔN TẬP VÀ BỔ SUNG (Revision and supplement),
  p. 6: Bài 1 Ôn tập các số đến 100, p. 6; Bài 2 Tia số. Số liền
  trước, số liền sau (number ray; predecessor and successor),
  p. 10; Bài 3 Các thành phần của phép cộng, phép trừ
  (components of addition/subtraction: addends/sum,
  minuend/subtrahend/difference), p. 13; Bài 4 Hơn, kém nhau bao
  nhiêu (how many more/fewer), p. 16; Bài 5 Ôn tập phép cộng,
  phép trừ (không nhớ) trong phạm vi 100, p. 19; Bài 6 Luyện
  tập chung, p. 23.
- Theme 2 — PHÉP CỘNG, PHÉP TRỪ TRONG PHẠM VI 20, p. 26:
  Bài 7 Phép cộng (qua 10) trong phạm vi 20 (addition crossing
  10), p. 26; Bài 8 Bảng cộng (qua 10), p. 33; Bài 9 Bài toán
  về thêm, bớt một số đơn vị (word problems: adding/removing
  some units), p. 36; Bài 10 Luyện tập chung, p. 38; Bài 11
  Phép trừ (qua 10) trong phạm vi 20, p. 41; Bài 12 Bảng trừ
  (qua 10), p. 47; Bài 13 Bài toán về nhiều hơn, ít hơn một
  số đơn vị (more/fewer word problems), p. 50; Bài 14 Luyện
  tập chung, p. 53.
- Theme 3 — LÀM QUEN VỚI KHỐI LƯỢNG, DUNG TÍCH (Getting to know
  mass and capacity), p. 57: Bài 15 Ki-lô-gam, p. 57; Bài 16
  Lít, p. 62; Bài 17 Thực hành và trải nghiệm với các đơn vị
  ki-lô-gam, lít (hands-on experience with kg and litre),
  p. 66; Bài 18 Luyện tập chung, p. 70.
- Theme 4 — PHÉP CỘNG, PHÉP TRỪ (có nhớ) TRONG PHẠM VI 100
  (Addition/subtraction WITH regrouping within 100), p. 72:
  Bài 19 Phép cộng (có nhớ) số có hai chữ số với số có một chữ
  số, p. 72; Bài 20 Phép cộng (có nhớ) số có hai chữ số với số
  có hai chữ số, p. 76 (contents OCR garbled here; title
  confirmed by pattern + anchor check); Bài 21 Luyện tập chung,
  p. 80; Bài 22 Phép trừ (có nhớ) số có hai chữ số cho số có
  một chữ số, p. 83; Bài 23 Phép trừ (có nhớ) số có hai chữ số
  cho số có hai chữ số, p. 89; Bài 24 Luyện tập chung, p. 95.
- Theme 5 — LÀM QUEN VỚI HÌNH PHẲNG (Getting to know plane
  shapes), p. 98: Bài 25 Điểm, đoạn thẳng, đường thẳng, đường
  cong, ba điểm thẳng hàng (point, segment, straight line,
  curve, three collinear points), p. 98; Bài 26 Đường gấp khúc.
  Hình tứ giác (broken line; quadrilateral), p. 102; Bài 27
  Thực hành gấp, cắt, ghép, xếp hình. Vẽ đoạn thẳng (folding,
  cutting, assembling, arranging shapes; drawing a segment),
  p. 106; Bài 28 Luyện tập chung, p. 110.
- Theme 6 — NGÀY – GIỜ, GIỜ – PHÚT, NGÀY – THÁNG (Day–hour,
  hour–minute, day–month), p. 112: Bài 29 Ngày – giờ, giờ – phút,
  p. 112; Bài 30 Ngày – tháng, p. 116; Bài 31 Thực hành và trải
  nghiệm xem đồng hồ, xem lịch (reading clocks and calendars),
  p. 119; Bài 32 Luyện tập chung, p. 122.
- Theme 7 — ÔN TẬP HỌC KÌ 1 (Term 1 revision), p. 124: Bài 33
  Ôn tập phép cộng, phép trừ trong phạm vi 20, 100, p. 124;
  Bài 34 Ôn tập hình phẳng, p. 129; Bài 35 Ôn tập đo lường,
  p. 132; Bài 36 Ôn tập chung, p. 135. Glossary p. 138.

### G2 v2 — 142 PDF pp. (Bài 37–75; themes 8–14, continuing v1's 1–7)

- Theme 8 — PHÉP NHÂN, PHÉP CHIA (Multiplication, division),
  p. 4: Bài 37 Phép nhân (multiplication as repeated addition:
  2 + 2 + 2 = 6 becomes 2 × 3 = 6; × is the multiplication sign),
  p. 4; Bài 38 Thừa số, tích (factors, product), p. 7; Bài 39
  Bảng nhân 2 (×2 table), p. 9; Bài 40 Bảng nhân 5, p. 12;
  Bài 41 Phép chia (division as sharing/grouping), p. 15;
  Bài 42 Số bị chia, số chia, thương (dividend, divisor,
  quotient), p. 18; Bài 43 Bảng chia 2, p. 21; Bài 44 Bảng chia
  5, p. 24; Bài 45 Luyện tập chung, p. 27.
- Theme 9 — LÀM QUEN VỚI HÌNH KHỐI (Getting to know solid
  shapes), p. 34: Bài 46 Khối trụ, khối cầu (cylinder, sphere),
  p. 34; Bài 47 Luyện tập chung, p. 37.
- Theme 10 — CÁC SỐ TRONG PHẠM VI 1 000 (Numbers within 1,000),
  p. 40: Bài 48 Đơn vị, chục, trăm, nghìn (ones, tens, hundreds,
  thousands), p. 40; Bài 49 Các số tròn trăm, tròn chục (round
  hundreds, round tens), p. 43; Bài 50 So sánh các Số tròn trăm,
  tròn chục, p. 47; Bài 51 Số có ba chữ số (three-digit numbers),
  p. 50; Bài 52 Viết Số thành tổng các trăm, chục, đơn vị
  (writing a number as a sum of hundreds, tens, ones), p. 55;
  Bài 53 So sánh các Số có ba chữ số, p. 58; Bài 54 Luyện tập
  chung, p. 61.
- Theme 11 — ĐỘ DÀI VÀ ĐƠN VỊ ĐO ĐỘ DÀI. TIỀN VIỆT NAM (Length
  and length units. Vietnamese money), p. 65: Bài 55 Đề-xi-mét.
  Mét. Ki-lô-mét (decimetre, metre, kilometre), p. 65; Bài 56
  Giới thiệu tiền Việt Nam (introducing Vietnamese money),
  p. 71; Bài 57 Thực hành và trải nghiệm đo độ dài, p. 73;
  Bài 58 Luyện tập chung, p. 75.
- Theme 12 — PHÉP CỘNG, PHÉP TRỪ TRONG PHẠM VI 1 000, p. 79:
  Bài 59 Phép cộng (không nhớ) trong phạm vi 1 000, p. 79;
  Bài 60 Phép cộng (có nhớ) trong phạm vi 1 000, p. 83; Bài 61
  Phép trừ (không nhớ) trong phạm vi 1 000, p. 87; Bài 62 Phép
  trừ (có nhớ) trong phạm vi 1 000, p. 91; Bài 63 Luyện tập
  chung, p. 97.
- Theme 13 — LÀM QUEN VỚI YẾU TỐ THỐNG KÊ, XÁC SUẤT (Getting to
  know statistics and probability elements), p. 100: Bài 64 Thu
  thập, phân loại, kiểm đếm Số liệu (collecting, classifying,
  counting data), p. 100; Bài 65 Biểu đồ tranh (picture charts),
  p. 102; Bài 66 Chắc chắn, có thể, không thể (certain, possible,
  impossible), p. 106; Bài 67 Thực hành và trải nghiệm thu thập,
  phân loại, kiểm đếm Số liệu, p. 108.
- Theme 14 — ÔN TẬP CUỐI NĂM (End-of-year revision), p. 110:
  Bài 68 Ôn tập các Số trong phạm vi 1 000, p. 110; Bài 69 Ôn
  tập phép cộng, phép trừ trong phạm vi 100, p. 113; Bài 70
  (title confirmed on the lesson opener: Ôn tập phép cộng,
  phép trừ trong phạm vi 1 000), p. 117; Bài 71
  Ôn tập phép nhân, phép chia, p. 122; Bài 72 Ôn tập hình học,
  p. 127; Bài 73 Ôn tập đo lường, p. 131; Bài 74 Ôn tập kiểm
  đếm Số liệu và lựa chọn khả năng, p. 134; Bài 75 Ôn tập chung,
  p. 136. Glossary p. 139.

G2 v2 honest negatives: multiplication/division tables are ONLY
×2, ×5, ÷2, ÷5 (no ×3/×4 tables in Grade 2); no fractions or
decimals; money is introduction only (Bài 56, no money
arithmetic in the titles); probability is only the
certain/possible/impossible language (Bài 66), no numerical
probability; statistics is collecting/classifying/counting and
picture charts only.

### GRADE 2 summary

75 lessons (Bài 1–75) across the year. Arc: revision to 100 →
+/− within 20 crossing 10 → kg/litre → +/− within 100 with
regrouping → plane shapes → day/hour/minute/month → Term 1
revision; then ×/÷ (tables 2 and 5 only) → solids (cylinder,
sphere) → numbers to 1,000 → dm/m/km + Vietnamese money →
+/− within 1,000 → first statistics/probability elements →
final revision. Regrouping ("có nhớ") is the year's hinge:
absent in Grade 1, taught first within 100 (v1 theme 4) and
then within 1,000 (v2 theme 12).

G2 v1 honest negatives: no three-digit numbers (ceiling is 100);
no multiplication/division yet (those arrive in v2); no
fractions, decimals or money; geometry is points/lines/curves
and quadrilaterals only (no triangles/circles as a theme here —
they were Grade 1's shapes); time reaches hour–minute and
day–month but the contents titles do not promise
minutes-past/to work beyond reading.

## GRADE 3 — Toán 3, Tập Một + Tập Hai

Lesson numbering is continuous across the year's two volumes
(v1 Bài 1–44, v2 Bài 45–81), as in Grades 1–2; theme numbering
is likewise continuous (v1 themes 1–7, v2 themes 8–16).
Authors (v1 title page confirmed): Hà Huy Khoái (general
editor), Lê Anh Vinh (editor), Nguyễn Áng, Vũ Văn Dương,
Nguyễn Minh Hải, Hoàng Quế Hương, Bùi Bá Mạnh; v1 4th reprint.

### G3 v1 — 126 PDF pp. (Bài 1–44)

- Theme 1 — ÔN TẬP VÀ BỔ SUNG (Revision and supplement), p. 6:
  Bài 1 Ôn tập các Số đến 1 000, p. 6; Bài 2 Ôn tập phép cộng,
  phép trừ trong phạm vi 1 000, p. 9; Bài 3 Tìm thành phần trong
  phép cộng, phép trừ (finding the unknown addend/minuend/
  subtrahend), p. 11; Bài 4 Ôn tập bảng nhân 2, 5, bảng chia 2,
  5, p. 14; Bài 5 Bảng nhân 3, bảng chia 3, p. 16; Bài 6 Bảng
  nhân 4, bảng chia 4, p. 19; Bài 7 Ôn tập hình học và đo lường,
  p. 21; Bài 8 Luyện tập chung, p. 24.
- Theme 2 — BẢNG NHÂN, BẢNG CHIA (Multiplication/division
  tables), p. 28: Bài 9 Bảng nhân 6, bảng chia 6, p. 28; Bài 10
  Bảng nhân 7, bảng chia 7, p. 31; Bài 11 Bảng nhân 8, bảng chia
  8, p. 33; Bài 12 Bảng nhân 9, bảng chia 9, p. 36; Bài 13 Tìm
  thành phần trong phép nhân, phép chia (unknown factor/
  dividend/divisor), p. 39; Bài 14 Một phần mấy (one part out
  of how many — unit fractions as "one part of"), p. 42; Bài 15
  Luyện tập chung, p. 46.
- Theme 3 — LÀM QUEN VỚI HÌNH PHẲNG, HÌNH KHỐI (Getting to know
  plane shapes and solids), p. 49: Bài 16 Điểm ở giữa, trung
  điểm của đoạn thẳng (midpoint of a segment), p. 49; Bài 17
  Hình tròn. Tâm, bán kính, đường kính của hình tròn (circle:
  centre, radius, diameter), p. 52; Bài 18 Góc, góc vuông, góc
  không vuông (angle, right angle, non-right angle), p. 54;
  Bài 19 Hình tam giác, hình tứ giác. Hình chữ nhật, hình vuông
  (triangle, quadrilateral; rectangle, square), p. 56; Bài 20
  Thực hành vẽ góc vuông, vẽ đường tròn, hình vuông, hình chữ
  nhật và vẽ trang trí (drawing right angles, circles, squares,
  rectangles and decorative drawing), p. 61; Bài 21 Khối lập
  phương, khối hộp chữ nhật (cube, rectangular box), p. 63;
  Bài 22 Luyện tập chung, p. 65.
- Theme 4 — PHÉP NHÂN, PHÉP CHIA TRONG PHẠM VI 100, p. 67:
  Bài 23 Nhân Số có hai chữ số với Số có một chữ số, p. 67;
  Bài 24 Gấp một Số lên một Số lần (multiplying a number by
  several times), p. 70; Bài 25 Phép chia hết, phép chia có dư
  (exact division, division with remainder), p. 72; Bài 26 Chia
  Số có hai chữ số cho Số có một chữ số, p. 75; Bài 27 Giảm một
  Số đi một Số lần (dividing a number down by several times),
  p. 79; Bài 28 Bài toán giải bằng hai bước tính (two-step word
  problems), p. 81; Bài 29 Luyện tập chung, p. 83.
- Theme 5 — MỘT SỐ ĐƠN VỊ ĐO ĐỘ DÀI, KHỐI LƯỢNG, DUNG TÍCH,
  NHIỆT ĐỘ (Some units of length, mass, capacity, temperature),
  p. 85: Bài 30 Mi-li-mét, p. 85; Bài 31 Gam, p. 87; Bài 32
  Mi-li-lít, p. 89; Bài 33 Nhiệt độ. Đơn vị đo nhiệt độ
  (temperature; °C), p. 91; Bài 34 Thực hành và trải nghiệm với
  các đơn vị mi-li-mét, gam, mi-li-lít, °C, p. 93; Bài 35 Luyện
  tập chung, p. 95.
- Theme 6 — PHÉP NHÂN, PHÉP CHIA TRONG PHẠM VI 1 000, p. 97:
  Bài 36 Nhân Số có ba chữ số với Số có một chữ số, p. 97;
  Bài 37 Chia Số có ba chữ số cho Số có một chữ số, p. 99
  (contents OCR misreads this number as "66"; folio 99 verified
  visually on the lesson's opener page, which works 312 : 2 =
  156 and 156 : 5 = 31 (dư 1)); Bài 38 Biểu thức
  Số. Tính giá trị của biểu thức Số (numerical expressions;
  evaluating them), p. 104; Bài 39 So sánh Số lớn gấp mấy lần
  Số bé (how many times bigger), p. 109; Bài 40 Luyện tập
  chung, p. 111.
- Theme 7 — ÔN TẬP HỌC KÌ 1 (Term 1 revision), p. 113: Bài 41
  Ôn tập phép nhân, phép chia trong phạm vi 100, 1 000, p. 113;
  Bài 42 Ôn tập biểu thức Số, p. 116; Bài 43 Ôn tập hình học
  và đo lường, p. 118; Bài 44 Ôn tập chung, p. 120. Glossary
  p. 122.

G3 v1 honest negatives: fractions are only "một phần mấy"
(unit-fraction language, Bài 14) — no fraction addition, no
equivalence, no decimals; division with remainder arrives here
(Bài 25) but only within 100; three-digit ×/÷ by one digit only
(no two-digit multipliers); no area/perimeter formulas (shapes
are identified, drawn and their elements named); no data
handling theme in v1.

### G3 v2 — 130 PDF pp. (Bài 45–81; themes 8–16)

Title page: same author team as v1 (Hà Huy Khoái, Lê Anh Vinh,
Nguyễn Áng, Vũ Văn Dương, Nguyễn Minh Hải, Hoàng Quế Hương,
Bùi Bá Mạnh), "(Tái bản lần thứ tư)" (4th reprint).

- Theme 8 — CÁC SỐ ĐẾN 10 000 (Numbers to 10,000), p. 4: Bài 45
  Các Số có bốn chữ số. Số 10 000 (four-digit numbers; 10,000),
  p. 4; Bài 46 So sánh các Số trong phạm vi 10 000, p. 9;
  Bài 47 Làm quen với chữ Số La Mã (Roman numerals), p. 12;
  Bài 48 Làm tròn Số đến hàng chục, hàng trăm (rounding to
  tens, hundreds), p. 15; Bài 49 Luyện tập chung, p. 17.
- Theme 9 — CHU VI, DIỆN TÍCH MỘT SỐ HÌNH PHẲNG (Perimeter and
  area of some plane shapes), p. 21: Bài 50 Chu vi hình tam
  giác, hình tứ giác, hình chữ nhật, hình vuông (perimeter of
  triangle, quadrilateral, rectangle, square), p. 21 (contents
  OCR garbled; title verified on the lesson opener); Bài 51 Diện tích của một hình. Xăng-ti-mét vuông (area
  of a shape; square centimetre), p. 26; Bài 52 Diện tích hình
  chữ nhật, diện tích hình vuông, p. 30; Bài 53 Luyện tập
  chung, p. 35.
- Theme 10 — CỘNG, TRỪ, NHÂN, CHIA TRONG PHẠM VI 10 000, p. 38:
  Bài 54 Phép cộng trong phạm vi 10 000, p. 38; Bài 55 Phép trừ
  trong phạm vi 10 000, p. 41; Bài 56 Nhân Số có bốn chữ số
  với Số có một chữ số, p. 43 (contents OCR garbled; title
  verified on the lesson opener); Bài 57 Chia
  Số có bốn chữ số cho Số có một chữ số, p. 47; Bài 58 Luyện
  tập chung, p. 52.
- Theme 11 — CÁC SỐ ĐẾN 100 000 (Numbers to 100,000), p. 56:
  Bài 59 Các Số có năm chữ số. Số 100 000, p. 56; Bài 60 So
  sánh các Số trong phạm vi 100 000, p. 61; Bài 61 Làm tròn Số
  đến hàng nghìn, hàng chục nghìn (rounding to thousands,
  ten-thousands), p. 64; Bài 62 Luyện tập chung, p. 66.
- Theme 12 — CỘNG, TRỪ TRONG PHẠM VI 100 000, p. 70: Bài 63
  Phép cộng trong phạm vi 100 000, p. 70; Bài 64 Phép trừ trong
  phạm vi 100 000, p. 73; Bài 65 Luyện tập chung, p. 76.
- Theme 13 — XEM ĐỒNG HỒ. THÁNG – NĂM. TIỀN VIỆT NAM (Telling
  time. Months–years. Vietnamese money), p. 77: Bài 66 Xem đồng
  hồ. Tháng – năm, p. 77; Bài 67 Thực hành xem đồng hồ, xem
  lịch, p. 81; Bài 68 Tiền Việt Nam, p. 85; Bài 69 Luyện tập
  chung, p. 88.
- Theme 14 — NHÂN, CHIA TRONG PHẠM VI 100 000, p. 94: Bài 70
  Nhân Số có năm chữ số với Số có một chữ số, p. 94; Bài 71
  Chia Số có năm chữ số cho Số có một chữ số, p. 97; Bài 72
  Luyện tập chung, p. 101.
- Theme 15 — LÀM QUEN VỚI YẾU TỐ THỐNG KÊ, XÁC SUẤT
  (Statistics/probability elements), p. 103: Bài 73 Thu thập,
  phân loại, ghi chép Số liệu. Bảng Số liệu (collecting,
  classifying, recording data; data tables), p. 103 (contents
  line missing in OCR; title verified on the lesson opener); Bài 74 Khả năng xảy ra
  của một sự kiện (likelihood of an event), p. 108; Bài 75
  Thực hành và trải nghiệm thu thập, phân loại, ghi chép Số
  liệu, đọc bảng Số liệu, p. 110.
- Theme 16 — ÔN TẬP CUỐI NĂM (End-of-year revision), p. 112:
  Bài 76 Ôn tập các Số trong phạm vi 10 000, 100 000, p. 112
  (contents line missing in OCR; title verified on the lesson
  opener); Bài 77 Ôn tập phép cộng, phép
  trừ trong phạm vi 100 000, p. 115; Bài 78 Ôn tập phép nhân,
  phép chia trong phạm vi 100 000, p. 118; Bài 79 Ôn tập hình
  học và đo lường, p. 121; Bài 80 Ôn tập bảng Số liệu, khả
  năng xảy ra của một sự kiện, p. 123; Bài 81 Ôn tập chung,
  p. 125. Glossary p. 127.

G3 v2 honest negatives: ×/÷ stay one-digit multipliers/divisors
throughout Grade 3 (no two-digit ×/÷); no fraction arithmetic
(beyond Grade 3 v1's "một phần mấy"); no decimals; area is
rectangle/square only (no triangle area formula in the titles);
Roman numerals are "getting to know" only (Bài 47); money
(Bài 68) is the second money lesson after Grade 2's introduction
— money arithmetic, if any, sits inside practice lessons, not
as its own titled lesson.

### GRADE 3 summary

G3 teaches, across v1+v2: all ×/÷ tables 2–9 (v1 themes 1–2
complete the tables); unit fractions ("một phần mấy"); circle
elements and angle types; perimeter and rectangle/square area;
numbers to 100,000 with rounding; four operations within
100,000 with one-digit ×/÷; mm/g/ml/°C; Roman numerals;
time/months/money; and a statistics/probability strand that
grows from Grade 2's picture charts to data tables and event
likelihood. Lesson and theme numbering are continuous across
the year's two volumes (v1 Bài 1–44 / themes 1–7, v2 Bài 45–81
/ themes 8–16); the filing keeps the books' own numbers.

## GRADE 4 — Toán 4, Tập Một + Tập Hai

Grade 4 is the first grade whose maths lives ONLY in the
approved-private tree copies (no gov release copies exist for
Grade 4 maths — see set verification). Lesson/theme numbering
continuous across volumes (v1 Bài 1–37 / themes 1–7, v2 Bài 38–73
/ themes 8–13).

### G4 v1 — 135 PDF pp. (Bài 1–37)

- Theme 1 — ÔN TẬP VÀ BỔ SUNG (Revision and supplement), p. 6:
  Bài 1 Ôn tập các Số đến 100 000, p. 6; Bài 2 Ôn tập các phép
  tính trong phạm vi 100 000, p. 9; Bài 3 Số chẵn, Số lẻ (even,
  odd numbers), p. 12; Bài 4 Biểu thức chứa chữ (expressions
  containing a letter — first algebra: letters standing for
  numbers), p. 14; Bài 5 Giải bài toán có ba bước tính
  (three-step word problems), p. 19; Bài 6 Luyện tập chung,
  p. 21.
- Theme 2 — GÓC VÀ ĐƠN VỊ ĐO GÓC (Angles and angle units),
  p. 23: Bài 7 Đo góc, đơn vị đo góc (measuring angles; degrees),
  p. 23; Bài 8 Góc nhọn, góc tù, góc bẹt (acute, obtuse,
  straight angles), p. 26; Bài 9 Luyện tập chung, p. 31.
- Theme 3 — SỐ CÓ NHIỀU CHỮ SỐ (Multi-digit numbers), p. 33:
  Bài 10 Số có sáu chữ số. Số 1 000 000 (six-digit numbers;
  1,000,000), p. 33; Bài 11 Hàng và lớp (places and classes —
  units/thousands/millions classes), p. 37; Bài 12 Các Số trong
  phạm vi lớp triệu (numbers within the millions class), p. 41;
  Bài 13 Làm tròn Số đến hàng trăm nghìn (rounding to hundred
  thousands), p. 45; Bài 14 So sánh các Số có nhiều chữ số,
  p. 47; Bài 15 Làm quen với dãy Số tự nhiên (the natural-number
  sequence), p. 50; Bài 16 Luyện tập chung, p. 52.
- Theme 4 — MỘT SỐ ĐƠN VỊ ĐO ĐẠI LƯỢNG (Some measurement units),
  p. 56: Bài 17 Yến, tạ, tấn (traditional mass units: yến, tạ,
  tấn), p. 56; Bài 18 Đề-xi-mét vuông, mét vuông, mi-li-mét
  vuông (square decimetre/metre/millimetre), p. 60; Bài 19
  Giây, thế kỉ (seconds, centuries), p. 66; Bài 20 Thực hành và
  trải nghiệm sử dụng một Số đơn vị đo đại lượng, p. 69;
  Bài 21 Luyện tập chung, p. 73.
- Theme 5 — PHÉP CỘNG VÀ PHÉP TRỪ (Addition and subtraction),
  p. 76: Bài 22 Phép cộng các Số có nhiều chữ số, p. 76;
  Bài 23 Phép trừ các Số có nhiều chữ số, p. 79; Bài 24 Tính
  chất giao hoán và kết hợp của phép cộng (commutative and
  associative properties of addition), p. 82; Bài 25 Tìm hai Số
  biết tổng và hiệu của hai Số đó (finding two numbers from
  their sum and difference), p. 86; Bài 26 Luyện tập chung,
  p. 88.
- Theme 6 — ĐƯỜNG THẲNG VUÔNG GÓC. ĐƯỜNG THẲNG SONG SONG
  (Perpendicular lines. Parallel lines), p. 91: Bài 27 Hai đường
  thẳng vuông góc, p. 91; Bài 28 Thực hành và trải nghiệm về
  hai đường thẳng vuông góc, p. 94; Bài 29 Hai đường thẳng song
  song, p. 98; Bài 30 Thực hành và trải nghiệm về hai đường
  thẳng song song, p. 101; Bài 31 Hình bình hành, hình thoi
  (parallelogram, rhombus), p. 105; Bài 32 Luyện tập chung,
  p. 110.
- Theme 7 — ÔN TẬP HỌC KÌ 1 (Term 1 revision), p. 114: Bài 33
  Ôn tập các Số đến lớp triệu, p. 114; Bài 34 Ôn tập phép cộng,
  phép trừ, p. 118; Bài 35 Ôn tập hình học, p. 121; Bài 36 Ôn
  tập đo lường, p. 125; Bài 37 Ôn tập chung, p. 127. Glossary
  p. 131.

### G4 v2 — 123 PDF pp. (Bài 38–73)

- Theme 8 — PHÉP NHÂN VÀ PHÉP CHIA (Multiplication and
  division), p. 4: Bài 38 Nhân với Số có một chữ số, p. 4;
  Bài 39 Chia cho Số có một chữ số, p. 6; Bài 40 Tính chất giao
  hoán và kết hợp của phép nhân, p. 9; Bài 41 Nhân, chia với
  10, 100, 1 000, …, p. 14; Bài 42 Tính chất phân phối của phép
  nhân đối với phép cộng (distributive property), p. 17;
  Bài 43 Nhân với Số có hai chữ số, p. 20; Bài 44 Chia cho Số
  có hai chữ số, p. 23; Bài 45 Thực hành và trải nghiệm ước
  lượng trong tính toán (estimation in calculation), p. 27;
  Bài 46 Tìm Số trung bình cộng (mean average), p. 29; Bài 47
  Bài toán liên quan đến rút về đơn vị (unitary-method word
  problems), p. 31; Bài 48 Luyện tập chung, p. 33.
- Theme 9 — LÀM QUEN VỚI YẾU TỐ THỐNG KÊ, XÁC SUẤT, p. 36:
  Bài 49 Dãy Số liệu thống kê (statistical data sequences),
  p. 36; Bài 50 Biểu đồ cột (bar charts), p. 39; Bài 51 Số lần
  xuất hiện của một sự kiện (how many times an event occurs —
  frequency), p. 43; Bài 52 Luyện tập chung, p. 47.
- Theme 10 — PHÂN SỐ (Fractions), p. 49: Bài 53 Khái niệm phân
  Số (the fraction concept), p. 49; Bài 54 Phân Số và phép chia
  Số tự nhiên (fractions and division of natural numbers),
  p. 52; Bài 55 Tính chất cơ bản của phân Số (fundamental
  property — equivalence), p. 56; Bài 56 Rút gọn phân Số
  (simplifying), p. 59; Bài 57 Quy đồng mẫu Số các phân Số
  (common denominators), p. 62; Bài 58 So sánh phân Số, p. 64;
  Bài 59 Luyện tập chung, p. 69.
- Theme 11 — PHÉP CỘNG, PHÉP TRỪ PHÂN SỐ, p. 74: Bài 60 Phép
  cộng phân Số, p. 74; Bài 61 Phép trừ phân Số, p. 80; Bài 62
  Luyện tập chung, p. 83.
- Theme 12 — PHÉP NHÂN, PHÉP CHIA PHÂN SỐ, p. 86: Bài 63 Phép
  nhân phân Số, p. 86; Bài 64 Phép chia phân Số, p. 91; Bài 65
  Tìm phân Số của một Số (fraction of a number), p. 95; Bài 66
  Luyện tập chung, p. 98.
- Theme 13 — ÔN TẬP CUỐI NĂM (End-of-year revision), p. 102:
  Bài 67 Ôn tập Số tự nhiên, p. 102; Bài 68 Ôn tập phép tính
  với Số tự nhiên, p. 105; Bài 69 Ôn tập phân Số, p. 107;
  Bài 70 Ôn tập phép tính với phân Số, p. 110; Bài 71 Ôn tập
  hình học và đo lường, p. 112; Bài 72 Ôn tập một Số yếu tố
  thống kê và xác suất, p. 114; Bài 73 Ôn tập chung, p. 116.
  Glossary p. 119.

G4 honest negatives: decimals are NOT taught in Grade 4 (the
fraction work stops at fraction arithmetic; decimal notation
arrives in Grade 5); two-digit ×/÷ arrive only in v2 theme 8
(and division by two digits is the year's ceiling); no negative
numbers, no powers, no ratio/proportion as its own topic (the
unitary method, Bài 47, is the closest); geometry is lines,
angles, parallelogram/rhombus — no circle theorems, no volume.

### GRADE 4 summary

Grade 4 is the hinge from arithmetic to pre-algebra: letters in
expressions (Bài 4), operation properties (commutative,
associative, distributive), sum-and-difference problems, the
mean, and a full fraction course (concept → equivalence →
simplification → common denominators → comparison → all four
operations → fraction of a number) — while whole-number work
extends to millions and two-digit multipliers/divisors.

# Band B — Grades 5–6 (5 files, 663 PDF pages)

## GRADE 5 — Toán 5, Tập Một + Tập Hai

National appraisal note (both title pages): appraised by the
National Textbook Appraisal Council for Grade 5, Decision
1963/QĐ-BGDĐT, 5 July 2023, MoET. Lesson/theme numbering
continuous across volumes (v1 Bài 1–35 / themes 1–6, v2 Bài 36–75
/ themes 7–12).

### G5 v1 — 143 PDF pp. (Bài 1–35)

- Theme 1 — ÔN TẬP VÀ BỔ SUNG (Revision and supplement), p. 6:
  Bài 1 Ôn tập Số tự nhiên, p. 6; Bài 2 Ôn tập các phép tính với
  Số tự nhiên, p. 9; Bài 3 Ôn tập phân Số, p. 11; Bài 4 Phân Số
  thập phân (decimal fractions — fractions with denominators
  10, 100, 1 000), p. 14; Bài 5 Ôn tập các phép tính với phân
  Số, p. 16; Bài 6 Cộng, trừ hai phân Số khác mẫu Số, p. 20;
  Bài 7 Hỗn Số (mixed numbers), p. 23; Bài 8 Ôn tập hình học và
  đo lường, p. 26; Bài 9 Luyện tập chung, p. 29.
- Theme 2 — SỐ THẬP PHÂN (Decimal numbers), p. 32: Bài 10 Khái
  niệm Số thập phân, p. 32; Bài 11 So sánh các Số thập phân,
  p. 38; Bài 12 Viết Số đo đại lượng dưới dạng Số thập phân
  (writing measurements as decimals), p. 42; Bài 13 Làm tròn Số
  thập phân, p. 47; Bài 14 Luyện tập chung, p. 51.
- Theme 3 — MỘT SỐ ĐƠN VỊ ĐO DIỆN TÍCH (Some area units),
  p. 53: Bài 15 Ki-lô-mét vuông. Héc-ta (square kilometre,
  hectare), p. 53; Bài 16 Các đơn vị đo diện tích, p. 56;
  Bài 17 Thực hành và trải nghiệm với một Số đơn vị đo đại
  lượng, p. 60; Bài 18 Luyện tập chung, p. 62.
- Theme 4 — CÁC PHÉP TÍNH VỚI SỐ THẬP PHÂN, p. 65: Bài 19 Phép
  cộng Số thập phân, p. 65; Bài 20 Phép trừ Số thập phân,
  p. 68; Bài 21 Phép nhân Số thập phân, p. 71; Bài 22 Phép chia
  Số thập phân, p. 76; Bài 23 Nhân, chia Số thập phân với 10;
  100; 1 000, …; với 0,1; 0,01; 0,001, …, p. 83; Bài 24 Luyện
  tập chung, p. 88.
- Theme 5 — MỘT SỐ HÌNH PHẲNG. CHU VI VÀ DIỆN TÍCH (Some plane
  shapes. Perimeter and area), p. 91: Bài 25 Hình tam giác.
  Diện tích hình tam giác, p. 91; Bài 26 Hình thang. Diện tích
  hình thang, p. 98; Bài 27 Đường tròn. Chu vi và diện tích
  hình tròn, p. 105; Bài 28 Thực hành và trải nghiệm đo, vẽ,
  lắp ghép, tạo hình, p. 113; Bài 29 Luyện tập chung, p. 116.
- Theme 6 — ÔN TẬP HỌC KÌ 1 (Term 1 revision), p. 120: Bài 30
  Ôn tập Số thập phân, p. 120; Bài 31 Ôn tập các phép tính với
  Số thập phân, p. 123; Bài 32 Ôn tập một Số hình phẳng,
  p. 127; Bài 33 Ôn tập diện tích, chu vi một Số hình phẳng,
  p. 130; Bài 34 Ôn tập đo lường, p. 133; Bài 35 Ôn tập chung,
  p. 135. Glossary p. 139.

### G5 v2 — 139 PDF pp. (Bài 36–75)

- Theme 7 — TỈ SỐ VÀ CÁC BÀI TOÁN LIÊN QUAN (Ratios and related
  problems), p. 4: Bài 36 Tỉ Số. Tỉ Số phần trăm (ratio;
  percentage ratio), p. 4; Bài 37 Tỉ lệ bản đồ và ứng dụng
  (map scale and applications), p. 8; Bài 38 Tìm hai Số khi
  biết tổng và tỉ Số của hai Số đó, p. 12; Bài 39 Tìm hai Số
  khi biết hiệu và tỉ Số của hai Số đó, p. 15; Bài 40 Tìm tỉ
  Số phần trăm của hai Số, p. 18; Bài 41 Tìm giá trị phần trăm
  của một Số, p. 21; Bài 42 Máy tính cầm tay (handheld
  calculator), p. 23; Bài 43 Thực hành và trải nghiệm sử dụng
  máy tính cầm tay, p. 27; Bài 44 Luyện tập chung, p. 28.
- Theme 8 — THỂ TÍCH. ĐƠN VỊ ĐO THỂ TÍCH (Volume. Volume units),
  p. 30: Bài 45 Thể tích của một hình, p. 30; Bài 46 Xăng-ti-mét
  khối. Đề-xi-mét khối, p. 33; Bài 47 Mét khối, p. 35; Bài 48
  Luyện tập chung, p. 38.
- Theme 9 — DIỆN TÍCH VÀ THỂ TÍCH CỦA MỘT SỐ HÌNH KHỐI (Area
  and volume of some solids), p. 40: Bài 49 Hình khai triển của
  hình lập phương, hình hộp chữ nhật và hình trụ (nets of cube,
  rectangular box and cylinder), p. 40; Bài 50 Diện tích xung
  quanh và diện tích toàn phần của hình hộp chữ nhật, p. 44;
  Bài 51 Diện tích xung quanh và diện tích toàn phần của hình
  lập phương, p. 48; Bài 52 Thể tích của hình hộp chữ nhật,
  p. 51; Bài 53 Thể tích của hình lập phương, p. 54; Bài 54
  Thực hành tính toán và ước lượng thể tích một Số hình khối,
  p. 58; Bài 55 Luyện tập chung, p. 60.
- Theme 10 — SỐ ĐO THỜI GIAN, VẬN TỐC. CÁC BÀI TOÁN LIÊN QUAN
  ĐẾN CHUYỂN ĐỘNG ĐỀU (Time measurement, speed. Uniform-motion
  problems), p. 64: Bài 56 Các đơn vị đo thời gian, p. 64;
  Bài 57 Cộng, trừ Số đo thời gian, p. 67; Bài 58 Nhân, chia
  Số đo thời gian với một Số, p. 71; Bài 59 Vận tốc của một
  chuyển động đều, p. 76; Bài 60 Quãng đường, thời gian của
  một chuyển động đều, p. 78; Bài 61 Thực hành tính toán và
  ước lượng về vận tốc, quãng đường, thời gian trong chuyển
  động đều, p. 82; Bài 62 Luyện tập chung, p. 84.
- Theme 11 — MỘT SỐ YẾU TỐ THỐNG KÊ VÀ XÁC SUẤT, p. 87:
  Bài 63 Thu thập, phân loại, sắp xếp các Số liệu, p. 87;
  Bài 64 Biểu đồ hình quạt tròn (pie charts), p. 90; Bài 65 Tỉ
  Số của Số lần lặp lại một sự kiện so với tổng Số lần thực
  hiện (the ratio of an event's repeat count to the total
  number of trials — experimental relative frequency), p. 94;
  Bài 66 Thực hành và trải nghiệm thu thập, phân tích, biểu
  diễn các Số liệu thống kê, p. 96; Bài 67 Luyện tập chung,
  p. 100.
- Theme 12 — ÔN TẬP CUỐI NĂM (End-of-year revision), p. 103:
  Bài 68 Ôn tập Số tự nhiên, phân Số, Số thập phân, p. 103;
  Bài 69 Ôn tập các phép tính với Số tự nhiên, phân Số, Số
  thập phân, p. 107; Bài 70 Ôn tập tỉ Số, tỉ Số phần trăm,
  p. 111; Bài 71 Ôn tập hình học, p. 113; Bài 72 Ôn tập đo
  lường, p. 119; Bài 73 Ôn tập toán chuyển động đều, p. 121;
  Bài 74 Ôn tập một Số yếu tố thống kê và xác suất, p. 123;
  Bài 75 Ôn tập chung, p. 128. Glossary p. 135.

G5 honest negatives: no negative numbers; no powers/roots; no
algebra beyond the ratio/percent problem types (no equations
solved symbolically in the titles); no circle theorems, no
Pythagoras; probability is experimental frequency only (Bài 65)
— no theoretical probability, no tree diagrams; the calculator
is introduced as a tool (Bài 42–43), not as a substitute for
the decimal arithmetic taught in v1.

### GRADE 5 summary

Grade 5 completes primary arithmetic: decimals (concept →
comparison → measurement → rounding → all four operations →
×/÷ by powers of ten and by 0.1/0.01/0.001), mixed numbers,
triangle/trapezoid/circle area, ratio and percent (including
map scale and sum/difference-ratio problems), volume and
surface area of boxes and cubes, time arithmetic and uniform
motion (v = s/t in words), and statistics up to pie charts and
relative frequency. It is the last primary grade: Grade 6
restarts the secondary structure with chapters, not themes.


## GRADE 6 — Toán 6, Tập Một + Tập Hai + Bài tập Toán 6 Tập Hai

Secondary structure begins: CHƯƠNG (chapters) with Bài lessons,
"Luyện tập chung" practice sets inside chapters, "Bài tập cuối
chương" end-of-chapter exercises, and a closing "Hoạt động thực
hành trải nghiệm" (hands-on experience activities) section.
Contents in v1 is a single page (printed p. 4), visually verified
— the two-column OCR interleaving misread Bài 2 (p. 9, not 6),
Bài 20 (p. 90, not 06) and Bài 21 (p. 98, not 86); the visual
contents settles all three.

### G6 v1 — 126 PDF pp. (Bài 1–22, chapters I–V)

- Chương I — TẬP HỢP CÁC SỐ TỰ NHIÊN, p. 5: Bài 1 Tập hợp, p. 5;
  Bài 2 Cách ghi Số tự nhiên, p. 9; Bài 3 Thứ tự trong tập hợp
  các Số tự nhiên, p. 13; Bài 4 Phép cộng và phép trừ Số tự
  nhiên, p. 15; Bài 5 Phép nhân và phép chia Số tự nhiên,
  p. 17; Luyện tập chung p. 20; Bài 6 Lũy thừa với Số mũ tự
  nhiên, p. 22; Bài 7 Thứ tự thực hiện các phép tính, p. 25;
  Luyện tập chung p. 27; Bài tập cuối chương I, p. 28.
- Chương II — TÍNH CHIA HẾT TRONG TẬP HỢP CÁC SỐ TỰ NHIÊN,
  p. 29: Bài 8 Quan hệ chia hết và tính chất, p. 29; Bài 9 Dấu
  hiệu chia hết, p. 34; Bài 10 Số nguyên tố, p. 38; Luyện tập
  chung p. 43; Bài 11 Ước chung. Ước chung lớn nhất, p. 44;
  Bài 12 Bội chung. Bội chung nhỏ nhất, p. 49; Luyện tập chung
  p. 54; Bài tập cuối chương II, p. 56.
- Chương III — SỐ NGUYÊN, p. 57: Bài 13 Tập hợp các Số nguyên,
  p. 57; Bài 14 Phép cộng và phép trừ Số nguyên, p. 62; Bài 15
  Quy tắc dấu ngoặc (bracket rules), p. 67; Luyện tập chung
  p. 69; Bài 16 Phép nhân Số nguyên, p. 70; Bài 17 Phép chia
  hết. Ước và bội của một Số nguyên, p. 73; Luyện tập chung
  p. 75; Bài tập cuối chương III, p. 76.
- Chương IV — MỘT SỐ HÌNH PHẲNG TRONG THỰC TIỄN, p. 77:
  Bài 18 Hình tam giác đều. Hình vuông. Hình lục giác đều,
  p. 77; Bài 19 Hình chữ nhật. Hình thoi. Hình bình hành. Hình
  thang cân, p. 83; Bài 20 Chu vi và diện tích của một Số tứ
  giác đã học, p. 90; Luyện tập chung p. 95; Bài tập cuối
  chương IV, p. 97.
- Chương V — TÍNH ĐỐI XỨNG CỦA HÌNH PHẲNG TRONG TỰ NHIÊN,
  p. 98: Bài 21 Hình có trục đối xứng, p. 98; Bài 22 Hình có
  tâm đối xứng, p. 103; Luyện tập chung p. 108; Bài tập cuối
  chương V, p. 110.
- Hoạt động thực hành trải nghiệm: Tấm thiệp và phòng học của
  em, p. 111; Vẽ hình đơn giản với phần mềm GeoGebra, p. 113;
  Sử dụng máy tính cầm tay, p. 119. Bảng tra cứu thuật ngữ
  p. 122; Bảng giải thích thuật ngữ p. 123.

G6 v1 honest negatives: no fractions or decimals in v1 (those
are v2's chapters); no equations solved as a topic (unknowns
appear inside number work, not as equation-solving); no
coordinate geometry, no powers beyond natural exponents
(Bài 6); symmetry is recognition and construction (Bài 21–22),
not transformation groups or congruence proofs.

### G6 v2 — 114 PDF pp. (Bài 23–43, chapters VI–IX)

Contents is a single page (printed p. 3), visually verified;
Bài 42's page (p. 89) was garbled in the two-column OCR and is
settled by the visual contents. Negative fractions arrive here:
Bài 23 extends fractions to negative numerators/denominators
(the opener works −2 : 5 = −2/5).

- Chương VI — PHÂN SỐ (Fractions), p. 4: Bài 23 Mở rộng khái
  niệm phân số. Phân số bằng nhau (extending the fraction
  concept; equal fractions — including negative fractions),
  p. 4; Bài 24 So sánh phân số. Hỗn số dương (comparing
  fractions; positive mixed numbers), p. 9; Luyện tập chung
  p. 13; Bài 25 Phép cộng và phép trừ phân số, p. 15; Bài 26
  Phép nhân và phép chia phân số, p. 19; Bài 27 Hai bài toán về
  phân số (two fraction problems: fraction of a number; finding
  a number from its fraction), p. 22; Luyện tập chung p. 25;
  Bài tập cuối chương VI, p. 27.
- Chương VII — SỐ THẬP PHÂN (Decimal numbers), p. 28: Bài 28
  Số thập phân, p. 28; Bài 29 Tính toán với Số thập phân,
  p. 31; Bài 30 Làm tròn và ước lượng, p. 35; Bài 31 Một Số
  bài toán về tỉ Số và tỉ Số phần trăm, p. 38; Luyện tập chung
  p. 41; Bài tập cuối chương VII, p. 42.
- Chương VIII — NHỮNG HÌNH HÌNH HỌC CƠ BẢN (Basic geometric
  shapes), p. 43: Bài 32 Điểm và đường thẳng, p. 43; Bài 33
  Điểm nằm giữa hai điểm. Tia (point between two points; ray),
  p. 48; Bài 34 Đoạn thẳng. Độ dài đoạn thẳng, p. 51; Bài 35
  Trung điểm của đoạn thẳng (midpoint), p. 55; Luyện tập chung
  p. 57; Bài 36 Góc, p. 58; Bài 37 Số đo góc, p. 61; Luyện tập
  chung p. 65; Bài tập cuối chương VIII, p. 67.
- Chương IX — DỮ LIỆU VÀ XÁC SUẤT THỰC NGHIỆM (Data and
  experimental probability), p. 68: Bài 38 Dữ liệu và thu thập
  dữ liệu, p. 68; Bài 39 Bảng thống kê và biểu đồ tranh
  (statistical tables and picture charts), p. 73; Bài 40 Biểu đồ
  cột (bar charts), p. 77; Bài 41 Biểu đồ cột kép (double bar
  charts), p. 82; Luyện tập chung p. 87; Bài 42 Kết quả có thể
  và sự kiện trong trò chơi, thí nghiệm (possible outcomes and
  events in games/experiments), p. 89; Bài 43 Xác suất thực
  nghiệm (experimental probability), p. 94; Luyện tập chung
  p. 97; Bài tập cuối chương IX, p. 98.
- Hoạt động thực hành trải nghiệm: Kế hoạch chi tiêu cá nhân và
  gia đình, p. 99; Hoạt động thể thao nào được yêu thích nhất
  trong hè?, p. 101; Vẽ hình đơn giản với phần mềm GeoGebra,
  p. 105. Bài tập ôn tập cuối năm, p. 108. Bảng tra cứu thuật
  ngữ p. 110; Bảng giải thích thuật ngữ p. 111.

G6 v2 honest negatives: no algebra (no equations, no
expressions with variables as a topic — Bài 23's fractions use
negative integers but no literal algebra); no ratio beyond
percent problems (Bài 31); geometry is points/lines/rays/
segments/angles only (no triangles, circles or polygons as a
chapter here — those were v1 chapter IV); probability is
experimental only (Bài 43: relative frequency from trials),
with possible outcomes/events (Bài 42) as its vocabulary —
no theoretical probability formula, no sample-space counting
beyond listing outcomes.

### G6 workbook v2 — Bài tập Toán 6 Tập Hai — 141 PDF pp.

Cover team: Nguyễn Huy Đoan (editor), Trần Mạnh Cường, Đoàn
Minh Cường, Lưu Bá Thắng, Đặng Hùng Thắng (a slightly
different team from the student books). Held copy: a
Blogtailieu.com scan, watermarked on every page. The workbook
is NOT a second textbook: it is write-in exercises following
the student book's Volume 2 chapter/lesson order exactly, with
a chapter revision ("Ôn tập chương") closing each chapter
instead of the student book's practice sets and end-of-chapter
exercises.

- Chương VI (Phân số), p. 4: Bài 23 exercises p. 4; Bài 24
  p. 7; Bài 25 p. 10; Bài 26 p. 13; Bài 27 p. 17; Ôn tập
  chương VI p. 20.
- Chương VII (Số thập phân), p. 23: Bài 28 p. 23; Bài 29
  p. 26; Bài 30 p. 29; Bài 31 p. 32; Ôn tập chương VII p. 36.
- Chương VIII (Những hình hình học cơ bản), p. 40: Bài 32
  p. 40; Bài 33 p. 44; Bài 34 p. 47; Bài 35 p. 50; Bài 36 p. 52;
  Bài 37 p. 55; Ôn tập chương VIII p. 58.
- Chương IX (Dữ liệu và xác suất thực nghiệm), p. 61: Bài 38
  p. 61; Bài 39 p. 65; Bài 40 p. 70; Bài 41 p. 76; Bài 42 p. 82;
  Bài 43 p. 85; Ôn tập chương IX p. 87.
- Bài tập ôn tập cuối năm (final revision exercises), p. 92.
- Lời giải / Hướng dẫn / Đáp số (solutions, guidance, answers):
  Chương VI p. 98; Chương VII p. 107; Chương VIII p. 115;
  Chương IX p. 124; final revision p. 134. This is the ONLY
  held Vietnam maths file that prints answers — no student
  book in the set prints an answer key (student-book practice
  sets carry no printed keys; verify in the check pass).

Workbook gaps (against its own student volume): Volume 1 has no
workbook in the set at all (no Bài tập Toán 6 Tập Một in the
record or the tree); this volume's exercises add no new
taught content — they practise Volume 2's lessons only.

### GRADE 6 summary

Grade 6 is the secondary restart: sets and set notation, natural
numbers with powers and order of operations, divisibility
(divisors, multiples, primes, GCD, LCM), integers (including
bracket rules and integer division), practical plane shapes
(regular polygons, parallelogram, rhombus, isosceles trapezium,
their perimeters/areas) and symmetry (line and centre), then
negative fractions, decimals with rounding/estimation and
percent problems, basic geometry (points, lines, rays, segments,
midpoints, angles and angle measure), and data with experimental
probability (tables, picture/bar/double-bar charts, possible
outcomes, relative frequency). The workbook covers Volume 2
only and is the set's sole answer-key carrier.

# Band C — Grades 7–9 (6 files, 764 PDF pages)

## GRADE 7 — Toán 7, Tập Một + Tập Hai

Author team (v1 title page): Hà Huy Khoái (general editor),
Nguyễn Huy Đoan (editor), Cung Thế Anh, Nguyễn Cao Cường,
Trần Mạnh Cường, Đoàn Minh Cường, Trần Phương Dung, Sĩ Đức
Quang, Lưu Bá Thắng, Đặng Hùng Thắng. V1 "(Tái bản lần thứ
tư)" (4th reprint).

### G7 v1 — 122 PDF pp. (Bài 1–19, chapters I–V)

Contents p. 4 (visual read; folio 4 = PDF 5, so printed =
PDF − 1).

- Chương I — SỐ HỮU TỈ (Rational numbers), p. 5: Bài 1 Tập
  hợp các Số hữu tỉ, p. 5; Bài 2 Cộng, trừ, nhân, chia Số hữu
  tỉ, p. 10; Luyện tập chung p. 14; Bài 3 Lũy thừa với Số mũ tự
  nhiên của một Số hữu tỉ, p. 16; Bài 4 Thứ tự thực hiện các
  phép tính. Quy tắc chuyển vế (order of operations; the
  transposition rule), p. 20; Luyện tập chung p. 23; Bài tập
  cuối chương I, p. 25.
- Chương II — SỐ THỰC (Real numbers), p. 26: Bài 5 Làm quen
  với Số thập phân vô hạn tuần hoàn (repeating infinite
  decimals), p. 26; Bài 6 Số vô tỉ. Căn bậc hai Số học
  (irrational numbers; arithmetic square roots), p. 29; Bài 7
  Tập hợp các Số thực, p. 33; Luyện tập chung p. 37; Bài tập
  cuối chương II, p. 39.
- Chương III — GÓC VÀ ĐƯỜNG THẲNG SONG SONG (Angles and
  parallel lines), p. 40: Bài 8 Góc ở vị trí đặc biệt. Tia phân
  giác của một góc (special-position angles; angle bisector),
  p. 40; Bài 9 Hai đường thẳng song song và dấu hiệu nhận
  biết, p. 46; Luyện tập chung p. 50; Bài 10 Tiên đề Euclid.
  Tính chất của hai đường thẳng song song (Euclid's postulate;
  properties of parallel lines), p. 51; Bài 11 Định lí và chứng
  minh định lí (theorems and proving theorems), p. 55; Luyện
  tập chung p. 58; Bài tập cuối chương III, p. 59.
- Chương IV — TAM GIÁC BẰNG NHAU (Congruent triangles), p. 60:
  Bài 12 Tổng các góc trong một tam giác, p. 60; Bài 13 Hai tam
  giác bằng nhau. Trường hợp bằng nhau thứ nhất của tam giác
  (first congruence case), p. 63; Luyện tập chung p. 68; Bài 14
  Trường hợp bằng nhau thứ hai và thứ ba của tam giác, p. 70;
  Luyện tập chung p. 74; Bài 15 Các trường hợp bằng nhau của
  tam giác vuông, p. 75; Bài 16 Tam giác cân. Đường trung trực
  của đoạn thẳng (isosceles triangle; perpendicular bisector),
  p. 80; Luyện tập chung p. 85; Bài tập cuối chương IV, p. 87.
- Chương V — THU THẬP VÀ BIỂU DIỄN DỮ LIỆU (Collecting and
  presenting data), p. 88: Bài 17 Thu thập và phân loại dữ
  liệu, p. 88; Bài 18 Biểu đồ hình quạt tròn (pie charts),
  p. 93; Bài 19 Biểu đồ đoạn thẳng (line charts), p. 100;
  Luyện tập chung p. 106; Bài tập cuối chương V, p. 108.
- Hoạt động thực hành trải nghiệm: Vẽ hình đơn giản với phần
  mềm GeoGebra, p. 110; Dân số và cơ cấu dân số Việt Nam,
  p. 115. Bảng tra cứu thuật ngữ p. 118; Bảng giải thích thuật
  ngữ p. 119.

G7 v1 honest negatives: no equations as a topic (the
transposition rule, Bài 4, is taught inside rational-number
computation, not as equation-solving); no functions; no
Pythagoras (right triangles appear only through congruence
cases, Bài 15); no similarity (congruence only); statistics
is collecting/classifying and pie/line charts — no mean/
median/mode as a chapter here (the mean was Grade 4's Bài 46
and returns in Grade 8's data chapter, to confirm).

### G7 v2 — 118 PDF pp. (Bài 20–37, chapters VI–X)

Contents p. 3 (visual read; folio 3 = PDF 4, so printed =
PDF − 1).

- Chương VI — TỈ LỆ THỨC VÀ ĐẠI LƯỢNG TỈ LỆ, p. 4: Bài 20 Tỉ
  lệ thức, p. 4; Bài 21 Tính chất của dãy tỉ Số bằng nhau,
  p. 8; Luyện tập chung p. 10; Bài 22 Đại lượng tỉ lệ thuận,
  p. 11; Bài 23 Đại lượng tỉ lệ nghịch, p. 15; Luyện tập chung
  p. 19; Bài tập cuối chương VI, p. 21.
- Chương VII — BIỂU THỨC ĐẠI SỐ VÀ ĐA THỨC MỘT BIẾN, p. 22:
  Bài 24 Biểu thức đại số, p. 22; Bài 25 Đa thức một biến,
  p. 25; Bài 26 Phép cộng và phép trừ đa thức một biến, p. 31;
  Luyện tập chung p. 34; Bài 27 Phép nhân đa thức một biến,
  p. 36; Bài 28 Phép chia đa thức một biến, p. 39; Luyện tập
  chung p. 44; Bài tập cuối chương VII, p. 46.
- Chương VIII — LÀM QUEN VỚI BIẾN CỐ VÀ XÁC SUẤT CỦA BIẾN CỐ,
  p. 47: Bài 29 Làm quen với biến cố, p. 47; Bài 30 Làm quen
  với xác suất của biến cố, p. 51; Luyện tập chung p. 56; Bài
  tập cuối chương VIII, p. 58.
- Chương IX — QUAN HỆ GIỮA CÁC YẾU TỐ TRONG MỘT TAM GIÁC,
  p. 59: Bài 31 Quan hệ giữa góc và cạnh đối diện trong một
  tam giác, p. 59; Bài 32 Quan hệ giữa đường vuông góc và
  đường xiên, p. 63; Bài 33 Quan hệ giữa ba cạnh của một tam
  giác, p. 66; Luyện tập chung p. 70; Bài 34 Sự đồng quy của
  ba đường trung tuyến, ba đường phân giác trong một tam giác,
  p. 72; Bài 35 Sự đồng quy của ba đường trung trực, ba đường
  cao trong một tam giác, p. 77; Luyện tập chung p. 82; Bài
  tập cuối chương IX, p. 84.
- Chương X — MỘT SỐ HÌNH KHỐI TRONG THỰC TIỄN, p. 85: Bài 36
  Hình hộp chữ nhật và hình lập phương, p. 85; Luyện tập
  p. 92; Bài 37 Hình lăng trụ đứng tam giác và hình lăng trụ
  đứng tứ giác, p. 94; Luyện tập p. 100; Bài tập cuối chương X,
  p. 102.
- Hoạt động thực hành trải nghiệm: Đại lượng tỉ lệ trong đời
  sống, p. 103; Vòng quay may mắn, p. 106; Hộp quà và chân đế
  lịch để bàn của em, p. 108. Bài tập ôn tập cuối năm, p. 110.
  Bảng tra cứu thuật ngữ p. 114; Bảng giải thích thuật ngữ
  p. 115.

G7 v2 honest negatives: algebra is one-variable polynomials
only (no two-variable systems, no quadratic equations — those
are Grade 8/9); probability is "getting to know" events and
their probability (Bài 29–30) without a formal probability
formula chapter; triangle work is relations and concurrences
(medians, bisectors, perpendicular bisectors, altitudes) — no
congruence criteria here (those are v1's chapters, to confirm)
and no Pythagoras yet; solids are boxes, cubes and right prisms
only (no pyramids, cylinders, cones, spheres in v2).

## GRADE 8 — Toán 8, Tập Một + Tập Hai

### G8 v1 — 126 PDF pp. (Bài 1–20, chapters I–V)

Contents p. 4 (visual read; folio 4 = PDF 5, so printed =
PDF − 1). The preface (PDF 4, printed p. 3) states the book's
motto "Kết nối tri thức với cuộc sống" and the "Học đi đôi với
hành" (learn together with practice) message.

- Chương I — ĐA THỨC (Polynomials), p. 5: Bài 1 Đơn thức
  (monomials), p. 5; Bài 2 Đa thức, p. 11; Bài 3 Phép cộng và
  phép trừ đa thức, p. 15; Luyện tập chung p. 17; Bài 4 Phép
  nhân đa thức, p. 19; Bài 5 Phép chia đa thức cho đơn thức,
  p. 22; Luyện tập chung p. 25; Bài tập cuối chương I, p. 27.
- Chương II — HẰNG ĐẲNG THỨC ĐÁNG NHỚ VÀ ỨNG DỤNG (Notable
  identities and applications), p. 29: Bài 6 Hiệu hai bình
  phương. Bình phương của một tổng hay một hiệu, p. 29; Bài 7
  Lập phương của một tổng. Lập phương của một hiệu, p. 34;
  Bài 8 Tổng và hiệu hai lập phương, p. 37; Luyện tập chung
  p. 40; Bài 9 Phân tích đa thức thành nhân tử (factorising),
  p. 42; Luyện tập chung p. 45; Bài tập cuối chương II, p. 47.
- Chương III — TỨ GIÁC (Quadrilaterals), p. 48: Bài 10 Tứ giác,
  p. 48; Bài 11 Hình thang cân, p. 52; Luyện tập chung p. 56;
  Bài 12 Hình bình hành, p. 57; Luyện tập chung p. 62; Bài 13
  Hình chữ nhật, p. 64; Bài 14 Hình thoi và hình vuông, p. 67;
  Luyện tập chung p. 73; Bài tập cuối chương III, p. 74.
- Chương IV — ĐỊNH LÍ THALÈS (Thales' theorem), p. 76: Bài 15
  Định lí Thalès trong tam giác, p. 76; Bài 16 Đường trung bình
  của tam giác (midline), p. 81; Bài 17 Tính chất đường phân
  giác của tam giác (angle-bisector property), p. 84; Luyện tập
  chung p. 87; Bài tập cuối chương IV, p. 89.
- Chương V — DỮ LIỆU VÀ BIỂU ĐỒ (Data and charts), p. 90:
  Bài 18 Thu thập và phân loại dữ liệu, p. 90; Bài 19 Biểu diễn
  dữ liệu bằng bảng, biểu đồ, p. 93; Bài 20 Phân tích Số liệu
  thống kê dựa vào biểu đồ, p. 99; Luyện tập chung p. 106; Bài
  tập cuối chương V, p. 109.
- Hoạt động thực hành trải nghiệm: Công thức lãi kép (compound
  interest formula), p. 111; Thực hiện tính toán trên đa thức
  với phần mềm GeoGebra, p. 113; Vẽ hình đơn giản với phần mềm
  GeoGebra, p. 115; Phân tích đặc điểm khí hậu Việt Nam,
  p. 120. Bảng tra cứu thuật ngữ p. 122; Bảng giải thích thuật
  ngữ p. 123.

G8 v1 honest negatives: no equations chapter (polynomial work
stops at division by a monomial — no polynomial long division
by a polynomial, no equation-solving as a topic); no functions
or graphs; no Pythagoras (Thales and midlines, but the right-
triangle metric theorem is Grade 9's); no similarity as a named
topic (Thales is taught as a theorem about proportions, not
under the heading of similar triangles); statistics is
collecting/classifying/presenting/reading charts — no measures
of centre/spread chapter here.

### G8 v2 — 142 PDF pp. (Bài 21–39, chapters VI–X)

Contents p. 3 (visual read; folio 3 = PDF 4, so printed =
PDF − 1). Chapter VI's opener frames the chapter explicitly:
in Grade 7, from Z (integers) the set Q (rationals) was built;
likewise, from polynomials a new set — algebraic fractions —
is built here.

- Chương VI — PHÂN THỨC ĐẠI SỐ (Algebraic fractions), p. 4:
  Bài 21 Phân thức đại số, p. 4; Bài 22 Tính chất cơ bản của
  phân thức đại số, p. 8; Luyện tập chung p. 13; Bài 23 Phép
  cộng và phép trừ phân thức đại số, p. 15; Bài 24 Phép nhân
  và phép chia phân thức đại số, p. 20; Luyện tập chung p. 23;
  Bài tập cuối chương VI, p. 25.
- Chương VII — PHƯƠNG TRÌNH BẬC NHẤT VÀ HÀM SỐ BẬC NHẤT
  (First-degree equations and first-degree functions), p. 27:
  Bài 25 Phương trình bậc nhất một ẩn, p. 27; Bài 26 Giải bài
  toán bằng cách lập phương trình, p. 33; Luyện tập chung
  p. 37; Bài 27 Khái niệm hàm số và đồ thị của hàm số, p. 40;
  Bài 28 Hàm số bậc nhất và đồ thị của hàm số bậc nhất,
  p. 47; Bài 29 Hệ số góc của đường thẳng, p. 51; Luyện tập
  chung p. 55; Bài tập cuối chương VII, p. 57.
- Chương VIII — MỞ ĐẦU VỀ TÍNH XÁC SUẤT CỦA BIẾN CỐ
  (Introduction to probability of events), p. 59: Bài 30 Kết
  quả có thể và kết quả thuận lợi (possible and favourable
  outcomes), p. 59; Bài 31 Cách tính xác suất của biến cố bằng
  tỉ số (computing probability as a ratio), p. 63; Bài 32 Mối
  liên hệ giữa xác suất thực nghiệm với xác suất và ứng dụng
  (experimental vs theoretical probability), p. 67; Luyện tập
  chung p. 74; Bài tập cuối chương VIII, p. 76.
- Chương IX — TAM GIÁC ĐỒNG DẠNG (Similar triangles), p. 78:
  Bài 33 Hai tam giác đồng dạng, p. 78; Bài 34 Ba trường hợp
  đồng dạng của hai tam giác, p. 83; Luyện tập chung p. 91;
  Bài 35 Định lí Pythagore và ứng dụng, p. 93; Bài 36 Các
  trường hợp đồng dạng của hai tam giác vuông, p. 98; Bài 37
  Hình đồng dạng (similar figures), p. 104; Luyện tập chung
  p. 108; Bài tập cuối chương IX, p. 110.
- Chương X — MỘT SỐ HÌNH KHỐI TRONG THỰC TIỄN, p. 112:
  Bài 38 Hình chóp tam giác đều (regular triangular pyramid),
  p. 112; Bài 39 Hình chóp tứ giác đều, p. 117; Luyện tập chung
  p. 121; Bài tập cuối chương X, p. 123.
- Hoạt động thực hành trải nghiệm: Một vài ứng dụng của hàm
  số bậc nhất trong tài chính, p. 125; Ứng dụng định lí Thalès,
  định lí Pythagore và tam giác đồng dạng để đo chiều cao,
  khoảng cách, p. 128; Thực hành tính toán trên phân thức đại
  số và vẽ đồ thị hàm số với phần mềm GeoGebra, p. 130; Mô tả
  thí nghiệm ngẫu nhiên với phần mềm Excel, p. 133. Bài tập ôn
  tập cuối năm, p. 135. Bảng tra cứu thuật ngữ p. 138; Bảng
  giải thích thuật ngữ p. 139.

G8 v2 honest negatives: equations are first-degree in ONE
unknown only (Bài 25–26) — no systems, no quadratics; functions
are first-degree only (Bài 27–29); probability becomes
theoretical here (Bài 31: favourable/possible ratio) but stays
at equally-likely outcomes — no combinatorics, no conditional
probability; solids are regular pyramids only (no cones,
cylinders, spheres in v2 — cylinders appeared as nets in Grade
5, not as volume solids here).

### GRADE 8 summary

Grade 8 is the algebra/geometry hinge: multi-variable
polynomials and notable identities, factorisation, quadrilaterals
in full, Thales/midline/bisector, data charts with analysis,
then algebraic fractions, first-degree equations and functions
(with slope), theoretical probability, similarity and
Pythagoras, and regular pyramids. Note the arc: Thales (v1)
prepares similarity (v2), and similarity prepares Pythagoras
(Bài 35 sits inside the similarity chapter, not as a standalone
metric chapter).

## GRADE 9 — Toán 9, Tập Một + Tập Hai

### G9 v1 — 122 PDF pp. (Bài 1–17, chapters I–V)

Contents p. 4 (visual read; folio 4 = PDF 5, so printed =
PDF − 1).

- Chương I — PHƯƠNG TRÌNH VÀ HỆ HAI PHƯƠNG TRÌNH BẬC NHẤT
  HAI ẨN, p. 5: Bài 1 Khái niệm phương trình và hệ hai phương
  trình bậc nhất hai ẩn, p. 5; Bài 2 Giải hệ hai phương trình
  bậc nhất hai ẩn, p. 11; Luyện tập chung p. 19; Bài 3 Giải bài
  toán bằng cách lập hệ phương trình, p. 21; Bài tập cuối
  chương I, p. 24.
- Chương II — PHƯƠNG TRÌNH VÀ BẤT PHƯƠNG TRÌNH BẬC NHẤT MỘT
  ẨN, p. 26: Bài 4 Phương trình quy về phương trình bậc nhất
  một ẩn, p. 26; Bài 5 Bất đẳng thức và tính chất, p. 31;
  Luyện tập chung p. 36; Bài 6 Bất phương trình bậc nhất một
  ẩn, p. 38; Bài tập cuối chương II, p. 42.
- Chương III — CĂN BẬC HAI VÀ CĂN BẬC BA, p. 44: Bài 7 Căn bậc
  hai và căn thức bậc hai, p. 44; Bài 8 Khai căn bậc hai với
  phép nhân và phép chia, p. 49; Luyện tập chung p. 52; Bài 9
  Biến đổi đơn giản và rút gọn biểu thức chứa căn thức bậc
  hai, p. 54; Bài 10 Căn bậc ba và căn thức bậc ba, p. 60;
  Luyện tập chung p. 63; Bài tập cuối chương III, p. 65.
- Chương IV — HỆ THỨC LƯỢNG TRONG TAM GIÁC VUÔNG, p. 66:
  Bài 11 Tỉ số lượng giác của góc nhọn, p. 66; Bài 12 Một số hệ
  thức giữa cạnh, góc trong tam giác vuông và ứng dụng, p. 74;
  Luyện tập chung p. 79; Bài tập cuối chương IV, p. 81.
- Chương V — ĐƯỜNG TRÒN, p. 83: Bài 13 Mở đầu về đường tròn,
  p. 83; Bài 14 Cung và dây của một đường tròn, p. 87; Bài 15
  Độ dài của cung tròn. Diện tích hình quạt tròn và hình vành
  khuyên, p. 91; Luyện tập chung p. 96; Bài 16 Vị trí tương đối
  của đường thẳng và đường tròn, p. 99; Bài 17 Vị trí tương đối
  của hai đường tròn, p. 104; Luyện tập chung p. 108; Bài tập
  cuối chương V, p. 112.
- Hoạt động thực hành trải nghiệm: Pha chế dung dịch theo nồng
  độ yêu cầu, p. 114; Tính chiều cao và xác định khoảng cách,
  p. 116. Bảng tra cứu từ ngữ p. 118; Bảng giải thích thuật
  ngữ p. 119.

### G9 v2 — 134 PDF pp. (Bài 18–32, chapters VI–X)

Contents p. 3 (visual read; folio 3 = PDF 4, so printed =
PDF − 1).

- Chương VI — HÀM SỐ y = ax² (a ≠ 0). PHƯƠNG TRÌNH BẬC HAI
  MỘT ẨN, p. 4: Bài 18 Hàm số y = ax² (a ≠ 0), p. 4; Bài 19
  Phương trình bậc hai một ẩn, p. 10; Luyện tập chung p. 18;
  Bài 20 Định lí Viète và ứng dụng, p. 21; Bài 21 Giải bài toán
  bằng cách lập phương trình, p. 25; Luyện tập chung p. 28;
  Bài tập cuối chương VI, p. 30.
- Chương VII — TẦN SỐ VÀ TẦN SỐ TƯƠNG ĐỐI, p. 32: Bài 22 Bảng
  tần số và biểu đồ tần số, p. 32; Bài 23 Bảng tần số tương
  đối và biểu đồ tần số tương đối, p. 38; Luyện tập chung
  p. 43; Bài 24 Bảng tần số, tần số tương đối ghép nhóm và
  biểu đồ, p. 46; Bài tập cuối chương VII, p. 54.
- Chương VIII — XÁC SUẤT CỦA BIẾN CỐ TRONG MỘT SỐ MÔ HÌNH
  XÁC SUẤT ĐƠN GIẢN, p. 56: Bài 25 Phép thử ngẫu nhiên và
  không gian mẫu, p. 56; Bài 26 Xác suất của biến cố liên quan
  tới phép thử, p. 60; Luyện tập chung p. 64; Bài tập cuối
  chương VIII, p. 66.
- Chương IX — ĐƯỜNG TRÒN NGOẠI TIẾP VÀ ĐƯỜNG TRÒN NỘI TIẾP,
  p. 67: Bài 27 Góc nội tiếp, p. 67; Bài 28 Đường tròn ngoại
  tiếp và đường tròn nội tiếp của một tam giác, p. 72; Luyện
  tập chung p. 78; Bài 29 Tứ giác nội tiếp, p. 80; Bài 30 Đa
  giác đều, p. 84; Luyện tập chung p. 90; Bài tập cuối chương
  IX, p. 92.
- Chương X — MỘT SỐ HÌNH KHỐI TRONG THỰC TIỄN, p. 93: Bài 31
  Hình trụ và hình nón, p. 93; Bài 32 Hình cầu, p. 101; Luyện
  tập chung p. 106; Bài tập cuối chương X, p. 108.
- Hoạt động thực hành trải nghiệm: Giải phương trình, hệ
  phương trình và vẽ đồ thị hàm số với phần mềm GeoGebra,
  p. 111; Vẽ hình đơn giản với phần mềm GeoGebra, p. 115; Xác
  định tần số, tần số tương đối, vẽ các biểu đồ biểu diễn bằng
  tần số, tần số tương đối bằng Excel, p. 120; Gene trội trong
  các thế hệ lai, p. 125. Bài tập ôn tập cuối năm, p. 127.
  Bảng tra cứu thuật ngữ p. 130; Bảng giải thích từ ngữ p. 131.

G9 honest negatives: no logarithms or exponentials; no
trigonometry beyond acute-angle ratios and right-triangle
relations (no sine/cosine rules for general triangles, no
trigonometric functions/graphs); no calculus; no vectors or
coordinate geometry beyond function graphs; probability stays
in simple models (Bài 25–26: random trials, sample spaces,
event probability) — no conditional probability, no
distributions; statistics is frequency/relative-frequency
tables and charts (grouped included, Bài 24) — no mean/
variance/standard-deviation chapter in Grade 9.

### GRADE 9 summary

Grade 9 completes lower secondary: two-unknown linear systems,
first-degree equations/inequalities (including equations
reducible to first-degree), square/cube roots and radical
manipulation, right-triangle trigonometry (ratios + side-angle
relations), the circle in full (arcs, chords, sectors, annuli,
relative positions, inscribed angles, cyclic quadrilaterals,
regular polygons), quadratic functions and equations with
Viète, frequency statistics, simple-model probability, and
cylinders, cones and spheres. It is the last grade taught in
two volumes; Grades 10–12 switch to a single book per volume
plus a study-topics book.

### BAND C summary (Grades 7–9)

The lower-secondary arc: Grade 7 builds rationals → reals →
congruence → proportions → one-variable polynomials → event
probability language → triangle relations/concurrences. Grade 8
adds multi-variable polynomials, identities, factorisation,
quadrilaterals, Thales, then algebraic fractions, first-degree
equations/functions, theoretical probability, similarity,
Pythagoras and pyramids. Grade 9 adds systems, inequalities,
radicals, trigonometry, circles, quadratics, frequency
statistics, simple-model probability and round solids. No grade
in the band teaches logarithms, general-triangle trigonometry,
vectors, coordinate geometry beyond graphs, calculus, or
conditional probability.

# Band D — Grades 10–12 (9 files, 891 PDF pages)

## GRADE 10 — Toán 10, Tập Một + Tập Hai + Chuyên đề học tập Toán 10

### G10 v1 — 106 PDF pp. (Bài 1–14, chapters I–V)

Contents p. 4 (visual read; folio 4 = PDF 5, so printed =
PDF − 1).

- Chương I — MỆNH ĐỀ VÀ TẬP HỢP, p. 5: Bài 1 Mệnh đề
  (propositions), p. 5; Bài 2 Tập hợp và các phép toán trên tập
  hợp, p. 12; Bài tập cuối chương I, p. 20.
- Chương II — BẤT PHƯƠNG TRÌNH VÀ HỆ BẤT PHƯƠNG TRÌNH BẬC
  NHẤT HAI ẨN, p. 22: Bài 3 Bất phương trình bậc nhất hai ẩn,
  p. 22; Bài 4 Hệ bất phương trình bậc nhất hai ẩn, p. 26; Bài
  tập cuối chương II, p. 31.
- Chương III — HỆ THỨC LƯỢNG TRONG TAM GIÁC, p. 33: Bài 5 Giá
  trị lượng giác của một góc từ 0° đến 180°, p. 33; Bài 6 Hệ
  thức lượng trong tam giác (sine rule, cosine rule, area
  formulas), p. 38; Bài tập cuối chương III, p. 44.
- Chương IV — VECTƠ, p. 46: Bài 7 Các khái niệm mở đầu, p. 46;
  Bài 8 Tổng và hiệu của hai vectơ, p. 51; Bài 9 Tích của một
  vectơ với một số, p. 55; Bài 10 Vectơ trong mặt phẳng tọa
  độ, p. 60; Bài 11 Tích vô hướng của hai vectơ, p. 66; Bài
  tập cuối chương IV, p. 71.
- Chương V — CÁC SỐ ĐẶC TRƯNG CỦA MẪU SỐ LIỆU KHÔNG GHÉP
  NHÓM, p. 73: Bài 12 Số gần đúng và sai số (approximate
  numbers and errors), p. 73; Bài 13 Các số đặc trưng đo xu thế
  trung tâm (mean, median, mode, quartiles as central-tendency
  measures), p. 78; Bài 14 Các Số đặc trưng đo độ phân tán
  (range, interquartile range, variance, standard deviation),
  p. 84; Bài tập cuối chương V, p. 89.
- Hoạt động thực hành trải nghiệm: Tìm hiểu một số kiến thức
  về tài chính, p. 91; Mạng xã hội: Lợi và hại, p. 96. Bảng tra
  cứu thuật ngữ p. 102; Bảng giải thích thuật ngữ p. 103.

### G10 v2 — 102 PDF pp. (Bài 15–27, chapters VI–IX)

Contents p. 3 (visual read; folio 3 = PDF 4, so printed =
PDF − 1).

- Chương VI — HÀM SỐ, ĐỒ THỊ VÀ ỨNG DỤNG, p. 4: Bài 15 Hàm
  số, p. 4; Bài 16 Hàm số bậc hai, p. 11; Bài 17 Dấu của tam
  thức bậc hai, p. 19; Bài 18 Phương trình quy về phương trình
  bậc hai, p. 25; Bài tập cuối chương VI, p. 28.
- Chương VII — PHƯƠNG PHÁP TỌA ĐỘ TRONG MẶT PHẲNG, p. 30:
  Bài 19 Phương trình đường thẳng, p. 30; Bài 20 Vị trí tương
  đối giữa hai đường thẳng. Góc và khoảng cách, p. 36; Bài 21
  Đường tròn trong mặt phẳng tọa độ, p. 43; Bài 22 Ba đường
  conic, p. 48; Bài tập cuối chương VII, p. 58.
- Chương VIII — ĐẠI SỐ TỔ HỢP, p. 60: Bài 23 Quy tắc đếm,
  p. 60; Bài 24 Hoán vị, chỉnh hợp và tổ hợp, p. 66; Bài 25
  Nhị thức Newton, p. 72; Bài tập cuối chương VIII, p. 76.
- Chương IX — TÍNH XÁC SUẤT THEO ĐỊNH NGHĨA CỔ ĐIỂN, p. 77:
  Bài 26 Biến cố và định nghĩa cổ điển của xác suất, p. 77;
  Bài 27 Thực hành tính xác suất theo định nghĩa cổ điển,
  p. 83; Bài tập cuối chương IX, p. 88.
- Hoạt động thực hành trải nghiệm: Một số nội dung cho hoạt
  động trải nghiệm hình học, p. 90; Ước tính số cá thể trong
  một quần thể, p. 93. Bài tập ôn tập cuối năm, p. 95. Bảng tra
  cứu thuật ngữ p. 98; Bảng giải thích thuật ngữ p. 99.

### G10 study — Chuyên đề học tập Toán 10 — 67 PDF pp. (Bài 1–8, 3 topics)

Preface (printed p. 3) states the book's three topics and their
purpose: deeper-but-not-harder extensions of the main books,
with more real-life applications; conic sections are introduced
with their history (known since the 3rd century BC, Apollonius;
Kepler's laws in the 17th century) and their links from
architecture to reflecting mirrors. Front matter runs one page
longer than the student books: how-to-use printed p. 2 = PDF 4,
preface printed p. 3 = PDF 5, contents printed p. 4 = PDF 6, so
printed = PDF − 2 in this book.

- Chuyên đề 1 — HỆ PHƯƠNG TRÌNH BẬC NHẤT BA ẨN, p. 5: Bài 1
  Hệ phương trình bậc nhất ba ẩn, p. 5; Bài 2 Ứng dụng của hệ
  phương trình bậc nhất ba ẩn, p. 15; Bài tập cuối chuyên đề
  1, p. 23.
- Chuyên đề 2 — PHƯƠNG PHÁP QUY NẠP TOÁN HỌC. NHỊ THỨC
  NEWTON, p. 25: Bài 3 Phương pháp quy nạp toán học
  (mathematical induction — the first formal proof method in
  the series), p. 25; Bài 4 Nhị thức Newton, p. 32; Bài tập
  cuối chuyên đề 2, p. 38.
- Chuyên đề 3 — BA ĐƯỜNG CONIC VÀ ỨNG DỤNG, p. 39: Bài 5
  Elip, p. 39; Bài 6 Hypebol, p. 47; Bài 7 Parabol, p. 54;
  Bài 8 Sự thống nhất giữa ba đường conic, p. 57; Bài tập
  cuối chuyên đề 3, p. 61. Bảng tra cứu thuật ngữ p. 62; Bảng
  giải thích thuật ngữ p. 63.

G10 study-topics note: the study book extends, and partly
duplicates, main-book topics — three-unknown systems extend
Grade 9's two-unknown systems; Newton's binomial extends v2's
Bài 25 (same theorem, now with induction proofs); conics extend
v2's Bài 22 (coordinate conics) with dedicated ellipse/
hyperbola/parabola lessons and a unification lesson. For course
building these are enrichment, not the first teaching of the
topics (except induction, which is new here).

G10 honest negatives: no calculus (no limits, derivatives or
integrals); no logarithms/exponentials; no complex numbers; no
3-D geometry (vectors and coordinates stay in the plane);
probability is classical-definition only (Bài 26–27) — no
conditional probability, no distributions; statistics is
ungrouped samples only in v1 chapter V (grouped data waits for
Grade 11/12).

## GRADE 11 — Toán 11, Tập Một + Tập Hai + Chuyên đề học tập Toán 11

### G11 v1 — 135 PDF pp. (Bài 1–17, chapters I–V)

Contents p. 4 (visual read; folio 4 = PDF 6, so printed =
PDF − 2). The preface names the book's modelling thread:
chapters and lessons start from real-life situations, and the
citizen skill trained throughout is "mô hình hoá" (modelling)
— turning a real problem into a mathematical model, learning
new maths from it, then returning the maths to the real problem.

- Chương I — HÀM SỐ LƯỢNG GIÁC VÀ PHƯƠNG TRÌNH LƯỢNG GIÁC,
  p. 5: Bài 1 Giá trị lượng giác của góc lượng giác, p. 5;
  Bài 2 Công thức lượng giác, p. 17; Bài 3 Hàm số lượng giác,
  p. 22; Bài 4 Phương trình lượng giác cơ bản, p. 31; Bài tập
  cuối chương I, p. 40.
- Chương II — DÃY SỐ. CẤP SỐ CỘNG VÀ CẤP SỐ NHÂN, p. 42:
  Bài 5 Dãy số, p. 42; Bài 6 Cấp số cộng, p. 48; Bài 7 Cấp số
  nhân, p. 52; Bài tập cuối chương II, p. 56.
- Chương III — CÁC SỐ ĐẶC TRƯNG ĐO XU THẾ TRUNG TÂM CỦA MẪU
  SỐ LIỆU GHÉP NHÓM, p. 58: Bài 8 Mẫu số liệu ghép nhóm, p. 58;
  Bài 9 Các số đặc trưng đo xu thế trung tâm, p. 62; Bài tập
  cuối chương III, p. 69.
- Chương IV — QUAN HỆ SONG SONG TRONG KHÔNG GIAN, p. 70:
  Bài 10 Đường thẳng và mặt phẳng trong không gian, p. 70;
  Bài 11 Hai đường thẳng song song, p. 78; Bài 12 Đường thẳng
  và mặt phẳng song song, p. 84; Bài 13 Hai mặt phẳng song
  song, p. 88; Bài 14 Phép chiếu song song, p. 95; Bài tập cuối
  chương IV, p. 102.
- Chương V — GIỚI HẠN. HÀM SỐ LIÊN TỤC, p. 104: Bài 15 Giới
  hạn của dãy số, p. 104; Bài 16 Giới hạn của hàm số, p. 111;
  Bài 17 Hàm số liên tục, p. 119; Bài tập cuối chương V,
  p. 123.
- Hoạt động thực hành trải nghiệm: Một vài áp dụng của Toán
  học trong tài chính, p. 125; Lực căng mặt ngoài của nước,
  p. 128. Bảng tra cứu thuật ngữ p. 130; Bảng giải thích thuật
  ngữ p. 131.

### G11 v2 — 115 PDF pp. (Bài 18–33, chapters VI–IX)

Contents p. 3 (visual read; folio 3 = PDF 5, so printed =
PDF − 2). Chapter VI's opener states its arc: powers with
natural exponents are extended to rational, then real,
exponents, and from that the logarithm is formed; exponential
and logarithmic functions follow, and the chapter closes with
simple exponential/logarithmic equations and inequalities.

- Chương VI — HÀM SỐ MŨ VÀ HÀM SỐ LÔGARIT, p. 4: Bài 18 Lũy
  thừa với số mũ thực, p. 4; Bài 19 Lôgarit, p. 10; Bài 20 Hàm
  số mũ và hàm số lôgarit, p. 16; Bài 21 Phương trình, bất
  phương trình mũ và lôgarit, p. 20; Bài tập cuối chương VI,
  p. 25.
- Chương VII — QUAN HỆ VUÔNG GÓC TRONG KHÔNG GIAN, p. 27:
  Bài 22 Hai đường thẳng vuông góc, p. 27; Bài 23 Đường thẳng
  vuông góc với mặt phẳng, p. 31; Bài 24 Phép chiếu vuông góc.
  Góc giữa đường thẳng và mặt phẳng, p. 38; Bài 25 Hai mặt
  phẳng vuông góc, p. 44; Bài 26 Khoảng cách, p. 54; Bài 27
  Thể tích, p. 61; Bài tập cuối chương VII, p. 64.
- Chương VIII — CÁC QUY TẮC TÍNH XÁC SUẤT, p. 66: Bài 28 Biến
  cố hợp, biến cố giao, biến cố độc lập, p. 66; Bài 29 Công
  thức cộng xác suất, p. 72; Bài 30 Công thức nhân xác suất
  cho hai biến cố độc lập, p. 76; Bài tập cuối chương VIII,
  p. 79.
- Chương IX — ĐẠO HÀM, p. 81: Bài 31 Định nghĩa và ý nghĩa
  của đạo hàm, p. 81; Bài 32 Các quy tắc tính đạo hàm, p. 88;
  Bài 33 Đạo hàm cấp hai, p. 95; Bài tập cuối chương IX,
  p. 97.
- Hoạt động thực hành trải nghiệm: Một vài mô hình toán học sử
  dụng hàm số mũ và hàm số lôgarit, p. 99; Hoạt động thực hành
  trải nghiệm Hình học, p. 102. Bài tập ôn tập cuối năm,
  p. 105. Bảng tra cứu thuật ngữ p. 110; Bảng giải thích thuật
  ngữ p. 111.

### G11 study — Chuyên đề học tập Toán 11 — 87 PDF pp. (Bài 1–12, 3 topics)

Contents p. 4 (visual read; folio 4 = PDF 6, so printed =
PDF − 2).

- Chuyên đề 1 — PHÉP BIẾN HÌNH TRONG MẶT PHẲNG
  (Transformations in the plane), p. 5: Bài 1 Phép biến hình,
  p. 5; Bài 2 Phép tịnh tiến (translation), p. 9; Bài 3 Phép
  đối xứng trục (axial symmetry), p. 12; Bài 4 Phép quay và
  phép đối xứng tâm (rotation and central symmetry), p. 16;
  Bài 5 Phép dời hình (isometry), p. 21; Bài 6 Phép vị tự
  (homothety), p. 26; Bài 7 Phép đồng dạng (similarity
  transformation), p. 30; Bài tập cuối chuyên đề 1, p. 33.
- Chuyên đề 2 — LÀM QUEN VỚI MỘT VÀI KHÁI NIỆM CỦA LÍ THUYẾT
  ĐỒ THỊ (Introduction to some graph-theory concepts), p. 34:
  Bài 8 Một vài khái niệm cơ bản, p. 34; Bài 9 Đường đi Euler
  và đường đi Hamilton, p. 41; Bài 10 Bài toán tìm đường đi
  tối ưu trong một vài trường hợp đơn giản, p. 46; Bài tập
  cuối chuyên đề 2, p. 50.
- Chuyên đề 3 — MỘT SỐ YẾU TỐ VỀ KĨ THUẬT (Some technical
  elements), p. 52: Bài 11 Hình chiếu vuông góc và hình chiếu
  trục đo (orthogonal and axonometric projections), p. 52;
  Bài 12 Bản vẽ kĩ thuật (technical drawing), p. 68; Bài tập
  cuối chuyên đề 3, p. 80. Bảng tra cứu thuật ngữ p. 82; Bảng
  giải thích thuật ngữ p. 83.

G11 study-topics note: all three topics are NEW material, not
extensions of main-book chapters — plane transformations (the
main books teach symmetry only as shape properties, never as
mappings), graph theory (Euler/Hamilton paths, shortest-path
problems — nowhere in the main books), and technical drawing
(projections and engineering drawings). For course building
these are the series' only treatment of transformations-as-
functions and of graphs.

G11 honest negatives: no integrals (derivatives only, and only
to second order, Bài 33); no complex numbers; no vectors in
space as a topic (space work is synthetic: parallelism,
perpendicularity, distance, volume); no distributions (the
probability rules stay at union/intersection/independence and
the addition/multiplication formulas); no matrices.

## GRADE 12 — Toán 12, Tập Một + Tập Hai + Chuyên đề học tập Toán 12

### G12 v1 — 104 PDF pp. (Bài 1–10, chapters I–III)

Contents p. 4 (visual read; folio 4 = PDF 6, so printed =
PDF − 2). The preface repeats Grade 11's modelling thread
("mô hình hoá") for the final year.

- Chương I — ỨNG DỤNG ĐẠO HÀM ĐỂ KHẢO SÁT VÀ VẼ ĐỒ THỊ HÀM
  SỐ, p. 5: Bài 1 Tính đơn điệu và cực trị của hàm số
  (monotonicity and extrema), p. 5; Bài 2 Giá trị lớn nhất và
  giá trị nhỏ nhất của hàm số, p. 15; Bài 3 Đường tiệm cận của
  đồ thị hàm số (asymptotes), p. 20; Bài 4 Khảo sát sự biến
  thiên và vẽ đồ thị của hàm số, p. 26; Bài 5 Ứng dụng đạo hàm
  để giải quyết một số vấn đề liên quan đến thực tiễn, p. 33;
  Bài tập cuối chương I, p. 42.
- Chương II — VECTƠ VÀ HỆ TRỤC TỌA ĐỘ TRONG KHÔNG GIAN,
  p. 45: Bài 6 Vectơ trong không gian, p. 45; Bài 7 Hệ trục tọa
  độ trong không gian, p. 60; Bài 8 Biểu thức tọa độ của các
  phép toán vectơ, p. 67; Bài tập cuối chương II, p. 73.
- Chương III — CÁC SỐ ĐẶC TRƯNG ĐO MỨC ĐỘ PHÂN TÁN CỦA MẪU
  SỐ LIỆU GHÉP NHÓM, p. 75: Bài 9 Khoảng biến thiên và khoảng
  tứ phân vị (range and interquartile range), p. 75; Bài 10
  Phương sai và độ lệch chuẩn (variance and standard
  deviation), p. 80; Bài tập cuối chương III, p. 85.
- Hoạt động thực hành trải nghiệm: Khảo sát và vẽ đồ thị hàm
  số với phần mềm GeoGebra, p. 87; Vẽ vectơ tổng của ba vectơ
  trong không gian bằng phần mềm GeoGebra, p. 92; Độ dài gang
  tay (gang tay của bạn dài bao nhiêu?), p. 94. Bảng tra cứu
  từ ngữ p. 99; Bảng giải thích thuật ngữ p. 100.

### G12 v2 — 99 PDF pp. (Bài 11–19, chapters IV–VI)

Contents p. 3 (visual read; folio 3 = PDF 5, so printed =
PDF − 2).

- Chương IV — NGUYÊN HÀM VÀ TÍCH PHÂN, p. 4: Bài 11 Nguyên
  hàm (antiderivatives), p. 4; Bài 12 Tích phân (integrals),
  p. 12; Bài 13 Ứng dụng hình học của tích phân (geometric
  applications: areas/volumes), p. 19; Bài tập cuối chương IV,
  p. 27.
- Chương V — PHƯƠNG PHÁP TỌA ĐỘ TRONG KHÔNG GIAN, p. 29:
  Bài 14 Phương trình mặt phẳng, p. 29; Bài 15 Phương trình
  đường thẳng trong không gian, p. 41; Bài 16 Công thức tính
  góc trong không gian, p. 50; Bài 17 Phương trình mặt cầu,
  p. 54; Bài tập cuối chương V, p. 61.
- Chương VI — XÁC SUẤT CÓ ĐIỀU KIỆN, p. 64: Bài 18 Xác suất
  có điều kiện (conditional probability), p. 64; Bài 19 Công
  thức xác suất toàn phần và công thức Bayes (total probability
  and Bayes' formula), p. 72; Bài tập cuối chương VI, p. 79.
- Hoạt động thực hành trải nghiệm: Tính nguyên hàm và tích
  phân với phần mềm GeoGebra. Tính gần đúng tích phân bằng
  phương pháp hình thang (trapezium approximation), p. 81; Vẽ
  đồ họa 3D với phần mềm GeoGebra, p. 85. Bài tập ôn tập cuối
  năm, p. 90. Bảng tra cứu từ ngữ p. 94; Bảng giải thích thuật
  ngữ p. 95.

### G12 study — Chuyên đề học tập Toán 12 — 76 PDF pp. (Bài 1–7, 3 topics)

Contents p. 4 (visual read; folio 4 = PDF 6, so printed =
PDF − 2).

- Chuyên đề 1 — BIẾN NGẪU NHIÊN RỜI RẠC. CÁC SỐ ĐẶC TRƯNG
  CỦA BIẾN NGẪU NHIÊN RỜI RẠC (Discrete random variables and
  their characteristics), p. 5: Bài 1 Biến ngẫu nhiên rời rạc
  và các số đặc trưng, p. 5; Bài 2 Biến ngẫu nhiên có phân bố
  nhị thức và áp dụng (binomial distribution and applications),
  p. 15; Bài tập cuối chuyên đề 1, p. 22.
- Chuyên đề 2 — ỨNG DỤNG TOÁN HỌC ĐỂ GIẢI QUYẾT MỘT SỐ BÀI
  TOÁN TỐI ƯU (Applying maths to optimisation problems),
  p. 23: Bài 3 Vận dụng hệ bất phương trình bậc nhất hai ẩn
  để giải quyết một số bài toán quy hoạch tuyến tính (linear
  programming via two-unknown linear inequality systems),
  p. 23; Bài 4 Vận dụng đạo hàm để giải quyết một số bài toán
  tối ưu, p. 34; Bài tập cuối chuyên đề 2, p. 44.
- Chuyên đề 3 — ỨNG DỤNG TOÁN HỌC TRONG MỘT SỐ VẤN ĐỀ LIÊN
  QUAN ĐẾN TÀI CHÍNH (Applying maths to financial questions),
  p. 46: Bài 5 Tiền tệ. Lãi suất (money; interest rates),
  p. 46; Bài 6 Tín dụng. Vay nợ (credit; borrowing), p. 54;
  Bài 7 Đầu tư tài chính. Lập kế hoạch tài chính cá nhân
  (financial investment; personal financial planning), p. 60;
  Bài tập cuối chuyên đề 3, p. 70. Bảng tra cứu từ ngữ p. 71;
  Bảng giải thích thuật ngữ p. 72.

G12 study-topics note: topic 1 is the series' ONLY treatment of
random variables and distributions (the main books reach
conditional probability and Bayes but never define a random
variable); topics 2–3 are applications of main-book tools
(inequality systems, derivatives) to optimisation and finance,
not new theory.

G12 honest negatives: no differential equations; no complex
numbers anywhere in Grades 10–12; no matrices/determinants;
no multivariable calculus; no continuous distributions (the
binomial in the study book is discrete only); no hypothesis
testing or confidence intervals (statistics ends at grouped-
sample spread measures plus the study book's discrete random
variables).

### BAND D summary (Grades 10–12)

Upper secondary completes the series: Grade 10 adds logic and
sets, two-unknown inequalities, general-triangle trigonometry
(sine/cosine rules), plane vectors with dot products, ungrouped
sample statistics, functions and quadratics revisited, plane
coordinate geometry with conics, combinatorics, and classical
probability — plus study topics in three-unknown systems,
induction/Newton's binomial, and conics. Grade 11 adds trig
functions and equations, sequences, grouped-sample central
tendency, space parallelism, limits and continuity, exponentials
and logarithms, space perpendicularity/distance/volume,
probability rules, and derivatives — plus study topics in plane
transformations, graph theory, and technical drawing. Grade 12
adds derivative applications (monotonicity, extrema, asymptotes,
curve sketching), space vectors and coordinates, grouped-sample
spread, antiderivatives and integrals with geometric
applications, space coordinate geometry (planes, lines, angles,
spheres), and conditional probability with Bayes — plus study
topics in discrete random variables (including the binomial),
optimisation (linear programming, derivative methods), and
financial maths. The series' ceiling is single-variable calculus
(derivatives to second order, integrals of one variable) plus
Bayes; it never reaches complex numbers, matrices, differential
equations, or continuous distributions.

### GRADE 10–12 structure note (no tracks)

Grades 10–12 are taught from ONE student book per volume plus
ONE study-topics book — there is no separate science/social-
science track split inside these books. The study-topics books
are enrichment/extension volumes (some topics new: induction,
transformations, graph theory, random variables; some deeper
re-treatments: conics, binomial, optimisation, finance), not
track alternatives. Any course mapping that assumes a
Vietnamese maths track split would be wrong for this series.

## Citation checks

Separate check pass (checker pass after reading): 18 anchors
per distinct work, each verified on the exact PDF page in the
real book — contents page or lesson-opener/title page.
Evidence: liqlearns-courses-work/vietnam-maths/anchors.md
(504 anchors) and check-blocks.md (full method and page list).

- **Band A (Grades 1–4, 144 anchors): 144 passed, 0 corrected
  in check, 0 not found.** 7 anchors had been corrected during
  reading from opener pages (G2 v1 Bài 20, G2 v2 Bài 70, G3 v1
  Bài 37, G3 v2 Bài 50/56/73/76); the check confirmed them.
- **Band B (Grades 5–6, 90 anchors): 90 passed, 0 corrected in
  check, 0 not found.** 4 anchors had been corrected during
  reading from visual contents (G6 v1 Bài 2/20/21, G6 v2
  Bài 42); the check confirmed them.
- **Band C (Grades 7–9, 108 anchors): 108 passed, 0 corrected
  in check, 0 not found.** All contents pages read visually.
- **Band D (Grades 10–12, 162 anchors): 162 passed, 0 corrected
  in check, 0 not found.** All contents pages read visually.
- **Total: 504 passed, 0 corrected in check, 0 not found.**
  11 anchors in total reached the check already corrected
  during reading (listed above); the check pass itself changed
  nothing.

