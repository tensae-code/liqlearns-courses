# Lesson plan — Calling AI Platform Tools from Python

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Calling AI Platform Tools from Python
**Place in the curriculum:** ICT expansion — China (2026-11-14) — in the title Programming on the ICT course ladder (TITLES.md). Built new from China's *IT Compulsory 1 (Grade 11 record)*, because no existing lesson in the course covers this thing as its own lesson.
**The one thing this lesson teaches:** AI platforms offer ready-made intelligent tools — recognising speech, understanding text, answering questions — that a program can call through an interface: the program sends a request with its data, the platform's tool does the intelligent work, and the program receives the result and uses it — which is how the book's students build a working WeChat chatbot in Python.
**This lesson's own level:** It stands on the Python programming lessons and on the AI lessons of Chapter 4 of Compulsory 1 (what AI is, AI tools on platforms). It is the summit of the volume: everything before it — data, algorithms, Python — is used at once.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **AI platform tools and how a program calls them** — An **AI platform** is a service that gathers trained AI abilities — speech recognition, language understanding, image recognition, question answering — and offers each as a **tool** other programs can use. The program does not contain the AI; it **calls** it through the tool's interface: it packages a **request** (the text to understand, the sound to recognise, plus the key that identifies the caller), sends it to the platform, and receives a **response** carrying the tool's result, which the program then uses like any other value. The pattern is the client's pattern from the email and chat lessons, one level up: your program is the client; the platform's tool is the server; the intelligence lives on the far side of the call.
2. **Building a WeChat chatbot** — The book's practical joins the calls into a working thing: a **chatbot** on WeChat, the messaging app. A Python library for WeChat (the book uses **itchat**) lets the program log in to an account, notice each arriving message, and send replies. The program's loop is small: receive a friend's message → call the platform's intelligent tool with the message text → take the tool's answer → reply with it. To the friend, the account now converses; in truth a few lines of Python are carrying messages back and forth between the friend and the platform's AI. The lesson the practical teaches is the volume's deepest: a programmer's power is not only writing intelligence, but **composing** — joining ready tools with a little code of your own into something new.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the earlier lessons this one stands on, as named in its own level line above. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- China's own way is kept: see the placement and own-way notes in lesson/sources.md.

## What the learner can do when it ends
1. Say what an AI platform tool is, and what a request and a response carry.
2. Explain the pattern: your program is the client, the platform's tool is the server, the intelligence lives across the call.
3. Describe the chatbot loop: receive, call the tool, take the answer, reply.
4. Say what 'composing' means here, and why it multiplies a programmer's power.

## What you need
A computer with Python; the teacher provides the platform account/key and the WeChat test account used in class. Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — You could never write a program that understands spoken Chinese from nothing — that takes years and mountains of data. But a platform has already built that ability and left a door in it: your small program knocks with a request, the giant tool answers. In this lesson your program learns to knock — and builds a chatbot that really talks. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of a small student program at a counter, handing a sealed request envelope across to a vast machine room labelled AI PLATFORM, and receiving a small answer card back — the student points at the envelope and the card and says what each carries.
   - ADD GIF: a GIF of a phone chat: a friend types a question, the message hops to a small Python program, across to a glowing platform, and back as an answer appearing in the chat — the student watches once and names the three stops the message made.
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a small student program at a counter, handing a sealed request envelope across to a vast machine room labelled AI PLATFORM, and receiving a small answer card back → the student points at the envelope and the card and says what each carries
- GIF — a GIF of a phone chat: a friend types a question, the message hops to a small Python program, across to a glowing platform, and back as an answer appearing in the chat → the student watches once and names the three stops the message made
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Thinks the student's program itself understands the messages → it carries them; the understanding happens in the platform's trained tool. The program's own intelligence is the loop: receive, call, reply. Expects the chatbot to answer well about everything → the chatbot is exactly as good as the tool it calls and the requests it sends; composing joins powers, it does not add new ones.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
