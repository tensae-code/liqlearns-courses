# ON UPDATE CASCADE — Keeping Related Tables in Step — matching

Match each item on the left with the one it belongs to on the right.

**1. (Sub lesson 1) What does PRAGMA foreign_keys = ON do?** → **Switches on the database's enforcement of foreign-key links**

**2. (Sub lesson 1) What are the rules without the switch?** → **Wishes — the links are declared but not enforced**

**3. (Sub lesson 1) Is the switch permanent or per connection?** → **Per connection — every program must turn it on**

**4. (Sub lesson 1) What event does this lesson govern?** → **Updating a parent table's key**

**5. (Sub lesson 1) What does ON UPDATE CASCADE do?** → **Updates every child's foreign key to match, automatically**

**6. (Sub lesson 2) What does NO ACTION do?** → **Refuses the parent update while children still point at the old key**

**7. (Sub lesson 2) When is cascade the right choice?** → **Where the key is a mere label the children must follow**

**8. (Sub lesson 2) When is NO ACTION right?** → **Where a change should never slip through silently**

**9. (Sub lesson 2) What is an orphan child, in this teaching?** → **A child row whose foreign key names no real parent**

**10. (Sub lesson 2) Which book teaches this?** → **Kuwait Grade 11 Information Technology Term 2, Unit 1 Lesson 5**
