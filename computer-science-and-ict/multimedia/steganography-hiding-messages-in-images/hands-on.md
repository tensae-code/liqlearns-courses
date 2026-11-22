# Hands-on — Steganography — Hiding Messages in Images

The lesson with your hands and your feet, not only your eyes.

## Hide bits by hand
Take these four colour values: 200, 61, 40, 128. Hide the message bits 1, 0, 1, 1 in their least significant bits (change a value only if its last bit differs). Write the new values. Then hand the new values to a partner without the message: can they decode your four bits? What did they need to know?

## The real round trip
With Python and Pillow, write the coding program for a three-letter message using a 6-bit code, hide it in a copy of a photo saved as PNG, then write the decoding program and recover the message. Now save the carrier as JPEG and try decoding again — write down what happened and why.
