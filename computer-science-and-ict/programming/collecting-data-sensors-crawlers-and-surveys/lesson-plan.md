# Lesson plan — Collecting Data — Sensors, Crawlers and Surveys

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Collecting Data — Sensors, Crawlers and Surveys
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Data collection gathers the data a question needs from the world and from people: automatically, with sensors that measure and record on their own; from the web, with a crawler program that visits pages and extracts what matches; and from people directly, with questionnaires and surveys — each route chosen by what the data is and where it lives.
**This lesson's own level:** It stands on the general-process lesson: this is stage one, done properly. The crawler part assumes the Python lessons; the sensor and survey parts need only careful thinking.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Collecting from the world — sensors and records** — Some data is collected by **sensors**: devices that measure a physical quantity — temperature, light, motion, water level — and record it as data, automatically, as often as needed, in places people cannot stay. A weather station, a step counter and a river gauge all work this way: measure, convert to data (digitisation at work), store, repeat. Other data already exists in **records** — registers, receipts, past results — and collection there means gathering and copying what organisations already hold. The shared rule: decide from the question what to collect, how often, and in what units, *before* collecting — data gathered without a plan usually misses the one column the analysis later needs.
2. **Collecting online — web crawlers and questionnaires** — Data that lives on web pages can be collected by a **web crawler**: a program that requests a page, reads its structure, extracts the items that match (with a library such as Python's **BeautifulSoup**, which parses the page's HTML into findable parts), stores them, and moves to the next page — doing in an hour what a person with a clipboard could not do in a month, provided the collection respects the site's rules and the data's owners. Data that lives in people's heads needs the third route: **questionnaires and online surveys** — carefully worded questions, sent to the right people, whose answers return already digital. A good survey question can be answered in one tap and means the same thing to everyone who reads it; a bad one collects noise that no later cleaning can remove.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Name the collection routes: sensors, existing records, web crawlers, questionnaires/surveys — and say what each is for.
2. Describe what a web crawler does, step by step, and what BeautifulSoup does inside it.
3. Say what makes a survey question good, and why a bad one cannot be repaired later.
4. Choose a collection route for a given question and defend the choice.

## What you need
Paper and a pencil. A computer with Python for the crawler demonstration, if available.

## The run of the lesson (in order)
1. **Do it first** — A weather station on the school roof knows the temperature every minute without anyone climbing up. A researcher knows the price of the same phone in fifty online shops without visiting one. A teacher knows what two hundred parents think without two hundred conversations. Three different kinds of knowing — three different ways of collecting. This lesson separates them. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the school roof weather station with a dotted line of readings flowing down into a growing table on a notebook below — the student points at the sensor, then at the table, and says what travels between them and how often.
   - ADD GIF: a GIF of a small spider-shaped program walking a web of pages, dropping each price tag it finds into a basket that becomes a neat table — the student watches once, then says which part BeautifulSoup plays in the walk.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the school roof weather station with a dotted line of readings flowing down into a growing table on a notebook below → the student points at the sensor, then at the table, and says what travels between them and how often
- GIF — a GIF of a small spider-shaped program walking a web of pages, dropping each price tag it finds into a basket that becomes a neat table → the student watches once, then says which part BeautifulSoup plays in the walk
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Chooses a survey for everything → ask where the data lives: in the physical world (sensor), in records, on pages (crawler), or in people's heads (survey). The data's home picks the route. Writes survey questions that can be answered five ways → a collectable question has one meaning and a short list of answers; ambiguity at collection becomes 'dirty data' at cleaning.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
