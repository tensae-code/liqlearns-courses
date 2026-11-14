# Video script — Validating User Input on the Server

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Validation** (pengesahsahihan data) checks a sent value against its rules before the program uses or stores it. The standing checks are: **presence** — the field was not left empty; **type** — a number where a number is required; **range** — a mark between 0 and 100, an age a human could have; **format** — an email shaped like an email, a date that exists; and **length** — a password long enough, a name not absurdly long. Each failed check is reported **to the user, by field**, so the sending can be corrected — a bare 'invalid' teaches nothing and protects by luck.
Pages can check too (JavaScript validation, for comfort and speed), but the **server's check is the one that counts**: the page's code runs in the visitor's own browser, where it can be skipped, altered or bypassed entirely — a sender need never load your page at all. Data that reaches storage has passed the server or it has passed nothing. Malaysia's architecture is therefore **both**: the client checks for the user's sake, the server checks for the **data's** sake — and the stored text files of this unit hold only what the server's gate let through.
