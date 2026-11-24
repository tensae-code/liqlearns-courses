# PageRank — How Search Engines Rank Pages

## Do it first

Four pages: A links to B and C. B links to C. C links to A. D links to C, and nobody links to D. In your notebook, draw the four pages as circles and the links as arrows. Now guess: which page would a search engine call the most important, and which the least? Is it simply the page with the most arrows arriving? Keep your drawing — the lesson gives you the rule, a way to compute the answer by hand, and a surprise about page D.

## Sub lesson 1 — The link graph and the score a page passes on

Draw the Web the way a search engine sees it: every page is a point, every link is an arrow. That drawing is a **graph**, and it holds the secret of ranking. When page X links to page Y, X is voting for Y: "this page is worth visiting." So a page with many incoming links collects many votes.

But two refinements make the idea work. First, a page **shares out** what it passes on: if X links to three pages, each of them receives a third of X's vote — a page that links to everything recommends nothing strongly. Second, votes are **weighted**: a link from an important page carries more than a link from a page nobody reads. That sounds circular — importance defined by importance — and it is: the circle is closed by computing all the scores together, which is the next part. In the drawing from Do it first, C receives from A, B and D — but A's vote is split between B and C, and D's vote, as we shall see, is worth very little, because nobody votes for D.

In your mind's eye: four pages as circles with arrows for links, the arrows thick or thin according to the share of importance they carry.

## Sub lesson 2 — The random surfer and working PageRank out by iteration

Google's founders closed the circle with a story: the **random surfer**. Imagine a person who starts on a random page and clicks links at random, never stopping; from time to time, bored, they jump to any page at all. Some pages the surfer visits again and again; others almost never. **PageRank is that share of visits.** A page is important exactly when the random walk keeps coming back to it.

To compute it, work in rounds. Give every page an equal starting score. In each round, every page hands its score out along its outgoing links, split evenly, and collects what the others hand to it — that collection is its new score. Round by round the numbers move, then settle: when a round changes nothing, you have the PageRank values. France's book has you run these rounds in a spreadsheet and watch them settle in a simulator, and the 2010 "reasonable surfer" refinement weights links by how likely a real reader is to click them — a link in the main text counts more than one buried in a footer.

In your mind's eye: a table of four pages whose scores change over five rounds and then stay still, the settled column highlighted.

## Say it to your companion

Tell your companion, in your own words: pages are ranked by the links pointing to them; each page splits what it passes among its outgoing links; a link from an important page counts more; and PageRank is the share of time a random surfer spends on the page. Run one round of scores on your four-page drawing as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: draw a small set of pages as a link graph and say which page each link votes for. Do this with a real example of your own — on paper, or in a spreadsheet if one is available — and write or say how you know it is right.
2. Show it, don't just say it: explain why a page splits what it passes on among all its outgoing links. Do this with a real example of your own — on paper, or in a spreadsheet if one is available — and write or say how you know it is right.
3. Show it, don't just say it: run two or three PageRank rounds on a small graph and say when the scores have settled. Do this with a real example of your own — on paper, or in a spreadsheet if one is available — and write or say how you know it is right.
4. Show it, don't just say it: explain the random surfer model and what a page's PageRank number means. Do this with a real example of your own — on paper, or in a spreadsheet if one is available — and write or say how you know it is right.
