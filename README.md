# LiqLearns Courses

Courses built from the textbook library (the government books collected from every country).

**The books are never given out.** The website offers no textbook downloads —
not even government books (Tensae's decision, 2026-10-24: he does not want
the legal trouble). The books are the source he learns from; what learners
get is the courses built from them. The site may say the library exists and
that the courses are made from it — nothing more.

## How this is organized

```
liqlearns-courses/
  <subject>/                     ← ONE course per subject. Chemistry from every
                                   country together is one course. Same for
                                   Biology, Mathematics, and every other subject.
    <title>/                     ← a big part of the subject. The name is the one
                                   most countries use for that part.
      <lesson>/                  ← one lesson (example: photosynthesis)
        lesson/                  ← the lesson itself: the teaching text
          lesson.md
          sources.md             ← which books, from which countries, this
                                   lesson was built from — so anyone (or the AI)
                                   can trace every lesson back to its books
        questions/               ← questions for this lesson only. Split TWO
                                   ways: by TYPE (one file per type, below)
                                   and by the way a person likes to learn.
          multiple-choice.md     ← choice questions only — pick the right
                                   answer from the options given.
          short-answer.md        ← short-answer questions only — the learner
                                   answers in a word or a short sentence.
          fill-in-the-blank.md   ← fill questions only — a sentence with a
                                   space, the learner puts the missing word.
          true-or-false.md       ← true-or-false questions only.
          matching.md            ← matching questions only — join the two
                                   sides that go together.
          (more type files the same way — one file per type, e.g.
          writing.md, ordering.md — a type file is created only when the
          lesson actually has questions of that type. Question types are
          never mixed inside one file. Inside each type file, questions
          are grouped by level, tied to the learner's skill number.)
          levels.md              ← practice sessions by level, tied to the
                                   learner's skill number (starts at 100 and
                                   moves as they learn). Example for maths:
                                   single-digit level, then double-digit level.
          video-script.md        ← a script written as simple as possible,
                                   like explaining to a grade-one child, ready
                                   to hand to a video AI later. We write and
                                   save these now; videos get made when there
                                   is budget for it.
          hands-on.md            ← projects and real things to do with your
                                   hands, so the learner understands by doing.
```

## Rules (Tensae's design — do not change without his word)

- The AI that builds these starts EMPTY. Everything it knows comes from the
  collected books only.
- A lesson is built from ALL the books that cover that thing, merged into one
  smallest lesson. NOTHING is cut: when books explain it differently, every
  explanation stays, as examples. A thing only one book has (like a traditional
  song) stays too.
- HOW THE MERGE WORKS (2026-10-24): compare every country's explanation of
  the part. The parts that say the SAME thing are held ONCE — the same
  explanation repeated by ten countries is a repeat, not ten lessons. The
  parts that say it DIFFERENTLY are all kept, as examples. The parts only
  one book has are kept. Nothing different is ever cut. The lesson will
  still be long — that is fine. And the countries that said the kept-once
  part are all listed in sources.md: that count IS the acceptance points.
