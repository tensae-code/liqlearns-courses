# Lesson plan — Procedures and Functions in JavaScript

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Procedures and Functions in JavaScript
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How procedures and functions are used in JavaScript — a function is declared once with the function keyword, called by name with arguments, and answers through return (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Declaring and calling** — A JavaScript function is **declared once** — function greet(name) { … } — naming it, listing its **parameters** in brackets, and writing its body in braces. It is **called** wherever its work is needed — greet('Aina'); — with **arguments** handed in for the parameters. In this course's language, a JavaScript function that only **does a job** (shows a message) works as a **procedure**; one that **answers a value** works as a function proper. The declaration sits apart from the calls, so the script's reading order is: definitions gathered, then the story that uses them.
2. **Returning — the function's answer** — A function answers through **return**: return total; ends the function at once and hands the value back to the caller, where it can be stored, printed, or used inside a larger expression — let avg = average(m1, m2);. A function with no return hands back **undefined** — correct for procedures, a silent fault for a function whose answer is then used in a sum. Malaysia's rule from the functions strand holds in JavaScript unchanged: one job per function, a name that says the job, and parameters for everything the job needs from outside — a function that reaches for the page's loose variables instead of its parameters cannot be tested alone, and what cannot be tested alone will be debugged in company.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Once, with the function keyword — name, parameters in brackets, body in braces
2. Arguments, for the parameters
3. A procedure
4. Through return — which ends the function at once and hands the value to the caller

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — A page's script grows: the same checking is needed in three places. Malaysia's JavaScript chapter answers with the course's old friends in new dress — functions. In this lesson you declare, call and answer with JavaScript functions. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of declaring and calling as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of returning — the function's answer in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of declaring and calling → the student studies the picture and names what each part shows
- GIF — a GIF of returning — the function's answer in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
