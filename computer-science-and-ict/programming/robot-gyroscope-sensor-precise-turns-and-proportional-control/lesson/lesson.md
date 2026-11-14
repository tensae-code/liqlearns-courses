# Robot Gyroscope Sensor — Precise Turns and Proportional Control

## Do it first

Counting motor turns makes sloppy corners. Grade 8's next sensor measures the turn itself. This lesson is the gyroscope — and the control idea that turns measurement into straight driving: proportional correction.

## Sub lesson 1 — The gyroscope — knowing the robot's angle

The **gyroscope sensor** measures the robot's **rotation**: how many degrees it has turned from where it started. With it, a turn stops being timed and hoped — the program turns **until the gyro reads the target angle**, then stops: 90 means 90, on any floor, with any battery. Precise turns are the first gift; the second is knowing the robot's heading at every moment, the fact straight driving needs.

[Picture — The gyroscope — knowing the robot's angle]

## Sub lesson 2 — Proportional control — correcting by the error, with Kp

Driving straight is a fight against drift, and **proportional control** is the fair way to fight it: measure the **error** — how far the heading is from the target — and correct **in proportion** to it: a big error, a strong correction; a small error, a gentle one. The proportion is set by the constant **Kp**: too small and the robot wanders; too large and it twitches. Tuning Kp — trying, watching, adjusting — is the engineer's real work, and Kuwait teaches it by name in Grade 8.

[Picture — Proportional control — correcting by the error, with Kp]

## Say it to your companion

Tell your companion, in your own words: The **gyroscope sensor** measures the robot's **rotation**: how many degrees it has turned from where it started. With it, a turn stops being timed and hoped — the program turns **until the gyro reads the target angle**, then stops: 90 means 90, on any floor, with any battery. Precise turns are the first gift; the second is knowing the robot's heading at every moment, the fact straight driving needs. Driving straight is a fight against drift, and **proportional control** is the fair way to fight it: measure the **error** — how far the heading is from the target — and correct **in proportion** to it: a big error, a strong correction; a small error, a gentle one. The proportion is set by the constant **Kp**: too small and the robot wanders; too large and it twitches. Tuning Kp — trying, watching, adjusting — is the engineer's real work, and Kuwait teaches it by name in Grade 8. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The robot's rotation — degrees turned from its start. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The program turns until the gyro reads the target angle, then stops. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 90 means 90 on any floor, with any battery — the turn is measured, not hoped. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The robot's heading at every moment. Do this with a real example of your own and write or say how you know it is right.
