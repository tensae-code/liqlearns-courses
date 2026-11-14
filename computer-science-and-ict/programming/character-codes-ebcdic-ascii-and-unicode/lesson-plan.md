# Lesson plan — Character Codes — EBCDIC, ASCII and Unicode

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Character Codes — EBCDIC, ASCII and Unicode
**Place in the curriculum:** ICT expansion — Bangladesh (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from Bangladesh's NCTB student books (Bangladesh HSC ICT (Classes XI–XII and Alim)), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** character codes: the three great agreements for writing characters as numbers — EBCDIC of the mainframes, ASCII of the early personal computer, and Unicode (UTF-8, UTF-16, UTF-32) that holds every script, with Bangladesh's own Bangla Unicode table (Bangladesh HSC ICT, Chapter 3, §3.6.2).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **EBCDIC and ASCII — the first two agreements** — **EBCDIC** (Extended Binary Coded Decimal Interchange Code) is the 8-bit code of IBM's mainframe world — 256 characters, its letter order broken into ranges by its punched-card ancestry. **ASCII** is the 7-bit code that won the wider world: 128 characters — control codes, digits, English letters and signs in one clean order (the codes lesson's table). ASCII's limit is written on its face: 128 places cannot hold the world's scripts — not Bangla, not Chinese, not even the accented letters of French.
2. **Unicode — every character, one table; and the Bangla table** — **Unicode** answers by giving **every character of every script its own number** — over a hundred thousand places and growing. Its storage forms trade size for reach: **UTF-8** spends 1–4 bytes per character and rules the web; **UTF-16** spends mostly 2; **UTF-32** spends a fixed 4. The book prints the **Bangla Unicode table** — the block where Bangla's letters live — because for its readers Unicode is not an abstraction: it is the agreement that lets their own language be typed, stored, printed and sent, the agreement the web chapter's charset line declares.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Programming on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Bangladesh's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The 8-bit character code of IBM's mainframe world
2. 128, in 7 bits
3. Control codes, digits, English letters and signs
4. Too few places for the world's scripts

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — The BCD lesson coded digits. Letters, signs and whole alphabets need bigger agreements — and history made three of them, each wider than the last. The third one is the first that can write Bangla, which is why this lesson, of all the codes lessons, is Bangladesh's own. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of ebcdic and ascii — the first two agreements as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of unicode — every character, one table; and the bangla table in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of ebcdic and ascii — the first two agreements → the student studies the picture and names what each part shows
- GIF — a GIF of unicode — every character, one table; and the bangla table in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
