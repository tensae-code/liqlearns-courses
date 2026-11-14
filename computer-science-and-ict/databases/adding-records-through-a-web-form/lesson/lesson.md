# Adding Records Through a Web Form — the Add_Term Page

## Do it first

The most complete single page in Egypt's Grade 11 project: Add_Term.php, where a visitor's typed term travels from a web form, through a PHP page, into the MySQL database — the full circle of the dynamic web, built by pupils as one named page.

## Sub lesson 1 — The form — where the journey starts

The page opens with an **HTML form**: fields for the term, its meaning and its illustration, and a submit button. The form's job is **gathering and naming** — each field carries a **name**, because that name is how the receiving page will know which typed value is which. A well-built form also guards the journey's first step: required fields marked, lengths matching the database table's columns, so what the visitor sends is already shaped like what the database can hold. Egypt builds this page inside the dictionary project, where the need is real: a dictionary that cannot grow is a poster, not a dictionary.

[Picture — The form — where the journey starts]

## Sub lesson 2 — The PHP receiving page — from submission to stored record

On submit, the browser sends the named values to **Add_Term.php**, whose PHP code **reads** each value by its field name, **checks** it (present, sane, safe to store), and runs the **INSERT** that adds one new **record** to the dictionary table in MySQL — then answers the visitor: added, or not added and why. The faults the book makes pupils hunt are the journey's own: a field name mistyped between form and page (the value arrives as nothing), a check skipped (an empty term stored), a success claimed before the insert ran. When the page works, the circle closes — the next visitor who searches the dictionary finds the term this visitor added.

[Picture — The PHP receiving page — from submission to stored record]

## Say it to your companion

Tell your companion, in your own words: The page opens with an **HTML form**: fields for the term, its meaning and its illustration, and a submit button. The form's job is **gathering and naming** — each field carries a **name**, because that name is how the receiving page will know which typed value is which. A well-built form also guards the journey's first step: required fields marked, lengths matching the database table's columns, so what the visitor sends is already shaped like what the database can hold. Egypt builds this page inside the dictionary project, where the need is real: a dictionary that cannot grow is a poster, not a dictionary. On submit, the browser sends the named values to **Add_Term.php**, whose PHP code **reads** each value by its field name, **checks** it (present, sane, safe to store), and runs the **INSERT** that adds one new **record** to the dictionary table in MySQL — then answers the visitor: added, or not added and why. The faults the book makes pupils hunt are the journey's own: a field name mistyped between form and page (the value arrives as nothing), a check skipped (an empty term stored), a success claimed before the insert ran. When the page works, the circle closes — the next visitor who searches the dictionary finds the term this visitor added. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Takes a term typed into a web form and stores it as a new record in the MySQL database. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Gathering and naming — each field's name tells the receiving page which value is which. Do this with a real example of your own and write or say how you know it is right.
6. Show it, don't just say it: INSERT — adding one new record to the dictionary table. Do this with a real example of your own and write or say how you know it is right.
7. Show it, don't just say it: Whether the term was added — or not added, and why. Do this with a real example of your own and write or say how you know it is right.
