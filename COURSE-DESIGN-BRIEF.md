# LiqLearns Courses — the full design, in the founder's words and decisions

LiqLearns is a learning platform for all ages. Its courses are built from a
library of official government school textbooks collected from every country
in the world (nursery through Grade 12/13, all subjects). The founder is
Tensae. Everything below is his design — decided by him, not invented by an
assistant.

## The source rule

- The AI that builds the courses starts EMPTY. It knows nothing except what
  is in these textbooks. Everything it teaches comes from the books only.
- Courses are built ONLY from countries that are FINISHED in the library —
  every book of that country found AND uploaded. When a new country
  finishes, its books merge into the courses and the counts grow.
- The books themselves are NEVER given out. No textbook downloads on the
  website, not even government books (legal safety). Learners get the
  courses built from the books. The site may say the library exists and the
  courses are made from it — nothing more.
- Books are read ONE AT A TIME. A book is fully read and everything basic in
  it filed into its lesson before the next book starts. One file per book.

## How a course is organized

- ONE course per subject, from ALL countries together. Chemistry from every
  country is one Chemistry course. Same for Biology, Mathematics, English,
  and every other subject.
- Inside a subject: TITLE → SUBTITLE → LESSON.
  - A TITLE is a big part of the subject, named by what the thing IS — the
    common-sense name most countries use: Conversation, Alphabet, Words,
    Sentence, Paragraph, Letter. Never a book's unit name, never a story or
    character name. The title must be the BIG true name: "Greetings" was too
    small — hi, how-are-you, introducing yourself, asking age are all
    CONVERSATION, so the title is Conversation.
  - A SUBTITLE is one kind under the title (under Words: nouns, verbs,
    adjectives, adverbs, pronouns).
  - Each subtitle folder holds ONE lesson that teaches ONE thing only. If a
    book unit teaches several things, they split into several lessons.
    Depth INSIDE the one thing stays in that lesson (pronouns carry he, she,
    I, you, it, we, they and all their forms). A different thing BESIDE it
    gets its own lesson. Related lessons point at each other; they never
    merge.
- Every course gets a CURRICULUM file: the plan for the WHOLE course — one
  school year, four terms, each term a level, units inside terms, lessons in
  the order they should be taken. Terms are not sealed boxes: each term is
  the BASE for the next (Term 1 → 2 → 3 → 4); the terms fix order and what
  depends on what.
- Every lesson gets a LESSON PLAN file: the plan for that ONE lesson — its
  one thing, its place in the curriculum, what the learner can do at the
  end, the run of the lesson in order, and ADD-ON SLOTS: at the exact places
  they belong, a line like "a picture of …" written in words, plus one
  little line saying what the student does with it. On the website the real
  image/GIF/video/audio is dropped into the slot and the little line stays
  as the student's guide.
- English ladder, from the bottom: Letter → Word → Sentence → Paragraph →
  Essay → Story → Novel. Reading comes before greetings; the youngest books
  (kindergarten) come first.
- PENCIL AND LINES is its own normal course — holding a pencil, drawing and
  understanding lines — and it stands as the recommended prerequisite
  before EVERY language course, because words are written: the hand learns
  first.

## How a lesson is built (the merge)

- A lesson pulls EVERYTHING every book says about that one thing, from all
  finished countries, and merges it into one lesson. NOTHING is cut.
- Parts that say the SAME thing are held ONCE — a repeat by ten countries is
  a repeat, not ten lessons. Parts that say it DIFFERENTLY are all kept, as
  examples. Parts only one book has are kept.
- Folding keeps the BEST version: the easiest wording AND the most detail.
  If one book says "it takes sunlight," another "the light of sunlight,"
  another "it takes DIRECT sunlight," the folded part keeps the easy words
  and the deeper detail. Surface-same is never a reason to drop a variant's
  extra depth.
