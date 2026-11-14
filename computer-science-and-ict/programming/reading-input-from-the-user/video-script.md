# Video script — Reading Input from the User

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The pattern is two steps: **cout** a prompt ("Enter your age: "), then **cin >> age;** waits for typing, converts what was typed to age's **type**, and stores it. The **>>** points the way the data flows — from the keyboard stream into the variable. Without the prompt the program waits in silence and the user cannot tell it is waiting at all.
Reads chain — **cin >> a >> b;** takes two values separated by spaces or new lines — and a program can read as many values as it has statements for. The book returns to entering data for **further practice** (§3.23) after the if-else work: reading a value and immediately deciding on it is the first shape of nearly every interactive program, so the practice set drills the prompt-read-decide rhythm.
