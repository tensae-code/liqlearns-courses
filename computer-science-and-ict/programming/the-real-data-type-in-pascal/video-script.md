# Video script — The Real Data Type in Pascal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

The **real** type holds numbers **with fractional parts**: 3.14, −0.5, the average 7.333…. A real value may be written in **fixed form** (2.75) or in **exponent form** (2.75E3 = 2750), the form science uses for the very large and very small. Declaration mirrors integer's: `var x: real;`. Unlike an integer's exact shelf of values, a real is held **approximately** — the type stores a very close neighbour of the true value, a fact whose consequences the Grade 12 error lessons will cash in.
Reals take the full arithmetic: +, −, *, and **/** — division that keeps the fraction (7 / 2 = 3.5, where integer div gave 3). The standard functions serve them: **abs**, **sqr**, **sqrt**, **sin**, **cos** and their kin take reals and answer reals. One warning travels with the type: because reals are approximate, **testing two reals for exact equality is unsafe** — 0.1 + 0.2 may not sit exactly on 0.3. Compare reals by closeness, not by identity: the professional's habit, taught from the first real lesson.
