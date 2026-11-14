# Video script — Digitising an Analogue Signal

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Your voice is smooth. It takes every value between loud and quiet, with no steps.

A computer cannot store smooth. It stores counted things: levels, codes, bits.

Step one: sampling. Measure the signal at regular instants. Keep only the measures.

Measure at least twice as fast as the signal's fastest wiggle — or false patterns appear. CDs measure 44 100 times a second.

Step two: quantisation. Round each measure to the nearest level. 16 bits give 65 536 levels.

The rounding loses a little — that loss is quantisation error, heard as noise.

Step three: coding. Write each level's number in binary. The stream of codes is the recording.
