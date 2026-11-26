# Steganography — Hiding Messages in Images

## Do it first

Two pixels: (200, 60, 40) and (201, 60, 40). The reds differ by one part in 255. Displayed side by side, no eye on Earth can tell them apart. Now think like a spy: that worthless last step of each number — the difference between even and odd — could carry something. Each colour number of each pixel could secretly stand for one bit of a message, and the photo would look utterly unchanged. Keep the idea — the lesson names this art, shows the exact scheme the SNT book programs, and its limits.

## Sub lesson 1 — Hiding bits in the least significant bits

**Steganography** is the art of hiding the very existence of a message — not scrambling it, as encryption does, but tucking it inside something ordinary. For images, the hiding place is the **least significant bit** (LSB) of each colour value. A colour value is a byte, a number from 0 to 255 written in binary with eight bits; the last bit contributes just 1 to the value. Set it to 0 and the value is even; set it to 1 and it is odd; either way it moves by at most one — far below what an eye can see, as Do it first showed.

The scheme is then simple: take the message's bits one by one, and write them into the LSBs of the red, green and blue values, pixel after pixel, in an order both sides agree on. A photo of twelve million pixels offers thirty-six million hiding places — room for whole books — while looking, to any eye, exactly like the innocent original.

In your mind's eye: one colour byte drawn as eight bit boxes, the last box highlighted and being swapped for a message bit, the value changing from 200 to 200.

[Picture 46411 — one colour byte drawn as eight bit boxes, the last box highlighted and being swapped for a message bit, the value changing from 200 to 200]

## Sub lesson 2 — Coding and decoding a hidden message

To hide text, the letters must first become bits. The SNT book uses a **base-64 code on 6 bits**: each character is given a number among 64 possibilities, written in binary with exactly six bits — six hiding places per letter. The **coding program** walks the image with PIL, as in the filters lesson, but instead of computing new colours it writes the message's bits into the LSBs, then saves the image — as a **PNG**, never a JPEG, because JPEG compression rewrites the colour values and would shred the hidden bits. The **decoding program** walks the same pixels in the same order, reads the LSBs, groups them by six, and turns the numbers back into letters: the message steps out of the photo.

Two limits keep the art honest. Capacity and survival: recompressing, resizing or filtering the image destroys the message. And secrecy: steganography hides that a message exists, but anyone who suspects the scheme can read it — hiding is not encrypting, and the two are often combined: encrypt first, then hide.

In your mind's eye: the round trip drawn as a circle. A sentence, its 6-bit codes, an innocent-looking photo, the same sentence again.

[Picture 46412 — the round trip drawn as a circle. A sentence, its 6-bit codes, an innocent-looking photo, the same sentence again]

## Say it to your companion

Tell your companion, in your own words: steganography hides a message in the least significant bits of an image’s colour values, where a change of at most one is invisible; letters become 6-bit codes, a program writes and reads the bits, and the file must survive untouched — no JPEG — for the message to live. Work one byte by hand as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: explain what the least significant bit of a colour value is and why changing it cannot be seen. Do this with a real example of your own — in a real Python program with Pillow, on a copy of a photo — and write or say how you know it is right.
2. Show it, don't just say it: turn a short message into bits with a 6-bit code and say how many hiding places each letter needs. Do this with a real example of your own — in a real Python program with Pillow, on a copy of a photo — and write or say how you know it is right.
3. Show it, don't just say it: describe the coding program and the decoding program, step by step. Do this with a real example of your own — in a real Python program with Pillow, on a copy of a photo — and write or say how you know it is right.
4. Show it, don't just say it: state why the carrier image must be saved as PNG rather than JPEG, and why hiding is not the same as encrypting. Do this with a real example of your own — in a real Python program with Pillow, on a copy of a photo — and write or say how you know it is right.
