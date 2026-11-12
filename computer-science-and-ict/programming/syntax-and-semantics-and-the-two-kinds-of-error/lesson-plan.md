# Lesson plan - Syntax and semantics - and the two kinds of error

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Syntax and semantics - and the two kinds of error
**Place in the curriculum:** Unit 6 - Fundamentals of Programming (CURRICULUM.md).
**The one thing this lesson teaches:** syntax is a language's rules and semantics is meaning; breaking a syntax rule gives a syntax error the translator reports, while a logic error runs quietly and gives a wrong answer.
**This lesson's own level:** it stands on it stands on High-level languages - compilers and interpreters: the translators of that lesson are the ones that catch, or miss, this lesson's two errors.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on - an image, a GIF, a video, an audio. Every slot is written as **"a picture of ..." in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps - a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order - the list the learner sees from the start, locked ahead, each opening when the one before it is proved (the gate: README, "Units, Lessons and Sub Lessons (ruled 2026-11-08)"):

1. **Syntax - the rules of the language** - Syntax is the rules of a programming language - the structure or grammar programs must strictly follow.
2. **Semantics - the meaning** - Semantics is the meaning of a program's elements and what they do.
3. **Syntax errors - the translator stops you** - Breaking a syntax rule makes the compiler or interpreter produce an error message: a syntax error.
4. **Logic errors - the quiet wrong answer (teacher guide - evidence)** - A syntax-perfect program can run and still do the wrong thing: a logic error, tied to semantics, which no translator catches - far harder to find and fix. The guide adds why: translators point to a syntax error's kind and place, but a logic error lets the program run as if nothing were wrong, so only a human watching the behaviour notices.

Gate pool: all questions of the sub lesson - no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Recommended first: High-level languages - compilers and interpreters. Recommended, never forced.

## What the learner can do when it ends
1. Say what syntax and semantics each mean.
2. Say what a syntax error is and who reports it.
3. Say what a logic error is, and why no translator catches it.
4. Explain why a logic error is far harder to find and fix - including the teacher guide's reason.

## What you need
A computer with Python IDLE where one is available; paper and a pencil for every activity away from the machine.

## The run of the lesson (in order)
1. **Do it first** - the learner tries the lesson's opening task before any explanation (lesson/lesson.md).
2. **The explanation** - the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 18103]: a picture of two programs - one stopped by a red syntax flag, one running happily with a wrong answer circled - the student the student points at each program and names its error kind.
   - ADD AUDIO: a voice reading this lesson's key words aloud - syntax, semantics, syntax error, logic error - the student listens, then says each word and what it means.
3. **Say it to your companion** - explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed - the lesson retold in the super-simple voice (made later, when videos are made).
4. **Questions** - from questions/: multiple-choice, true-or-false, fill-in-the-blank - served at the learner's level (levels.md).
5. **Hands-on** - hands-on.md.
6. **Do It Yourself** - the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 18103] - two programs - one stopped by a red syntax flag, one running happily with a wrong answer circled → the student the student points at each program and names its error kind.
- AUDIO - a voice reading this lesson's key words aloud - syntax, semantics, syntax error, logic error - the student listens, then says each word and what it means.
- VIDEO - the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot - the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Calls every error a syntax error -> ask: did the translator announce it, or did the program run? Announced = syntax; ran-but-wrong = logic.
- Thinks a running program must be correct -> running only proves the building obeyed the rules; the meaning can still be wrong - the wrong-formula circle is the standing example.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 11 Information Technology, Unit 6 - Fundamentals of Programming). A teacher sending this lesson sends the lesson and its question list as they are - choosing, not remaking.
