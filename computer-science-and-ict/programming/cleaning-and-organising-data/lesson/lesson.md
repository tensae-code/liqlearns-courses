# Cleaning and Organising Data

## Do it first

Two hundred survey answers arrive. One age is written 'fifteen', one is 15, one is 150. The same pupil appears twice. A whole column of villages is spelled three ways. Nothing here is false exactly — but no program can count it, and no chart can be trusted. The work of this lesson is the rescue: turning that heap into data you would sign your name under.

## Sub lesson 1 — Spotting dirty data — the five faults

Collected data is dirty in five recurring ways. **Missing values**: an entry left blank where the analysis will need it. **Wrong formats**: the same kind of value written in different shapes — 'fifteen', 15, '15 yrs'. **Duplicates**: the same record entered twice, quietly doubling its weight. **Impossible entries**: an age of 150, a date of 32 January — values that cannot be true, born of slips. **Inconsistent spellings**: one village under three names, which a counting program will treat as three villages. Spotting them is a skill of its own: scan each column asking 'what shapes appear here, and do they agree?'

[Picture — a table with five problem cells highlighted in five colours — one empty, one word among numbers, one row repeated, one impossible age, one village spelled a new way]

## Sub lesson 2 — Cleaning and organising — the repairs

Cleaning repairs each fault by its own rule, decided **before** touching the data and applied the **same way everywhere**. Formats are unified (all ages as numbers, all dates in one pattern). Spellings are standardised to one agreed name per thing. Duplicates are hunted by their identifying columns and merged or removed. Missing and impossible values are handled honestly: go back to the source if possible; if not, mark them clearly as missing rather than inventing plausible numbers — an invented value is a lie the analysis will repeat with confidence. Around the cleaning sits the **organising**: one table, one row per record, one column per kind of value, headings agreed — the shape every later tool expects.

[Picture — the messy table from the first sub lesson being repaired cell by cell — words becoming numbers, the double row dissolving, the three village spellings merging into one — until the table stands clean and even]

## Say it to your companion

Tell your companion, in your own words: dirty data has five faults — missing values, wrong formats, duplicates, impossible entries, inconsistent spellings — and cleaning repairs each by a rule set in advance and applied everywhere, never by inventing values; organising gives the result one table, one row per record, one column per kind. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the five faults of dirty data and spot each in a sample table. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: say the repair rule for each fault, and why rules are set in advance and applied uniformly. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: explain why a missing value must be marked, never invented. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: organise a small messy dataset into one clean table (one row per record, one column per kind). Do this with a real example of your own and write or say how you know it is right.
