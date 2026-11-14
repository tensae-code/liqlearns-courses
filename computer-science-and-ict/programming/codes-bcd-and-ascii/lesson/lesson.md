# Codes — BCD and ASCII

## Do it first

A shop till shows the price 47, and your screen shows the letter K. But inside the machine there are no prices and no letters — there are only bits, 0s and 1s. So the machine and the people who build machines must agree: this pattern of bits means this digit, that pattern means that letter. An agreement like that is called a code. This lesson teaches the two codes Montenegro's book starts with: BCD, which codes decimal digits, and ASCII, which codes letters, digits and signs.

## Sub lesson 1 — The BCD code — each decimal digit in four bits

There are two ways to put the decimal number 47 inside a machine. The way you met in the last lesson is to convert the whole number: 47 = 101111₂. The **BCD** way — BCD stands for **binary-coded decimal** — does something different: it codes *each decimal digit on its own*, in four bits. The digit 4 is 0100, the digit 7 is 0111, so 47 in BCD is **0100 0111**.

Four bits can make sixteen patterns, but a decimal digit needs only ten of them, 0000 to 1001. The six patterns 1010, 1011, 1100, 1101, 1110 and 1111 are never used in BCD — if one of them ever appears, something has gone wrong, which makes BCD easy to check.

[Picture — the number 47 split into its two digits, each digit turning into its own four-bit group, with the plain binary of 47 beside it for contrast]

Why keep a number digit by digit instead of converting it whole? Because some machines live digit by digit: a digital clock, a measuring instrument, a price display, a cash amount. Each digit is shown and handled separately, and BCD matches that exactly — read the groups of four from the left and the decimal number stands in front of you again, with no conversion arithmetic. The price of this convenience is space: BCD uses more bits than plain binary for the same number, and arithmetic in BCD needs extra correction steps, which is why computers calculate in plain binary and use BCD where digits must stay visible one by one.

## Sub lesson 2 — The ASCII code — every character its own number

Numbers are only half of what a machine must hold. The other half is text — letters, digit characters, punctuation, spaces. The agreed code for text is **ASCII**, the American Standard Code for Information Interchange. ASCII gives **every character a fixed number**, written in 7 bits, so there are 128 characters in all: the first 32 are control characters (for jobs like 'new line'), and the rest are the printable characters you can see.

The table is built in a sensible order, and the order itself is worth learning. The space is 32. The digit characters run from '0' = 48 to '9' = 57 — notice: the character '5' is not the number 5; it is code 53, because it is a picture of a digit, not a value. The capital letters run in order from A = 65 to Z = 90, and the small letters from a = 97 to z = 122. So the word *Cat* is the three codes 67, 97, 116 — and in bits, 1000011 1100001 1110100.

[Picture — a strip of the ASCII table showing the space, the digit characters, the capitals and the small letters in their runs, with the word Cat picked out]

Because every maker agreed to the same table, a text file written on one machine opens correctly on any other machine in the world. That is what a standard buys. ASCII's limit is its size: 128 characters cannot hold the letters of every language — Montenegro's own letters č, ć, š, ž and đ are not in it — so wider codes were built later on top of the same idea. The idea itself starts here: a character is a number, and the table is the agreement.

## Say it to your companion

Tell your companion, in your own words: a code is an agreement about which bits mean what; BCD writes every decimal digit separately in four bits, so 47 is 0100 0111; ASCII gives every character a fixed 7-bit number — A is 65, a is 97, the character '0' is 48. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a code is, and write a decimal number in BCD, four bits per digit. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: name the six four-bit patterns BCD never uses, and say where BCD is used and why. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: say what ASCII is, and find the ASCII code of a character from its runs (space 32, '0' = 48, A = 65, a = 97). Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: read a short word given as ASCII numbers back into letters, and say why the character '5' is not the number 5. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
