# Video script — PHP for Dynamic Web Pages

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **static** page is a finished file: every visitor gets the same bytes. A **dynamic** page is **generated**: a program on the server builds the page's HTML **in response to this request** — reading the database, choosing what this visitor asked for — and sends the result. **PHP** is the language the book uses for that generating program: PHP code sits inside the page file, runs **on the server** (the visitor never sees it — only its output), and its whole job is producing the page, often out of database content. The dictionary becomes dynamic the moment its term pages are PHP: add a term to the database, and the site shows it — no page edited by hand.
The working rhythm is the project's heartbeat: the browser **requests** a PHP page, perhaps with a choice attached (which term? which letter?); the server runs the PHP, which **queries MySQL**; the answers come back as data; the PHP **builds HTML around the data** and the server sends that HTML to the browser. Every part of the Grade 11 project meets here — the Expression Web pages provide the pattern the data is poured into, the MySQL database created earlier provides the content, and the Add_Term page is this same rhythm running in reverse, storing instead of showing. Egypt teaches PHP inside one real site because a dynamic page only makes sense attached to data someone actually wants.
