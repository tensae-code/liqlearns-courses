# Maths course — CATCH-UP PLAN (2026-11-06)

Built under the user's EVERYTHING-GOES-IN ruling (2026-11-06,
commit 17e6715): every teaching item in every read book lands
in the course; a topic with no lesson gets a NEW lesson; a
country's own way of teaching a thing is content too.

## How this plan was made

Nine inventory sweeps read every maths filing in
`maths/books/*.md` (26 countries) plus the placements folders
(china-maths, pakistan-maths, iran-maths) and listed every
topic TAUGHT with book + printed-page evidence that none of
the 52 built lessons covers. The sweeps returned **358 topic
rows**; the same topic found by several sweeps merges into
one lesson here. Syria is excluded — its read is still
running and unverified; its catch-up sweep is owed when its
read lands. Result: **84 new lessons**, numbered 53–136
(the existing 52 keep their numbers; lesson = level, so the
course becomes 136 levels). New lessons extend existing
stages where a topic truly belongs, and six new stages
(13–18) stand after Stage 12.

## Decisions on the borderline calls (recorded, binding for builders)

- **Absolute value** — NO new lesson. The filings (Kuwait,
  Laos) teach absolute-value equations/inequalities inside
  equations/inequalities territory, and the merges keyed them
  there. The absolute-value *function* and its graph are
  stocked inside lesson 81 (step-and-piecewise-functions).
- **Heron's formula** — covered by perimeter-and-area. No new
  lesson.
- **Volumes of revolution** — CANNOT be built from verified
  sources: its only dedicated filing rows (Iraq G12 Sci
  [4-9]) are marked UNVERIFIED-BY-CHECK and may never be
  cited; everywhere else it appears only as an application
  inside integrals lessons. Listed in the could-not-build
  annex below.
- **Differentials / linear approximation** — an application
  inside derivatives (Laos G10 p.188). No new lesson.
- **Stem-and-leaf plots** — covered by
  collecting-and-showing-data. **Viète's relations and the
  discriminant** — covered by quadratic-equations.
  **Open sentences** — covered by expressions.
- **Unitary method** — BUILT (lesson 56): Pakistan and
  Bangladesh teach it as a named method.
- **Floor / sign / fractional-part functions** — BUILT
  (lesson 81): Iran, Nicaragua, Kazakhstan and Laos teach
  them as named special functions.
- **Cartesian product and relations** — BUILT as lesson 85
  (relations); the pure set-theory side stays in sets.
- **Locus basics** — inside coordinates-and-graphs; the
  construction of loci is BUILT as lesson 78.
- **Matrix cryptography** (Nicaragua G10 pp.243–244) — a
  two-page application of matrices, stocked as the closing
  part of lesson 93 (determinants-and-cramers-rule), not a
  standalone lesson.
- **Density and work rates** — stocked as parts of lesson
  116 (speed-distance-and-time): all three are compound
  rates, taught with the same triangle method in the books.
- **Geographic coordinates (latitude/longitude)** — one
  source (Greece G8); stocked as a part of lesson 64
  (scale-drawing-and-maps).
- **ANOVA** — stocked as a closing part of lesson 122
  (correlation-and-regression); its only full sources
  (Laos G12 L16, Kuwait) teach it beside correlation.
- **Z-scores and the empirical rule** — stocked inside
  lesson 118 (random-variables-and-distributions), with the
  normal distribution, where the books use them.
- **Population (demographic) statistics, data types,
  misleading statistics, randomised response** — stocked as
  parts of lesson 119 (sampling-and-sampling-distributions).
- **The German tank problem** — stocked as a part of
  lesson 120 (estimation-and-confidence-intervals).
- **Mendel's pea ratios as a probability model** — stocked
  as a part of lesson 130 (monte-carlo-and-simulation):
  testing a model against real counts.
- **Binomial series for negative/fractional powers**
  (Pakistan) — stocked as the closing part of lesson 106
  (the-binomial-theorem).

## Standing flags (apply to every builder)

- NEVER cite an item a filing marks UNVERIFIED-BY-CHECK.
  The full never-cite list: Iraq G12 Sci Rolle/MVT [3-2]
  and volumes of revolution [4-9]; Cambodia G12 Advanced
  guide's six sequence-limit answers; Ethiopia G12 examples
  at pp.330 and 380 and the p.170 variance set; Laos G8
  L14/L15 items; South Sudan P3 equivalent-fractions chain;
  Indonesia G12 Merdeka (2022) for Pascal's triangle
  (NOT FOUND there — cite the 2025 Revisi pp.113–118 or
  Grade 8 K13 instead).
- TEACHER-EVIDENCE stock (all Ghana rows; all Sierra Leone
  Primary rows; Cambodia skewness + deciles answers; Armenia
  G12 guide rows; Jordan G4 nets; South Sudan S1
  discount/commission; Ethiopia G1 calendar/patterns guides;
  Nepal G8 mismatch guides — cite the student books only;
  Laos old-series G1/G2 guides; Nicaragua G1 guide sorting;
  Kuwait G11 T1 workbook-only items) is worded as teacher
  evidence in sources.md and counted as such.
- Cambodia's five Khem Putthi G12 booklets are PRIVATE, not
  MoEYS — label PRIVATE wherever cited. Its Space Geometry
  booklet L1 answer key is unreliable as printed.
- Jordan's Grade 11 Term 1 exercise book is an ORPHAN
  WORKBOOK (companion student book not in hand) — cite as
  workbook evidence as filed.
- Book errors are taught CORRECTED, never as fact; each
  lesson's error-corrected values are in the inventory rows
  and the filings.
- Filings hold summaries only — never transcribe textbook
  passages. Questions are drawn from the books' own
  exercises as filed.

## The new lessons (number = level; folder = stage folder)

### Extensions to existing stages

**Stage 1 — Numbers** (folder `numbers`)
- 53 `number-bases` — Binary numbers and other bases
- 54 `numerals-of-the-world` — Roman numerals and the
  numeral systems of the world
- 55 `the-real-number-system` — The real number system and
  the laws of operations

**Stage 4 — Fractions, Decimals, Percentages, Ratio**
(folder `fractions`)
- 56 `unitary-method` — The unitary method
- 57 `variation` — Direct, inverse, joint and partial
  variation

**Stage 6 — Algebra** (folder `algebra`)
- 58 `polynomial-division` — Dividing polynomials: the
  remainder and factor theorems
- 59 `partial-fractions` — Partial fractions

**Stage 7 — Shapes and Angles** (folder `shapes-angles`)
- 60 `compass-constructions` — Constructions with ruler
  and compass
- 61 `constructing-triangles-and-quadrilaterals` —
  Constructing triangles and quadrilaterals
- 62 `tessellations` — Tessellations: tiling the plane
- 63 `platonic-solids-and-eulers-formula` — The regular
  polyhedra and Euler's formula

**Stage 8 — Measuring** (folder `measuring`)
- 64 `scale-drawing-and-maps` — Scale drawing and maps
- 65 `estimating-areas` — Estimating areas: counting
  squares and the trapezium rule
- 66 `equal-areas` — Equal areas: shapes that share a base
- 67 `cavalieris-principle` — Cavalieri's principle
- 68 `errors-and-accuracy` — Errors and accuracy: absolute,
  relative and percentage error
- 69 `temperature-and-traditional-measures` — Temperature
  and the measures people used before standard units
- 70 `projections-and-views` — Projections and views:
  drawing solids on paper

**Stage 9 — Further Geometry** (folder `further-geometry`)
- 71 `radian-measure` — Measuring angles: degrees, radians
  and gradians
- 72 `trigonometric-identities` — Trigonometric identities
- 73 `trigonometric-equations` — Solving trigonometric
  equations
- 74 `inverse-trigonometric-functions` — Inverse
  trigonometric functions
- 75 `three-dimensional-trigonometry` — Trigonometry in
  three dimensions
- 76 `bearings` — Bearings
- 77 `triangle-centres` — The special lines and centres
  of a triangle
- 78 `loci` — Loci: paths of moving points
- 79 `fractals` — Fractals: shapes inside shapes

**Stage 10 — Functions and Graphs** (folder
`functions-graphs`)
- 80 `coordinate-geometry` — Coordinate geometry: the
  section formula, distance to a line, the circle's
  equation
- 81 `step-and-piecewise-functions` — Step functions,
  the floor function and piecewise functions
- 82 `trigonometric-functions` — Trigonometric functions
  and their graphs
- 83 `polar-coordinates` — Polar coordinates
- 84 `special-sequences` — Special sequences: harmonic,
  arithmetico-geometric, square and triangular numbers

**Stage 11 — Statistics and Probability** (folder
`statistics-probability`)
- 85 `relations` — Relations: ordered pairs, the Cartesian
  product and equivalence relations
- 86 `carroll-diagrams` — Carroll diagrams

**Stage 12 — Advanced** (folder `advanced`)
- 87 `limits` — Limits
- 88 `continuity` — Continuity
- 89 `rolles-theorem-and-the-mean-value-theorem` — Rolle's
  theorem, the Mean Value Theorem and L'Hôpital's rule
- 90 `conic-sections` — Conic sections: parabola, ellipse,
  hyperbola
- 91 `geometry-in-space` — Geometry in space: lines and
  planes
- 92 `analytic-geometry-in-space` — Coordinates and
  vectors in space: equations of lines and planes
- 93 `determinants-and-cramers-rule` — Determinants and
  Cramer's rule
- 94 `de-moivres-theorem` — The trigonometric form,
  De Moivre's theorem and roots of complex numbers
- 95 `hyperbolic-functions` — Hyperbolic functions and
  their inverses
- 96 `taylor-and-maclaurin-series` — Taylor and Maclaurin
  series
