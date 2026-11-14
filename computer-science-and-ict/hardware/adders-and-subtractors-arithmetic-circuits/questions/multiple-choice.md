# Adders and Subtractors — Arithmetic Circuits — multiple choice

Pick the one right answer.

**1. (Sub lesson 1) In a half adder, the Sum output is produced by —**
a) An AND gate  b) An XOR gate  c) An OR gate  d) An inverter
**Answer: b) An XOR gate** — The Sum column of two-bit addition reads 0, 1, 1, 0 — exactly XOR's table.

**2. (Sub lesson 1) A half adder is called 'half' because it cannot —**
a) Add 1 + 1  b) Accept a carry-in from a previous column  c) Produce a carry  d) Work with bits
**Answer: b) Accept a carry-in from a previous column** — A real column has three inputs — A, B and the incoming carry. Handling that third input is the full adder's job.

**3. (Sub lesson 1) A full adder is built from —**
a) Four XOR gates  b) Two half adders and an OR gate  c) One flip-flop and an AND  d) A decoder
**Answer: b) Two half adders and an OR gate** — First half adder adds A + B, second adds Cin; the OR joins the two possible carries into Cout.

**4. (Sub lesson 2) In the adder/subtractor, setting SUB = 1 makes each XOR gate on the B line —**
a) Pass B unchanged  b) Invert its bit of B  c) Output 0 always  d) Act as an AND
**Answer: b) Invert its bit of B** — X ⊕ 1 = X̄: with SUB = 1 every B bit is flipped, producing the ones' complement of B.

**5. (Sub lesson 2) For subtraction, the chain's first carry-in Cin must be 1 because —**
a) It looks tidier  b) It supplies the +1 that turns ones' complement into two's complement  c) Carries always start at 1  d) It clears the register
**Answer: b) It supplies the +1 that turns ones' complement into two's complement** — Invert-and-add-1 is the two's complement recipe; the XORs do the inverting and Cin does the adding of 1 — which is why Cin is wired to SUB.

**6. (Sub lesson 2) To subtract with the adder/subtractor, the final carry-out of the chain is —**
a) Stored as the sign  b) Fed back as input  c) Discarded, exactly as in the pencil complement method  d) An error signal
**Answer: c) Discarded, exactly as in the pencil complement method** — In a fixed-length register the overflow carry falls away, and two's complement guarantees the remaining bits are the true difference.
