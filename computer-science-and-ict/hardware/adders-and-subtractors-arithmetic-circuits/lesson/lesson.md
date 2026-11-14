# Adders and Subtractors — Arithmetic Circuits

## Do it first

Add two single bits, 1 + 1. The answer needs two wires to say it: a sum wire showing 0 and a carry wire showing 1 — because the answer '10' is two bits. Now ask which gates you already own behave exactly like those two wires. The sum column of a two-bit addition reads 0, 1, 1, 0 down the input rows — that is XOR's table. The carry column reads 0, 0, 0, 1 — that is AND's table. So one XOR gate and one AND gate *are* a two-bit adder. Everything in this lesson — full adders, word-wide adders, subtractors — is that discovery, chained and given a second job.

## Sub lesson 1 — Half adders and full adders

The **half adder** is the smallest arithmetic circuit: two inputs, A and B (one bit each); two outputs, **Sum** and **Carry**. Its truth table is binary addition itself — 0+0: sum 0, carry 0; 0+1: sum 1, carry 0; 1+0: sum 1, carry 0; 1+1: sum 0, carry 1. Reading the columns as gates: the Sum column is **A ⊕ B** (XOR), the Carry column is **A · B** (AND). Two gates, and two bits can be added. It is called *half* for an honest reason: a real column of a long addition has *three* things to add — the two bits and the carry arriving from the column before — and the half adder has no door for that third input.

The **full adder** adds all three: A, B and **Cin** (carry-in), producing Sum and **Cout** (carry-out). Its construction is a lesson in building from parts: take two half adders and an OR gate. The first half adder adds A + B. The second half adder adds that result to Cin, giving the final Sum. Each half adder produces its own carry; the OR of those two carries is Cout — at most one of them can be 1 in a way that matters, so OR joins them safely.

[Picture — a full adder drawn openly: two half-adder boxes, the first fed by A and B, the second adding Cin, an OR gate gathering the two carries into Cout]

Now chain them: one full adder per bit of the word, each stage's Cout wired into the next stage's Cin, the first stage's Cin set to 0. Four full adders add two 4-bit words; eight add bytes; the carry *ripples* down the chain — the same word 'ripple' as the series counter, and the same small delay price. This **parallel adder** is the arithmetic heart the previous lesson promised: present two words, and the sum stands on the outputs faster than the eye can follow a single carry.

## Sub lesson 2 — Subtractors — and one circuit that does both

Subtraction can be wired the direct way first, to see its shape: a **half subtractor** takes A − B for single bits and gives a **Difference** (again A ⊕ B — the same XOR) and a **Borrow**, which is 1 exactly when A = 0 and B = 1: the column had to borrow from its neighbour. A **full subtractor** adds the incoming borrow as a third input. These circuits work — but the arithmetic lesson already taught a cheaper truth: with two's complement, **A − B = A + (complement of B) + ... exactly the +1 included**, and addition hardware is already built. Why build a second machine?

So the practical arithmetic unit is one **adder/subtractor**, steered by a single control line named SUB. The B input does not go straight to the adders: each bit of B passes through an **XOR gate whose other input is SUB**. Remember XOR's two faces: X ⊕ 0 = X (pass unchanged) and X ⊕ 1 = X̄ (invert). So with SUB = 0, B flows in as itself, and the chain's first Cin is wired to SUB — 0 — and the unit **adds**: A + B. Flip SUB = 1: every XOR now inverts its bit of B, giving the ones' complement, and Cin = 1 delivers the missing +1 that turns it into two's complement — so the unit **subtracts**: A + (two's complement of B), discarding the final carry exactly as the pencil method did.

[Picture — a 4-bit adder/subtractor: two registers feeding a chain of full adders, the B line passing through four XOR gates all steered by one SUB line, which also feeds the first carry-in]

One control bit chooses the operation; one set of gates does both jobs. This is the arithmetic circuit inside every processor's ALU, and it is nothing but the lessons of this climb stacked: complements from arithmetic, XOR from gates, chains from registers' patience with wiring.

## Say it to your companion

Tell your companion, in your own words: a half adder adds two bits with XOR for the sum and AND for the carry; a full adder adds a carry-in too and is built from two half adders and an OR; chained full adders add whole words; and a subtractor needs no new machine — XOR gates steered by one SUB line invert B while Cin adds the two's-complement 1, so one circuit adds and subtracts. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: write the half adder's truth table and give Sum = A ⊕ B, Carry = A · B. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: explain why the half adder is only 'half', and build the full adder from two half adders and an OR gate. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: trace a word addition through a chain of full adders, carry-out to carry-in. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: explain how XOR gates steered by SUB, plus Cin = SUB, turn the same adder into a subtractor using two's complement. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
