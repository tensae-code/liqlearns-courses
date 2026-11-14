# Video script — Building a User Interface

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **graphical interface** is built from **controls** — the window's working furniture — placed by the **Controls object**. **AddButton** puts a labelled button the user can click; **AddTextBox** takes a line of typed input; **AddMultiLineTextBox** takes whole paragraphs. Each control is placed by coordinates, sized, and filled with its text — the GraphicsWindow's grid, furnished. The program's centre of gravity moves: in the console the program asked the questions; in the window the user chooses what happens, and the program must be ready for every choice at once.
A windowed program runs on **events**: the user's acts — a click, a key — arrive in no promised order, and each event is met by its **event handler**, the subprogram written for that event alone. The book's crown builds the whole doctrine into one artefact: a **quadratic-equation solver as a windowed program** — coefficients in text boxes, the solving behind a button, the answer appearing in the window. Mongolia's contrast is the chapter's lesson: the console program is a road; the windowed program is a room with staff — and designing the interface means deciding what the room offers and training the staff, handler by handler.
