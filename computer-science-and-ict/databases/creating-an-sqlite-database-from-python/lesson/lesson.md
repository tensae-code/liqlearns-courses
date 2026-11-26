# Creating an SQLite Database from Python

## Do it first

Other courses click a database into existence. Kuwait's Grade 11 makes it in code: a Python program connects, and the database is born. This lesson is that birth — connection, automatic creation, and doing it safely.

## Sub lesson 1 — Connecting with sqlite3 — the file that creates itself

Python carries the **sqlite3** module built in. The program **imports** it and **connects** to a named file — the course's running example, **Kuwait_landmarks.db**. If the file does not exist, the connection **creates it automatically**: an empty database, ready for tables. The connection is the program's doorway: through it travel every CREATE, INSERT and SELECT of the course, and it is closed when the work is done.

In your mind's eye: connecting with sqlite3 — the file that creates itself.

[Picture 46481 — connecting with sqlite3 — the file that creates itself]

## Sub lesson 2 — Creating safely — with exceptions

Real programs fail politely or not at all. Kuwait creates the database **safely, with exceptions**: the connecting code is wrapped so that if the file cannot be made or opened — a wrong place, a locked file — the program **catches the error and reports it** instead of dying mid-work with the data half-kept. Safe creation is the course's first professional habit: the database is the memory of everything after it, and its birth is guarded.

In your mind's eye: creating safely — with exceptions.

[Picture 46482 — creating safely — with exceptions]

## Say it to your companion

Tell your companion, in your own words: Python carries the **sqlite3** module built in. The program **imports** it and **connects** to a named file — the course's running example, **Kuwait_landmarks.db**. If the file does not exist, the connection **creates it automatically**: an empty database, ready for tables. The connection is the program's doorway: through it travel every CREATE, INSERT and SELECT of the course, and it is closed when the work is done. Real programs fail politely or not at all. Kuwait creates the database **safely, with exceptions**: the connecting code is wrapped so that if the file cannot be made or opened — a wrong place, a locked file — the program **catches the error and reports it** instead of dying mid-work with the data half-kept. Safe creation is the course's first professional habit: the database is the memory of everything after it, and its birth is guarded. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: sqlite3 — built into Python. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Kuwait_landmarks.db. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The connection creates it automatically — an empty database. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Every CREATE, INSERT and SELECT of the course. Do this with a real example of your own and write or say how you know it is right.
