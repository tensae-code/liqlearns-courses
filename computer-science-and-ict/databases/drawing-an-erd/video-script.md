# Video script — Drawing an ERD

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

FULL script — this is the walkthrough script named in the teacher-guide placement for the case-study ERD (item 14): it finds the entities first, then the attributes, then the relationships, and it walks both the book's worked example and the solved case.

---

Today we draw a data model. Not in words — in shapes. Three shapes only.

First shape: a rectangle. A rectangle is an entity — a thing data is kept about.

Draw one. Write STUDENT inside it.

Second shape: an ellipse — an oval. An ellipse is an attribute, a property of the thing.

Hang four ellipses on the student: student ID. Name. Age. Address. Join each one to the rectangle with a short line.

Now a second rectangle: BOOK. Three ellipses: book ID. Title. Publication year.

Third shape — just a line. A line between two entities is a relationship, and we write its name on the line. The student *borrows* the book. Write BORROWS on the line.

That is the whole diagram. Rectangle, ellipse, line. Entity, attribute, relationship.

Now the way to solve any case. Listen to the order, because the order is the skill.

Step one: find the ENTITIES first. In the case from the review, the story names three: a PRODUCT, a CUSTOMER, an ORDER. Three rectangles.

Step two: give each entity its ATTRIBUTES — the properties the case keeps about it. Ellipses around each rectangle.

Step three: draw the RELATIONSHIPS, and check each rule as you draw it. A customer makes one or many orders — line from Customer to Order. An order is for one or more products — line from Order to Product. A product may have no order at all, or belong to only one order — that rule is written at the Product end of the line.

Entities first. Attributes second. Relationships last, checked rule by rule.

Now you: draw the teacher and the schedule. Rectangles first.
