# The Type of an Expression in Pascal

## Do it first

A value is not just a value — it is a value of a type, and an expression inherits its type from its parts. Grade 8 and Grade 10 both pause here, before assignment, because an assignment is only legal when the types agree.

## Sub lesson 1 — The type follows the operations

An expression's **type** is determined by its operands and operators together. Arithmetic on **integers** with +, −, * stays **integer**; the same operands under **div or mod** stay integer too, but under **/** the result is **real** — one operator changes the type of the whole. Reals anywhere in an arithmetic expression make the result **real**. The type is not written beside the expression; it is **derived**, by the compiler and by the reader who knows the rules, from the types of the parts.

[Picture — The type follows the operations]

## Sub lesson 2 — Relations give booleans — and types guard assignments

A **relation** (comparison) takes operands of a matching type and gives a **boolean**: `a + 1 > b` is boolean whatever a and b are. Logical operators (and, or, not) take booleans and give booleans. The type system then guards the exits: assigning a **real expression to an integer variable is an error**, because a fraction cannot honestly enter a whole-number box; assigning integer to real is allowed (whole numbers are reals with empty fractions). Know the type before you assign — that is this section's whole discipline.

[Picture — Relations give booleans — and types guard assignments]

## Say it to your companion

Tell your companion, in your own words: An expression's **type** is determined by its operands and operators together. Arithmetic on **integers** with +, −, * stays **integer**; the same operands under **div or mod** stay integer too, but under **/** the result is **real** — one operator changes the type of the whole. Reals anywhere in an arithmetic expression make the result **real**. The type is not written beside the expression; it is **derived**, by the compiler and by the reader who knows the rules, from the types of the parts. A **relation** (comparison) takes operands of a matching type and gives a **boolean**: `a + 1 > b` is boolean whatever a and b are. Logical operators (and, or, not) take booleans and give booleans. The type system then guards the exits: assigning a **real expression to an integer variable is an error**, because a fraction cannot honestly enter a whole-number box; assigning integer to real is allowed (whole numbers are reals with empty fractions). Know the type before you assign — that is this section's whole discipline. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its operands and operators together. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Integer — integer arithmetic with * stays integer. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 7 / 3 is real; 7 div 3 is integer. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It makes the whole result real. Do this with a real example of your own and write or say how you know it is right.
