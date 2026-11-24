# The CSS Box Model

## Do it first

the CSS box model — every element is a box of content wrapped in padding, a border and a margin, and its true size is the sum of the layers (Vietnam Grade 12)

## Sub lesson 1 — Four layers — content, padding, border, margin

CSS treats **every element as a box** of four layers. At the centre, the **content** — the text or image, sized by width and height. Around it, **padding** — clear space inside the box, between content and edge. Around that, the **border** — the box's visible line, with its width, style and colour. Outside everything, the **margin** — clear space between this box and its neighbours. Vietnam's Grade 12 book teaches the model as a picture first, because every layout surprise later is one of these layers being forgotten.

In your mind's eye: four layers — content, padding, border, margin.

## Sub lesson 2 — True size — the sum of the layers

The model's hard lesson is arithmetic: an element's **true width** is width + left and right padding + left and right border + left and right margin. Two boxes that 'should' fit side by side overflow when their paddings and borders are forgotten. The working habits: set padding and border **deliberately**, expect margins between neighbours to sit **between** the boxes (adjoining vertical margins even collapse into one), and when a layout breaks, **draw the boxes** — the picture finds the forgotten layer.

In your mind's eye: true size — the sum of the layers.

## Say it to your companion

Tell your companion, in your own words: CSS treats **every element as a box** of four layers. At the centre, the **content** — the text or image, sized by width and height. Around it, **padding** — clear space inside the box, between content and edge. Around that, the **border** — the box's visible line, with its width, style and colour. Outside everything, the **margin** — clear space between this box and its neighbours. Vietnam's Grade 12 book teaches the model as a picture first, because every layout surprise later is one of these layers being forgotten. The model's hard lesson is arithmetic: an element's **true width** is width + left and right padding + left and right border + left and right margin. Two boxes that 'should' fit side by side overflow when their paddings and borders are forgotten. The working habits: set padding and border **deliberately**, expect margins between neighbours to sit **between** the boxes (adjoining vertical margins even collapse into one), and when a layout breaks, **draw the boxes** — the picture finds the forgotten layer. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Content, padding, border, margin Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: Inside the box — clear space between the content and the edge Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Its width, its style and its colour Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: Outside the box — clear space between this box and its neighbours Do this with a real example of your own and write or say how you know it is right.
