# Lesson plan — Colour Models — RGB, HSL and CMYK

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Colour Models — RGB, HSL and CMYK
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A colour can be named by numbers in more than one system: RGB mixes red, green and blue light for screens; HSL names a colour by its hue, saturation and lightness, the way a person describes it; and CMYK mixes cyan, magenta, yellow and black inks for printing — each model fits the machine that must reproduce the colour.
**This lesson's own level:** It stands on the image-coding lessons: pixels and the RGB coding 0–255. A learner who knows a colour is three numbers can start here directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **RGB and HSL — colour on screens** — RGB builds every colour by adding red, green and blue light, each 0–255, the coding of the pixel lessons; HSL (in French TSL: teinte, saturation, luminosité) names the same colour by hue around a circle, saturation from grey to vivid, and lightness from black to white — the human description of colour, as numbers.
2. **CMYK — colour in print** — Printing makes colour by subtracting light with inks: cyan, magenta and yellow laid on white paper, plus black ink (K) for true blacks and cheaper dark tones — which is why a screen colour can change when it is printed, and why print work is prepared in CMYK.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Multimedia lessons on pixels, bitmaps and colour depth, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "La photographie numérique", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Describe one colour in RGB terms and say what each of the three numbers drives.
2. Describe the same colour in HSL terms — hue, saturation, lightness — and say what each term means.
3. Explain why printing uses CMYK, including why the black ink K is added.
4. Explain why a colour can look different printed from how it looks on the screen.

## What you need
Paper and a pencil. A computer with an image editor or a colour picker makes the hands-on work direct, but the lesson stands without it.

## The run of the lesson (in order)
1. **Do it first** — Describe the colour of a ripe orange to a friend using only words, then try to give the same colour as numbers — before the lesson shows the three systems. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the hue circle with saturation fading to grey at the centre and a lightness scale beside it, one orange marked on all three — the student places a second colour of their own on the circle and reads off its HSL description
   - ADD IMAGE: a picture of a bright screen image beside its printed version, the neon colours duller in print, with the four cartridges C, M, Y, K below — the student points at the colour that changed most and says why print could not reach it
   - ADD GIF: a GIF of three coloured lights — red, green, blue — sliding over each other, the overlap turning yellow, then white — the student calls out each new colour before the overlap completes
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the hue circle with saturation fading to grey at the centre and a lightness scale beside it, one orange marked on all three → the student places a second colour of their own on the circle and reads off its HSL description
- IMAGE — a picture of a bright screen image beside its printed version, the neon colours duller in print, with the four cartridges C, M, Y, K below → the student points at the colour that changed most and says why print could not reach it
- GIF — a GIF of three coloured lights — red, green, blue — sliding over each other, the overlap turning yellow, then white → the student calls out each new colour before the overlap completes
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Mixes up saturation and lightness → saturation fades a colour towards grey at the same lightness; lightness slides it towards black or white. Thinks CMYK’s K is a spare colour → K exists because CMY overprints make a muddy, costly black; true black ink is sharper and cheaper. Expects print to match the screen exactly → the two models reach different sets of colours; the mismatch is in the physics, not in the printer.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches the TSL system inside its image-coding Cours and the additive/CMYK contrast in its display-and-sharing Cours of the photography theme — this lesson joins those two places into the colour-models lesson the wave’s map called for.
