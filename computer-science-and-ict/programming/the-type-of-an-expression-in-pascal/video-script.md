# Video script — The Type of an Expression in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An expression's **type** is determined by its operands and operators together. Arithmetic on **integers** with +, −, * stays **integer**; the same operands under **div or mod** stay integer too, but under **/** the result is **real** — one operator changes the type of the whole. Reals anywhere in an arithmetic expression make the result **real**. The type is not written beside the expression; it is **derived**, by the compiler and by the reader who knows the rules, from the types of the parts.
A **relation** (comparison) takes operands of a matching type and gives a **boolean**: `a + 1 > b` is boolean whatever a and b are. Logical operators (and, or, not) take booleans and give booleans. The type system then guards the exits: assigning a **real expression to an integer variable is an error**, because a fraction cannot honestly enter a whole-number box; assigning integer to real is allowed (whole numbers are reals with empty fractions). Know the type before you assign — that is this section's whole discipline.
