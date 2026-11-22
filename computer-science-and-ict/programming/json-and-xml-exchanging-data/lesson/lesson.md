# JSON and XML — Exchanging Data

## Do it first

Somewhere above you, the International Space Station is circling the Earth with a crew aboard. A web service knows their names right now, and if a program asks, it answers with a block of JSON text: braces, quoted names, colons, lists. Read such a block by eye (your teacher or the lesson can show one) and list what it knows: how many people, their names, their craft. You read it easily — it is made of names and values. Keep your list — the lesson shows the few lines of Python that fetch that block live and read it the same way you just did, only exactly, and then the older XML way of doing the same job.

## Sub lesson 1 — JSON — data as dictionaries

**JSON** is the web’s way of answering programs. A program asks a **web service** for data — the book uses `api.open-notify.org`, which reports the people currently in space — and the service answers with JSON text. Python’s part is three moves: **urllib** fetches the answer from its address; the **json** module parses the text; and what comes out is ordinary Python — a JSON object becomes a **dictionary**, a JSON array becomes a **list**, strings and numbers stay themselves. From there it is the dictionary lesson at work: read the value at a name, loop over the list of astronauts, print each name. The fit is exact because JSON was designed from the same shapes — which is why it, and not a spreadsheet file, is what programs pass each other all day.

[Picture — a satellite beaming a block of JSON text down to a laptop, where the text unfolds into a dictionary and a list]

## Sub lesson 2 — XML — data as a tree of elements

**XML** is the older, stricter cousin: the same information written as a **tree of elements**, each value wrapped in a named tag — the book’s file is `films.xml`, a catalogue of films with title, director and year elements. Python’s **ElementTree** parses the file into that tree in memory: a **root** element, its **children**, and theirs below. Each element carries its **tag**, its **text** (what sits between the tags) and possibly **attributes**. The program then walks: find every `film` element, loop over them, print each one’s title and year. The family resemblance to the DOM lesson is real — a page and an XML file are both trees of named nodes — and the choice between the formats is practical: JSON for most program-to-program exchange today, XML where documents and strict catalogues rule. Both, notice, are plain text you can open and read — that openness is why they won.

[Picture — a films.xml file on the left becoming a tree of element boxes on the right, one film branch unfolded to its title, director and year]

## Say it to your companion

Tell your companion, in your own words: JSON answers become Python dictionaries and lists through the json module after urllib fetches them, so values are read by name; XML parses with ElementTree into a tree of elements the program walks and loops over. Name the three moves of the JSON fetch as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: fetch a web service’s JSON answer with urllib and parse it with the json module. Do this with a real example of your own — in a real Python program, fetching the live ISS service if the connection allows, or the book’s films.xml offline — and write or say how you know it is right.
2. Show it, don't just say it: read values out of the parsed JSON by name, and loop over a list inside it. Do this with a real example of your own — in a real Python program, fetching the live ISS service if the connection allows, or the book’s films.xml offline — and write or say how you know it is right.
3. Show it, don't just say it: parse an XML file with ElementTree and describe its tree of elements. Do this with a real example of your own — in a real Python program, fetching the live ISS service if the connection allows, or the book’s films.xml offline — and write or say how you know it is right.
4. Show it, don't just say it: loop over all elements of one kind in an XML file and print a chosen field from each. Do this with a real example of your own — in a real Python program, fetching the live ISS service if the connection allows, or the book’s films.xml offline — and write or say how you know it is right.
