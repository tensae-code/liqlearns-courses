# Video script — Training a Decision Tree Algorithm

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

**Training** a decision tree means choosing its questions. The algorithm tries candidate **splits** — a question about one feature ('mark ≥ 60?') — and keeps the split that **separates the kinds best**: the purest groups, the least mixed. It repeats the choosing down each branch until the leaves are pure enough or the data runs out. The tree that results is the training data, reorganised into an asking order — which is why a tree can always show its reasons: every decision is a path of named questions.
To **use** the tree, a new case walks from the root, answering each question, until it lands in a leaf — the leaf's majority kind is the prediction. Judging a tree watches its two faults: **overgrown** trees (memorising noise — overfitting, cured by pruning or limiting depth) and **stumps** (too simple to catch the pattern). Jordan trains trees inside the ML unit because they make the whole idea of training visible: data in, questions chosen, a decider out.
