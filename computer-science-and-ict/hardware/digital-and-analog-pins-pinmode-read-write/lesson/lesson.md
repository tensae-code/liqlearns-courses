# Digital and Analog Pins — pinMode, Read and Write

## Do it first

Digital and analog pins — commanding an Arduino's pins: pinMode sets a pin's direction, digitalRead and digitalWrite work the on/off pins, analogRead and analogWrite the graded ones

## Sub lesson 1 — Digital pins — direction first, then read and write

A pin is the board's hand and eye on the world, and every pin must first be told its direction with **pinMode(pin, INPUT or OUTPUT)** — a pin set wrong is the beginner's most common silent fault. A **digital** pin knows two states: **digitalWrite(pin, HIGH or LOW)** drives an output pin fully on or off (lighting the LED, sounding the buzzer), and **digitalRead(pin)** reports an input pin's state — the button pressed or not. Indonesia's Arduino course teaches the pair as one commandment: set the mode, then read or write.

In your mind's eye: digital pins — direction first, then read and write.

[Picture 45182 — digital pins — direction first, then read and write]

## Sub lesson 2 — Analog pins — the graded world

The world is not only on and off: light fades, temperature climbs. **Analog** pins measure and imitate that graded world. **analogRead(pin)** converts a varying voltage — from a light or temperature sensor — into a number (0–1023 on the Uno), and **analogWrite(pin, value)** sets an output's average level (0–255), dimming an LED or pacing a motor as if by degrees. The digital/analog split is the board's two languages: digital for decisions, analog for degrees — and most real projects speak both at once.

In your mind's eye: analog pins — the graded world.

[Picture 45183 — analog pins — the graded world]

## Say it to your companion

Tell your companion, in your own words: A pin is the board's hand and eye on the world, and every pin must first be told its direction with **pinMode(pin, INPUT or OUTPUT)** — a pin set wrong is the beginner's most common silent fault. A **digital** pin knows two states: **digitalWrite(pin, HIGH or LOW)** drives an output pin fully on or off (lighting the LED, sounding the buzzer), and **digitalRead(pin)** reports an input pin's state — the button pressed or not. Indonesia's Arduino course teaches the pair as one commandment: set the mode, then read or write. The world is not only on and off: light fades, temperature climbs. **Analog** pins measure and imitate that graded world. **analogRead(pin)** converts a varying voltage — from a light or temperature sensor — into a number (0–1023 on the Uno), and **analogWrite(pin, value)** sets an output's average level (0–255), dimming an LED or pacing a motor as if by degrees. The digital/analog split is the board's two languages: digital for decisions, analog for degrees — and most real projects speak both at once. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its direction — with pinMode(pin, INPUT or OUTPUT) Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: A pin set to the wrong mode Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Drives an output pin fully on (HIGH) or off (LOW) Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: An input pin's state — the button pressed or not Do this with a real example of your own and write or say how you know it is right.