- Every part keeps its SOURCE TAG: country + book + page. A learner can ask
  "Where does this come from?" and the lesson shows a picture of the actual
  textbook page, inside the lesson. A shown page is proof, not a download.
- Each book's own title stays as a searchable tag in its own language, so a
  learner can find their own country's book inside a lesson.
- ACCEPTANCE POINTS: every part carries a number = how many countries teach
  it ("taught in 140 countries"). The more countries teach it, the more
  accepted it is. Learners can see this number — it is the proof behind the
  learning.

## How a lesson teaches

- The rule of the house: "You do it, we guide you." The lesson first prompts
  the learner to DO the thing, then explains. The tutor guides; it never
  just performs. Every lesson ends in a real experience — something to do
  with your hands.
- The written lesson sounds like a tutor explaining OUT LOUD — read-aloud
  ready, so a teacher can read it and they ARE explaining it. The writing
  forms pictures in the mind: concrete scenes you can see, not abstract
  statements.
- THE EXPLAIN COMPANION: when a learner registers, they pick or make
  something to explain things TO (a pillow, a cardboard character). Lessons
  prompt them to read aloud and explain it to their companion — explaining
  is how you understand it more.
- LESSONS ARE LEVELED TOO: one lesson in layers, not many lessons. Level 1
  is the simplest explanation. Each level up opens more of the same lesson —
  more of what the books say, more examples, the why under it. Nothing is
  cut; the learner's level decides how deep they go.
- Levels mean DEPTH (simple → advanced), NOT school grades. Depth is set by
  how many countries explain a part and where they place it.
- When books disagree: show both sides, show the split as numbers, and tell
  the learner to ask their teacher or parents.
- History lessons are told like a story.
- Prerequisites are a recommended "start here instead" path — never forced.
  A learner can open just the one part they need and jump straight in.
- TEACHING DIALS — the learner chooses how they are taught when they build
  a course: Explanation: none / small / detailed. Questions: none / light /
  heavy. Question hardness: easy / hard. Named mixes include: Revise it,
  Questions only, Heavy on questions low on lessons, Hard questions small
  explanation, Detailed explanation easy questions.
- The platform's narrator is an AI narrator built INSIDE the platform: it
  explains what is on screen and the learner clicks Next through the parts
  of a lesson.

## Questions

- Questions live in SEPARATE FILES BY TYPE — one file for multiple-choice,
  one for short-answer, one for fill-in-the-blank, one for true-or-false,
  one for matching, and so on. Types are never mixed in one file, so a
  teacher, a battle, or a learner can pull exactly the type they want.
  Inside each file, questions are grouped by level.
- QUESTION HARDNESS IS A LIVING NUMBER: every question's hardness is counted
  from EVERYONE who ever answered it, and it moves both ways forever — a
  question can be re-marked harder or easier at any time as the crowd
  grows, like IQ. When a question's hardness moves, the scores of people
  who answered it before are RE-BASED against the new hardness (re-scored
  on a rhythm, e.g. nightly, never flickering live). A hardness from few
  answers is marked PROVISIONAL.
- TEACHER SEND: a teacher picks a lesson and finds its question list
  waiting. They can use the questions as they are or select certain ones,
  then send to the whole class in one tap. Teachers never remake or reread
  everything.

## Skill numbers and battles

- Every learner has a SKILL NUMBER per SMALL PART (e.g. single-digit
  adding). Topic, subject, and course numbers are just the parts added up.
  A new part borrows its starting number from its bigger topic, then fixes
  itself with the learner's own answers.
- Next to the number sits a hidden HOW-SURE value. Few answers = not sure
  yet. Matching uses the careful, low reading until the system is sure, so
  a lucky streak can't throw a learner against a much stronger player.
- BATTLES: friends play the SAME GAME, not the same questions. Each player
  gets questions at their own level; points are weighed by question
  hardness. A battle moves ratings only a little; learning sessions move
  them more.
