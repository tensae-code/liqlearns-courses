# Video script — Data Integrity, Consistency and Redundancy

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Data integrity** means the data is **correct and complete** — true values, entered under rules (a mark between 0 and 100, a date that exists), not corrupted or half-saved. **Data consistency** means the database **never disagrees with itself**: the same fact, wherever it is read, reads the same. A pupil's class changed in the class list must be the same class in the marks list. Integrity guards each value; consistency guards the agreement between values.
**Redundancy** is storing the **same fact in more than one place**. It wastes storage, but its deeper harm is that the copies can **drift apart** — update one, miss another, and consistency is broken by the design itself. Malaysia's design answer follows: store each fact **once**, in its own table, and let other tables **refer** to it by a key rather than copy it. Some copying is sometimes accepted knowingly for speed — but as a chosen trade, never as an accident of design.