- 97 `parametric-equations` — Parametric equations and
  parametric curves
- 98 `barycentres` — Barycentres: balancing weighted
  points
- 99 `quaternions` — Quaternions

### New stages after Stage 12

**Stage 13 — Logic and Proof** (folder `logic-and-proof`)
- 100 `mathematical-logic` — Mathematical logic:
  propositions, connectives and quantifiers
- 101 `proof-methods` — How mathematicians prove things
- 102 `mathematical-induction` — Proof by induction
- 103 `pigeonhole-principle` — The pigeonhole principle
- 104 `problem-solving-strategies` — Problem-solving
  strategies

**Stage 14 — Counting and Discrete Mathematics** (folder
`counting-and-discrete`)
- 105 `counting-principles` — Counting: permutations and
  combinations
- 106 `the-binomial-theorem` — The binomial theorem and
  Pascal's triangle
- 107 `inclusion-exclusion-and-venn-counting` — Counting
  with Venn diagrams: inclusion–exclusion
- 108 `graph-theory` — Graph theory: networks, paths and
  shortest routes
- 109 `congruences-and-diophantine-equations` —
  Congruences, Euclid's algorithm and Diophantine
  equations
- 110 `latin-squares` — Latin squares
- 111 `algebraic-structures` — Algebraic structures:
  groups, rings and fields
- 112 `mathematical-investigations` — Mathematical
  investigations: the balance search, the phone tree and
  the painted cube

**Stage 15 — Money, Time and Everyday Mathematics**
(folder `money-and-time`)
- 113 `money` — Money: notes, coins, paying and change
- 114 `business-mathematics` — Business mathematics:
  interest, profit, tax, partnership, insurance and more
- 115 `time-and-calendars` — Time and calendars: clocks,
  12 and 24 hours, and the calendars of the world
- 116 `speed-distance-and-time` — Speed, distance and
  time (with density and work rates)

**Stage 16 — Further Statistics and Probability** (folder
`further-statistics`)
- 117 `conditional-probability-and-bayes` — Conditional
  probability and Bayes' theorem
- 118 `random-variables-and-distributions` — Random
  variables and probability distributions
- 119 `sampling-and-sampling-distributions` — Sampling,
  populations and sampling distributions
- 120 `estimation-and-confidence-intervals` — Estimation
  and confidence intervals
- 121 `hypothesis-testing` — Hypothesis testing
- 122 `correlation-and-regression` — Correlation and
  regression
- 123 `association-of-attributes` — Association: the
  chi-square test, Yule's Q and the contingency
  coefficient
- 124 `time-series` — Time series
- 125 `index-numbers` — Index numbers
- 126 `quartiles-percentiles-and-box-plots` — Quartiles,
  deciles, percentiles and box-and-whisker plots
- 127 `mean-deviation-and-variation` — Mean deviation,
  quartile deviation and the coefficient of variation
- 128 `moments-skewness-and-kurtosis` — Moments, skewness
  and kurtosis
- 129 `geometric-and-experimental-probability` —
  Probability from area and from frequency
- 130 `monte-carlo-and-simulation` — Simulation and the
  Monte Carlo method
- 131 `odds` — Odds

**Stage 17 — Mechanics** (folder `mechanics`)
- 132 `statics` — Statics: forces in balance
- 133 `dynamics` — Dynamics: motion, momentum and energy

**Stage 18 — First Steps** (folder `first-steps`)
- 134 `position-and-direction` — Position and direction
  words
- 135 `sorting-and-classifying` — Sorting and classifying
- 136 `repeating-patterns` — Repeating patterns and
  pattern rules

## Sources per lesson (compact rows; builders verify against the filings)

Format: Country — book (grade) — printed pages — what is taught [flags].
Inventory detail lives in `liqlearns-courses-work/catch-up-maths/inventory-*.md`.

### 53 number-bases
- Sierra Leone — JSS3 L18–20; SSS1 L14–20 — full bases course: base-2/5/10 conversion, arithmetic in bases
- Laos — G6 (2010) L8 pp.56–64 — bases via base ten; 111011₂=59; base-5 examples; arithmetic in bases 2,3,4,5,7
- Bangladesh — C7 Exp.7 pp.141–160; C8 Exp.9 pp.189–206 — binary; radix point; (23.25)₁₀=(10111.01)₂; 1's/2's complements
- Nepal — G7 Unit 12; G8 Unit 11 — binary and bases
- Pakistan — G12 Statistics Ch.17 pp.281–284 — binary/octal/hexadecimal for computers (the rest of Ch.17 is computer history — not maths, excluded)

### 54 numerals-of-the-world
- Laos — G6 (2010) L1 pp.1–9 — Roman I,V,X,L,C,D,M with repetition/subtraction rules, conversions to MMMCMXCIX
- Ethiopia — G3 §1.5 p.15; G4 — Ge'ez numerals to 100 (G1–G2 student books do NOT teach it)
- Nepal — G-books as filed — Devanagari digits; lakh/crore naming
- Bangladesh — C6 Ch.1 pp.1–14 Roman; C3 Ch.1 Ayut/lakh; C4 §§1.1–1.2 pp.2–18 ajut/lac/nijut/crore, grouping 1,00,000
- Cambodia — G1 Khmer numeral stroke order; G2 words; G4 "saen"
- Laos — G1 (new) Ch.18 p.154 — Lao digits ໐–໙
- South Africa — G5/G6 workbooks — ancient Egyptian numerals
- Jordan — G3 p.20 — Hindi/Indian numerals
- Sierra Leone — JSS3 — Roman numerals; South Sudan — Roman 1–50; Vietnam — G3 Bài 47 p.12 Roman, "getting to know" only
- Kazakhstan — old Slavic letter numerals [extra reading, OPTIONAL as filed]

### 55 the-real-number-system
- Pakistan — G8 Unit 1 pp.1–3, 6–9 — N⊂W⊂Z⊂Q⊂R, irrationals, π≠22/7; properties stated and checked (closure, commutative, associative, distributive, identities, inverses)
- Pakistan — G5 pp.13–15, 31–38; G6 pp.32–33, 38–39; G7 pp.16–19 — verifying the laws for whole numbers, fractions, integers, rationals

### 56 unitary-method
- Pakistan — G5 pp.89–90 — the unitary method as a named method: many → one → many
- Bangladesh — Class books as filed — unitary method

### 57 variation
- Sierra Leone — SSS2 L17–20 — joint and partial variation
- Jordan — G-books as filed — direct/inverse base forms only
- Pakistan — Class 10 Variations unit pp.49–73 — full variations treatment

### 58 polynomial-division
- Ethiopia — G10 Unit 2 — division; remainder and factor theorems PROVED
- Indonesia — G11 TL Revisi (2024) Bab 2 pp.70–88 — division algorithm, long division, Horner; remainder theorem; factor theorem; rational-zero theorem
- Pakistan — G11 Unit 9 pp.169–176 — long + synthetic division; remainder/factor applications
- Yemen — G10 Pt1 Unit 4 pp.88, 92 — remainder/factor theorems used; zeros
- Bangladesh — C9–10 Ch.4 §§8.3/9/10.1 pp.96–102 — division; Remainder Theorem; Factor Theorem
- Laos — G9 Ch.1 L3 p.10; G11 Ch.1 L3–L5 pp.10, 15, 19 — long + synthetic division; roots
- Nicaragua — G8/G10 — division incl. synthetic; Iran — G9 pp.126–129; Cambodia — G10 Pt1 pp.78–90 + GCD/LCM of polynomials; Egypt — G7 algebraic long division; Greece — G9/G11 division (theorems not named there)
- Kuwait — G11 T1 WORKBOOK ONLY Unit 3 pp.43–48 [workbook evidence — student book not in hand]

### 59 partial-fractions
- South Sudan — S4 Additional Unit 4 pp.126–148 — full treatment [worked example pp.130–131 is muddled; final answers A=3/4, B=−1/4 correct — teach the method, not that working]
- Pakistan — G11 Unit 5 pp.78–87 — Cases I–IV incl. repeated irreducible quadratic; G12 Ch.3 §3.5 — inside integration
- Bangladesh — C9–10 Ch.4 §10.8 pp.107–111 — distinct/repeated linear; linear+quadratic; division first for improper
- Jordan — G12 p.23; integration use p.45 [orphan workbook rows as filed]
- Kuwait — G12 T2 5-6 pp.42–49 — distinct linear factors ONLY [negative: no repeated/quadratic]

### 60 compass-constructions
- Sierra Leone — SSS2 L79–91 — full construction course; JSS1 — first constructions
- Laos — G6 (2010) L12–L14, L18, L20 pp.87–107, 136–166 — parallels/perpendiculars through a point; perpendicular bisector; copying angle/segment
- Iran — Geometry (1) pp.10–16 — constructions WITH justifications
- Kazakhstan — six sources as filed; Greece — G3/G7/W5; Nicaragua — G7/G6/G3; Ethiopia — G5/G6; Nepal — G6/G7/G9/G10
- Laos — G4 L21 p.56 using a compass; G5 Ch.3 L15 pp.30–43 ruler-and-compass figures
- Bangladesh — C4 Ch.14 pp.155–160; C7 Exp.5 pp.104–124; Kuwait — G7 T2 Unit 6 pp.63–128; G8 T2 L5-2 p.26
- Yemen — G3 Pt1 p.92 segment of given length; G5 Pt2 Unit 8 pp.137–160 — segments, angles, triangles, parallelograms, rhombuses
- Pakistan — G6 pp.139–143; G7 pp.142, 144–147; Libya — G5 Unit 15 pp.221, 225; G8 §§3-2/4-4/4-7 pp.74, 84, 93
- Armenia — Geometry 7 Ch.II §10, §17 pp.34–76, 107–140 — constructions as a method; the stages of a construction problem
- Cambodia — G5/G6/G8; South Africa — G6–G9 workbooks; Egypt — G7 T2; Jordan — G6

