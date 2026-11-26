# Connecting a Program to a Database — DataSet and BindingSource

## Do it first

Kuwait's Grade 12 database book makes the VB program and the database meet. Between them stand two named things the pupil must understand before any grid fills: the DataSet and the BindingSource. This lesson is that meeting.

## Sub lesson 1 — The connection and the DataSet — the database, held in the program

A VB program works on a database through a **connection** — its opened line to the database file (the book works on the **Db_inf database**). Through the connection, the program fills a **DataSet**: the database's tables **copied into the program's memory**, where the form can show and edit them while the real database waits, untouched, until the work is saved back. The DataSet is the program's working copy — the meeting place, not the store itself.

In your mind's eye: the connection and the DataSet — the database, held in the program.

[Picture 46471 — the connection and the DataSet — the database, held in the program]

## Sub lesson 2 — The BindingSource — the link between data and form

Between the DataSet and the form's controls stands the **BindingSource**: the component that **binds** a table to the controls, so a grid shows the DataSet's rows and the form's boxes show the **current record** — and moving the current record moves every bound control together. It is the traffic officer of the form: the data changes place, the display follows; the user edits, the BindingSource knows what must be saved.

In your mind's eye: the BindingSource — the link between data and form.

[Picture 46472 — the BindingSource — the link between data and form]

## Say it to your companion

Tell your companion, in your own words: A VB program works on a database through a **connection** — its opened line to the database file (the book works on the **Db_inf database**). Through the connection, the program fills a **DataSet**: the database's tables **copied into the program's memory**, where the form can show and edit them while the real database waits, untouched, until the work is saved back. The DataSet is the program's working copy — the meeting place, not the store itself. Between the DataSet and the form's controls stands the **BindingSource**: the component that **binds** a table to the controls, so a grid shows the DataSet's rows and the form's boxes show the **current record** — and moving the current record moves every bound control together. It is the traffic officer of the form: the data changes place, the display follows; the user edits, the BindingSource knows what must be saved. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: A connection — its opened line to the database file. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Db_inf. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The database's tables copied into the program's memory. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: No — it is the program's working copy; the real database waits until saving back. Do this with a real example of your own and write or say how you know it is right.
