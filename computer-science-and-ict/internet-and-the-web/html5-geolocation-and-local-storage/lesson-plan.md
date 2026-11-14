# Lesson plan — HTML5 Geolocation and Local Storage

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** HTML5 Geolocation and Local Storage
**Place in the curriculum:** ICT expansion — North Macedonia (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from North Macedonia's *Informatics* (2026), because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** Modern HTML5 lets a web page ask the browser two new things: where the user is (geolocation — only with the user's permission, giving latitude and longitude) and a place to keep data in the browser itself (local storage — key-and-value pairs that survive closing the page, unlike a single visit's session).
**This lesson's own level:** It stands on the earlier lessons of its title and on the North Macedonia book's own order — it follows the book's sections in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Geolocation — with permission** — **Geolocation** asks the browser for the device's position — **latitude and longitude** — gathered from GPS, Wi-Fi or network signals. The browser **always asks the user first**; refuse, and the page gets nothing. Pages use it for maps, local search and delivery estimates, and a careful page must still work for users who say no.
2. **Local storage — the page remembers** — **Local storage** gives each website a small store **in the browser**: **key–value pairs** of text (a name for each value, like a labelled drawer) saved by the page's code and **still there** after the tab closes and the browser restarts — settings, drafts and preferences live there. Its cousin **session storage** forgets when the tab closes. Storage is per-site: one site cannot read another's drawers.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- North Macedonia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The device's position — latitude and longitude.
2. GPS, Wi-Fi or network signals.
3. Key–value pairs of text.
4. It forgets when the tab closes.

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Pages used to forget you the moment you left and had no idea where you were. This lesson covers the two HTML5 features that changed that — and the permission that guards one of them. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of geolocation — with permission as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of local storage — the page remembers in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of geolocation — with permission → the student studies the picture and names what each part shows
- GIF — a GIF of local storage — the page remembers in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
