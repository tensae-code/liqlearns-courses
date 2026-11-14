# Neural Networks — Many Neurons Together

## Do it first

The last lesson's neuron was deliberately humble: one weighted sum, one small decision. Nothing humble, though, about what the book builds from it here — 'together, neurons are strong'. Stacked in layers and trained together, artificial neurons recognise faces in photographs and words in sound: the systems behind most of the AI in this strand's headlines. This lesson follows one input through a whole network, slowly, so the strength stops being a slogan and becomes a mechanism you can trace.

## Sub lesson 1 — Layers — how a network is wired

A **neural network** is neurons arranged in **layers**, each layer's outputs feeding the next layer's inputs. The **input layer** takes the world in as numbers — for a small black-and-white image of a handwritten digit, one input per pixel: how dark is this spot? The **output layer** gives the answer: for the digit recogniser, ten neurons, one per digit 0–9, and the answer is whichever output neuron fires strongest. Between them sit the **hidden layers** — hidden because the world neither feeds them directly nor reads them directly; they are the machine's inner workshop.

Trace one forward pass. The photograph's pixel numbers enter at the left. Every neuron in the first hidden layer computes its weighted sum over **all** the pixel values and fires or not, by its own weights. Their firing pattern becomes the input of the next layer, whose neurons weigh **those** numbers, and so on, layer by layer, until the output layer's pattern appears: perhaps the '7' neuron at 0.92, '1' at 0.31, the rest near zero. The system's answer is 7 — with its confidence written in the numbers.

[Picture — network-layers: a three-layer network drawn fully connected, with one photograph's journey highlighted from pixels to the winning output neuron]

Count the knowledge: every connecting line carries a **weight**, so even a modest network holds thousands to millions of weights — and the whole set of them, together, is what the system knows.

## Sub lesson 2 — What the layers learn — features upon features, and image recognition

Nobody assigns the hidden neurons their jobs. **Training** — the loop from two lessons ago, now applied to every weight in every layer — discovers a division of labour on its own, and in image networks it is always recognisably the same shape. Neurons in the **first** hidden layer become detectors of the simplest features: an edge slanting this way, a short stroke, a dark patch. Neurons in **later** layers, fed by those, combine features into parts: a loop, a corner, a crossing. The output layer combines parts into **wholes**: this arrangement of loop-and-stroke is a 9; that one is a 4. **Features upon features** — that stacking is what 'deep' means in deep learning, and it is why the machine can do what no single neuron, and no hand-written rule list, could: the features themselves were learned from the examples, at every level.

[Picture — network-features: three panels — pixels, then edge detectors lighting up, then part detectors, then whole digits — for one handwritten 9]

The costs keep the earlier lessons' honesty. A network's millions of weights are millions of dials that only data can set, so image networks are trained on **millions of labelled photographs**; the computation is heavy enough to need specialised hardware; and when the trained system errs, its answer comes from the whole web of weights at once — no single rule to point at, the data-based weakness from §4.2 at full scale. Strong together, yes — and hungry, heavy and hard to interrogate, together. The strand's last lesson puts systems like this to work, and weighs what they change.

## Say it to your companion

Tell your companion, in your own words: a neural network wires neurons in layers — inputs in, hidden layers judging features upon features, outputs giving the answer — and training sets every weight in every layer against many examples. Trace one photo's journey through the layers as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: draw a small network's layers and trace one input's journey to an output. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
2. Show it, don't just say it: say, with the image-recognition example, what hidden layers contribute that one neuron cannot. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
3. Show it, don't just say it: say what training adjusts across a whole network, and why depth helps and costs. Do this with a real example of your own, on paper or on a device you have, and write or say how you know it is right.
