# Lesson plan — Maps with Layers — OpenStreetMap and uMap

**Course:** Computer Science and ICT · **Title:** Multimedia · **Lesson:** Maps with Layers — OpenStreetMap and uMap
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Multimedia on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** A modern digital map is not one picture but a stack of layers — base map, roads, relief, satellite view, and your own data — that can be shown or hidden independently; OpenStreetMap is the world map drawn by its users, and with uMap anyone can lay their own points, lines and files (such as a KML track) over it and publish the result.
**This lesson's own level:** It stands on the latitude/longitude lesson. No drawing skill is needed; the maps are assembled, not drawn from nothing.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Modern maps and their layers** — The layer idea (in French, calques): a base layer — drawn map, relief shading, or satellite imagery such as IGN’s data in Géoportail — with thematic layers above it that can be toggled; zooming and panning over data far too large for any sheet, because the machine assembles the view from the layers on demand.
2. **Making and enriching your own map** — OpenStreetMap: the free world map drawn and corrected by its users. uMap: the tool that lets anyone create a personal map over OSM — adding points with descriptions, drawing lines and areas, importing a data file such as a KML flight or voyage track — and share it by link.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Networks lesson on latitude and longitude, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Localisation, cartographie et mobilité", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Explain the layer (calque) idea and name typical base and thematic layers.
2. Choose and justify a layer set for a stated reader and purpose.
3. Describe what OpenStreetMap is and who draws it.
4. Describe the steps to build a uMap with placed points and an imported KML track.

## What you need
Paper for planning; a computer with a browser for uMap and OpenStreetMap work, if available.

## The run of the lesson (in order)
1. **Do it first** — List everything a paper map of your town must squeeze onto one sheet, and what you would rather switch on and off — before the lesson introduces layers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a map exploded into four transparent sheets with tick boxes beside each — the student ticks the sheets for a stated purpose and defends one tick they left empty
   - ADD GIF: a GIF of a map zooming from a whole continent down to one street, the layers rebuilding at each scale — the student names a detail that only appears at the deepest zoom and says which layer carries it
   - ADD IMAGE: a picture of a uMap screen with placed points, one description open, and an imported curved track — the student points at the imported track and says what file it came from
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a map exploded into four transparent sheets with tick boxes beside each → the student ticks the sheets for a stated purpose and defends one tick they left empty
- GIF — a GIF of a map zooming from a whole continent down to one street, the layers rebuilding at each scale → the student names a detail that only appears at the deepest zoom and says which layer carries it
- IMAGE — a picture of a uMap screen with placed points, one description open, and an imported curved track → the student points at the imported track and says what file it came from
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Treats the digital map as one fixed picture → it is assembled from layers on demand; the same data shows differently to different readers by design. Confuses OpenStreetMap with Google Maps → OSM is drawn and corrected by its users and free to reuse; that openness is why uMap can build on it. Imports a track and sees nothing → check the import landed in its own layer, that the layer is switched on, and zoom to the track’s area.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches modern cartography through IGN/Géoportail, OpenStreetMap and Google Maps layers in its Cours, map-making with uMap in a second Cours, and a KML flight import in the Activités — this lesson follows that order.
