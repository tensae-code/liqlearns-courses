# Lesson plan — Building a Simple Email Client

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Building a Simple Email Client
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 2*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** An email client is a program that sends mail through a sending (SMTP) server and fetches mail from a receiving (POP3/IMAP) server — and a learner can build a working one in Python: connect, log in, compose the message, send it, then fetch and read what arrived.
**This lesson's own level:** It stands on the programming lessons about Python data types, variables and program structure, and on the networks lessons about clients and servers. The learner should have written small Python programs before it.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **How email travels — servers and protocols** — Email does not fly directly from your computer to your friend's. When you send, your **client** (the program you use) hands the message to a **sending mail server** using the protocol **SMTP** (Simple Mail Transfer Protocol). That server passes it across the internet to the receiver's mail server, where it waits in the receiver's mailbox. When your friend's client collects mail, it asks that server with a receiving protocol — **POP3**, which downloads the messages, or **IMAP**, which reads them while they stay on the server. Two errands, two protocols: SMTP pushes mail out; POP3 or IMAP pulls mail in.
2. **Building the client in Python** — Python's standard library carries the tools. The **`smtplib`** module speaks SMTP: the program connects to the sending server, logs in with the account name and password, builds the message — sender, receiver, subject and body — as one text (the `email` module helps format it), and calls the send method. Receiving uses **`poplib`** for POP3: connect, log in, count the waiting messages, fetch one by its number, and print its text. The book's practical builds exactly this: a small client that first sends a real message, then fetches and shows a real one — the moment the program works, the protocols of the first sub lesson stop being theory.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Describe the journey of an email: client, sending server, receiver's server and mailbox, receiving client.
2. Say what SMTP does, and what POP3 and IMAP do, and how POP3 and IMAP differ.
3. Name the Python modules for sending and fetching mail, and the steps each program follows.
4. Build (or walk through line by line) a simple client that sends one real message and fetches one.

## What you need
A computer with Python installed, and a test email account the teacher provides. Paper and a pencil for the journey sketch.

## The run of the lesson (in order)
1. **Do it first** — Every day you tap 'send' and trust the mail app. But the app is only a program doing errands: it carries your letter to a sending server, and later knocks on a receiving server to collect replies. In this lesson you build that errand-runner yourself, in Python — small, simple, and really working. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a letter's journey drawn as four stops — your computer, a sending server, the receiver's server with a mailbox, your friend's computer — with the labels SMTP on the way out and POP3/IMAP on the way in — the student traces the journey with a finger and says which protocol works at each hop.
   - ADD GIF: a GIF of a short Python program running: a 'message sent' line appearing, then an inbox count, then the text of a fetched message printing — the student watches once, then names the two library modules that did the two errands.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a letter's journey drawn as four stops — your computer, a sending server, the receiver's server with a mailbox, your friend's computer — with the labels SMTP on the way out and POP3/IMAP on the way in → the student traces the journey with a finger and says which protocol works at each hop
- GIF — a GIF of a short Python program running: a 'message sent' line appearing, then an inbox count, then the text of a fetched message printing → the student watches once, then names the two library modules that did the two errands
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Confuses SMTP with the receiving protocols → SMTP pushes out (S for Send), POP3/IMAP pull in. Thinks mail travels computer-to-computer directly → draw the four stops; servers hold mail so a switched-off receiver loses nothing. Login fails in the practical → check the server address and port for the protocol being used before touching the code.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
