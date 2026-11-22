# Lesson plan — Data Centres — Where the Cloud Lives

**Course:** Computer Science and ICT · **Title:** New Technologies · **Lesson:** Data Centres — Where the Cloud Lives
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title New Technologies on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The cloud is not a cloud: it is data centres — warehouses of servers running day and night, kept alive by duplicate power supplies and uninterruptible power supplies (UPS), cooled against the heat their own work makes, guarded like banks — and their hunger for electricity is one of the real costs of digital life.
**This lesson's own level:** It stands on the cloud-storage lesson. No technical background is needed; the energy part uses simple multiplication from school mathematics.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Inside a data centre** — Rows of servers in racks, network connections in and out, power arriving by two routes with a UPS — batteries that bridge any cut instantly — and generators behind them; cooling systems carrying away the heat of thousands of machines; physical security: fences, guards, badges, cameras.
2. **The energy cost of data centres** — Every computation and every stored file burns electricity twice — once to run, once to cool — and France’s book has students compute it: a centre’s consumption in kilowatt-hours and its carbon weight, the share of digital technology in energy use, and why sobriety (deleting, choosing, switching off) is part of the topic.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the New Technologies lesson on cloud storage, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Données structurées et leur traitement", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Name what a data centre holds and what its servers do for the cloud.
2. Explain the three life-support systems — power with UPS, cooling, security — and what each protects against.
3. Calculate a simple energy consumption figure from power and time.
4. State one digital sobriety habit and connect it to the data centre’s meter.

## What you need
Paper, a pencil and a calculator for the energy figures.

## The run of the lesson (in order)
1. **Do it first** — List everything that must never stop for a service like a hospital’s records or a bank to stay online at 3 a.m. — before the lesson walks you inside the building that guarantees it. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a data centre aisle with racks of servers and cold and warm air arrows — the student follows one arrow path and says which life-support system it belongs to
   - ADD GIF: a GIF of a power cut striking a building while a UPS battery icon bridges the gap and the servers never blink — the student says what would happen in the seconds before the generator starts, and what covers those seconds
   - ADD IMAGE: a picture of one server, a rack, a hall and a town, each step multiplying the meter beside it — the student works the multiplication for the rack step aloud
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a data centre aisle with racks of servers and cold and warm air arrows → the student follows one arrow path and says which life-support system it belongs to
- GIF — a GIF of a power cut striking a building while a UPS battery icon bridges the gap and the servers never blink → the student says what would happen in the seconds before the generator starts, and what covers those seconds
- IMAGE — a picture of one server, a rack, a hall and a town, each step multiplying the meter beside it → the student works the multiplication for the rack step aloud
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks the cloud floats above physical places → every cloud service runs in a data centre somewhere, with an address and an electricity meter. Confuses UPS with the generator → the UPS is batteries: instant, but brief; the generator is the long-distance runner that starts behind it. Forgets cooling in the energy sum → the heat of computation must be removed by machines that also consume; running is only part of the bill.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France’s SNT book teaches data centres in the Activités of its structured-data theme — equipment, locating centres, and energy calculations in a spreadsheet — and pairs them with digital sobriety; this lesson keeps that pairing.
