# Lesson plan — Showing Bangla on a Web Page — Charset and Language

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Showing Bangla on a Web Page — Charset and Language
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** showing Bangla on a web page: the meta charset declaration that tells the browser the page is UTF-8, and the lang attribute that names its language — Bangladesh's own worked example in the HSC web chapter (Chapter 4, §4.2, printed p. 135).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Meta charset — declare UTF-8** — Characters travel as numbers (the character-codes lesson), and the browser must be told which code table the numbers use. The declaration lives in the head: **<meta charset="utf-8">** — 'this page is encoded in UTF-8', the Unicode form that holds Bangla and every other script. With it, the page's bytes are read as meant; without it, the browser guesses, and guesses fail exactly on the scripts that need the declaration most. The charset line goes first in the head, before anything it must protect.
2. **The lang attribute — name the language** — The page's other declaration names its **language**: the **lang attribute** on the html element — `<html lang="bn">` for a Bangla page. Lang does quiet, essential work: screen readers pronounce by it, search engines file the page under its language, browsers offer translation and choose fonts and hyphenation by it. Together the two declarations are the page's passport: charset says how its letters are coded, lang says what language they speak — and a page that carries both can travel the whole web and be read as written, in Dhaka or anywhere.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The character encoding the page uses
2. <meta charset="utf-8">
3. First in the head
4. The browser guesses the code — and Bangla arrives as boxes

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Write a web page in Bangla, open it, and the letters arrive as boxes and question marks — the text was fine; the browser guessed its code wrongly. One line in the page's head ends the guessing forever. For a Bangladeshi learner this is not a foreign example: it is the line that puts their own language on the web. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of meta charset — declare utf-8 as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of the lang attribute — name the language in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of meta charset — declare utf-8 → the student studies the picture and names what each part shows
- GIF — a GIF of the lang attribute — name the language in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
