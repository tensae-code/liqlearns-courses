# Knowledge-Based and Data-Based AI

## Do it first

How do you put intelligence into a machine? The book's look behind the scenes (its §4.2) finds two honest answers, invented decades apart. Either you take what experts know and write it down as rules the machine applies — or you give the machine no knowledge at all, only data, and let it extract its own patterns. Modern AI headlines belong mostly to the second; the first still runs quietly in more places than you think. Knowing both is knowing what any given system can and cannot do.

## Sub lesson 1 — Knowledge-based AI — expertise written as rules

A **knowledge-based** system holds what it knows the way a careful expert holds it: as **facts** and **rules**. The rules are written **IF–THEN**: *IF the patient has a fever AND a stiff neck THEN meningitis is likely.* Hundreds or thousands of such rules, gathered by interviewing human experts, form the **knowledge base**. Beside it sits the **inference engine**, the part that works: given new facts about a case, it finds rules whose IF-parts match, fires them, adds their conclusions as new facts, and chains onward until it reaches an answer.

This shape has two proud strengths. It is **exact** within its rules, and it can **explain itself**: ask why it concluded meningitis, and it lists the rules it fired — a chain a human can inspect, trust or challenge. Medicine, fault-finding in machines, tax and law advice were its classic fields.

[Picture — knowledge-based-rules: a wall of IF–THEN rule cards and a small engine walking from card to card along a glowing chain]

Its weaknesses are the mirror image. Writing down an expert's knowledge is **slow and expensive** — experts know more than they can say, and every rule must be caught, checked and kept current. And the system is **blind outside its rules**: a case no rule covers gets no wisdom at all, only silence or a wrong match. It cannot learn from the case it just failed, either: tomorrow it fails it again, until a human writes a new rule.

## Sub lesson 2 — Data-based AI — patterns found, not written

A **data-based** system starts empty of rules. It is shown **examples** — thousands of photographs labelled 'cat' or 'no cat', thousands of sentences and their translations — and a **learning procedure** adjusts the system's insides, a little at a time, until its answers on the examples are mostly right. What it 'knows' at the end is not a shelf of rules anyone can read: it is a vast pattern of numbers tuned by the data, which is why this approach is also called **machine learning** — the neighbouring lesson opens it fully.

Its strengths answer the rule-book's weaknesses exactly. Nobody can write IF–THEN rules for 'this photograph shows a cat' — fur, pose, light and breed vary beyond listing — yet data-based systems do it well, because they never needed the rules written: they **found** the pattern. Speech, handwriting, translation and recommendation all yielded to data after resisting rules for decades.

[Picture — data-based-learning: a river of labelled example photographs flowing into a machine whose inner dials settle a little with each one]

Its weaknesses are the rule-book's strengths, lost. It is **hungry**: thousands to millions of good examples, or it learns nothing reliable. It is **silent about its reasons**: it answers, but cannot show a chain of rules a human can audit — the numbers inside are not an explanation. And it **inherits its data**: examples that are few, wrong or one-sided produce a system that is few, wrong or one-sided, confidently. Two ways of building intelligence, two opposite sets of virtues — the rest of this strand lives mostly in the data-based world, and now you know what that world costs and buys.

## Say it to your companion

Tell your companion, in your own words: knowledge-based AI holds experts' facts and IF–THEN rules and reasons over them — exact and explainable, but limited to what was written; data-based AI is given examples and finds its own patterns — powerful where rules cannot be written, but hungry and unable to explain itself. Pick one everyday system and argue which kind it is, as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: describe how a knowledge-based system stores and uses expertise, with the expert-system shape. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: describe how a data-based system learns its behaviour from examples instead. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: choose the right approach for a stated job, and give the reason. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
