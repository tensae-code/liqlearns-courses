# Video script — Single-Board Controllers — Microcontrollers

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A **single-board controller** is a **microcontroller on a PCB**: one chip holding processor, memory and input/output, mounted on a board that exposes its pins and adds the little it needs to run. It is not a small general computer: it holds **one program**, written for the device it lives in, and runs that program from the moment power arrives — in the washing machine, the toy, the smart bin. Indonesia's Grade 12 chapter sets it beside the single-board computer so the pair is never confused again: the computer runs many programs under an operating system; the controller is one program in a board.
The controller's whole life is a loop: **read** its input pins (sensors, buttons), **decide** by its program, **drive** its output pins (lights, motors, sounds) — forever, at electronic speed, without screen or keyboard. The board around the chip is the lesson's point: power parts, a clock, connection pins and often a USB door for loading the program turn a bare chip into a thing a pupil can build with. Arduino — the next lessons' platform — is this chapter's working example of the kind.
