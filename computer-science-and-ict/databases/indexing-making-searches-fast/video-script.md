# Video script — Indexing — Making Searches Fast

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **index** is a separate, sorted structure the DBMS keeps beside a table: for an indexed field it holds each value in order, with a pointer to the record that carries it. Searching by that field then works like a book's index — look the value up in the sorted list, follow the pointer, done — instead of a **full table scan**, reading every record to find the few that match. The wider the table grows, the more the index earns: on ten records it is nothing; on ten million it is the difference between instant and unusable.
An index is not free: it takes **storage**, and every INSERT, UPDATE and DELETE must update the index too, so writes grow slower as indexes multiply. The designer's craft is choosing: index the fields searches actually use — the key, the name looked up daily — and leave the rest unindexed. Bangladesh's exercises practise exactly this judgement on school-sized tables, where the principle can be seen whole before the tables grow beyond seeing.
