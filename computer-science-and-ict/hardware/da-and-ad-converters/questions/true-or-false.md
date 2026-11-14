# DA and AD Converters — true or false

Say whether each statement is true or false.

**1. (Sub lesson 1) A DAC with more bits produces a smoother-looking output because its steps are smaller.**
**Answer: True** — More bits divide full scale into more, smaller steps — the staircase approaches a ramp.

**2. (Sub lesson 1) The DAC output for the maximum input code equals exactly Vref.**
**Answer: False** — The largest code is 2ⁿ − 1, so the output is Vref × (2ⁿ − 1)/2ⁿ — one step below full scale.

**3. (Sub lesson 2) An ADC performs sampling, quantisation and coding — the same three steps as digitising by hand.**
**Answer: True** — The ADC is the digitising process built as a circuit; its datasheet numbers are the digitising lesson's choices.

**4. (Sub lesson 2) For every job, the best ADC is simply the one with the most bits.**
**Answer: False** — Bits trade against conversion speed and cost; a fast signal may need speed more than fineness. The signal's needs choose the converter.
