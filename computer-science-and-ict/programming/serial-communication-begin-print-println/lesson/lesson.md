# Serial Communication — begin, print, println

## Do it first

Serial communication in Arduino programs — the board talking to the computer: Serial.begin opens the channel, Serial.print and Serial.println send the board's words and numbers

## Sub lesson 1 — Opening the channel — Serial.begin

A board running alone is mute; **serial communication** is its voice — a stream of characters between board and computer over the USB connection, watched in the IDE's Serial Monitor. Every conversation opens with **`Serial.begin(speed)`** in setup() — the speed (9600 is the standing choice) being the agreement both ends must share, or the stream arrives as garbage. Indonesia's Arduino course teaches serial as its own lesson because it is the programmer's window into a running program: without it, a fault inside loop() is invisible; with it, the board reports itself.

In your mind's eye: opening the channel — Serial.begin.

[Picture 47667 — opening the channel — Serial.begin]

## Sub lesson 2 — print and println — sending values out

Two commands send. **`Serial.print(value)`** writes the value — a number as its digits, a text as itself — and stays on the same line; **`Serial.println(value)`** writes it and moves to a new line, so a stream of readings becomes a readable list. With them the board can report anything it knows: the sensor's number, the state of a pin, the name of the step it is on. The debugging habit the lesson builds is permanent: when a program misbehaves, make it *say* what it is doing — print the value, watch the truth, fix the line the truth accuses.

In your mind's eye: print and println — sending values out.

[Picture 47668 — print and println — sending values out]

## Say it to your companion

Tell your companion, in your own words: A board running alone is mute; **serial communication** is its voice — a stream of characters between board and computer over the USB connection, watched in the IDE's Serial Monitor. Every conversation opens with **`Serial.begin(speed)`** in setup() — the speed (9600 is the standing choice) being the agreement both ends must share, or the stream arrives as garbage. Indonesia's Arduino course teaches serial as its own lesson because it is the programmer's window into a running program: without it, a fault inside loop() is invisible; with it, the board reports itself. Two commands send. **`Serial.print(value)`** writes the value — a number as its digits, a text as itself — and stays on the same line; **`Serial.println(value)`** writes it and moves to a new line, so a stream of readings becomes a readable list. With them the board can report anything it knows: the sensor's number, the state of a pin, the name of the step it is on. The debugging habit the lesson builds is permanent: when a program misbehaves, make it *say* what it is doing — print the value, watch the truth, fix the line the truth accuses. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its voice — a stream of characters between board and computer, watched in the Serial Monitor Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Serial.begin(speed), called in setup() Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: 9600 Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The stream arrives as garbage Do this with a real example of your own and write or say how you know it is right.
