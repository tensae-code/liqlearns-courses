# Video script — Pulse Generators — and the Clock Signal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **pulse** is a signal that jumps between two levels — low and high — staying a measured time at each: drawn, it is a **rectangle**, not a wave. A **pulse generator** (clock generator) produces an endless, even train of them: the **clock signal**. Its measure is **frequency** — pulses per second, in **hertz (Hz)**, and its inverse, the **period** — the seconds one full pulse cycle takes. A 1 MHz clock beats a million times per second; a gigahertz clock, a billion.
Sequential circuits — flip-flops, registers, counters — change state **at the clock's edge**, all together: the clock is the conductor whose beat makes a million separate circuits one **synchronous** machine. Without it, signals would arrive at their own speeds and memory would smear. The clock's frequency therefore **rates the whole computer**: operations per second track it, which is why processors advertise it. Grade 11's next chapter — architecture — assembles its computer on this beat.