### 61 constructing-triangles-and-quadrilaterals
- Pakistan — G8 pp.161–170 — quadrilaterals (square, rectangle, rhombus, parallelogram, kite, trapezium); triangles SSS/SAS/ASA/RHS; incentre/circumcentre constructions
- Bangladesh — C8 Exp.5 pp.93–124 — constructing quadrilaterals
- Yemen — G4 Pt2 pp.100, 103 — rectangle from length/width; square; G5 Pt2 8-3 p.145 — triangle, two sides + included angle, 5 steps
- Sierra Leone — SSS2 construction course rows; South Sudan — P5–P8 constructions incl. incentre/circumcentre (P8)

### 62 tessellations
- Laos — G5 (2009) Ch.10 L49–L50 pp.112–123 — translation+reflection tilings; rotation 90°; hexagon tessellation
- Greece — G1/G3 — tessellation; South Africa — G4/G5 + glide reflection
- Pakistan — G7 p.163 — tessellation defined; Libya — G8 p.126; G9 pp.134, 137–153
- Nepal — G6/G7 [G8 guide is a MISMATCH guide — TEACHER-EVIDENCE only]; Iraq — G2/G6

### 63 platonic-solids-and-eulers-formula
- Nicaragua — G10 Unit 6 pp.304–308 — the five regular polyhedra
- China — A版 Ch.8 review; B版 Ch.11 pp.66–72 — Euler's formula V+F−E=2 as exploration and review exercise
- Armenia — Geometry 10 Ch.II p.74 — Euler's formula in the polyhedra chapter
- Greece — Ch.13 regular polyhedra; South Africa — G8/G9

### 64 scale-drawing-and-maps
- Laos — G6 (2010) L16, L21–L22 pp.116–128, 167–182 — scale = map ÷ real; bar scales; 1 cm = 5 km → 1:500,000; G5 (2009) L52 pp.124–129; G7 L43; G9 L6 p.25 (minor)
- Kuwait — G10 T1 project p.81 — Kuwait Towers model at 1:500; 2-1 pp.82–96 scale drawing worked
- Libya — G8 §2-8 p.41 — scale drawing and maps as its own section
- Vietnam — G5 v1 Bài 37 p.8 — map scale and applications; Mauritania — G6 p.81
- Yemen — G6 Pt2 5-3 p.17 enlargement/reduction; 5-4 p.23 scale drawing
- South Africa — map work/grid position G3–G6; Nepal — G7 compass points [NOT three-figure bearings there]
- Greece — G8 — latitude/longitude (part: geographic coordinates)
- Jordan — scale drawing rows as filed

### 65 estimating-areas
- South Sudan — S4 pp.20–29 — counting squares; the mid-ordinate rule; the trapezium rule for irregular areas [sole source]

### 66 equal-areas
- Yemen — G8 Pt2 Unit 7: 7-7 p.87 equivalence of triangles; 7-8 p.94 equivalence of parallelograms — "equivalent" = equal area (checker-corrected: NOT congruence)

### 67 cavalieris-principle
- China — B版必修四 Ch.11 §11.1.6 p.82 — Zu Geng's principle named; A版必修二 Ch.8 §8.3 pp.121–123 — as inquiry: V=Sh, V=⅓Sh

### 68 errors-and-accuracy
- Kazakhstan — G7 books as filed — absolute and relative error
- Sierra Leone — SSS2 L7–8 — percentage error; degree of accuracy

### 69 temperature-and-traditional-measures
- Nepal — G-books as filed — °C/°F; ropani/aana/katha land units
- South Africa — G5–G7 thermometers [South Sudan P7 guide prints conversion formulas WITHOUT the 32 offset — do not cite that guide]
- Mauritania — 6AS-LO Ch.1 pp.8–13 — traditional Islamic measures: cubit ≈49.5 cm, farsakh, raṭl ≈312.5 g, ṣāʿ ≈2.5 L; 5AS-LO Ch.1 p.9
- Nicaragua — body units jeme/brazada/paso; vara/manzana; Kazakhstan — old Kazakh units
- Laos — G5 (2009) L31 pp.76–89 — traditional Lao mass units baht, salung, hun, and the carat

### 70 projections-and-views
- Vietnam — G11 study book Chuyên đề 3: Bài 11 p.52 orthogonal + axonometric projections; Bài 12 p.68 technical drawing
- Laos — G7 Part 7 L44 pp.203–226 — projections and shadows; a birdhouse from different viewpoints
- North Macedonia — G8 (2010) Theme 4 pp.168, 171 — parallel and orthogonal projection; representing a solid by drawing
- China — A版 Ch.8 reading pp.112–113 — descriptive geometry and Monge [reading as filed]
- Jordan — G8 nets/views/cross-sections; South Africa — G6/G9 perspective drawing (enrichment part)

### 71 radian-measure
- Bangladesh — C9–10 Ch.7 §11 pp.175–177 — radian measure; s=rθ; 360°=2π
- Laos — G10 Ch.IX L22 pp.233–250 — directed angles and radians; coterminal angles
- Nicaragua — G10 + module — sexagesimal DMS and centesimal gradian systems
- Nepal — G9 Optional §2.1 — angle-measure systems; Jordan — G11 p.8 radian measure

### 72 trigonometric-identities
- Pakistan — G11 Unit 10 pp.177–199 — fundamental law cos(α−β) proved on the unit circle; addition/double/half/triple proved [ERROR-CORRECTED: p.184 cot(−225°)=−1, not 1]
- Libya — G12 (Science) Ch.2 pp.37–54 — compound/double/half; a·cosθ ± b·sinθ as a single term; proving identities
- Yemen — G11 Sci Pt2 Unit 9 pp.91, 97, 104 — sum/difference; double/half; sum↔product
- Laos — G10 Ch.IX L22 pp.233–250 — cos(a−b) proved by dot product; full formula chain
- China — B版必修三 Ch.8 §8.2 pp.87–110 — the identity chain proved link by link
- Armenia — G10 Ch.4 §§7–9 pp.100, 103, 116; Kazakhstan — four G9 formula cycles (identities only); Egypt — G10; Pure G11 sum/difference/double
- Cambodia — G11 Basic formulas; Iran — five books; Jordan — G12 Unit 2; G10 p.88; Ethiopia — G10 Unit 4; Indonesia — G11 TL Revisi pp.139–141 [pp.136–138 basics sit in functions]; Kuwait — G10 T2 pp.95–113; G11 T2 pp.82–113; Vietnam — G11 v1 Bài 2 p.17

### 73 trigonometric-equations
- Nicaragua — G10 — trig equations (equations rest mainly here per sweep B)
- Laos — G11 Ch.8 L31 p.237 equations; L32 p.244 inequalities on the unit circle (cos(2x−π/4) ≥ √3/2)
- Armenia — G10 Ch.4 §§10–11 pp.119, 133 — trig equations; main solving methods
- Libya — G12 Ch.2 (equations of the a·cosθ ± b·sinθ form); G11 Ch.3 pp.71–92 — simple identities, equations, graphs
- Yemen — G11 Sci Pt2 9-5 p.108 — trigonometric equations
- Kuwait — G10 T2 pp.103–106; G11 T2 pp.92–99; Cambodia — G11 Basic + G11 Adv equations; Vietnam — G11 v1 Bài 4 p.31; South Sudan — S4 Additional equations; China — B版 Ch.7 solving from graphs

### 74 inverse-trigonometric-functions
- Nicaragua — G10 pp.133–141 — full treatment
- Armenia — G10 Ch.4 §12 p.145 — inverse trig functions (arcsine/arccosine/arctangent/arccotangent from §10 p.119)
- Cambodia — G12 Adv §3.2 p.54 [filed from contents+guide; section start not read in detail — word as filed]
- Laos — G12 Ch.8 L24 p.227 — inverses of trigonometric functions

### 75 three-dimensional-trigonometry
- Jordan — G10 Unit 4 L5 p.124 — 3-D trigonometry [sole full source]

### 76 bearings
- Sierra Leone — SSS2 L117–124 — full bearings course
- Libya — G11 (Science) Ch.2 pp.42–68 — bearings with the sine/cosine rules
- Nepal — G8 — three-digit bearings [the G8 GUIDE is a mismatch guide — cite the student book only]
- Jordan — G10 p.100; South Sudan — S1

### 77 triangle-centres
- Kuwait — G9 T2 Unit 7 pp.140–190 — mid-segment theorem; median to hypotenuse; circumcentre; incentre; orthocentre; centroid 2:1 [ERROR-CORRECTED: G10 T2 p.23 "Circum Center" should read Incenter]
- Laos — G7 Part 5 L33 — notable lines; balancing a paper triangle to find the centroid; OA=OB=OC
- Yemen — G8 Pt2 Unit 7 pp.65, 70, 74, 77, 79, 83 — side–angle relations; midsegment; hypotenuse-midpoint; 30°-side theorem; medians; altitudes; Unit 6 pp.23, 31, 36 Thales + bisectors
- Cambodia — G8 L16 — full concurrence system; Egypt — G8 medians/centroid; Greece — centroid/orthocentre
- Iraq — G9 centroid p.116; Jordan — G9 Unit 5; Sierra Leone — mid-point/bisector theorems; Kazakhstan — G8 §1.7 + G9 §20 excircles

### 78 loci
- Sierra Leone — SSS2 L92–96 — loci
- Kazakhstan — Smirnov §21; Turapbekov — loci
- Iran — locus catalogue inside the conics material

