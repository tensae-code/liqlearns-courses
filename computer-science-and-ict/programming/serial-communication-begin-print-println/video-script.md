# Video script — Serial Communication — begin, print, println

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A board running alone is mute; **serial communication** is its voice — a stream of characters between board and computer over the USB connection, watched in the IDE's Serial Monitor. Every conversation opens with **`Serial.begin(speed)`** in setup() — the speed (9600 is the standing choice) being the agreement both ends must share, or the stream arrives as garbage. Indonesia's Arduino course teaches serial as its own lesson because it is the programmer's window into a running program: without it, a fault inside loop() is invisible; with it, the board reports itself.
Two commands send. **`Serial.print(value)`** writes the value — a number as its digits, a text as itself — and stays on the same line; **`Serial.println(value)`** writes it and moves to a new line, so a stream of readings becomes a readable list. With them the board can report anything it knows: the sensor's number, the state of a pin, the name of the step it is on. The debugging habit the lesson builds is permanent: when a program misbehaves, make it *say* what it is doing — print the value, watch the truth, fix the line the truth accuses.
