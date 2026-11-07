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
      <subtitle>/                ← one kind under that title (example: under
                                   Word — nouns, verbs, adjectives, adverbs,
                                   pronouns). This folder holds ONE lesson,
                                   and that lesson explains ONE thing only —
                                   a conversation lesson is conversation
                                   only, never telling the time or anything
                                   else the same book unit happened to teach. Several things
                                   in one book unit split into several
                                   subtitle folders, each with its own lesson.
                                   One thing can still be BIG inside itself:
                                   pronouns alone carry he (a man) / she (a
                                   woman) / I / you / it / we / they and their
                                   other forms, with many explanations and
                                   questions — all of that depth stays inside
                                   the pronouns lesson. The split test: a part
                                   INSIDE the thing stays; a different thing
                                   BESIDE it (noun next to pronoun) gets its
                                   own folder, even if a book teaches them
                                   together. Related lessons point at each
                                   other; they do not merge.
        lesson-plan.md           ← the plan for THIS one lesson (2026-10-25):
                                   its one thing, its place in the curriculum,
                                   what the learner can do at the end, the run
                                   of the lesson in order, and the ADD-ON
                                   slots — at the exact places they belong,
                                   lines like "ADD IMAGE: a picture of …",
                                   "ADD GIF: …", "ADD VIDEO: …", "ADD
                                   AUDIO: …", each slot describing the
                                   add-on in words PLUS one little line
                                   saying what the student does with it.
                                   The words carry the picture while the
                                   course is built and while the AI learns
                                   from the books (a picture book is learned
                                   from by describing its pictures); on the
                                   website the real add-on is dropped into
                                   the slot and the little explanation stays
                                   as the student's guide. The plan is the
                                   build sheet for the lesson page.
                                   (A curriculum is for the WHOLE course;
                                   a lesson plan is for ONE lesson.)
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
        levels.md                ← practice sessions by level, tied to the
                                   learner's skill number (starts at 100 and
                                   moves as they learn). Example for maths:
                                   single-digit level, then double-digit level.
                                   (Moved out of questions/ 2026-10-26 —
                                   levels are not questions.)
        video-script.md          ← a script written as simple as possible,
                                   like explaining to a grade-one child, ready
                                   to hand to a video AI later. We write and
                                   save these now; videos get made when there
                                   is budget for it. (Also moved out of
                                   questions/ 2026-10-26.)
        hands-on.md              ← projects and real things to do with your
                                   hands, so the learner understands by doing.
                                   (Also moved out of questions/ 2026-10-26.)