- FOLDING KEEPS THE BEST ONE (2026-10-24, his correction): folding same-said
  parts into one never means dropping depth. The version that survives the
  fold is the one that explains it BEST — the easiest way it is explained,
  and the most detail: if one book says "it takes sunlight," another says
  "the light of sunlight," and another goes deeper ("it takes DIRECT
  sunlight"), the folded part keeps the easy words AND the deeper detail.
  If the easiest wording and the deepest detail live in different books,
  the fold takes both. "It says the same thing" is never a reason to leave
  out a variant's extra detail — surface-same can hide depth. Fold only
  true repeats; every added detail from any book survives into the part.
- WRITTEN LESSON STYLE (2026-10-24, refined same night): the lesson text is
  written the way a tutor EXPLAINS TO YOU out loud — someone telling you:
  "so the sunlight is this, this, this." Reading it feels like explaining it
  to yourself. It is READ-ALOUD READY: a teacher using the lesson can simply
  read the text and they ARE explaining it to their class — including the
  doing lines ("go get a sponge and soap"). And the writing must form
  PICTURES in the reader's mind: concrete scenes you can see — the green
  leaves, fall coming, the leaves turning and falling — not abstract
  statements. What you can see, you hardly forget. The super-simple voice
  ("there is a sun, the sun has light") belongs to the video script, and to
  the lesson's level-1 layer.
- THE EXPLAIN COMPANION (2026-10-24): when a learner registers, they pick —
  or make — something to explain things TO: a pillow, a cardboard character
  they build, whatever they want. Lessons then prompt them to read ALOUD and
  explain it to their companion, because explaining is how you understand it
  more. It is fun on purpose. This is the doing in "You do it, we guide
  you": the learner teaches, the platform guides.
- Each book's own title stays as a searchable tag in its own language, so a
  learner can find their own country's book inside the lesson.
- EVERY PART KEEPS ITS SOURCE TAG (2026-10-24): no piece enters a lesson
  without its tag — which country, which book, which page. Because the AI
  starts empty and knows only these books, a learner reading a lesson can
  hover over or select any part and ask: "Where does this come from? Who
  teaches this?" The answer is the book itself: the system brings out the
  actual PDF from the library and shows a picture (screenshot) of the exact
  page, inside the lesson. Never a link away to another website. A shown
  page is proof, not a download — the book file is never handed out (see
  the no-downloads rule at the top).
- BUILD FROM FINISHED COUNTRIES ONLY — THEN UPDATE (2026-10-25, his
  order, settling the source question): a course is built only from the
  books of countries that are FINISHED in the library (every book found
  AND secured in GitHub — his definition of finished). Every country is
  still the end goal of every course. As the library is updated — a new
  country finishes — the courses are updated with it: that country's
  books merge into the lessons, and the acceptance counts grow. A
  country that is only closed (found, not yet secured) does not enter a
  course until it finishes.
- TITLES USE THE COMMON-SENSE NAME OF THE THING ITSELF (2026-10-25, his
  order): a title is what the part IS — Greetings, Alphabet, Words
  (nouns, verbs, and the other word kinds), Sentence, Paragraph, Letter —
  never a book's unit name ("Welcome to My School" is Egypt's unit name,
  not a course title) and never a story or character name from a book
  (no "Hana" titles). The book's own name for the part stays where it
  belongs: in sources.md and as a searchable tag in its own language.
  This is the "named by what most countries call that part" rule, said
  plainer: if most books teach it, they call it by what it is.
- QUESTIONS LIVE IN SEPARATE FILES BY TYPE (2026-10-25, his order): for
  questions, create different files — one for choice, another for short
  answer, another for fill-in-the-blank, and so on. One question type per
  file, never mixed. This is so a teacher, a battle, or a learner building
  their own course can pull exactly the type they want without digging
  through the others. Inside each type file the questions are still
  grouped by level, and each question still carries its living hardness
  number (see the next rule). A type file exists only when the lesson has
  questions of that type — no empty files.
- QUESTION HARDNESS IS A LIVING NUMBER, BOTH WAYS (2026-10-24): every
  question carries a hardness point, counted from EVERYONE who ever
  answered it. It is not fixed when the question is made: if the first 10
  people find the even numbers easy, they are marked easy — and if 10,000
  people later show the big evens (8 and 6) are hard, the point moves.
  Both ways: a question can be re-marked harder OR easier at any time.
  And when a question's point moves, the scores of the people who answered
  it BEFORE are re-based too — every answer is saved (who, which question,
  right or wrong, how long), and a learner's number is always computed
  against the CURRENT hardness of the questions they answered, so an old
  answer to a question that proved hard earns its true value, and an old
  answer to a question that proved easy comes down. Like IQ: the number
  means "measured against everyone else," and the scale is re-set as the
  crowd grows. Two guards: a hardness point from few answers is marked
  provisional until enough people have answered; re-scoring runs on a
  rhythm (e.g. nightly), so a learner's number never flickers live.
- THE BATTLE AND RATING RULE (proposed by Muse, approved by Tensae
  2026-10-24 — all six parts):
  1. The skill number lives per SMALL PART (adding → single-digit adding).
     Topic, subject and course numbers are just the parts added up — the
     computer counts them, nobody manages them by hand. A brand-new part
     does not start cold: its number borrows from the bigger topic, then
     fixes itself with the learner's own answers.
  2. Next to the number sits a hidden second value: HOW SURE the system
     is. Few answers, or answers from only one corner, = not sure yet.
     Battle matching uses the careful, LOW reading of the number until the
     system is sure — a lucky streak cannot throw a learner against a much
     stronger player.
  3. Battles: friends play the SAME GAME, not the same questions. Each
     player gets questions at their own level, and points are weighed by
     the question's hardness (see the living-hardness rule above). A battle
     result moves ratings only a little; learning sessions move them more —
     battles are noisy.
  4. Speed gives only a SMALL bonus, measured against that question's
     normal speed — if everyone answers the evens in 2 seconds, your
     2 seconds is nothing special. Answering faster than a person could
     read the question counts as a guess, not knowledge.
  5. The system watches for CORNERS: it knows which corners of a part a
     learner has and has not been tested on (evens done, odds never
     served). Before a part's number may go high, the system feeds the
     untested corners in normal sessions. Nobody maxes a part from one
     easy corner of it.
  6. (With the push rule:) the system always serves a little ABOVE the
     learner's number; a wrong answer on a part the learner was never
     taught is not a failure — it routes them to learn that part first.
