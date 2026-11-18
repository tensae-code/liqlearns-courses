# About the History — Iran course

**The first page (what learners are told):** everything in this course comes from government textbooks — Iran's own Ministry of Education History and Social Studies books. The one exception is the **Tip boxes**: a tip in a box is from us, the people making LiqLearns. Tips are ours; the lessons are the books'.

## How this course is organised

This is ONE course for Iran inside the History folder (one course per country). Inside it, the organisation is by **levels, not grades**: a learner's place is found by what they prove, and each level stands on the ones before it as a recommended-first path — never a forced gate. The school grades the books come from appear only in each lesson's `lesson/sources.md`, as provenance.

The course as built has **six levels**, following the story as Iran's own books present it in their spiral (see CURRICULUM.md for the derivation): Level 1 — first steps: how history is known (7 lessons); Level 2 — the ancient world and ancient Iran (17 lessons); Level 3 — Islam and the Iranian-Islamic civilisation (13 lessons); Level 4 — Mongols, Timurids and the Safavid state (6 lessons); Level 5 — Qajars, constitution and the Pahlavis (19 lessons); Level 6 — oil, revolution, republic and war (18 lessons).

**Course-intro video script** (written here, made later; the books' own shape, walked in order):

- *The arc whole:* "First, how history is known at all — heritage, evidence, dates and the spade. Then the ancient world whole, and ancient Iran at its centre: Elam, Cyrus, the Medes, Persepolis, and how an empire was ruled, fed and believed. Then Islam arrives, and Iran answers with its own Islamic civilisation — dynasties, viziers, scientists. Then catastrophe and flowering: Mongols, Timurids, and the Safavids who weld Iran into one state. Then the hard modern centuries — Qajars, a constitution won and defended, Reza Shah, occupation — and at the top oil, a coup, a revolution, a republic and an eight-year war, closing on the symbols and days that hold the story together."

## The books (Iran)

Book entries are named in full in each lesson's `lesson/sources.md`. The set in hand for this build — 18 records / 11 distinct books, grabbed via grab.py — the books.json tree paths 404 (see library debts), so the TSV release-asset routes were used; byte size and page count verified against books.json, cover rendered and checked, full Persian text extracted with pdftotext -layout and read (contents + every lesson); placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`:

**Student books:**

**Book 1:** History 1, Grade 10 (student book, Persian)
- Title as printed: تاریخ (۱) ایران و جهان باستان — History (1): Iran and the Ancient World
- Grade: Grade 10, Humanities branch (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning (سازمان پژوهش و برنامه‌ریزی آموزشی), Tehran; year 1405–1406 (2026–27); ISBN no ISBN printed (book code 110219)
- PDF pages: 168 (cover/title page verified against the record title)
- Verdict: COMPLETE
- Tally: 21 placements — 12 to existing lessons, 9 NEW LESSON NEEDED
- Iran's own way: a full first chapter on how history itself is known (historiography, time and place, archaeology) before any narrative; "examining evidence and documents" (بررسی شواهد و مدارک) source boxes run through every lesson, and the ancient-Iran chapter is organised by theme (statecraft, society, economy, religion, language/science, art) after the dynastic story — identity ("the beginning of Iranian identity") is the chapter's stated frame.
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 2:** History 2, Grade 11 (student book, Persian)
- Title as printed: تاریخ (۲) از بعثت پیامبر اسلام تا پایان صفویه — History (2): From the Prophet of Islam's mission to the end of the Safavids
- Grade: Grade 11, Humanities branch (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN no ISBN printed (book code 111219)
- PDF pages: 216 (cover/title page verified against the record title; byte size 11,426,218 and page count match the books.json record exactly. NOTE: the record's TSV URL duplicates the Contemporary History release asset; this book was fetched from the same release under its own asset name grade-11-gov-iran-history-student-full-year.pdf — see library debts)
- Verdict: COMPLETE
- Tally: 16 placements — 6 to existing lessons, 10 NEW LESSON NEEDED
- Iran's own way: the Islamic centuries are told twice — once as the caliphate's story (Mecca, Medina, Umayyads, Abbasids) and once as Iran's own (local dynasties, Mongol catastrophe and Timurid flowering, Safavid state-building) — with Europe's Middle Ages and Renaissance appended as the outside mirror, and source-validity method taught first.
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 3:** Contemporary History of Iran, Grade 11 (student book, Persian)
- Title as printed: تاریخ معاصر ایران — Contemporary History of Iran (for all branches except Humanities and Islamic Sciences)
- Grade: Grade 11 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN no ISBN printed (book code 111220)
- PDF pages: 271 (cover/title page verified against the record title; byte size 5,525,706 and page count match the books.json record)
- Verdict: COMPLETE
- Tally: 27 placements — 0 to existing lessons, 27 NEW LESSON NEEDED
- Iran's own way: contemporary history is written as one long struggle against two enemies named in lesson 4's title — "internal despotism and foreign colonialism" — with Britain, Russia and then America as the recurring outside hand; the preface orders teachers to use "scientific, analytical historiography" (causes and effects, documents) instead of chronicle memorisation.
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 4:** History 3, Grade 12 (student book, Persian)
- Title as printed: تاریخ (۳) ایران و جهان معاصر — History (3): Contemporary Iran and the World
- Grade: Grade 12, Humanities branch (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406 (text revised 1399–1400); ISBN no ISBN printed (book code 112219)
- PDF pages: 176 (cover/title page verified against the record title; byte size 7,837,886 and page count match the books.json record)
- Verdict: COMPLETE
- Tally: 14 placements — 4 to existing lessons, 10 NEW LESSON NEEDED
- Iran's own way: the Humanities track re-tells the same two centuries as the Grade 11 general book but analytically and with the world wars given their own lessons — Iran's story is repeatedly set inside the world's (WWI, WWII and the post-1945 order), and the course still opens with historiography and sources before narrative.
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 5:** Social Studies, Grade 7 (student book, Persian) — COMBINED Civics–Geography–History
- Title as printed: مطالعات اجتماعی (مدنی، جغرافیا، تاریخ) — Social Studies (Civics, Geography, History)
- Grade: Grade 7 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN no ISBN printed (book code 707)
- PDF pages: 184 (cover/title page verified against the record title; byte size 17,567,146 and page count match the books.json record)
- Verdict: COMPLETE (History chapters 9–12 placed; other parts named below)
- Tally: 9 placements — 2 to existing lessons, 7 NEW LESSON NEEDED
- Iran's own way: History enters the combined book last, as the final four of twelve chapters, and runs ancient Iran in the same thematic order the Grade 10 book will use (settlements → empires → administering → society → economy → beliefs → knowledge and art) — a deliberate spiral.
- Non-History parts named, not placed: Ch. 1 Our rights and responsibilities (printed pp. 1–12, Civics), Ch. 2 Law (pp. 13–20, Civics), Ch. 3 Coping with accidents — empathy, insurance (pp. 21–30), Ch. 4 Production, distribution, consumption (pp. 31–42, Economics), Ch. 5 Knowing our living environment (pp. 43–56, Geography), Ch. 6 Protecting Iran's habitats (pp. 57–72, Geography), Ch. 7 Population and resources (pp. 73–88, Geography), Ch. 8 Tourism in Iran (pp. 89–102, Geography).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 6:** Social Studies, Grade 8 (student book, Persian) — COMBINED Civics–Geography–History
- Title as printed: مطالعات اجتماعی (مدنی، تاریخ، جغرافیا) — Social Studies (Civics, History, Geography)
- Grade: Grade 8 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN no ISBN printed (book code 807)
- PDF pages: 200 (cover/title page verified against the record title; byte size 21,287,483 and page count match the books.json record)
- Verdict: COMPLETE (History chapters 5–8 placed; other parts named below)
- Tally: 8 placements — 1 to existing lessons, 7 NEW LESSON NEEDED
- Iran's own way: the Islamic centuries are framed by two chapter titles that carry the thesis — "From Hira to Nineveh" (Islam's rise to Karbala) and "Victory of culture over the sword" (Iranian culture outlasting Mongol and Timurid conquest).
- Non-History parts named, not placed: Ch. 1 Cooperation (printed pp. 1–12), Ch. 2 The government's role in running the country (pp. 13–22, Civics), Ch. 3 Adolescents and the law (pp. 23–34, Civics), Ch. 4 The age of communications (pp. 35–46), Ch. 9 Asia, the largest continent (pp. 107–122, Geography), Ch. 10 The Southwest Asia region and Iran's place in it (pp. 123–136, Geography), Ch. 11 Europe and Africa (pp. 137–152, Geography), Ch. 12 The Americas and Oceania (pp. 153–169, Geography).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 7:** Social Studies, Grade 9 (student book, Persian) — COMBINED Geography–History–Civics
- Title as printed: مطالعات اجتماعی (جغرافیا، تاریخ، مدنی) — Social Studies (Geography, History, Civics)
- Grade: Grade 9 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN no ISBN printed (book code 907)
- PDF pages: 200 (cover/title page verified against the record title; byte size 15,729,422 and page count match the books.json record)
- Verdict: COMPLETE (History chapters 5–8 placed; other parts named below)
- Tally: 8 placements — 0 to existing lessons, 8 NEW LESSON NEEDED
- Iran's own way: middle school closes with a sprint from Safavid unification to the Islamic Republic in eight lessons — the whole modern national story at survey speed, framed as unity gained, lost to foreign pressure, and regained.
- Non-History parts named, not placed: Ch. 1–2 Earth and its spheres (printed pp. 1–28, Geography), Ch. 3 Biosphere (pp. 29–40, Geography), Ch. 4 Inhabitants of planet Earth — world population and inequality (pp. 41–52, Geography), Ch. 9 Culture and identity (pp. 117–130), Ch. 10 Family and society (pp. 131–142), Ch. 11 Government and the people (pp. 143–156, Civics), Ch. 12 Productivity (pp. 157–170, Economics).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 8:** Social Studies, Grade 6 (student book, Persian) — COMBINED
- Title as printed: مطالعات اجتماعی ششم دبستان — Social Studies, Grade 6 (primary)
- Grade: Grade 6 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN no ISBN printed
- PDF pages: 152 (cover/title page verified against the record title)
- Verdict: COMPLETE (History chapters 5, 6, 11, 12 placed; other parts named below)
- Tally: 8 placements — 0 to existing lessons, 8 NEW LESSON NEEDED
- Iran's own way: primary history is four story-clusters — Muslim scientists, Safavid Isfahan, resisting colonialism, and the fall and liberation of Khorramshahr told as a two-act war story with the city's own name as the title.
- Non-History parts named, not placed: Ch. 1 Our friends (printed pp. 11–20), Ch. 2 Decision-making (pp. 21–30), Ch. 3 Agriculture in Iran (pp. 31–44, Geography/Economics), Ch. 4 Iran and energy resources, incl. Lesson 7 "Black gold" (oil) (pp. 45–58, Geography/Economics), Ch. 7 Free time (pp. 83–94), Ch. 8 Our clothing (pp. 95–106), Ch. 9 Iran's seas (pp. 107–118, Geography), Ch. 10 Iran and its neighbours (pp. 119–130, Geography).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 9:** Social Studies, Grade 5 (student book, Persian) — COMBINED
- Title as printed: مطالعات اجتماعی پنجم دبستان — Social Studies, Grade 5 (primary)
- Grade: Grade 5 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN 978-964-05-2426-8
- PDF pages: 136 (cover/title page verified against the record title)
- Verdict: COMPLETE (Chapter 4 pilgrimage narratives and Chapter 5 "Iran after Islam" placed; other parts named below)
- Tally: 7 placements — 1 to existing lessons, 6 NEW LESSON NEEDED
- Iran's own way: history at Grade 5 is told as journeys and story-lessons — a return from Hajj, a trip to the Prophet's Medina and to Karbala, then four blunt story titles for post-Islam Iran: forming governments, capable ministers and flourishing cities, ruthless conquerors, rebuilding the ruins.
- Non-History parts named, not placed: Ch. 1 Living with others (printed pp. 2–23), Ch. 2 Our land — population, water, industry, roads and transport, how our country is governed (pp. 24–65, Geography/Civics), Ch. 3 Life in other parts of the world — neighbour countries, Earth's movements, world regions (pp. 66–91, Geography).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 10:** Social Studies, Grade 4 (student book, Persian) — COMBINED
- Title as printed: مطالعات اجتماعی چهارم دبستان — Social Studies, Grade 4 (primary)
- Grade: Grade 4 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN 978-964-05-2358-2
- PDF pages: 120 (cover/title page verified against the record title)
- Verdict: COMPLETE (History chapters 3–4 and the national-symbols lessons of chapter 6 placed; other parts named below)
- Tally: 8 placements — 3 to existing lessons, 5 NEW LESSON NEEDED
- Iran's own way: a nine-year-old's first history is a journey — how villages and cities began, how historians know, then three trips: to Median Hamadan, to Persepolis (two lessons), and to Kermanshah's Bisotun — place itself is the textbook.
- Non-History parts named, not placed: Ch. 1 Our neighbourhood (printed pp. 2–23), Ch. 2 My city, my village — city/village life, compass directions, how geographers study environments (pp. 24–37, Geography), Ch. 5 My beautiful country — mountains, plains, weather, climate zones, plants and animals of Iran (pp. 74–99, Geography).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Book 11:** Social Studies, Grade 3 (student book, Persian) — COMBINED
- Title as printed: مطالعات اجتماعی سوم دبستان — Social Studies, Grade 3 (primary)
- Grade: Grade 3 (student/teacher: STUDENT)
- Publisher: Ministry of Education, Organisation for Educational Research and Planning, Tehran; year 1405–1406; ISBN 978-964-05-1915-8
- PDF pages: 104 (cover/title page verified against the record title)
- Verdict: COMPLETE — read in full; the book contains no History chapters (Iran's primary History begins at Grade 4); only the time-and-change seed lessons are placed, the rest is named below
- Tally: 1 placement — 1 to existing lessons, 0 NEW LESSON NEEDED
- Iran's own way: at Grade 3 the "time, continuity and change" strand is entirely personal — the child's own birth, growth and family change are the first timeline, years before the nation's past appears.
- Non-History parts named, not placed: Ch. 2 Family (printed pp. 16–29), Ch. 3 Cooperation in the family (pp. 30–37), Ch. 4 The family's needs — provision, resources, correct consumption, recycling (pp. 38–55), Ch. 5 Our home (pp. 56–71), Ch. 6 Our school (pp. 72–81), Ch. 7 From home to school — addresses, main directions, the post, street safety (pp. 82–95).
Placements at `liqlearns-courses-work/expansion-history-2026-11-15/iran-placements.md`.

**Teacher guides:** none in the Iran filing — every book in hand is a student book.

**Contents map (combined books — parts named, not placed):**

Books 5–11 are combined Social Studies books, and Book 1's and Book 2's companions in the set are History-only; only the combined books' History parts are placed in this course. Their non-History parts, exactly as filed, are:

- **Book 5:** Non-History parts named, not placed: Ch. 1 Our rights and responsibilities (printed pp. 1–12, Civics), Ch. 2 Law (pp. 13–20, Civics), Ch. 3 Coping with accidents — empathy, insurance (pp. 21–30), Ch. 4 Production, distribution, consumption (pp. 31–42, Economics), Ch. 5 Knowing our living environment (pp. 43–56, Geography), Ch. 6 Protecting Iran's habitats (pp. 57–72, Geography), Ch. 7 Population and resources (pp. 73–88, Geography), Ch. 8 Tourism in Iran (pp. 89–102, Geography).
- **Book 6:** Non-History parts named, not placed: Ch. 1 Cooperation (printed pp. 1–12), Ch. 2 The government's role in running the country (pp. 13–22, Civics), Ch. 3 Adolescents and the law (pp. 23–34, Civics), Ch. 4 The age of communications (pp. 35–46), Ch. 9 Asia, the largest continent (pp. 107–122, Geography), Ch. 10 The Southwest Asia region and Iran's place in it (pp. 123–136, Geography), Ch. 11 Europe and Africa (pp. 137–152, Geography), Ch. 12 The Americas and Oceania (pp. 153–169, Geography).
- **Book 7:** Non-History parts named, not placed: Ch. 1–2 Earth and its spheres (printed pp. 1–28, Geography), Ch. 3 Biosphere (pp. 29–40, Geography), Ch. 4 Inhabitants of planet Earth — world population and inequality (pp. 41–52, Geography), Ch. 9 Culture and identity (pp. 117–130), Ch. 10 Family and society (pp. 131–142), Ch. 11 Government and the people (pp. 143–156, Civics), Ch. 12 Productivity (pp. 157–170, Economics).
- **Book 8:** Non-History parts named, not placed: Ch. 1 Our friends (printed pp. 11–20), Ch. 2 Decision-making (pp. 21–30), Ch. 3 Agriculture in Iran (pp. 31–44, Geography/Economics), Ch. 4 Iran and energy resources, incl. Lesson 7 "Black gold" (oil) (pp. 45–58, Geography/Economics), Ch. 7 Free time (pp. 83–94), Ch. 8 Our clothing (pp. 95–106), Ch. 9 Iran's seas (pp. 107–118, Geography), Ch. 10 Iran and its neighbours (pp. 119–130, Geography).
- **Book 9:** Non-History parts named, not placed: Ch. 1 Living with others (printed pp. 2–23), Ch. 2 Our land — population, water, industry, roads and transport, how our country is governed (pp. 24–65, Geography/Civics), Ch. 3 Life in other parts of the world — neighbour countries, Earth's movements, world regions (pp. 66–91, Geography).
- **Book 10:** Non-History parts named, not placed: Ch. 1 Our neighbourhood (printed pp. 2–23), Ch. 2 My city, my village — city/village life, compass directions, how geographers study environments (pp. 24–37, Geography), Ch. 5 My beautiful country — mountains, plains, weather, climate zones, plants and animals of Iran (pp. 74–99, Geography).
- **Book 11:** Non-History parts named, not placed: Ch. 2 Family (printed pp. 16–29), Ch. 3 Cooperation in the family (pp. 30–37), Ch. 4 The family's needs — provision, resources, correct consumption, recycling (pp. 38–55), Ch. 5 Our home (pp. 56–71), Ch. 6 Our school (pp. 72–81), Ch. 7 From home to school — addresses, main directions, the post, street safety (pp. 82–95).

- **Book 11 (Grade 3 Social Studies):** read in full; the book contains no History chapters (Iran's primary History begins at Grade 4); only the time-and-change seed lessons are placed, the rest is named in its header above (Ch. 2 Family; Ch. 3 Cooperation in the family; Ch. 4 The family's needs; Ch. 5 Our home; Ch. 6 Our school; Ch. 7 From home to school).

## The way of the books (their own shape, preserved)

**Book 1:** (no own-way note filed)

**Book 2:** (no own-way note filed)

**Book 3:** (no own-way note filed)

**Book 4:** (no own-way note filed)

**Book 5:** (no own-way note filed)

**Book 6:** (no own-way note filed)

**Book 7:** (no own-way note filed)

**Book 8:** (no own-way note filed)

**Book 9:** (no own-way note filed)

**Book 10:** (no own-way note filed)

**Book 11:** (no own-way note filed)

## Acceptance reckoning

- **Pupil-taught from Iran's books:** all 80 lessons stand on the **student books** (Books 1–11) — taught in **1 country (Iran)**.
- **Teacher-guide evidence only, counted nowhere:** none — the filing holds no teacher guide or programme.
- Every lesson's `lesson/sources.md` carries its own acceptance line in exactly these terms.
- Totals: 127 placements stocked into 80 lessons, as filed (Book 1: 21 · Book 2: 16 · Book 3: 27 · Book 4: 14 · Book 5: 9 · Book 6: 8 · Book 7: 8 · Book 8: 8 · Book 9: 7 · Book 10: 8 · Book 11: 1).

## Honesty notes (course level)

- **Verdicts, carried exactly as filed:** all eleven books are COMPLETE as filed (Books 5–10 COMPLETE for their History chapters, their other parts named, not placed; Book 11 COMPLETE — read in full, containing no History chapters, only its time-and-change seed lessons placed). No book in the Iran filing is PARTIAL, UNREAD, wrong-file or record-only, and no teacher guide is in hand.
- **Route note, as filed:** the books were grabbed via grab.py — the books.json tree paths 404 (see library debts), so the TSV release-asset routes were used; byte size and page count verified against books.json, cover rendered and checked, full Persian text extracted with pdftotext -layout and read (contents + every lesson). Filings are summarised in English from the Persian.
- **Book 2 route note, as filed:** the record's TSV URL duplicates the Contemporary History release asset; Book 2 was fetched from the same release under its own asset name grade-11-gov-iran-history-student-full-year.pdf — see library debts. Its byte size 11,426,218 and page count match the books.json record exactly.
- **Combined Social Studies books:** History parts placed, Geography/Civics parts named in the headers and in the contents map above only, exactly as filed.
- **Slug merge:** `ancient-world/iran-dawn-of-civilisation-elam-and-early-cities` (filed in Books 5 and 10) is a plain same-thing variant of `ancient-world/iran-dawn-of-civilisation-elam-and-the-early-cities` (filed in Book 1); the two are stocked as ONE lesson under the Book 1 slug, and the merged-away slug is recorded in that lesson's sources.md. No other slugs were merged.
- **UNREAD books:** none named — no Iran book stands in the filing as held-but-unread or record-only. The filing carries 18 records / 11 distinct books, all read as filed. Books not in the filing do not exist for this build.
