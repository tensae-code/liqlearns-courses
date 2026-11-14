# Video script — JavaScript — Making Pages Interactive

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A page of HTML and CSS alone is fixed at the moment it loads: it can be read, styled and linked, but it cannot **react**. **JavaScript** is the page's behaviour layer — a programming language whose scripts are written into or linked from the page and run **in the visitor's browser** when something happens: a click, a key press, a form sent. The script can change the page on the spot — show, hide, calculate, warn — **without reloading** it. Egypt's order is the web's own: structure, style, then behaviour, each layer standing on the one before.
A first JavaScript program follows the pattern of every program in this course: an **event** wakes the script (the button was clicked), the script **reads** the page's values (what the visitor typed), **decides** (is the field empty? is the number in range?), and **acts** (show the message, mark the field, allow the sending). Form checking is the classic first job because it shows the layer's whole point: the visitor is answered **immediately**, by their own browser, instead of after a round trip to the server. The chapter then hands this skill to the quiz app — a page that asks, checks and scores is HTML and CSS for its face, and JavaScript for its mind.
