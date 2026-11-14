# Lesson plan — Creating an Application or Applet

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Creating an Application or Applet
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How an application or an applet is created in Java — the two shapes a finished Java program takes: a standalone application with a main method, and an applet made to run inside a web page (Malaysia, Tingkatan 4, NetBeans)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The application — a program that stands alone** — A Java **application** is a standalone program: it is started from the computer (in this course, run from NetBeans or the command line) and runs in its own right, opening with its **main method** — public static void main(String[] args) — the door every application enters by. Creating one means building the project, writing its classes with their main method, and running it to its own window or console. Nothing else hosts it: the application carries its own start and its own finish.
2. **The applet — a program that lives in a page** — An **applet** is a Java program made to run **inside a web page**, hosted by the browser: it has **no main method** — instead the browser calls its life-cycle methods (it is initialised, started, painted, stopped) as the page is visited and left. Creating one means writing the applet class and naming it in the page that hosts it. Malaysia teaches the pair as the two deliveries of the SDLC's final work: the same language, the same care — one program stands alone, the other is a guest in a page, and the creator chooses by where the users will meet it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A standalone application, and an applet inside a web page
2. Its main method — public static void main(String[] args)
3. Nothing else — it stands alone, carrying its own start and finish
4. Inside a web page, hosted by the browser

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Malaysia's programming chapter ends by shipping its work: the program becomes an application a user can run — or an applet that lives in a web page. In this lesson you learn the two shapes of a finished Java program, and how each is created. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of the application — a program that stands alone as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the applet — a program that lives in a page in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the application — a program that stands alone → the student studies the picture and names what each part shows
- GIF — a GIF of the applet — a program that lives in a page in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
