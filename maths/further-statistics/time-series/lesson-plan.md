# Lesson plan — Time Series

**Course:** Maths · **Stage:** Stage 16 — Further Statistics and Probability · **Lesson:** Time Series
**Place in the curriculum:** Level 124 of 136, the eighth lesson of Stage 16 — Further Statistics and Probability (maths/CURRICULUM.md).
**The one thing this lesson teaches:** a time series — values recorded in time order — pulled apart into its four components (trend, seasonal, cyclical, irregular), with the trend measured four ways (freehand, semi-averages, moving averages, least squares) and seasonal indices found by simple averages.
**This lesson's own level:** it stands on Averages and Spread (Stage 11) and on Correlation and Regression (Level 122, same stage) — means, and the least-squares line, are already in the learner's hands. It needs nothing else.

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

## Before this lesson
- Recommended first: Averages and Spread (Stage 11) — semi-averages and moving averages are means of pieces of the series. Recommended, never forced.
- Recommended first: Correlation and Regression (Level 122, same stage) — the least-squares trend is the regression line with time as x. Recommended, never forced.
- Recommended first: Collecting and Showing Data (Stage 11) — a time series is first of all a graph against time, Pakistan's historigram. Recommended, never forced.

## What the learner can do when it ends
1. Say what a time series is and draw its graph, the historigram, the way Pakistan's Statistics Class 12 book opens with the census populations of Pakistan, 1951–1998 (Ch. 16, p.241).
2. Name and tell apart the four components — trend T, seasonal S, cyclical C, irregular I — and walk a business cycle through trough, expansion, peak and recession (Pakistan, Ch. 16, pp.242–243; Libya, Grade 12 Humanities, Ch. 3, pp.59–88; Greece, EPAL Business Statistics, Ch. VII, pp.205–233).
3. State the two models, multiplicative Y = T × S × C × I and additive Y = T + S + C + I, and use a coded time variable (Pakistan, Ch. 16, pp.243–244).
4. Draw a trend by the freehand method and say what it can and cannot do (Pakistan, Ch. 16, pp.245–246; Libya, Ch. 3, pp.59–88).
5. Measure the trend by semi-averages, plotting the two half-means at their half-midpoints (Pakistan, Ch. 16, pp.247–250).
6. Smooth a series with moving averages, centred when the period is even (Pakistan, Ch. 16, pp.250–253).
7. Fit a least-squares trend with coded time, a = ȳ and b = Σxy/Σx², shift the origin, and say how a parabolic trend is compared by Σe² (Pakistan, Ch. 16, pp.253–261; Greece, Ch. VII, pp.205–233 — the linear trend).
8. Find seasonal indices by the simple-averages method and check they average to 100 (Libya, Ch. 3, pp.59–88 — Pakistan's chapter measures trend only and computes no seasonal index, as filed).
9. Read a series the way Iran's Grade 11 book files it, for study: compare two cities' rainfall by mean and standard deviation, and use interpolation inside the series and extrapolation beyond it, cautiously (Iran, Mathematics and Statistics (2), Grade 11, pp.63–70, filed "for study").

## What you need
Paper and a pencil, squared paper if you have it.
A ruler for the trend lines.
Numbers recorded over time — your own if you can: prices, rainfall, people passing a door, counted week by week.

## The run of the lesson (in order)
1. **Do it first** — the learner writes down something they know changes with time, guesses its pattern over a year, then meets the census series Pakistan opens with (lesson/lesson.md).
2. **The explanation** — what a time series is; the four components and the business cycle; the two models; then the trend four ways — freehand, semi-averages, moving averages, least squares (linear and parabolic); then seasonal indices by simple averages; closing with Iran's for-study reading, interpolation and extrapolation (lesson/lesson.md).
   - ADD IMAGE at the components part: a picture of one wavy series line pulled apart into four stacked lines — a rising trend, a yearly wave, a slow cycle, and random spikes → the student points at each line and names its component.
   - ADD GIF at the moving-averages part: a picture of a window of three points sliding along a jagged series, leaving a smooth line behind it → the student says each smoothed value as the window lands.
   - ADD IMAGE at the business-cycle part: a picture of a wave labelled trough, expansion, peak, recession in order around one turn → the student traces one full turn with a finger, naming the four stages.
   - ADD GIF at the seasonal-indices part: a picture of four quarter-bars rising and falling against a flat line at 100 → the student reads each quarter's index off its bar.
3. **Say it to your companion** — name the four components from a story, and defend a trend method against your companion's choice (lesson/lesson.md).
   - ADD VIDEO: the script in video-script.md, filmed — time series in the super-simple voice (made later, when videos are made).
4. **Questions** — from questions/: multiple-choice, short-answer, fill-in-the-blank, true-or-false, ordering, matching — served at the learner's level and teaching-mix (levels.md).
5. **Hands-on** — hands-on.md.
6. **Do It Yourself** — a moving average computed, a coded least-squares trend fitted and used, and seasonal indices found and checked (lesson/lesson.md).

## Add-ons for this lesson (the full list)
- IMAGE — a picture of a series pulled apart into its four component lines → the student names each component.
- GIF — a picture of a three-point window sliding along a series, leaving the moving-average line → the student says each smoothed value.
- IMAGE — a picture of a business-cycle wave labelled trough, expansion, peak, recession → the student traces one turn, naming the stages.
- GIF — a picture of four quarter-bars against the 100 line → the student reads each seasonal index.
- VIDEO — the video-script filmed (made later) → the student names the components along with it.

A slot the builder cannot fill yet stays in the plan as a slot — the
plan is the build sheet, so nothing the lesson needs gets forgotten.

## If the learner is stuck
- Mixes seasonal and cyclical → the seasonal wave repeats inside every year, on a fixed calendar rhythm; the cyclical wave is the long business swing, trough to trough, with no fixed length. Pakistan keeps the two apart in its components list (pp.242–243).
- Averages the whole series for semi-averages → split it in two halves first, mean each half, and plot each mean over the *middle* of its own half; the line joins those two plotted points (Pakistan, pp.247–250).
- Loses the ends with moving averages → that is the method, not a mistake: a 3-term moving average has no value at the first or last point, and an even period must be centred before it lines up with a time point (Pakistan, pp.250–253).
- Fits least squares with the raw years → code the time first: with the middle year as 0, Σx = 0 and the formulas shrink to a = ȳ, b = Σxy/Σx² (Pakistan, pp.253–261).
- Looks for a seasonal index in Pakistan's chapter → it is not there: Pakistan measures trend only, as filed. The seasonal indices in this lesson are Libya's (Ch. 3, pp.59–88).
- This lesson's next door: Index Numbers (Level 125, same stage) — another way of comparing values across time, against a base year.

## Teacher note
The full text is lesson/lesson.md; every part traces to a book and page in lesson/sources.md (Pakistan Statistics Class 12, Ch. 16 — trend only, no seasonal index computed there, as filed; Libya Grade 12 Statistics, Humanities — the seasonal indices by simple averages; Greece EPAL Business Statistics, Grade 11 — components and the linear trend for business use; Jordan Grade 12 Business Mathematics, Term 2 — time series and variance in time series; Iran Mathematics and Statistics (2), Grade 11 — the time-series lesson filed "for study", worded as filed). A teacher sending this lesson sends the lesson and its question list as they are — choosing, not remaking.
