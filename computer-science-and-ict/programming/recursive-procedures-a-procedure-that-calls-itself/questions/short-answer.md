# Recursive procedures — a procedure that calls itself — short answer

Answer in one or two sentences.

**1.** What does the star procedure's single body command do, step by step?
**Answer: REPEAT 100 [fd 100 rt 144] makes the turtle go forward 100 and turn 144 degrees, one hundred times — drawing the many-pointed star by repetition.**

**2.** Why is the star procedure, as printed, not truly recursive — and what would have to change?
**Answer: Its body never contains the word star, so it never calls itself; a self-call — the procedure's own name inside its body — would have to appear for it to be recursive.**
