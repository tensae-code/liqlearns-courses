# Structured Data — Objects, Descriptors and Collections

## Do it first

Choose one object in the room — a book, a bag, a chair. Your task: describe it so precisely that a stranger could find exactly it among a hundred similar objects, and could answer questions about it without seeing it. What facts do you need? Its kind? Its colour? Its size? Who owns it? Write the list of facts you chose. Now the hard question: would the same list of facts work to describe every other object of the same kind? Keep your list — the lesson gives names to the object, to your list, and to the gathering of many objects described the same way.

## Sub lesson 1 — Objects and their descriptors

To store facts about the world, first decide what one **object** is: one book, one student, one product — a single thing the data is about. Then decide how it will be described. Each named aspect is a **descriptor**: for a book, its title, its author, its year, its number of pages. For one particular book, each descriptor holds a **value**: the title is this title, the year is 2023. Object, descriptor, value — with those three words you can describe anything, and the describing is a human decision: a library describes a book by author and year; a bookshop describes the same book by price and stock. Neither is wrong; the purpose chooses the descriptors.

In your mind's eye: one book with labelled lines running from it to its descriptors and their values. Title, author, year, pages.

## Sub lesson 2 — Collections — data in tables

One described object is a note; the power comes from gathering many. A **collection** is a set of objects described by **the same descriptors** — all the books with title, author, year, pages; all the students with name, class, birth year. A collection has a natural drawing: the **table**. Each **row** is one object. Each **column** is one descriptor, headed by its name, and every cell holds that object's value for that descriptor. An empty cell means the value is missing — the table shows that honestly too.

This shape is not one program's habit; it is the shape of structured data itself. The spreadsheet grid is this table. The CSV file is this table written as text. The database table of the later lessons is this table with rules added. France's SNT book begins its whole data theme here — objects, descriptors, collections — because everything after, from file formats to SQL, is this one idea at work.

In your mind's eye: three described books becoming the three rows of a table, their shared descriptors becoming the column headings.

## Say it to your companion

Tell your companion, in your own words: an object is one thing described; a descriptor is a named aspect of it, holding a value for each object; a collection gathers objects sharing the same descriptors and draws as a table — rows for objects, columns for descriptors. Describe one object near you, then sketch its collection’s table, as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: describe one object by at least four descriptors, each with its value. Do this with a real example of your own — with objects from the room around you, drawn as a table on paper — and write or say how you know it is right.
2. Show it, don't just say it: explain why the choice of descriptors depends on the purpose of the data. Do this with a real example of your own — with objects from the room around you, drawn as a table on paper — and write or say how you know it is right.
3. Show it, don't just say it: turn a small collection of objects into a table with the rows and columns in the right places. Do this with a real example of your own — with objects from the room around you, drawn as a table on paper — and write or say how you know it is right.
4. Show it, don't just say it: say what an empty cell in such a table means. Do this with a real example of your own — with objects from the room around you, drawn as a table on paper — and write or say how you know it is right.
