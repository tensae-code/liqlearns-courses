# Video script — Adding Records Through a Web Form — the Add_Term Page

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The page opens with an **HTML form**: fields for the term, its meaning and its illustration, and a submit button. The form's job is **gathering and naming** — each field carries a **name**, because that name is how the receiving page will know which typed value is which. A well-built form also guards the journey's first step: required fields marked, lengths matching the database table's columns, so what the visitor sends is already shaped like what the database can hold. Egypt builds this page inside the dictionary project, where the need is real: a dictionary that cannot grow is a poster, not a dictionary.
On submit, the browser sends the named values to **Add_Term.php**, whose PHP code **reads** each value by its field name, **checks** it (present, sane, safe to store), and runs the **INSERT** that adds one new **record** to the dictionary table in MySQL — then answers the visitor: added, or not added and why. The faults the book makes pupils hunt are the journey's own: a field name mistyped between form and page (the value arrives as nothing), a check skipped (an empty term stored), a success claimed before the insert ran. When the page works, the circle closes — the next visitor who searches the dictionary finds the term this visitor added.
