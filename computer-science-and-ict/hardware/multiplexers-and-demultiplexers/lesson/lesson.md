# Multiplexers and Demultiplexers

## Do it first

Think of four security cameras and one guard's screen, joined by a single cable laid across a building. The cable can carry one camera's picture at a time — so a chooser at the camera end keeps selecting which camera is connected, switching so fast that the screen seems to show all four. At the other end of a line, the opposite need appears: one stream of data arrives, and it must be delivered to one of several destinations — this one now, that one next. The circuit that chooses among many inputs is the multiplexer; the circuit that delivers to one of many outputs is the demultiplexer. Together they are how one wire does the work of many.

## Sub lesson 1 — The multiplexer — many inputs, one chosen

A **multiplexer**, short name **MUX**, is a selector: many data inputs, **one** output, and a set of **select lines** that say which input is connected. It behaves like a rotary switch with a digital hand: the binary number on the select lines is the position of the switch.

The book's example is the **4-to-1 multiplexer**: data inputs D0, D1, D2, D3, two select lines S1 and S0, and one output Y. Select code 00 connects D0 to Y. Code 01 connects D1. Code 10 connects D2. Code 11 connects D3. Whatever the chosen input is doing, the output copies it; the other three inputs may do as they please — they are not connected. Count the pattern: **2ⁿ data inputs need n select lines** — 4 inputs need 2, 8 inputs need 3, 16 need 4.

[Picture — the 4-to-1 multiplexer drawn as a rotary switch whose hand is turned by the two select lines, and beside it as a block with D0–D3 entering, Y leaving, and S1 S0 entering from below]

Inside, the decoder's trick returns: one AND gate per data input, enabled by exactly one select pattern (the inverters arrange that). D2's gate opens only for S1S0 = 10, passing D2 through; all four AND outputs feed one OR gate, and since only one AND is ever open, the OR simply delivers the chosen input. That is the whole circuit: selection = AND gates watching select patterns, delivery = OR.

A MUX has a second trick worth knowing. Hold its select lines as variables and wire its data inputs to fixed 0s and 1s, and the output becomes a **switching function of the select lines** — any function of two variables from one 4-to-1 MUX, chosen by the pattern of fixed inputs. The selector doubles as a small programmable function box.

## Sub lesson 2 — The demultiplexer — one input, delivered to the chosen output

The **demultiplexer**, or **DEMUX**, is the multiplexer seen from the other end of the wire: **one** data input, many outputs, and select lines whose code chooses **which output receives the data**. A 1-to-4 DEMUX with select code 10 sends its input to output 2; outputs 0, 1 and 3 stay at 0, whatever the input does. The selected output copies the input; the rest are silent.

Inside, it is the same AND-gate pattern you have now met three times: one AND gate per output, each enabled by one select pattern, each fed by the common data input. Only the selected gate is open, so only its output can follow the data. Notice what that makes the DEMUX: it is the **decoder** of the previous lesson with one small change — the decoder's fixed 'watch for the pattern' input replaced by the data itself. A decoder with an enable input *is* a demultiplexer; the two names meet in one circuit.

[Picture — a MUX and a DEMUX facing each other across one long line: four senders at the left, the MUX choosing one, the line, the DEMUX delivering to the matching receiver at the right, both select dials showing the same code]

Now put the pair to work, because together they earn their names. Four senders must talk to four receivers over **one** line. At the sending end a MUX selects sender 2; the data crosses the single line; at the far end a DEMUX with the *same* select code delivers it to receiver 2. Change both select codes together and sender 3 talks to receiver 3. The line is shared by turns — **multiplexing** — and because electronic turns can change millions of times a second, many conversations ride one wire as if each had its own. That sharing, born in these two small circuits, is the idea under every cable that carries many channels at once.

## Say it to your companion

Tell your companion, in your own words: a multiplexer is a digitally controlled switch — the binary code on its select lines connects one of its many inputs to its single output; a demultiplexer delivers one input to the one output its select code names; 2ⁿ lines need n select lines; and a MUX and DEMUX kept in step let many senders and receivers share one wire. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: say what a multiplexer does and work a 4-to-1 MUX for any select code. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
2. Show it, don't just say it: state the select-line rule: 2ⁿ data inputs need n select lines. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
3. Show it, don't just say it: explain the multiplexer's insides — one AND gate per input opened by its select pattern, all feeding one OR gate. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
4. Show it, don't just say it: say what a demultiplexer does, how it relates to a decoder with an enable, and how a MUX–DEMUX pair shares one line between many senders and receivers. Do this with a real example of your own — on paper, or built in a circuit simulator such as TINA or Circuit Wizard — and write or say how you know it is right.
