<!-- Sub-lessons restructure (2026-11-08 ruling): template = maths/numbers/counting/lesson-plan.md -->

# Lesson plan — Correlation and Regression

**Course:** Maths · **Unit:** Unit 16 — Further Statistics and Probability · **Lesson:** Correlation and Regression
**Place in the curriculum:** Level 122 of 136, the sixth lesson of Stage 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** when two quantities are measured together, how to see their link in a scatter diagram, measure it with Pearson's r and Spearman's rank coefficient, fit the least-squares regression line and use it to predict — and why a strong correlation still does not prove that one thing causes the other.
**This lesson's own level:** it stands on Collecting and Showing Data and Averages and Spread (Stage 11) — paired data, means and standard deviations — and on Hypothesis Testing (Level 121, same stage) only for the closing ANOVA part's way of splitting variation. It needs nothing else.

A lesson plan also says **what goes on top of the lesson**: at the
exact places marked below, the lesson page carries an add-on — an
image, a GIF, a video, an audio. Every slot is written as **"a picture
of …" in words, plus one little line saying what the student does
with it**. The words carry the picture while the course is built and
while the AI learns from the books; on the website the real add-on is
dropped into that slot and the little explanation stays as the
student's guide. Images follow the picture rule (a real photograph,
or real art, with its source). GIFs come first where a thing must be
shown changing.

