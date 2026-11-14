# Video script — JavaScript Data Types and Variables

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

JavaScript works with **number** (both whole and decimal — 42 and 3.14 are the same type), **string** (text, in quotes — 'Aina'), **boolean** (true and false), and the empty markers **undefined** (a variable declared but given nothing) and **null** (a value deliberately nothing). JavaScript is **loosely typed**: a variable's type is the type of the value it currently holds, and the same variable may hold a number today and a string tomorrow — freedom the programmer must police, because '5' + 3 joins as text while '5' - 3 calculates as 2.
Variables are **declared** before use with one of three words: **let** — the modern default, for a value that will change; **const** — for a **constant**, whose assignment cannot be replaced (const PI = 3.14159;), the JavaScript pemalar; and **var** — the older word, whose wider scope still appears in older scripts Malaysia's learners will meet. Declaring is naming with intent: let promises change, const promises fixity, and the promises are the documentation the next reader trusts.
