# Lesson plan — Simulating Logic Gates in VB.NET

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Simulating Logic Gates in VB.NET
**Place in the curriculum:** ICT expansion — Egypt (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Egypt's student books (Egypt Ministry of Education and Technical Education / Ministry of Education), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A small program that behaves as the gate behaves — inputs set, logic applied, output shown.
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The simulation idea — inputs in, lamp out** — A **gate simulation** is a small program that behaves as the gate behaves: the user sets the **inputs** (switches, check boxes, buttons — 0s and 1s made clickable), the program applies the gate's **logic**, and an **output** — a lamp, a label, a colour — shows the result. Building it in **VB.NET** means building a form: controls placed for the two inputs and the output, and code behind the controls that recomputes the output whenever an input changes. The simulation's teaching power is its honesty: set the inputs to every row of the gate's truth table and the program must agree with the table every time — the table becomes a test the program can fail.
2. **AND, then OR, then NOT — one project, three logics** — Egypt builds the project **three times**, once per gate, and the repetition is the method. For **AND**, the output code demands both inputs; for **OR**, either suffices; for **NOT**, the single input is inverted. Everything else — the form, the switches, the lamp, the event code that refreshes the output — stays the same, so the pupil sees the **one line that is the gate** standing out from the machinery around it. By the third build the pattern is owned: a new gate would need a new line and nothing else. The project then mirrors the whole thing in PHP — the same logic wearing a web page — and closes by spending the gates on life decisions.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Egypt's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A small program that behaves as the gate behaves — inputs set, logic applied, output shown.
2. Inputs as switches or similar controls; the output as a lamp, label or colour.
3. Only the gate's logic — the form, switches, lamp and refresh machinery stay the same.
4. The output is on only when both inputs are on.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Egypt's Grade 12 programming project takes each logic gate three times: the gate itself, then a simulation program of it in Visual Basic .NET, then the same in PHP. This lesson is the VB.NET telling — one project per gate, rebuilt as the gates change, so the pupil's program grows exactly as their logic does. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the simulation idea — inputs in, lamp out as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of and, then or, then not — one project, three logics in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the simulation idea — inputs in, lamp out → the student studies the picture and names what each part shows
- GIF — a GIF of and, then or, then not — one project, three logics in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