## Sub lessons
The parts of this lesson, in order — the list the learner sees
from the start, locked ahead, each opening when the one before
it is proved (the gate: README, "Units, Lessons and Sub Lessons
(ruled 2026-11-08)"):

1. **Scatter Diagrams and the Mean Point** — plot paired data as a scatter diagram, find and plot the mean point, and describe the cloud's direction and strength. (Was depth Level 1.)
2. **Pearson's r and Spearman's Rank Coefficient** — compute Pearson's r and place it in the strength bands, rank paired data with ties averaged, and compute Spearman's rank coefficient from Σd². (Was depth Level 2.)
3. **The Regression Line, Determination, Causation and ANOVA** — fit the least-squares regression line and predict with it, use the coefficient of determination r², explain why correlation is not causation, and say what ANOVA compares. (Was depth Level 3.)

Gate pool: all questions of the sub lesson (no hardness ranking is written in this lesson's question files).

## Before this lesson
- Recommended first: Collecting and Showing Data (Stage 11) — a scatter diagram is a chart of paired measurements. Recommended, never forced.
- Recommended first: Averages and Spread (Stage 11) — Pearson's r and the regression slope are built from means, deviations and the covariance. Recommended, never forced.
- Recommended first: Hypothesis Testing (Level 121, same stage) — the closing ANOVA part splits variation into parts, the way a test splits a decision. Recommended, never forced.

## What the learner can do when it ends
1. Plot paired data as a scatter diagram and read its direction and strength — upward, downward, strong, weak, or no pattern (Egypt's Statistics book, Unit 1, 1-1, p.4; Libya's Grade 11 Science book, Ch. 6, pp.113–133).
2. Compute the mean point (x̄, ȳ) of bivariate data and plot it — Cambodia's Grade 12 Basic book teaches bivariate statistics and the mean point in §5.1 (p.146), on a table of **6 babies** — masses 2.8, 2.9, 3.8, 3.6, 3, 3.7 kg and heights 38, 38, 42, 39, 40, 43 cm — taught corrected: the book's text says 8 babies, but its table has 6 columns (p.146, corrected as filed).
3. Compute Pearson's r and say what its sign and size mean, using Kuwait's strength bands: |r| in (0.7, 1] strong, (0.5, 0.7] medium, (0, 0.5] weak (Kuwait Grade 12 Term 1, 4-3, pp.182–193; Pakistan Statistics Class 12, Ch. 14, pp.200–202).
4. Rank paired data and compute Spearman's rank coefficient r_s = 1 − 6Σd²/(n(n² − 1)), including a case with tied ranks (Iraq Grade 11 Literary, Ch. 4, worked examples pp.116–117 — the verified pages only; Pakistan Statistics Class 12, Ch. 15, pp.236–237).
5. Fit the least-squares regression line ŷ = a + bx with b = s_xy/s²_x and a = ȳ − bx̄, know it passes through (x̄, ȳ), and use it to predict, stating the error of prediction (Pakistan Statistics Class 12, Ch. 14, pp.185–194; Kuwait Grade 12 Term 1, 4-3, pp.182–193).
6. State the coefficient of determination r² as the share of y's variation the line accounts for (Indonesia Grade 11, Bab 3, pp.79–130).
7. Say, in a whole sentence, why correlation does not imply causation, and name the limits of the linear model (Pakistan Statistics Class 12, Ch. 14, p.195 and p.206).
8. Say what analysis of variance (ANOVA) is for — comparing the means of more than two groups by splitting total variation into a between-groups part and a within-groups part — as the closing part (Laos Grade 12, Ch. 5, L16, p.175).

## What you need
Paper and a pencil.
Squared paper for scatter diagrams.
A calculator — Egypt's book computes Pearson's coefficient with calculator and spreadsheet tools (Unit 1, 1-1, p.4).

## The run of the lesson (in order)
1. **Do it first** — the learner plots Cambodia's six babies (mass against height), finds the mean point, and says in words whether heavier babies look taller — before any coefficient is named (lesson/lesson.md).
2. **The explanation** — scatter diagrams and the mean point; Pearson's r; Spearman's rank coefficient; the least-squares line, the two regression lines and prediction; the coefficient of determination; correlation is not causation and the limits of the line; closing part: ANOVA (lesson/lesson.md).
   - ADD IMAGE at the scatter part: a picture of a scatter diagram of the six babies with the mean point marked as a cross — the student says which way the cloud of points leans before reading on.
   - ADD GIF at the Pearson part: a picture of a scatter cloud tightening and loosening while r slides from 0 to 1 to −1 — the student calls out "strong", "weak", "none" as the cloud changes.
   - ADD GIF at the regression part: a picture of a line tilting on a scatter diagram while the squared errors shrink to their smallest total — the student watches why the least-squares line sits where it sits.
   - ADD IMAGE at the Spearman part: a picture of two rank columns with the differences d written between them — the student checks one d and one d² by hand.
3. **Say it to your companion** — describe a scatter in whole sentences, defend an r value, and argue both sides of "does this correlation prove a cause?" (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — scatter, r, ranks and the line in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — a full scatter with r computed, one Spearman ranking, one fitted line with a prediction and its error, and Iraq's regression points taught corrected (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- IMAGE — a picture of the six babies plotted, mean point marked → the student reads the cloud's direction.
- GIF — a picture of a scatter cloud tightening and loosening as r changes → the student names the strength at each stage.
- GIF — a picture of a line tilting until the squared errors are smallest → the student sees what "least squares" chooses.
- IMAGE — a picture of two rank columns with d and d² between them → the student checks a row by hand.
- VIDEO — the video-script filmed (made later) → the student plots along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Sees points but no pattern → plot the mean point first and split the picture into four quarters around it; points crowding the top-right and bottom-left quarters lean positive, the other pairing leans negative. Cambodia's book builds the picture around the mean point for this reason (§5.1, p.146).
- Computes r outside −1 to 1 → the arithmetic is wrong somewhere; r can never leave that range (Pakistan, Ch. 14, pp.200–202). Check the deviations before the sums.
- Mixes up the two regression lines → there are two: y on x for predicting y, x on y for predicting x; they both pass through (x̄, ȳ) and meet there (Pakistan, Ch. 14, pp.203–206). Predict with the line of the thing you want on the thing you know.
- Uses Iraq's Spearman introduction pages as a worked source → pp.113–115 of Iraq's Grade 11 Literary book were not read individually and are cited nowhere here; the worked Spearman ground is the verified examples at pp.116–117 and Pakistan's derivation (Ch. 15, pp.236–237).
- Reads a strong r as a proved cause → Pakistan's warning stands at p.206: correlation does not imply causation. A third quantity may drive both.
- Predicts far outside the data → the line is fitted to the data's range; Kuwait's falling-ball line predicts 52.52 m at t = 4 s for a ball dropped from 50 m, and the book never flags it — this lesson does: outside the range, a prediction is a guess wearing the line's clothes.
- This lesson's next door: Association of Attributes (Level 123, same stage) — the same "are these linked?" question for qualities instead of measurements.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Statistics Class 12, Ch. 14 and Ch. 15; Libya Grade 11 Science and Grade 12 Humanities; Indonesia Grade 11 (2021) and Grade 11 Edisi Revisi (2024); Yemen Grade 11 Science Part 2 and Grade 12 Literary; Egypt Statistics Grade 12; Greece W9, W11 and W13; Iraq Grade 11 Literary — with its p.124 regression points taught corrected as (4, 8.85) and (8, 5.05), and its Spearman introduction at pp.113–115 cited nowhere because those pages were not read individually — and Iraq Grade 10 Literary and Scientific at concept level; Cambodia Grade 12 Basic — with its p.146 baby table taught corrected as 6 babies, not 8; Jordan Grade 12 Business and Grade 10 — scatter and best-fit only in Grade 10, no correlation coefficient filed there; Kuwait Grade 12 Term 1; Laos Grade 12 for the ANOVA closing part). Two recorded negatives stand: South Africa teaches scatter plots only, with no regression or correlation, and Iran teaches none of this lesson's ground — neither is a source here. A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
