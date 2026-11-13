# Signal attenuation — why signals weaken with distance

## Do it first
Before you read: walk away from a radio playing until the music dissolves into hiss. Nothing broke — the signal simply spread, thinned and got robbed on its way to you, while the world's noise stayed as loud as ever. Engineers have a name and a unit for that thinning, and three standard answers to it. This lesson is all four.

## Sub lesson 1 — Spreading — the geometry tax

A receiving aerial can only collect the fraction of the sphere its own area covers — the rest of the transmitted power passes by, spent on empty space. Directional aerials (dishes, beams) fight the tax by refusing to pay most of it: they concentrate the radiation into a narrow solid angle.

[Picture 36736]

## Sub lesson 2 — Absorption, scattering and the cable's resistance

Losses multiply, so engineers count them in **decibels**: each −3 dB halves the power, −10 dB leaves a tenth; a link budget adds the journey's losses in dB the way a traveller adds tolls.

## Sub lesson 3 — The answers — amplify, repeat, guide

Three answers recur. **Amplify**: boost the weakened signal — but an amplifier boosts the noise picked up along the way too, so amplification has limits. **Repeat**: receive, clean up and **re-transmit** the signal at full strength — a repeater (or a chain of them, or a satellite) resets the journey, and digital signals repeat especially well because their clean 0/1 pattern can be recognised and regenerated exactly. **Guide and aim**: keep the signal from spreading in the first place — cables, fibres, waveguide, directional aerials. Vietnam's sequence closes the loop the topic opened: a radio system is modulate → transmit → survive attenuation → receive — and designing the survival is half the engineering.

## The key ideas

- Attenuation is the weakening of a signal on its journey: spreading (inverse-square), absorption and scattering in the medium, and resistive heating in cables
- Losses are counted in decibels: −3 dB halves the power, −10 dB leaves a tenth; a link budget adds up the journey's tolls
- Directional aerials fight the spreading tax; optical fibre guides light with fractions of a dB lost per kilometre
- The answers: amplify (noise and all), repeat (receive, regenerate, re-transmit — digital repeats best), and guide the signal so it cannot spread

## Say it to your companion
Tell your companion: Every travelling signal weakens — attenuation: its power falls because the wave spreads over an ever-larger area, because the medium absorbs and scatters it, and (in cables) because resistance turns signal into heat; the loss is measured in decibels, and engineers answer it with amplifiers, repeaters, higher aerials and fibres that guide the signal instead of letting it spread. If your companion can work the Do It Yourself tasks without looking back, the lesson has landed.

## Do It Yourself
1. A signal leaves at 100 mW and arrives at 1 mW. How many decibels were lost on the journey?
2. A receiver is moved from 2 km to 6 km from a transmitter (free spreading). By what factor does the received intensity fall?
3. Why does a chain of digital repeaters beat one big amplifier for a very long link?
