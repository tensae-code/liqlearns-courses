# Responsive Design and Flexbox

## Do it first

Picture a page with a menu on the left, three boxes of news across the middle, and a photo on the right — beautiful on a wide monitor. Now squeeze the same page into a narrow phone screen without changing anything: the boxes crush into each other, the text runs off the edge, the photo swallows the screen. Write down two things that break. The lesson gives you the two tools professionals use so this never happens: a layout system whose boxes flex by themselves, and CSS rules that switch the layout when the screen is narrow.

## Sub lesson 1 — Flexbox — laying out with flexible boxes

Fixed layouts break because screens are not fixed. **Flexbox** is CSS's answer: instead of placing every box at an exact position, you declare a **flex container** and let its children arrange themselves. The children line up along a **main axis** — a row across, or a column down — and Flexbox shares the available space among them: a box can be told to grow to fill what is free, or to shrink when space runs out, in the proportions you set. Across the other axis they can be aligned to the start, the centre or the end, or stretched to the same height. And with wrapping allowed, boxes that no longer fit side by side simply flow onto the next line, like words in a paragraph. The three crushed news boxes from Do it first, placed in a flex row with wrapping, arrange themselves — two across, then one — with no new code.

In your mind's eye: three boxes in a flex row on a wide screen, then the same three boxes wrapped onto two lines on a narrow screen.

## Sub lesson 2 — Media queries — one page, many screens

Flexbox adapts a layout continuously; sometimes a design must change in a step. That is the job of a **media query**: a block of CSS that applies only when a condition about the screen is true — most often its width. You write the wide-screen layout as the normal rules, then add `@media (max-width: 600px) { … }` containing the narrow-screen rules: the menu becomes a single column, the three boxes stack, the photo takes the full width. The width where the design switches is called the **breakpoint**. One HTML file, one CSS file, two layouts — the page itself asks the screen how wide it is and dresses accordingly. That is **responsive design**: not a separate mobile site, but one page that responds.

In your mind's eye: the same page drawn twice, wide and narrow, with the media query that switches between them written underneath.

## Say it to your companion

Tell your companion, in your own words: Flexbox lets boxes stretch, shrink and wrap by themselves along an axis, and a media query applies different CSS when the screen is narrower than a breakpoint — together they make one page fit every screen. Sketch the three-box page both ways as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: turn a container into a flex container and make its boxes share the space in a row. Do this with a real example of your own — in a real page you write in an editor and open in a browser — and write or say how you know it is right.
2. Show it, don't just say it: make flex boxes wrap onto new lines when the screen narrows. Do this with a real example of your own — in a real page you write in an editor and open in a browser — and write or say how you know it is right.
3. Show it, don't just say it: write a media query with a breakpoint that changes the layout for narrow screens. Do this with a real example of your own — in a real page you write in an editor and open in a browser — and write or say how you know it is right.
4. Show it, don't just say it: explain why one responsive page is better than a separate mobile site. Do this with a real example of your own — in a real page you write in an editor and open in a browser — and write or say how you know it is right.
