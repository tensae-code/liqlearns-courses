# Video script — Building a Number Converter in PHP

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

In the PHP telling, the converter's parts change their homes. The **form** — number field, from-system and to-system choices, convert button — lives in the visitor's browser. On submit, the values travel to the **server**, where the PHP reads them, **validates** them (a binary field holding a 2 is refused here, exactly as in the desktop project), runs the **conversion**, and **generates the answer page**. The visitor's experience is one honest round trip: type, send, read. Everything the Grade 11 course taught about dynamic pages — request, processing, generated answer — is spent here on Grade 12's mathematics.
Not one conversion rule changes: repeated division for decimal-out, place values for decimal-in, groups of four bits between binary and hexadecimal. That is the project's argument, made by building it: the **algorithm** is the durable possession; VB.NET forms and PHP pages are two temporary houses for it. The testing discipline travels too — the PHP converter is checked against the same hand-worked conversions as its desktop twin, and a difference between the twins is a fault in a house, never in the mathematics. With this subject, Unit One closes as Unit Two will: learn the thing, build it twice, and finish able to say what stayed the same — because that, and only that, is what was actually learned.
