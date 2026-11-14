# DA and AD Converters

## Do it first

Every sound your phone plays began as numbers in a file and ended as a smoothly varying voltage pushing a speaker cone. Every sound it records travelled the other way: a microphone's smooth voltage became numbers in a file. The circuits at that border crossing have names: the **DA converter** (digital-to-analogue, DAC) walks numbers out into the analogue world; the **AD converter** (analogue-to-digital, ADC) walks analogue signals in, turning them into numbers — the digitising lesson's three steps built in hardware. Montenegro's book ends its placed climb here, and so do we: after this lesson a signal can make the whole journey, world → machine → world.

## Sub lesson 1 — DA converters — numbers into voltage

A **DA converter (DAC)** promises: give me a binary number, and I will give you the voltage that number stands for. The promise in formula: with n bits and a reference voltage Vref (the converter's 'full scale'), the output is **Vref × (input value / 2ⁿ)**. An 8-bit DAC with Vref = 5 V given the code 10000000 (128) outputs 5 × 128/256 = **2.5 V** — exactly half scale for exactly half the counting range. Count the input upward 0, 1, 2, 3… and the output climbs a **staircase** of 256 equal small steps; with enough bits the steps are too fine to see and the staircase passes for a ramp.

How is a number turned into a voltage? The book's construction is the **R–2R resistor ladder**, and its soul is the place-value table from the first lesson. Each input bit controls a switch. A set bit lets its current flow into a summing point; the ladder's resistors — only two values, R and 2R, repeated — arrange that the most significant bit contributes half of full scale, the next a quarter, the next an eighth: each bit contributing exactly its binary weight. Add the contributions of the set bits and the total *is* the number, as a voltage.

[Picture — an R–2R ladder DAC: four bit switches feeding a ladder of R and 2R resistors into a summing point, with the contributions ½, ¼, ⅛, 1⁄16 of full scale labelled over the switches]

Judge a DAC by its bits and its settling: more bits mean finer steps and a truer analogue copy (the quantisation lesson's ladder, now on the way out), and the converter must settle to its new voltage quickly when the input code changes, or fast-moving outputs smear. Every audio output, every screen brightness control, every motor drive that a digital system commands passes through this staircase.

## Sub lesson 2 — AD converters — voltage into numbers

The **AD converter (ADC)** is the digitising lesson with a part number. Its input is a voltage; its output is that voltage's binary code, produced by exactly the three steps you know: **sample** the voltage at the chosen rate, **quantise** it to the nearest of the converter's levels, **code** the level in binary. Everything the last lesson said about faithfulness returns as this circuit's specification sheet.

The specification that matters first is **resolution**: an n-bit ADC divides its full-scale range into **2ⁿ levels**. An 8-bit ADC over a 0–5 V range has 256 levels, each level ≈ 5/256 ≈ 0.0195 V wide — a voltage is reported as the number of the level it falls in, and cannot be reported more finely than that step (there is the quantisation error again, wearing a circuit's clothes). A 4-bit ADC over the same range has only 16 levels of ≈ 0.31 V: quick and coarse. Sixteen bits: 65 536 levels: slow, fine, expensive.

One honest way to picture a conversion is the **flash** arrangement: a ladder of resistors divides the reference into all the level boundaries at once; a row of **comparators** — one per boundary — each answers 'is the input above my boundary?'; and encoder logic (the encoders lesson, returning to work) turns the pattern of answers into the binary code of the highest boundary passed. All comparisons happen in a single instant, which makes flash ADCs extremely fast — paid for with a comparator per level, so they are built with few bits. Other constructions trade that speed for bits, converting step by step.

[Picture — a flash ADC: a resistor ladder making the level boundaries, a column of comparators each comparing the input against one boundary, and encoder logic gathering their answers into the output code]

Choosing a converter is choosing a point on the trade: the signal's fastest change sets the needed conversion speed (think of the sampling theorem), and the smallest difference worth knowing sets the needed resolution. Temperature logging: slow signal, fine differences matter little — few bits, any speed. Music: fast signal, fine differences are the product — the CD numbers from the last lesson. That is the whole engineering of the border: DACs and ADCs matched to the signal they serve.

## Say it to your companion

Tell your companion, in your own words: a DAC turns a binary number into the proportional voltage — Vref times value over 2ⁿ — using weighted contributions like an R–2R ladder where each bit adds its place value; an ADC does the reverse, sampling, quantising into 2ⁿ levels and coding, with resolution in bits traded against conversion speed. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: compute a DAC's output voltage from Vref × (input value / 2ⁿ), and describe the staircase its output climbs as the input counts. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: explain how an R–2R ladder gives each bit its binary weight of contribution. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: state that an n-bit ADC quantises into 2ⁿ levels, and work a voltage into its output code for a stated range and bit count. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: name the ADC trade — resolution (bits) against conversion speed and cost — and match converter choices to a slow signal and a fast signal. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
