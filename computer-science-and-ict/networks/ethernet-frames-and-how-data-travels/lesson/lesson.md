# Ethernet Frames and How Data Travels

## Do it first

Here is one real Ethernet frame, captured from a school network with Wireshark and written out as numbers: it begins with a run of the same byte repeated, then come two addresses of six bytes each, then a short code, then the load it carries, then four bytes at the very end that are not data at all. Before reading on, point at the parts and guess: which bytes say who sent this, which say who must receive it, and which are the parcel itself? Keep your guesses — the lesson now names every field, and you will check them.

## Sub lesson 1 — The parts of an Ethernet frame

Data crossing a local network travels inside an **Ethernet frame**. A frame is an envelope with a fixed shape, and every device on the network reads the same fields in the same order.

The frame opens with a **preamble**: a short run of the same byte repeated, which tells every listening device "a frame is starting — get ready and synchronise your clock." Then comes the **destination address**: the MAC address, six bytes, of the machine the frame is for. Right after it, the **source address**: the MAC address of the machine that sent it — so the receiver always knows who to answer. Next, a two-byte **type** field says what kind of thing the frame is carrying — most often an IP packet, which is how the receiver knows which protocol must take over. Then comes the **data** itself, the parcel. The frame closes with a **frame check sequence**: a few bytes calculated from everything before them. The receiver does the same calculation; if the two results differ, the frame was damaged on the way and is thrown away.

In your mind's eye: one Ethernet frame drawn as a long envelope cut into labelled boxes. Preamble, destination MAC, source MAC, type, data, check sequence.

[Picture 46099 — one Ethernet frame drawn as a long envelope cut into labelled boxes. Preamble, destination MAC, source MAC, type, data, check sequence]

## Sub lesson 2 — Decoding a real frame from a capture

A field list is only words until you read a real one. Network tools such as **Wireshark** capture frames as they pass and show them as hexadecimal bytes, grouped and decoded. Decoding by hand means walking the same road the machine walks: count off the preamble bytes; the next six bytes are the destination MAC — write them in pairs, like 3C:7A:9F:…; the six after that are the source. Two bytes of type follow: the code 0800, for instance, announces an IPv4 packet inside. Everything after that, until the last four bytes, is the carried data — open it and you find the IP packet with its own addresses inside, the envelope within the envelope. The last four bytes are the check sequence, never data.

In your mind's eye: a Wireshark capture line with the bytes coloured in blocks, each block matched to the field it belongs to.

[Picture 46100 — a Wireshark capture line with the bytes coloured in blocks, each block matched to the field it belongs to]

Worked this way, a capture stops being a wall of numbers: it becomes a conversation you can follow frame by frame — who spoke, to whom, carrying what.

## Say it to your companion

Tell your companion, in your own words: an Ethernet frame is an envelope with a fixed shape — preamble, destination MAC, source MAC, type, data, check sequence — and a capture can be decoded by walking the fields in order. Decode the first bytes of the printed frame aloud as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: name the fields of an Ethernet frame in their order and say what each field is for. Do this with a real example of your own — on paper, or from a real capture if Wireshark is available — and write or say how you know it is right.
2. Show it, don't just say it: read the destination and source MAC addresses out of a captured frame written in hexadecimal. Do this with a real example of your own — on paper, or from a real capture if Wireshark is available — and write or say how you know it is right.
3. Show it, don't just say it: say what the type field announces and where the carried data begins and ends in a frame. Do this with a real example of your own — on paper, or from a real capture if Wireshark is available — and write or say how you know it is right.
4. Show it, don't just say it: explain what the frame check sequence does and what happens when it does not match. Do this with a real example of your own — on paper, or from a real capture if Wireshark is available — and write or say how you know it is right.
