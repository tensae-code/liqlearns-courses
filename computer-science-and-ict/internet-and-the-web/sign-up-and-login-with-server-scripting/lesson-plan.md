# Lesson plan — Sign-Up and Login with Server Scripting

**Course:** Computer Science and ICT · **Title:** Internet and the Web · **Lesson:** Sign-Up and Login with Server Scripting
**Place in the curriculum:** ICT expansion — Malaysia (2026-11-14) — in the title Internet and the Web on the ICT course ladder (TITLES.md). Built new from Malaysia's student books (Kementerian Pendidikan Malaysia), because no existing lesson in the course covers this thing as its own lesson — the live tree and live lesson content were checked for the slug and for near matches before building.
**The one thing this lesson teaches:** How sign-up (daftar) and login are built with server scripting — an account record stored on the server at sign-up, and a login that checks the sent name and password against the store (Malaysia, Tingkatan 5)
**This lesson's own level:** It stands on the earlier lessons of its title and on the book's own order — it follows the book's lessons in sequence, so its neighbours in the book are its natural companions. It stands alone for a learner landing on it directly.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **Sign-up — making the account record** — **Sign-up** (daftar) collects the new user's details on a form, **validates** them on the server (present, well-formed, the name **not already taken** — checked by querying the store), and **stores the account** as a record in the server file: name, email, and the password kept for checking. Sign-up is the unit's whole craft in one act: a form, a gate, a stored line. Its answer to the user is one of two — an account made, or the field-by-field reasons it was not.
2. **Login — checking against the store** — **Login** takes a sent name and password and **checks them against the stored record**: the program queries the file for the name, compares the password with the stored one, and on a **match** lets the visitor in **as that user** — the following pages are built for them, their name at the top, their data the one shown. On a **mismatch** the login refuses with one careful message ('name or password not recognised') that does not say **which** part failed — a courtesy to the honest and a wall to the guesser. Malaysia's closing caution belongs to the real world: passwords in this unit's plain text files are a **school model** of the shape; real systems store passwords protected, never readable — the shape is what is taught, and the caution travels with it.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons in Internet and the Web on the ladder. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- Malaysia's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. The details on a form; validated on the server; the account stored as a record
2. Presence; well-formed fields; the name not already taken
3. By querying the store
4. The sent name and password against the stored record

## What you need
Paper and a pencil, and a computer with the program this lesson uses, if available.

## The run of the lesson (in order)
1. **Do it first** — Almost every site asks two things of its visitors: who are you — once, at sign-up — and prove it — every visit, at login. Malaysia's PHP unit builds both. In this lesson you put the unit together: files, validation and queries in one working account system. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of sign-up — making the account record as the lesson describes it — the student studies the picture and names what each part shows.
   - ADD GIF: a GIF of login — checking against the store in action — the student watches once, then says what changed and why.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-false, matching, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of sign-up — making the account record → the student studies the picture and names what each part shows
- GIF — a GIF of login — checking against the store in action → the student watches once, then says what changed and why
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Returns to the one thing this lesson teaches and works it with a smaller example of their own, then tries the stuck part again. Mixes this lesson's tools or terms with a neighbouring lesson's → place the two side by side and name the difference in one sentence each.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
