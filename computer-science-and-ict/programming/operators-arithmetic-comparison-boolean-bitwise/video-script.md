# Video script — Operators — Arithmetic, Comparison, Boolean, Bitwise

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Operators** are the symbols that work on values. The **arithmetic** family computes: `+ − * /` and the remainder `%`, building every number a sketch needs from sensor readings and constants. The **comparison** family asks: `== != < > <= >=` — each returns TRUE or FALSE, and they are the senses of every `if` the program will ever write. Indonesia's Arduino course gathers all four families into one lesson because a sketch's whole behaviour is these symbols at work; the beginner's classic fault lives here too — writing `=` (assignment) where `==` (comparison) was meant, and setting a value when they meant to ask about it.
The **boolean** family combines tests: `&&` (AND), `||` (OR), `!` (NOT) — the grammar of conditions with more than one sense open. The **bitwise** family works inside numbers, bit by bit: `& | ^ ~` and the shifts `<< >>` — moving and masking the single bits that are a board's flags, pin states and packed settings, where one number carries eight yes/no answers at once. The four families divide the operator world by the size of what they touch: values, tests, combinations of tests, and the bits inside the values themselves.
