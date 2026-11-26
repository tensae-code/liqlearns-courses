# Maintaining a Database

## Do it first

The Access course ends not with a query but with a duty. A database that is used grows, fragments and is one accident away from loss; maintenance is the set of habits that keep it alive.

## Sub lesson 1 — Compact and repair — the file healed and shrunk

Deleting records and objects in Access **does not shrink the file**: the space stays claimed, as gaps — the file **bloats**, slows, and over years can corrupt. **Compact and Repair** is the cure: it **rebuilds the database file** — records recopied in order, gaps dropped, indexes rebuilt, and detected damage repaired where possible. The course's rule makes it a routine, not a rescue: compact **regularly** (weekly in working databases, always after mass deletions), and only ever on a **copy kept safe** until the compacted file proves sound.

In your mind's eye: compact and repair — the file healed and shrunk.

[Picture 46554 — compact and repair — the file healed and shrunk]

## Sub lesson 2 — Backup, splitting and protection — the standing care

The rest of maintenance is standing defence. **Backups**: dated copies of the file, kept apart from the working machine, on a rhythm the data's value sets — the only true repair for corruption, theft or fire. **Splitting**: a working database is divided into a **back-end** (tables only, on the shared place) and **front-ends** (queries, forms, reports on each user's machine), so many users share data without sharing damage. **Protection**: passwords and permissions keep the merely curious and the careless from the tables. Maintenance is unglamorous and decisive: databases rarely die of hard questions — they die **unkept**.

In your mind's eye: backup, splitting and protection — the standing care.

[Picture 46555 — backup, splitting and protection — the standing care]

## Say it to your companion

Tell your companion, in your own words: Deleting records and objects in Access **does not shrink the file**: the space stays claimed, as gaps — the file **bloats**, slows, and over years can corrupt. **Compact and Repair** is the cure: it **rebuilds the database file** — records recopied in order, gaps dropped, indexes rebuilt, and detected damage repaired where possible. The course's rule makes it a routine, not a rescue: compact **regularly** (weekly in working databases, always after mass deletions), and only ever on a **copy kept safe** until the compacted file proves sound. The rest of maintenance is standing defence. **Backups**: dated copies of the file, kept apart from the working machine, on a rhythm the data's value sets — the only true repair for corruption, theft or fire. **Splitting**: a working database is divided into a **back-end** (tables only, on the shared place) and **front-ends** (queries, forms, reports on each user's machine), so many users share data without sharing damage. **Protection**: passwords and permissions keep the merely curious and the careless from the tables. Maintenance is unglamorous and decisive: databases rarely die of hard questions — they die **unkept**. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Deleted records and objects leave claimed, empty gaps — the file does not shrink. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Rebuilds the file — records in order, gaps dropped, indexes rebuilt, damage repaired where possible. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Regularly — weekly in working databases, and always after mass deletions. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: On a copy kept safe until the compacted file proves sound. Do this with a real example of your own and write or say how you know it is right.
