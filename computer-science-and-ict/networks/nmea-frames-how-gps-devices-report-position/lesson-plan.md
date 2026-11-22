# Lesson plan — NMEA Frames — How GPS Devices Report Position

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** NMEA Frames — How GPS Devices Report Position
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Networks on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A GPS receiver reports its work as NMEA 0183 frames — one-line text sentences beginning with $, the most useful being $GPGGA, whose comma-separated fields carry the time, the latitude and longitude in a degrees-and-minutes writing, the fix quality and the altitude — a frame anyone can decode by hand and a program can decode exactly.
**This lesson's own level:** It stands on the latitude/longitude lesson and on the GPS lesson. The frame is plain text; no electronics is needed.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The $GPGGA frame field by field** — The anatomy: $ and the talker/type GPGGA; then fields separated by commas — UTC time; latitude as ddmm.mmmm with N/S; longitude as dddmm.mmmm with E/W; fix quality; satellites used; precision; altitude; and the checksum after the * that guards the line against corruption.
2. **Decoding a frame in Python** — The program’s road: split the sentence on commas, pick the fields by their positions, convert the NMEA coordinate writing (degrees and decimal minutes) into decimal degrees, apply the hemisphere letters, and place the result on a map with folium — the book’s En codant work.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Networks lessons on latitude and longitude and on GPS, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Localisation, cartographie et mobilité", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Name the fields of a $GPGGA frame in order.
2. Convert an NMEA latitude and longitude into decimal degrees, with the right sign.
3. Say what the fix quality field and the checksum are for.
4. Describe the Python decoder’s steps from a frame to a point on a map.

## What you need
Paper and a pencil; a computer with Python for the decoding part, if available.

## The run of the lesson (in order)
1. **Do it first** — Read one real $GPGGA line with no help and harvest every number you can guess the meaning of — before the lesson names the fields. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one $GPGGA line stretched out with each field bracketed and named, the coordinates converted beneath — the student brackets the fields of a second frame without the names
   - ADD GIF: a GIF of a frame’s fields lighting up one by one as a voice reads their meanings — the student names the next field before it lights
   - ADD IMAGE: a picture of a coastline with a dotted boat track and three frames printed beside their points — the student picks one frame and says which point on the track is its
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one $GPGGA line stretched out with each field bracketed and named, the coordinates converted beneath → the student brackets the fields of a second frame without the names
- GIF — a GIF of a frame’s fields lighting up one by one as a voice reads their meanings → the student names the next field before it lights
- IMAGE — a picture of a coastline with a dotted boat track and three frames printed beside their points → the student picks one frame and says which point on the track is its
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Reads 4807.038 as 48.07038° → the writing is degrees then minutes: 48° and 07.038 minutes; the minutes must be divided by 60 before joining. Longitude split wrongly → longitude takes THREE degree digits (dddmm.mmmm), latitude two. Loses the hemisphere → N/S and E/W are separate fields; south and west make the decimal value negative, and a dropped letter puts the point in the wrong ocean.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book decodes a sailboat’s NMEA frames by hand in the Activités of its localisation theme and programs the decoder with folium in En codant — this lesson keeps that hand-then-machine order.
