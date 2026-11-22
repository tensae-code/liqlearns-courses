# Lesson plan — Latitude and Longitude — Locating Any Place

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** Latitude and Longitude — Locating Any Place
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Networks on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** Every place on Earth is fixed by two numbers: latitude — the angle north or south of the equator, 0° to 90° — and longitude — the angle east or west of the Greenwich meridian, 0° to 180° — written either in decimal degrees or in degrees, minutes and seconds, with altitude as the third number when height matters.
**This lesson's own level:** It stands on angles and decimals from school mathematics and on knowing the equator and the poles. It is the first lesson of the localisation ladder; the GPS lesson builds on it.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The two coordinates** — Latitude measures the angle from the equator — 0° at the equator, 90° at the poles, N or S. Longitude measures the angle from the prime meridian through Greenwich — 0° there, up to 180° east or west. Together they fix one point; neither alone does.
2. **Writing coordinates — decimal, DMS, and altitude** — The two writings: decimal degrees (48.8566°) and degrees-minutes-seconds (48° 51′ 24″), and converting between them — a minute is a sixtieth of a degree, a second a sixtieth of a minute. Altitude, height above sea level, joins as the third number where it matters.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Networks lessons on networks around the world, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Localisation, cartographie et mobilité", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Explain what latitude measures and give its range and letters.
2. Explain what longitude measures, and why its zero line had to be chosen by agreement.
3. Convert a coordinate between decimal degrees and degrees-minutes-seconds.
4. State a place completely — latitude, longitude and altitude — and say what each number does.

## What you need
Paper, a pencil, and a globe or a world map if one is available.

## The run of the lesson (in order)
1. **Do it first** — Try to tell a friend exactly where your school is — so exactly that someone who has never seen your town could stand on the spot — using only numbers, before the lesson gives the world’s two numbers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a globe with the equator and Greenwich meridian bold and one place marked with its two angles — the student points at the place and reads its two angles off the drawing
   - ADD GIF: a GIF of the angle arm rising from the equator to a place, the latitude number growing as it rises — the student calls the latitude when the arm stops at the place they named
   - ADD IMAGE: a picture of one coordinate written in decimal degrees and in DMS with the ×60 conversion steps between — the student converts the next coordinate following the same steps
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a globe with the equator and Greenwich meridian bold and one place marked with its two angles → the student points at the place and reads its two angles off the drawing
- GIF — a GIF of the angle arm rising from the equator to a place, the latitude number growing as it rises → the student calls the latitude when the arm stops at the place they named
- IMAGE — a picture of one coordinate written in decimal degrees and in DMS with the ×60 conversion steps between → the student converts the next coordinate following the same steps
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Swaps the two coordinates → latitude is measured from the equator (never above 90), longitude from Greenwich (up to 180); if a "latitude" exceeds 90, the pair is swapped. Treats minutes as hundredths → minutes and seconds are sixtieths: multiply the decimal part by 60, never by 100. Forgets the letter → 48° alone names two circles’ worth of places, north and south; N/S and E/W are part of the number.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book opens its localisation theme with latitude and longitude before any satellite appears — this lesson keeps that order, as the ground the GPS and NMEA lessons stand on.
