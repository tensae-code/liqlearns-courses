# NMEA Frames — How GPS Devices Report Position

## Do it first

Here is one line, exactly as a GPS receiver printed it: `$GPGGA,123519,4807.038,N,01131.000,E,1,08,0.9,545.4,M,46.9,M,,*47`. It looks like noise — but it is a complete report: where the receiver is, when, and how well it knows. Harvest it: which pieces might be a time? Which two look like the coordinates from the latitude lesson, and what is odd about their writing? What might the single digit 1 and the number 545.4 be? Write your guesses field by field. Keep them — the lesson now walks the frame field by field, and the programming part decodes one exactly.

## Sub lesson 1 — The $GPGGA frame field by field

GPS receivers speak **NMEA 0183**, a standard of one-line text sentences called **frames**, each beginning with **$**. The frame that matters most is **$GPGGA** — the fix data. Its fields, separated by commas, in order: the **time** in UTC, written hhmmss (123519 = 12:35:19); the **latitude**, written as **ddmm.mmmm** — two digits of degrees, then minutes with decimals (4807.038 = 48° 07.038′) — followed by **N or S**; the **longitude** as **dddmm.mmmm** — three digits of degrees, since longitude runs to 180 — followed by **E or W**; the **fix quality** (1 = a real GPS fix); the **number of satellites** used (08); a precision figure; the **altitude** in metres (545.4); and after the **\***, a **checksum** — a guard value computed from the whole line, so a corrupted frame can be detected and dropped.

To use the position, convert: 48° + 07.038/60 = 48.1173° N; 011° + 31.000/60 = 11.5167° E. The mystery of the writing is only that minutes arrive decimalised and glued to the degrees — split, divide by 60, add.

[Picture — one $GPGGA line stretched out with each field bracketed and named, the two coordinates pulled out and converted beneath]

## Sub lesson 2 — Decoding a frame in Python

What a hand can do for one frame, a program does for thousands — a boat’s whole day is a file of frames. The SNT book’s En codant strand writes the decoder in **Python**: read each line; keep the $GPGGA ones; **split on the commas**; take the fields by position; convert the coordinate fields (the first two or three digits are degrees, the rest is minutes; divide the minutes by 60 and add; then let the hemisphere letter set the sign — south and west negative). With decimal latitude and longitude in hand, the **folium** library drops the point onto a map, and a file of frames becomes the drawn track of the voyage — the same frames the book’s Activités decode by hand from a sailboat’s log. Hand first, then machine: you cannot trust the decoder’s map until you have decoded one frame yourself.

[Picture — a coastline with a dotted boat track along it, three frames from the log printed beside their points on the track]

## Say it to your companion

Tell your companion, in your own words: a GPS receiver reports in NMEA frames; $GPGGA carries time, latitude and longitude in a degrees-and-decimal-minutes writing, fix quality, satellites and altitude, guarded by a checksum; converting means splitting the degrees from the minutes, dividing the minutes by 60, and signing by the hemisphere letter. Decode the lesson’s frame aloud as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book’s exact words.

## Do It Yourself

1. Show it, don't just say it: name the fields of a $GPGGA frame in order. Do this with a real example of your own — with the printed frame in the lesson, or a real GPS log if one is available — and write or say how you know it is right.
2. Show it, don't just say it: convert an NMEA latitude and longitude into decimal degrees, with the right sign. Do this with a real example of your own — with the printed frame in the lesson, or a real GPS log if one is available — and write or say how you know it is right.
3. Show it, don't just say it: say what the fix quality field and the checksum are for. Do this with a real example of your own — with the printed frame in the lesson, or a real GPS log if one is available — and write or say how you know it is right.
4. Show it, don't just say it: describe the Python decoder’s steps from a frame to a point on a map. Do this with a real example of your own — with the printed frame in the lesson, or a real GPS log if one is available — and write or say how you know it is right.
