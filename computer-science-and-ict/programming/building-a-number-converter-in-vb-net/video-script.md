# Video script — Building a Number Converter in VB.NET

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **number-conversion project** takes a number **in** one system and returns it **in** another — decimal to binary, binary to hexadecimal, and their reverses — the conversions of the systems lesson, done by a program the pupil owns. Building it in **VB.NET** means a form again: a place to type the number, a choice of the systems (from, to), a convert action, and a place the answer appears. The design discipline comes first, as in every Egypt project: the procedures for implementing it are set out before code — what the form holds, what each part does, what the program must refuse (a 'binary' number containing a 2 is not binary, and the converter must say so).
Inside, the converter runs the **same algorithms** the pupil learned on paper: decimal to another base by **repeated division** with remainders read back; another base to decimal by **place values** multiplied and added; binary and hexadecimal trading by **groups of four bits**. The program's value over paper is speed and tirelessness; the paper's value over the program is **checking** — Egypt's project is tested against hand-worked conversions, because a converter that cannot be checked is a guess with a form around it. Finished, the project is rebuilt in PHP — the course's standing pattern — and the pair together close Unit One: the systems learned, then built, twice.
