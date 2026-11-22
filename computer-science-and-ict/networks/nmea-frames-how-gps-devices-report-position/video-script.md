# Video script — NMEA Frames — How GPS Devices Report Position

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

A GPS receiver talks in text. One line at a time. Each line is a frame, and it starts with a dollar sign.

The most useful frame is $GPGGA. Inside, separated by commas: the time. The latitude. The longitude. How good the fix is. How many satellites. The altitude.

The coordinates come in a strange writing: degrees glued to decimal minutes. Split them. Divide the minutes by sixty. Add. Let the letter — north, south, east, west — set the sign.

Now the numbers are decimal degrees, and any map will take them. A whole voyage is just a file of these lines, waiting to be drawn.
