# Lesson plan — Command-line tools — ipconfig and ping

**Course:** Computer Science and ICT · **Title:** Hardware · **Lesson:** Command-line tools — ipconfig and ping
**Place in the curriculum:** Unit 5 — Maintenance and Troubleshooting (CURRICULUM.md).
**The one thing this lesson teaches:** The Command Prompt's ipconfig shows a host's IP address, subnet mask and default gateway, and ping tests the road to another host: send a datagram, and a working network brings it back.
**This lesson's own level:** It stands on the network troubleshooting steps: these are two of the 'available tools' those steps use. The guide's lab practice (teacher evidence) sends pupils to get their own IP address and network information from the command line.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps — a GIF here is 2 seconds.

## Sub lessons
1. **Opening the prompt — and ipconfig** — the Start-menu search or "cmd" in Run; ipconfig's job and its three address lines; the guide's lab practice (teacher evidence).
2. **ping — send a datagram, get it back** — the datagram out and back; the book's gateway, 192.168.0.1.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Steps 2–6 — test a scenario, fix, verify, document, in this same title. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.

## What the learner can do when it ends
1. Open the Command Prompt from the Start menu or with "cmd".
2. Read IP address, subnet mask and default gateway from ipconfig.
3. Ping the default gateway and interpret the reply.

## What you need
A Windows school computer if available — paper works too. Paper and a pencil.

## The run of the lesson (in order)
1. **Do it first** — the learner attempts the lesson's task from what they already know, then works the lesson and corrects their attempt (lesson/lesson.md).
2. **The explanation** — the parts of lesson/lesson.md in order, keeping the book's step order exactly where the lesson is a doing-lesson.
   - ADD IMAGE [Picture 31317]: a picture of a command window showing an address block — IP address, subnet mask, default gateway — beside a ping packet bouncing back from a gateway — the student reads the three address lines, then follows the packet out and back.
   - ADD GIF [GIF 31335]: a picture of a packet travelling from a computer to its default gateway and the reply travelling back — the student says what a returned packet proves about the network.
   - ADD AUDIO: a voice reading the lesson's key words aloud — Command Prompt, cmd, ipconfig, ping, IP address, subnet mask, default gateway — the student listens once through, then reads the same words aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/ — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 31317] — a picture of a command window showing an address block — IP address, subnet mask, default gateway — beside a ping packet bouncing back from a gateway → the student reads the three address lines, then follows the packet out and back.
- GIF [GIF 31335] — a picture of a packet travelling from a computer to its default gateway and the reply travelling back → the student says what a returned packet proves about the network.
- AUDIO — a voice reading the key words aloud (Command Prompt, cmd, ipconfig, ping, IP address, subnet mask, default gateway) → the student listens, then reads along aloud. (Described slot only; no audio file is made in this build.)
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Types commands on the desktop → commands belong in the Command Prompt; open it first.
- Reads a failed ping as a dead computer → ping tests the ROAD to a host; the host may be fine and the path broken.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
