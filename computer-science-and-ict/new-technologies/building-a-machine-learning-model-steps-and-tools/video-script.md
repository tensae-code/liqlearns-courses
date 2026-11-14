# Video script — Building a Machine Learning Model — Steps and Tools

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

Building needs its **requirements** first: a **problem stated as a prediction**, **data** enough and honest, **computing** to train on, and a way to **judge success** before starting. The steps then run: **collect and prepare the data** (clean it, split it into training and test parts), **choose the algorithm** family that fits, and **train** — let the algorithm find its pattern in the training part. Preparation eats most of the time; Jordan says so plainly, because pupils who expect magic skip it and build on sand.
The trained model meets the **test data** it never saw: its score there — not on the training data — is the honest one. Then **tuning**: adjust, retrain, retest, watching for **overfitting** (a model that memorised its training data and fails strangers). The **tools** are the environments where this is done — Python with its libraries (the course's own road), or visual tools that build models by dragging. The steps do not change with the tool; that is why the book teaches steps first.
