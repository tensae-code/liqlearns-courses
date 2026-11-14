# Lesson plan — Memory Addressing — How Data Sits at Addresses

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Memory Addressing — How Data Sits at Addresses
**Place in the curriculum:** ICT expansion — Indonesia (2026-11-14) — in the title Hardware on the ICT course ladder (TITLES.md). Built new from Indonesia's Informatika books (Indonesia Grade 8 G8 Informatika student), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** memory addressing — data lives in memory at numbered addresses, and the processor finds every value by its address, the way a letter is found by the address on its envelope (Indonesia Grade 8).
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Every value has an address** — Memory is not a heap but a street: a long row of storage places, each with a number — its **address** (pengalamatan memori). When a value is stored, it is placed **at an address**; when the processor needs it, the address is what it asks for. Indonesia's Grade 8 book introduces addressing inside the computer-system chapter because it explains the machine's most basic miracle — finding one exact value among billions — with a picture any pupil knows: the letter is found not by searching the city, but by the address written on it.
2. **Physical addresses — and why programs care** — The addresses of the machine's own street are **physical addresses**: the real places in the memory hardware. Programs are written as if data simply has names — the variable's name in the program is the programmer's address for the same place — and the system joins name to physical address behind the scenes. Addressing also sets memory's measure: the number of addresses a processor can name limits how much memory it can use, which is why 'how much memory can this machine address?' is a real specification and not a slogan.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Hardware on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Indonesia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The number of a storage place in memory's long row
2. By its address — as a letter is found by the address on its envelope
3. It is placed at an address
4. The real places in the memory hardware — the machine's own street

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Memory addressing — data lives in memory at numbered addresses, and the processor finds every value by its address, the way a letter is found by the address on its envelope (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of every value has an address as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of physical addresses — and why programs care in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of every value has an address → the student studies the picture and names what each part shows
- GIF — a GIF of physical addresses — and why programs care in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
