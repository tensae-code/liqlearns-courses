# Training and Optimising an AI System

## Do it first

From an idea to a working AI system there is a road, and the book walks it in order: the system must be fed, trained, measured honestly, and improved — the same honest cycle whether the system sorts fruit or reads scans. The heart of the road is a discipline every examination candidate knows: never judge the learner only on the questions it practised. Keep that thought; the whole lesson hangs on it.

## Sub lesson 1 — From idea to trained system — data, split, train

The road has a fixed order. **First, the task is framed** exactly: not 'understand fruit' but 'given a photograph, answer apple or banana.' **Second, data is gathered and prepared**: many examples, each with its correct answer (**label**) attached — checked, cleaned, and made consistent, because a system trained on mislabelled examples learns the mislabelling with the same loyalty.

**Third — the discipline step — the data is split.** Most of it becomes **training data**, which the learning procedure may study freely. A smaller part is locked away as **test data**: examples the system will never train on, saved for the final honest measurement. **Fourth, a model shape is chosen** (a decision tree, a nearest-neighbour rule, a neural network — the next lessons open the last of these). **Fifth, training**: the procedure shows the system the training examples again and again; after each pass it measures the **error** — how often, and by how much, the system is wrong — and adjusts the system's insides a step in the direction that lowers that error. Training is that loop, run until the error stops falling.

[Picture — training-loop: a circular arrow — examples in, answers compared, error measured, insides adjusted — around a small model]

## Sub lesson 2 — Optimising — and the trap called overfitting

Now the locked drawer opens. The trained system is run on the **test data** it has never seen, and its score there — the share of right answers — is the honest measure of the system. Not a courtesy score: the whole point of the split was a measurement that cannot be flattered by practice.

The trap it exposes has a name every builder in this field knows: **overfitting**. A flexible enough system, trained long enough, stops learning the pattern and starts **memorising the examples** — quirks, noise and all. Its training score climbs to perfection while its test score sags: it has become the candidate who can recite last year's paper and cannot answer a fresh question on the same topic. (The opposite failure, a model too simple to catch the pattern at all, is **underfitting**.) Overfitting is why 'it scored 100%' is a suspicious sentence until you ask: on which data?

[Picture — overfitting-curve: two lines over training time — training error falling steadily, test error falling, then rising — with the sweet spot marked]

**Optimising** is the builder's response: adjust the choices *around* the training — the **hyperparameters** the learning procedure itself does not set: how much data to feed, how complex a model to allow, how long to train, how big each adjustment step is. Try a setting, retrain, and judge **only by the test score**; keep the setting that generalises best, not the one that memorises fastest. From idea to system, then, is a loop of its own: build, measure honestly, tune, measure again — and the test data stays locked between measurements, or the honesty is spent.

## Say it to your companion

Tell your companion, in your own words: an AI system is built in stages — frame the task, gather labelled data, split off unseen test data, train by shrinking the error, and judge only on the test data; overfitting is memorising the practice set, and optimising tunes the settings around training against the honest score. Use the exam candidate story as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: walk an AI project through its stages — data, split, train, test — in order. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: say what overfitting is, and how unseen test data exposes it. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: name two optimising choices a builder tunes, and say what 'better' is judged by. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
