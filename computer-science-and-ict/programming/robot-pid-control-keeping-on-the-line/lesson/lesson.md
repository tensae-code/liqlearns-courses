# Robot PID Control — Keeping on the Line

## Do it first

Grade 8 corrected drift in proportion to the error. Grade 9 completes the controller: three corrections together, each answering a different failure of the simple one. This lesson is PID — the robot engineer's standard answer to staying on a line.

## Sub lesson 1 — Three corrections — P, I and D

**PID** names three corrections added together. **Proportional (P)** corrects by the error **now** — the Grade 8 teaching. **Integral (I)** corrects by the error **accumulated**: a drift that leans the same way for a long time is summed, and the sum pushes back, ending the lean a merely present correction tolerates. **Derivative (D)** corrects by the error's **rate of change**: a fast-growing error is met early, before it becomes a swerve. Now, accumulated, and coming — the three tenses of error.

[Picture — Three corrections — P, I and D]

## Sub lesson 2 — PID on the line

On the line, the error is the reflected-light reading's distance from the line's edge value, read many times a second. P alone wanders around the edge; I removes the stubborn offset of a curved or tilted run; D damps the zigzag that eager correction causes. Tuning three constants instead of one is harder and is the point: the Grade 9 robot is kept on its line by the same controller family that keeps real machines on theirs — Kuwait's robotics strand arriving at genuine control theory.

[Picture — PID on the line]

## Say it to your companion

Tell your companion, in your own words: **PID** names three corrections added together. **Proportional (P)** corrects by the error **now** — the Grade 8 teaching. **Integral (I)** corrects by the error **accumulated**: a drift that leans the same way for a long time is summed, and the sum pushes back, ending the lean a merely present correction tolerates. **Derivative (D)** corrects by the error's **rate of change**: a fast-growing error is met early, before it becomes a swerve. Now, accumulated, and coming — the three tenses of error. On the line, the error is the reflected-light reading's distance from the line's edge value, read many times a second. P alone wanders around the edge; I removes the stubborn offset of a curved or tilted run; D damps the zigzag that eager correction causes. Tuning three constants instead of one is harder and is the point: the Grade 9 robot is kept on its line by the same controller family that keeps real machines on theirs — Kuwait's robotics strand arriving at genuine control theory. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Proportional, Integral, Derivative. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The error now. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: The accumulated error over time — ending a long lean. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The error's rate of change — meeting a fast-growing error early. Do this with a real example of your own and write or say how you know it is right.
