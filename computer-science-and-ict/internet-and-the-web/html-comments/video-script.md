# Video script — HTML Comments

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

An HTML **comment** begins with **<!--** and ends with **-->**: <!-- Menu starts here -->. Everything between the marks is **ignored by the browser** — it is not shown on the page, takes no space, and cannot be a heading, image or link. Comments can stand on their own line or sit after code on the same line, and a comment can cover several lines. The shape is strict: a missing closing mark swallows the rest of the page's code into the comment, and the page breaks below it.
Comments serve the **people who maintain the code**: they label the parts of a page (<!-- Banner -->), leave reminders (<!-- Update the exam dates in June -->), and explain unusual code. A second working use is **switching code off**: wrapping a block in comment marks hides it without deleting it, so it can be restored by removing the marks. Malaysia's caution stands with the uses: comments are visible to anyone who views the page's source, so a comment is a note to fellow builders — never a place for passwords or private remarks.