```

## Rules (Tensae's design — do not change without his word)

- The AI that builds these starts EMPTY. Everything it knows comes from the
  collected books only.
- LEVELS, NOT TERMS (his ruling, 2026-10-26): a course's big parts are
  LEVELS, climbed at the learner's own pace — not school terms tied to
  a calendar. The English path's titles were also split the same day:
  the old "Letter" title is now **Alphabet** (the letters themselves)
  and **Phonics** (the sounds, blending, blends, word families) —
  "Letter" also means the letter you write and send, and the two
  meanings no longer share one title. CURRICULUM.md holds the plan
  only (units and lessons in order); each book's stocking notes live
  with the book's own map.
- ONE FORMER UNIT = ONE LEVEL ON THE ENGLISH PATH (his ruling,
  2026-10-27): the English course was first built as four broad levels
  of four units each, and the units were uneven in size. He separated
  them: every former unit is now a level of its own — 17 levels in all:
  1 Pencil and Lines · 2 The Alphabet · 3 Sounds Together · 4 First
  Words · 5 Conversation · 6 Word Kinds · 7 Words for the World ·
  8 Using the Dictionary · 9 Numbers, Days, and Time · 10 Building a
  Sentence · 11 Questions · 12 Now, Before, Later · 13 Joining and
  Describing · 14 The Paragraph · 15 Reading Whole Texts · 16 The
  Essay · 17 Stories. **Pencil and Lines is Level 1** (his correction:
  that is level one — not a step before Level 1, and not Level 11),
  while it remains its own shared course before every language.
- A LESSON IS A LEVEL (his ruling, 2026-10-26): every lesson is itself a
  level on the ladder — not just the course's big Levels. A lesson's
  level is counted from its chain: a lesson that needs nothing before
  it is level 1; a lesson that needs a level 1 lesson first is level 2;
  and so on. So a lesson CAN MOVE — a lesson that is level 1 today
  becomes level 2 later if something new comes before it. The numbers
  grow by themselves from the chain; nobody renumbers by hand. The
  small steps INSIDE one lesson (its sub-lessons) are RANKS.
  Restated by him 2026-10-27 with the maxing frame: one lesson is
  one level, and a course is ONE thing you master — you max it
  out, the way in Clash of Clans you max out the Town Hall and
  then move to the next one. It is all about maxing: max the
  level, max the course. (His older word, 2026-10-10, rides with
  it: when a course later gains new material, a learner who had
  it maxed is un-maxed until they finish the new work — nothing
  earned is erased; the ceiling grows.)
- LAUNCH FIRST, TOUCH-UPS AS UPDATES (his ruling, 2026-10-26): the
  product launches when the textbook library is complete — every
  country's books found — and the courses are made. The courses built
  from the books found (and still being found) are the BASE. Level
  fixes and touch-ups, and extra-bonus material, come later as
  UPDATES after launch — they are not work for now.
- THE LEARNER CODE (his design, ruled 2026-10-26): at signup the
  learner answers about ten lists — how long they like to stay
  (5 / 10 / 30 / 60 minutes), what they like doing most (games or
  courses), more questions or more lessons, and more more-of /
  less-of lists like those. The answers (first list A, second D,
  third B…) are joined into a CODE kept inside the learner's ID,
  and every course they open follows that code — it is how the
  platform knows how this person likes learning. **The code works
  BOTH WAYS (his ruling):** the picks write its first version, and
  the platform then adjusts it from how the person actually
  learns — real session lengths, the real mix of questions to
  lessons. The seed of the code already exists in the site's
  Settings (the learning-style picks and the accessibility picks —
  "Teach me visually," Dyslexia Support, ADHD Focus Mode, high
  contrast, and the rest). One line inside it: NEEDS never
  auto-change — a dyslexia font, contrast, a calm mode is changed
  only by the person, in Settings; HABITS can tune themselves.
- THE FOCUS CLOCK (his ruling, 2026-10-26; his model is the MGM
  training platform): the platform can tell when the learner
  leaves the study screen — tab hidden, window minimised, app
  switched. When they leave, the CLOCK stops: the time away is
  not counted as studying, and audio/video pause; the class does
  not visibly stop and nobody is punished. Quick trips away — a
  minute or two, back and forth, the way a person checks notes
  kept on the side — still count as studying; split-screen
  counts as present. It exists so the code's session-length list
  stays honest: time "watched" while the learner was elsewhere
  would poison it.
- FULL READS ONLY (his ruling, 2026-10-26, correcting Muse):
  every book is read WHOLE — every page, everything in it. The
  "basics-only" pass (a tight map instead of a full read) was
  Muse's own change, made while handling another AI's review;
  it was never his order, and he revoked it in his words:
  "Forget what Claude said. Forget the basic things only."
  The reason for full reads is the build itself: every
  country's version of a thing is put together into ONE
  explanation, and ALL of the book's questions are taken out
  and saved for play and for teachers — that needs the whole
  book, page by page, not its outline. Books filed basics-only
  before this ruling (Egypt Secondary 10 T2–12, India,
  Bangladesh, the Ghana and Palestine filings, Nicaragua
  Activity Books 3–4) stand in their files as MAPPED, not
  read, and each owes a full re-read before the citation
  check and before any lesson is built from it.
- THE CITATION CHECK (his ruling, 2026-10-26): no book is pushed
  or called FINISHED on the reader's word alone. Between the
  reading and the push, a separate checking pass goes through
  the book's filing item by item: everything the filing mentions
  must be attached to its place in the real textbook — country,
  book, and PAGE — and the checker opens those pages in the book
  itself and confirms the thing is really there. An item with no
  page, or a page that does not hold it, sends the book back; it
  is not finished. This is what the whole build is for: a learner
  inside a lesson can ask the AI "where does it say this?" and
  be taken to the page and the book of that country. The filings'
  page tags are the index the AI answers from, and a lesson's
  `sources.md` inherits them.
- THE PROVENANCE TEST (his design, stated 2026-10-26): a
  lesson file must stand on its own in front of a stranger.
  He will one day send a whole lesson file to an AI that has
  never seen the books (his example: DeepSeek) and ask it,
  part by part, "where does this come from?" — and it must
  be able to answer from the file alone: **this country,
  this book, this grade, this page**, for every part, one
  after another. So every part of a lesson carries its
  country + book + grade + page with it (in the lesson's
  sources, part by part — not one lump sum for the whole
  lesson). A part that cannot be traced that way is not
  finished. The citation works as a REFERENCE, the way he
  will use it himself: "on this page of this country's
  textbook, it says this" — no page pictures and no copied
  text are sent out for checking; the reference itself is
  the proof.
- THE TWO-WAY RULE (his design, ruled 2026-10-26): the
  books and the course must match BOTH ways. Everything
  in the books must be in the course — nothing a book
  teaches gets dropped. And everything in the course
  must be in the books — nothing in a lesson is invented
  (the provenance test is this direction). It must work
  for a person, too: he can open any book, find a thing,
  ask the AI "explain this / make a course on this," and
  be pointed to the lesson that teaches it; open the
  lesson, learn it there. So every book part knows its
  lesson, and every lesson part knows its book page.
- THE DONE STANDARD (his design, ruled 2026-10-26): we
  are a tutorial platform. We must know everything in
  the books, explain it better than anyone, and make
  sure the learner really understands it. When a learner
  opens the app for a certain thing and learns it, they
  close the app DONE with that thing — not half-taught,
  not "come back later and maybe." A lesson that leaves
  the thing shaky is not finished.
- THE DASHBOARD FEELING (his design, ruled 2026-10-26):
  when learners open the app and see their dashboard,
  they should feel: I am trying, I am getting somewhere,
  I am doing great — AND there is a skill open in front
  of me that I can still learn to be better. Great now,
  and able to be the best. The dashboard shows real
  progress they have honestly made, plus the next skill
  opening ahead of them — pride and a road, both.
- RANKED AND UNRANKED COURSES (his design, ruled 2026-10-26): a
  course can be taken two ways. RANKED is the platform's side —
  "amongst each other, among different people": the shared
  ladder where a learner's level, points and standing live.
  Finishing a ranked course gives you a level, and behind it
  sits the point system — where you are standing, how you are
  learning — and from that the platform fixes your future
  things. UNRANKED is for yourself: you have an exam tomorrow,
  you mix a bunch of things from different classes and learn
  them; you can go back and work through a thing again; and
  there are NO pass-gates — you don't pass something before
  knowing the other one. Unranked is also what you use for
  your classes — learning your own curriculum, your country's
  curriculum. (Ranked and unranked GAMES are a separate
  question, parked by him — "we'll return to it.")
- THE FIRST STAGE IS PICTURES, SOUND AND VIDEO (his design,
  ruled 2026-10-26): in English, everything before the learner
  can make sentences and hold the basic conversation every
  toddler knows — hi, how are you, good morning, good
  afternoon, telling the time, and so on — is taught mostly
  with PICTURES, AUDIO and VIDEO, with very few written
  words: the learner may not read yet, in any language. One
  course serves everyone — a small child and an adult
  starting from zero take the same first stage. Two parts
  of it are his design:
  - **TRACING BY SOUND:** letters are traced stroke by
    stroke, and each stroke direction carries its own
    cartoon sound — the falling sound when the pen goes
    down, another sound when it goes across, another when
    it goes up. Learners already know these sounds from
    cartoons and films, so the sound itself tells the hand
    which way to move, in any language.
  - **LETTER + WORD + PICTURE, NO "FOR":** a letter is
    taught with its word and the picture of the thing shown
    together — "A — apple", "B — ball". We never say "A for
    apple": the "for" is an extra word a beginner does not
    need. Letter, word, picture — side by side, nothing
    between them.
  The pictures, audio and video for this stage are made for
  the course (AI-made or otherwise — his call at build
  time); no textbook teaches this stage in words, so its
  lesson plans carry it as add-on slots described in words,
  under the slot rule below.
- MEDIA FOR EXPLAINING — GIFs FIRST (his design, ruled
  2026-10-26): wherever a lesson has to EXPLAIN something,
  the explanation can ride on a picture, a video, or a GIF
  dropped into the lesson's media slots. **GIFs are the
  default moving media** — one or two seconds, easy to
  make, easy to edit, easy to swap out later. Where a GIF
  is not enough, a short video: found (a video that already
  explains the thing well), made by him as an animation, or
  AI-generated. Story-like subjects are taught as stories —
  history above all is better explained by a video that
  tells it like a story (his model: the animated map films
  of armies on the move). Process subjects get motion too:
  geography explaining how kinds of rocks are formed needs
  an animation, not a paragraph alone. **Everything is
  written first:** every lesson plan writes each picture,
  GIF and video it needs as a described slot in words (the
  slot rule), so the course is complete on paper and the
  media can be made, found, or swapped at any time without
  touching the lesson. This updates the 2026-10-25 posture
  (video scripts filed, no videos made): full lesson videos
  are still not the plan — short, swappable GIFs and clips
  are.
- SPEAKER BUTTON + TWO KINDS OF PARTS (his ruling, 2026-11-01):
  most learners using these courses start knowing almost
  nothing of the language the book is written in — they may be
  children or adults. So every course page carries a **speaker
  button at the top**, and **at signup the learner is asked
  their main language**. The button opens a dropdown with two
  choices: (1) **read out loud** — reading the book out IS
  explaining the book; and (2) **in my own language** — the
  explanation read/translated into the learner's main
  language. For that to work, **every part of every lesson is
  marked as one of two kinds when the lesson is built**:
  - **EXPLANATION parts** — everything around the thing being
    taught ("the book says, to say hi in Amharic you have to
    say…"). These follow the learner's chosen language: they
    can be read aloud and translated into the learner's main
    language.
  - **TARGET parts** — the thing itself being taught: the
    letter, the word, the phrase (ሰላም — "selam", S-E-L-A-M).
    These are NEVER translated and never read in another
    language's voice. The reader **switches to the target
    language's own voice** to read that part — pronunciation
    is read the way that language reads — then **switches
    back** to the explanation language and reads the rest.
  This refines the 2026-10-28 zero-start rule: a language
  course's TARGET is still never translated (it is learned as
  it is, with pictures and its own pronunciation); what the
  learner's own language carries is the EXPLANATION around
  it. He will add the same button on LiqLearns itself.
  Same ruling: the FIRST course (Pencil and Lines) cannot
  lean on text at all — **every step (all five grip steps)
  and the first explanation carry a GIF or short video**, so
  a learner who cannot read yet can copy the moving picture.
- TIPS ARE OURS (his ruling, 2026-10-26): a lesson's teaching comes from
  the government textbooks only. Anything extra — a clearer way to say a
  thing, a check or a trick that helps the learner DO the thing, or help
  taken from other material later — never goes into the lesson as if a
  book said it. It goes in a **Tip box** inside the lesson, marked as
  ours ("Tip — from us, not from the books"). The course's first page
  tells the learner exactly this: everything here is from government
  textbooks around the world; the tips in boxes are from us, to help
  you understand. (The textbooks themselves teach this way — their own
  Tip boxes explain things beside the lesson.)
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
- EVERYTHING GOES IN — NO BOOK, NO ITEM LEFT OUT (2026-11-06, his words):
  "blend everything into one course… I need everything in the course. I do
  not care if they teach it or not, there might be other countries that
  might learn from the way they teach it in Iran. Or any other country. So
  do not leave out anything. Any book." This REVOKES the old practice of
  holding "unkeyed" stock aside when a book teaches something no existing
  lesson covers. From now on: (1) every teaching item in every read book
  lands in the course — if no lesson covers that thing, a NEW lesson is
  built for it (one lesson = one thing, standard shape, real book + page
  sources); (2) a country's own WAY of teaching a thing (its method,
  examples, order) is itself course content, kept as examples even when
  few countries teach that thing; (3) merges no longer report items as
  "held unkeyed" — they either stock an existing lesson or create the new
  lesson in the same pass. The catch-up builds for the stock held out of
  the English and Maths merges before this ruling run under this rule.
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
- ONE BOOK AT A TIME, ONE FILE PER BOOK (2026-10-25, his workflow
  rule): download a book, read it, create its file (english/books/
  <country>.md), and fill the file as the reading finds things; a
  book is finished — whole map read, every basic filed into its
  lesson — before the next book starts. No parallel half-reads
  spread across countries.
- PENCIL AND LINES — A NORMAL COURSE, PREREQUISITE BEFORE EVERY
  LANGUAGE (2026-10-25, his ruling): holding a pencil and drawing /
  understanding lines is not a side lesson inside English. It is its
  own course (pencil-and-lines/), standing as the prerequisite before
  EVERY language course — because learners have to learn the words,
  and words are written: the hand learns first. Recommended, never
  forced, like every prerequisite. Content merges from every closed
  country's first books (KG/Grade 1) whose files are in hand, as
  basics are found and filed where they belong. **On the English path it is Level 1** (his
  correction, 2026-10-27) — being Level 1 there does not remove it as
  the shared standalone course for the other languages.
- BUILD FROM EVERY CLOSED COUNTRY — READ WHAT WE HAVE (2026-11-03, his
  order: "open the courses to all 52 closed countries, read their
  English books as we have the files"): a course is built from the
  books of every country that is CLOSED in the library (every required
  book found — 52 countries as of 2026-11-03). A closed country joins
  the courses pool the day it closes; its books are read as we have the
  actual files in hand, and a book that is still link-only enters when
  its file lands. Finished countries (every book found AND secured in
  GitHub) join the same way as before. Every country is still the end
  goal of every course, and the courses keep updating as the library
  updates: books merge into the lessons and the acceptance counts grow.
  This supersedes the 2026-10-25 rule "build from finished countries
  only — then update."
- TITLES USE THE COMMON-SENSE NAME OF THE THING ITSELF (2026-10-25, his
  order): a title is what the part IS — Conversation, Alphabet, Words
  (nouns, verbs, and the other word kinds), Sentence, Paragraph, Letter —
  and the title must be the BIG true name of the thing, not a small
  corner of it (his correction, 2026-10-25: "Greetings" was too small —
  hi, how-are-you, introducing yourself, and asking someone's age are
  all CONVERSATION, so the title is Conversation and Age is not a title
  of its own);
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
- THE LIQLEARNS DICTIONARY (his design, 2026-10-27 — a FUTURE
  update, not a right-now project; he will start it soon): we make
  our OWN dictionary inside the platform. It sits as a word list on
  the side: the learner scrolls the list or searches a word — or a
  whole sentence — and picks a country; the word is shown as it is
  called in that country's tongue, in that language's own letters,
  with its English-letters spelling (his example: Amharic for hello
  is ሰላም, written "selam," S-E-L-A-M). Entries live in a document:
  English on one side, every country's word on the other. Ours,
  because Google Translate covers only some languages and its
  translations carry misalignments. When it ships, it is named in
  the update list like his other updates ("we created an update
  for the dictionary"). This is the tool itself, separate from the
  lesson that teaches dictionary skill (English Level 8, Using the
  Dictionary). Full filing: DICTIONARY.md in this repo's root.
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
    (Amendment, his ruling 2026-10-26: for TEACHING pictures inside a
    lesson — a step-by-step hand diagram, a child growing taller, a chart —
    a simple drawing IS allowed when no real photo can teach the thing.
    Real things — animals, places, real people, history — still take real
    photos or real art.)
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

## DIRECT ENTRY — LEARN THE ONE THING YOU CAME FOR (2026-11-04)

His ruling, courses chat, 2026-11-04: when a learner opens a lesson, they want to learn THAT thing only — they do not want to be started from things they already know. Most people come for one certain thing, learn it on its one level, and that is it.

- Every lesson must stand alone for a learner who lands on it directly: it teaches its one thing completely without requiring the earlier lessons first.
- Prerequisites may be shown only as a soft hint at the top — in his shape: if you know this one, this course will be easier for you, so you might as well try this one first. A suggestion, never a gate, never a forced start.
- This sharpens the standing prerequisite rule (recommended "start here instead" paths, never forced, 2026-10-11): the hint stays, the standalone lesson is the law.