### 79 fractals
- China — B版必修四 Ch.10 reading pp.40–41 — Julia/Mandelbrot from z→z²+c; G9 v2 reading pp.45–46 — Sierpiński carpet/triangle, Koch snowflake [readings as filed]

### 80 coordinate-geometry
- Jordan — G9 pp.168–177 — distance from a point to a line; coordinate proof; G10 p.54 — equation of a circle
- Ethiopia — G10 §7.5 — equation of a circle [its G10 guide does NOT cover §7.5]
- South Sudan — S4 pp.30–40 — the circle's equation
- Kuwait — G10 T2 9-2 pp.124–130 — the section formula: internal/external division
- Laos — G9 Ch.4 L32 p.150 — section formula (minor); Iran — analytic circle

### 81 step-and-piecewise-functions
- Iran — three books as filed — the floor (greatest-integer) function; piecewise definitions
- Nicaragua — G10 pp.269–271 — step functions
- Kazakhstan — [x] and {x} notation; Laos — G10 L10 p.83 — floor [x] and sign sgn(x)

### 82 trigonometric-functions
- China — B版必修三 Ch.7 pp.1–68 — trig functions of a general angle; y=sin x, y=A sin(ωx+φ), cos, tan graphed; tide models [the filing itself flags: no trig-functions slug exists]
- Pakistan — G11 Unit 11 pp.200–217 — all six functions; domains/ranges; periodicity; a+b sin(cθ+d); Ferris wheel and tides
- Iraq — G10 Sci Ch.4; G11 Sci Ch.4 — circular functions incl. cot/sec/csc; the winding mapping
- Greece — W6 Ch.3 — trig functions of any angle; Iran — periodicity/tangent; Vietnam — G11 v1 Bài 3 p.22
- Ethiopia — G10 trig graphs; South Sudan — S4 pp.41–45 trig graphs

### 83 polar-coordinates
- Bangladesh — C9–10 Ch.7 §10.2 pp.173–175 — P(r,θ); x=r cos θ, y=r sin θ [ERROR-CORRECTED: E15 p.174 r=2, P(2,150°), not r=√5]
- Kuwait — G11 T2 7-2 pp.25–32 — polar coordinates (trig form of complex numbers is stocked in lesson 94)

### 84 special-sequences
- Pakistan — G11 Unit 6 pp.88–122 — arithmetico-geometric progressions (sum to n and ∞); harmonic progressions; harmonic mean
- Mauritania — harmonic and arithmetico-geometric sequences as filed
- Sierra Leone — Primary 6 — square/cube/triangular numbers [TEACHER-EVIDENCE]

### 85 relations
- Libya — G10 Pt1 Ch.1 pp.9–43 — Cartesian product; binary relations; domain/range; inverse relation
- Yemen — G7 Unit 1 pp.32, 34, 37 — ordered pair; Cartesian product (S×T ≠ T×S); relations; G9 Pt1 Unit 1 pp.17, 25 — transitive relations; equivalence relations
- Bangladesh — C9 §1.9 p.24 Cartesian product (minor); Kuwait — G8 T1 Unit 1 pp.15–67 (minor); Laos — G10 Ch.II L4/L6 (minor)

### 86 carroll-diagrams
- Kuwait — G4 T1 4-10 p.158 — Carroll diagrams
- Laos — G6 (2010) L25 pp.193–197 — Carroll vs Venn (Carroll 1832–1898, Venn 1834–1923 credited)
- North Macedonia — G1 (2022) pp.157–158 — Carroll diagram (fish / not a fish × colour); China — Carroll diagrams as filed

