# Video script — Choosing the Right Data Type

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The first questions are about the **value**: is it whole or decimal (int against double), a single character or text (char against String), a truth (boolean)? Then its **range**: a class mark fits a byte, a population does not — too small a type **overflows**, silently wrapping or failing; too large a type merely wastes space. Malaysia's order is value first, range second: the kind of the value names the family, the range settles the member.
The second questions are about the **job**: a value that will be **calculated with** must be numeric — a phone number kept as int loses its leading zero and invites arithmetic it will never need, so it belongs in String; a mark kept as String cannot be averaged. Wrong choices charge rent throughout the program: conversions at every use, comparisons that sort as text ('10' before '9'), totals that refuse to add. Choosing the type is choosing what the value **can do** — the lesson's rule is to decide it once, at declaration, from the value's kind and career, not from the first value it happens to hold.
