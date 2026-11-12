# Lesson plan - Type conversion - when Python does it, when you must

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Type conversion - when Python does it, when you must
**Place in the curriculum:** Unit 6 - Fundamentals of Programming (CURRICULUM.md).
**The one thing this lesson teaches:** type conversion changes a value from one type to another: implicit conversion is done by Python itself to avoid losing data, and explicit conversion is done by the programmer with int(), float() and str() - the fix when Python refuses to add a string to an integer.
**This lesson's own level:** it stands on it stands on Python data types - int, float, str, bool: conversion only makes sense once values have types. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on - an image, a GIF, a video, an audio. Every slot is written as **"a picture of ..." in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps - a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order - the list the learner sees from the start, locked ahead, each opening when the one before it is proved (the gate: README, "Units, Lessons and Sub Lessons (ruled 2026-11-08)"):

1. **Implicit conversion - Python does it itself** - Implicit conversion is done by Python itself, without the programmer, to avoid losing data - adding an int to a float yields a float, because forcing the result into int would lose part of it.
2. **Explicit conversion - you do it, with int(), float(), str()** - Explicit conversion is done by the programmer with the built-in functions named for the target type: int(), float(), str().
3. **The clash and its fix - a string meets an integer (doing)** - Python refuses to add a string to an integer and shows an error; the fix is to explicitly convert the string's value to int before adding. Worked end to end in the lesson.

Gate pool: all questions of the sub lesson - no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Recommended first: Python data types - int, float, str, bool. Recommended, never forced.

## What the learner can do when it ends
1. Say what type conversion is.
2. Explain implicit conversion and why Python does it - to avoid losing data.
3. Convert explicitly with int(), float() and str().
4. Fix the string-plus-integer error by converting the string's value to int before adding.

## What you need
A computer with Python IDLE where one is available; paper and a pencil for every activity away from the machine.

## The run of the lesson (in order)
1. **Do it first** - the learner tries the lesson's opening task before any explanation (lesson/lesson.md).
2. **The explanation** - the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 18113]: a picture of a string and a number colliding with an error, then passing through a converter and adding cleanly - the student the student acts the clash, then the conversion, then the clean add.
   - ADD AUDIO: a voice reading the clash aloud - quote-five plus three: error - then int of quote-five plus three: eight - the student listens, then reads the fix aloud.
3. **Say it to your companion** - explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed - the lesson retold in the super-simple voice (made later, when videos are made).
4. **Questions** - from questions/: multiple-choice, true-or-false, fill-in-the-blank - served at the learner's level (levels.md).
5. **Hands-on** - hands-on.md.
6. **Do It Yourself** - the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 18113] - a string and a number colliding with an error, then passing through a converter and adding cleanly → the student the student acts the clash, then the conversion, then the clean add.
- AUDIO - a voice reading the clash aloud - quote-five plus three: error - then int of quote-five plus three: eight - the student listens, then reads the fix aloud.
- VIDEO - the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot - the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Waits for Python to fix "5" + 3 -> implicit conversion only happens where no data would be lost and the operation makes sense; a string-integer add is refused, so the programmer converts explicitly.
- Converts the wrong side -> convert the STRING's value to int (int("5")) so both sides are numbers; the picture's arrow shows the direction.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 11 Information Technology, Unit 6 - Fundamentals of Programming). A teacher sending this lesson sends the lesson and its question list as they are - choosing, not remaking.
