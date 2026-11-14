# Indexing — Making Searches Fast

## Do it first

Find one name in a thousand-page book with no index and you will read for an hour. With the index, ten seconds. A database with a million records has the same problem at machine speed — and the same answer, which this lesson teaches. Honesty first: Bangladesh's book names indexing inside its DDL command list and practises it in exercises rather than teaching it in its own section; the lesson is built from that naming and that practice.

## Sub lesson 1 — The index — a book's index inside the database

An **index** is a separate, sorted structure the DBMS keeps beside a table: for an indexed field it holds each value in order, with a pointer to the record that carries it. Searching by that field then works like a book's index — look the value up in the sorted list, follow the pointer, done — instead of a **full table scan**, reading every record to find the few that match. The wider the table grows, the more the index earns: on ten records it is nothing; on ten million it is the difference between instant and unusable.

[Picture — The index — a book's index inside the database]

## Sub lesson 2 — The price of the index — and choosing fields

An index is not free: it takes **storage**, and every INSERT, UPDATE and DELETE must update the index too, so writes grow slower as indexes multiply. The designer's craft is choosing: index the fields searches actually use — the key, the name looked up daily — and leave the rest unindexed. Bangladesh's exercises practise exactly this judgement on school-sized tables, where the principle can be seen whole before the tables grow beyond seeing.

[Picture — The price of the index — and choosing fields]

## Say it to your companion

Tell your companion, in your own words: An **index** is a separate, sorted structure the DBMS keeps beside a table: for an indexed field it holds each value in order, with a pointer to the record that carries it. Searching by that field then works like a book's index — look the value up in the sorted list, follow the pointer, done — instead of a **full table scan**, reading every record to find the few that match. The wider the table grows, the more the index earns: on ten records it is nothing; on ten million it is the difference between instant and unusable. An index is not free: it takes **storage**, and every INSERT, UPDATE and DELETE must update the index too, so writes grow slower as indexes multiply. The designer's craft is choosing: index the fields searches actually use — the key, the name looked up daily — and leave the rest unindexed. Bangladesh's exercises practise exactly this judgement on school-sized tables, where the principle can be seen whole before the tables grow beyond seeing. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A sorted lookup structure kept beside a table. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A value in order, with a pointer to its record. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: A full table scan — reading every record. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: On very large tables. Do this with a real example of your own and write or say how you know it is right.
