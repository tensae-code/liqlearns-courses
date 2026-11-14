# Training a Decision Tree Algorithm

## Do it first

Of all machine-learning algorithms, the decision tree is the one you can watch think. This lesson grows one from data, question by question.

## Sub lesson 1 — How a tree is trained

**Training** a decision tree means choosing its questions. The algorithm tries candidate **splits** — a question about one feature ('mark ≥ 60?') — and keeps the split that **separates the kinds best**: the purest groups, the least mixed. It repeats the choosing down each branch until the leaves are pure enough or the data runs out. The tree that results is the training data, reorganised into an asking order — which is why a tree can always show its reasons: every decision is a path of named questions.

[Picture — How a tree is trained]

## Sub lesson 2 — Using and judging the tree

To **use** the tree, a new case walks from the root, answering each question, until it lands in a leaf — the leaf's majority kind is the prediction. Judging a tree watches its two faults: **overgrown** trees (memorising noise — overfitting, cured by pruning or limiting depth) and **stumps** (too simple to catch the pattern). Jordan trains trees inside the ML unit because they make the whole idea of training visible: data in, questions chosen, a decider out.

[Picture — Using and judging the tree]

## Say it to your companion

Tell your companion, in your own words: **Training** a decision tree means choosing its questions. The algorithm tries candidate **splits** — a question about one feature ('mark ≥ 60?') — and keeps the split that **separates the kinds best**: the purest groups, the least mixed. It repeats the choosing down each branch until the leaves are pure enough or the data runs out. The tree that results is the training data, reorganised into an asking order — which is why a tree can always show its reasons: every decision is a path of named questions. To **use** the tree, a new case walks from the root, answering each question, until it lands in a leaf — the leaf's majority kind is the prediction. Judging a tree watches its two faults: **overgrown** trees (memorising noise — overfitting, cured by pruning or limiting depth) and **stumps** (too simple to catch the pattern). Jordan trains trees inside the ML unit because they make the whole idea of training visible: data in, questions chosen, a decider out. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Its questions — the splits. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: The one that separates the kinds best — purest groups. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: When leaves are pure enough or the data runs out. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The training data reorganised into an asking order. Do this with a real example of your own and write or say how you know it is right.