- TEACHER SEND (2026-10-24): a teacher picks a course, then a lesson, and
  finds that lesson's question list waiting. They can use the questions
  as they are, or select certain ones, then hit send — it goes to the whole
  class as a notification and the learners work them out. The point:
  teachers never have to remake or reread everything; the questions are
  already made.
- SUBJECT TOOLS, BUILT IN-HOUSE (2026-10-24): some lessons need a working
  tool, not just text — for example arts: a whiteboard where you draw with
  two colors and it shows the color they make together, and the shades.
  These tools get built INSIDE the platform. The way: find open-source
  projects (e.g. on GitHub) that do the thing, study how they work, and
  remake it as ours. No embedding, no depending on third-party apps —
  everything in the platform is ours and understood by us. (Copying how a
  thing works is fine; literal code follows that project's license.)
- Lesson shape: first prompt the learner to DO it, then explain how it works.
  "You do it, we guide you" — the tutor prompts, the learner does the thing.
  Every lesson ends in a real experience (the hands-on file).
- Levels mean DEPTH — simple to advanced — not school grades. Depth is set by
  how many countries explain that part and where they place it.
- When books disagree, show both sides, show the split as numbers, and tell
  the learner to ask their teacher or parents.
- History lessons are told like a story.
- A course can list what you should know first. The app shows it as a
  recommended "start here instead" path — never forced; the learner can jump
  straight in.
- The same lesson is delivered many ways (text, video script, hands-on,
  levels). Which way a learner gets is separate from how hard it is — the
  skill number sets the hardness, the form is its own choice, and special-needs
  switches are in from the start.
- Courses are built first; afterwards they feed the website AI.
- The English course is the FIRST course to be made — Tensae tests the system
  on himself.
- LESSONS ARE LEVELED TOO (2026-10-24): not only the questions — the lesson
  itself comes in levels. The way you explain a thing to someone who
  understands fast is not the way you explain it to a beginner. It is NOT
  many separate lessons (that would be too big): it is ONE lesson in layers.
  Level 1 = the simplest explanation, in the same simple voice as the video
  script. Each level up opens more of the same lesson — more of what the
  countries' books say, more examples, the why under it. The merged lesson
  stays whole (nothing cut); the learner's level decides how deep into it
  they go.
- NO-LEVEL COURSES (2026-10-24): some subjects are different in every country
  — history is the example. Those courses have no levels. The learner picks
  their country (or the course already knows it) and gets their own country's
  version first — that is what their school teaches and tests. On the same
  lesson there is a switch: "see how other countries teach this" — the other
  versions shown side by side (with the disagreement rule above). Nobody gets
  ranked against another country's version.
- PICK YOUR PART (2026-10-24): a learner can open just the one part they need
  — one part of the maths book, not the whole book. (Same as the prerequisite
  rule: the path is a recommendation, never a wall.)
- UPLOAD — MISSING GOVERNMENT BOOKS ONLY (2026-10-24, clarified same night):
  "bring your own material" means GOVERNMENT textbooks the library is
  MISSING — not books we already have, and NOT private school books.
  Uploads are the gap-filling channel: someone who holds a government book
  we lack can bring it; it gets checked like every library book.
- CREATE A COURSE (2026-10-24): from their dashboard, a learner builds
  their own course. The case he gave: an exam tomorrow — "Chemistry is
  coming from Unit 2, Biology is Unit 3, from your country's textbooks."
  If the book is on the platform, they pick the units they want. If they
  don't find their book or units, they SEARCH the platform's courses and
  pick the parts themselves. Either way the system assembles a personal
  course from those parts, and they go through it that night. (This is
  also how private-school students are served: no uploads of their books —
  they search and build.)
- EXAM COURSES TEACH IN FULL DETAIL (2026-10-24): a self-built exam course
  does NOT use the normal slow, leveled pacing. It teaches everything
  about the picked parts, in detail, as much as can be taught — the full
  coverage, because tomorrow there is an exam.
- ACCEPTANCE POINTS (2026-10-24): every topic carries points = how many
  countries teach that part. The more countries teach it, the more accepted
  it is. The learner can SEE this ("taught in 140 countries") — it is the
  proof behind the learning, the same reason Sophia Learning's credits are
  wanted: other schools accept them. (Same country-count that sets depth.)
- MY COUNTRIES (2026-10-24): a learner picks the countries they want their
  books from — one, or three or four (for example to fix their scholarship
  chances in a country they want to study in). Then they are shown courses
  built ONLY from those countries' books — and any subject those countries
  require that the learner does not have gets ADDED into their path, so
  nothing their chosen countries expect is missing.
- FUTURE — A REAL SCHOOL (2026-10-24, vision, not now): one day apply for a
  school permit and run an actual school on this curriculum — take in
  homeschooling children, give parents teacher access, hire teachers from
  other countries to teach it. The acceptance points and the per-country
  records are the proof such a school would stand on.
- THREE KINDS OF COURSES (2026-10-24, his taxonomy — replaces "two kinds"):
  1. LEVEL courses — the same facts everywhere: mathematics, biology,
     chemistry, physics.
  2. SKILL courses — global skills you practice: health and fitness,
     computer skills, language skills (English or any language: reading,
     writing, grammar), music basics.
  3. NO-LEVEL country courses — cultural, changes by country: history,
     civics, religion (separate versions, see above), a country's own
     literature and stories. Geography sits here by his list — but see the
     mixed-subjects note below.
- INSIDE A NO-LEVEL COURSE (2026-10-24), e.g. History:
  * "As in your textbook" — your own country's version.
  * Your picked countries (chosen in Settings — the "my countries" for
    scholarships etc.; change them in Settings and your feed changes) —
    each picked country's version, pick any.
  * "The World" — the main path: the same part learned from EVERY country.
    It is big, but the learner who takes the World way earns MORE (bonuses —
    exact bonus still open). History on the World way is told as a story,
    like a picture book.
  * PICTURE RULE for the World way: pictures must be REAL — real photographs
    where they exist, or real art: paintings and pieces that sit in museums,
    art made in that time about that thing. Never a drawing made just to
    explain the lesson. A real piece that truly belongs next to it.
- RELIGION — direction SET, work DEFERRED (2026-10-24): religions come in
  versions — Christianity is almost the same everywhere but different for
  Coptic, Orthodox, Protestant, Catholic and others. Rule: each version gets
  its OWN separate version of the course, and EVERYTHING is taken in —
  nothing excluded. (This sets the direction for cases like Egypt's tracks.)
  But religion itself is NOT now: it comes in the future, with its own
  research pass first.
- VALUES CONTENT FOLLOWS THE BOOKS AND THE LEARNER (2026-10-24): the
  platform teaches what each country's books teach and what learners want
  to learn. The founder's personal beliefs do not gate the content — his
  words: "if people want to know, who am I to say no... I'm a businessman
  at the end of the day." Same machine as everything else: the country's
  version stands as that country teaches it.
- MIXED SUBJECTS — MUSE'S ANSWER to his geography question (2026-10-24,
  proposed, awaiting his ruling): geography is two subjects in one coat —
  PHYSICAL geography (how the earth works: rivers, climate, landforms,
  maps) is science, the same everywhere, leveled; HUMAN geography (your
  country's regions, resources, borders, "our land") is country-shaped,
  no-level. The general fix: don't classify subjects — classify TITLES.
  Each part of a mixed subject goes where IT belongs, so one Geography
  course holds leveled physical titles + the learner's country's human
  titles, woven together. Other mixed subjects like geography: economics
  (principles = level/skill; your country's economy and money = country),
  biology (the human body = level; your country's farming, crops and
  nature = country-flavored), language (grammar = skill; literature =
  country) — his design already splits that last pair.
- COLD START — VALUES COME FROM ALL THE COUNTRIES TOGETHER (2026-10-24,
  corrected same night): there is NO base country. When a course is
  created, each part is valued from the pattern across the countries: if a
  part repeats in grade 1 in country after country, it is a grade-1-level
  part — low level, low points, because the explanation for small kids is
  simpler and lower. If a part sits in the big grades, its explanation is
  deeper and it carries a higher point. The SAME topic can live at several
  levels: photosynthesis as grade 1 teaches it and photosynthesis as
  grade 12 teaches it are different layers with different points. Every
  seeded value is PROVISIONAL: as real learners come in, the system
  re-assesses and the values get fixed — the same living-number machine as
  question hardness.
- HOW YOU'RE TAUGHT IS YOUR CHOICE (2026-10-25): when a learner builds a
  course, they choose the teaching mix themselves:
  * Explanation: none / small / detailed.
  * Questions: none / light / heavy.
  * Question hardness: easy / hard.
  Named shapes from his words: Revise it · Detailed explanation ·
  Questions only · Heavy on questions, low on lessons · Hard questions,
  small explanation · Detailed explanation, easy questions. This is the
  delivery-form knob from the one-course-many-forms design, put in the
  learner's hands at build time.
