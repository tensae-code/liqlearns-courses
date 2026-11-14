# Video script — ASCII Encoding in Octal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**ASCII** gives every character — letters, digits, punctuation, space — its own **code value**: a decimal number agreed everywhere, such as A = 65, B = 66, a = 97, 0 (the digit character) = 48, space = 32. The character itself is never stored; the number is. Finding the value is a table job: the value is looked up, not worked out, and capital and small letters have different values.
The ASCII value is then **converted to octal** by the divide-by-8 method: A = 65 → 65 ÷ 8 = 8 rem 1; 8 ÷ 8 = 1 rem 0; 1 ÷ 8 = 0 rem 1 → read upwards, **101₈**. So the character A is held as octal 101. Malaysia teaches the chain in this order — character, code value, octal — because each step has its own rule and mixing the steps is where errors enter.
