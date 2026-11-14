# Video script — The CSS Box Model

The super-simple voice, for the video that rides on top of the lesson (lesson-plan.md, add-on list). Made later, when videos are made; the script is the slot's written form until then.

---

CSS treats **every element as a box** of four layers. At the centre, the **content** — the text or image, sized by width and height. Around it, **padding** — clear space inside the box, between content and edge. Around that, the **border** — the box's visible line, with its width, style and colour. Outside everything, the **margin** — clear space between this box and its neighbours. Vietnam's Grade 12 book teaches the model as a picture first, because every layout surprise later is one of these layers being forgotten.
The model's hard lesson is arithmetic: an element's **true width** is width + left and right padding + left and right border + left and right margin. Two boxes that 'should' fit side by side overflow when their paddings and borders are forgotten. The working habits: set padding and border **deliberately**, expect margins between neighbours to sit **between** the boxes (adjoining vertical margins even collapse into one), and when a layout breaks, **draw the boxes** — the picture finds the forgotten layer.