### 87 limits
- Greece — W12 Ch.1 pp.11–90 — limits as a full chapter
- Pakistan — G11 Unit 12 pp.218–236; G12 Ch.1 ch-pp.18–31 — limit theorems; sandwich theorem; sinθ/θ→1 [ERROR-CORRECTED: G12 p.25 limit at ∞ is −∞, not ∞]
- Libya — G11 (Science) Ch.5 pp.111–138 — indeterminate values; one-sided limits; limits at infinity
- Vietnam — G11 v1 Ch.V pp.104, 111 — limits of sequences; limits of functions
- Armenia — G11 Ch.3/4 — sequence limits built from infinitesimals; the number e
- Iran — Hesaban (1) pp.113–151 (no ε-δ) + three more books; Egypt — Pure G11 Unit 3 + General abridged
- Cambodia — G11 Basic; G12 Basic ε-δ [ERROR-CORRECTED: 369/4; thresholds ≈11.1/−8.1]; Limits booklet [PRIVATE]; G12 Adv sequence limits [guide's six sequence-limit answers UNVERIFIED-BY-CHECK — NEVER cite]
- Kuwait — G12 (sci) T1 Unit 1 pp.12–47 [ERROR-CORRECTED p.47 tables: sin x/x at 37π/7 ≈ −0.0471; cos x/x at 100 = +0.00862; at 450 = −0.00162256]
- Laos — G10 Ch.VI L16 pp.166–175; South Sudan — S4 Additional Unit 1 pp.1–66; Indonesia — G12 TL Bab 2 pp.65–96; TL Revisi A.1 pp.82–96; Yemen — G11 Sci Pt1 5-1 p.118; G11 Lit 4-1 p.87; Mauritania — streams as filed; Nepal — G9 Optional (Nepal stops at continuity)
- Jordan — G11 p.50 [orphan WORKBOOK rows as workbook evidence]

### 88 continuity
- Kuwait — G12 (sci) T1 1-5/1-6/1-7 pp.48–71 — continuity; theorems; continuity on an interval
- Laos — G10 L16 pp.166–175 — the three conditions; worked discontinuities
- Armenia — G11 Ch.4/5 §§1–2 — continuity of a function; of elementary functions
- Vietnam — G11 v1 Bài 17 p.119 — continuous functions; Libya — G11 Ch.5 close + Ch.6 pp.139–160
- Pakistan — G11 Unit 12; G12 Ch.1 ch-pp.32–35 — three conditions; removable/jump discontinuities
- Yemen — G11 Sci Pt1 5-2 p.133; G12 Sci 6-1 p.154 (trig functions); Indonesia — TL Revisi Definisi 2.2 p.96; Nepal — G10 Optional continuity

### 89 rolles-theorem-and-the-mean-value-theorem
- Greece — W12 — Rolle; the Mean Value Theorem; Ch.2 — L'Hôpital's rule
- Cambodia — Derivatives booklet pp.50–52 — both theorems PROVED [PRIVATE booklet — label]; L'Hôpital + approximation rows from the booklets
- Yemen — G12 Sci Unit 6, 6-7 — Rolle + MVT, contents/PDF p.183 (footer 184; cite contents/PDF numbers for this book from 6-4 on)
- Iraq — G12 Sci [3-2] is UNVERIFIED-BY-CHECK — cited NOWHERE in this lesson

### 90 conic-sections
- Greece — W7 Ch.3 pp.79–134 — full conic course
- Iraq — G12 Sci pp.48–89 full; G11 Sci pp.39–53 circle only
- Pakistan — G12 Ch.6 ch-pp.1–78 — cone-cutting; focus–directrix with e; tangents/normals; general second-degree [ERROR-CORRECTED: latus rectum 8/3 not 4/3; hyperbola c²=41, foci (±√41,0), e=√41/4; parabola focus (−1/26, 3/52)]
- Laos — G10 Ch.XI L24–L28 pp.278–308 — MF/MH=e; y²=4cx; ellipse a²=b²+c²; hyperbola asymptotes
- Kuwait — G12 T2 Unit 7 pp.100–133 — parabola/ellipse/hyperbola + eccentricity as its own lesson
- Yemen — G12 Sci Unit 4 pp.104–129 — conics as loci; translation AND rotation of axes
- Indonesia — G12 TL Bab 1 pp.1–64; TL Revisi ellipse pp.18–37 full, parabola (enrichment) pp.68–77 full [hyperbola EQUATIONS not taught in Revisi — definition/elements only, p.77 external link; do not cite Revisi for hyperbola equations]
- Vietnam — G10 v2 Bài 22 p.48; G10 study book pp.39, 47, 54, 57 (one lesson per conic + unification)
- Iran — Geometry (3) pp.34–60 ellipse geometric + parabola y²=4ax [hyperbola explicitly NOT taught there]; Maths (3) pp.122–142
- Cambodia — G12 Basic Ch.6 [ellipse/hyperbola evidence is contents+guide+answers; section starts not read in detail — word as filed; ERROR-CORRECTED vertex (0,−5)]
- Nicaragua — G11 pp.98–117 origin-centred only; Mauritania — 7AS-C Ch.14 p.169; Nepal — §8.3 introduction ONLY (minor)

### 91 geometry-in-space
- China — B版必修四 Ch.11 pp.82–120; A版必修二 Ch.8 pp.121–160 — three basic facts + corollaries; skew lines; parallelism/perpendicularity criteria and properties
- Armenia — Geometry 10 Ch.I pp.5–46 — axioms of stereometry; positions; line ⊥ plane
- Vietnam — G11 v1 Ch.IV pp.70, 78, 84, 88, 95; v2 Ch.VII pp.27, 31, 38, 44, 54 — synthetic theorem system
- Kuwait — G11 T2 Unit 10 pp.116–149 — postulates; skew lines; three-perpendiculars theorem; dihedral angle; perpendicular planes [synthetic only — no vectors/coordinates for Kuwait]
- Greece — W5 Vol.B Ch.12; Iraq — G11 Sci Ch.7; G12 Sci Ch.6; Yemen — G11 Sci Pt2 Unit 8 pp.65–78; G12 Sci Unit 5 pp.133–147 (dihedral angle p.147)
- Cambodia — G10 Ch.11; Space Geometry booklet [PRIVATE; L1 answer key unreliable]; Kazakhstan — Smirnov Geometry 10 + Soltan solutions manual [worked-solutions manual; parent textbook not held — word as filed]
- Laos — G11 Ch.10 L35–L38 pp.261, 266, 272, 281; North Macedonia — G8 Theme 4 pp.160–171 (basic positions only); Iran — Geometry (1) pp.77–96

### 92 analytic-geometry-in-space
- Egypt — Pure G12 Units 3–4 — analytic 3-D: vectors in space, cross and mixed products, direction cosines, lines/planes
- Laos — G10 Ch.X L23 pp.251–277 — octants; distance in R³; direction cosines; 3-D dot product; G12 Ch.10 L28–L29 pp.270, 278 — equations of lines and planes; line–plane angle
- Cambodia — G11/G12 Adv vectors in space; Jordan — G12 vectors/lines in space

### 93 determinants-and-cramers-rule
- Egypt — G10 old 1-4/1-5 — determinants; Cramer's rule
- Cambodia — G11 Basic Ch.4 L2 — 3×3 determinants; Cramer
- Kuwait — G10 T2 7-4/7-5 pp.74–82 — 2×2 determinant; inverse-matrix and Cramer solutions
- Laos — G12 Ch.3 L8 p.67; L10 p.96 — determinants and inverse matrices; AX=B ⇒ X=A⁻¹B
- Nicaragua — G10 pp.243–244 — matrices used for codes (closing application part)

### 94 de-moivres-theorem
- South Sudan — S4 Additional Unit 6 pp.178–195 — polar form; De Moivre; roots [ERROR-CORRECTED: cube roots of 8 are 2, −1+i√3, −1−i√3; guide identity sin 3θ = 3 sin θ − 4 sin³θ]
- Laos — G12 Ch.4 L13 p.134 — trig form; De Moivre; nth roots
- Kuwait — G11 T2 7-2 pp.25–32 — trig form; division in trig form [negative: NO De Moivre, NO nth roots for Kuwait]

### 95 hyperbolic-functions
- Laos — G12 Ch.7 L19–L22 pp.207, 210, 217, 221; Ch.8 L25 p.243 — hyperbolics, graphs, domains/ranges; inverse hyperbolics
- Pakistan — G12 Ch.1 ch-pp.10–11 (definitions, log forms); Ch.2 ch-pp.61–66 (derivatives; inverse hyperbolics) [ERROR-CORRECTED: d/dx cosech x = −coth x cosech x; d/dx sech x = −sech x tanh x — the p.62 summary drops the minus signs]

### 96 taylor-and-maclaurin-series
- Pakistan — G12 Ch.2 §2.17 ch-pp.74–81 — Maclaurin for 1/(1+x), sin x, aˣ, eˣ, (1+x)ⁿ; Taylor: ln(1+x) about x=2; sin 31° ≈ 0.5150 [sole full source]

### 97 parametric-equations
- Cambodia — G12 Adv Ch.9 pp.235–252 — parametric equations; projectile motion [teach v₀ = 48 cm/s, not the guide's 45]
- Mauritania — 7AS-C Ch.13 p.159 — parametric curves

### 98 barycentres
- Mauritania — 5AS-M Ch.6 p.57; 5AS-D Ch.6 p.47; 6AS-M Ch.4 p.51; 6AS-C Ch.4 p.51 — barycentre chapters in four streams
- Laos — G11 Ch.9 L33 p.249; L34 p.254 — barycentre of two points; of a system; α·GA+β·GB+γ·GC=0

### 99 quaternions
- China — B版必修四 Ch.10 extended reading pp.47–48 — a+bi+cj+dk; i²=j²=k²=−1; non-commutative multiplication [extended reading as filed]

### 100 mathematical-logic
- Laos — G10 Ch.I L1–L3 pp.1–29 — propositions; connectives ∧ ∨ xor ⇒ ⇔ ¬; truth tables (2ⁿ rows); series/parallel circuit models; equivalence; De Morgan; contrapositive; tautology/contradiction; open sentences; ∀/∃ and their negations
- Armenia — G12 logic book pp.9, 14, 19, 24, 36, 52 — statements; logical sum/product + negations; definition/axiom/theorem; converse/opposite; necessary/sufficient conditions; G11 pp.42–43 / pp.51, 58
- Iraq — G10 Sci Ch.1 pp.4–20; Greece — G10 pp.9–12; Cambodia — G10 Pt1 pp.2–17 (De Morgan p.17)
- Yemen — G10 Pt1 Unit 1 pp.7–22 — propositions, connectives, equivalence, inference, quantifiers
- Sierra Leone — SSS2 L41–48; Iran — two G11 books; Vietnam — G10 v1 Ch.I Bài 1 p.5; Kazakhstan — primary statements/logic problems

### 101 proof-methods
- Kazakhstan — Geometry 7 books — the Euclidean deductive method as a course opening
- Iran — Discrete pp.2–8; G9 pp.33–58; Geometry (1) pp.17–28
- Armenia — G11 pp.63, 68, 72 — deductive/inductive reasoning; proof and refutation methods; G12 p.30 — proving/refuting ∀ and ∃ assertions; Geometry 7 §§ within pp.34–76 — first proof by contradiction
- Greece — W5 Vol.A Ch.1 — the deductive method; Egypt — G7 "Steps to Write a Proof" p.81
- Nicaragua — G8/G9 — two-column proofs; Kuwait — G9 T2 Unit 7 givens/required/proof format; Laos — G10 L3 pp.20–29 — validity, modus ponens/tollens, the affirming-the-consequent fallacy; China — G6 review pp.100–104 — opposite-angles proof

### 102 mathematical-induction
- Pakistan — G11 Unit 8 pp.140–150 — principle; Euler's n²−n+41 counter-example warning; series/divisibility proofs; extended induction
- Armenia — G11 p.51; pp.87, 94 — method + applications
- Vietnam — G10 study book Bài 3 p.25 (Bài 4 p.32 proves Newton's binomial by it)
- Greece — W7 Ch.4; Cambodia — G11 Adv pp.24–34; Kazakhstan — four G9 books; Laos — G11 Ch.2 L7 p.28 — the three steps
- Iraq — G12 Sci pp.42–43 [filed "for information only" — word as filed]

### 103 pigeonhole-principle
- Iran — Discrete pp.82–84
- China — G6 下册 U5 pp.68–71 — drawer principle; 7÷3=2…1; Dirichlet box
- North Macedonia — G8 (2010) Theme 3 unit 8 pp.153–155 — 30 pupils / 9 error counts ⇒ ≥4 share
- Kazakhstan — G8 starred §6.5 [OPTIONAL as filed — word as filed]

### 104 problem-solving-strategies
- Iran — G7 Ch.1 — eight named strategies; G1–G6 per-chapter strategy lessons
- Greece — G5 Ch.3 pp.11–12 five steps; G2 Ch.5; Iraq — G1 plan-lesson in every chapter through G8
- China — G2 下册 U9 pp.109–112 — elimination tables; proto-Sudoku 4×4; G4 下册 U9 pp.103–107 — chickens-and-rabbits by listing and the assumption method; G3 p.114 — differencing (bottle + cups); G6 review pp.100–104 — 0/1 tables, symbol substitution

### 105 counting-principles
- Pakistan — G11 Unit 7 pp.123–139 — fundamental principle; ⁿPᵣ; repeats; circular (n−1)! and (n−1)!/2; ⁿCᵣ with proof [ERROR-CORRECTED: p.134 example = 6,160, not 36,960]
- Kuwait — G8 T2 L8-1 pp.180–191; G10 T2 10-4 pp.183–191; G11 T2 11-1 pp.152–161 (circular); G11 Statistics T2 5-1 pp.52–62
- Yemen — G12 Sci Unit 2 pp.45–55; G12 Lit Unit 1 pp.6–16 (3×2=6; P(4,4)=24; C(4,2)=6)
- Vietnam — G10 v2 Ch.VIII pp.60, 66; Mauritania — counting chapters in seven streams (3AS p.255; 5AS-M p.155; 5AS-D p.89; 6AS-M p.171; 6AS-C p.192; 6AS-D p.147; 6AS-LM p.67; 7AS-LM p.81)
- Indonesia — G12 Bab 3 pp.89–148; G12 Revisi Bab 3 pp.81–122; China — G3 下册 U8 pp.101–105 (systematic listing; 4 teams → 6 matches)
- Iran — three books; Egypt — Pure + General G11; Cambodia — G10 Pt2 Ch.8 + Probability booklet [PRIVATE]; Kazakhstan — four G9 books + primary option-trees; Nicaragua — G10/G11; Iraq — G9 p.147; G11 Sci Ch.8; G12 Lit Ch.1; Jordan — G11 p.120; G8 p.161; Ethiopia — G11 Unit 8; South Sudan — S4 pp.56–59; Laos — G11 Ch.6 L27 p.169
- Armenia — G12 guide Ch.2 [TEACHER-EVIDENCE — student book not held]

### 106 the-binomial-theorem
- Egypt — Pure G12 Unit 1; Iraq — G11 [8-6]; G12 Lit 1-5; Kazakhstan — G9 books; Ethiopia — G11 §8.4
- Indonesia — G12 Revisi pp.113–118 — theorem + Pascal's triangle in the body; G8 K13 Bab 1 pp.1–40 — Pascal's triangle as pattern [2022 Merdeka: Pascal NOT FOUND — never cite]
- Vietnam — G10 v2 Bài 25 p.72; study book Bài 4 p.32; Yemen — G12 Sci 2-4 p.65 — (a+b)ⁿ = Σ C(n,k)aⁿ⁻ᵏbᵏ
- Kuwait — G11 T2 11-2 pp.162–166; G11 Statistics T2 5-2 pp.63–67; Laos — G11 Ch.6 L28 p.180; Cambodia — G10 (1+a)ⁿ
- Pakistan — G11 Unit 8 pp.151–168 — theorem proved by induction; closing part: binomial series for negative/fractional indices, |x|<1, pp.158–159
- Armenia — G12 guide Ch.2 §4 [TEACHER-EVIDENCE]

### 107 inclusion-exclusion-and-venn-counting
- Iran — Discrete pp.73–78 — inclusion–exclusion incl. counting onto functions
- Laos — G10 Ch.II L5 pp.38–48 — n(A∪B) and the three-set formula in survey problems
- Nepal — G8 §10.3; G9; G10 [ERROR-CORRECTED: the "neither" count is 18]
- Sierra Leone — SSS1 L64–70 three sets; SSS3 L121 formulae; Kazakhstan — G5 §5.4; G9 books; South Sudan — S2

### 108 graph-theory
- Iran — Discrete pp.32–54 — graphs incl. dominating sets γ(G)
- Vietnam — G11 study book Chuyên đề 2: Bài 8 p.34 concepts; Bài 9 p.41 Euler + Hamilton paths; Bài 10 p.46 shortest paths
- Jordan — G12 Business Unit 2 pp.58–107 — algorithms, bin-packing, Euler graphs
- Mauritania — Euler/Hamilton/shortest path rows as filed; China — G6 review — Königsberg box [enrichment as filed]

### 109 congruences-and-diophantine-equations
- Iran — Discrete pp.18–30 — congruences; pp.26–29 — Diophantine equations
- Greece — W7 Ch.4 — linear Diophantine equations + congruences
- Sierra Leone — SSS1 L21–24 — modular arithmetic
- Kazakhstan — G6 §10.1 Diophantine; Soltan G9; G8 starred Euclid's algorithm [OPTIONAL as filed]

### 110 latin-squares
- Iran — Discrete pp.62–71 [sole source]

### 111 algebraic-structures
- Yemen — G10 Pt1 Unit 5 pp.96–110 — binary operations; the group axioms; G11 Sci Pt1 Unit 1 pp.6–24 — rings; fields; ℝ as a field

### 112 mathematical-investigations
- China — G5 下册 U8 pp.111–114 — finding the defective product on a balance (split in THREE; guarantee table 2–3→1, 4–9→2, 10–27→3, 28–81→4, 82–243→5); ★ p.44 painted cubes; ★ pp.102–103 the phone-call tree (2ⁿ know after n minutes); G6 review pp.100–104 — counting segments n points → 1+2+…+(n−1)

### 113 money
Taught in EVERY swept group; per-country rows in the inventory files. Lead rows:
- Bangladesh — C1 Ch.17 pp.105–108 coins 1/2/5 taka, notes to 100; C2 Ch.6 pp.121–124 exchanging 200/500/1000; C3 Ch.10 pp.99–109 100 paisa = 1 taka
- China — G1 下册 U5 pp.52–60 — RMB 元/角/分; 59.90元 = 59元9角
- Pakistan — Primer pp.132–133; G1 Unit 4 pp.82–93 — Rs coins/notes; making Rs 50/100; "is the money enough?"
- Libya — G1 Unit 17 pp.82–83; G2 Unit 8 pp.8–17; G3 Unit 10 pp.8–17 — 1 dinar = 1,000 dirhams
- Kuwait — G1 T2 p.144; G2 T2 pp.148, 150; G3 T2 pp.140, 142 [ERROR-CORRECTED: p.147 item has NO correct option — teach the skill, not that item]; G4 T2 p.150; G5 T2 Unit 8
- Laos — G2 Ch.15 p.190 banknotes + change; G3 L11 p.40 notes 100–50,000 kip
- North Macedonia — G1 (2022) pp.90, 91, 93, 94, 159 — denars; school bazaar
- Vietnam — G2 v2 Bài 56 p.71; G3 v2 Bài 68 p.85 [introductions as filed]; Yemen — G1 Pt2 p.135; G2 Pt2 p.114 — riyals
- Ghana — JICA B3 Lessons 74–76; DL Workbook L1 worked total GH¢465 [ALL TEACHER-EVIDENCE]; Sierra Leone — Leone rows [TEACHER-EVIDENCE; pre-redenomination — examples re-based]; plus SA rand, Iran rial, Egypt LE, Cambodia riel (G4 first buying/change), Kazakhstan tenge, Nicaragua córdoba, Jordan dinar, Ethiopia santim/birr, Nepal rupees/paisa, South Sudan SSP, Mauritania G1–G2 rows as filed
- Iraq — explicit NEGATIVE: money is never a topic there (recorded, not cited as a source)

### 114 business-mathematics
- Greece — EPAL W8 — a full financial-mathematics book: interest, discounting, bills of exchange, annuities, amortisation
- Nepal — tax/VAT chain, commission, dividend, household bills, currency exchange, population growth, compound depreciation (books as filed)
- Sierra Leone — SSS3 L59–72 full commercial block + JSS rows; South Sudan — P4–S2 commercial arithmetic [many ERROR-CORRECTED items — take corrected values from the filing]
- Pakistan — G8 pp.62–78 — currency conversion pp.62–63; markup as interest pp.68–71; insurance pp.71–73; partnership pp.74–76; inheritance pp.76–78 (widow 1/8; sons:daughters 2:1); G7 pp.62–63 zakat (niṣāb 7.5 tola gold / 52.5 silver; 2.5%) + ushr p.63 (10% natural / 5% artificial irrigation)
- Indonesia — G12 Revisi Bab 1–2 pp.1–80 — interest, compound investment, annuities, loans; G10 Revisi Bab 2 C pp.35–70 — simple/compound interest
- Ethiopia — G12 Unit 5 — business applications incl. annuities/amortisation [TWO examples UNVERIFIED-BY-CHECK, pp.330 and 380 — NEVER cite]
- Iraq — G11 Lit pp.59–63 — present value, annuity, insurance [ERROR-CORRECTED: log 0.0253 not 0.253; the annuity 59,875,000 is log-rounding, not an error]
- Yemen — G6 Pt1 pp.132, 136 profit/loss; zakat = 1/40 on 500,000 riyals; G6 Pt2 5-7 p.43 inheritance
- Bangladesh — C5 Ch.9 §§9.2–9.3 pp.96, 98; C8 Exp.4 pp.71–92 [ERROR-CORRECTED: English p.76 principal is 15,000 tk, not 1,500]
- Kuwait — G7 T2 Unit 7 pp.130–171 — discount; zakat with a Zakat House calculation; G6 T2 Unit 6 — inheritance as ratio; G9 T2 pp.208–222 successive changes
- Laos — G9 Ch.1 L7 p.32 — I=PTR/100; A=P(1+r)ⁿ; instalments; G5 L51 pp.124–129 interest tables in kip
- Vietnam — G12 study book Chuyên đề 3 pp.46, 54, 60 — money, credit, investment; Libya — G8 §2-13 pp.54, 58, 60 profit/loss, discount, commission
- Cambodia — G6/G8/G9/G11 rows; SA — G7–G9 finance worksheets; Jordan — G7 financial applications + proportional division; Kazakhstan — simple interest + compound formula [OPTIONAL once, as filed]; Nicaragua — G7 module; G10 module [ERROR-CORRECTED: (1.005)¹²⁰, not (1.015)¹²⁰]; Mauritania — G4 pp.76, 78 buying/selling, profit/loss; G6 pp.22, 24; 6AS-LO zakat niṣāb (gold 85 g, silver 595 g → 2.5%)
- Bills and budgets part: Nepal — G3/G4 bills [ERROR-CORRECTED: fruit bill total Rs 90, not 70]; South Sudan — P7 bills [ERROR-CORRECTED: total SSP 1,750, not 10,500]; South Africa — budgets

### 115 time-and-calendars
Taught in EVERY swept group; lead rows:
- Pakistan — G1 Unit 5 pp.95–103 (solar + Islamic months); G2 Unit 5 pp.123–131 a.m./p.m.; G3 Unit 5 pp.119–130 adding/subtracting hours; G4 Unit 5 pp.113–125 12h↔24h conversion
- Cambodia — G5 24-hour clock [ERROR-CORRECTED: teach 24:00, not 12:00]; Khmer months + full 2015 calendar
- Nepal — Bikram Sambat months + printed calendars; G3 [ERROR-CORRECTED: 6h15m + 3h10m = 9h25m]
- Ethiopia — the Ethiopian calendar and time reckoning [G1 guide — TEACHER-EVIDENCE]
- Laos — G5 (2009) Ch.16 L65 pp.156–163 — adding/subtracting/multiplying/dividing compound time; G1–G4 rows
- Kuwait — G1 T1 pp.68–76 (Gregorian + Hijri months [ERROR-CORRECTED: p.76 November layout is 2025's; Nov 2026 starts Sunday]); G2–G4 rows
- Bangladesh — C2 Ch.5 pp.117–120 (Bengali + English months); C5 Ch.12 pp.133–141 (Bangla calendar; leap year, decade, era, century; 24-hour clock p.133)
- Yemen — G2 Pt2 pp.118–128 (clock; Hijri months); G4 Pt2 p.143 Hijri + Gregorian side by side; Ghana — JICA B3 Lessons 94–110, B4 Lessons 89–107 [TEACHER-EVIDENCE]
- China — G3 下册 U6 pp.76–90 (leap-year ÷4 rule; 24-hour clock); Libya — G1–G3 + G7 §5-2 p.119; Vietnam — G1–G5 rows; North Macedonia — G1 pp.149–155; Mauritania — G4 pp.144–151; G5 pp.41, 94–96 sexagesimal arithmetic; G6 p.51; Iraq — G2 p.112 Gregorian months; G3 p.84 Hijri year; Greece — months/seasons/century/millennium

### 116 speed-distance-and-time
- Laos — G9 Ch.1 L8 p.39 — v=S/t; meeting problems; G5 L41–L42 distance–time graphs; L66 mixed conversions
- Kazakhstan — motion types (meeting/opposite/catch-up) + motion graphs
- Vietnam — G5 v2 Theme 10 pp.76, 78, 82 — uniform motion v=s/t in words
- Libya — G6 Unit 8 pp.118, 127, 134, 141 (Tripoli–Ghadames at 90 km/h); G7 §5-4 p.129
- Yemen — G6 Pt2 7-9 p.134 — 80 m/min cyclist; 90 km/h car; 750 km/h plane
- Cambodia — v=d/t + average speed; South Sudan — the triangle + unit conversion [P8 guide key wrong 6/10 — cite the STUDENT book only]
- Sierra Leone — travel graphs; Egypt — distance–time graphs; Mauritania — G5 p.110; G6 p.77 uniform motion; China — bicycle-gears project p.67 [project as filed]
- Density part: Cambodia — G8 [ERROR-CORRECTED: d²=(2×10⁻³ m)²=4×10⁻⁶ m²; population-density row is a TEACHER-EVIDENCE addition]; Nicaragua — G7 module SI/density; Sierra Leone — SSS3 density
- Work-rates part: Kazakhstan — G4–G5 productivity/joint-work/yield problems

### 117 conditional-probability-and-bayes
- Kuwait — G10 T2 10-5 pp.192–205; G11 T2 11-3 pp.167–178 — conditional probability; Bayes (quality-test example)
- Egypt — Stats 3-2/3-3 — conditional probability; Bayes
- Cambodia — Probability booklet pp.85–94 — Bayes [PRIVATE booklet — label]
- Greece — W13 §3.4; Kazakhstan — Shynybekov §5.1.5; Nicaragua — G11 pp.141–142; Iraq — G9/G11 rows
- Sierra Leone — SSS3 tree diagrams only [no P(A|B) notation there — word as filed]

### 118 random-variables-and-distributions
- Pakistan — G11 Stats Ch.7–9 pp.186–249 — RVs; pmf/pdf; E, Var; cdf; binomial; hypergeometric [ERROR-CORRECTED: p.206 ex.8.8 sums to 1.07 not 1; p.245 P(X=5)=0.003968=1/252, and 5 tomato cans not 7]; G12 Stats Ch.10 pp.1–26 normal + Appendix A pp.287–288 χ² and t variables [appendix tables pp.301–306 NOT cited]
- Indonesia — G12 TL Revisi Bab 4 pp.221–280 — RVs Definisi 4.1 p.227; discrete p.232; continuous p.239; pdf p.249; binomial pp.253–263 [ERROR-CORRECTED: Definisi 4.6 p.256 coefficient is (n/x), not (n/p)]; normal pp.265–273; z-table pp.281–282 [uniform NOT in Revisi]; G12 TL (2022) Bab 5 pp.169–196 — uniform, binomial, normal
- Kuwait — G12 T2 Unit 8 pp.140–177 — discrete RVs, expectation, CDF; uniform + normal, z-tables [ERROR-CORRECTED: p.169 summary CDF forms false for discrete — correct forms in filing; p.171 binomial table n=2,x=2 last entries 0.490, 0.640, 0.810, 0.902]; G12 Statistics T2 Unit 4 pp.14–50
- Egypt — Stats Unit 4 (discrete/geometric/binomial) + Unit 5 (normal); Jordan — G11 discrete RVs; G12 + Business distributions units
- Libya — G12 (Science) Ch.2–3 — RVs; binomial, Poisson, normal, t [G11 Stats books teach NO distributions — do not back-project]
- Vietnam — G12 study book Chuyên đề 1 pp.5, 15 — discrete RVs; binomial [the series' only distributions; NO continuous distributions in Vietnam]
- Yemen — G12 Sci Unit 3 pp.93, 98 — binomial law; sampling with/without replacement; Armenia — G10 Ch.5 §3 p.163 discrete RVs + expectation; G12 guide §6 normal [TEACHER-EVIDENCE]
- Cambodia — G12 Adv binomial/Bernoulli + normal; G11 Basic normal + z-table p.246; Laos — G11 Ch.7 L30 p.205 RVs; appendix p.300 binomial sums table; G12 appendix p.293 normal table
- Iran — G10 bell curve descriptive only (±1σ/2σ/3σ) [p.92 "96 of 100" is loose wording, NOT an error — never cite 96 as exact]
- Z-score part: Kuwait — G11 Statistics T2 4-3 pp.27–32 — empirical rule 68–95–99.7; z=(x−x̄)/σ; G11 T1 WORKBOOK 6-5/6-6 pp.93–96 [workbook evidence]

### 119 sampling-and-sampling-distributions
- Pakistan — G12 Stats Ch.11 pp.27–72 — frames/designs; sampling vs non-sampling errors; bias=E(T)−θ; sampling distributions; the Central Limit Theorem
- Kuwait — G11 Statistics T1 Unit 2 pp.36–53 — census vs sampling; simple/stratified/systematic; random-number table; G11 T1 WORKBOOK Unit 6 pp.85–88 [workbook evidence]
- Indonesia — G9 Bab 4 pp.215–282 — population vs sample; estimating a population from samples
- Libya — G12 (Science) Ch.4 (ch-p.121) — sampling distribution of the mean; Mauritania — Échantillonnage chapters in five streams; North Macedonia — G8 Theme 1 unit 13 pp.48, 50–51 — representative samples; criticising a bus-stop survey
- Egypt — G8/G9 populations/censuses; Iraq — G9 survey design + misleading statistics pp.139, 143; Kazakhstan — G7/G8; Nicaragua — G9
- Data-types part: Kazakhstan — NIS discrete/continuous chart; Nicaragua — G9; Ghana — JICA B6 Lessons 99–108 [TEACHER-EVIDENCE]
- Population-statistics part: Libya — G12 (Humanities) Ch.4 pp.89–107+ — census; density; growth rate; sex ratio; vital statistics
- Randomised-response part: China — A版 Ch.9 reading p.185 [reading as filed]

### 120 estimation-and-confidence-intervals
- Pakistan — G12 Stats Ch.12 pp.73–110 — point vs interval; unbiasedness (Ŝ² n−1 vs S² n); CIs for mean (σ known/unknown), proportion, differences of means/proportions
- Jordan — G12 Business Unit 6 — full inference unit
- Kuwait — G12 (sci) T1 4-1 pp.168–176 — point estimation; margin of error; t for σ unknown, n<30, 95% only [ERROR-CORRECTED: p.171 |x̄−μ| is the point estimation ERROR; standard error = σ/√n]
- Egypt — Stats 5-3 p.136; Libya — G12 (Science) Ch.5 pp.144–147; Laos — G12 Ch.5 L14 p.145
- Iran — G11 Stats pp.97–121 — point/interval estimation WITHOUT z-machinery [hypothesis testing NOT taught in Iran — Fisher mention p.79 only; never cite Iran for tests]
- German-tank part: China — A版 Ch.9 reading pp.208–209 — N ≈ x_max·(n+1)/n [reading as filed]

### 121 hypothesis-testing
- Pakistan — G12 Stats Ch.13 pp.111–180 — H₀/H₁; Type I/II errors; nine steps; Z/t tests; paired t; proportion tests
- Jordan — G12 Business Unit 6 — testing inside the inference unit
- Libya — G12 (Science) Ch.6 (ch-p.161) — hypotheses; errors; t-tests for a mean
- Kuwait — G12 (sci) T1 4-2 pp.177–181 — two-sided tests ONLY [negatives: no p-values, no χ² tests]
- Explicit negatives recorded: no hypothesis testing in Egypt, Cambodia, Greece or Iran filings

### 122 correlation-and-regression
- Pakistan — G12 Stats Ch.14 pp.181–214 + Ch.15 pp.236–237 — scatter; covariance; least squares b=s_xy/s²_x; Pearson r; two regression lines; correlation ≠ causation; Spearman r_s [unkeyed remainder: limitations of the linear model p.195]
- Libya — G11 (Science) Ch.6 pp.113–133; G12 (Humanities) Ch.1 pp.9–32 — Pearson + Spearman + least squares
- Indonesia — G11 Bab 3 pp.79–130 (least squares; product-moment; determination); G11 Revisi Bab 1 pp.1–80 (two-way tables; outliers' effect)
- Yemen — G11 Sci Pt2 Unit 10 pp.127, 138; G12 Lit Unit 2 pp.33, 43 — regression line a=[nΣxy−ΣxΣy]/[nΣx²−(Σx)²], b=ȳ−a·x̄
- Egypt — Stats G12 Unit 1 Pearson + regression; Greece — W9 §VI; W11 2.7; W13 §§2.4–2.5; Iraq — G11 Lit Ch.4 Pearson + Spearman [ERROR-CORRECTED: points (4, 8.85)/(8, 5.05); Spearman intro pp.113–115 partly unverified — cite the verified parts only]; G10 concept-level
- Cambodia — G12 Basic Ch.5 [ERROR-CORRECTED: 6 babies, not 8]; Jordan — G12 Business; G10 scatter/best-fit only; Kuwait — G12 (sci) T1 4-3 pp.182–193 Pearson + least squares
- ANOVA part: Laos — G12 Ch.5 L16 p.175 ANOVA + correlation; Kuwait — ANOVA rows as filed
- South Africa — scatter plots ONLY (G9 WS132) [no regression/correlation in SA or Iran — recorded negative]

### 123 association-of-attributes
- Pakistan — G12 Stats Ch.15 pp.215–240 — attributes; 2×2 tables; independence (AB)=(A)(B)/n; Yule's Q p.220; χ² test pp.224–225 (e_ij rule, df=(r−1)(c−1), expected ≥5, Yates); contingency coefficient p.226 [NO goodness-of-fit test in this book — recorded negative; sole full source]
- Greece — W11 Units 2.5–2.6 — contingency tables, descriptive only

### 124 time-series
- Pakistan — G12 Stats Ch.16 pp.241–268 — four components; freehand, semi-averages, moving averages, least-squares and parabolic trends
- Libya — G12 (Humanities) Ch.3 pp.59–88 — components; seasonal indices by simple averages
- Greece — W9 §VII pp.205–233; Jordan — Business Unit 4; Iran — G11 Maths & Stats (2) pp.63–70 [filed "for study" — word as filed]

### 125 index-numbers
- Pakistan — G11 Stats Ch.5 pp.128–158 — Laspeyres, Paasche, Fisher √(L×P); CPI/WPI/SPI; purchasing power = 1/CPI [ERROR-CORRECTED: potato link relatives 111.1/100.0; Paasche 110.4; Fisher 114.5]
- Libya — G12 (Humanities) Ch.2 pp.33–58 — Laspeyres, Paasche, Marshall–Edgeworth, Fisher; changing the base
- Iran — price index, poverty line, inflation pp.56–60 + inflation box pp.89–90 [ERROR-CORRECTED: ≈14.3%, not 14%]

### 126 quartiles-percentiles-and-box-plots
- Kuwait — G9 T1 4-5 pp.198–203 box-and-whisker; G10 T2 10-2 pp.170–175 quartiles; G11 Statistics T2 4-1 pp.12–18 (grouped interpolation); 4-3 p.23 semi-interquartile range
- Cambodia — G11 Basic Ch.7 — deciles/percentiles [decile ANSWERS are guide evidence — TEACHER-EVIDENCE wording]; Ethiopia — G11 guide [ERROR-CORRECTED: D3=20.15, Q1=34, cf=92 — guide evidence]
- Jordan — G8 p.144 box-and-whisker; Kazakhstan — NIS G8 box plots; Nepal — G9/G10 Optional box plots
- Iraq — G10 Lit pp.78–82 cumulative frequency + ogives; Nepal — G7/G9 ogives; South Sudan — S2 assumed mean + ogive; Sierra Leone — SSS3 percentiles from cf curves

### 127 mean-deviation-and-variation
- Bangladesh — C9–10 Ch.9 pp.211–235 — range p.215; mean deviation pp.217–222; variance pp.223–226; SD pp.229–232 [ERROR-CORRECTED: p.223 Pearson's variance year is 1893, not 1983] [quartile deviation NAMED p.211 but NEVER taught there — do not cite Bangladesh for it]
- Laos — G9 Ch.7 L44 p.239 — SAMPLE variance s²=Σ(x−x̄)²/(n−1), grouped (rainfall s²=147.37)
- Pakistan — G11 Stats Ch.4 — variance with denominator n [the book's own convention — present both conventions attributed]; dispersion rows groups F/G: quartile deviation, mean deviation, coefficient of variation

### 128 moments-skewness-and-kurtosis
- Pakistan — G11 Stats Ch.4 pp.104–120 — moments about the mean/origin/zero; Sheppard's corrections; √β₁ and b₁=m₃²/m₂³; Pearson's and Bowley's skewness; β₂ kurtosis [sole moments source; ERROR-CORRECTED: p.91 Q1=40.51 (used as 40.15); p.102 coefficient of Q.D. denominator is (Q3+Q1)]
- Kuwait — G11 Statistics T2 4-2 pp.19–22 — skewness against mean/median/mode and the box plot
- Cambodia — skewness guide p.236, value −0.05 [TEACHER-EVIDENCE only]

### 129 geometric-and-experimental-probability
- Kazakhstan — four G9 books — geometric probability; four G9 books — frequentist/statistical probability
- Jordan — G9 p.165 — geometric probability
- Nicaragua — G10 pp.45–48 — statistical probability

### 130 monte-carlo-and-simulation
- Pakistan — G11 Stats Ch.7 pp.186–196 — random digits; linear congruential generator xₙ₊₁=axₙ+b (mod m); Monte Carlo with Table 7.1 (coin simulations; PPS ranges)
- China — A版必修二 Ch.10 §10.3.2 p.255 — random simulation / Monte Carlo
- Mendel part: China — A版 Ch.10 reading pp.259–260 — DD/Dd/dd 0.25/0.5/0.25 vs the ≈3:1 pea ratios [reading as filed]

### 131 odds
- Kuwait — G9 T1 4-6 pp.204–210 — odds ↔ probability (2:3 ↔ 2/5) inside weighting/fairness [sole source]

### 132 statics
- Egypt — Applied G11 T1: intro p.2; 1-1 p.12 … 1-6 p.50 — forces, resolution, resultants, equilibrium, friction/limiting equilibrium
- Egypt — Applied G12 Pt1: Moments p.10; Parallel forces pp.22–32; Couples pp.42–50

### 133 dynamics
- Egypt — Applied G11 T2: 1-1 p.15 … 2-4 p.61 — rectilinear motion, free fall, momentum, Newton's laws, impulse
- Egypt — Applied G12 Pt2 pp.72–150 — work, energy, power and the advanced dynamics run

### 134 position-and-direction
- Kuwait — G1 T1 1-1/1-2 pp.17, 20 — over/under, above/below, right/left, inside/between/outside; G2 T1 1-1 p.17
- Bangladesh — C2 Ch.1 pp.34–39 — ordinals 1st–10th; front/back/left/right; Laos — G1 Ch.3 p.22 order
- North Macedonia — G1 (2022) pp.10, 13–18 — position pairs; inside/outside/on; left/right movement
- Pakistan — Primer pp.134, 135; G1 Unit 6 pp.116–126 — inside/outside, above/below, over/under, far/near, before/after
- Yemen — G1 Pt1 1-4 p.18 (inside/outside p.20); Indonesia — G2 Ch.4 pp.101–124; China — G3 下册 U1 p.2 — eight compass directions, north-up maps
- Ghana — JICA B5 Lessons 103–105; B6 Lesson 93 [TEACHER-EVIDENCE]

### 135 sorting-and-classifying
- Yemen — G1 Pt1 Unit 1 pp.8, 12, 14 — sorting by one attribute, then two; G2 Pt2 Unit 11 p.140 — sorting opens statistics
- Indonesia — G1 shapes chapter pp.115–144 — grouping by shape/colour/size
- Kazakhstan — sorting rows; Nicaragua — G1 guide [TEACHER-EVIDENCE]; China — attribute sorting rows

### 136 repeating-patterns
- Kuwait — G1 T1 1-4 p.24; G2 T1 1-2 p.20 — repeating patterns
- Yemen — G1 Pt1 1-5 p.22 + repeats at 3-8 p.84, 4-7 p.110, 5-3 p.126
- Indonesia — G2 Ch.4 pp.101–124 (shape/colour/movement/sound); G4 Bab 3 pp.85–102 growing/shrinking patterns; G8 K13 Bab 1 pp.1–40 (tile patterns, lamp cycles, unit digits)
- Ghana — JICA B3 Lessons 77–79; B5 Lessons 73–78 (divide-by-2 chain 560, 280, 140, 70, 35) [TEACHER-EVIDENCE]

## Checked and already covered (no new lesson — do not double-build)

Absolute value (equations/inequalities) · Heron's formula (perimeter-and-area) ·
stem-and-leaf (collecting-and-showing-data) · cumulative frequency as charting
(collecting-and-showing-data / averages-and-spread — the cf-curve *percentile*
work is in lesson 126) · Viète + discriminant (quadratic-equations) ·
differentials (derivatives) · open sentences (expressions) · Fibonacci-type
sequences (sequences-and-series) · GCD/LCM of fractions and algebraic
expressions (factors-multiples-and-primes extension) · recurring decimals
(decimals/fractions) · distance/midpoint/slope/line equation
(coordinates-and-graphs) · elevation/depression angles
(right-triangle-trigonometry) · Richter/decibel log applications
(logarithms-and-exponentials) · Thales/midpoint theorems
(congruence-and-similarity) · van Schooten + Pitot theorems (Indonesia G11
Bab 2 pp.45–78 — stocked inside circle-theorems) · Excel/calculator tool use
(not a maths topic) · Pakistan G10 back-matter log tables + glossary-only
function definitions (printed, NOT taught — excluded as filed).

## Could NOT be built into a sourced lesson

1. **Volumes of revolution** — the only dedicated filing rows (Iraq G12
   Sci [4-9]) are UNVERIFIED-BY-CHECK and may never be cited; everywhere
   else it is an application inside integrals lessons. Revisit only if a
   future read verifies a source.
2. **Iraq's Rolle / Mean Value Theorem rows** — UNVERIFIED-BY-CHECK;
   lesson 89 is built from Greece, Cambodia and Yemen instead, with Iraq
   cited nowhere.
3. **Cambodia G12 Advanced guide's six sequence-limit answers** —
   UNVERIFIED-BY-CHECK (not found); lesson 87 stands on the other
   countries.
4. **Pakistan G12 Statistics appendix tables, printed pp.301–306** —
   shuffled appendix leaves; the inventory directs they are not cited.
   The χ²/t variables themselves are cited at pp.287–288 in lesson 118.
5. **Pakistan Primer non-number readiness items** (colours, hard/soft,
   some/all, a maze — Primer pp.2–8, 37, 47, 56–57, 142) — readiness
   activities, not mathematics topics; recorded here so nothing is
   silently dropped.

Everything else in the nine inventories maps to a lesson above.
