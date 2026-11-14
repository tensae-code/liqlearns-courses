# Representing Information Through Coding

## Do it first

Look at a barcode on any packet, a QR square on a poster, the number on a player's shirt. None of them is the thing itself — stripes, squares, a number — yet each stands for the thing, and a reader who knows the rule gets the thing back. That act — representing information by a rule in another form — is coding, and it is the doorway to everything a computer stores: the computer's own form, as the next lesson shows, is bits.

## Sub lesson 1 — What a code is — representation by rule

A **code** is an assignment rule: it pairs every piece of information with a **sign** that stands for it. Writing with the rule is **encoding**; reading back with the rule is **decoding**. The information does not change — only its form does. The letter A is information; ·− in Morse, a pattern of stripes, and the number 1 on a list are three of its possible signs, under three different codes.

Codes are chosen for their **channel**. Morse code (dots, dashes, gaps) fits a channel that can only beep, flash or tap — a telegraph wire, a torch at night. A barcode fits a laser scanner at a till. A QR code fits a phone camera and holds far more than stripes can. The player's number fits eyes across a stadium. Same idea everywhere: first ask *what must carry the message*, then pick signs that channel can hold.

[Picture — coding-representations: one letter and one price shown four ways — as a letter, in Morse, as a barcode, and as a QR square]

A code also lives or dies by being shared. The sign means nothing without the rule: ·− is just beeps to someone who has never seen the Morse table. Every code in this strand — and every cipher in the lessons after it — is a rule that sender and receiver hold in common, or agree before the message travels.

## Sub lesson 2 — What a good code must do

Three demands decide whether a code works. First, **unambiguous**: one sign must never stand for two different things, or decoding becomes guessing. Second, **uniquely decodable**: when signs run together in a stream, there must be only one way to split the stream back into signs. If A = ·− and B = ·−·− sent back to back without gaps, the beeps ·−·− could be one B or two As — a failed code for that channel, unless gaps (themselves part of the rule) separate the letters.

Third, a code should **fit the traffic**: frequent items deserve short signs. Morse knew this in the 1830s — E, the commonest letter in English, is a single dot; rare Q is dash-dash-dot-dash. Short-for-frequent keeps messages quick and small, and the same pressure shapes how computers pack data.

[Picture — coding-uniqueness: a stream of dots and dashes splitting two ways under a bad code, and only one way under a good code]

Some codes even build in a tripwire for damage: an extra sign computed from the others (a **check digit**, like the last digit of a barcode) lets the reader notice a misread or a smudge — the code then not only represents the information, it guards it. Hold the three demands — unambiguous, uniquely decodable, fitted to its traffic — and you can judge any code, including the ones the computer itself uses in the next lesson.

## Say it to your companion

Tell your companion, in your own words: a code is a rule pairing information with signs; encoding writes with the rule, decoding reads back; a good code is unambiguous, uniquely decodable, and fits its channel and traffic. Encode your companion's initials in a code of your own as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a code is, and name the rule that makes a given representation a code. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: encode and decode a short message with a simple given code. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: judge a code against the job: say why it must be unambiguous and suited to its channel. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
