# Lesson plan — Ethernet Frames and How Data Travels

**Course:** Computer Science and ICT · **Title:** Networks · **Lesson:** Ethernet Frames and How Data Travels
**Place in the curriculum:** ICT leftovers — France (2026-11-22) — in the title Networks on the ICT course ladder (TITLES.md). Built new from France's *SNT 2de — Manuel Libre de Sciences numériques et technologie, Seconde* (Les Manuels Libres), because no existing lesson covers this thing as its own lesson — the live tree was checked for the slug and for near matches before building.
**The one thing this lesson teaches:** On a local network, data does not travel naked: it is wrapped in an Ethernet frame — a fixed envelope with a start signal, the MAC addresses of the sender and the receiver, a type label, the data itself, and an error-check tail — and anyone can open a real captured frame and read every field.
**This lesson's own level:** It stands on the idea of a local network and of devices having addresses. The companion lesson on MAC addresses names the physical address; this lesson shows where that address actually rides.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on — an image, a GIF, a video, an audio. Every slot is written as **"a picture of …" in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving — a GIF here is 1–2 seconds.

## Sub lessons
The parts of this lesson, in order — the list the learner sees from the start, locked ahead, each opening when the one before it is proved:

1. **The parts of an Ethernet frame** — The frame in order: the preamble that wakes the receivers up and synchronises them; the destination MAC address; the source MAC address; the type field that says what kind of data is inside (for example an IP packet); the data itself; and the frame check sequence at the end, a calculated tail the receiver recomputes to catch errors.
2. **Decoding a real frame from a capture** — Taking a frame captured with Wireshark and reading it field by field: splitting the hexadecimal into bytes, reading the two MAC addresses, identifying the type, finding where the carried data begins and ends, and saying what the check tail will do at the receiver.

Gate pool: all questions of the sub lesson — no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: the Networks lessons on MAC addresses and on protocols, in this course. Recommended, never forced — a learner may land on this lesson directly, and it stands alone.
- France's own way is kept: the SNT book teaches this inside its theme "Internet", in the order the rows in lesson/sources.md name, with the book's own examples.

## What the learner can do when it ends
1. Name the fields of an Ethernet frame in their order and say what each field is for.
2. Read the destination and source MAC addresses out of a captured frame written in hexadecimal.
3. Say what the type field announces and where the carried data begins and ends in a frame.
4. Explain what the frame check sequence does and what happens when it does not match.

## What you need
Paper and a pencil, and the printed frame from the lesson. If a computer with Wireshark is available, the hands-on work uses it; the lesson stands without it.

## The run of the lesson (in order)
1. **Do it first** — Look at the printed capture of one real Ethernet frame in the lesson and try to guess, before any explanation, which part says where the frame is going. (lesson/lesson.md).
2. **The explanation** — the lesson text in lesson/lesson.md, in its parts in order.
   - ADD IMAGE: a picture of one Ethernet frame drawn as a long envelope cut into labelled boxes — preamble, destination MAC, source MAC, type, data, check sequence — the student points at each box and says what that field is for
   - ADD GIF: a GIF of a frame travelling along a cable while its fields light up one by one in order — the student names each field as it lights up, then pauses the GIF and names the next field before it lights
   - ADD IMAGE: a picture of a Wireshark capture line with the bytes coloured in blocks matched to their fields — the student covers the labels and decodes the blocks alone, then uncovers to check
   - ADD AUDIO: a voice reading the lesson's key names and definitions aloud, in the order the lesson gives them — the student listens once through, then reads the same lines aloud along with the voice. (Audio is a described slot in this build; no audio file is made.)
3. **Say it to your companion** — the companion block in lesson/lesson.md.
   - ADD VIDEO: the script in video-script.md, filmed — the lesson in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, true-or-false, fill-in-the-blank, short-answer — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE — a picture of one Ethernet frame drawn as a long envelope cut into labelled boxes — preamble, destination MAC, source MAC, type, data, check sequence → the student points at each box and says what that field is for
- GIF — a GIF of a frame travelling along a cable while its fields light up one by one in order → the student names each field as it lights up, then pauses the GIF and names the next field before it lights
- IMAGE — a picture of a Wireshark capture line with the bytes coloured in blocks matched to their fields → the student covers the labels and decodes the blocks alone, then uncovers to check
- AUDIO — the key names and definitions read aloud (described slot only; no audio file is made in this build) → the student listens, then reads along aloud.
- VIDEO — the video-script filmed (made later) → the student follows the lesson in the super-simple voice.

A slot the builder cannot fill yet stays in the plan as a slot — the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
Loses count in the hexadecimal → group the bytes in pairs first and number the pairs; the fields are counted in bytes, never in single digits. Confuses MAC and IP addresses → the MAC addresses are the envelope's own addresses, read by the local network; the IP addresses live inside the carried packet. Thinks the check bytes are data → they are calculated from the frame, and the lesson's last field is always the check.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and section in lesson/sources.md. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking. France's SNT book teaches this inside its Internet theme, from a real Wireshark capture in the Activités strand — the frame in this lesson follows that activity's own decoding order.
