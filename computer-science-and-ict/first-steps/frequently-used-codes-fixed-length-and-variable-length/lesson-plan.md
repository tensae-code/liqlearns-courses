# Lesson plan — Frequently Used Codes — Fixed-Length and Variable-Length

**Course:** Computer Science and ICT · **Title:** First Steps · **Lesson:** Frequently Used Codes — Fixed-Length and Variable-Length
**Place in the curriculum:** ICT expansion — Moldova (2026-11-14) — in the title First Steps on the ICT course ladder (TITLES.md). Built new from Moldova's student books (Editura Știința / Educație Digitală, Romanian), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** The codes in everyday use and their two architectures: fixed-length codes giving every character the same number of bits, and variable-length codes giving frequent characters short code words — with binary alphabets and Bacon's code (Moldova Grade 11, Informatică, §2.3).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Fixed-length codes — the same size for every character** — A **fixed-length code** gives **every character the same number of bits**: with n bits per character, 2ⁿ different characters can be coded — 7 bits for the classic **ASCII** (128 characters), 8 bits for its extended byte forms. The architecture's virtue is simplicity: the third character of a text begins exactly at bit 2n — any place can be **found by counting**, and decoding needs no markers. A **binary alphabet** is its alphabet form: a fixed set of symbols per character, as in **Bacon's code**, where each letter is five symbols drawn from two kinds (a/b) — an early binary code in disguise.
2. **Variable-length codes — short words for frequent guests** — A **variable-length code** gives **frequent characters short code words and rare characters long ones**: Morse code is its grandfather — E (the commonest letter) is one dot, Q is a long dash-dash-dot-dash. The average message then takes **fewer bits** than any fixed-length coding of the same alphabet. The price is decoding discipline: code words must be **prefix-free** (no word is the start of another) and the receiver must find the borders — Morse does it with pauses, computer codes with tree-shaped decodings. Compression begins in this section.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in First Steps on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Moldova's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. A code giving every character the same number of bits
2. 2ⁿ — 128 for ASCII's 7 bits
3. Simplicity — any character's place is found by counting
4. Each letter as five symbols from two kinds (a/b) — an early binary code

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Grade 11's information chapter leaves theory for the codes actually used. Some are so familiar they are invisible — and all of them take one of two shapes: the same length for everyone, or short words for the frequent. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of fixed-length codes — the same size for every character as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of variable-length codes — short words for frequent guests in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of fixed-length codes — the same size for every character → the student studies the picture and names what each part shows
- GIF — a GIF of variable-length codes — short words for frequent guests in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
