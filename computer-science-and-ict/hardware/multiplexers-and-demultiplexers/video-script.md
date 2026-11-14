# Video script — Multiplexers and Demultiplexers

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Many inputs. One output. Who is connected? The multiplexer decides.

Its select lines hold a binary number — the address of the chosen input.

Select says 10: input 2 reaches the output. The others are cut off.

Four inputs need two select lines. Eight inputs need three. 2-to-the-n inputs, n lines.

The demultiplexer delivers: one input, and the select code picks which output receives it.

Put them at the two ends of one wire, keep their codes together — and many pairs share a single line.
