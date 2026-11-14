# Choosing the Right Data Type

## Do it first

Every value in a program must live somewhere, and the type of that somewhere is a decision. Malaysia's Java chapter teaches type choice as a skill of its own. In this lesson you learn to choose by the value, its range, and its job — and what each wrong choice costs.

## Sub lesson 1 — Choose by the value and its range

The first questions are about the **value**: is it whole or decimal (int against double), a single character or text (char against String), a truth (boolean)? Then its **range**: a class mark fits a byte, a population does not — too small a type **overflows**, silently wrapping or failing; too large a type merely wastes space. Malaysia's order is value first, range second: the kind of the value names the family, the range settles the member.

[Picture — Choose by the value and its range]

## Sub lesson 2 — Choose by the job — and pay for wrong choices

The second questions are about the **job**: a value that will be **calculated with** must be numeric — a phone number kept as int loses its leading zero and invites arithmetic it will never need, so it belongs in String; a mark kept as String cannot be averaged. Wrong choices charge rent throughout the program: conversions at every use, comparisons that sort as text ('10' before '9'), totals that refuse to add. Choosing the type is choosing what the value **can do** — the lesson's rule is to decide it once, at declaration, from the value's kind and career, not from the first value it happens to hold.

[Picture — Choose by the job — and pay for wrong choices]

## Say it to your companion

Tell your companion, in your own words: The first questions are about the **value**: is it whole or decimal (int against double), a single character or text (char against String), a truth (boolean)? Then its **range**: a class mark fits a byte, a population does not — too small a type **overflows**, silently wrapping or failing; too large a type merely wastes space. Malaysia's order is value first, range second: the kind of the value names the family, the range settles the member. The second questions are about the **job**: a value that will be **calculated with** must be numeric — a phone number kept as int loses its leading zero and invites arithmetic it will never need, so it belongs in String; a mark kept as String cannot be averaged. Wrong choices charge rent throughout the program: conversions at every use, comparisons that sort as text ('10' before '9'), totals that refuse to add. Choosing the type is choosing what the value **can do** — the lesson's rule is to decide it once, at declaration, from the value's kind and career, not from the first value it happens to hold. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The value — whole or decimal, character or text, truth or not. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The value's range. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: It overflows — silently wrapping or failing. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: String — as int it loses its leading zero and invites arithmetic it never needs. Do this with a real example of your own and write or say how you know it is right.
