# CSS Selector Priority — Which Rule Wins

## Do it first

CSS selector priority — when several rules style the same element, a fixed order decides which one wins: inline styles, then id, class and element selectors, and the cascade's last word (Vietnam Grade 12)

## Sub lesson 1 — When rules fight — the priority ladder

A page often gives one element **several rules at once**: the element selector says paragraphs are black, a class says this paragraph is blue, an id says it is red. CSS settles the fight by **priority (specificity)**: an **inline style** (written in the element's style attribute) beats all; below it the **id** selector beats the **class** selector, and the class beats the **element** selector. Vietnam's Grade 12 book closes its CSS strand with this ladder, because until a learner can predict the winner, styling is guessing.

In your mind's eye: when rules fight — the priority ladder.

## Sub lesson 2 — Equal priority — the cascade's last word, and working with the ladder

When two rules have **equal priority**, the **later rule in the stylesheet wins** — the cascade reads top to bottom and the last word stands. The working habits follow: style generally first (elements), then classes for groups, ids sparingly for the one special element, and inline styles almost never — because a style that cannot be overridden becomes a trap when the design changes. Debugging a wrong colour is now a method: find every rule that touches the element, and climb the ladder.

In your mind's eye: equal priority — the cascade's last word, and working with the ladder.

## Say it to your companion

Tell your companion, in your own words: A page often gives one element **several rules at once**: the element selector says paragraphs are black, a class says this paragraph is blue, an id says it is red. CSS settles the fight by **priority (specificity)**: an **inline style** (written in the element's style attribute) beats all; below it the **id** selector beats the **class** selector, and the class beats the **element** selector. Vietnam's Grade 12 book closes its CSS strand with this ladder, because until a learner can predict the winner, styling is guessing. When two rules have **equal priority**, the **later rule in the stylesheet wins** — the cascade reads top to bottom and the last word stands. The working habits follow: style generally first (elements), then classes for groups, ids sparingly for the one special element, and inline styles almost never — because a style that cannot be overridden becomes a trap when the design changes. Debugging a wrong colour is now a method: find every rule that touches the element, and climb the ladder. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: Priority — specificity: the more specific selector wins Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: An inline style, written in the element's style attribute Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: Id highest, then class, then element Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The class rule — blue Do this with a real example of your own and write or say how you know it is right.
