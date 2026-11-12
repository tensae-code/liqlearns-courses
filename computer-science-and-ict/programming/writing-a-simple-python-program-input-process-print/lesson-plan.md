# Lesson plan - Writing a simple Python program - input, process, print

**Course:** Computer Science and ICT · **Title:** Programming · **Lesson:** Writing a simple Python program - input, process, print
**Place in the curriculum:** Unit 6 - Fundamentals of Programming (CURRICULUM.md).
**The one thing this lesson teaches:** a function is a piece of code that does a task, called by name; a simple program takes input with input() - which always returns a string - processes it, and prints output with print(), as in the circle program that reads a radius, converts it to float, and prints the area and circumference.
**This lesson's own level:** it stands on it stands on everything in the unit - the shell, scripts, variables, types and conversion meet in one working program. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the exact places marked below, the lesson page carries an add-on - an image, a GIF, a video, an audio. Every slot is written as **"a picture of ..." in words, plus one little line saying what the student does with it**. The words carry the picture while the course is built and while the AI learns from the books; on the website the real add-on is dropped into that slot and the little explanation stays as the student's guide. GIFs come first where a thing must be shown moving or in steps - a GIF here is 2 seconds.

## Sub lessons
The parts of this lesson, in order - the list the learner sees from the start, locked ahead, each opening when the one before it is proved (the gate: README, "Units, Lessons and Sub Lessons (ruled 2026-11-08)"):

1. **Functions, input() and print()** - A function is a piece of code that does a task, called by name, taking input data and optionally returning output. print() displays any expression's value, and several comma-separated values print on one line; input() shows its prompt string, waits for typing and Enter, and returns what was typed always as a string.
2. **The circle program - separate lines (doing)** - Read a circle's radius, convert it to float, and print the area and circumference - first on separate lines. Run with radius 3: area 28.26, circumference 18.84.
3. **The same answers on one line each (doing)** - The combined form: label and value together on one line each, using comma-separated values in print(). The guide's model solutions for the closing practice - product of two numbers, BMI from weight and height - are filed as verified expected outputs.

Gate pool: all questions of the sub lesson - no hardness ranking is written in questions/, so the sub lesson's whole question set is the gate pool.

## Before this lesson
- Recommended first: Recommended first: Statements and expressions - telling them apart, and Type conversion. Recommended, never forced.

## What the learner can do when it ends
1. Say what a function is, in the book's words.
2. Describe what input() does - prompt, wait, Enter, and always a string back.
3. Write the circle program: read a radius, convert to float, print area and circumference.
4. Print several comma-separated values on one line - area and circumference each on a single combined line.

## What you need
A computer with Python IDLE where one is available; paper and a pencil for every activity away from the machine.

## The run of the lesson (in order)
1. **Do it first** - the learner tries the lesson's opening task before any explanation (lesson/lesson.md).
2. **The explanation** - the parts below, in order (lesson/lesson.md).
   - ADD IMAGE [Picture 18115]: a picture of the circle program as a three-stage flow - a typed radius in, the maths in the middle, area and circumference out - the student the student traces one run through the three stages.
   - ADD GIF [GIF 18116]: a picture of typing a radius at the prompt and the two answers printing - the student the student says what the program is waiting for, then reads the two answers as they print.
   - ADD AUDIO: a voice reading one full run aloud - prompt, typed three, area twenty-eight point two six, circumference eighteen point eight four - the student listens, then reads a run aloud the same way.
3. **Say it to your companion** - explain the lesson back in your own words (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed - the lesson retold in the super-simple voice (made later, when videos are made).
4. **Questions** - from questions/: multiple-choice, true-or-false, fill-in-the-blank - served at the learner's level (levels.md).
5. **Hands-on** - hands-on.md.
6. **Do It Yourself** - the doing block at the end of lesson/lesson.md.

## Add-ons for this lesson (the full list)
- IMAGE [Picture 18115] - the circle program as a three-stage flow - a typed radius in, the maths in the middle, area and circumference out → the student the student traces one run through the three stages.
- GIF [GIF 18116] - typing a radius at the prompt and the two answers printing → the student the student says what the program is waiting for, then reads the two answers as they print.
- AUDIO - a voice reading one full run aloud - prompt, typed three, area twenty-eight point two six, circumference eighteen point eight four - the student listens, then reads a run aloud the same way.
- VIDEO - the video-script filmed (made later) → the student watches and follows along.

A slot the builder cannot fill yet stays in the plan as a slot - the plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Does maths on input() directly -> input() always returns a string; convert with float() (or int()) inside the input line, as the worked program does.
- Prints the label and value on separate lines when one line was wanted -> comma-separated values inside one print() call land on one line: print("Area:", area).

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Ethiopia, Grade 11 Information Technology, Unit 6 - Fundamentals of Programming). A teacher sending this lesson sends the lesson and its question list as they are - choosing, not remaking.
