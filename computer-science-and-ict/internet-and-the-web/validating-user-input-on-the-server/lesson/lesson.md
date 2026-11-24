# Validating User Input on the Server

## Do it first

Users send everything: blanks, letters in number fields, dates that do not exist. Malaysia's PHP unit checks the sending on the server before believing it. In this lesson you validate — the gate every value passes before it is stored.

## Sub lesson 1 — What validation checks

**Validation** (pengesahsahihan data) checks a sent value against its rules before the program uses or stores it. The standing checks are: **presence** — the field was not left empty; **type** — a number where a number is required; **range** — a mark between 0 and 100, an age a human could have; **format** — an email shaped like an email, a date that exists; and **length** — a password long enough, a name not absurdly long. Each failed check is reported **to the user, by field**, so the sending can be corrected — a bare 'invalid' teaches nothing and protects by luck.

In your mind's eye: what validation checks.

## Sub lesson 2 — Why the server must check — even if the page already did

Pages can check too (JavaScript validation, for comfort and speed), but the **server's check is the one that counts**: the page's code runs in the visitor's own browser, where it can be skipped, altered or bypassed entirely — a sender need never load your page at all. Data that reaches storage has passed the server or it has passed nothing. Malaysia's architecture is therefore **both**: the client checks for the user's sake, the server checks for the **data's** sake — and the stored text files of this unit hold only what the server's gate let through.

In your mind's eye: why the server must check — even if the page already did.

## Say it to your companion

Tell your companion, in your own words: **Validation** (pengesahsahihan data) checks a sent value against its rules before the program uses or stores it. The standing checks are: **presence** — the field was not left empty; **type** — a number where a number is required; **range** — a mark between 0 and 100, an age a human could have; **format** — an email shaped like an email, a date that exists; and **length** — a password long enough, a name not absurdly long. Each failed check is reported **to the user, by field**, so the sending can be corrected — a bare 'invalid' teaches nothing and protects by luck. Pages can check too (JavaScript validation, for comfort and speed), but the **server's check is the one that counts**: the page's code runs in the visitor's own browser, where it can be skipped, altered or bypassed entirely — a sender need never load your page at all. Data that reaches storage has passed the server or it has passed nothing. Malaysia's architecture is therefore **both**: the client checks for the user's sake, the server checks for the **data's** sake — and the stored text files of this unit hold only what the server's gate let through. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Checking a sent value against its rules before the program uses or stores it. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Presence, type, range, format, length. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Range — a mark must lie between 0 and 100. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: It teaches nothing and protects by luck. Do this with a real example of your own and write or say how you know it is right.
