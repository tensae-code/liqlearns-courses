# Inverse trigonometric functions — the lesson

Course: Maths · Stage: Stage 9 — Further Geometry · Lesson: Inverse trigonometric functions
Built from: Nicaragua, Grade 10 student book — Armenia, Algebra and Elements of Mathematical Analysis 10 — Laos, Grade 12 student book — Cambodia, Grade 12 Advanced student book (placement only, as filed) — see lesson/sources.md for every part.

## Do it first
You know sin 30° = 1/2. Now run it backwards: a calculator tells you sin θ = 1/2 — what is θ? You will say 30°. But sin 150° is also 1/2. And sin 390°. One ratio, many angles. Undoing sine cannot give all of them — it must give ONE. Choosing which one, honestly and by rule, is this whole lesson.

## Then the explanation
**Why restriction comes first.** Sine, cosine and tangent are not one-to-one: the same value comes back again and again as the angle grows. Nicaragua's Grade 10 book makes this the opening point of its treatment (Unit 2, printed pp. 133–141): before any inverse is defined, each function's domain is cut down to a piece where it never repeats a value — sine to [−π/2, π/2], cosine to [0, π], tangent to (−π/2, π/2). Only then can the undoing be a function at all. Armenia's Grade 10 book builds the same ground in the same order: the arcsine, arccosine, arctangent and arccotangent are first named inside its trigonometric-equations section (Chapter 4, §10, printed p. 119), and its inverse section then starts from the inverse-function concept and the condition for an inverse to exist (Chapter 4, §12, printed p. 145).

**The three inverses and the ranges they answer in.** With the domains cut as above, Nicaragua's book defines arcsin, arccos and arctan (printed pp. 133–141). Say what each one means in words: arcsin a is THE angle in [−90°, 90°] whose sine is a. That gives the three ranges you must hold:

- arcsin a lies in [−90°, 90°], and a must lie in [−1, 1].
- arccos a lies in [0°, 180°], and a must lie in [−1, 1].
- arctan a lies in (−90°, 90°), and a can be any real number.

So arcsin(1/2) = 30°, arccos(1/2) = 60°, arctan(1) = 45°, arcsin(−1/2) = −30°. Armenia's book treats the same four inverses — arcsine, arccosine, arctangent and arccotangent — as its §12 topic (printed p. 145).

**Calculator values.** Not every ratio is a special angle. Nicaragua's book uses the calculator for inverse values, including tan⁻¹(2016) — a huge input whose answer still lands just below 90°, inside the arctangent range (printed pp. 133–141). The range is the check: if a calculator answer for arcsine ever falls outside [−90°, 90°], the working, not the range, is wrong.

**Undoing, and when undoing does not bring you back.** For x inside the restricted domain, f⁻¹(f(x)) = x. Outside it, that fails — and Nicaragua's book insists on the failure case: sen⁻¹(sen 5π/…) is NOT the angle you started with, because the answer must fold back into [−π/2, π/2] (printed pp. 133–141). The inverse always answers inside its range; an outside angle is folded to the inside angle with the same ratio.

**Compositions: turn the inverse into a triangle.** To simplify cos(arcsin x), let θ = arcsin x. Then sin θ = x = x/1: draw a right triangle with hypotenuse 1 and opposite x. Pythagoras gives the adjacent side √(1 − x²), so cos(arcsin x) = √(1 − x²). Nicaragua's book works this family — cos(sen⁻¹ x), sen(2 sen⁻¹ u) and sen(sen⁻¹ u + sen⁻¹ v) (printed pp. 133–141). The method never changes: name the angle, draw its triangle, read the ratio off.

**Solving graphically.** The same book solves trigonometric equations by drawing both sides and reading the crossings — its examples include tan x = sen x and cos 2t = −3 cos t − 2 (printed pp. 133–141). An inverse value is one crossing read exactly; the graph shows all the crossings in the interval you draw.

**Where the other books place this.** Laos's Grade 12 book gives the inverses of the trigonometric functions their own lesson inside its inverse-functions chapter — Chapter 8, Lesson 24, printed p. 227, straight after the definition and properties of inverse functions in Lesson 23 (printed p. 224). Cambodia's Grade 12 Advanced book also carries the topic: §3.2, Inverse trigonometric functions, printed p. 54 — filed from the table of contents and the teacher guide's lesson plan; the section start was not read in detail in the student book, so this lesson takes the placement from Cambodia and no detail beyond it.

Tip — from us, not from the books. Check the range before you check the arithmetic. Nine wrong inverse answers out of ten are a right ratio attached to an angle outside its range — the range test catches them in one second.

## Say it to your companion
Give your companion a ratio — say sin θ = √3/2 — and ask: "What does arcsin give back, and why not the other angle with the same sine?" They answer: 60°, because arcsine only answers inside [−90°, 90°], and 120° lives outside it. Swap: they give a ratio, you give the inverse value and its range defence. Three rounds each, one per function.

## Do It Yourself
1. Write arcsin(√2/2), arccos(0) and arctan(√3) as angles. (Answers: 45°, 90°, 60°.)
2. A calculator gives tan⁻¹(2016). Without trusting it blindly, say between which two whole degrees the answer must lie, and why. (Answer: between 89° and 90° — arctangent answers inside (−90°, 90°), and a very large input pushes the angle close to 90° without reaching it.)
3. Let θ = arcsin(3/5). Draw θ's triangle and find cos θ and tan θ. (Answers: cos θ = 4/5, tan θ = 3/4.)
4. Is arcsin(sin 200°) equal to 200°? Say what it equals and why. (Answer: No — sin 200° ≈ −0.342, and arcsin answers inside [−90°, 90°]: arcsin(sin 200°) = −20°, the inside angle with the same sine.)
