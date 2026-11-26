# Tabular File Formats — CSV, JSON and XML

## Do it first

On paper, draw a tiny table: three students, with name, class and birth year. Now forget the drawing. Your task: write the same information as pure text, in a file any computer could read, with no table lines at all. How will the reader know where one value ends and the next begins? Where one student ends and the next begins? How will they know which value is the name and which the year? Invent your answers and write the file. Keep it — the lesson shows the three standard answers the world settled on, and one of them is probably close to yours.

## Sub lesson 1 — Spreadsheet files and CSV

A **spreadsheet file** — **XLSX** (Excel) or **ODS** (LibreOffice) — stores much more than data: formulas, colours, column widths, several sheets. That richness has a price: the file belongs to one family of programs, and its content is not readable as plain text. When data must travel simply, the world uses **CSV** — comma-separated values. A CSV file is the table as pure text. The **first line is the header**: the descriptors’ names, separated. Each following line is **one row**, its values in the header’s order, separated by the same mark. The mark is usually a comma — but in France, where the comma is the decimal separator in numbers, CSV files conventionally use the **semicolon**, a detail the SNT book insists on because French students meet it in every real file. CSV carries no presentation and no formulas: values only — which is exactly why every program on Earth can read it.

In your mind's eye: one small table shown three ways. As a spreadsheet grid, then as the same table typed as CSV text with the header line underlined.

[Picture 46612 — one small table shown three ways. As a spreadsheet grid, then as the same table typed as CSV text with the header line underlined]

## Sub lesson 2 — JSON and XML — structured text formats

Sometimes values need their names attached one by one, and data must nest — a list inside an object, objects inside a list. Two text formats do this. **JSON** (JavaScript Object Notation) writes an object as braces holding **name–value pairs** — `"nom": "Awa", "annee": 2009` — and lists in square brackets; it is the language web services speak, as the programming lessons will use it. **XML** writes a **tree of elements**: each value is wrapped in a named tag — `<eleve><nom>Awa</nom><annee>2009</annee></eleve>` — with opening and closing tags nesting like the DOM tree of a web page. Both are plain text, both name every value so no header order must be remembered, and both are heavier than CSV for a simple flat table. The craft is choosing: flat table for a spreadsheet — CSV; data exchanged between programs, nested or named — JSON or XML; a document to be presented — the spreadsheet file itself.

In your mind's eye: the same student written three ways. One CSV line, one JSON object, one XML element tree, the three names and years colour-matched across the three.

[Picture 46613 — the same student written three ways. One CSV line, one JSON object, one XML element tree, the three names and years colour-matched across the three]

## Say it to your companion

Tell your companion, in your own words: XLSX and ODS carry data with its presentation; CSV is the table as plain text with a header line and one row per line, separated by commas or, in France, semicolons; JSON and XML name every value — pairs in braces, or tagged elements in a tree — for programs exchanging data. Write one student in all three formats as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: write a small table as a correct CSV file, header line included. Do this with a real example of your own — on paper, or in a text editor and spreadsheet if available — and write or say how you know it is right.
2. Show it, don't just say it: say why French CSV files often use the semicolon instead of the comma. Do this with a real example of your own — on paper, or in a text editor and spreadsheet if available — and write or say how you know it is right.
3. Show it, don't just say it: read a small JSON object and state the table it describes. Do this with a real example of your own — on paper, or in a text editor and spreadsheet if available — and write or say how you know it is right.
4. Show it, don't just say it: read a small XML document and state the table it describes, and choose the right format for a given job. Do this with a real example of your own — on paper, or in a text editor and spreadsheet if available — and write or say how you know it is right.
