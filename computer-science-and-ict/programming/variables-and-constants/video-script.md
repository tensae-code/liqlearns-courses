# Video script — Variables and Constants

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **variable** is a named store whose value **can change** while the program runs: a score starts at 0 and grows, a name is read in and replaced next run. In Python a variable is made by assigning (score = 0) and its type follows the value it holds; in Java it is declared with its type (int score = 0;). Changing a variable is normal work — assignment replaces the old value entirely; the old value is gone unless it was copied elsewhere first.
A **constant** (pemalar) is a named store whose value is **fixed when it is set and must not change** during the run: pi, the passing mark, the number of days in a week. Languages guard them differently — Python uses the capital-name convention (PI = 3.14159, a promise by the programmer), Java uses the keyword **final** (final int PASS_MARK = 50;), which the compiler enforces. Constants exist so fixed values have **one home**: change the rule once, in one place, and every use follows; a constant that could change silently would be a variable wearing a false name.
