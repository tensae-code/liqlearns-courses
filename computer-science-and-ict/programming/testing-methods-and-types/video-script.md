# Video script — Testing Methods and Types

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Black-box testing** judges a program from outside: inputs in, outputs checked, code unseen — it tests *what* the program does. **White-box testing** (glass-box) works from the code: test cases are chosen to walk particular paths, branches and loops *inside* the program. The methods complement each other: black-box can miss an untested inner path; white-box can miss a requirement nobody coded. Armenia's Grade 12 book closes its programming course with testing — concepts and stages first, then methods and types (Lessons 8–9).
Testing also divides by **aim**: **functional** testing checks the program does its jobs; **performance** testing checks speed and load; **usability** testing checks people can use it; **security** testing probes defences; **regression** testing re-runs old tests after a change, to catch what the change broke. By **moment**, tests run during building (unit), at joining (integration), before release (system/acceptance) and after every repair (regression again) — testing is a rhythm, not a final event.
