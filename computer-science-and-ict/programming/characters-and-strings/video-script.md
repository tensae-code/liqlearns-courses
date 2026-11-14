# Video script — Characters and Strings

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Text enters a program one **character** at a time: a letter, a digit, a space, a punctuation mark — each a single symbol, stored as a **code number** from the character set the machine agrees on. The character is a data type of its own (in the book's C-flavoured world, `char`): it can be stored, compared and printed, and — because it is a code underneath — even counted with. Indonesia's Grade 11 data-structure design places characters right after arrays for a reason the next sub lesson collects: a string is the array's closest relative.
A **string** is a **sequence of characters** kept as one value: a name, a word, a whole sentence. Its properties follow from the row: it has a **length** (how many characters), an **order** (first character, second, …), and parts that can be cut out and joined — the operations every text program is built from. Designing with strings means choosing them deliberately: text that must be searched, compared or taken apart belongs in strings, and the designer names a value's kind — number, character, string — before the program is written, not after it breaks.
