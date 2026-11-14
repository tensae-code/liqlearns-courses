# Video script — Robot Gyroscope Sensor — Precise Turns and Proportional Control

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **gyroscope sensor** measures the robot's **rotation**: how many degrees it has turned from where it started. With it, a turn stops being timed and hoped — the program turns **until the gyro reads the target angle**, then stops: 90 means 90, on any floor, with any battery. Precise turns are the first gift; the second is knowing the robot's heading at every moment, the fact straight driving needs.
Driving straight is a fight against drift, and **proportional control** is the fair way to fight it: measure the **error** — how far the heading is from the target — and correct **in proportion** to it: a big error, a strong correction; a small error, a gentle one. The proportion is set by the constant **Kp**: too small and the robot wanders; too large and it twitches. Tuning Kp — trying, watching, adjusting — is the engineer's real work, and Kuwait teaches it by name in Grade 8.
