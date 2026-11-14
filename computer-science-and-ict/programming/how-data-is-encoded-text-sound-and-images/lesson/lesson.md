# How Data Is Encoded — Text, Sound and Images

## Do it first

Hold three things in your mind: the letter A, one second of a sung note, and a photograph of your face. The computer stores all three as nothing but numbers — but not by the same trick. Each kind has its own code. This lesson opens all three codes and looks inside.

## Sub lesson 1 — Encoding text — every character a number

Text is the simplest code. The characters a language uses are listed in an agreed table, and each character is given a number: in the **ASCII** code, capital A is 65, B is 66, the digit 5 is 53 — and the computer stores the number, in binary, wherever the character appears. Wider tables such as Unicode extend the same idea to the characters of all the world's scripts, including Chinese characters, so any text in any language becomes numbers by one rule: *look the character up, store its number; look the number up, get the character back.* Encoding and decoding are the same table read in opposite directions.

[Picture — a code table like a bus timetable — letters down the side, numbers beside them — with the letter A highlighted beside its number 65, and 65 rewritten in binary beside it]

## Sub lesson 2 — Encoding sound and images — sampling and pixels

A sound is continuous, so it cannot be looked up — it must be **sampled**: the wave's height is measured at regular moments, thousands of times per second, and each measurement is stored as a number. Played back, the numbers rebuild a wave so close to the original that the ear accepts it; more samples per second and finer measurements mean a closer copy and a bigger file. An image is split instead of timed: it is cut into a grid of tiny dots, **pixels**, and each pixel's colour is stored as numbers (for example, amounts of red, green and blue). More pixels mean a sharper picture and, again, a bigger file. Quality against size is the trade every encoding makes.

[Picture — a sound wave being measured by a row of vertical lines rising one after another, each turning into a number — then the same numbers growing back into the wave]

## Say it to your companion

Tell your companion, in your own words: text is encoded by a code table — each character a number; sound is encoded by sampling — measuring the wave thousands of times a second; images are encoded as pixels — each dot's colour as numbers; and more detail always means a bigger file. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say how text is encoded, using a code table such as ASCII, and decode a number back to its character. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: say how sound is encoded by sampling, and what more samples per second changes. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: say how an image is encoded with pixels and colour numbers. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: state the trade every encoding makes: more detail (quality) against bigger file size. Do this with a real example of your own and write or say how you know it is right.
