# Video script — Connecting a Program to a Database — DataSet and BindingSource

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A VB program works on a database through a **connection** — its opened line to the database file (the book works on the **Db_inf database**). Through the connection, the program fills a **DataSet**: the database's tables **copied into the program's memory**, where the form can show and edit them while the real database waits, untouched, until the work is saved back. The DataSet is the program's working copy — the meeting place, not the store itself.
Between the DataSet and the form's controls stands the **BindingSource**: the component that **binds** a table to the controls, so a grid shows the DataSet's rows and the form's boxes show the **current record** — and moving the current record moves every bound control together. It is the traffic officer of the form: the data changes place, the display follows; the user edits, the BindingSource knows what must be saved.
