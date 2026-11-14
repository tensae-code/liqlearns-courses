# Video script — HTML Forms

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An HTML **form** (the `<form>` element) collects a visitor's input and sends it to a server. Its commonest field is **`<input>`**, whose **type** attribute chooses its kind: `text` (one line), `password` (hidden as typed), `number`, `email`, `checkbox` (tick any), `radio` (pick one of a group), and `date`. Every field needs a **`<label>`** — the visible words that say what the field asks — joined to the field by matching `for` and `id`. Armenia's Grade 9 book teaches forms together with lists in §5: the page stops only displaying, and starts asking.
A form is sent by its **submit** control (`<button type="submit">` or `<input type="submit">`); the form's **action** says where the data goes and **method** how (GET puts it in the address, POST sends it in the body). Good forms help the visitor: mark needed fields with **required**, give examples in **placeholder** text, keep the form short, and ask only what will actually be used — a form is a request for a stranger's data, and it should behave like one.
