# Lesson plan — EXIF Metadata — the Hidden Data in Photos

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** EXIF Metadata — the Hidden Data in Photos
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Every digital photo file secretly carries a block of written data about itself — the EXIF metadata: the camera or phone that took it, the date and time, the settings, and very often the GPS coordinates of the place — and anyone who receives the photo can read all of it.
**This lesson's own level:** It stands on the image-formats lesson (a photo is a file) and on the idea of metadata from the databases lessons. It also feeds the localisation lessons: EXIF coordinates are latitude and longitude.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **What EXIF records** — The EXIF block inside a JPEG or HEIC file: device make and model, date and time, exposure and flash settings, image size — and, when location is on, the GPS latitude and longitude of the shot; all written automatically at the moment of capture, invisible in the picture itself.
2. **Reading EXIF and finding where a photo was taken** — Opening a photo’s properties or using a small program to read the EXIF; converting the stored GPS numbers into a point on a map; and the privacy lesson — sharing a photo shares its EXIF, so the book teaches checking and stripping it before posting photos of home.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Multimedia lesson on image file formats and the Databases lesson on metadata, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "La photographie numérique", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. List the main kinds of data an EXIF block holds and say when they are written.
2. Explain why EXIF coordinates can reveal where a photo was taken.
3. Read a photo’s GPS numbers from its EXIF and place them on a map.
4. Say how to share a photo without giving away its location.

## What you need
Paper and a pencil. A phone or computer with a photo to inspect makes the hands-on work direct; the lesson stands without one.

## The run of the lesson (in order)
1. **Do it first** — Look at one photo on a phone and list everything the phone could tell a stranger about it beyond what the picture shows — before the lesson names the data block. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one photo shown twice — the picture, and beside it its EXIF record as a list with device, date, settings and GPS numbers — the student reads the record and says which line could betray the photographer’s home
   - ADD GIF: a GIF of GPS numbers being copied from an EXIF list onto a map, the pin dropping as the second number lands — the student says which number is latitude and which is longitude before the pin drops
   - ADD IMAGE: a picture of a phone’s share sheet with the "remove location" choice highlighted — the student explains what that choice removes and what it leaves in the file
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one photo shown twice — the picture, and beside it its EXIF record as a list with device, date, settings and GPS numbers → the student reads the record and says which line could betray the photographer’s home
- GIF — a GIF of GPS numbers being copied from an EXIF list onto a map, the pin dropping as the second number lands → the student says which number is latitude and which is longitude before the pin drops
- IMAGE — a picture of a phone’s share sheet with the "remove location" choice highlighted → the student explains what that choice removes and what it leaves in the file
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks EXIF is part of the picture → it is a separate written block inside the file; the picture can be printed with none of it showing. Cannot use the GPS numbers → they are latitude and longitude, stored as degrees/minutes/seconds; convert each to decimal degrees, then place the pair on a map. Assumes sharing always strips EXIF → platforms often strip it on upload, but original files sent directly usually keep it; check before trusting.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book returns to EXIF twice — extracting it in the photography theme and hunting a mystery photo’s location in the localisation theme; this lesson carries both placements, in that order.
