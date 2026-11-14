# Video script — Digital and Analog Pins — pinMode, Read and Write

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A pin is the board's hand and eye on the world, and every pin must first be told its direction with **pinMode(pin, INPUT or OUTPUT)** — a pin set wrong is the beginner's most common silent fault. A **digital** pin knows two states: **digitalWrite(pin, HIGH or LOW)** drives an output pin fully on or off (lighting the LED, sounding the buzzer), and **digitalRead(pin)** reports an input pin's state — the button pressed or not. Indonesia's Arduino course teaches the pair as one commandment: set the mode, then read or write.
The world is not only on and off: light fades, temperature climbs. **Analog** pins measure and imitate that graded world. **analogRead(pin)** converts a varying voltage — from a light or temperature sensor — into a number (0–1023 on the Uno), and **analogWrite(pin, value)** sets an output's average level (0–255), dimming an LED or pacing a motor as if by degrees. The digital/analog split is the board's two languages: digital for decisions, analog for degrees — and most real projects speak both at once.