- Speed gives only a SMALL bonus, measured against that question's normal
  speed. Answering faster than a person could read the question counts as
  a guess, not knowledge.
- CORNER-WATCHING: the system tracks which corners of a part a learner has
  and hasn't been tested on. Before a part's number may go high, the
  untested corners get served in normal sessions.
- The system always serves a little ABOVE the learner's number. A wrong
  answer on a part the learner was never taught is not a failure — it
  routes them to learn that part first.
- COLD START: there is NO base country. A new part's value is seeded from
  the pattern ACROSS countries: if a part sits in Grade 1 in country after
  country, it's a low-level part; if it sits in the big grades, it's deeper
  and carries more. The same topic can live at several levels. All seeded
  values are provisional and get fixed as real learners come in.

## The three kinds of courses

1. LEVEL courses — the same facts everywhere: mathematics, biology,
   chemistry, physics.
2. SKILL courses — global skills you practice: health and fitness, computer
   skills, language skills (reading, writing, grammar), music basics.
3. NO-LEVEL country courses — culture-shaped, different by country:
   history, civics, religion, a country's own literature and stories.

- INSIDE a no-level course, the learner chooses: "As in your textbook"
  (their own country's version) · their picked countries' versions · "The
  World" — the same part learned from EVERY country (bigger, and earns
  more). Nobody is ranked against another country's version.
- PICTURE RULE: pictures must be REAL — real photographs, or real art from
  that time (paintings, museum pieces). Never a drawing made just to
  explain the lesson.
- MY COUNTRIES: a learner picks the countries they want their books from
  (one, or three or four — e.g. a country they want a scholarship in).
  They see courses built only from those countries' books, and any subject
  those countries require that they don't have gets ADDED to their path.
- MIXED SUBJECTS (proposed by the assistant, awaiting the founder's final
  ruling): don't classify whole subjects — classify TITLES. In Geography,
  physical geography (rivers, climate, maps) is leveled science; human
  geography (your country's regions and resources) is country-shaped. Each
  part goes where IT belongs inside one course.
- RELIGION: versions are done SEPARATELY — Coptic, Orthodox, Protestant,
  Catholic, and every other version gets its own course version, and
  EVERYTHING is taken in, nothing excluded. The religion work itself is
  deferred to later, with its own research pass first.
- VALUES: the platform teaches what each country's books teach and what
  learners want to learn. The founder's personal beliefs do not gate the
  content — his words: "if people want to know, who am I to say no… I'm a
  businessman at the end of the day."

## Building your own course

- CREATE A COURSE: from their dashboard, a learner builds a personal course
  — e.g. an exam tomorrow: "Chemistry is Unit 2, Biology is Unit 3, from
  my country's textbooks." If the book is on the platform they pick the
  units; if not, they search the platform's courses and pick the parts
  themselves. The system assembles the course from those parts.
- Exam courses teach in FULL DETAIL — no slow leveling — because tomorrow
  there is an exam.
- UPLOADS: learners may upload ONLY government textbooks the library is
  MISSING. Not books already held, not private-school books. Uploads are
  the gap-filling channel and get checked like every library book.
- SUBJECT TOOLS are built INSIDE the platform (e.g. for art: a whiteboard
  where you draw with two colors and it shows the color they make). The
  way: study open-source projects, understand how they work, remake it as
  ours. No embedding third-party apps.
- Courses are built first; afterwards they feed the website's AI.

## Where the work stands (October 26, 2026)

- The ENGLISH course is the first course being built; the founder tests the
  system on himself. First source country: EGYPT — its primary books are
  fully read and preparatory reading is under way. LIBYA's books (Grades
  1–12) are fully read and join the sources when Libya's place in the
  finished list is used. LAOS finished in the library on 2026-10-26 and
  now qualifies as a source country.
- The library itself: 46 countries closed (every book found), 16 finished
  (every book uploaded) and counting.
