# Video script — Robot PID Control — Keeping on the Line

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**PID** names three corrections added together. **Proportional (P)** corrects by the error **now** — the Grade 8 teaching. **Integral (I)** corrects by the error **accumulated**: a drift that leans the same way for a long time is summed, and the sum pushes back, ending the lean a merely present correction tolerates. **Derivative (D)** corrects by the error's **rate of change**: a fast-growing error is met early, before it becomes a swerve. Now, accumulated, and coming — the three tenses of error.
On the line, the error is the reflected-light reading's distance from the line's edge value, read many times a second. P alone wanders around the edge; I removes the stubborn offset of a curved or tilted run; D damps the zigzag that eager correction causes. Tuning three constants instead of one is harder and is the point: the Grade 9 robot is kept on its line by the same controller family that keeps real machines on theirs — Kuwait's robotics strand arriving at genuine control theory.
