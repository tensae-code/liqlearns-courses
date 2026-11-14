# The Artificial Neuron

## Do it first

Modern AI's most famous machine, the neural network, is built from one small unit repeated enormously. This lesson takes that unit alone — the artificial neuron, the book's 'building block of the neural network' — and computes with it by hand. Everything in it is arithmetic you already own: multiply, add, compare. The intelligence of the larger machine comes from how many of these there are and how their weights are set, and both of those are the next lesson; this one makes a single neuron completely clear.

## Sub lesson 1 — Inside one neuron — inputs, weights, sum

An **artificial neuron** receives its information as numbers: the **inputs** x₁, x₂, … — pixels of an image, measurements of a fruit, answers to questions, each boiled down to a number. On every incoming line sits a **weight** w: how much that input counts. A big positive weight means 'this input speaks strongly for firing'; a negative weight means 'this input speaks against'; a weight near zero means the neuron has learned to ignore that line.

The neuron's arithmetic is one line. It multiplies each input by its weight, adds them all, and adds one more number — the **bias** b, the neuron's own built-in tendency, a thumb resting on the scale before any evidence arrives. The result is the **net input** z:

**z = w₁·x₁ + w₂·x₂ + … + wₙ·xₙ + b**

[Picture — artificial-neuron-anatomy: three input lines with weight labels running into one circle, the weighted sum forming inside, bias entering from above]

Work it. A neuron judges 'go out without a jacket?' from two inputs: sunshine x₁ = 1 (yes) and wind x₂ = 0.6. Its weights: sunshine speaks for going out, w₁ = 2; wind speaks against, w₂ = −3; its bias b = 0.5. Then z = 2·1 + (−3)·0.6 + 0.5 = 2 − 1.8 + 0.5 = **0.7**. The sum is the neuron's weighed-up opinion — but an opinion is not yet a decision. That takes one more part.

## Sub lesson 2 — From sum to output — activation, and what learning adjusts

The **activation function** turns the net input z into the neuron's **output** — its answer to the next layer, or to the world. The simplest activation is the **step**: if z reaches a threshold (say 0), output **1** — the neuron 'fires'; below it, output **0**. Our jacket neuron's z = 0.7 ≥ 0, so it fires: go out. Change only the wind to x₂ = 1 and z = 2 − 3 + 0.5 = −0.5: no fire — stay in. The same neuron, the same weights, a different world, a different answer. (Smoother activations exist — functions that output a graded number between 0 and 1 instead of a hard step — and real networks prefer them because small weight changes then change the output a little, which makes learning steadier; the step is the honest first form.)

[Picture — activation-step: a graph of the step function — flat at 0, jumping to 1 at the threshold — with the two worked z values marked on it]

Now the sentence that connects this lesson to the whole strand: **learning is the adjusting of the weights and the bias.** The inputs are the world's; the activation is fixed by design; what training (last lesson's loop) tunes, example after example, is exactly the w's and the b — nudging each weight in the direction that would have made the last answer less wrong. A neuron with well-set weights is a small expert on one tiny judgement. A network, next, is what happens when small experts are wired so their answers become each other's inputs.

## Say it to your companion

Tell your companion, in your own words: an artificial neuron multiplies each input by a weight, adds them and a bias into a net input, and passes it through an activation function to produce its output; learning means adjusting the weights and the bias. Compute one neuron aloud together as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: compute a neuron's output from given inputs, weights, bias and a simple activation rule. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: say what a weight means — how much an input counts — in one sentence. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: say what training changes inside a neuron, and what it never changes. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
