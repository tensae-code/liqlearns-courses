# Video script — Expressions and Arithmetic in Small Basic

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An **expression** is a written working-out: values and variables joined by operators, which the machine evaluates to a single result. Programs get their starting values from the user with **ReadNumber**, the TextWindow operation that pauses, takes a typed number, and hands it to a variable. Input, then expression, then assignment — `area = side * side` — is the rhythm of every numeric program in the book: read the quantities, work the expression, keep the result.
Small Basic's **arithmetic operators** are the school set: **+ − * /** and the remainder and powers met through the Math object. Joined in one expression they are **not** worked left to right by habit but by **operator precedence**: multiplication and division before addition and subtraction, and **parentheses** above all — the bracketed part is worked first, always. Precedence is the lesson's warning label: `2 + 3 * 4` is 14, not 20, and the programmer who needs 20 must write the brackets and say so.
