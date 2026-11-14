# Saving Data in Text Files with PHP

## Do it first

A page forgets everything when it closes — unless its data was written somewhere that stays. Malaysia's PHP unit keeps its data in the humblest store: text files on the server. In this lesson you produce and save data as text, line by line.

## Sub lesson 1 — Why a text file — data that outlives the page

Server data must **outlive** any single page visit: names signed up today are read tomorrow. A **text file** is the unit's store: plain lines of characters, kept in a file on the server, readable by the program and by people. Each **record** is written as **one line**, its **fields separated by a chosen mark** (such as a comma or a | ) — Aina|aina@mail.com|2026 — so the line can later be split back into its fields. The format is an agreement the whole unit keeps: writer and reader must use the same mark and the same field order, or the data reads as nonsense.

[Picture — Why a text file — data that outlives the page]

## Sub lesson 2 — Writing — from program values to stored lines

In PHP the writing follows a fixed rhythm: **open** the file for appending (so old records are kept), **write** the new record as one formatted line (the fields joined by the mark, ended by a newline), and **close** the file. Appending matters: opening a file for plain writing **replaces** its contents, and the difference between keeping a term's sign-ups and keeping only the last one is that single choice. Malaysia's check is performed by eye: after saving, the file is opened as text and **read** — if the new line does not stand correctly among the old, the writing, not the idea, is repaired.

[Picture — Writing — from program values to stored lines]

## Say it to your companion

Tell your companion, in your own words: Server data must **outlive** any single page visit: names signed up today are read tomorrow. A **text file** is the unit's store: plain lines of characters, kept in a file on the server, readable by the program and by people. Each **record** is written as **one line**, its **fields separated by a chosen mark** (such as a comma or a | ) — Aina|aina@mail.com|2026 — so the line can later be split back into its fields. The format is an agreement the whole unit keeps: writer and reader must use the same mark and the same field order, or the data reads as nonsense. In PHP the writing follows a fixed rhythm: **open** the file for appending (so old records are kept), **write** the new record as one formatted line (the fields joined by the mark, ended by a newline), and **close** the file. Appending matters: opening a file for plain writing **replaces** its contents, and the difference between keeping a term's sign-ups and keeping only the last one is that single choice. Malaysia's check is performed by eye: after saving, the file is opened as text and **read** — if the new line does not stand correctly among the old, the writing, not the idea, is repaired. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Names signed up today are read tomorrow — the page forgets; the file stays. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A text file on the server — plain lines of characters. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: As one line, its fields separated by a chosen mark. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Open the file, write the line, close the file. Do this with a real example of your own and write or say how you know it is right.
