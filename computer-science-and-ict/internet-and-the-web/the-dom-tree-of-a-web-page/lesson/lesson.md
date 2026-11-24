# The DOM — the Tree of a Web Page

## Do it first

Here is a small piece of a page: a `div` holding a heading `h1` with the words "My school", and a paragraph `p` holding the words "Welcome" and a link `a` with the words "Enter". On paper, draw this as a family tree: what contains what? Put the container at the top and everything it holds beneath it, and the words themselves at the very ends. Keep the drawing — the lesson shows you that the browser builds exactly this tree for every page, gives it a name, and lets programs climb all over it.

## Sub lesson 1 — The page as a tree of nodes

An HTML file is a text. But the browser does not keep it as a text: as it loads the page, it builds a structure called the **DOM — the Document Object Model**. At the top sits the **document** node, the whole page. Under it, every element becomes a **node**: the `html` element, then `head` and `body`, then everything they contain, in the exact nesting of your tags. The words inside an element are nodes too — **text nodes**, the leaves at the ends of the branches.

Because it is a tree, the DOM speaks the language of families: a node has one **parent** (the element directly containing it), may have **children** (what it directly contains), and shares its parent with its **siblings**. Your drawing from Do it first is a DOM: the `div` is the parent of `h1` and `p`; `h1` and `p` are siblings; the link `a` is a child of `p`; "Enter" is a text node, child of `a`. Nothing in the tree is decoration: it is the page, in the form a program can work with.

In your mind's eye: a small HTML fragment on the left and its DOM tree on the right, arrows joining each tag to its node.

## Sub lesson 2 — Using the DOM — finding and changing nodes

Why build a tree at all? Because a tree can be **walked and changed**. When JavaScript runs on a page — the subject of the JavaScript lesson — it does not edit the HTML file; it works on the DOM. It can search the tree for one node, most simply by the `id` you gave the element; read what the node contains; and change it: new text, a new attribute, a different style. The browser redraws from the changed tree instantly, so the reader sees the page itself change — a message appears, an error shows under a form field, a menu opens. Every interactive page you have ever used is, underneath, a program climbing this tree. Learn to draw the tree of a fragment and you can predict what a script will find; learn the family words — parent, child, sibling — and you can say precisely where it will land.

In your mind's eye: a script's hand pointing at one highlighted node in a page's tree while the same element glows on the rendered page beside it.

## Say it to your companion

Tell your companion, in your own words: the browser turns HTML into the DOM, a tree with the document at the root, elements as branches and text as leaves; scripts find nodes in the tree — often by id — and change them, and the page changes with them. Draw the tree of a three-element fragment as you say it. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: draw the DOM tree of a small HTML fragment, with element and text nodes in the right places. Do this with a real example of your own — on paper, or in a real page inspected with the browser's developer tools — and write or say how you know it is right.
2. Show it, don't just say it: use the words parent, child and sibling correctly about the nodes of a tree you drew. Do this with a real example of your own — on paper, or in a real page inspected with the browser's developer tools — and write or say how you know it is right.
3. Show it, don't just say it: explain why the browser builds the DOM instead of keeping the page as plain text. Do this with a real example of your own — on paper, or in a real page inspected with the browser's developer tools — and write or say how you know it is right.
4. Show it, don't just say it: say how a script finds one node by its id and what happens on screen when it changes that node. Do this with a real example of your own — on paper, or in a real page inspected with the browser's developer tools — and write or say how you know it is right.
