# Showing Bangla on a Web Page — Charset and Language

## Do it first

Write a web page in Bangla, open it, and the letters arrive as boxes and question marks — the text was fine; the browser guessed its code wrongly. One line in the page's head ends the guessing forever. For a Bangladeshi learner this is not a foreign example: it is the line that puts their own language on the web.

## Sub lesson 1 — Meta charset — declare UTF-8

Characters travel as numbers (the character-codes lesson), and the browser must be told which code table the numbers use. The declaration lives in the head: **<meta charset="utf-8">** — 'this page is encoded in UTF-8', the Unicode form that holds Bangla and every other script. With it, the page's bytes are read as meant; without it, the browser guesses, and guesses fail exactly on the scripts that need the declaration most. The charset line goes first in the head, before anything it must protect.

In your mind's eye: meta charset — declare UTF-8.

[Picture 46028 — meta charset — declare UTF-8]

## Sub lesson 2 — The lang attribute — name the language

The page's other declaration names its **language**: the **lang attribute** on the html element — `<html lang="bn">` for a Bangla page. Lang does quiet, essential work: screen readers pronounce by it, search engines file the page under its language, browsers offer translation and choose fonts and hyphenation by it. Together the two declarations are the page's passport: charset says how its letters are coded, lang says what language they speak — and a page that carries both can travel the whole web and be read as written, in Dhaka or anywhere.

In your mind's eye: the lang attribute. Name the language.

[Picture 46029 — the lang attribute. Name the language]

## Say it to your companion

Tell your companion, in your own words: Characters travel as numbers (the character-codes lesson), and the browser must be told which code table the numbers use. The declaration lives in the head: **<meta charset="utf-8">** — 'this page is encoded in UTF-8', the Unicode form that holds Bangla and every other script. With it, the page's bytes are read as meant; without it, the browser guesses, and guesses fail exactly on the scripts that need the declaration most. The charset line goes first in the head, before anything it must protect. The page's other declaration names its **language**: the **lang attribute** on the html element — `<html lang="bn">` for a Bangla page. Lang does quiet, essential work: screen readers pronounce by it, search engines file the page under its language, browsers offer translation and choose fonts and hyphenation by it. Together the two declarations are the page's passport: charset says how its letters are coded, lang says what language they speak — and a page that carries both can travel the whole web and be read as written, in Dhaka or anywhere. Then let your companion ask you one question about it — and answer from the lesson, not from memory of the book's exact words.

## Do It Yourself

1. Show it, don't just say it: The character encoding the page uses. Do this with a real example of your own and write or say how you know it is right.
2. Show it, don't just say it: <meta charset="utf-8">. Do this with a real example of your own and write or say how you know it is right.
3. Show it, don't just say it: First in the head. Do this with a real example of your own and write or say how you know it is right.
4. Show it, don't just say it: The browser guesses the code — and Bangla arrives as boxes. Do this with a real example of your own and write or say how you know it is right.
