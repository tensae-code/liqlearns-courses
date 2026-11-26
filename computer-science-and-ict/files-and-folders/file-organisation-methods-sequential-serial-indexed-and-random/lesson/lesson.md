# File Organisation Methods — Sequential, Serial, Indexed and Random

## Do it first

Take ten pieces of paper and write a name and a number on each — shuffle them. Line them up in the order you pick them up: that row is one kind of file. Now sort the row by number: that is a second kind. Try finding number 7 in each row and feel the difference. Keep both rows in mind — the lesson names the four standard ways records are organised, and your two rows are the first two.

## Sub lesson 1 — Serial and sequential organisation

How a file is organised decides how fast you can reach one record. The simplest method is **serial organisation**: each new record is simply added at the end, in the order it arrives — a pile of transaction slips. Adding is instant, but finding one record means reading from the beginning until you trip over it, and the records sit in no useful order.

**Sequential organisation** keeps the same one-after-another layout but stores the records **sorted by their key field** — account number, admission number. Processing reads them in that order, start to finish, which is exactly what batch jobs do: a payroll run visits every record anyway, so reading in order wastes nothing, and a sorted file merges neatly with a sorted transaction file.

Both methods share a limit: there is no jumping. Reaching the ten-thousandth record costs ten thousand reads. Sequential files historically lived on tape, which can only wind forwards — the medium and the method fit each other. The next two methods exist to break that limit.

In your mind's eye: two rows of record cards: the first row in jumbled number order labelled serial, the second in neat ascending order labelled sequential.

## Sub lesson 2 — Indexed-sequential and random organisation

**Indexed-sequential organisation** keeps the records sorted, like a sequential file, and adds an **index**: a small side table that says which part of the file holds which range of keys, the way a book's index points to pages. To find a record, you read the index, jump to the right neighbourhood, then read a few records in order. You keep both powers — whole-file processing in order, and fast jumps to one record. This was the workhorse organisation of business data processing.

**Random organisation** (also called direct) abandons order entirely. Each record's address is **calculated from its key** by a formula — hashing — so the program goes straight to the record in one jump, however big the file. That is what an ATM needs: your balance, now, not after reading a million accounts. The costs: wasted space where the formula leaves gaps, collisions when two keys calculate the same address, and no meaningful 'next record in key order'.

Choosing is engineering judgement: process everything in order — sequential; jump to one record instantly — random; need both — indexed-sequential; just collect records as they come — serial. Kenya's Form 3 data-processing chapter teaches the four methods side by side, as the standard comparison every ICT learner is expected to make.

In your mind's eye: a sorted stack of records with a small index card beside it pointing ranges of keys to stack positions, and next to it a key being fed into a formula box that outputs an address.

## Say it to your companion

Tell your companion, in your own words: A file's organisation is the rule for where each record sits and how you reach it: serial files store records in arrival order, sequential files store them sorted by key and read them in order, indexed-sequential files add an index so you can jump near a record as well as read in order, and random (direct) files calculate each record's address from its key for instant access. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: describe serial, sequential, indexed-sequential and random file organisation in your own words. Do this with a real example of your own, and write or say how you know it is right.
2. Show it, don't just say it: say which access each method allows: sequential only, or direct as well. Do this with a real example of your own, and write or say how you know it is right.
3. Show it, don't just say it: match a real job (payroll run, bank account lookup) to the organisation that fits it. Do this with a real example of your own, and write or say how you know it is right.
4. Show it, don't just say it: name one strength and one weakness of each method. Do this with a real example of your own, and write or say how you know it is right.
