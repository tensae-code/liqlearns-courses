# Video script — Variable Types in C++

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**int** holds **whole numbers** in a limited range; **double** holds numbers **with fractions**, approximately, across a huge range; **char** holds **one character** (a letter, digit or symbol, stored as a code); **bool** holds exactly **true or false**. Declaring `int age;` reserves int-sized memory under the name age and forbids text from living there.
The type steers the operations: int division **drops fractions**, double division keeps them; adding to a char moves its **code** ('A' + 1 is 'B'); a bool is what conditions test. Giving a value to the wrong type converts or refuses it — 3.9 poured into an int becomes **3** — so choosing the type is the first design decision for every value in the program.
