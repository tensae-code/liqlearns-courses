# Lesson plan — Building a Network Chat System in Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Building a Network Chat System in Python
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 2*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** A network chat system is a server program and client programs joined by a live connection: each client sends its messages to the server, and the server passes every message on to all the other clients — built here in Python with WebSocket, which keeps a two-way connection open so messages arrive the instant they are sent.
**This lesson's own level:** It stands on the email-client lesson (clients, servers, protocols) and on the Python programming lessons. A learner who has built the email client already knows the shape; this lesson makes the conversation live.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **How network chat works — server in the middle** — A chat system has the same two kinds of program as email, arranged differently. The **server** runs in one place and waits. Each user's **client** connects to it and stays connected. When one client sends a message, it goes only to the server; the server then **broadcasts** it — passes it on to every other connected client, whose screens show it at once. The server is the meeting room: nobody talks across the room directly, everything passes through the middle, which is also how the server can keep order, note who is present, and record what was said.
2. **Building it with Python and WebSocket** — Ordinary web requests are one question, one answer, then silence — too slow a rhythm for chat. **WebSocket** is a protocol that opens one connection and keeps it open, so both sides can send at any moment: that is what live chat needs. In Python, a WebSocket library gives the server its shape: accept each client's connection, keep the list of connected clients, and whenever a message arrives from one, loop through the list and send it to all the others. The client program is smaller: connect, then do two jobs at once — listen for arriving messages and show them, and take typed lines and send them. The book's practical runs server and clients on the classroom network until the room is chatting through code the students wrote.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Explain the shape of a chat system: one server, many clients, all messages passing through the server.
2. Say what broadcasting means and why the server does it.
3. Say why chat needs WebSocket's always-open connection rather than one-shot requests.
4. Describe the server program's loop and the client program's two jobs.

## What you need
Computers on one classroom network, with Python and a WebSocket library installed (the teacher sets this up). Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — Email is a letter: you send it and wait. Chat is a conversation: the words appear as they are typed. The difference is the connection — chat keeps it open, talking both ways at once. In this lesson you build that: one server, several clients, messages flying between classroom computers. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of five computers in a ring with one server in the centre, arrows running from each computer only to the centre and back — the student picks one computer, and traces a message from it to the screen of the computer opposite.
   - ADD GIF: a GIF of three chat windows on three screens: a line typed in the first window appearing a moment later in the other two — the student watches once, then says which program — server or client — did the passing-on.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of five computers in a ring with one server in the centre, arrows running from each computer only to the centre and back → the student picks one computer, and traces a message from it to the screen of the computer opposite
- GIF — a GIF of three chat windows on three screens: a line typed in the first window appearing a moment later in the other two → the student watches once, then says which program — server or client — did the passing-on
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks clients send messages straight to each other → trace the arrows: every message visits the server first; that is what lets a late joiner, a record, or a rule exist. Messages appear twice on the sender's own screen → the sender's client both shows the typed line and receives its own broadcast; show it once, by design. Nothing arrives → check in order: is the server running, is the client's address and port right, are the machines on the same network?

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
