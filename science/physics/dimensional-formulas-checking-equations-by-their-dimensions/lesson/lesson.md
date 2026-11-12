# Dimensional formulas — checking equations by their dimensions

## Do it first
Take the familiar equation v = u + at. Without putting any numbers in, ask only about kinds: v and u are speeds, a is an acceleration and t is a time. Does "acceleration × time" give the same kind of thing as a speed? This lesson builds the tool that answers that question for any equation at all — the dimensional formula — and shows how it catches wrong formulas on sight.

## Sub lesson 1 — The dimensional formula of a quantity

A quantity's dimensional formula says how it is built from the base quantities: write mass as M, length as L, time as T (current I, temperature Θ, amount mol and luminous intensity complete the seven). Speed is length ÷ time, so its formula is L T⁻¹; acceleration is speed ÷ time, L T⁻²; force, from F = ma, is M L T⁻². Area is L², volume L³, density M L⁻³, energy M L² T⁻² and pressure M L⁻¹ T⁻² — each one read straight off the quantity's own defining equation.

Work is force × distance, M L T⁻² × L = M L² T⁻², and power is work ÷ time, M L² T⁻³. The method never changes: take the defining equation, replace each quantity by its dimensions, and multiply out. A quantity with no dimensions at all — a pure number like an angle in radians, a ratio, or a count — is called dimensionless, written M⁰L⁰T⁰.

## Sub lesson 2 — Checking an equation by its dimensions

An equation can only be true if every term in it has the same dimensional formula — quantities can only be added, subtracted or equated when they are the same kind of thing. Test v = u + at: [at] = L T⁻² × T = L T⁻¹, which is exactly [v] and [u], so the equation passes the check. Test s = ut + ½at² term by term: [ut] = L and [at²] = L T⁻² × T² = L, and the ½ is a pure number with no dimensions, so both terms are lengths and the equation is dimensionally sound.

The same test exposes wrong formulas instantly. The guess v = u + a/t gives [a/t] = L T⁻³, which is not a speed, so the guess is certainly wrong — no experiment is needed to kill it. Dimensions can also rebuild a formula: the period of a pendulum can only combine length L and g (L T⁻²) to make a time, and L ÷ (L T⁻²) = T², so the period must go as √(L/g) — which is the true law, apart from a pure number the dimensions cannot see.

## Sub lesson 3 — What dimensions can and cannot prove

Passing the dimension check does not prove an equation right: s = ut + at² (without the ½) passes perfectly, yet it is wrong, because pure numbers — ½, 2, 2π — are invisible to the test. Dimensions also cannot tell apart different quantities that share a formula: work and torque are both M L² T⁻², and frequency and angular speed differ only by a hidden 2π.

So the rule of use is: dimensions are a sieve, not a proof. A formula that fails is certainly wrong; a formula that passes is only possibly right, and still needs its numbers and its pure-number factors earned by derivation or experiment. Used that way, the check costs ten seconds and catches a large share of algebra slips, misremembered laws and swapped quantities before they do damage.

## The key ideas

- Every quantity has a dimensional formula built from the base dimensions — force is M L T⁻², energy M L² T⁻², pressure M L⁻¹ T⁻².
- An equation is dimensionally sound only when every added or equated term has the same dimensional formula.
- The check kills wrong formulas for free (v = u + a/t fails, since a/t is L T⁻³, not a speed) and can even rebuild a law's shape, as √(L/g) for the pendulum's period.
- Dimensions cannot see pure numbers (½, 2π) and cannot separate quantities sharing a formula (work and torque) — passing is necessary, never sufficient.

## Say it to your companion
Tell your companion the whole lesson in order, in your own words — start with the opening activity, then take each sub lesson in turn and finish with what it is used for. If your companion can repeat the main idea back to you, the lesson has landed.

## Do It Yourself
1. Find the dimensional formula of pressure two ways: from force ÷ area, and from energy ÷ volume. Show the two answers agree.
2. A student writes the period of a pendulum as T = 2π√(g/L). Use dimensions to show this cannot be right, and say what swap repairs it.
3. Check the equation v² = u² + 2as dimensionally, term by term, and state exactly what the check does and does not establish.
