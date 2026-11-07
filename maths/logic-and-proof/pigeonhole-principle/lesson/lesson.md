# The pigeonhole principle — the lesson

Course: Maths · Stage: Stage 13 — Logic and Proof · Lesson: The pigeonhole principle
Built from: Iran, Discrete Mathematics, Grade 12 — China, Mathematics, Grade 6, Volume 2 — North Macedonia, Mathematics, Grade 8 (2010 edition) — Kazakhstan, Algebra, Grade 8 (starred, optional additional material as filed)

## Do it first
Take 5 pencils and 4 boxes. Put the pencils into the boxes any way you like — and try to keep every box at one pencil or fewer. You will fail. Four boxes can hold four single pencils, and the fifth pencil has nowhere of its own to go: some box must end with two. You did not choose which box, and you cannot stop it happening. That forced sharing is the whole lesson, and four countries' books teach it as a way of *proving* things.

## Then the explanation
**The plain principle.** If more things go into fewer boxes, some box must hold at least two. With n boxes, n + 1 things are enough to force it. China's Grade 6 book teaches exactly this as the **drawer principle**, working it first by drawing every case and then by division with remainder, in problems that all ask what can be *guaranteed* (Grade 6, Volume 2, Unit 5, pp.68–71). A box in the book is a drawer; in other books it is a perch, a hutch or a pile — the shape of the box never matters, only the count.

**The division form.** Share the things out as fairly as you can. China's own working: 7 things into 3 drawers gives 7 ÷ 3 = 2 remainder 1 — every drawer can take 2, and the 1 left over must land somewhere, so some drawer holds at least 3 (Grade 6, p.68). The rule: divide, and if there is any remainder at all, the guaranteed number in some box is the quotient plus one. If there is no remainder, the quotient itself is guaranteed, because fair sharing already puts that many everywhere.

**A real proof with it.** North Macedonia's Grade 8 book uses the principle — there called **Dirichlet's principle** — as a proof method inside its systems-of-equations theme (Theme 3, unit 8, pp.153–155). Its class example: 30 pupils take a test, and each pupil's number of errors is one of the 9 counts 0, 1, 2, …, 8. The 9 counts are the boxes; the 30 pupils are the things. Sharing fairly: 30 = 3·9 + 3, so after three full rounds three pupils are still unplaced, and wherever they go, some count is shared by at least 4 pupils. The book works the same way through birthdays, initials, divisibility of differences and angle arguments (pp.153–155) — in each one, the work is choosing the boxes well.

**The generalised form.** Iran's Discrete Mathematics book states the principle and its generalised form in its counting chapter: kn + 1 objects in n boxes force some box to hold at least k + 1, and it closes the chapter with pigeonhole proofs in the exercises (Grade 12, Discrete Mathematics, pp.82–84). Its own first application is the birth-month guarantee: 13 people, 12 months — here k = 1 and n = 12, so 13 = 1·12 + 1 people force two to share a birth month (p.82). Push it one step: 25 people is 2·12 + 1, so some month holds at least 3 birthdays.

**The same principle, a fourth home.** Kazakhstan's Grade 8 Algebra carries the Dirichlet principle too — as starred, optional additional material in its closing chapter of extra topics, §6.5* (p.177), with worked "rabbits into hutches" examples: the hutches are the boxes, the rabbits are the things. It is filed as optional in that book, and it is taught here as exactly that — an optional-extra home for a principle the other three books teach in their main text.

Tip — from us, not from the books. In every pigeonhole problem, name the boxes first, out loud, before you count anything. "The boxes are the 12 months." Nine problems out of ten become easy the moment the boxes are named — choosing the boxes IS the problem.

## Say it to your companion
Say the principle in your own words: "More things than boxes — some box gets two." Then prove to your companion that in any class of 13 pupils, two share a birth month, naming the boxes and the things. Trade: your companion proves that pulling 4 socks from a drawer of socks in 3 colours must give a matching pair, and you say where the boxes are in that proof.

## Do It Yourself
1. Ten pigeons, nine holes. What is guaranteed, and why?
2. A class has 31 pupils. Prove that at least three of them share a birth month. (31 = 2·12 + 7 — where do the extra pupils force the third?)
3. Eleven whole numbers are chosen. Prove that two of them end in the same digit — so their difference is divisible by 10. (The boxes are the 10 possible last digits.)
4. Kazakhstan's way: 10 rabbits, 9 hutches. State the guarantee, then say the smallest number of rabbits that would force some hutch to hold at least 3.
